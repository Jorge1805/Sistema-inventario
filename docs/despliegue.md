# Estrategia de despliegue

| Elemento | Descripción |
|---|---|
| Estrategia | Blue/Green |
| Ambiente | Desarrollo (Docker local) → Pruebas (GitHub Actions) → Producción (Blue y Green) |
| Proceso | Merge a `main` → CI → imagen Docker → despliegue en Green → pruebas de humo → cambio de tráfico a Green → Blue queda de respaldo |
| Riesgos | Costo de dos ambientes; sincronización de base de datos; cambios de esquema incompatibles |
| Ventajas | Sin tiempo de inactividad; regreso inmediato a la versión anterior |
| Recuperación | Regresar el tráfico a Blue, revisar logs, corregir en `fix/*` y repetir; respaldo de BD antes de cada versión |
