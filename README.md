# 📝 NotesApp

Aplicación de ejemplo usada para demostrar prácticas de **CI/CD** con **Azure DevOps**, **Docker** y **Kubernetes (GKE)**.  
Construida con **Java 17 + Spring Boot**, incluye endpoints REST y health checks listos para entornos productivos.

---

## 🚀 Características principales

- ✅ API REST para gestionar tareas (To-Do).
- ✅ Endpoints para verificar health:
  - `/actuator/health/liveness`
  - `/actuator/health/readiness`
- ✅ Configuración lista para CI/CD con **Azure Pipelines**.
- ✅ Contenedorización con **Docker** y despliegue automático a **Google Kubernetes Engine (GKE)**.

---

## 🛠️ Tecnologías utilizadas

- **Java 17** + **Spring Boot**
- **Maven** para compilación y empaquetado
- **Docker** para imágenes de contenedor
- **Google Artifact Registry** como repositorio de imágenes
- **Kubernetes (GKE)** para despliegue
- **Azure DevOps Pipelines** para CI/CD
