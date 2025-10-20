# 
# Aplicación Web Java - Eclipse

Aplicación web básica en Java, utilizando Servlets y JSP. Desarrollada en Eclipse con la plantilla **Dynamic Web Project** con conexión a base de datos MySQL mediante JDBC.

Este proyecto **no utiliza Maven**; las dependencias están incluidas manualmente en la carpeta `lib/`.

## Requisitos

- Java 8 o superior
- Eclipse IDE con soporte para Java EE
- Apache Tomcat 9
- MySQL 8 o compatible  
- Navegador web

## Estructura

- `src/` – Código fuente Java
- `WebContent/` – Archivos web (JSP, HTML, CSS, JS)
- `WEB-INF/web.xml` – Configuración de despliegue
- `lib/` – Librerías externas (.jar)
- `database/` – Scripts SQL para estructura de base de datos

## Cómo usar

1. Clona este repositorio.
2. Abre Eclipse y ve a `File > Import > Existing Projects into Workspace`.
3. Asegúrate de tener Tomcat configurado como servidor.
4. Ejecuta el script SQL ubicado en `database/` para crear la tabla necesaria en tu base de datos MySQL.
5. Ejecuta el proyecto con **Run on Server**.

---
