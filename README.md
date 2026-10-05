# Sistema de Control de Inventario

Sistema para registrar, consultar, modificar y eliminar productos, consultar existencias, registrar entradas/salidas y generar un reporte básico de inventario.

> Estado: entorno DevOps configurado. El código fuente se desarrollará en `src/`.

## Estructura
- `docs/`: configuración, plan de pruebas, casos de prueba y despliegue
- `src/`: código fuente
- `tests/`: pruebas automatizadas (pytest)
- `.github/workflows/`: integración continua (GitHub Actions)

## Flujo de trabajo
`main` (estable) ← `release` ← `develop` ← `feature/*`. Todo cambio entra por Pull Request con revisión.

## Ejecutar pruebas
```bash
pip install -r requirements.txt
pytest
```

## Docker
```bash
docker build -t sistema-inventario .
docker run sistema-inventario
```

## Equipo
- Jorge Eduardo Estrada Soto
- [Integrante 2]
- [Integrante 3]
