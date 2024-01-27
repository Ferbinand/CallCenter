# Call Center de Servicios Técnicos - Aplicación en C# .NET

Bienvenido/a a nuestra aplicación de gestión de call center diseñada para servicios técnicos y atención al cliente. Esta aplicación proporciona una plataforma integral para registrar reclamos, mantener una bitácora de su avance, y gestionar perfiles de clientes, usuarios, supervisores y administradores.

## Características Principales

- **Registro de Reclamos:** Permite a los agentes del call center registrar los reclamos de los clientes, proporcionando detalles clave y prioridades.

- **Bitácora de Reclamos:** Mantiene un historial detallado de cada reclamo, incluyendo actualizaciones, acciones tomadas y el estado actual.

- **Gestión de Perfiles:** La aplicación incluye varios perfiles con distintos niveles de acceso, como clientes, usuarios del call center, supervisores y administradores.

- **Alta/Baja de Usuarios:** Facilita la administración de usuarios permitiendo la creación y desactivación de cuentas según sea necesario.

- **Registro de Clientes:** Permite el registro y mantenimiento de información de clientes, facilitando la identificación y seguimiento de los reclamos asociados a cada cliente.

## Requisitos del Sistema

- **Plataforma:** La aplicación está desarrollada en C# .NET y requiere el entorno de ejecución .NET Framework.

- **Base de Datos:** Utiliza [CALL_CENTER], se proporciona un script de creación de la base de datos para pruebas.

## Instalación

1. Clone el repositorio: `git clone https://github.com/Ferbinand/CallCenter`

2. Abra la solución en Visual Studio.

3. Compile la solución y asegúrese de que todas las dependencias se descarguen automáticamente.

4. Ejecute el script de creación de la base de datos en su servidor SQL.

5. Configure la cadena de conexión en el archivo de configuración de la aplicación (`App.config` o similar).

6. Ejecute la aplicación desde Visual Studio o implemente el archivo ejecutable en su servidor.

## Uso

1. Inicie sesión con las credenciales proporcionadas según su perfil (cliente, usuario, supervisor, administrador).

2. Explore las diferentes funcionalidades según su perfil.

3. Registre nuevos reclamos, actualice el estado de los reclamos existentes y gestione perfiles según sea necesario.

