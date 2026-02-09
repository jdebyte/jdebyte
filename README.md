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

---

## 📫 Contacto

* **LinkedIn:** www.linkedin.com/in/lpjonathandaniel
* **Email:** lpenaloza.jd@gmail.com
* **Ubicación:** Ecatepec de Morelos, Méx.

⭐️ *Gracias por visitar mi portafolio.*
