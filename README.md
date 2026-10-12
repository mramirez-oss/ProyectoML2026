# 🍅📡 PhytoRadar-PY

Prevención temprana del Tizón Tardío (Phytophthora infestans) en cultivos de tomate mediante Inteligencia Artificial y Mapeo Georreferenciado en Paraguay.

## 📖 Sobre el Proyecto

PhytoRadar-PY es una solución tecnológica de doble componente (App Móvil + Plataforma Web) inspirada en sistemas exitosos como USAblight y EuroBlight. Busca empoderar al productor agrícola paraguayo permitiéndole diagnosticar posibles casos de tizón tardío tomando una simple fotografía de sus plantas.

Cada reporte positivo identificado por nuestro modelo de Machine Learning alimenta un mapa nacional en tiempo real, generando alertas tempranas de expansión y un registro histórico invaluable para instituciones gubernamentales e investigadores.

## ⚠️ El Problema

El tizón tardío prospera en ambientes húmedos y calurosos (condiciones habituales en Paraguay) y puede destruir cultivos enteros en pocos días. Actualmente, el ecosistema agrícola paraguayo enfrenta:

Detección tardía: El productor suele notar la enfermedad cuando el foco ya infectó su finca.

Uso abusivo de agroquímicos: Como respuesta a la falta de información, se aplican químicos de forma preventiva y a ciegas, aumentando costos y riesgos ambientales.

Información aislada: Los datos los tienen técnicos, cooperativas o el Estado, pero no existe un sistema nacional que los integre y emita alertas tempranas.

## 💡 La Solución

### 1. App Móvil (Para el Productor)

Diagnóstico fotográfico instantáneo mediante un modelo de Machine Learning.

Guías visuales sencillas e intuitivas para el reconocimiento de síntomas en campo.

Reporte rápido y geolocalizado de casos sospechosos.

### 2. Plataforma Web (Para Monitoreo Estatal/Investigación)

Mapeo georreferenciado de todos los reportes a nivel nacional.

Generación de alertas zonales de expansión.

Historial epidemiológico de la enfermedad.

## 🛠️ Stack Tecnológico (Preliminar)

Lenguaje Principal: Python 🐍

Inteligencia Artificial: Se prioriza un enfoque de Machine Learning clásico/básico (extracción de características de imágenes y algoritmos de clasificación tradicional) en lugar de arquitecturas complejas de Deep Learning. Esto asegura un modelo más ligero, goza de mayor interpretabilidad y reduce los costos computacionales para esta etapa de prototipo.

Frontend/Mobile: A definir según la conformación final del equipo de desarrollo.

## 🎯 Objetivos

### Objetivo General:
Reducir las pérdidas de cosecha y el uso excesivo de agroquímicos mediante la detección temprana y el monitoreo nacional de la expansión del tizón tardío.

### Objetivos Específicos:

Recopilar y etiquetar un dataset de imágenes de plantas sanas y enfermas.

Entrenar y validar un modelo de ML robusto en condiciones reales de campo.

Diseñar una app móvil accesible para el productor paraguayo.

Implementar la plataforma de mapeo y alertas para articulación público-privada.

## 🚧 Alcance del Proyecto

### ✅ INCLUYE:

Desarrollo de App móvil con IA para la detección específica del Tizón Tardío.

Aplicación web de mapeo georreferenciado y alertas.

### ❌ QUEDA FUERA:

Monitoreo de otras enfermedades, plagas (insectos, malezas) o incendios.

Extensión del sistema a otros cultivos (enfocado inicialmente en el tomate).

## 📈 Estado Actual y Roadmap

Actualmente el proyecto se encuentra en la fase de Diseño Conceptual y Definición del Problema.

Hitos a corto plazo (Demo Day - Noviembre):

[ ] Construcción del dataset inicial.

[ ] Entrenamiento del algoritmo de Machine Learning.

[ ] Prototipo/Maquetas de la aplicación móvil (UI/UX).

[ ] Diseño de la arquitectura de la base de datos para la plataforma web.

## 🤝 Ecosistema y Colaboración

Este proyecto busca crear un puente directo entre el sector privado y el público, beneficiando a:

Productores Nacionales

Instituciones Estatales y de Investigación: SENAVE, MAG, IPTA, CONACYT.

## 🧑‍💻 ¿Cómo puedes ayudar? (Necesidades del Equipo)

Buscamos sumar perfiles multidisciplinarios para fortalecer el proyecto:

🌱 Agronomía: Asesoramiento experto para comprender el contexto de campo y validar síntomas.

💻 Desarrollo y Datos: Especialistas en Python, Machine Learning clásico, y desarrollo Mobile/Web.

⚖️ Propiedad Intelectual: Asesoramiento en transferencia tecnológica y marcos legales.

Este proyecto nació en el marco del programa SHELL LAB FIUNA 2026 - Facultad de Ingeniería de la Universidad Nacional de Asunción.

