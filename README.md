# Nuevas-tecnologias-proyecto-integrador
Repositorio como requisito evaluativo momento 1 de Nuevas Tecnologías de Programación.
Integrantes:
1. Selva Natalia Benítez Peláez
2. Eusebio José Caballero Olivella
3. Sergio Campo De la Cruz
4. Juliana Osorio López
5. Felipe Rodríguez Restrepo

Descripción del proyecto.

AulaBot — Sistema de Gestión Académica

AulaBot es un sistema de gestión académica orientado a digitalizar y centralizar los procesos administrativos de una institución educativa: registro y consulta de estudiantes, docentes, asistencia y calificaciones. El proyecto está desarrollado con Spring Boot en el backend, siguiendo una arquitectura por capas (dominio, persistencia con JPA/Hibernate, y presentación vía API REST) sobre una base de datos MySQL, y con un frontend en React + Tailwind CSS que consume dicha API.

El objetivo del proyecto es ofrecer una alternativa organizada y escalable a la gestión manual o dispersa de la información académica, permitiendo a administradores y docentes registrar, consultar y actualizar datos clave del proceso educativo de forma ágil y centralizada.

## Reglas de Colaboración y Trabajo

### Estrategia de Ramas (GitFlow)
* `main`: Rama de producción (código estable y probado).
* `develop`: Rama principal de integración donde se unen todas las tareas.
* `feature/...`: Ramas temporales para desarrollar módulos individuales (`feature/auth`, `feature/dashboard`, etc.).

### Convención de Commits
* `feat:` Nueva funcionalidad para el proyecto.
* `fix:` Corrección de un error o bug.
* `docs:` Cambios en la documentación.
* `style:` Formato, espacios o CSS sin alterar la lógica.
* `refactor:` Reestructuración de código sin alterar su comportamiento.
* `test:` Adición o modificación de pruebas.

### Reglas para Pull Requests (PR)
1. Queda prohibido hacer push directamente a `main` o `develop`.
2. Todo desarrollo debe subirse mediante un Pull Request desde la rama `feature/...` hacia la rama `develop`.
3. Todo PR requiere la revisión y aprobación de al menos 1 integrante del equipo antes de ser integrado.

### Reglas para Merges (Fusiones)
* Las fusiones se realizan únicamente desde la interfaz de GitHub tras la aprobación del Pull Request correspondiente.





