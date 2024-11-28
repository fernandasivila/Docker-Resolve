# Resolve Gym - Dockerización del Sistema de Gestión para Gimnasios

## **Descripción del Proyecto**
Resolve Gym es un sistema integral de gestión para gimnasios que facilita la administración de socios, empleados, actividades y accesorios. Desarrollado como proyecto final para la materia *Programación y Servicios Informáticos*, este sistema mejora la eficiencia de las operaciones diarias y la experiencia de los usuarios.

### **Stack Tecnológico**
- **Frontend:** Angular, HTML, CSS, Bootstrap, TypeScript.
- **Backend:** Node.js, Express.js.
- **Base de Datos:** MongoDB.

El proyecto incluye la dockerización del sistema y la configuración de un clúster de replicación para la base de datos MongoDB, garantizando alta disponibilidad, resiliencia y escalabilidad en el manejo de los datos.

## **Requisitos del Sistema**
- Docker (versión mínima: 20.10).
- Docker Compose.
- Repositorio del proyecto: [Sistema de Gestión de Gimnasios 2024](https://github.com/fernandasivila/Sistema-de-Gestion-de-Gimnasios).

## **Acceso al Sistema**
- Frontend: http://localhost:4200
- Backend: http://localhost:3000
- Cliente MongoDB: http://localhost:8081 (Usuario: user, Contraseña: admin1234)
- Prometheus: http://localhost:9090
- Grafana: http://localhost:3001 (Usuario: admin, Contraseña: admin1234)

## **Características Principales**
- Red personalizada para comunicación segura entre contenedores.
- Backup automatizado de la base de datos cada 30 minutos.
- Despliegue continuo utilizando GitHub Actions, Render y Netlify.

## **Créditos**
- Marisel Evelin Alarcón Arias
- Maximiliano Martinez Gonzalez
- Maximiliano Alejandro Pelazzo
- Fernanda Belén Sivila
