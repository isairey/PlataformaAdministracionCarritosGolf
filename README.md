<div align="center">

<img width="220" src="https://cdn-icons-png.flaticon.com/512/854/854878.png" />

# ⛳ Golf Cart Rentals

### Plataforma web de administración y reservación de carritos de golf 🚀

<p align="center">
  <b>Golf Cart Rentals</b> es un sistema web de gestión de alquileres diseñado para administrar reservaciones, inventario, departamentos y usuarios mediante una plataforma centralizada orientada al control administrativo y operativo.
</p>

<p align="center">
  <img src="https://img.shields.io/badge/GolfCart-RentalSystem-2E8B57?style=for-the-badge">
  <img src="https://img.shields.io/badge/WebBased-Management-blue?style=for-the-badge">
  <img src="https://img.shields.io/badge/Admin-ControlSystem-orange?style=for-the-badge">
  <img src="https://img.shields.io/badge/OpenSource-Archived-red?style=for-the-badge">
  <img src="https://img.shields.io/badge/Rental-Platform-success?style=for-the-badge">
</p>

<p align="center">
  <a href="#-acerca-del-proyecto">Acerca</a> •
  <a href="#-características">Características</a> •
  <a href="#-arquitectura-del-sistema">Arquitectura</a> •
  <a href="#-tecnologías-utilizadas">Tecnologías</a> •
  <a href="#-vista-previa">Vista previa</a>
</p>

</div>

---

# 🌌 Acerca del proyecto

**Golf Cart Rentals** es una plataforma web enfocada en la administración y control de alquileres de carritos de golf mediante un sistema centralizado de reservas, usuarios y departamentos.

El proyecto fue diseñado para facilitar:

- ⛳ Gestión de carritos de golf
- 📅 Reservaciones múltiples
- 👥 Administración de usuarios
- 🏢 Control por departamentos
- 📄 Gestión de acuerdos y tarifas
- 📊 Control administrativo
- 🔐 Gestión de permisos
- 🗄️ Relaciones de base de datos

Cada carrito puede tener múltiples reservaciones, diferentes tipos de unidades y reglas de alquiler específicas según tarifas y acuerdos asociados.

---

# ✨ Características

## ⛳ Gestión de alquileres

- 📅 Reservaciones múltiples por artículo
- 📋 Control de disponibilidad
- 🧾 Gestión de tarifas
- 📄 Acuerdos de alquiler
- 🏷️ Tipos de carritos personalizados

---

## 👥 Administración de usuarios

- 👤 Registro de usuarios
- 🏢 Asignación por departamentos
- 🔐 Gestión de permisos
- 👨‍💼 Control administrativo
- 📊 Historial de reservaciones

---

## 🛠️ Panel administrativo

- ➕ Crear usuarios y departamentos
- ✏️ Editar registros
- ❌ Eliminar elementos
- 📋 Administrar reservaciones
- 🔒 Control de permisos individuales y grupales

---

## 📊 Gestión organizacional

- 🏢 Departamentos asociados
- 💳 Facturación por departamento
- 📅 Calendario de reservas
- 📈 Visualización de disponibilidad
- 📂 Control centralizado

---

# 🏗️ Arquitectura del sistema

## 🧠 Relaciones del sistema

La plataforma utiliza una arquitectura basada en entidades relacionadas para administrar usuarios, departamentos, artículos y reservaciones.

### 📌 Componentes principales

- 👥 Usuarios
- 🏢 Departamentos
- ⛳ Carritos de golf
- 📅 Reservaciones
- 🧾 Tarifas
- 🔐 Roles y permisos

---

# 🛠️ Tecnologías utilizadas

## 🎨 Frontend

<p>
  <img src="https://skillicons.dev/icons?i=html,css,js" />
</p>

- HTML5
- CSS3
- JavaScript
- Interfaz web administrativa

---

## ⚙️ Backend

<p>
  <img src="https://skillicons.dev/icons?i=nodejs" />
</p>

- Node.js
- Arquitectura web modular
- Gestión de usuarios
- Sistema de reservas

---

## 🗄️ Base de datos

<p>
  <img src="https://skillicons.dev/icons?i=mysql" />
</p>

- MySQL
- Relaciones SQL
- Persistencia relacional
- Gestión de inventario

---

## 🧰 Herramientas

