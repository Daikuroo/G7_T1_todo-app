# Modelo de análisis de riegos - STRIDE

| Categoría         | Riesgo detectado                               | Medida aplicada                         |
|-------------------|------------------------------------------------|-----------------------------------------|
| Spoofing          | No hay login, posible suplantación             | Planificado agregar autenticación JWT   |
| Tampering         | Usuario puede modificar datos vía API          | Validación en backend, filtros          |
| Repudiation       | No hay logging de usuarios                     | Se considera de bajo impacto            |
| Information Disclosure | Posibles errores dev exponiendo info      | Desactivado modo debug en producción    |
| Denial of Service | Bombardeo de requests                          | Limitar tamaño de payload (pending)     |
| Elevation of Privilege | No hay roles                              | Riesgo conocido, en evaluación          |
