<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C0392B,100:C89B3C&height=200&section=header&text=Brian%20Moro%20(Willy)&fontSize=45&fontColor=ffffff&animation=fadeIn&desc=Full%20Stack%20Developer&descAlignY=75&descSize=18" width="100%" alt="Header" />

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=C89B3C&center=true&vCenter=true&width=600&lines=Angular+%C2%B7+Node.js+%C2%B7+MySQL;Construyendo+Wilson+Pizzas+de+punta+a+punta;Corriendo+y+jugando+LoL+en+mis+ratos+libres+%F0%9F%8F%83)](https://git.io/typing-svg)

📍 Rosario, Santa Fe, Argentina · 💼 Disponible para trabajos freelance

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-williams-moro-570532193/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:brianmorossj3@gmail.com)

</div>

Estudiante de la **Tecnicatura Superior en Desarrollo de Software** en el [Terciario Urquiza](https://terciariourquiza.edu.ar/), Rosario. Aprendo construyendo proyectos reales de punta a punta: desde la base de datos hasta la interfaz, pasando por el deploy en producción.

*Full Stack Developer student (Angular · Node.js · MySQL), based in Rosario, Argentina. I learn by shipping real, production-deployed projects — not just tutorials.*

---

## 🍕 Proyecto destacado: Wilson Pizzas

Sistema de pedidos online completo para una pizzería real, construido y desplegado en producción de punta a punta: catálogo interactivo, carrito, checkout, pagos, gestión de pedidos en tiempo real, control de stock, analíticas y un panel de administración completo.

<div align="center">
<img src="assets/wilson-pizzas-home.png" width="48%" alt="Catálogo — Wilson Pizzas" />
<img src="assets/wilson-pizzas-cart.png" width="48%" alt="Carrito — Wilson Pizzas" />

<img src="assets/wilson-pizzas-checkout.png" width="70%" alt="Checkout — Wilson Pizzas" />

<img src="assets/wilson-pizzas-mobile.png" width="24%" alt="Vista mobile — Wilson Pizzas" />

**[🔗 Ver demo en vivo](https://wilson-pizzas.vercel.app)**

</div>

**Stack:** Angular 22 (standalone components + signals) · Node.js/Express · MySQL · Socket.IO · JWT · Cloudinary · Leaflet + geocoding · Web Push (VAPID) · ExcelJS

**Algunas features del backend y frontend:**
- API REST en capas (`routes → controllers → models`) con 17 controllers, 19 modelos y ~50 endpoints
- Autenticación JWT con roles (admin / cliente / invitado) y rate limiting contra fuerza bruta
- Pedidos y notificaciones en tiempo real con Socket.IO + Web Push
- Panel admin con Kanban de pedidos (drag & drop), gestión de stock con predicción de duración e ingredientes por receta, y analíticas de negocio (embudo de conversión, AOV, heatmaps de ventas)
- Subida de imágenes dual-mode: Cloudinary en producción, filesystem en desarrollo
- Zonas de envío geolocalizadas dibujadas sobre un mapa (Leaflet + LocationIQ), validadas server-side
- Sistema de auto-migraciones de base de datos (23 migraciones incrementales) para actualizar el esquema sin downtime
- Frontend Angular con signals para estado reactivo, lazy loading por ruta y arquitectura standalone sin NgModules

<div align="center">
<img src="assets/wilson-pizzas-admin-stats.png" width="48%" alt="Panel admin — Analíticas" />
<img src="assets/wilson-pizzas-admin-kanban.png" width="48%" alt="Panel admin — Kanban de pedidos" />

<sub>Panel admin: analíticas de negocio + Kanban de pedidos en tiempo real</sub>
</div>

> El repositorio del código es privado (es la base de un negocio real), pero el demo está en vivo y puedo compartir el código en una entrevista.

<details>
<summary><b>🇬🇧 English summary</b></summary>
<br>

Full online ordering system for a real pizzeria, built and deployed end-to-end: interactive catalog, cart, checkout, real-time order management, inventory control, analytics and a full admin panel.

**Stack:** Angular 22 (standalone + signals) · Node.js/Express · MySQL · Socket.IO · JWT · Cloudinary · Leaflet · Web Push.

Live demo: https://wilson-pizzas.vercel.app — source is private (it runs a real business) but available on request for interviews.

</details>

---

## 🎸 STRUM & OCTAVE

Fork independiente activo de dos proyectos de [opria123](https://github.com/opria123): una IA que convierte canciones en charts jugables para Clone Hero/GHWTDE, y el editor visual de escritorio que los edita. Sigo iterando sobre la base original con crédito completo a opria123 — sin depender de su ritmo de releases.

<table align="center">
<tr>
<td width="50%" valign="top">

**[STRUM](https://github.com/Willyssj3/strum)** — *Spectral Transcription & Rhythm Understanding Model*

Pipeline de audio-a-chart con transcripción neuronal de batería, mapeo de trastes de guitarra/bajo, transcripción vocal (Whisper) y detección de teclado.

![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)

</td>
<td width="50%" valign="top">

**[OCTAVE](https://github.com/Willyssj3/octave)** <img src="assets/octave-logo.svg" width="16" height="16" alt="" /> — *Orchestrated Chart & Track Authoring Visual Editor*

Editor de escritorio para crear y ajustar charts a mano, integrado con STRUM. Electron + React + Three.js.

![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)

</td>
</tr>
</table>

<sub>Trabajando codo a codo con el upstream: [PR con LaneAcc en la tabla de performance](https://github.com/opria123/strum/pull/5) e [issue de doc/code drift](https://github.com/opria123/strum/issues) reportados sobre opria123/strum.</sub>

---

## 🛠️ Stack & herramientas

![Angular](https://img.shields.io/badge/Angular-DD0031?style=flat&logo=angular&logoColor=white)
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Node.js](https://img.shields.io/badge/Node.js-339933?style=flat&logo=node.js&logoColor=white)
![Express](https://img.shields.io/badge/Express-000000?style=flat&logo=express&logoColor=white)
![MySQL](https://img.shields.io/badge/MySQL-4479A1?style=flat&logo=mysql&logoColor=white)
![Socket.IO](https://img.shields.io/badge/Socket.IO-010101?style=flat&logo=socket.io&logoColor=white)
![React](https://img.shields.io/badge/React-61DAFB?style=flat&logo=react&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat&logo=pytorch&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-7952B3?style=flat&logo=bootstrap&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat&logo=git&logoColor=white)
![Vercel](https://img.shields.io/badge/Vercel-000000?style=flat&logo=vercel&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-0B0D0E?style=flat&logo=railway&logoColor=white)

**Además:** JWT, REST APIs, arquitectura en capas, integración con servicios externos (Cloudinary, LocationIQ, Web Push), Excel (ExcelJS), Postman, VS Code.

---

## 🎓 Formación

- **Tecnicatura Superior en Desarrollo de Software** — [Terciario Urquiza](https://terciariourquiza.edu.ar/), Rosario *(último año, segundo cuatrimestre — graduación estimada fines de 2026 / principios de 2027)*

---

## 🎮 Fuera del código

Cuando no estoy programando, lo más probable es que esté corriendo o jugando **League of Legends** — main **Heimerdinger** 🔧🤖 *(sí, hasta en el Rift me gusta construir cosas)*.

<div align="center">

![League of Legends](https://img.shields.io/badge/League%20of%20Legends-Heimerdinger%20main-C89B3C?style=for-the-badge)
![Running](https://img.shields.io/badge/Running-cuando%20el%20c%C3%B3digo%20me%20deja-FC4C02?style=for-the-badge&logo=strava&logoColor=white)

</div>

---

## 📊 GitHub stats

<div align="center">
<img src="https://streak-stats.demolab.com/?user=Willyssj3&theme=dark&hide_border=true" alt="Racha de contribuciones" height="165" />
</div>

<!--
El instance público de github-readme-stats.vercel.app está caído desde enero 2026
(503 DEPLOYMENT_PAUSED, ver https://github.com/anuraghazra/github-readme-stats/issues/4737).
Las tarjetas de "Estadísticas de GitHub" y "Lenguajes más usados" se sacaron temporalmente
para no mostrar imagen rota. Se pueden restaurar apenas se self-hostee una instancia propia
en Vercel (botón de deploy en el repo de anuraghazra/github-readme-stats), reemplazando el
dominio en estas URLs:
<img src="https://github-readme-stats.vercel.app/api?username=Willyssj3&show_icons=true&theme=dark&hide_border=true&count_private=true" alt="Estadísticas de GitHub" height="165" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Willyssj3&layout=compact&theme=dark&hide_border=true&langs_count=8" alt="Lenguajes más usados" height="165" />
-->

## 📈 Actividad

<div align="center">
<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/Willyssj3/Willyssj3/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/Willyssj3/Willyssj3/output/github-contribution-grid-snake.svg" />
  <img alt="Serpiente comiendo mis contribuciones" src="https://raw.githubusercontent.com/Willyssj3/Willyssj3/output/github-contribution-grid-snake.svg" width="100%" />
</picture>
</div>

---

<div align="center">

📫 **¿Hablamos?** [LinkedIn](https://www.linkedin.com/in/brian-williams-moro-570532193/) · brianmorossj3@gmail.com

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C89B3C,100:C0392B&height=100&section=footer" width="100%" alt="Footer" />

</div>
