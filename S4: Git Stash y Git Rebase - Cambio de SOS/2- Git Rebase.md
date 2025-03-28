# Rebase - Actualizando una rama.
## Ejemplo 1 para el uso del rebase.
![image](https://github.com/user-attachments/assets/e8b5031c-3069-474a-b7cd-146be9b058a5)

- Vemos que se creo una rama que nunca se unio a la master, mientras que la master siguio teniendo commits.

### Usamos el comando rebase.
```
git branch
git checkout rama-misiones-completadas
git rebase master
git lg
```
![image](https://github.com/user-attachments/assets/f56a67f2-b95e-4169-95df-f7182b6f47a4)

### Unimos los cambios a la master.
```
git checkout master
git merge rama-misiones-completadas
git lg
```
![image](https://github.com/user-attachments/assets/0322df0c-82b2-4320-a18e-f13289cd5de5)

## Ejemplo 2 para el uso del rebase (squash).
![image](https://github.com/user-attachments/assets/e5a7fc37-587d-4c01-ab46-4e3db396d9eb)

- Realizamos una modificacion en los dos archivos, hicimos el commit y vemos que el anterior commit cumple la misma funcion que el nuestro (NO SON IGUALES)

### Usamos el comando rebase -i
```
git rebase -i HEAD~4
```
![image](https://github.com/user-attachments/assets/b929f5ba-1831-41d1-a3ff-fd7e101c0333)
![image](https://github.com/user-attachments/assets/da7a1977-e314-4047-8e04-62383e1ddd01)

- Vemos que se unificaron los dos commit y quedo guardada la ultima modificacion hecha.

## Ejemplo 3 para el uso del rebase (reword).
![image](https://github.com/user-attachments/assets/2628dbc2-8b41-47d8-96a3-f52c45ef0446)

- Supongamos que no nos gusta los nombres o comentarios de alguno de estos commits

### Usamos el comando rebase -i
```
git rebase -i HEAD~4
```
![image](https://github.com/user-attachments/assets/985893df-dae1-4186-80e0-3e9e8b1fa162)
![image](https://github.com/user-attachments/assets/fabf7f9b-bf95-4862-9d41-cf9e946a1d29)
![image](https://github.com/user-attachments/assets/be6907fd-23f7-4a2c-92c5-f0a7b677f620)

- Modificamos el comentario o nombre de los commits anteriores.
