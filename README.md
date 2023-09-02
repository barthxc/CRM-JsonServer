# Documentación del Proyecto CRM con JSON Server

Documentación de la práctica de un proyecto usando JSON Server, CRUD y funciones asíncronas

Esta documentación proporciona información detallada sobre el proyecto de CRM basado en JSON Server. Aquí, aprenderás cómo desplegar el servidor JSON y cómo funciona la aplicación.

## Requisitos Previos

Asegúrate de tener instalado Node.js en tu sistema. Puedes descargarlo desde [nodejs.org](https://nodejs.org/).

## Instalación

1. Clona o descarga el proyecto desde el repositorio.

```bash
git clone <URL_del_repositorio>
cd proyecto-crm-json-server
```

2. Instala las dependncias del proyecto
   ```bash
   npm install -g json-server
   ```

# Despligue de JSON Server
El servidor JSON se utiliza para almacenar y gestionar los datos de la aplicación CRM. Sigue estos pasos para desplegar el servidor JSON:
1. Asegúrate de estar en el directorio raíz del proyecto.
2. Crea un archivo llamado __db.json__ en el directorio raíz del proyecto. Este archivo contendrá los datos de tu aplicación CRM.
3. Inicia el servidor JSON con el siguiente comando:
   ```bash
   npx json-server --watch db.json --port 4000
   ```
Esto iniciará el servidor JSON en el puerto 4000 y estará listo para recibir solicitudes.

# Uso de la Aplicación
Para usar la aplicación CRM, abre un navegador web y accede a la URL donde se encuentra desplegada la aplicación. Puedes realizar las siguientes acciones:

-Ver la lista de clientes.
-Editar clientes existentes.
-Agregar nuevos clientes.
# Conclusiones
Este documento proporciona una visión general del proyecto de CRM basado en JSON Server, incluyendo los comandos para desplegar el servidor JSON. Para obtener más detalles sobre el funcionamiento de la aplicación, consulta el código fuente.

!Disfruta de tu aplicación CRM!
Documentación hecha en __ChatGPT__
