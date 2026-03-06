# Hola, soy Jonathan Daniel López Peñaloza 👋
### QA Engineer Jr | Test Automation | Python & Selenium

Soy Ingeniero de QA con un fuerte enfoque en automatización y calidad de software. Mi objetivo es crear frameworks de prueba eficientes y asegurar que tanto el Frontend como el Backend funcionen correctamente. Aquí comparto mis proyectos más recientes del Bootcamp de TripleTen, donde puse especial atención en las buenas prácticas y la estructura del código.

---

## 🛠 Habilidades Técnicas

* **Lenguajes:** Python.
* **Automatización Web:** Selenium WebDriver, Page Object Model (POM).
* **API Testing:** Requests library, Postman, Análisis de códigos de estado (201, 400).
* **Herramientas:** Git/GitHub, PyCharm, Pytest.

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
