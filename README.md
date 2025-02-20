# Tomas
Proyecto Tomas - página web
video presentación del proyecto: https://ucoc-my.sharepoint.com/:v:/g/personal/macarmur624e_linkiafp_online/ETinkm8u_qVPgSBFrZKsuVcBCRXWldzvERtkKSpiGypkRw?e=6Jh3bi
# Proyecto Web de Cargadores Eléctricos

Este proyecto es una plataforma web que permite a los usuarios registrarse, iniciar sesión, gestionar su perfil y encontrar cargadores eléctricos cercanos a su ubicación mediante la geolocalización. Está desarrollado con **PHP**, **MySQL** y **Bootstrap 5**.

Video funcionalidad página web: https://youtu.be/6K-M6ekNb40

## Características principales
- **Registro y autenticación de usuarios**: Los usuarios pueden registrarse con su correo electrónico, nombre, apellidos, fecha de nacimiento y teléfono. Las contraseñas se almacenan de forma segura utilizando **bcrypt**.
- **Área reservada**: Una vez que el usuario inicia sesión, accede a su perfil, donde puede ver y editar su información personal.
- **Cargadores cercanos**: El sistema muestra cargadores eléctricos cercanos utilizando las coordenadas geográficas del usuario, con un radio de búsqueda de 50 km.
- **Diseño responsivo**: La interfaz de usuario es completamente responsiva, construida con **Bootstrap 5**.
  
## Configuración en GitHub

Para comenzar con este proyecto, sigue estos pasos:

### 1. Clonar el repositorio:
```bash
git clone https://github.com/Mirel/Tomas.git

2. Instalar dependencias:
Asegúrate de tener un servidor local de PHP como XAMPP o MAMP para ejecutar el proyecto.
Configura una base de datos MySQL en tu servidor local.
Crea una base de datos con el nombre que prefieras y usa las tablas y campos proporcionados en la documentación del proyecto.
3. Configurar el archivo conexion.php:
Abre el archivo conexion.php y actualiza las credenciales de la base de datos con tus propios valores (usuario, contraseña, nombre de la base de datos, etc.).
4. Crear la base de datos y tablas:
Crea las tablas necesarias (usuarios y ubicaciones_cargadores) en tu base de datos. Puedes encontrar la estructura de las tablas en la documentación proporcionada en el proyecto.
5. Añadir la clave API de Goolge maps en index.php
6. Iniciar el servidor PHP:
Ejecuta el servidor PHP en tu entorno local para comenzar a probar la aplicación.
7. Acceder a la aplicación:
Una vez que el servidor esté en funcionamiento, abre tu navegador y accede a http://localhost:8888 para ver la página de inicio del proyecto.


