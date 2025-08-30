# ✈️ Sistema de Gestión de Boletos Aéreos  

![Spring Boot](https://img.shields.io/badge/Backend-SpringBoot-green)  
![MySQL](https://img.shields.io/badge/Database-MySQL-blue)  
![Scrum](https://img.shields.io/badge/Metodología-Scrum-orange)  
![Estado](https://img.shields.io/badge/Status-En%20Desarrollo-yellow)  

---

## 📌 Descripción  

El **Sistema de Gestión de Boletos Aéreos** es una aplicación académica desarrollada con **Java + Spring Boot** y una **API REST**, diseñada para administrar **aerolíneas, vuelos, pasajeros y reservaciones** de manera eficiente, escalable y segura.  

👉 En esta primera fase, el frontend está representado mediante **prototipos en Figma**, y el sistema simula procesos como pagos y reservas.  

---

## 👨‍💻 Equipo de Desarrollo  

| Nombre                           | Rol                  | Carnet    |  
|----------------------------------|----------------------|-----------|  
| **Carlos Eduardo Merino Ventura** | Líder de Proyecto    | MV242667  |  
| **José Adrián López Medina**      | Control de Calidad   | LM242664  |  
| **Christian Levi González Castro**| Desarrollador Backend| GC242649  |  
| **Christopher Tommy Núñez Pineda**| Desarrollador Frontend| NP242671 |  

---

## 🎯 Funcionalidades  

<details>
<summary>✨ Click para ver lista completa</summary>

- ✅ **Gestión de Aerolíneas:** registro, actualización y consulta.  
- ✅ **Administración de Vuelos:** rutas, horarios y tarifas.  
- ✅ **Gestión de Aviones y Tripulación:** registro y asignación a vuelos.  
- ✅ **Registro de Pasajeros.**  
- ✅ **Reservación de Boletos:** búsqueda de vuelos, confirmación y simulación de pagos.  
- ✅ **Gestión de Reclamos.**  
- ✅ **Reportes básicos de estadísticas.**  

⚠️ **Límites de esta fase:**  
- Pagos simulados (no integración real).  
- Frontend solo en prototipos.  
- No hay versión móvil ni reportes avanzados.  

</details>

---

## 🛠️ Tecnologías Utilizadas  

- **Backend:** Java + Spring Boot  
- **Base de Datos:** MySQL  
- **Control de Versiones:** GitHub  
- **Gestión de Proyectos:** Trello / Notion  
- **Diseño de Interfaces:** Figma  
- **QA & Testing:** Postman  
- **Metodología:** Scrum (sprints de 2 semanas)  

---

## 🗄️ Base de Datos  

📌 Diagrama Relacional (ERD):  

![Modelo BD](./docs/db_diagram.png)  

La base incluye tablas para: aerolíneas, vuelos, tripulación, pasajeros, boletos, pagos y reclamos.  

---

## 🚀 Instalación y Uso  

1. Clonar el repositorio:  
   ```bash
   git clone https://github.com/ineedoritos/catedra-DWF.git
   cd catedra-DWF
   ```

2. Configurar la base de datos en `application.properties`:  
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/aerolinea_db
   spring.datasource.username=root
   spring.datasource.password=tu_password
   ```

3. Ejecutar el proyecto:  
   ```bash
   ./mvnw spring-boot:run
   ```

4. Probar la API en Postman o navegador:  
   ```
   http://localhost:8080/api/v1
   ```

---

## 📅 Organización  

- 🌀 **Scrum**: sprints de 2 semanas.  
- ✅ **Revisiones de código** en GitHub (Pull Requests).  
- 📝 **Reportes semanales** de progreso.  

---

## 📌 Enlaces  

- 🔗 [Repositorio GitHub](https://github.com/ineedoritos/catedra-DWF)  
- 🎨 [Mockups en Figma](https://www.figma.com/)  
- 📖 [Guía Scrum](https://scrumguides.org)  
- 📚 [Spring Boot](https://spring.io/projects/spring-boot)  

---
