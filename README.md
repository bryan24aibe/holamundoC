# Hello World in ASP.NET Core

This project is a simple "Hello World" web application developed in **ASP.NET Core**. It displays a welcome message on the home page.

## Project Contents

The project includes the following main files and folders:

- **Pages/Index.cshtml**: Main page that displays the message "Welcome soy Lara Bryan".
- **Pages/Privacy.cshtml**: Privacy page.
- **wwwroot/**: Folder for static files (CSS, JavaScript, etc.).
- **appsettings.json**: Configuration file for the application.
- **Program.cs**: Application entry point.
- **Dockerfile**: Configuration file for Docker containers.

## Prerequisites

To run this project, you need:

- **.NET SDK** (version 6.0 or higher)
- **Visual Studio** (recommended) or **Visual Studio Code**
- Optional: **Docker** to run the application in a container

## Running the Application

1. Clone the repository or download the source code.
2. Open the project in Visual Studio or your preferred IDE.
3. Run the project by pressing **F5** or selecting "Run".

## Running in Docker

1. Ensure Docker is installed and running.
2. Open a terminal in the project folder.
3. Build the Docker image:

   ```bash
   docker build -t hello-world-aspnet .
   ```

4. Run the container:

   ```bash
   docker run -p 8080:80 hello-world-aspnet
   ```

5. Open your browser and go to `http://localhost:8080` to view the application.

## Customization

To change the welcome message, edit the `Index.cshtml` file in the **Pages** folder. Find the line:

```html
<h1 class="display-4">Welcome soy Lara Bryan</h1>
```

and replace the text `"Welcome soy Lara Bryan"` with the message you want.

