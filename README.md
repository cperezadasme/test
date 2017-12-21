# Tutorial Git

### Crear nueva rama
```
$ git checkout -b nombre_rama
```

### Cambiar de rama
```
$ git checkout rama
```
### Agregar cambios

```
$ git add -A
```

### Commit

```
$ git commit -a -m "comentario"
```

### Ver estados
```
$ git status 
```

### Subir cambios a git

```
$ git push origin nombre_rama
```

Si no existe otra rama
```
$ git push origin master
```

### Pull request
Crear rama y luego hacer pull request en github

### Eliminar rama
Del repositorio local
```
$ git branch -D nombre_rama
```

Del repositorio remoto (github)
```
git push origin --delete nombre_rama
```

