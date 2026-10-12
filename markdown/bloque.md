# Elementos de Bloque

## Párrafos

```markdown
Una LÍNEA de texto crea un PÁRRAFO.
Una LÍNEA CONTIGUA pertenece al párrafo anterior.
DOS ESPACIOS al final de la línea:  
Crean un SALTO DE LÍNEA dentro del mismo párrafo.

Una LÍNEA EN BLANCO crea un NUEVO PÁRRAFO.
```

## Encabezados

```markdown
# Encabezado de nivel 1
## Encabezado de nivel 2
### Encabezado de nivel 3
#### Encabezado de nivel 4
##### Encabezado de nivel 5
###### Encabezado de nivel 6
```

## Bloques de Código

~~~markdown
```javascript
console.log('Ana');
```
~~~

## Líneas Horizontales

```markdown
---
```

## Listas

### Ordenada

```markdown
1. Primer elemento de lista ordenada
1. Segundo elemento de la misma lista
    - Sublista no ordenada, dejar 4 espacios
1. Tercer elemento, la numeración es automática
    1. Sublista ordenada, dejar 4 espacios
        1. Subsublista ordenada, dejar 4 espacios más
        1. Subsublista previa
    1. Sublista previa
1. Último elemento de la lista
```

### No Ordenada

```markdown
- Lista no ordenada
- Otro elemento de la misma lista
  1. Sublista ordenada, dejar 2 espacios
- Otro elemento más
  - Sublista ordenada, dejar 2 espacios
    - Subsublista ordenada, dejar 2 espacios más
    - Subsublista previa
  - Sublista previa
- Último elemento de la lista
```

## Citas

```markdown
> Una línea de una CITA.
Una LÍNEA CONTIGUA pertenece a la cita anterior.

Una LÍNEA EN BLANCO termina la cita.

>> CITA ANIDADA o de mayor nivel
>
> Esta línea es de menor nivel.
> Esta línea también continúa a la anterior.
```
