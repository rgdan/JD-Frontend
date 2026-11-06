# JustDoIt Frontend

Interfaz para gestionar usuarios y tareas, hecha con HTML, CSS y JavaScript.

## Ejecutar localmente

1. Inicie el backend en `http://localhost:8080` con CORS habilitado.
2. Desde la carpeta `JD-Frontend`, ejecute (requiere Python 3):

   ```sh
   python3 -m http.server 5500
   ```

3. Abra `http://localhost:5500` en el navegador y cree un usuario o ingrese con uno existente.

La dirección del backend se configura en `BASE_URL`, en `js/api.js`.
