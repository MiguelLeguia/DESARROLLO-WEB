# DESARROLLO-WEB

Aplicación web desarrollada con **Spring Boot + React** para la gestión de usuarios, autenticación y administración de clientes y vendedores.

---

# 🚀 Tecnologías Utilizadas

## Backend

* Java 17
* Spring Boot
* Spring Security
* Maven
* REST API

## Frontend

* React
* JavaScript
* HTML5
* CSS3

---

# 📋 Requisitos Previos

Antes de ejecutar el proyecto debes tener instalado:

* Java JDK 17 o superior
* Node.js
* npm o yarn
* Maven
* Git

---

# ⚙️ Instalación del Proyecto

## 1️⃣ Clonar el repositorio

```bash
git clone https://github.com/MiguelLeguia/DESARROLLO-WEB.git
```

---

# ▶️ Ejecución del Backend

Ir a la carpeta backend:

```bash
cd backend
```

Ejecutar el proyecto:

```bash
mvn spring-boot:run
```

En Windows también puedes usar:

```bash
mvnw spring-boot:run
```

El backend se ejecutará en:

```bash
http://localhost:8080
```

---

# ▶️ Ejecución del Frontend

Ir a la carpeta frontend:

```bash
cd frontend/mitienda
```

Instalar dependencias:

```bash
npm install
```

Ejecutar el frontend:

```bash
npm start
```

El frontend se ejecutará en:

```bash
http://localhost:3000
```

---

# 🔗 Integración Backend - Frontend

El frontend consume los servicios REST desarrollados en Spring Boot.

Verifica que:

* El backend esté ejecutándose en el puerto 8080
* El frontend esté ejecutándose en el puerto 3000
* CORS esté habilitado correctamente

---

# 👥 Funcionalidades

✅ Registro de usuarios
✅ Inicio de sesión (Login)
✅ Gestión de clientes
✅ Gestión de vendedores
✅ Seguridad y autenticación
✅ Consumo de API REST
✅ Arquitectura Frontend + Backend separada

---

# 📂 Estructura del Proyecto

```bash
DESARROLLO-WEB/
│
├── backend/
│   ├── src/
│   ├── pom.xml
│
├── frontend/
│   └── mitienda/
│
└── README.md
```

---

# 🗄 Configuración de Base de Datos

La configuración de la base de datos se encuentra en:

```bash
backend/src/main/resources/application.properties
```

El proyecto puede adaptarse fácilmente para:

* MySQL
* PostgreSQL
* SQL Server
* H2 Database

---

# 📌 Recomendaciones

* Ejecutar primero el backend y luego el frontend
* Verificar que los puertos 8080 y 3000 estén libres
* Mantener actualizadas las dependencias de Node y Maven

---

# 🧠 Autor

Proyecto desarrollado por **Miguel Ángel Leguía** como práctica académica de integración de tecnologías web modernas.

---

# 📄 Licencia

Proyecto de uso académico y educativo.

# 🗄 Base de Datos

La base de datos MySQL se encuentra en la carpeta:

```bash id="q4qj2p"
database/
```

Para importar la base de datos:

1. Abrir MySQL Workbench
2. Ir a `Server > Data Import`
3. Seleccionar el archivo `.sql`
4. Ejecutar la importación

