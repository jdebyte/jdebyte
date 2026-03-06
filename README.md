# Hola, soy Daniel López 👋
### QA Engineer | Manual Testing | API Testing | SQL

Soy un QA Engineer enfocado en asegurar la calidad del software a través de un análisis crítico y técnico. Mi objetivo es garantizar productos robustos mediante el diseño de estrategias de prueba exhaustivas, validación de datos y pruebas de integración de servicios.

Recientemente completé mi formación en TripleTen, donde desarrollé proyectos centrados en el ciclo de vida de pruebas (STLC), detectando errores críticos en etapas tempranas y asegurando una experiencia de usuario impecable tanto en el Frontend como en el Backend.

---

## 💪 Mis Fortalezas

* **Análisis Funcional:** Diseño de casos de prueba, ejecución de pruebas exploratorias y de regresión.  
* **API Testing:** Pruebas de caja negra y gris para servicios REST, validación de esquemas y códigos de respuesta.  
* **Data Integrity:** Consultas complejas en bases de datos para verificar la persistencia y consistencia de la información.  
* **Documentación de Calidad:** Reportes de errores (Bug Reports) claros, concisos y accionables que facilitan el trabajo del equipo de desarrollo.  

---

## 🛠 Habilidades Técnicas

* **Manual Testing:** Gestión del ciclo de vida del defecto, creación de Checklists y Planes de Prueba.
* **API Testing:** Postman, análisis de documentación en Swagger, validación de JSON y códigos de estado (200, 201, 400, 404, 500).
* **Bases de Datos:** SQL (PostgreSQL / MySQL) para verificación de datos y pruebas de Backend.
* **Herramientas & Metodologías:** Git/GitHub, Metodologías Ágiles (Scrum), Jira, DevTools del navegador.

---

## 🚀 Proyectos Destacados

### 1. Urban Routes - Automatización E2E con Selenium (Sprint 9)
**Tipo:** UI Testing | **Tecnologías:** Python, Selenium WebDriver, Pytest  
**Repositorio:** https://github.com/jdebyte/qa-project-Urban-Routes-es

Desarrollé un script de automatización completo para el flujo de "Pedir un Taxi" en la aplicación Urban Routes. El objetivo fue cubrir el recorrido completo del usuario (End-to-End).

* **Arquitectura:** Implementé el patrón de diseño **Page Object Model (POM)** para separar la lógica de prueba de los localizadores, facilitando el mantenimiento.
    * `pages.py`: Clase `UrbanRoutesPage` con localizadores y métodos.
    * `main.py`: Ejecución de casos de prueba.
    * `data.py`: Centralización de datos de prueba.
* **Cobertura:** Configuración de ruta, selección de tarifa "Comfort", relleno de datos personales, adición de tarjeta de crédito (simulando enfoque de teclado), y validación de modales de búsqueda de conductor.
* **Logro:** Ejecución exitosa de 9/9 pruebas críticas con manejo correcto de esperas explícitas (`WebDriverWait`).

> *Feedback del Revisor:* "Implementación excelente del patrón POM, código limpio y mantenible. Métodos descriptivos y buena separación de responsabilidades."

### 2. Urban Grocers - Automatización de Pruebas de API (Sprint 8)
**Tipo:** API Testing | **Tecnologías:** Python, Requests  
**Repositorio:** https://github.com/jdebyte/qa-project-Urban-Grocers-app-es

Creación de una suite de pruebas automatizadas para verificar la funcionalidad de "Crear un Kit" en la API de Urban Grocers. Me enfoqué en la validación de datos y manejo de errores.

* **Escenarios de Prueba:** Validación de nombres de kits utilizando **Clases de Equivalencia y Valores Límite**:
    * Creación exitosa (201): 1 caracter, 511 caracteres, caracteres especiales, espacios permitidos.
    * Validación de error (400): 0 caracteres, 512 caracteres, tipos de datos incorrectos.
* **Estructura:** Uso de archivos de configuración (`configuration.py`) y funciones de solicitud reutilizables (`sender_stand_request.py`).
* **Logro:** Automatización del flujo de creación de usuarios y kits pasando tokens de autorización (`authToken`) dinámicos.

> *Feedback del Revisor:* "Excelente trabajo en la automatización. Nombres de variables claros y métodos que describen con precisión la acción que realizan."

### 3. SauceDemo - Pruebas Manuales de Funcionalidad E-commerce
**Tipo:** Manual Testing | **Tecnologías:** Test Cases, Exploratory Testing, Bug Reports  
**Repositorio:** https://github.com/jdebyte/qa-testing-manual-saucedemo

Ejecución de pruebas manuales en la plataforma de e-commerce SauceDemo enfocadas en validar funcionalidades clave del flujo de compra como productos, carrito y proceso de checkout.

* **Escenarios de Prueba:** Validación del flujo de compra mediante pruebas positivas, negativas y exploratorias:
    * **Login:** verificación de autenticación de usuarios con credenciales válidas e inválidas y validación de mensajes de error.  
    * **Carrito de compras:** persistencia de productos después de cerrar sesión, visualización de imágenes y validación de restricciones con carrito vacío.  
    * **Checkout:** validación de campos del formulario como nombre y código postal utilizando caracteres especiales, números y formatos inválidos.  
    * **Flujo de compra:** verificación de restricciones del sistema para evitar continuar o finalizar compras sin productos en el carrito.  
* **Estructura:** Organización de casos de prueba por módulos (Login, Productos, Carrito y Checkout), ejecución de pruebas manuales y documentación de defectos con pasos de reproducción, resultado esperado y resultado actual.  
* **Logro:** Identificación de múltiples defectos funcionales, incluyendo validaciones incorrectas en formularios y la posibilidad de completar el proceso de compra con el carrito vacío.

---

## 📫 Contacto

* **LinkedIn:** www.linkedin.com/in/lpjonathandaniel
* **Email:** lpenaloza.jd@gmail.com
* **Ubicación:** Tecámac, Méx.

⭐️ *Gracias por visitar mi portafolio.*
