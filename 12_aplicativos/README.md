# Aplicativos

**Bloque:** Producto y tecnología

Código fuente y documentación técnica de cada aplicativo del sistema.

## Subcarpetas

| Carpeta | Contenido |
|---|---|
| `00_documentacion_tecnica/` | Arquitectura, diagramas, registro de decisiones técnicas, especificación de la API. |
| `app_movil/` | App para tablet y celular (iOS y Android). Producto principal: debe funcionar sin internet. |
| `backend_api/` | Servidor: cuentas, sincronización y respaldo de tableros, licencias. |
| `base_datos/` | Modelo de datos, migraciones, scripts y datos semilla (vocabulario base). |
| `frontend_web/` | Portal web para familias y terapeutas: editar tableros y ver el progreso. |
| `panel_administracion/` | Backoffice interno: usuarios, licencias, contenidos. |
| `pagina_web/` | Sitio institucional y landing de descarga. |
| `infraestructura_devops/` | Nube, integración y despliegue continuo (CI/CD), monitoreo. |
| `qa_pruebas/` | Planes de prueba, pruebas automatizadas, reportes de errores. |

## Notas

- La estructura interna de cada aplicativo (src, tests, etc.) la define el framework elegido al iniciar su desarrollo.
- Nunca subir claves, contraseñas ni archivos `.env` al repositorio.
