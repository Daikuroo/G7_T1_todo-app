# Consideraciones de Seguridad en Docker

- Contenedores no usan root: ✔️
- Variables sensibles no están hardcodeadas
- `.env` excluido del repositorio
- Solo se expone el puerto necesario (8080)
- Uso de volúmenes controlado
