# Etiquetas - Tags.
## Creando una etiqueta.
```
git tag string
```
![image](https://github.com/user-attachments/assets/5c7f53a4-deb1-49c1-a220-08b03afa9112)

## Eliminar una etiqueta.
```
git tag
git tag -d string
```
![image](https://github.com/user-attachments/assets/c331daf5-a8a1-48ae-8f39-8496749e42e0)

## Creando una etiqueta con versionado.
```
git tag -a v1.0.0 -m "Version 1.0.0 lista"
```
![image](https://github.com/user-attachments/assets/2ec0c731-4e65-4cf1-9b4c-d7ab382e22a8)

## Agregar una version a un commit anterior.
```
git tag -a v0.1.0 hash -m "Version Alpha de nuestra app"
```
![image](https://github.com/user-attachments/assets/0c763460-87ce-4e99-a448-913d7a3b1911)

## Ver mas info cuando consultamos los tags.
```
git tag
git show v0.1.0
```
![image](https://github.com/user-attachments/assets/57ecfd56-fcbb-4ece-8db9-4ced5598a274)
