# HTML, CSS y JavaScript para Periodistas

Este proyecto tiene como objetivo enseñar a periodistas los fundamentos de HTML, CSS y JavaScript a través de lecciones interactivas en línea, con soporte para dos idiomas: inglés y español.

## Requisitos Previos

Asegúrate de tener instalado lo siguiente en tu sistema:

- [Node.js](https://nodejs.org/en/) (v14.17.0 o superior)
- [npm](https://www.npmjs.com/) (v6.14.13 o superior)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Git](https://git-scm.com/)

## Configuración del Proyecto

Sigue los pasos a continuación para configurar el entorno de desarrollo:

### 1. Clonar el Repositorio

Primero, clona el repositorio del proyecto en tu máquina local:

```bash
git clone https://github.com/sil7en/html-css-js-course.git
cd html-css-js-para-periodistas
```

### 2. Instalación de Dependencias

Instala las dependencias del proyecto utilizando `npm`:

```bash
npm install
```

### 3. Configuración de TailwindCSS

TailwindCSS ya está instalado y configurado en el proyecto. No es necesario hacer pasos adicionales para la configuración. Si deseas personalizarlo, revisa el archivo `tailwind.config.js`.

### 4. Iniciar el Servidor de Desarrollo

Para iniciar el servidor de desarrollo, ejecuta el siguiente comando:

```bash
npm run dev
```

Abre tu navegador y navega a `http://localhost:3000` para ver el sitio en ejecución.

### 5. Configuración de PostgreSQL

Sigue los pasos para configurar PostgreSQL en tu máquina local:

1. Instala PostgreSQL desde [aquí](https://www.postgresql.org/download/).
2. Crea una base de datos llamada `html_css_js_db` ejecutando el siguiente comando en la CLI de PostgreSQL:

    ```bash
    createdb html_css_js_db
    ```

Asegúrate de que PostgreSQL esté corriendo y listo para la integración con el backend en etapas futuras.


### 6. Creación del archivo .env

Para que el entorno funcione correctamente, es necesario crear un archivo `.env` en la raíz del proyecto. En este archivo, deberás definir las variables de entorno necesarias para la configuración del proyecto. Un ejemplo de contenido de `.env` podría ser:

```bash
DATABASE_URL=postgresql://usuario:contraseña@localhost:5432/html_css_js_db
```

### 7. Despliegue en Vercel

Este proyecto está configurado para desplegarse automáticamente en [Vercel](https://vercel.com/). Para hacer un despliegue continuo:

1. Conéctate a Vercel y enlaza tu cuenta de GitHub.
2. Importa el repositorio `html-css-js-course` en tu dashboard de Vercel.
3. Vercel automáticamente desplegará tu proyecto. Puedes ver el sitio en la URL proporcionada por Vercel.

### 8. Contribuir

Si deseas contribuir a este proyecto, sigue los siguientes pasos:

1. Crea una rama nueva desde `main`:

   ```bash
   git checkout -b feature/nueva-funcionalidad
   ```

2. Haz tus cambios y commitea tus actualizaciones:

   ```bash
   git add .
   git commit -m "Añadir nueva funcionalidad"
   ```

3. Sube tus cambios al repositorio remoto:

   ```bash
   git push origin feature/nueva-funcionalidad
   ```

4. Abre un Pull Request en GitHub.

---

## Futuras Implementaciones

- Integración de un editor de código interactivo con validación en línea.
- Sistema de lecciones multilingües (inglés y español).
- Optimización SEO para mejorar la indexación en motores de búsqueda.

## Licencia

Este proyecto está bajo la licencia MIT.


# HTML, CSS, and JavaScript for Journalists

This project aims to teach journalists the basics of HTML, CSS, and JavaScript through interactive online lessons, with support for two languages: English and Spanish.

## Prerequisites

Make sure you have the following installed on your system:

- [Node.js](https://nodejs.org/en/) (v14.17.0 or higher)
- [npm](https://www.npmjs.com/) (v6.14.13 or higher)
- [PostgreSQL](https://www.postgresql.org/download/)
- [Git](https://git-scm.com/)

## Project Setup

Follow the steps below to set up the development environment:

### 1. Clone the Repository

First, clone the project repository to your local machine:

```bash
git clone https://github.com/sil7en/html-css-js-course.git
cd html-css-js-course
```

### 2. Install Dependencies

Install the project dependencies using `npm`:

```bash
npm install
```

### 3. TailwindCSS Setup

TailwindCSS is already installed and configured in the project. No additional setup steps are required. If you want to customize it, check the `tailwind.config.js` file.

### 4. Start the Development Server

To start the development server, run the following command:

```bash
npm run dev
```

Open your browser and navigate to `http://localhost:3000` to see the site in action.

### 5. PostgreSQL Setup

Follow these steps to set up PostgreSQL on your local machine:

1. Install PostgreSQL from [here](https://www.postgresql.org/download/).
2. Create a database named `html_css_js_db` by running the following command in the PostgreSQL CLI:

    ```bash
    createdb html_css_js_db
    ```

Make sure PostgreSQL is running and ready for backend integration in future stages.


### 6. Create the .env File

To ensure the environment works correctly, create a `.env` file in the root of the project. In this file, you should define the environment variables necessary for configuring the project. An example `.env` content could be:

```bash
DATABASE_URL=postgresql://user:password@localhost:5432/html_css_js_db
```

### 7. Deployment on Vercel

This project is set up for automatic deployment on [Vercel](https://vercel.com/). To set up continuous deployment:

1. Connect to Vercel and link your GitHub account.
2. Import the `html-css-js-course` repository into your Vercel dashboard.
3. Vercel will automatically deploy your project. You can view the site at the URL provided by Vercel.

### 8. Contributing

If you want to contribute to this project, follow these steps:

1. Create a new branch from `main`:

   ```bash
   git checkout -b feature/new-feature
   ```

2. Make your changes and commit your updates:

   ```bash
   git add .
   git commit -m "Add new feature"
   ```

3. Push your changes to the remote repository:

   ```bash
   git push origin feature/new-feature
   ```

4. Open a Pull Request on GitHub.

---

## Future Implementations

- Integration of an interactive code editor with real-time validation.
- Multilingual lesson system (English and Spanish).
- SEO optimization to improve search engine indexing.

## License

This project is licensed under the MIT License.
