# Parcial 2

### Configuraci贸n inicial 馃敡

1. Realizar el fork del repositorio

2. Clonar el repositorio

3. Instalar npm modules (en el root)

   ```bash
   npm install
   ```

4. Instalar npm modules (dentro de carpeta _frontreact_)

   ```bash
   cd frontreact
   npm install
   ```

5. Ejecutar servidor (nodemon, servidor de archivos est谩ticos). Ubicado en el root del repositorio ejecutar:

   ```bash
   npm run start
   ```

   El anterior comando desplegar谩 el backend de la aplicaci贸n en el puerto 3001. Ir **http://localhost:3001/img/products/N0CA_430.png** deber铆a ver una imagen de un producto el cual est谩 expuesta por el servidor.

6. Ejecutar servidor de desarrollo para react. Ubicado en el directorio _frontreact_ ejecutar:

   ```bash
   npm run start
   ```

   El anterior comando desplegar谩 el frontend de la aplicaci贸n en el puerto 3000. Ir **http://localhost:3000/home** deber铆a ver la p谩gina principal de la aplicaci贸n en react.

7. Si desea ejecutar la aplicaci贸n en modo producci贸n. Siga los siguientes pasos:

- Ubicarse sobre el directorio _frontreact_ y ejecutar:
  ```bash
  npm run build
  ```
- Luego, sobre el root del repositorio ejecutar:
  ```bash
  npm run start
  ```
- Ahora al ingresar a **http://localhost:3001** deber铆a observar la aplicaci贸n en react.

_Jhonatan Alarc贸n._
