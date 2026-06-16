# Laboratorio 01: Entorno y Herramientas de Python

## Herramientas Utilizadas

- **Poetry**: Gestión de dependencias y entornos virtuales
- **Black**: Formateador de código (PEP 8)
- **isort**: Organizador de imports
- **Ruff**: Linter para análisis estático de código
- **pre-commit**: Hooks para automatizar validaciones

### 1. Instalación de Poetry

Instalación recomendada (instalador oficial)
Windows (PowerShell):

(Invoke-WebRequest -Uri https://install.python-poetry.org -UseBasicParsing).Content | py -

Tras la instalación, añade Poetry a tu PATH. El instalador imprime la ruta exacta — normalmente $HOME/.local/bin en Linux/macOS o %APPDATA%\Python\Scripts en Windows.

Verifica la instalación:
poetry --versión

Poetry (version 2.4.1)
