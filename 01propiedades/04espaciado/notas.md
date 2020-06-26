# NOTAS

## Definición de propiedades

Se pueden definir columnas y filas por separado o directamente en una sola:

Ejemplo separado:

```css
.container {
  display: grid;
  grid-template: 300px 150px / 25% 200px 25%;
  grid-row-gap: 20px;
  grid-column-gap: 30px;
}
```

Ejemplo en una unica propiedad:

```css
.container {
  display: grid;
  grid-template: 300px 150px / 25% 200px 25%;
  /* en este caso solo se requiere de un espacio */
  /** filas columnas */
  grid-gap: 20px 30px;
}
```
