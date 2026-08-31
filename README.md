<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:C0392B,100:C89B3C&height=200&section=header&text=Brian%20Moro%20(Willy)&fontSize=45&fontColor=ffffff&animation=fadeIn&desc=Full%20Stack%20Developer&descAlignY=75&descSize=18" width="100%" alt="Header" />

[![Typing SVG](https://readme-typing-svg.demolab.com/?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=C89B3C&center=true&vCenter=true&width=600&lines=Angular+%C2%B7+Node.js+%C2%B7+MySQL;Construyendo+Wilson+Pizzas+de+punta+a+punta;Corriendo+y+jugando+LoL+en+mis+ratos+libres+%F0%9F%8F%83)](https://git.io/typing-svg)

📍 Rosario, Santa Fe, Argentina · 💼 Disponible para trabajos freelance

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/brian-williams-moro-570532193/)
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:brianmorossj3@gmail.com)
[![CV](https://img.shields.io/badge/📄_CV-Descargar-4CAF50?style=flat)](assets/Brian_Williams_Moro_CV.pdf)

</div>

Estudiante de la **Tecnicatura Superior en Desarrollo de Software** en el [Terciario Urquiza](https://terciariourquiza.edu.ar/), Rosario. Aprendo construyendo proyectos reales de punta a punta: desde la base de datos hasta la interfaz, pasando por el deploy en producción.

*Full Stack Developer student (Angular · Node.js · MySQL), based in Rosario, Argentina. I learn by shipping real, production-deployed projects — not just tutorials.*

Además, hace más de 3 años lidero equipos y capacito personal en Konecta (sector Telecom) — combino ese perfil de liderazgo y resolución de problemas con el técnico.

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

**Cursos y certificaciones:** JavaScript - De Cero a Experto (Udemy) · Metodologías Ágiles (Konecta) · Gestión de Proyecto PMI (Konecta) · Liderazgo (Santander Open Academy)

---

## 🎮 Fuera del código

Cuando no estoy programando, lo más probable es que esté corriendo, leyendo o jugando **League of Legends** — main **Heimerdinger** 🔧🤖 *(sí, hasta en el Rift me gusta construir cosas)*.

<div align="center">

![League of Legends](https://img.shields.io/badge/League%20of%20Legends-Heimerdinger%20main-C89B3C?style=for-the-badge)
![Running](https://img.shields.io/badge/Running-cuando%20el%20c%C3%B3digo%20me%20deja-FC4C02?style=for-the-badge&logo=strava&logoColor=white)

</div>

---

## 📚 Mi Biblioteca

Fuera del código, leo bastante — llevo el registro en [Fable](https://fable.co/fabler/brian-moro-238941921118) (Level 26). Van 44 libros entre leídos, en curso y en la lista.

<div align="center">
<img src="https://covers.openlibrary.org/b/id/465226-M.jpg" width="46" alt="El Hombre En Busca del Sentido Ultimo" title="El Hombre En Busca del Sentido Ultimo — Viktor E. Frankl" />
<img src="https://covers.openlibrary.org/b/id/11200092-M.jpg" width="46" alt="Proyecto Hail Mary" title="Proyecto Hail Mary — Andy Weir" />
<img src="https://covers.openlibrary.org/b/id/7396660-M.jpg" width="46" alt="Percy Jackson y los dioses griegos" title="Percy Jackson y los dioses griegos — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/11261770-M.jpg" width="46" alt="Rebelion en la Granja" title="Rebelion en la Granja — George Orwell" />
<img src="https://covers.openlibrary.org/b/id/12855074-M.jpg" width="46" alt="Navidades Tragicas" title="Navidades Tragicas — Agatha Christie" />
<img src="https://covers.openlibrary.org/b/id/12875748-M.jpg" width="46" alt="A Christmas Carol" title="A Christmas Carol — Charles Dickens" />
<img src="https://covers.openlibrary.org/b/id/14826658-M.jpg" width="46" alt="Las Indignas" title="Las Indignas — Agustina Bazterrica" />
<img src="https://covers.openlibrary.org/b/id/14420680-M.jpg" width="46" alt="The Demigod Files" title="The Demigod Files — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/9085353-M.jpg" width="46" alt="La llamada de Cthulhu" title="La llamada de Cthulhu — H.P. Lovecraft" />
<img src="https://covers.openlibrary.org/b/id/6624107-M.jpg" width="46" alt="Percy Jackson y el ultimo heroe del Olimpo" title="Percy Jackson y el ultimo heroe del Olimpo — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/12528372-M.jpg" width="46" alt="Prohibido suicidarse en primavera" title="Prohibido suicidarse en primavera — Alejandro Casona" />
<img src="https://covers.openlibrary.org/b/id/14263955-M.jpg" width="46" alt="Fugitivos en el tiempo" title="Fugitivos en el tiempo — Dalas Review" />
<img src="https://covers.openlibrary.org/b/id/14265077-M.jpg" width="46" alt="La vida es un chiste" title="La vida es un chiste — Zorman" />
<img src="https://covers.openlibrary.org/b/id/10871153-M.jpg" width="46" alt="Huesos Desnudos" title="Huesos Desnudos — Domergue" />
<img src="https://covers.openlibrary.org/b/id/10107644-M.jpg" width="46" alt="La sombra del viento" title="La sombra del viento — Carlos Ruiz Zafon" />
<img src="https://covers.openlibrary.org/b/id/8775559-M.jpg" width="46" alt="Mujercitas" title="Mujercitas — Louisa May Alcott" />
<img src="https://covers.openlibrary.org/b/id/6274739-M.jpg" width="46" alt="La batalla del laberinto" title="La batalla del laberinto — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/14601475-M.jpg" width="46" alt="Percy Jackson y la maldicion del titan" title="Percy Jackson y la maldicion del titan — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/108909-M.jpg" width="46" alt="Percy Jackson y el mar de los monstruos" title="Percy Jackson y el mar de los monstruos — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/7239831-M.jpg" width="46" alt="Percy Jackson y el ladron del rayo" title="Percy Jackson y el ladron del rayo — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/11793784-M.jpg" width="46" alt="William Wilson" title="William Wilson — Edgar Allan Poe" />
<img src="https://covers.openlibrary.org/b/id/13012029-M.jpg" width="46" alt="Percy Jackson y los heroes griegos" title="Percy Jackson y los heroes griegos — Rick Riordan" />
<img src="https://covers.openlibrary.org/b/id/8236920-M.jpg" width="46" alt="Colmillo Blanco" title="Colmillo Blanco — Jack London" />
<img src="https://covers.openlibrary.org/b/id/9267242-M.jpg" width="46" alt="1984" title="1984 — George Orwell" />
<img src="https://covers.openlibrary.org/b/id/12820198-M.jpg" width="46" alt="La metamorfosis" title="La metamorfosis — Franz Kafka" />
<img src="https://covers.openlibrary.org/b/id/12356249-M.jpg" width="46" alt="Frankenstein" title="Frankenstein — Mary Shelley" />
<img src="https://covers.openlibrary.org/b/id/14314858-M.jpg" width="46" alt="El retrato de Dorian Gray" title="El retrato de Dorian Gray — Oscar Wilde" />
<img src="https://covers.openlibrary.org/b/id/6960817-M.jpg" width="46" alt="El fantasma de Canterville" title="El fantasma de Canterville — Oscar Wilde" />
<img src="https://covers.openlibrary.org/b/id/13291765-M.jpg" width="46" alt="God of Malice" title="God of Malice — Rina Kent" />
<img src="https://covers.openlibrary.org/b/id/10585333-M.jpg" width="46" alt="El adversario" title="El adversario — Emmanuel Carrere" />
<img src="https://covers.openlibrary.org/b/id/14157290-M.jpg" width="46" alt="Ventisca" title="Ventisca — Marie Vingtras" />
<img src="https://covers.openlibrary.org/b/id/8052311-M.jpg" width="46" alt="Soy asesino y padre de familia" title="Soy asesino y padre de familia — Fabio Rubiano" />
<img src="https://covers.openlibrary.org/b/id/3362684-M.jpg" width="46" alt="Martin Fierro" title="Martin Fierro — Jose Hernandez" />
</div>

<details>
<summary><b>📖 Leyendo ahora (4)</b></summary>
<br>

- **El Hombre En Busca del Sentido Ultimo** — Viktor E. Frankl
- **Proyecto Hail Mary** — Andy Weir
- **Memento Mori** — Humberto Montesinos
- **Percy Jackson y los dioses griegos** — Rick Riordan

</details>

<details>
<summary><b>✅ Terminados (20)</b></summary>
<br>

- **Rebelion en la Granja** — George Orwell
- **Navidades Tragicas** — Agatha Christie
- **A Christmas Carol** — Charles Dickens
- **Las Indignas** — Agustina Bazterrica
- **Percy Jackson and the Olympians The Ultimate Guide** — Rick Riordan
- **The Demigod Files** — Rick Riordan
- **La llamada de Cthulhu** — H.P. Lovecraft
- **Percy Jackson y el ultimo heroe del Olimpo** — Rick Riordan
- **El hombre de tiza** — C.J. Tudor
- **Prohibido suicidarse en primavera** — Alejandro Casona
- **Fugitivos en el tiempo** — Dalas Review
- **La vida es un chiste** — Zorman
- **Huesos Desnudos** — Domergue
- **La sombra del dinosaurio** — Pablo De Santis
- **La sombra del viento** — Carlos Ruiz Zafon
- **Mujercitas** — Louisa May Alcott
- **La batalla del laberinto** — Rick Riordan
- **Percy Jackson y la maldicion del titan** — Rick Riordan
- **Percy Jackson y el mar de los monstruos** — Rick Riordan
- **Percy Jackson y el ladron del rayo** — Rick Riordan

</details>

<details>
<summary><b>📌 Quiero leer (20)</b></summary>
<br>

- **Rebelion en la Granja** — George Orwell
- **La libreria de los deseos** — Eric de Kermel
- **William Wilson** — Edgar Allan Poe
- **Percy Jackson y los heroes griegos** — Rick Riordan
- **Colmillo Blanco** — Jack London
- **Mi Planta de Naranja-Lima** — Jose Mauro de Vasconcelos
- **1984** — George Orwell
- **La metamorfosis** — Franz Kafka
- **Frankenstein** — Mary Shelley
- **El retrato de Dorian Gray** — Oscar Wilde
- **El fantasma de Canterville** — Oscar Wilde
- **God of Malice** — Rina Kent
- **El ultimo amor de Baba Dunja** — Alina Bronsky
- **Come Hombres** — Ryan Green
- **Una pizca de maldad** — A Yi
- **El adversario** — Emmanuel Carrere
- **Ventisca** — Marie Vingtras
- **Soy asesino y padre de familia** — Fabio Rubiano
- **Donde las mentiras sean eternas** — Pamela Stupia
- **Martin Fierro** — Jose Hernandez

</details>

---

## 📊 GitHub stats

<table align="center">
<tr>
<td><img src="assets/github-stats.svg" alt="Estadísticas de GitHub" height="165" /></td>
<td><img src="assets/streak-stats.svg" alt="Racha de contribuciones" height="165" /></td>
</tr>
</table>

<sub>Estas tarjetas se generan solas todos los días vía GitHub Actions (<a href=".github/workflows/stats.yml">stats.yml</a>) y quedan commiteadas acá mismo — no dependen de que un servicio externo esté arriba en el momento en que alguien entra a mi perfil.</sub>

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
