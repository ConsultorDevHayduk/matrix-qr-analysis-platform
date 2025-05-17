# Matrix QR Analysis Platform

Plataforma compuesta por microservicios para autenticación, análisis de códigos QR y factorización, desplegada sobre AWS Elastic Beanstalk. Esta arquitectura permite la separación de responsabilidades y escalabilidad de los servicios.

## 🧩 Microservicios

### 1. Autenticación

- **URL:** [`/security/login`](http://matrix-auth-api-env.eba-yj3dc7sn.us-east-2.elasticbeanstalk.com/security/login)
- **Descripción:** Servicio de autenticación de usuarios.

### 2. Factorización

- **URL:** [`/api/factorizar`](http://matrixes-qr-api-env.eba-qpvrkhgb.us-east-2.elasticbeanstalk.com/api/factorizar)
- **Descripción:** Servicio para el análisis y factorización de cadenas provenientes de códigos QR.

### 3. Análisis de QR

- **URL:** [`/api/analyze`](http://qr-analysis-api-env.eba-6uiu9zvq.us-east-2.elasticbeanstalk.com/api/analyze)
- **Descripción:** Servicio de procesamiento y análisis de datos obtenidos desde códigos QR.

