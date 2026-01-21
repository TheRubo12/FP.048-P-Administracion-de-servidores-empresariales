# Índice de documentación (FP.048)

## Producto 1 – Administración remota del servicio de directorio
**Objetivo:** analizar el sistema actual, diseñar la solución de dominio e implementar AD DS con DNS/DHCP y administración remota.  
**Contenido principal:**
- Inventario y análisis del estado inicial
- Diseño del dominio (estructura organizativa, mapa lógico/físico)
- Matriz de control de acceso (ACL) para recursos
- Implementación de controladores de dominio y servicios DNS/DHCP
- Habilitación de administración remota (RDP/RSAT) con acceso restringido

Archivo: `informes/producto-01-administracion-remota-servicio-directorio.pdf`

## Producto 2 – Servicios y recursos de red
**Objetivo:** completar la implementación del directorio y recursos según el diseño del Producto 1.  
**Contenido principal:**
- Creación de OUs, grupos y usuarios
- Automatización inicial con PowerShell
- Unión de Windows 11 al dominio
- Unión de Ubuntu al dominio (Samba/Winbind/Kerberos)
- Carpetas compartidas, permisos y unidades de red
- Servicio de impresión centralizado y pruebas

Archivo: `informes/producto-02-servicios-recursos-red.pdf`

## Producto 3 – Automatización de tareas y procesos
**Objetivo:** automatizar tareas repetitivas de administración y mantenimiento.  
**Contenido principal:**
- Scripts PowerShell: gestión de usuarios y grupos
- Monitorización (CPU, memoria, disco) y registro de alertas
- Gestión del sistema de ficheros (búsquedas por usuario/tipo/tamaño)
- Gestión de procesos (listados y métricas por usuario)
- Creación de tareas programadas y menú principal para ejecutar todo

Archivo: `informes/producto-03-automatizacion-tareas-procesos.pdf`

## Producto 4 – Implantación de base de datos
**Objetivo:** desplegar un servidor de base de datos empresarial y centralizar la información del negocio.  
**Contenido principal:**
- Análisis de necesidades y arquitectura
- Instalación de SGBD y herramienta de administración
- Integración con Active Directory (autenticación y permisos)
- Estrategia de copias de seguridad y restauración
- Tareas de mantenimiento/optimización
- Acceso web de demostración (IIS)

Archivo: `informes/producto-04-implantacion-base-datos.pdf`
