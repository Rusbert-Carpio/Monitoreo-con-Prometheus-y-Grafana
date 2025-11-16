# 🚀 Práctica de Monitoreo con Prometheus, Node Exporter y Grafana (Docker)

Esta práctica implementa un entorno básico de monitoreo utilizando **Docker Compose**, incluyendo:

- **Prometheus** → Sistema de métricas y scraping  
- **Node Exporter** → Exportación de métricas del host  
- **Grafana** → Visualización de métricas mediante dashboards  

El objetivo es practicar la creación de un entorno de monitoreo moderno usando contenedores.

---

## 📦 Requisitos

Antes de comenzar, asegúrate de tener instalado:

- **Docker Desktop** (Windows / Mac)
- **Docker Compose**
- PowerShell o terminal equivalente

---

## 📁 Estructura del proyecto

 practica-monitoring/
│── docker-compose.yml
│── prometheus.yml
└── README.md


---

## 🐳 1. Levantar los servicios con Docker

Desde la carpeta del proyecto, ejecutar:

```bash
docker compose up -d
