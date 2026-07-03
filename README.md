# Taller 4 - UEFA Champions League 🏆

Proyecto web desarrollado con **HTML5**, **Bootstrap 5.3.3** y **Bootstrap Icons**, que simula un sitio informativo y de gestión de la UEFA Champions League. Incluye una página pública de inicio, un sistema de autenticación (login, registro y recuperación de contraseña) y dos paneles internos: uno de administración y otro para clubes.

## 📁 Estructura del proyecto

```
├── index.html              # Página principal (pública)
├── assets/
│   └── img/                 # Imágenes del sitio (logos, escudos, estadios, carrusel)
└── app/
    ├── login.html            # Inicio de sesión
    ├── registro.html         # Registro de club
    ├── recuperar.html        # Recuperación de contraseña
    ├── admin.html            # Panel de administración
    └── cliente.html          # Panel del club (área de cliente)
```

> ⚠️ Como `index.html` está en la raíz y el resto de páginas dentro de `app/`, las rutas a los recursos (`assets/img/...`) e hipervínculos internos deben ajustarse según el nivel:
> - Desde `index.html` → `assets/img/...` y `app/login.html`
> - Desde archivos dentro de `app/` → `../assets/img/...` y `../index.html`

## 🌐 Páginas

| Página | Ruta | Descripción |
|---|---|---|
| Inicio | `index.html` | Landing page con carrusel, equipos clasificados y sedes del torneo |
| Iniciar sesión | `app/login.html` | Formulario de acceso de usuarios |
| Registro | `app/registro.html` | Formulario de registro de un nuevo club |
| Recuperar contraseña | `app/recuperar.html` | Formulario de recuperación de acceso |
| Panel Admin | `app/admin.html` | Panel con estadísticas generales del torneo (equipos, presupuesto, jugadores, etc.) |
| Panel del Club | `app/cliente.html` | Panel privado de información del club |

## 🛠️ Tecnologías utilizadas

- **HTML5** semántico
- **Bootstrap 5.3.3** (vía CDN)
- **Bootstrap Icons 1.11.3** (vía CDN)
- Diseño **responsive** (mobile-first)

## 🚀 Cómo ejecutar el proyecto

1. Clona o descarga este repositorio.
2. Verifica que la estructura de carpetas (`assets/img` y `app/`) se mantenga tal como está.
3. Abre `index.html` en tu navegador (no requiere servidor ni instalación de dependencias, ya que los estilos y scripts de Bootstrap se cargan desde CDN).

## ✍️ Autor

Sebastian Monsalve

## 📄 Licencia

Proyecto académico de uso educativo — Taller 4 de Desarrollo Web.
