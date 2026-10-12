# Comandos

## Staging Area

### Ver estado

```powershell
git status
```

### Agregar archivos

```powershell
git add .
```

### Quitar archivos

```powershell
# Sin commit
git rm -r --cached .
git rm --cached archivo.ext
```

```powershell
# Con commit
git restore --staged .
```

## Commits

### Mostrar commits

```powershell
git log
```

### Ejecutar commit

```powershell
git commit -m "Descripción breve de los cambios"
```

### Editar commit

```powershell
# No recomendado si ya está en remoto
git commit --amend -m "Descripción corregida del commit"
```

```powershell
# Forzar cambios del commit en remoto
git push origin main --force-with-lease
```

### Borrar commit

```powershell
# Conservar cambios y Staging Area
git reset --soft HEAD~1
```

```powershell
# Conservar cambios
git reset --mixed HEAD~1
```

```powershell
# Borrar todo
git reset --hard HEAD~1
```

## Repositorios remotos

### Descargar

```powershell
git clone url
```

### Mostrar url

```powershell
git remote -v
```

### Cambiar url

```powershell
git remote set-url origin url
```

## Versiones estables

### Mostrar etiquetas

```powershell
git tag
```

```powershell
# Detalles de etiqueta
git show v1.0.0
```

### Etiquetar commit

```powershell
git tag -a v1.0.0 -m "Descripción breve de la actualización"
```

### Subir a repositorio remoto

```powershell
git push origin --tags
```
