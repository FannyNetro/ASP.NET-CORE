## Proyecto ASP.NET Core – Lista de Tareas Personalizada

Este repositorio contiene el proyecto desarrollado durante el webinar "Uso de ASP.NET Core", donde se implementa una aplicación web utilizando el patrón Modelo-Vista-Controlador (MVC).

## Características principales
- Aplicación web construida con ASP.NET Core MVC.
- Autenticación de usuarios (cada usuario accede a su cuenta).
- Gestión de listas de tareas personalizadas por usuario.
- Funcionalidades CRUD:
  - Crear nuevas tareas.
  - Leer y visualizar tareas.
  - Actualizar tareas existentes.
  - Eliminar tareas.
- Filtrado por prioridad y orden para organizar las tareas.

## Requisitos
- [.NET SDK](https://github.com/FannyNetro/ASP.NET-CORE.git) 6.0 o superior.
- IDE recomendado: Visual Studio 2022 o Visual Studio Code con extensión C#.

## Instrucciones para ejecutar el proyecto

### 1. Clonar el repositorio
git clone https://github.com/FannyNetro/ASP.NET-CORE.git

## 2. Navegar al directorio del proyecto
cd nombre-del-repositorio

## 3. Restaurar dependencias
dotnet restore

## 4. Ejecutar la aplicación
dotnet run

La aplicación estará disponible en https://localhost:5001 o http://localhost:5000.

Estructura del proyecto

Controllers/: Contiene los controladores MVC que manejan la lógica de la aplicación.

Models/: Contiene las clases de modelo de datos.

Views/: Contiene las vistas de la aplicación (HTML + Razor).

wwwroot/: Archivos estáticos (CSS, JS, imágenes).

Créditos
