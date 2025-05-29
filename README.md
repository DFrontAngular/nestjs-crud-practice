# Proyecto de Backend en NestJS - CRUD de Coches

Este proyecto es un backend desarrollado en NestJS que permite la creación, lectura, actualización y eliminación (CRUD) de coches, incluyendo marcas, modelos y detalles de los mismos.

Además, cuenta con documentación Swagger disponible en http://localhost:3000/api-docs.

## Requisitos

- Node.js (LTS)

## Instalación

1. Clonar el repositorio:

   ```bash
   git clone git@github.com:DFrontAngular/nestjs-crud-practice.git
   ```

2. Instalar las dependencias:

   ```bash
   npm install
   ```

3. Levantar el servidor en local:
   ```bash
    npm start
   ```


### **Autenticación**

Para que la API funcione correctamente, es necesario almacenar en el `localStorage` un token de autenticación (ya que no vamos a desarrollar un login, porque se sale del objetivo de la práctica).  
Este token debe utilizarse en cada petición como un **Bearer Token** en la cabecera `Authorization`.

### **Instrucciones:**

1. Abre la consola del navegador (`F12`) y accede a la pestaña **Application**.
2. En la sección **Local Storage**, selecciona el dominio de la aplicación.
3. Añade una nueva clave con el siguiente formato:

   - **Clave:** `auth-token`
   - **Valor:** `"mock-token"`

   También puedes hacerlo mediante la consola ejecutando:

   ```javascript
   localStorage.setItem("auth-token", "mock-token");
   ```
