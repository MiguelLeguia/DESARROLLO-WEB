# DESARROLLO-WEB
Aplicación web desarrollada con Spring Boot + React que permite el registro, autenticación y gestión de usuarios (clientes y vendedores).
________________________________________
🛠 Tecnologías
Backend:
•	Java
•	Spring Boot
•	Spring Security
•	Maven
Frontend:
•	React
•	JavaScript
•	HTML / CSS

⚙️ Requisitos
Antes de ejecutar el proyecto necesitas:
•	Java JDK 17 o superior
•	Node.js
•	npm o yarn
•	Maven

▶️ Ejecución del Backend
1.	Ir a la carpeta:
cd backend
2.	Ejecutar:
mvn spring-boot:run
O en Windows:
mvnw spring-boot:run
El backend correrá en:
http://localhost:8080

▶️ Ejecución del Frontend
1.	Ir a la carpeta:
cd frontend/mitienda
2.	Instalar dependencias:
npm install
3.	Ejecutar:
npm start
El frontend correrá en:
http://localhost:3000

🔗 Conexión Backend - Frontend
El frontend consume los servicios REST del backend mediante HTTP.
Asegúrate de que:
•	El backend esté corriendo en el puerto 8080
•	CORS esté habilitado (ya configurado en el proyecto)

👥 Funcionalidades
•	Registro de usuarios
•	Login
•	Gestión de clientes y vendedores
•	Seguridad con autenticación

📂 Estructura
EpigeneticaProyecto/
 ├── backend/
 └── frontend/

🧠 Autor
Proyecto desarrollado como práctica académica para integración de tecnologías web modernas.

📌 Notas
•	Revisar application.properties para configuración de base de datos
•	Se puede adaptar fácilmente a MySQL u otra BD
•	Ideal para proyectos tipo tienda o sistema de usuarios
