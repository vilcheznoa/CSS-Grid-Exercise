# 💒 Galería Boda – CSS Grid

Demo en vivo: https://vilcheznoa.github.io/CSS-Grid-Exercise/

---

## 📸 Descripción
Pequeño ejercicio usando **CSS Grid** para presentar 11 fotografías de una boda con una cuadrícula flexible y accesible. Ideal para practicar distribución de imágenes, fuentes personalizadas y ajustes responsivos.

## ✨ Características principales
| Concepto | Detalle |
|----------|---------|
| Grid | `repeat(4, 1fr)` columnas, filas auto |
| Altura | `grid-auto-rows: minmax(150px, auto)` |
| Ajuste imagen | `object-fit: contain` para mostrar completa |
| Accesibilidad | Descripciones en cada `alt` |
| Fuente | Cargada vía `@font-face` (Glitter) |

## 🗂 Estructura
```
CSS-Grid-Exercise/
├── index.html          # Marcado principal
├── index.css           # Estilos y grid
├── README.md           # Documentación
└── img/                # Carpeta de imágenes
        ├── 1.jpg
        ├── 2.jpg
        ├── ...
        └── 11.jpg
```

## 🛠 Uso rápido
Clonar y abrir:
```bash
git clone https://github.com/vilcheznoa/CSS-Grid-Exercise.git
cd CSS-Grid-Exercise
```
Abrir `index.html` en tu navegador.

## 🤝 Créditos
Imágenes: colección privada (no redistribuir). Proyecto educativo.
