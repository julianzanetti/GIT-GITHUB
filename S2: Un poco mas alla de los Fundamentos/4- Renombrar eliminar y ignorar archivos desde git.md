# Renombrar un archivo desde git.
## Agregar un archivo a nuestro repositorio.
![image](https://github.com/user-attachments/assets/854533c4-4dc6-4fb9-b7f2-22ac7c55654e)

## Renombar este nuevo archivo.
```
git mv archivo1 archivo2
git commit -m
```
![image](https://github.com/user-attachments/assets/66b98a02-818e-4c6c-bdcd-ee8a5acf8c35)

## Elimnar este archivo.
```
git rm archivo1
git commit -m
```
![image](https://github.com/user-attachments/assets/50fec547-b5e7-494b-a5ba-ca2c0a1d0dc8)

## Ignorar archivos que no deseamos.
![image](https://github.com/user-attachments/assets/4c00412b-7260-4da7-88c1-8dbea72cf2b7)
![image](https://github.com/user-attachments/assets/515d052e-6568-476b-a55b-0b75b873c6ee)

```
touch .gitignore
git status
```
![image](https://github.com/user-attachments/assets/1af8181e-cf71-46cc-8d6a-376dbe809566)
![image](https://github.com/user-attachments/assets/aacb6d89-1325-4b4b-b370-5840a6e4b78a)

```
git add .
git commit -m ".gitignore agregado"
```
![image](https://github.com/user-attachments/assets/0c31f7bf-054f-46bc-b253-2a57c59d45f3)
