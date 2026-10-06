<h1 align="center">HelpDesk</h1>

<p align="center">Sistema de soporte interno basado en Kanban</p>

## Descripcion

HelpDesk es un proyecto para organizar solicitudes de soporte mediante un tablero Kanban. Las tareas se agrupan por departamento, muestran su estado y se asignan a los roles correspondientes. El sistema tambien contempla una guia interactiva para ayudar a las personas a comprender y usar sus funciones.

## Objetivos

- Centralizar las solicitudes y el seguimiento del trabajo de soporte.
- Hacer visible el avance de cada tarea mediante estados Kanban.
- Organizar las tareas y responsabilidades por departamento.
- Definir permisos de acuerdo con los roles de cada persona.
- Ofrecer orientacion interactiva para dudas comunes sobre el sistema.
- Comenzar con datos simulados en el almacenamiento local del navegador mientras se define la necesidad de una base de datos.

## Funciones previstas

- Tablero Kanban con tareas, estados, responsables y departamento asignado.
- Gestion de departamentos y asignacion de solicitudes.
- Roles propuestos: administrador, coordinador de departamento, agente de soporte y solicitante.
- Guia conversacional que responda preguntas de uso y ayude a encontrar acciones dentro del sistema.
- Persistencia inicial de datos de demostracion mediante `localStorage`.

Los estados y permisos definitivos se estableceran durante el desarrollo. La guia conversacional busca reconocer la intencion de una pregunta y relacionar frases equivalentes. Por ejemplo, "como estas" y "como te encuentras" podrian tratarse como preguntas de la misma categoria, sin guardar cada frase exacta. La tecnica de aprendizaje automatico y su alcance quedan pendientes de seleccion.

## Tecnologias

- Frontend: SvelteKit, Svelte 5, TypeScript y Vite.
- Backend: Python y Django.
- Persistencia inicial propuesta: `localStorage` del navegador con datos simulados.

## Estado del proyecto

El repositorio contiene el esqueleto inicial de SvelteKit y Django. La pagina del frontend sigue siendo la pantalla de bienvenida de SvelteKit y el backend solo tiene configurada la ruta de administracion. El tablero, los roles, la API, el almacenamiento local y el chatbot aun no estan implementados.

Django tiene SQLite configurado como base de datos predeterminada de su proyecto inicial, pero HelpDesk todavia no define ni utiliza modelos propios. La estrategia final de persistencia sigue pendiente.

## Requisitos

- Python instalado.
- Node.js y npm instalados.

cambio
cambio en develop