# Desafío 15: Desplegar nuestro proyecto en la nube

Para ejecutar el proyecto en local necesario:

1. Ejecute el script **DBscript** para crear o resetear:

   - La tabla products y users en SQLite3.

   ```
     npm run DBscript
   ```

2. Defina las configuraciones en el archivo .env acorde al archivo .env.example

- Firebase se usa para los mensajes del chat.
- SQLite para productos y manejo de usuarios.
- MongoDB para manejar las sesiones del usuario.

3. Ejecute el siguiente script para iniciar el proyecto

   ```
     npm run dev
   ```

# HEROKU

URL: https://backend-node-felix.herokuapp.com/

Algunas capturas:

![Captura2](./img2.png)