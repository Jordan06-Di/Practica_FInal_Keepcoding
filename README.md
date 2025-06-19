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

```
/Proyecto_Final_Malware
│
├── 📁 Evidencias
│   ├── capturas_misp/
│   ├── capturas_elastic/
│   └── iocs_extraidos/
│
├── 📁 Documentación
│   ├── presentacion_final.pdf
│   └── informe_tecnico.pdf
│
├── 📁 Configuración
│   ├── misp_config/
│   └── elastic_agent_config/
│
└── README.md
```

---

## 🛠️ Herramientas utilizadas

- 🧪 [Joe Sandbox](https://www.joesandbox.com/)
- 🐾 [ANY.RUN](https://any.run/)
- 🧬 [MISP](https://github.com/MISP/MISP)
- 📊 [Elastic Cloud SIEM](https://www.elastic.co/security)
- 🖥️ Windows 10 VM (agente ELK)
- 📦 Git & GitHub

---

## 📌 Objetivos Alcanzados

- ✅ Análisis detallado de múltiples muestras de malware recientes.
- ✅ Extracción y clasificación de indicadores de compromiso.
- ✅ Configuración de una plataforma MISP funcional y conectada.
- ✅ Integración con Elastic SIEM y generación de alertas reales.
- ✅ Documentación técnica completa y presentación efectiva del proyecto.

---

## 📄 Créditos

Este proyecto fue desarrollado por **Jordan Díaz** como parte del bootcamp de Ciberseguridad de **KeepCoding**.

---

## 📬 Contacto

Si deseas ponerte en contacto, puedes escribirme a:  
📧 jordandiaz@example.com  
🔗 [LinkedIn](https://linkedin.com/in/tuusuario)

---

## 🛡️ Licencia

Este proyecto se encuentra bajo la licencia [MIT](LICENSE).
