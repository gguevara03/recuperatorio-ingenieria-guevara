# recuperatorio-ingenieria-guevara

## Descripción

Proyecto simple que implementa un CRUD básico de tareas usando HTML, CSS y JavaScript puro. Permite agregar, eliminar y visualizar tareas en una lista.

## Requerimientos Funcionales

- Permitir al usuario agregar tareas.
- Permitir eliminar tareas.
- Visualizar la lista actual de tareas en pantalla.

## Requerimientos No Funcionales

- Interfaz simple y responsive.
- Código organizado dentro de la carpeta `/src`.

## Docker

Incluye un `Dockerfile` para servir el proyecto mediante Nginx dentro de un contenedor.

## Cómo correr el proyecto con Docker

```bash
docker build -t tareas-app .
docker run -d -p 8080:80 tareas-app
```

Para ver el contenedor en ejecución, usa:

```bash
docker ps
```

Luego, abre tu navegador y visita [http://localhost:8080](http://localhost:8080) para ver la aplicación.