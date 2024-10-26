# Pipeline de CI con GitHub Actions para la Aplicación Todoism

Este repositorio ejemplifica cómo configurar un pipeline de Integración Continua (CI) con **GitHub Actions**, que ejecuta pruebas automatizadas desde un repositorio externo utilizando **Playwright**. Las pruebas verifican las funcionalidades de la aplicación Todo, como:

1. **Creación de tareas**
2. **Marcar una tarea como completada**
3. **Limpiar las tareas**

Las pruebas se obtienen del repositorio [todoism-test](https://github.com/MateoEcheverriPelaez/todoism-test.git) y se ejecutan dentro de este pipeline de CI.