# Merge: Uniones con conflicto.
## Creamos otra rama.
```
git checkout -b rama-conflicto
```

## Modificamos un archivo de esta rama.
![image](https://github.com/user-attachments/assets/6ffb8d9e-0903-434e-bf82-463c797dc3c8)

## Volvemos a la master y realizamos una modificacion en el mismo archivo.
![image](https://github.com/user-attachments/assets/b96ab47c-2b45-44d5-b4c9-e67dd2aea31a)

## Realizamos el merge.
```
git merge ramas-conflictos
```
![image](https://github.com/user-attachments/assets/333511b6-943f-4ce7-b7f2-1df4f02ac2ab)
![image](https://github.com/user-attachments/assets/e5b2320b-8fe2-4f77-9b49-ab89b22de6be)

## Resolver el conflicto.
- Para resolver el conflicto tenemos que decidir como dejar el archivo modificado, modificandolo manualmente y dejarlo como queremos que quede.
- En VS nos dan algunas opciones para resolverlo.
![image](https://github.com/user-attachments/assets/eb993917-74af-4cb9-9c29-74990f2ba2b5)

- Realizamos el commit.
```
git commit -am "Union con rama-conflicto"
```
![image](https://github.com/user-attachments/assets/eb3eb124-4969-47c9-8347-8843ba381041)
