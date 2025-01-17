# Merge.
- ### Repositorio
![image](https://github.com/user-attachments/assets/c42a3d41-849b-40af-b87e-a73447870f97)

## Fast-Foward.
- ### Agregamos un archivo a nuestro repositorio.
![image](https://github.com/user-attachments/assets/ada7b2d5-65ed-46c1-9566-4441b17ee99a)

- ### Creamos una nueva rama llamada "rama-villanos"
```
git branch rama-villanos
git branch
```
![image](https://github.com/user-attachments/assets/e073df37-0670-4921-b29f-e031edb013fe)

- ### Cambiamos a la nueva rama.
```
git checkout rama-villanos
```
![image](https://github.com/user-attachments/assets/13f6bcee-5ef2-4ffa-a562-e7aef4b9e0bc)
![image](https://github.com/user-attachments/assets/f38ef799-d70f-443f-9748-4902cb905cae)
> [!NOTE]
> Vemos que la rama master y rama-villanos estan en el mismo punto.

- ### Agregamos el nuevo archivo y comiteamos.
```
git add .
git commit -m "villanos agregados"
git log
```
![image](https://github.com/user-attachments/assets/a8b30de1-06c0-40e1-a925-510ef8e69ae8)
> [!NOTE]
> Vemos que al agregar el archivo, la rama master quedo en el mismo punto pero nos movimos en la rama-villanos.
> Es decir, estamos trabajando en la rama secundaria.

- ### Modificar el archivo y comitear.
![image](https://github.com/user-attachments/assets/6fc627d4-4443-495b-824c-6021e08b7cd9)

- ### Volver a la rama master.
```
git checkout master
```
![image](https://github.com/user-attachments/assets/daacae8b-9f4f-400c-9a13-07395f973127)
![image](https://github.com/user-attachments/assets/c1c74d30-032c-442c-865a-12a14be886c3)
> [!IMPORTANT]
> Vemos que al volver a la rama master, el archivo creado desaparecio porque no pertenece a esta rama.

- ### Unir la rama-villano con la master.
```
git merge rama-villanos
git log
```
![image](https://github.com/user-attachments/assets/7d4d0feb-aa1b-4a72-9b91-61da94278f7b)
![image](https://github.com/user-attachments/assets/c201b06e-3062-4689-857a-bc0fc725f9cd)
![image](https://github.com/user-attachments/assets/dc13be9b-a881-4fe9-b2f5-053aa68b2644)

- ### Borrar la rama secundaria.
```
git branch -d rama-villanos
```
![image](https://github.com/user-attachments/assets/a3e0b1d2-4cdc-4520-9091-9563aa80df7f)
