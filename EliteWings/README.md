# ✈️ Elite Wings API

API para la gestión de vuelos, celebridades, jets privados y reportes de seguridad.

## 🚀 Tecnologías

- NestJS
- PostgreSQL
- Swagger (OpenAPI)
- TypeORM

## 🧪 Documentación de la API

Puedes acceder a la documentación completa en Swagger aquí:

👉 [http://localhost:8081/api](http://localhost:8081/api)

## 📦 Endpoints principales

### ✨ Celebridades
- `GET /celebrities`: Obtener todas las celebridades
- `POST /celebrities`: Crear nueva celebridad
- `GET /celebrities/{id}`: Obtener una celebridad por ID
- `PUT /celebrities/{id}`: Actualizar una celebridad
- `DELETE /celebrities/{id}`: Eliminar una celebridad

### 🛩️ Private Jets
- `POST /jets`: Registrar un jet privado
- `GET /jets/{id}`: Obtener detalles de un jet
- `PATCH /jets/{id}`: Actualizar un jet
- `DELETE /jets/{id}`: Eliminar un jet

### 🛫 Flights
- `POST /flights`: Crear un nuevo vuelo
- `GET /flights/{id}`: Obtener detalles de un vuelo
- `DELETE /flights/{id}`: Eliminar un vuelo
- `GET /flights/suspicious`: Listar vuelos sospechosos

### 🛡️ Security Reports
- `POST /security-reports`: Reportar un incidente
- `PATCH /security-reports/{id}/resolve`: Marcar como resuelto
- `GET /security-reports/unresolved`: Ver reportes no resueltos

## 🧰 Cómo correr el proyecto

```bash
./mvnw spring-boot:run


