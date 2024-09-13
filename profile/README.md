# Emisión de Seguros

Este proyecto tiene como objetivo desarrollar una plataforma web que permita la emisión de pólizas de seguro de manera ágil y segura. La solución está diseñada para ser accesible desde cualquier dispositivo, proporcionando una experiencia de usuario fluida y optimizada.

El sistema integrará formularios interactivos para la captura de datos del cliente, verificación de identidad, y validación de información mediante servicios web provistos por Nacional Seguros. Además, se incluirán características de generación automática de documentos como pólizas y facturas, firmadas digitalmente y acompañadas de códigos QR para su validación.

Uno de los componentes clave del proyecto es la integración de una pasarela de pago, que permitirá procesar transacciones de manera eficiente y segura. El proceso de emisión incluirá también la autenticación del cliente mediante OTP (One-Time Password) y el almacenamiento seguro de sus datos.

Este desarrollo está pensado para facilitar el proceso de contratación de seguros, asegurando el cumplimiento de las normativas y la trazabilidad de cada transacción mediante la generación de identificadores únicos en cada paso.

## Antecedentes

Puedes ver como inició el proyecto [aquí](https://github.com/Nacional-Seguros/.github/wiki/Antecedentes).

## Presupuesto

- Precio $us 12.500
- Se entragarán todos los códigos en este repositorio.
- 2 Meses de desarrollo + 1 mes pruebas

### Project Manager
- Agendar cita con multipagos para que nos asignen un agente
- Recopilar las APIS de Nacional Seguros
- Obtener las credenciales del entorno de pruebas de las APIS de Nacional Seguros
- Obtener las credenciales de multipagos

### Devobs
- Base de datos postgres-13 (Docker)
- Server Java-11 (Docker)
- Server Nginx para mostrar la landing (Docker)
- Docker-compose que levante el entorno completo.
- Documentación en esta wiki de como levantar el sistema.

### Front-End
- Desarrollar la landing page y formluarios (Html, css, java-script)
- Enviar los datos en de los formularios al server.
- Desarrollar la interfaz de la firma web.

### Back-End
- Realizar la integración con multipagos.
- Desarrollar el servicio callback para aprobar la compra despues de apribar el callback.

- Realiar la integracion con Nacional Seguros.
- <Faltan los tipos de servicios que nos ofece nacional seguros>
- Realizar algoritmo de validacion de carnet de identidad con foto.

- Desarrollar el PDF acorde a los datos registrados.
- Firmar con una firma digital y agregar un qr al pdf.
- Almacenar los pdf firmados apra su posterior descarga.


