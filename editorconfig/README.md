# EditorConfig

Apuntes generales del archivo de configuración [EditorConfig][editorconfig]

## Estructura Básica

```ini
# Comentario
[seccion]
propiedad = valor
```

### Secciones

```ini
# Cualquier tipo de archivo
[*]

# Un tipo de archivo específico
[*.py]

# Varios tipos de archivos específicos
[*.{py,js}]
```

### Propiedades

```ini
# Configuración raíz
root = true

# Tipo de indentación
indent_style = space
# Tamaño de indentación
indent_size = 4

# Conjunto de caracteres
charset = utf-8

# Borrar espacios al final de línea
trim_trailing_whitespace = true
# Insertar línea en blanco al final de texto
insert_final_newline = true
```

<!-- REFERENCIAS -->

[editorconfig]: https://editorconfig.org/
