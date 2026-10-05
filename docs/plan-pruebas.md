# Plan de pruebas

- **Objetivo:** verificar que las funciones principales del sistema de inventario operen de acuerdo con los requisitos.
- **Alcance:** productos (alta, consulta, modificación, baja), existencias, entradas/salidas y reporte básico. No incluye rendimiento ni seguridad avanzada.
- **Elementos a probar:** módulo de productos, módulo de movimientos, cálculo de existencias, validación de datos, reporte.
- **Tipos de pruebas:** funcionales, de integración, de validación de datos y de regresión.
- **Criterios de aceptación:** cada función cumple su requisito; los datos inválidos se rechazan con mensaje claro; las existencias reflejan entradas y salidas.
- **Aprobación/rechazo:** Aprobada si el resultado obtenido coincide con el esperado; No aprobada en caso contrario. Se libera con 100 % de casos críticos aprobados y CI en verde.
- **Ambiente:** local con Python/pytest, contenedor Docker y GitHub Actions (Ubuntu).
- **Responsables:** [Integrante 1], [Integrante 2], [Integrante 3].
- **Herramientas:** pytest, GitHub Actions, Docker, Git/GitHub.
