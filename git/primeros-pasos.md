# Primeros pasos

## Repositorio local

```powershell
# Crear repositorio oculto .git
git init
```

```powershell
# Agregar archivos al Staging Area
git add .
```

```powershell
# Agregar archivos al repositorio local
git commit -m "Primer commit"
```

## Repositorio en GitHub

No `README`, no `.gitignore` y no `license`

```powershell
git remote add origin https://github.com/usuario/ejemplo.git
```

```powershell
# Renombrar rama principal
git branch -M main
```

```powershell
# Subir commit al repositorio remoto
git push -u origin main
```

## Después del primer commit

```powershell
git add .
git commit -m "Descripción breve de los cambios"
git push
```

## Ignorar archivos

Archivo `.gitignore` en la raíz del proyecto

```ini
# comentario
nombre-carpeta
nombre-archivo.extensión
```
