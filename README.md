# AppTFG (nombre proyecto) 🎮
> Una plataforma social tipo Letterboxd para el sector del videojuego, con motor de recomendación por IA.

## 📝 Descripción del Proyecto
Este proyecto es un **TFG (Trabajo de Fin de Grado)** que consiste en una aplicación híbrida (iOS/Android/Web) desarrollada con **Ionic y Angular**. La plataforma permite a los usuarios gestionar su historial de juegos, interactuar con una comunidad y recibir recomendaciones personalizadas basadas en inteligencia artificial.

---

## 📑 Planificación y Análisis

### A. Recopilación de Información 📚
Se ha investigado el estado del arte de las aplicaciones de gestión de ludotecas. Se han seleccionado las siguientes fuentes de datos y herramientas:
* **APIs:** Evaluación de RAWG API y IGDB para el catálogo de juegos.
* **Referentes:** Análisis de UX/UI basado en Letterboxd y plataformas de streaming.
* **Tecnología:** Estudio de la documentación oficial de Ionic y Firebase para garantizar la sincronización en tiempo real.

### B. Estudio de Viabilidad Técnica ⚙️
El proyecto se considera viable utilizando el stack **Ionic + Angular + Firebase**:
* **Multiplataforma:** Un solo desarrollo para iOS, Android y Web.
* **Escalabilidad:** Firebase permite gestionar la autenticación y base de datos sin necesidad de infraestructura de servidor propia.
* **Integración:** Capacidad de conectar modelos de IA externos mediante Firebase Functions.

### C. Fases y Plazos de Ejecución 📅
Se sigue una metodología **Scrum** dividida en 3 hitos:
1. **Fase 1 (Semanas 1-2):** Setup, Auth y vinculación con Firestore (Infraestructura).
2. **Fase 2 (Semanas 3-5):** Core de la app: Búsqueda, Detalle del juego y Sistema de valoraciones.
3. **Fase 3 (Semanas 6-7):** Feed Social y módulo de Recomendación con IA (HuggingFace).

### D. Objetivos y Alcance 🎯
* **Objetivo:** Crear una comunidad donde el usuario pueda registrar su actividad gamer.
* **Alcance:** Sistema de login (Google/Email), buscador de juegos, sistema de estrellas, reseñas sociales y perfil personalizado con recomendaciones inteligentes.

### E. Actividades de Desarrollo 🛠️
* Configuración de entornos y repositorio Git.
* Modelado de datos en Firestore (Usuarios, Ratings, Reseñas).
* Desarrollo de componentes UI reutilizables (Cards, Sliders, Forms).
* Integración de lógica de IA para personalización de contenido.

### F. Recursos Necesarios 📦
* **Materiales:** PC de desarrollo, dispositivos de pruebas (Android/iOS), VS Code, Firebase Console.
* **Personales:** Jaime Verdugo Serrano (Full-stack Developer).

### G. Financiación y Presupuesto 💰
* **Costes de Infraestructura:** 0€ (Uso de niveles gratuitos: Firebase Spark Plan, HuggingFace Free Tier).
* **Coste de Desarrollo:** Autofinanciado (Estimación de 300 horas de desarrollo).

---

## 🚀 Stack Tecnológico
* **Frontend:** Ionic Framework & Angular.
* **Backend:** Firebase (Firestore, Auth, Storage).
* **IA:** HuggingFace API.

## 🛠️ Instalación y Ejecución
1. Clona el repositorio.
2. Ejecuta `npm install` para las dependencias.
3. Inicia el entorno con `ionic serve`.

---

## 👤 Autor
* **Nombre:** Jaime Verdugo Serrano
* **Correo:** [jaimeverdugo.dev@gmail.com](mailto:jaimeverdugo.dev@gmail.com)
