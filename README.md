# 📋 Planificador de Tareas

Aplicación web responsive para gestión de proyectos y tareas, construida en HTML, CSS y JavaScript puro (sin frameworks).

## ✨ Características

- **Tareas principales** con fechas de inicio y fin, y prioridad (Crítica / Alta / Media / Baja)
- **Subtareas** anidadas dentro de cada tarea principal
- **Estados automáticos** por proyecto: *No iniciada → En progreso → Terminada*
  - Al agregar la primera subtarea el proyecto pasa automáticamente a *En progreso*
  - Cuando todas las subtareas se terminan el proyecto se cierra solo
- **Cambio de estado rápido** haciendo clic en el badge de cada subtarea
- **Barra de progreso** que refleja el porcentaje real de subtareas completadas
- **Estadísticas globales** en el encabezado
- **Persistencia local** mediante `localStorage` (los datos se mantienen al recargar)
- **Diseño responsive** compatible con móvil y escritorio

## 🚀 Uso

No requiere instalación ni dependencias. Abre `planificador.html` directamente en el navegador.

```bash
# Opción 1 — abrir directamente
open planificador.html

# Opción 2 — servidor local rápido
npx serve .
```

## 🗂 Estructura

```
Planificador/
├── planificador.html   # Aplicación completa (single-file)
├── .gitignore
└── README.md
```

## 🛠 Tecnologías

| Tecnología | Uso |
|------------|-----|
| HTML5      | Estructura y semántica |
| CSS3       | Estilos, animaciones, responsive |
| JavaScript | Lógica, persistencia, estado automático |
| localStorage | Almacenamiento de datos en el navegador |

## 📄 Licencia

MIT — libre de usar y modificar.
