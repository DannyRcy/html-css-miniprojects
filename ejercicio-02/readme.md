# 🍝 Proyecto: Receta Interactiva con HTML y CSS

## Descripción
Este proyecto implementa una **página de receta** (Pasta a la Carbonara) con elementos HTML estructurados y estilos CSS avanzados. Incluye listas organizadas, tabla nutricional con efecto zebra y efectos de interacción mediante pseudo-clases.

---

## 📋 Contenido del Proyecto

### Archivos
- `index.html` - Estructura HTML con listas y tabla nutricional
- `style.css` - Estilos CSS con pseudo-clases de interacción
- `readme.md` - Este archivo

---

## ✨ Características Implementadas

### 1️⃣ Listas Estructuradas

#### Lista No Ordenada (`<ul>`)
- **Uso:** Ingredientes de la receta
- **Características:**
  - Ícono visual (✓) en cada elemento
  - Borde izquierdo coloreado
  - Interactividad con hover

#### Lista Ordenada (`<ol>`)
- **Uso:** Procedimiento paso a paso
- **Características:**
  - Numeración automática
  - Fondo alternado en hover
  - Transición suave de 0.2s

---

### 2️⃣ Tabla Nutricional

**Estructura HTML:**
```html
<table class="nutrition-table">
  <thead>
    <tr>
      <th>Nutriente</th>
      <th>Cantidad</th>
      <th>Unidad</th>
      <th>% Valor Diario</th>
    </tr>
  </thead>
  <tbody>
    <tr>...</tr>
  </tbody>
</table>
```

**Reglas CSS Aplicadas:**

| Elemento | Regla CSS | Resultado |
|----------|-----------|-----------|
| `<table>` | `border-collapse: collapse; width: 100%;` | Tabla limpia sin doble borde, adaptada al ancho completo |
| `<tr:nth-child(even)>` | `background-color: #F8F9FA;` | Efecto zebra para mejorar legibilidad |
| `<tr:hover>` | `background-color: #E9ECEF; transition: 0.2s;` | Resaltado interactivo al pasar el ratón |

---

### 3️⃣ Pseudo-clases de Interacción

#### `:hover`
- **Ingredientes:** Cambio de fondo a `#E9ECEF` con desplazamiento y sombra
- **Tabla:** Filas se resaltan al pasar el ratón

#### `:nth-child(even)`
- Aplica `background-color: #F8F9FA` a filas pares
- Crea efecto alternado para mejor lectura

#### `:nth-child(odd)`
- Mantiene fondo blanco en filas impares

---

## 🎨 Paleta de Colores

| Color | Uso |
|-------|-----|
| `#667eea` | Encabezados, bordes, botones |
| `#764ba2` | Títulos secundarios, gradientes |
| `#F8F9FA` | Fondo zebra (filas pares) |
| `#E9ECEF` | Estado hover |
| `#333` | Texto principal |
| `#666` | Descripción |

---

## 📱 Características Responsivas

- Grid adaptable para tarjetas de información
- Estilos optimizados para móviles
- Media queries para pantallas menores a 768px

---

## 🎯 Elementos Clave de CSS

### Border-collapse
```css
.nutrition-table {
    border-collapse: collapse;
    width: 100%;
}
```
Elimina el espaciado doble entre bordes de celdas.

### Efecto Zebra
```css
.nutrition-table tbody tr:nth-child(even) {
    background-color: #F8F9FA;
}
```
Alterna colores en filas para mejorar legibilidad.

### Transición Suave
```css
.ingredients-list li:hover {
    background-color: #E9ECEF;
    transition: all 0.2s ease;
}
```
Feedback visual instantáneo al usuario.

---

## 🚀 Cómo Usar

1. Abre `index.html` en tu navegador
2. Interactúa con los elementos:
   - Pasa el ratón sobre los ingredientes
   - Pasa el ratón sobre las filas de la tabla
   - Observa los efectos de transición

---

## 📚 Estructura HTML

```
index.html
├── Container
│   ├── Título y descripción
│   ├── Sección Ingredientes (<ul>)
│   ├── Sección Procedimiento (<ol>)
│   ├── Tabla Nutricional
│   │   ├── <thead>
│   │   └── <tbody>
│   └── Sección Información (tarjetas)
└── Vinculación a style.css
```

---

## 💡 Conceptos Aprendidos

✅ Estructura semántica de HTML (`<table>`, `<thead>`, `<tbody>`)
✅ Listas organizadas (`<ul>` y `<ol>`)
✅ Pseudo-clases CSS (`:hover`, `:nth-child()`)
✅ Propiedades de transición y animación
✅ Border-collapse para tablas limpias
✅ Diseño responsivo con Grid y Media Queries

---

## 🎓 Autor
Proyecto educativo de HTML y CSS avanzado.

**Fecha:** Septiembre 2026
