# Emisión de Seguros

Este proyecto tiene como objetivo desarrollar una plataforma web que permita la emisión de pólizas de seguro de manera ágil y segura. La solución está diseñada para ser accesible desde cualquier dispositivo, proporcionando una experiencia de usuario fluida y optimizada.

El sistema integrará formularios interactivos para la captura de datos del cliente, verificación de identidad, y validación de información mediante servicios web provistos por Nacional Seguros. Además, se incluirán características de generación automática de documentos como pólizas y facturas, firmadas digitalmente y acompañadas de códigos QR para su validación.

Uno de los componentes clave del proyecto es la integración de una pasarela de pago, que permitirá procesar transacciones de manera eficiente y segura. El proceso de emisión incluirá también la autenticación del cliente mediante OTP (One-Time Password) y el almacenamiento seguro de sus datos.

Este desarrollo está pensado para facilitar el proceso de contratación de seguros, asegurando el cumplimiento de las normativas y la trazabilidad de cada transacción mediante la generación de identificadores únicos en cada paso.

## Antecedentes

Puedes ver cómo nos contactaron [aquí](https://github.com/Nacional-Seguros/.github/wiki/Antecedentes).

## Presupuesto

- Precio Bs. 87.500,00
- Se entragarán todos los códigos en este repositorio con el manual de usuario en la wiki.
- 2 Meses de desarrollo + 1 mes pruebas.

### Forma de pago

|Estado|Cuota|Descripcion|Monto|Fecha a Pagar| Fecha Pago|
|-|-|-----------|-----|--|-|
|⚠️|1|Pago inicio de operaciones|Bs.30.000,00|__/__/____||
|⚠️|2|Pago inicio de pruebas|Bs.30.000,00|__/__/____||
|⚠️|3|Pago pase a producción |Bs.24.000,00|__/__/____||
||4|Langing #1| Bs.3.500|||
||5|Landing #2| Bs.3.500,00|||

## Tareas

### Project Manager
- Programar una cita con Multipagos para que nos asignen un agente.
- Recopilar las APIS de Nacional Seguros.
- Obtener las credenciales del entorno de pruebas de las APIS de Nacional Seguros.
- Obtener las credenciales de Multipagos.

### Devobs
- Base de datos Postgres-13 (Docker)
- Server Java-11 (Docker)
- Server Nginx para mostrar la landing (Docker)
- Docker-compose que levante el entorno completo.
- Documentación en esta wiki de cómo levantar el sistema.

### Front-End
- Desarrollar la landing page y formularios (HTML5, CSS3, JavaScript)
- Enviar los datos de los formularios al server.
- Desarrollar la interfaz de la firma web.

### Back-End
- Realizar la integración con Multipagos.
- Desarrollar el servicio callback para aprobar la compra después de aprobar el callback.

- Realizar la integración con Nacional Seguros.
- Faltan los tipos de servicios que nos ofrece Nacional Seguros.
- Realizar algoritmo de validación de carnet de identidad con foto.

- Desarrollar el PDF acorde a los datos registrados.
- Firmar digitalmente e incluir tanto la firma como un código QR en un archivo PDF.
- Almacenar los PDF firmados para su posterior descarga.
- Enviar PDF por correo electrónico.
- Reporte de descargas de cada póliza (PDF)
- Envío de OTP mail.
