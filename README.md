# Curso Spring - Proyectos

Este workspace contiene dos proyectos Spring Boot desarrollados en el Curso de Código Facilito.

## 📁 Proyectos

### 1. **ejemplos**
Proyecto básico de Spring Boot que demuestra conceptos fundamentales.

**Características:**
- Controladores para manejo de peticiones HTTP
- Modelos de datos (clases de entidad)
- Servicios para lógica de negocio
- Plantillas HTML con Thymeleaf
- Parámetros y gestión de rutas

**Rutas principales:**
- `/` - Página de inicio
- `/parametros` - Página de parámetros

---

### 2. **peliculas**
Aplicación completa para gestión de películas con interfaz web.

**Características:**
- **DAO (Data Access Object)** - Acceso a datos
- **Entidades** - Modelos de base de datos
- **Servicios** - Lógica de negocio
- **Controladores** - Gestión de peticiones HTTP
- **Templates** - Interfaz Thymeleaf con layout responsivo
- **Base de datos** - Inicialización con import.sql
- **Estilos** - CSS personalizado y JavaScript

**Estructura de vistas:**
- `home.html` - Página principal
- `listado.html` - Listado de películas
- `pelicula.html` - Detalle de película
- `layouts/` - Componentes reutilizables (header, head)

---

## 🚀 Cómo ejecutar

Cada proyecto usa **Maven** y tiene los scripts `mvnw` (Unix/Linux/Mac) y `mvnw.cmd` (Windows).

```bash
# Desde la carpeta del proyecto
./mvnw.cmd spring-boot:run
```

## 📋 Requisitos

- Java 8 o superior
- Maven 3.6+

## 📝 Notas

- Ambos proyectos están configurados en `application.properties`
- Las plantillas HTML están en `src/main/resources/templates/`
- Los estilos y scripts están en `src/main/resources/static/`
