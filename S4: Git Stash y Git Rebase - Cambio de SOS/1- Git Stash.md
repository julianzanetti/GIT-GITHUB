# Git Stash.
## Modificar uno de nuestros archivos.
![image](https://github.com/user-attachments/assets/7adccdbd-023b-4622-b489-b845f1b6a1b2)
![image](https://github.com/user-attachments/assets/4e76c531-a4b5-4698-a307-2fb35fa1fb0d)

## Agregarlo al stash.
```
git stash
```
![image](https://github.com/user-attachments/assets/1375f609-b403-4a05-bee8-9d59f0bf0eba)
![image](https://github.com/user-attachments/assets/56c2f77b-70bc-47a7-8a3f-b8865ddf985e)
![image](https://github.com/user-attachments/assets/9d4991cb-1b9f-4f6f-bb39-54d12e606fc2)

## Ver los stash que tengamos almacenados.
```
git stash list
```
![image](https://github.com/user-attachments/assets/7a00c922-b63b-4244-b0b4-ac881a1ea5fa)

## Modificar uno de nuestros archivos y realizamos el commit.
![image](https://github.com/user-attachments/assets/3a222486-d2bd-495d-9930-61caef9b0bb3)

## Unimos el ultimo stash que tengamos almacenado.
```
git stash pop
```
![image](https://github.com/user-attachments/assets/303bf71c-d2f3-475f-9293-8969f91f3e32)
![image](https://github.com/user-attachments/assets/29cb2611-d8d0-480f-a64f-f73612756998)
![image](https://github.com/user-attachments/assets/cf07cd7d-1ee4-49d4-8b15-65d66bbd0ad5)

## Eliminar todos los stash que tengamos.
```
git stash clear
```
![image](https://github.com/user-attachments/assets/31d8c859-54cf-4c24-aacf-a0937ed7c28b)

## Recuperar un stash especifico.
```
git stash apply [<stash>]
```
![image](https://github.com/user-attachments/assets/9684d2b2-7b87-42eb-83ba-b8e9d11cc461)
> [!NOTE]
> Como vemos si agregamos uno, este no se borra automaticamente.

## Borrar un stash especifico.
```
git stash drop [<stash>]
```
![image](https://github.com/user-attachments/assets/7cce5225-8702-49b7-9406-0d6383af3fc1)

## Guardar un stash con descripcion.
```
git stash save "Ejemplo de stash"
```
![image](https://github.com/user-attachments/assets/320b57bc-cbcd-4c34-90ce-205a61b59e7c)
