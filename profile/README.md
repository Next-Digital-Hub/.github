# 🌐 Next Digital - Repositorios de Desarrollo

![Next Digital Logo](https://avatars.githubusercontent.com/u/174029727?s=400&u=9fb86e6550a9a7bad92221ec5845c52a78800880&v=4)

Bienvenidos al repositorio de desarrollo de **Next Digital** en GitHub. Aquí encontrarás todos los recursos, documentación y proyectos en los que estamos trabajando.

## 📁 Repositorios

Encuentra nuestros proyectos organizados en las siguientes categorías:

- **Frontend**: Proyectos de desarrollo frontend.
- **Backend**: Proyectos de desarrollo backend.
- **Workflows**: Scripts y configuraciones para despliegues y automatización.
- **Data**: Proyectos relacionados con la ciencia de datos y análisis.

## 🚀 Tecnologías Utilizadas

Nos mantenemos a la vanguardia utilizando las siguientes tecnologías y herramientas:

- **Frontend**: ![React](https://img.shields.io/badge/-React-61DAFB?logo=react&logoColor=white) ![Angular](https://img.shields.io/badge/-Angular-DD0031?logo=angular&logoColor=white) ![Vue.js](https://img.shields.io/badge/-Vue.js-4FC08D?logo=vue.js&logoColor=white)
- **Backend**: ![Spring Boot](https://img.shields.io/badge/-Spring_Boot-6DB33F?logo=spring-boot&logoColor=white) 

## 🤝 Contribuciones

Por favor, sigue las siguientes directrices para contribuir a nuestros proyectos.

### 🏷 Estructura de Ramas

Nuestro repositorio sigue una estructura de ramas específica:

- `main`: La rama principal que contiene el código en producción.
- `develop`: La rama de desarrollo donde se integran las nuevas funcionalidades y correcciones antes de pasar a `main`.

### 🌿 Nombres de Ramas

Para mantener el orden en el repositorio, utiliza los siguientes prefijos al crear una nueva rama:

- `feat/*`: Para nuevas funcionalidades.
- `feature/*`: Alternativa para nuevas funcionalidades.
- `fix/*`: Para correcciones de errores.
- `hotfix/*`: Para correcciones urgentes que necesitan ser aplicadas directamente en `main`.

### 🚀 Flujo de Trabajo

1. **Crear una Nueva Rama**: Basada en `develop` para nuevas funcionalidades y correcciones.
   - Cambia a la rama `develop`.
   - Obtén los últimos cambios de `develop`.
   - Crea una nueva rama con el prefijo adecuado, por ejemplo, `feat/nueva-funcionalidad` o `fix/correccion-de-error`.

2. **Realizar Cambios y Commits**: Realiza tus cambios y asegúrate de describir claramente lo que hiciste en los mensajes de commit.
   - Añade tus cambios.
   - Crea un commit con una descripción clara de los cambios realizados.

3. **Push de la Rama**: Sube tu rama al repositorio remoto.
   - Haz push de tu rama al repositorio remoto.

4. **Abrir un Pull Request (PR)**: Abre un PR desde tu rama hacia `develop`. Asigna al menos un validador para que revise tu código.
   - **Título del PR**: Debe ser claro y descriptivo.
   - **Descripción del PR**: Incluye detalles sobre los cambios realizados y cualquier información relevante para los revisores.

5. **Revisar y Aprobar**: Un validador revisará tu PR. Si hay comentarios o solicitudes de cambio, por favor abórdalo y realiza los ajustes necesarios.

6. **Merge**: Una vez aprobado, el PR será fusionado a `develop`.

### 🔥 Hotfixes

Para correcciones urgentes que necesitan ser aplicadas directamente en producción:

1. **Crear una Nueva Rama desde `main`**:
   - Cambia a la rama `main`.
   - Obtén los últimos cambios de `main`.
   - Crea una nueva rama con el prefijo `hotfix`, por ejemplo, `hotfix/correccion-urgente`.

2. **Realizar Cambios y Commits**:
   - Añade tus cambios.
   - Crea un commit con una descripción clara de la corrección urgente.

3. **Push de la Rama**:
   - Haz push de tu rama al repositorio remoto.

4. **Abrir un Pull Request**: Abre un PR desde tu rama `hotfix` hacia `main`.

5. **Merge Directo a `main`**: Una vez aprobado, el PR será fusionado directamente a `main`.

