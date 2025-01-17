# Viajes en el tiempo, resets y reflog.
## Visualizamos los ultimos cambios en nuestra carpeta.
```
git log
```
![image](https://github.com/user-attachments/assets/4c107870-0905-4183-870b-73b66860ef55)

## Modificar el archivo heroes.md y agregarlo antes del ultimo commit.
```
vi heroes.md
git reset --soft PID
git status
git commit -am "Heroes.md: Robin y Linterna Verde"
```
![image](https://github.com/user-attachments/assets/3e4c4852-aa90-4c8b-a6e8-689fb74ea72c)
![image](https://github.com/user-attachments/assets/85ed0528-2cf1-4c1c-99f7-259f4cac43b4)

## Viajar en el tiempo a un commit predeterminado.
```
git log
```
![image](https://github.com/user-attachments/assets/9fb354e8-34d8-454e-9508-f266ab03b0be)

```
git reset PID
```
![image](https://github.com/user-attachments/assets/6d675587-e8cb-4318-af99-d075fadfe53d)

## Volver a un punto y que el repositorio quede como estaba en dicho momento.
```
git reset --hard PID
```
![image](https://github.com/user-attachments/assets/69ddf16a-9cf4-4dd6-aa33-229a6c00b6dc)
![image](https://github.com/user-attachments/assets/fbf216f0-5633-4b28-aa40-a711878ce197)
> [!NOTE]
> Como vemos, se volvio a restaurar ese punto eliminando todas las modificaciones que se hicieron posteriormente.

## Ver todo el historial de cambios que se efectuo en nuestro repositorio.
```
git reflog
```
![image](https://github.com/user-attachments/assets/f60139d2-26d8-4a07-bcb6-0fd40b5a59d6)

## Restaurar al ultimo punto donde modificamos nuestro archivo.
```
git reflog
git reset --hard PID
```
![image](https://github.com/user-attachments/assets/6ed60e00-6c23-485e-a326-562cd30e27c7)
