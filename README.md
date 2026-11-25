# Hola, soy Leonardo Galvis Ramírez

**Desarrollador Backend y Full Stack** · Python, Django y Django REST Framework · React · PostgreSQL · Docker  
📍 Cali, Colombia · Disponible para trabajo presencial, híbrido o remoto

Construyo aplicaciones web de punta a punta: análisis de requerimientos, diseño de la arquitectura, APIs, bases de datos, pruebas automatizadas y despliegue en la nube.

---

## Experiencia

- **4+ años** desarrollando software.
- Plataformas SaaS para la **gestión de exámenes y certificaciones**: usuarios, roles y permisos dinámicos, compras, integraciones con terceros, notificaciones y verificación de certificados.
- Despliegue de aplicaciones con **Docker en AWS** (EC2, RDS, S3, SES).
- Integraciones con **Oracle EBS**, procesos **ETL** y servicios en **.NET**.
- Actualmente aprendiendo **IA aplicada con Python**: integración de LLMs, RAG y agentes.

---

## Proyectos destacados

### 1. [FlowOps](https://github.com/leonardogr15/flowops) — flujos de aprobación multiempresa

![Django](https://img.shields.io/badge/Django-092E20?style=flat&logo=django&logoColor=white) ![DRF](https://img.shields.io/badge/Django_REST_Framework-A30000?style=flat&logo=django&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat&logo=docker&logoColor=white)

Aplicación SaaS en la que cada organización define flujos de aprobación por pasos para sus solicitudes.

- Aislamiento entre organizaciones en cada consulta, verificado con un arnés de pruebas que recorre la API.
- Flujos versionados y aprobaciones en orden; si dos personas deciden el mismo paso a la vez, solo una decisión cuenta (probado sobre PostgreSQL real).
- Registro de auditoría de solo inserción, protegido por un trigger de la base de datos.
- Integración continua con pruebas de backend, frontend, extremo a extremo y escaneo de secretos; decisiones de arquitectura documentadas como ADR.

<a href="https://github.com/leonardogr15/flowops"><img src="https://raw.githubusercontent.com/leonardogr15/flowops/main/docs/images/request-detail.png" alt="FlowOps: detalle de una solicitud con la ruta de aprobación y el historial de auditoría" width="640"></a>

### 2. [Jornada Laboral](https://github.com/leonardogr15/JornadaLaboral) — registro de jornadas laborales

![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=nodedotjs&logoColor=white) ![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white) ![PostgreSQL](https://img.shields.io/badge/PostgreSQL-4169E1?style=flat&logo=postgresql&logoColor=white) ![MongoDB](https://img.shields.io/badge/MongoDB-47A248?style=flat&logo=mongodb&logoColor=white) ![React](https://img.shields.io/badge/React-20232A?style=flat&logo=react&logoColor=61DAFB) ![Vite](https://img.shields.io/badge/Vite-646CFF?style=flat&logo=vite&logoColor=white)

Aplicación para registrar las horas de entrada y salida, con administración de usuarios y roles.

- Permisos verificados en el servidor en cada petición, con pruebas que intentan escalar privilegios.
- Persistencia políglota: usuarios y roles en PostgreSQL, jornadas en MongoDB.
- Interfaz React + Vite protegida por una Content-Security-Policy estricta, con comprobaciones de accesibilidad.
- Integración continua con pruebas de la API y del frontend, prueba de humo con Docker Compose y escaneo de secretos.

<a href="https://github.com/leonardogr15/JornadaLaboral"><img src="https://raw.githubusercontent.com/leonardogr15/JornadaLaboral/main/docs/images/shifts.png" alt="Jornada Laboral: formulario de registro, resumen de horas e historial de jornadas" width="640"></a>

---

## Tecnologías

- **Backend:** Python · Django · Django REST Framework · Node.js · Express · .NET
- **Frontend:** React · TypeScript · JavaScript
- **Datos:** PostgreSQL · MongoDB · Oracle
- **Nube y herramientas:** Docker · AWS (EC2, RDS, S3, SES) · GitHub Actions

---

## Contacto

[![LinkedIn](https://img.shields.io/badge/LinkedIn-Leonardo_Galvis_Ramírez-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/leonardo-galvis-ramirez-2424061b7)
