Paulis Studio
Sistema de Gestión Estética (QA & Automation)
Este documento contiene el framework de pruebas automatizadas para el
ecosistema digital Paulis Studio, desarrollado para la asignatura de
Administración de Bases de Datos y Validación de Software (8vo Semestre
- Ingeniería de Sistemas, CUN).
  
🚀 Descripción del Proyecto
Paulis Studio es una plataforma integral para la transformación digital de
centros de estética. El sistema permite la gestión automatizada de clientes,
servicios y productos de belleza mediante una arquitectura Serverless:
Frontend: React / Vercel.
Base de Datos: Firebase Cloud Firestore (NoSQL).
Notificaciones: API de Resend para confirmación de citas.
QA Engine: Selenium IDE.

🧪 Estrategia de Aseguramiento de Calidad (QA)
Se implementaron Pruebas de Caja Negra (Black Box Testing) para
certificar la funcionalidad del software desde la perspectiva del usuario final,
garantizando que el flujo de agendamiento y el control de inventario de
productos de belleza sean infalibles.
Casos de Prueba Automatizados

El archivo PaulisStudio_Tests.side incluye los siguientes escenarios:
CP-01: Autenticación de Estilistas
Validación de acceso al panel administrativo y protección de datos de
clientes.

CP-02: Control de Inventario de Insumos
Verificación de la persistencia de productos (tintes, esmaltes,
tratamientos) en las colecciones de Firestore.

CP-03: Ciclo de Vida de Citas Estéticas
Agendamiento: Registro de servicios (Manicura, Corte, Balayage) y
validación de horarios.

Cancelación: Eliminación de registros y actualización inmediata de la
agenda en el DOM.

🛠️ Ejecución de Pruebas
Instale la extensión de Selenium IDE.
Cargue el archivo Pruebas Automaticas Paulistudio.side
Configure la URL base: https://salonpaulistudio.vercel.app.
Ejecute la suite de pruebas y verifique los logs en verde.
Autora: Ingri Tatiana Faustino Callejas
Ingeniería de Sistemas - CUN (2026)
Guepsa-Santander
