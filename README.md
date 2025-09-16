# Prueba_vistaBlazor

Una aplicación Blazor .NET 8 de demostración con páginas interactivas.

## Características

- **Home**: Página de inicio con mensaje de bienvenida
- **Counter**: Página interactiva con contador que se puede incrementar
- **Weather**: Página que muestra datos meteorológicos de ejemplo en una tabla

## Requisitos

- .NET 8.0 SDK o superior

## Cómo ejecutar

1. Clonar el repositorio:
```bash
git clone https://github.com/JuanVasquez2025/Prueba_vistaBlazor.git
cd Prueba_vistaBlazor
```

2. Restaurar las dependencias:
```bash
dotnet restore
```

3. Compilar la aplicación:
```bash
dotnet build
```

4. Ejecutar la aplicación:
```bash
dotnet run
```

5. Abrir el navegador y navegar a `https://localhost:5001` o `http://localhost:5000`

## Tecnologías utilizadas

- ASP.NET Core 8.0
- Blazor Server
- Bootstrap CSS
- C# 12

## Estructura del proyecto

- `Components/`: Contiene todos los componentes Blazor
  - `Pages/`: Páginas de la aplicación (Home, Counter, Weather)
  - `Layout/`: Componentes de diseño y navegación
- `wwwroot/`: Archivos estáticos (CSS, JavaScript, imágenes)
- `Program.cs`: Punto de entrada de la aplicación