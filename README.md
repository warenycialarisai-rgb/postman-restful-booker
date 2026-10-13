# 🚀 API Testing Suite with Postman - Restful Boker

Este repositorio contiene una colección de pruebas automatizadas y funcionales creadas en Postman para validar los endpoints de la API REST de Restful Booker.

📌 Objetivos del Proyecto
Validar el correcto funcionamiento de las operaciones CRUD (GET, POST, PUT, DELETE).
Verificar los códigos de respuesta HTTP (200 OK, 201 Created, 400 Bad Request, 404 Not Found, etc.).
Asegurar la estructura e integridad de las respuestas en formato JSON.
Implementar validaciones automatizadas mediante scripts en JavaScript dentro de Postman.
🛠️ Herramientas y Tecnologías
Postman: Diseño, ejecución y automatización de peticiones HTTP.
JavaScript: Escribir aserciones y validaciones dentro de la pestaña Tests.
Postman Environments: Gestión dinámica de URLs y variables de entorno.
Git & GitHub: Control de versiones y documentación.
📋 Pruebas e Identificación de Cobertura

Entre las principales validaciones incluidas en las peticiones se encuentran:

1-Status Code Verification: Confirmación de estados HTTP esperados.

2-Response Time: Verificación de que los tiempos de respuesta sean menores a x milisegundos.

3-JSON Schema Validation: Comprobación de tipos de datos y campos requeridos en la respuesta.

4-Data Correlation: Uso de variables para capturar datos de una respuesta (ej. token o id) y reutilizarlos en peticiones posteriores.

⚙️ Configuración y Ejecución Local Para clonar y ejecutar este proyecto en tu entorno local:

1-Clonar el repositorio
2-Importar en Postman
3-Ejecutar la Colección:

💡 Nota sobre Seguridad: Las variables incluidas en environment.json corresponden a un entorno público de pruebas con datos sintéticos.

✒️ Larisa Warenycia - www.linkedin.com/in/larisa-warenycia-0759812b2
