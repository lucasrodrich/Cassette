# Cassette

[![CI](https://github.com/lucasrodrich/Cassette/actions/workflows/ci.yml/badge.svg)](https://github.com/lucasrodrich/Cassette/actions/workflows/ci.yml)

Mi primer proyecto de programación, hecho en grupo para una materia de la carrera (2024).

**Autores:** Rojo Justicia Candelaria, Portigliatti María Emilia, Rodríguez Richard Lucas.

## Qué es

Un mockup estático de una página de streaming de música: pantallas de Sign In / Sign Up, y una página principal con secciones de Playlists, Canciones, Artistas, Métodos de suscripción y pago, Contacto, Quiénes somos y un FAQ. No hay backend ni base de datos real: es una maqueta de interfaz, hecha para practicar HTML/CSS/JS.

Incluye el sketch y wireframe original en `sketch-wireframe/`.

Demo: https://canderojo.github.io

## Tecnologías

HTML, CSS y JavaScript plano, sin frameworks ni build tools. El login (`script.js`) guarda usuario/contraseña en `localStorage` del navegador solo para simular el flujo de Sign In / Sign Up — no es autenticación real. `animation.js` tiene una animación en `<canvas>` (logo rebotando) en la pantalla de login.

## Qué aprendí / qué haría distinto ahora

- Fue mi introducción a maquetar una interfaz completa a partir de un wireframe y a trabajar en equipo con Git (merges, conflictos, tres personas en el mismo repo).
- El "login" guarda la contraseña en texto plano en `localStorage`, que en su momento resolvía el problema de simular una sesión pero hoy sé que no tiene ningún valor como autenticación real.
- Hoy separaría más el CSS por componente en vez de un único `styles.css`, y evitaría manipular tanto el DOM a mano donde un framework simplificaría el estado (por ejemplo, el menú desplegable y las secciones ancladas).
