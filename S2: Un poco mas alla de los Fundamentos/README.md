# Tarea práctica - Fundamento de Git.
## Cree una carpeta llamada tarea01.
![image](https://github.com/user-attachments/assets/02e4cfb0-3d6e-44d1-a41d-a5a403e43d88)

## Dentro de esa carpeta, inicialice el proyecto de git.
```
git init
```
![image](https://github.com/user-attachments/assets/23eb6e92-44f7-4596-a6bc-3cc05d69ba7f)

## Dentro del repositorio cree un archivo llamado README.md, ingrese el siguiente contenido:
```
# Información
Este es el resultado de mi esfuerzo aprendiendo GIT
```
![image](https://github.com/user-attachments/assets/18654fc1-f88f-42fb-827d-569718546f49)

## Agregue el README.md al stage o escenario y realice el primer commit.
```
git add .
git commit -m "Creación del readme"
```
![image](https://github.com/user-attachments/assets/9800ee10-f910-44ba-a8d8-24ad7cba1737)

## Cree una carpeta dentro del proyecto llamada y dentro de la carpeta logs, cree dos archivos llamado hoy.log y historia.log.
![image](https://github.com/user-attachments/assets/545d8b0c-30fd-4fbb-b0e5-f84e12e08fe1)
![image](https://github.com/user-attachments/assets/c2f418d4-28e8-470a-96c8-eca9100327aa)

## Agregue únicamente el archivo hoy.log al stage.
```
git add hoy.log
git status
```
![image](https://github.com/user-attachments/assets/eaa22085-e451-40c5-9c89-bdad81b6f829)

## Realice el segundo commit con el archivo hoy.log, y en el mensaje coloque "Creamos el archivo hoy.log"
```
git commit -m "Creamos el archivo hoy.log"
```
![image](https://github.com/user-attachments/assets/d70813dd-f767-4c1e-93b2-646200d380a9)

## Crear el archivo .gitignore y ignorar completamente el archivo historia.log.
![image](https://github.com/user-attachments/assets/c3facc39-a9f5-490d-a61c-d3aa58db8d88)
![image](https://github.com/user-attachments/assets/8631d8e5-26fb-48f1-b308-e43f8605ba31)

## Agregue al stage el archivo .gitignore y realice el commit unicamente con el archivo .gitignore.
![image](https://github.com/user-attachments/assets/fd46c0cd-9a86-4687-98a6-e04f46ee8e5a)

## Borre la carpeta LOGS, el archivo hoy.log, historia.log y .gitignore.
![image](https://github.com/user-attachments/assets/24b05862-4cac-48c7-b35c-77b65cde7eff)

## Reconstruir todo lo borrado con un único comando.
```
git checkout -- .
```
![image](https://github.com/user-attachments/assets/39ebed74-7d95-478e-82d9-f5a765cbe887)

> [!NOTE]
> Vemos que el archivo historia.log no se restauro porque en ningun momento le pedimos a GIT que estuviera pendiente de sus cambios realizados al archivo.
