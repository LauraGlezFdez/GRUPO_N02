Este repositorio contiene el desarrollo realizado para la Actividad 3 de la asignatura Ingeniería del Software Avanzada, centrada en la aplicación práctica de metodologías de desarrollo dirigidas por pruebas (TDD) y comportamiento (BDD).

El trabajo se ha llevado a cabo sobre una aplicación web desarrollada en React denominada BuscaSofa, cuyo objetivo es proporcionar una interfaz de consulta y visualización de información procedente de servicios externos.

Objetivos

El proyecto persigue los siguientes objetivos:

Analizar una base de código existente e identificar incidencias mediante pruebas automatizadas.
Corregir los errores detectados respetando los escenarios de validación definidos.
Incorporar nuevas funcionalidades al producto.
Implementar pruebas unitarias y pruebas de aceptación que garanticen la calidad del software.
Aplicar buenas prácticas de desarrollo, control de versiones y validación continua.
Funcionalidades implementadas

Durante el desarrollo del proyecto se han realizado, entre otras, las siguientes actuaciones:

Corrección de incidencias detectadas por las pruebas existentes.
Implementación de una página para la gestión de rutas no válidas (Not Found).
Adaptación de elementos de navegación para satisfacer los requisitos definidos en los escenarios de prueba.
Ampliación de la sección informativa de la aplicación.
Incorporación de nuevos componentes de interfaz.
Desarrollo de nuevas pruebas automatizadas mediante Cypress.
Tecnologías utilizadas
React
Vite
Vitest
React Testing Library
Cypress
JavaScript
Git y GitHub
Ejecución del proyecto

Instalar dependencias:

npm install

Iniciar la aplicación:

npm run dev

Ejecutar pruebas unitarias:

npm test

Ejecutar pruebas de aceptación:

npx cypress open
Estructura de validación

El proyecto incluye:

Pruebas unitarias para componentes individuales.
Pruebas de aceptación E2E mediante Cypress.
Escenarios orientados a validar la navegación, autenticación, visualización de información y gestión de errores.
Licencia

Repositorio publicado con fines exclusivamente académicos y docentes.
