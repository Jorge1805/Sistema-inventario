# Configuración de herramientas

| Herramienta | Versión | Configuración | Propósito |
|---|---|---|---|
| Git | _completar_ | user.name, user.email, rama inicial `main` | Control de versiones |
| GitHub | N/A | Repositorio privado, `main` protegida | Almacenamiento y revisión |
| VS Code | _completar_ | Extensiones: Python, Pylance, Docker, GitLens | Desarrollo |
| Python + pytest | _completar_ | `requirements.txt` | Pruebas |
| Docker | _completar_ | Imagen `python:3.12-slim` | Contenedorización |
| GitHub Actions | N/A | `.github/workflows/ci.yml` | Integración continua |
| Trello | N/A | Tablero Kanban | Gestión del proyecto |

```bash
git config --global user.name "Nombre Apellido"
git config --global user.email "correo@ejemplo.com"
git config --global init.defaultBranch main
```
