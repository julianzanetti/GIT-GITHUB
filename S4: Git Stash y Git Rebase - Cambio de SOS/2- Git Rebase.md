# Rebase - Actualizando una rama.
## Ejemplo 1 para el uso del rebase.
![image](https://github.com/user-attachments/assets/e8b5031c-3069-474a-b7cd-146be9b058a5)

- Vemos que se creo una rama que nunca se unio a la master, mientras que la master siguio teniendo commits.

## Usamos el comando rebase.
```
git branch
git checkout rama-misiones-completadas
git rebase master
git lg
```
![image](https://github.com/user-attachments/assets/f56a67f2-b95e-4169-95df-f7182b6f47a4)

## Unimos los cambios a la master.
```
git checkout master
git merge rama-misiones-completadas
git lg
```
![image](https://github.com/user-attachments/assets/0322df0c-82b2-4320-a18e-f13289cd5de5)
