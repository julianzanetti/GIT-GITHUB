# Inicios en GitHub, Gitremote, Push & Pull.
## Subir nuestro archivo local a nuestro repo de GitHub.
1- Crear el repo en GitHub.
2- [Guardar nuestro Usuario y Contraseña de GitHub](https://docs.github.com/en/get-started/git-basics/caching-your-github-credentials-in-git#platform-linux)
3- Realizar la conexion a nuestro repo creado.
```
git remote add origin **`(link del Repo)`**
```

4- Realizar el commit.
```
git commit -m "Comentario"
```

5- Realizar el push
```
git push
```

## Subir nuestros Tags
1- Revisar los tags locales
```
git tag
```

2- Subirlo a GitHub.
```
git push tags
```
