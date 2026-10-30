<!-- ════════════════════════ CABECERA ════════════════════════ -->
<p align="center">
  <img src="assets/header.svg" width="100%" alt="Erwin González · Automatización con n8n, IA aplicada y Full Stack"/>
</p>

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&weight=500&size=17&duration=3000&pause=1200&color=00E5FF&center=true&vCenter=true&width=640&lines=Automatizo+procesos+de+negocio+con+n8n+%2B+IA;Despliego+agentes+de+IA+con+Claude+y+OpenAI;De+la+idea+al+prototipo+funcional+en+d%C3%ADas;Menos+trabajo+manual%2C+m%C3%A1s+negocio" alt="Automatizo procesos de negocio con n8n + IA"/>
</p>

<p align="center">
  <a href="https://portafolio-erwin.vercel.app/"><img src="https://img.shields.io/badge/Portafolio-00E5FF?style=for-the-badge&logo=vercel&logoColor=0B0F14" alt="Portafolio"/></a>
  <a href="https://www.linkedin.com/in/erwingonzalezbonilla"><img src="https://img.shields.io/badge/LinkedIn-161B22?style=for-the-badge&logo=linkedin&logoColor=00E5FF" alt="LinkedIn"/></a>
  <a href="mailto:alexcultural@gmail.com"><img src="https://img.shields.io/badge/Email-161B22?style=for-the-badge&logo=gmail&logoColor=00E5FF" alt="Email"/></a>
  <img src="https://komarev.com/ghpvc/?username=ErwinGonzalezBonilla&label=Visitas&color=161B22&style=for-the-badge" alt="Visitas"/>
</p>

<br/>

<!-- ════════════════════════ SOBRE MÍ ════════════════════════ -->
<table>
<tr>
<td width="58%" valign="top">

### Sobre mí

Durante **15+ años** gestioné inventario, compras, proveedores y equipos en Caracas, Santiago y Madrid. Hice a mano cientos de tareas que hoy sé automatizar.

Ahora construyo las herramientas que me habría gustado tener: **flujos con n8n**, **agentes y asistentes con IA** y **webs a medida** para negocios reales. Detecto dónde se pierde el tiempo en una operación y lo convierto en un prototipo funcional en días, no en meses.

**Busco:** rol de *AI Automation / AI Builder* en un equipo que quiera mover rápido. Presencial en Madrid o remoto.

</td>
<td width="42%" valign="top">

```ts
const erwin = {
  base:      "Madrid · presencial o remoto",
  foco:      ["n8n", "agentes de IA", "React", "Python"],
  día_a_día: ["Claude", "Claude Code", "ChatGPT", "OpenAI API"],
  idiomas:   { es: "nativo", en: "B1" },
  formación: "4Geeks Academy · Full Stack (2025)",
  próximo:   "AWS Cloud Practitioner",
  estado:    "disponible ✔",
};
```

</td>
</tr>
</table>

<!-- ════════════════════════ CIFRAS ════════════════════════ -->
<table align="center">
  <tr>
    <td align="center" width="190"><h2>15+</h2><sub>AÑOS EN NEGOCIOS<br/>REALES</sub></td>
    <td align="center" width="190"><h2>4</h2><sub>WEBS PARA<br/>CLIENTES</sub></td>
    <td align="center" width="190"><h2>3</h2><sub>PROYECTOS<br/>CON IA</sub></td>
    <td align="center" width="190"><h2>411</h2><sub>COMMITS EN<br/>EQUIPO</sub></td>
  </tr>
</table>

<br/>

<!-- ════════════════════════ SERVICIOS ════════════════════════ -->
## Qué hago

<table>
<tr>
<td width="33%" valign="top">

#### ⚡ Automatización
Flujos con **n8n** y **Make** que conectan formularios, hojas de cálculo, email y APIs, con reglas de negocio y ramas condicionales.

<sub>`recibir → clasificar → registrar → notificar`</sub>

</td>
<td width="33%" valign="top">

