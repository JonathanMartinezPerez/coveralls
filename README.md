# Integración continua y cubrimiento del código con Vitest, Coveralls y GitHub Actions

En este repositorio se ilustra la configuración de dos flujos de trabajo de GitHub:

1. El primer flujo de trabajo permite llevar a cabo integración continua, ejecutando las pruebas con diferentes
versiones de Node.js cada vez que se lleva a cabo un *push* o *pull request* en la rama main.
2. El segundo flujo de trabajo permite llevar a cabo el cubrimiento del código fuente e integrándolo con
Coveralls, una herramienta que permite ir registrando un histórico de cubrimiento.

[![Tests](https://github.com/JonathanMartinezPerez/coveralls/actions/workflows/ci.yml/badge.svg)](https://github.com/JonathanMartinezPerez/coveralls/actions/workflows/ci.yml)
[![Coverage Status](https://coveralls.io/repos/github/JonathanMartinezPerez/coveralls/badge.svg?branch=main)](https://coveralls.io/github/JonathanMartinezPerez/coveralls?branch=main)
