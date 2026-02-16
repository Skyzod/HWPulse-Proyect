# HWPulse-Proyect
Personal proyect

## Sistema Fullstack de Inventario y Diagnóstico Automático

**Darío Acevedo Hijano**

1. Finalidad
Este proyecto consiste en el desarrollo de un programa de monitorización y gestión de activos informáticos. El propósito principal es automatizar la recolección de datos técnicos de hardware y software en una red, eliminando la necesidad de auditorías manuales y ahorrando tiempo en la administración de sistemas. Se busca ofrecer una plataforma de inventario que también diagnostique el estado de salud de los componentes en tiempo real.

2. Objetivos
Automatización de activos: Desarrollar un agente capaz de extraer información detallada (CPU, RAM, Discos, S.O.) de forma autónoma.
Centralización de datos: Implementar un servidor centralizado que reciba y organice la información de múltiples clientes mediante una arquitectura API.
Diagnóstico preventivo: Crear un sistema de alertas basado en parámetros críticos (temperatura, uso de recursos, fallos de disco S.M.A.R.T.).
Despliegue eficiente: Utilizar tecnologías de virtualización como Docker-Compose para garantizar que el servidor sea fácil de desplegar en cualquier entorno Linux.

3. Medios hardware y software a utilizar
Para el desarrollo y ejecución del proyecto se requieren los siguientes recursos:
Hardware: PC de desarrollo y un servidor Linux para el despliegue de producción.
Entorno de desarrollo: Visual Studio Code como IDE principal.
Control de versiones: GitHub para la gestión del código fuente.
Backend: Python con el framework Django o FastAPI para gestionar la lógica de negocio y la API.
Base de Datos: PostgreSQL para el almacenamiento relacional de los componentes de hardware.
Frontend: Vue.js para la creación de un Dashboard administrativo dinámico e interactivo.
Infraestructura: Nginx como servidor web y proxy inverso, junto con Gunicorn para servir la aplicación Python.

4. Planificación
El proyecto se dividirá en dos fases principales:
Parte 1: Infraestructura y Servidor 
Esta fase se centra en preparar el entorno servidor:
Configuración del servidor Linux.
Configuración de contenedores con Docker y Docker-Compose.
Instalación y configuración de Nginx con CertBot para asegurar las comunicaciones mediante HTTPS.
Preparación de la base de datos PostgreSQL.
Parte 2: Desarrollo del Sistema 
Desarrollo de las funcionalidades específicas de inventario:
Agente de Extracción: Creación del script en Python que recolecta datos del hardware local.
API y Backend: Definición de modelos, vistas y endpoints en Django para recibir los datos de los agentes.
Dashboard Frontend: Desarrollo con Vue.js para visualizar el inventario, gráficas de rendimiento y gestión de alertas.
Pruebas e Informes: Validación del sistema y generación de reportes automáticos en PDF/Excel.
