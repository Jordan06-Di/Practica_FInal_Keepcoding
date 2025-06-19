# Practica_Final_Keepcoding
# 🧠 Proyecto Final - Análisis de Malware con MISP y Elastic SIEM

Este repositorio contiene la documentación, evidencias y configuración del proyecto final presentado como parte del bootcamp de Ciberseguridad. El objetivo principal fue realizar un **análisis completo de muestras de malware** y su integración con **MISP** (Malware Information Sharing Platform) y **Elastic Cloud SIEM** para generar alertas de seguridad automatizadas.

---

## 🧩 Descripción del Proyecto

Este proyecto busca demostrar un flujo de trabajo completo de detección, análisis y respuesta ante amenazas a partir de muestras reales de malware, utilizando herramientas de inteligencia y monitoreo en tiempo real.

### 🔍 Componentes principales:

1. **Máquina virtual con MISP**  
   Plataforma utilizada para almacenar, correlacionar y compartir indicadores de compromiso (IOCs) extraídos de las muestras.

2. **Análisis de malware**  
   Se analizaron muestras de malware utilizando **Joe Sandbox** y **ANY.RUN**, extrayendo indicadores como hashes, dominios, IPs, archivos y comportamiento malicioso.

3. **Integración con Elastic Cloud SIEM**  
   Los IOCs fueron integrados en el SIEM en la nube, que monitorea los eventos generados desde un agente instalado en una VM Windows simulando un entorno empresarial.

4. **Generación de alertas**  
   Se generaron alertas automáticas al detectar eventos relacionados con los IOCs cargados, simulando un entorno de respuesta ante incidentes.

---

## ⚙️ Estructura del Repositorio

