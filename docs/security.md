# Consideraciones de Seguridad

Durante el desarrollo del proyecto, se tomaron las siguientes medidas de seguridad:

### Backend
- **Validación de entradas**: Se aseguraron de que todas las entradas de usuario pasen por validaciones (como en `express-validator`) para prevenir inyecciones SQL o XSS.
- **Autenticación**: Uso de JWT para autenticación de usuarios.
  
### Frontend
- **Protección CSRF**: Se implementaron cabeceras para proteger contra ataques Cross-Site Request Forgery.
  
### Docker
- **Docker Security Best Practices**: El proyecto está aislado en contenedores para limitar el impacto de vulnerabilidades.