<p>
  <img src="https://skillicons.dev/icons?i=git,github" />
</p>

- Git
- GitHub
- Travis CI
- Code Climate

---

# 📂 Estructura del proyecto

```bash
PlataformaAdministracionCarritosGolf/
│
├── app/                     # Lógica principal
├── config/                  # Configuración del sistema
├── database/                # Migraciones y modelos
├── public/                  # Recursos públicos
├── routes/                  # Rutas de la aplicación
├── views/                   # Interfaces web
├── tests/                   # Pruebas del sistema
│
├── Golfcart Schema.png      # Diagrama relacional
├── README.md
└── LICENSE
```

---

# ⚡ Instalación

## 📋 Requisitos

- Node.js
- MySQL
- Git
- Navegador moderno

---

# 🚀 Configuración del proyecto

## 1️⃣ Clonar repositorio

```bash
git clone https://github.com/isairey/PlataformaAdministracionCarritosGolf.git
```

---

## 2️⃣ Instalar dependencias

```bash
npm install
```

---

## 3️⃣ Configurar base de datos

Crear una base de datos MySQL y configurar variables de entorno para conexión.

---

## 4️⃣ Ejecutar servidor

```bash
npm start
```

---

# 📊 Funcionalidades principales

## 📅 Sistema de reservaciones

- Reservas múltiples
- Gestión de fechas
- Disponibilidad en tiempo real
- Control de alquileres

---

## 👨‍💼 Administración avanzada

- Gestión de usuarios
- Gestión de departamentos
- Roles y permisos
- Control administrativo

---

## 📈 Gestión organizacional

- Facturación por departamento
- Tarifas configurables
- Administración de acuerdos
- Supervisión operativa

---

# 📸 Vista previa

<div align="center">

### 🧠 Diagrama relacional del sistema
![Schema](https://github.com/umts/golf-cart-rentals/blob/master/Golfcart%20Schema.png)

</div>

---

# 📚 Documentación

## 📖 Wiki del proyecto

La configuración completa y documentación original del sistema se encuentra en la wiki del repositorio.

Incluye:

- ⚙️ Configuración inicial
- 🗄️ Estructura de base de datos
- 🚀 Despliegue
- 🔐 Administración
- 📋 Gestión de reservaciones

---

# 🧠 Objetivos del proyecto

## 🎯 Aprendizaje y desarrollo

- Sistemas de reservaciones
- Arquitectura web
- Gestión administrativa
- Control de inventario
- Bases de datos relacionales
- Roles y permisos
- Desarrollo organizacional

---

# 📦 Estado del proyecto

## 🗃️ Proyecto archivado

El proyecto fue archivado debido a cambios internos en la estrategia de desarrollo y cancelación de aplicaciones relacionadas.

Sin embargo, sigue siendo una excelente referencia para:

- 📚 Aprendizaje académico
- 🏢 Sistemas administrativos
- 📅 Gestión de reservaciones
- 🔐 Control de usuarios
- 🗄️ Diseño relacional

---

# 🚧 Roadmap

## 🔮 Posibles mejoras futuras

- 📱 Aplicación móvil
- ☁️ Infraestructura cloud
- 📊 Dashboard avanzado
- 🔔 Notificaciones en tiempo real
- 🌐 API REST moderna
- 🤖 Automatización inteligente
- 📅 Calendario interactivo

---

# 🤝 Contribuciones

Las contribuciones son bienvenidas ❤️

## Cómo contribuir

1. Fork del proyecto

```bash
git checkout -b feature/nueva-funcionalidad
```

2. Commit

```bash
git commit -m "✨ Nueva funcionalidad"
```

3. Push

```bash
git push origin feature/nueva-funcionalidad
```

4. Pull Request 🚀

---

# 👨‍💻 Desarrollador

<div align="center">

## Isai Reyes — Full Stack Developer

Desarrollador apasionado por plataformas administrativas, sistemas empresariales y arquitectura web moderna 🚀

</div>

---

# 🌟 Apoya el proyecto

⭐ Dale una estrella  
🍴 Haz fork  
📢 Comparte el proyecto

---

# 📜 Licencia

Proyecto open source utilizado con fines educativos y de investigación administrativa.

---

<div align="center">

### ⛳ Golf Cart Rentals — gestión inteligente de alquileres y reservaciones 🚀

</div>
