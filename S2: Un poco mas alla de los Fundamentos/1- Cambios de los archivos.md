# Cambios de los archivos.
## Creamos una nueva carpeta con un nuevo archivo y inicializamos git.
```
mkdir ejemplos
code pasos.md
cat pasos.md
git init
git add .
git commit -m "Pasos.md agregado" 
```
![image](https://github.com/user-attachments/assets/a3126a18-73d9-4848-8fa7-06324c918c0a)
![image](https://github.com/user-attachments/assets/cf12df61-91a8-4775-8943-dd3531073d0c)

## Modificamos el archivo nuevamente y visualizamos las diferencias.
```
vi pasos.md
git diff
```
![image](https://github.com/user-attachments/assets/f92b429c-4ed7-42bb-abfd-b3ebf0e4366f)

## Agregar mas lineas y agregarlo al stage. Consultar diferencias.
```
vi pasos.md
git add .
git diff --staged
```
![image](https://github.com/user-attachments/assets/655e11ac-7819-4fd3-9128-6544ecd0c42b)

> [!NOTE]
> Una vez que se agrega al staged, no podemos ver las diferencias sin el --staged.
