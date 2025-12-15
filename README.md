# # AppTFG (Nombre Provisional) 🎮
> Una plataforma social para amantes de los videojuegos, inspirada en Letterboxd, para puntuar, reseñar y descubrir nuevos títulos mediante IA.

## 📝 Descripción del Proyecto
Este proyecto es un **TFG (Trabajo de Fin de Grado)** que consiste en una aplicación híbrida (iOS/Android/Web) desarrollada con **Ionic y Angular**. La plataforma permite a los usuarios gestionar su historial de juegos, interactuar con una comunidad y recibir recomendaciones personalizadas basadas en inteligencia artificial.

## 🚀 Tecnologías Utilizadas
* **Frontend:** Ionic Framework + Angular (Plantilla Tabs).
* **Backend & DB:** Firebase (Firestore, Auth, Storage).
* **Lenguajes:** TypeScript, SCSS, HTML.
* **APIs Externas:** RAWG API / IGDB para la base de datos de videojuegos.
* **IA:** Integración con modelos de HuggingFace para el sistema de recomendaciones.

---

## 📅 Planificación del Proyecto (Metodología Scrum)

La ejecución del proyecto se divide en los siguientes bloques funcionales extraídos del backlog técnico:

### 1. Configuración e Infraestructura 🛠️
- [ ] Setup del entorno (Node.js, Angular/Ionic CLI).
- [ ] Inicialización del repositorio Git y variables de entorno `.env`.
- [ ] Configuración de Firebase (Firestore, Auth, Storage).
- [ ] Conexión inicial y reglas de seguridad.

### 2. Gestión de Usuarios y Seguridad 👤
- [ ] Servicio de Autenticación (Email, Password y Google Login).
- [ ] Implementación de Guards de sesión.
- [ ] Creación de perfiles de usuario vinculados a Firestore.
- [ ] Funcionalidades de recuperación de contraseña y logout.

### 3. Núcleo de la Aplicación (Core) 🏠
- [ ] **Home:** Secciones de "Para Ti", "Reseñas" y "Siguiendo".
- [ ] **Búsqueda:** Integración de API externa con filtros por género y plataforma.
- [ ] **Detalle del Juego:** Información técnica, portadas y sistema de navegación.

### 4. Sistema Social y Valoraciones ⭐
- [ ] **Rating:** Componente de estrellas interactivo y cálculo de promedios.
- [ ] **Reseñas:** Sistema de feedback escrito vinculado a juegos y usuarios.
- [ ] **Social:** Funcionalidad de "Seguir usuario" y feed de actividad reciente.

### 5. Inteligencia Artificial (IA) 🤖
- [ ] Creación de dataset de usuario (juegos/géneros preferidos).
- [ ] Implementación de Firebase Functions para procesamiento.
- [ ] Integración con modelos de **HuggingFace** para recomendaciones personalizadas.

---

## 🛠️ Instalación y Ejecución
1. Clona el repositorio: `git clone [URL_DEL_REPO]`
2. Instala las dependencias: `npm install`
3. Levanta el servidor local: `ionic serve`

---

## 🎓 Autor
* **Nombre:** Jaime Verdugo Serrano
* **Contacto:** jaimeverdugo.dev@gmail.com
* **Centro:** IES Rafael ALberti