#### 🧠 IA aplicada
Agentes y asistentes con **Claude**, **OpenAI** y **Gemini** que atienden clientes, recomiendan productos y sugieren decisiones con datos reales.

<sub>`agentes · prompt engineering · APIs`</sub>

</td>
<td width="33%" valign="top">

#### 🌐 Webs y e-commerce
Webs, tiendas online y paneles con **React** y **Python**, con pagos con **Stripe**, gestión de stock y despliegue en Vercel.

<sub>`React · FastAPI · Flask · Stripe`</sub>

</td>
</tr>
</table>

<p align="center"><sub><b>CÓMO TRABAJO</b> &nbsp;·&nbsp; detectar el cuello de botella → prototipo funcional en días → medir → iterar</sub></p>

<br/>

<!-- ════════════════════════ PROYECTO DESTACADO ════════════════════════ -->
## Proyecto destacado

### [Automatización de solicitudes de clientes](https://github.com/ErwinGonzalezBonilla/n8n-gestion-solicitudes-clientes)

![En construcción](https://img.shields.io/badge/EN_CONSTRUCCIÓN-D29922?style=flat-square) ![n8n](https://img.shields.io/badge/n8n-161B22?style=flat-square&logo=n8n&logoColor=00E5FF) ![Google Sheets](https://img.shields.io/badge/Google_Sheets-161B22?style=flat-square&logo=googlesheets&logoColor=00E5FF) ![Gmail](https://img.shields.io/badge/Gmail-161B22?style=flat-square&logo=gmail&logoColor=00E5FF)

Un flujo en **n8n** que elimina el trabajo manual de recibir, revisar y organizar las solicitudes de clientes.

```mermaid
flowchart LR
    A["📝 Formulario<br/>datos · servicio · presupuesto"] --> B{"💶 Presupuesto<br/>≥ 300 €"}
    B -- Sí --> C["⭐ Prioritaria"]
    B -- No --> D["📋 Estándar"]
    C -.-> E[("📊 Google Sheets")]
    D -.-> E
    C -.-> F["📧 Email a negocio<br/>y cliente"]
    D -.-> F

    classDef base fill:#0D1117,stroke:#2B3540,color:#E6EDF3
    classDef hot fill:#0D1117,stroke:#00E5FF,color:#E6EDF3
    class A,C,D,E,F base
    class B hot
```

<sub>Línea continua: funcionando y probado con datos de prueba · Línea punteada: integración en curso</sub>

| Objetivo | Cómo | Estado |
|:---|:---|:---|
| Menos trabajo manual al gestionar solicitudes | Nodo **IF** con regla de negocio por presupuesto (≥ 300 €) | ✅ Validado con datos de prueba |
| Un registro central | **Google Sheets** como base de datos de solicitudes | 🔧 Integración en curso |
| Respuesta inmediata | **Email automático** al negocio y al cliente | 🔧 Integración y pruebas end-to-end |

<br/>

<!-- ════════════════════════ PROYECTOS ════════════════════════ -->
## Proyectos

<table>
<tr>
<td colspan="2" valign="top">

### 📦 [MyStock](https://github.com/ErwinGonzalezBonilla/MyStock) &nbsp;<img src="https://img.shields.io/badge/EN_CONSTRUCCIÓN-D29922?style=flat-square" alt="En construcción"/>

El software que me habría gustado tener en la tienda: **inventario, punto de venta, compras, clientes y proveedores** en un solo sitio. Incluye un **asistente de IA** que sugiere qué reponer y **automatizaciones con n8n** para las tareas repetitivas.

<sub>**Arquitectura** React → FastAPI → PostgreSQL → IA → n8n &nbsp;·&nbsp; **Seguridad** multi-tenant con JWT &nbsp;·&nbsp; **Producto** docs, roadmap y changelog</sub>

<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/OpenAI-161B22?style=flat-square&logo=openai&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/n8n-161B22?style=flat-square&logo=n8n&logoColor=00E5FF"/>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎤 [Kevin Alva](https://github.com/ErwinGonzalezBonilla/kevin-alva-web)
<img src="https://img.shields.io/badge/OPERATIVO-2EA043?style=flat-square"/> <img src="https://img.shields.io/badge/CLIENTE_REAL-161B22?style=flat-square"/>

Web de artista con **venta de entradas automatizada**: pago con Stripe → QR firmado (HMAC-SHA256) → validación en puerta.

<img src="https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=nodedotjs&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Stripe-161B22?style=flat-square&logo=stripe&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Vercel-161B22?style=flat-square&logo=vercel&logoColor=00E5FF"/>

**[Ver web →](https://www.kevinalvamusic.com)**

</td>
<td width="50%" valign="top">

### 🎈 [Ballonette](https://github.com/ErwinGonzalezBonilla/ballonette-react)
<img src="https://img.shields.io/badge/OPERATIVO-2EA043?style=flat-square"/> <img src="https://img.shields.io/badge/CLIENTE_REAL_·_IA-161B22?style=flat-square"/>

Web de eventos con galería, panel de administración y **BalloonBot**, un asistente con OpenAI que atiende a los clientes.

<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Cloudinary-161B22?style=flat-square&logo=cloudinary&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/OpenAI-161B22?style=flat-square&logo=openai&logoColor=00E5FF"/>

**[Ver web →](https://ballonette.com)**

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🐶 Don Dog · Tienda online
<img src="https://img.shields.io/badge/EN_CONSTRUCCIÓN-D29922?style=flat-square"/> <img src="https://img.shields.io/badge/CLIENTE_REAL_·_IA-161B22?style=flat-square"/>

Tienda para un pet shop con catálogo, carrito, **control de stock y pedidos**, y el bot **"El Don"**, que recomienda productos según la mascota y el stock disponible.

</td>
<td width="50%" valign="top">

### 💌 [Invitaciones](https://github.com/ErwinGonzalezBonilla/generador-invitaciones)
<img src="https://img.shields.io/badge/OPERATIVO-2EA043?style=flat-square"/> <img src="https://img.shields.io/badge/USO_PÚBLICO-161B22?style=flat-square"/>

Rellenas → vista previa → envío por WhatsApp. **Sin backend:** toda la invitación viaja en la URL.

<img src="https://img.shields.io/badge/HTML-161B22?style=flat-square&logo=html5&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/CSS-161B22?style=flat-square&logo=css3&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/JavaScript-161B22?style=flat-square&logo=javascript&logoColor=00E5FF"/>

**[Crear invitación →](https://generador-invitaciones.vercel.app)**

</td>
</tr>
<tr>
<td colspan="2" valign="top">

### 🐾 [Patitas Club](https://github.com/4GeeksAcademy/PatitasClub) &nbsp;<img src="https://img.shields.io/badge/COMPLETADO-2EA043?style=flat-square"/> <img src="https://img.shields.io/badge/EQUIPO_·_411_COMMITS-161B22?style=flat-square"/>

E-commerce para mascotas con API REST en Flask, login con JWT y pagos con Stripe. Proyecto final en equipo en 4Geeks Academy.

<img src="https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Flask-161B22?style=flat-square&logo=flask&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/SQLAlchemy-161B22?style=flat-square&logo=sqlalchemy&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Stripe-161B22?style=flat-square&logo=stripe&logoColor=00E5FF"/>

</td>
</tr>
</table>

<br/>

<!-- ════════════════════════ STACK ════════════════════════ -->
## Stack

| | |
|:---|:---|
| **Automatización** | <img src="https://img.shields.io/badge/n8n-161B22?style=for-the-badge&logo=n8n&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Make-161B22?style=for-the-badge&logo=make&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Webhooks-161B22?style=for-the-badge&logo=webhooks&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Google_Sheets-161B22?style=for-the-badge&logo=googlesheets&logoColor=00E5FF"/> |
| **IA** | <img src="https://img.shields.io/badge/OpenAI-161B22?style=for-the-badge&logo=openai&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Claude-161B22?style=for-the-badge&logo=anthropic&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Gemini-161B22?style=for-the-badge&logo=googlegemini&logoColor=00E5FF"/> |
| **Frontend** | <img src="https://skillicons.dev/icons?i=react,vite,js,html,css,bootstrap&theme=dark&perline=8" height="40"/> |
| **Backend** | <img src="https://skillicons.dev/icons?i=python,fastapi,flask,nodejs&theme=dark" height="40"/> |
| **Datos** | <img src="https://skillicons.dev/icons?i=postgres,mysql&theme=dark" height="40"/> |
| **Herramientas** | <img src="https://skillicons.dev/icons?i=git,github,vercel,vscode,postman&theme=dark" height="40"/> |
| **Servicios** | <img src="https://img.shields.io/badge/Stripe-161B22?style=for-the-badge&logo=stripe&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Cloudinary-161B22?style=for-the-badge&logo=cloudinary&logoColor=00E5FF"/> <img src="https://img.shields.io/badge/Gmail-161B22?style=for-the-badge&logo=gmail&logoColor=00E5FF"/> |

<br/>

<!-- ════════════════════════ TRAYECTORIA ════════════════════════ -->
## Trayectoria

<table>
<tr>
<td width="33%" valign="top">

**ANTES**<br/>
<sub>Caracas 🇻🇪 → Santiago 🇨🇱</sub>

15+ años en inventario, compras, proveedores y equipos. Entiendo cómo funciona un negocio por dentro y dónde se pierde el tiempo.

</td>
<td width="33%" valign="top">

**AHORA**<br/>
<sub>Madrid 🇪🇸 · 2025 →</sub>

Formación Full Stack en 4Geeks Academy. Automatizo con **n8n**, integro **IA** y construyo webs para clientes reales.

</td>
<td width="33%" valign="top">

**PRÓXIMO**<br/>
<sub>En curso</sub>

Primer rol en automatización o desarrollo. Preparando **AWS Cloud Practitioner**.

`███████░░░ 70%`

</td>
</tr>
</table>

<br/>

<!-- ════════════════════════ ACTIVIDAD ════════════════════════ -->
## Actividad en GitHub

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=ErwinGonzalezBonilla&show_icons=true&hide_border=true&bg_color=0D1117&title_color=00E5FF&icon_color=00E5FF&text_color=C9D1D9&locale=es&hide_rank=true" alt="Estadísticas"/>
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=ErwinGonzalezBonilla&layout=compact&hide_border=true&bg_color=0D1117&title_color=00E5FF&text_color=C9D1D9&locale=es" alt="Lenguajes"/>
</p>

<p align="center">
  <img width="100%" src="https://github-readme-activity-graph.vercel.app/graph?username=ErwinGonzalezBonilla&bg_color=0D1117&color=8B949E&title_color=00E5FF&line=00E5FF&point=FFFFFF&area=true&area_color=00E5FF&hide_border=true&radius=8" alt="Actividad"/>
</p>

<br/>

<!-- ════════════════════════ CONTACTO ════════════════════════ -->
<p align="center">
  <b>¿Tienes un proceso que se repite cada día?</b><br/>
  <sub>Probablemente se puede automatizar. Hablemos.</sub>
  <br/><br/>
  <a href="https://www.linkedin.com/in/erwingonzalezbonilla"><img src="https://img.shields.io/badge/Escríbeme_por_LinkedIn-00E5FF?style=for-the-badge&logo=linkedin&logoColor=0B0F14" alt="LinkedIn"/></a>
  <a href="mailto:alexcultural@gmail.com"><img src="https://img.shields.io/badge/Enviar_email-161B22?style=for-the-badge&logo=gmail&logoColor=00E5FF" alt="Email"/></a>
  <a href="https://portafolio-erwin.vercel.app/"><img src="https://img.shields.io/badge/Ver_portafolio-161B22?style=for-the-badge&logo=vercel&logoColor=00E5FF" alt="Portafolio"/></a>
</p>

<img src="https://capsule-render.vercel.app/api?type=rect&color=0:0B0F14,50:00E5FF,100:0B0F14&height=2&section=footer" width="100%"/>
