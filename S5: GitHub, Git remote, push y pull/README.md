# Inicios en GitHub, Gitremote, Push & Pull.
## Subir nuestro archivo local a nuestro repo de GitHub.
- Crear el repo en GitHub.
- [https://docs.github.com/en/get-started/git-basics/caching-your-github-credentials-in-git#platform-linux](Guardar nuestro Usuario y Contraseña de GitHub)
- Realizar la conexion a nuestro repo creado.
```
git remote add origin **`(link del Repo)`**
```

- Realizar el commit.
```
git commit -m "Comentario"
```

- Realizar el push
```
git push
```

## Subir nuestros Tags
- Revisar los tags locales
```
git tag
```

- Subirlo a GitHub.
```
git push tags
```
