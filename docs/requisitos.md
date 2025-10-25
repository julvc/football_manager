# 📋 Requisitos del Proyecto: TeamOptimizer

## 🎯 Objetivo del Proyecto
Desarrollar una aplicación web que analice estadísticas de jugadores de fútbol y sugiera la mejor alineación titular para un partido, utilizando Machine Learning.

## 👤 Caso de Uso Principal
> “Como entrenador, quiero ingresar estadísticas actualizadas de mi plantilla y recibir una sugerencia de alineación ideal para el próximo partido.”

## ⚽ Métricas Relevantes por Posición

| Posición     | Métricas clave |
|--------------|----------------|
| Arquero      | Atajadas, goles recibidos, precisión en despejes |
| Defensa      | Intercepciones, duelos ganados, faltas cometidas |
| Mediocampo   | Pases completados, asistencias, recuperación de balón |
| Delantero    | Goles, tiros a puerta, regates exitosos |

## 📊 Dataset Seleccionado
- [European Soccer Database – Kaggle](https://www.kaggle.com/datasets/hugomathien/soccer)

## ✅ Requisitos Funcionales
- Registrar jugadores y sus estadísticas
- Consultar estadísticas individuales
- Generar alineación sugerida
- Visualizar comparativas entre jugadores

## 🛠️ Requisitos Técnicos
- Backend: Java 21 + Spring Boot 3 (principios SOLID, JPA, PostgreSQL)
- ML Engine: Python 3.12 + scikit-learn, pandas, joblib
- Frontend: React 18 + Vite + Axios + Chart.js
- Testing: JUnit + Mockito (Java), pytest (Python), Jest + RTL (React)

## 🧱 Arquitectura General

```plaintext
[React Frontend] ←→ [Java Spring Boot API] ←→ [PostgreSQL]
                                 ↑
                           [Python ML Engine]
