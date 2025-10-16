Programa: Tecnología en Desarrollo de Sistemas Informáticos
Periodo: II Semestre 2025
Profesor: Mag. Carlos Adolfo Beltrán Castro
Estudiantes: JHAN CARLO SANABRIA VEGA 1005282536



Sistema Administrativo “Gym UTS”


El proyecto “Gym UTS” consiste en el desarrollo de un sistema administrativo para la gestión de un gimnasio.
Está construido utilizando Spring Boot y Thymeleaf, con conexión a una base de datos MySQL,
implementando un diseño web moderno, intuitivo y funcional.

El sistema permite la gestión de socios, entrenadores, membresías y pagos,
además de ofrecer un panel administrativo con menús interactivos y cierre de sesión.

Entre sus características principales se encuentran:

Login de administrador.

CRUD completo para Socios y Entrenadores.

Visualización profesional de Membresías y Pagos.

Con conexión a base de datos.

Control de sesión con redirección al inicio de sesión.
----------------------------------------------------------------------------------------
📋 Menú principal

🧍‍♂️ Socios: CRUD con conexión a base de datos.

🏋️‍♂️ Entrenadores: CRUD funcional.

💳 Pagos: panel dinámico enlazado con la base de datos, gráfico estadístico.

💼 Membresías: vista informativa con imágenes de los planes disponibles.

🚪 Cerrar sesión: mensaje visual de confirmación de cierre de sesión.

--------------------------------------------------------------------------------------------


Carpetas del proyecto

src/main/java/.../controlador → Controladores del sistema.

src/main/java/.../modelo → Entidades JPA (Socio, Entrenador, Pago, Membresía, etc.).

src/main/java/.../repositorio → Interfaces JpaRepository para la conexión con MySQL.

src/main/resources/templates → Vistas Thymeleaf (HTML).

--------------------------------------------------------------------------------------------


Base de Datos: gymdb
🔹 Tablas Principales

socio: almacena la información de los miembros registrados.

entrenador: gestiona los instructores y sus especialidades.

pago: registra los montos, fechas y estados de los pagos.

membresia: define los tipos de planes (básico, premium, VIP).

-----------------------------------------------------------------------------------------------


Tecnologías Utilizadas

Tecnología	
Java 17	
Spring Boot 3	
Thymeleaf	
Bootstrap 5	
MySQL	Base de datos relacional
------------------------------------------------------------------------------------------------

  
