# 🗺️ CHIQUINQUIRÁ EXPLORA+ | Sistema de Inteligencia Turística

![Estado del Proyecto](https://img.shields.io/badge/Estado-Producci%C3%B3n-success)
![Plataforma](https://img.shields.io/badge/Plataforma-AppSheet-blue)
![Data](https://img.shields.io/badge/Data-Google%20Sheets-green)
![BI](https://img.shields.io/badge/BI-Looker%20Studio-orange)

## 📖 Descripción General
**CHIQUINQUIRÁ EXPLORA+** es una solución tecnológica de gobernanza de datos diseñada para cerrar la brecha entre la información administrativa oficial (RNT) y la realidad territorial del sector turístico.

El sistema permite realizar un **censo digital en tiempo real**, identificando discrepancias de capacidad, georreferenciando la oferta informal y calculando automáticamente el **ICIT (Índice de Calidad de Información Turística)** para la toma de decisiones basada en evidencia.

## 🚀 Problema que Resuelve
1.  **Obsolescencia del Dato:** Depura bases de datos oficiales (RNT) eliminando "falsos positivos" (sitios cerrados o inexistentes).
2.  **Invisibilidad de la Informalidad:** Identifica, caracteriza y georreferencia prestadores informales (Nivel 0) para estrategias de formalización.
3.  **Falta de Métricas:** Estandariza la calidad de la oferta mediante el algoritmo ICIT (Niveles 0, 1, 2, 3).

## 🛠️ Arquitectura Tecnológica (No-Code)
El proyecto utiliza una arquitectura escalable y de bajo costo basada en el ecosistema de Google:

* **Frontend (Campo):** AppSheet (Captura de datos, GPS, Fotos, Trabajo Offline).
* **Backend (Base Maestra):** Google Sheets con lógica de unificación (`BD_Propia_UNIFICADA`).
* **Automatización:** AppSheet Bots & Automation (Sincronización y cálculo de indicadores).
* **Visualización (Decision Making):** Looker Studio (Mapas de calor, KPIs de formalidad y capacidad real).

## ✨ Funcionalidades Clave
- [x] **Algoritmo ICIT:** Cálculo automático del nivel de calidad (0-3) basado en reglas de negocio (GPS + Contacto + Legalidad).
- [x] **Gestión de Informalidad:** Generación de IDs de control interno (`CHI-INF-`) para sitios no registrados.
- [x] **Smart Filters:** Prevención de duplicidad en auditorías mediante Slices dinámicos.
- [x] **Mapas de Calor:** Visualización de zonas de alta informalidad vs. zonas consolidadas.
- [x] **Navegación Jerárquica:** Interfaz UX optimizada para trabajo de campo eficiente.

## 📊 Impacto
Transformación de un modelo de registro documental estático a un **sistema vivo de gestión territorial**, permitiendo a la Alcaldía de Chiquinquirá auditar la capacidad de carga real y mejorar la competitividad del destino.

---
*Desarrollado para el Reto de Datos al Ecosistema 2025.*
