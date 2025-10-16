# Resumen de Git y GitHub

Este documento resume mi conocimiento actual sobre Git y GitHub, así como las dudas que todavía tengo. El objetivo es compartirlo con mi equipo para aprender y mejorar juntos.

---

## 1. Qué sé sobre Git

Git es un **sistema de control de versiones distribuido** que permite llevar un seguimiento de los cambios en el código, colaborar con otros y mantener un historial claro de desarrollo.

### Comandos básicos que manejo
- `git init`: Inicializa un nuevo repositorio local.  
- `git clone <url>`: Clona un repositorio remoto a mi máquina local.  
- `git status`: Muestra el estado actual del repositorio (archivos modificados, sin seguimiento, etc.).  
- `git add <archivo>`: Añade cambios al área de staging (preparación para commit).  
- `git commit -m "mensaje"`: Guarda los cambios en el historial de Git.  
- `git push`: Sube los commits locales a un repositorio remoto.  
- `git pull`: Trae los cambios desde un repositorio remoto y los fusiona con mi copia local.  
- `git branch`: Lista las ramas locales.  
- `git checkout <rama>`: Cambia de rama.  
- `git merge <rama>`: Fusiona otra rama en la rama actual.

### Conceptos que entiendo
- **Ramas (branches)**: Permiten trabajar en diferentes funcionalidades sin afectar la rama principal.  
- **Repositorio local y remoto**: Diferencia entre lo que está en mi ordenador y lo que está en GitHub.  
- **Staging area**: Área donde preparas los cambios antes de hacer un commit.  
- **Historial de commits**: Registro de cambios que permite volver a versiones anteriores si es necesario.

---

## 2. Qué sé sobre GitHub

GitHub es una **plataforma para alojar repositorios Git** de forma remota. Facilita la colaboración, la revisión de código y la integración continua.

### Funcionalidades que uso
- Crear repositorios públicos y privados.  
- Subir proyectos desde mi repositorio local (`git push`).  
- Crear y gestionar ramas remotas.  
- Abrir **pull requests** para fusionar cambios de una rama a otra y recibir revisiones.  
- Usar Issues y Projects para organizar tareas y seguimiento de proyectos.  

---

## 3. Lo que todavía me confunde

Aunque manejo lo básico, tengo algunas dudas y áreas que quiero mejorar:  
- Diferencia exacta entre `merge` y `rebase`.  
- Cómo resolver **conflictos complejos** de manera eficiente.  
- Flujos de trabajo avanzados como **Gitflow** o **feature branching** en equipos grandes.  
- Buenas prácticas para escribir mensajes de commit claros y consistentes.  
- Uso de etiquetas (**tags**) y versiones en proyectos colaborativos.  

---

## 4. Preguntas para el equipo

- ¿Cómo gestionáis múltiples ramas y pull requests simultáneamente?  
- ¿Algún consejo para evitar conflictos frecuentes al colaborar?  
- ¿Cómo estructuráis los commits para proyectos largos o en equipo?  
- ¿Usáis alguna convención de nombres para ramas y commits que funcione bien?  

---

## 5. Recursos que estoy utilizando para aprender

- Documentación oficial de Git: [https://git-scm.com/doc](https://git-scm.com/doc)  
- Guía de GitHub: [https://docs.github.com](https://docs.github.com)  
- Tutoriales de YouTube y cursos de Git y GitHub  
- Práctica diaria con proyectos personales y colaborativos  

---

Este archivo servirá como referencia para futuras reuniones y revisiones de trabajo en equipo, y se actualizará conforme vaya aprendiendo más sobre Git y GitHub.
