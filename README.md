<div align="center">
<img src="img/banner.svg" alt="Samuel Bugueño Vega — desarrollo web y automatización" width="100%">
</div>

<div align="center">

![SvelteKit](https://img.shields.io/badge/SvelteKit_5-FF3E00?logo=svelte&logoColor=white) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?logo=typescript&logoColor=white) ![Tailwind](https://img.shields.io/badge/Tailwind_4-06B6D4?logo=tailwindcss&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-FFCA28?logo=firebase&logoColor=black) ![Node](https://img.shields.io/badge/Node.js-5FA04E?logo=nodedotjs&logoColor=white) ![Java](https://img.shields.io/badge/Java-ED8B00?logo=openjdk&logoColor=white) ![Android](https://img.shields.io/badge/Android-34A853?logo=android&logoColor=white) ![Playwright](https://img.shields.io/badge/Playwright-2EAD33?logo=playwright&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?logo=docker&logoColor=white)

</div>

## Sobre mí

Desarrollador **full-stack independiente** desde Ovalle, Región de Coquimbo (Chile).
Construyo soluciones web para negocios y proyectos de interés público: menús digitales,
sistemas de pedidos, e-commerce y automatización con IA.

Me gusta llevar cada proyecto **de punta a punta** — diseño, datos, pruebas y despliegue —
y entregar productos funcionales, rápidos y fáciles de usar para gente que no es técnica.

## Lo que hago

- **Aplicaciones web** con SvelteKit 5 + TypeScript
- **Menús digitales y sistemas de pedidos** para restaurantes y negocios locales
- **E-commerce y catálogos** con carrito, tallas y checkout
- **Datos públicos**: catálogos, costos y dashboards con la fuente al pie
- **Apps Android nativas** en Java
- **Automatización con IA** para tareas repetitivas de negocio
- **UI cuidada**: responsive, accesible (contraste AA) y rápida

## Proyectos

> El código de estos proyectos es privado. **Lo que está abierto es el producto**: entrá,
> usalo y juzgalo vos mismo.

### 🧭 Brújula — orientación vocacional y costo real de estudiar

Web para estudiantes de 3° y 4° medio de la Región de Coquimbo: **cuánto cuesta realmente
estudiar** una carrera, cuánto se gana después y qué alternativas existen cerca de casa.
Datos de fuentes públicas (SIES, INE, Mineduc), calculadora con desglose de costos y
comparación de cada carrera contra el promedio de su área.

571 carreras · 18 instituciones · cada cifra con su fuente y su año a la vista.

<div align="center">

### **[→ Abrir el sitio: brujula-coquimbo.web.app](https://brujula-coquimbo.web.app)**

</div>

*SvelteKit 5 · TypeScript · CSS propio por capas · sin dependencias de interfaz · beta en desarrollo.*

<table>
<tr>
<td width="33%"><img src="img/brujula-inicio.png" alt="Inicio Brújula"><br><sub>Portada</sub></td>
<td width="33%"><img src="img/brujula-calculadora.png" alt="Calculadora de costos"><br><sub>Calculadora de costos</sub></td>
<td width="33%"><img src="img/brujula-ficha.png" alt="Ficha de carrera"><br><sub>Ficha de carrera</sub></td>
</tr>
</table>

<img src="img/brujula-carreras.png" alt="Listado de carreras con buscador y filtros">

### 🌭 Los Ñeñecos — menú digital y pedidos para un local de comida al paso

PWA de menú digital y pedidos para **Comida al Paso Los Ñeñecos** (Ovalle). El cliente entra
desde el teléfono, arma su pedido y lo envía sin instalar nada; el local lo recibe en una
pantalla de cocina.

Catálogo en vivo sincronizado con Firestore, carrito y checkout, **panel de cocina** para
seguir el estado de cada pedido, panel de administración con roles (productos, categorías,
precios y promociones), botón directo de WhatsApp, modo oscuro y QA automatizado con
Vitest + Playwright sobre GitHub Actions.

<div align="center">

### **[→ Abrir el menú: nenekos-c1e77.web.app](https://nenekos-c1e77.web.app)**

</div>

*SvelteKit 5 · TypeScript · Tailwind CSS 4 · Firebase (Firestore, Auth, Hosting) · PWA.*

<table>
<tr>
<td width="33%"><img src="img/nenecos-menu.jpg" alt="Menú digital Los Ñeñecos"><br><sub>Menú en escritorio</sub></td>
<td width="33%"><img src="img/nenecos-menu-movil.jpg" alt="Menú en teléfono"><br><sub>La vista que usa el cliente</sub></td>
<td width="33%"><img src="img/nenecos-checkout.png" alt="Checkout del pedido"><br><sub>Checkout paso a paso</sub></td>
</tr>
</table>

### 🖤 GA Streetwear — e-commerce de una marca de ropa

Tienda online para la marca de streetwear **Giovani Ambiziosi** (Drop 01 · *Destinato alla
Vittoria*): catálogo con selección de tallas, estados de inventario, carrito persistente,
checkout guiado con retiro o delivery, seguimiento del pedido para el cliente y panel de
administración completo.

Es una **marca ficticia**: la armé como pieza de portafolio para construir la identidad
visual, el flujo de compra y el panel de admin de punta a punta, sin depender de un cliente
real.

<table>
<tr>
<td width="50%"><img src="img/ga-streetwear-inicio.jpg" alt="GA Streetwear — portada"><br><sub>Portada (escritorio)</sub></td>
<td width="50%"><img src="img/ga-streetwear-inicio-movil.jpg" alt="GA Streetwear — portada móvil"><br><sub>Portada (teléfono)</sub></td>
</tr>
</table>

*SvelteKit 5 · TypeScript 6 · Tailwind CSS 4 · Playwright · catálogo de prueba, sin backend real.*

### 📦 BodegaExpress — gestión de bodega en Android

App Android **nativa en Java** que cubre el ciclo completo de una bodega: inicio de sesión con
roles, alta, edición y búsqueda de productos, registro de entradas y salidas con validación de
stock, dashboard de indicadores y alerta de stock bajo.

La resolví como sistema, no como ejercicio: capas separadas (`data` · `model` · `ui` · `util`)
sobre un repositorio con semilla de datos, y un módulo de UI propio con vistas reutilizables
(cabeceras de sección, campos de formulario y badges de estado) en lugar de repetir la
interfaz pantalla por pantalla.

*Android SDK nativo · Java · Gradle Kotlin DSL · RecyclerView · ConstraintLayout.*

## Cómo trabajo

- **Pruebas antes de publicar:** cada entrega corre verificaciones automáticas (lógica de
  dominio, render en varios tamaños de pantalla, cero errores de consola) y no se publica si algo falla.
- **Accesibilidad y rendimiento** como parte del trabajo, no como extra.
- **Datos con fuente:** cada cifra va con su origen y su año a la vista.
- **Documentación** para que el proyecto siga vivo sin mí.

## Stack

| Capa | Tecnologías |
|------|-------------|
| Frontend | SvelteKit 5 · Svelte 5 · TypeScript · Tailwind CSS 4 · CSS propio por capas |
| Móvil | Android nativo · Java · Gradle KTS · componentes de UI reutilizables |
| Backend y datos | Firebase (Firestore, Auth, Functions) · Node.js · APIs REST |
| Pruebas | Playwright · Vitest · scripts de auditoría propios |
| Infra | Docker · GitHub Actions · despliegue en servidor propio |

---

<div align="center">
<sub>Ovalle, Región de Coquimbo · Chile — abierto a proyectos y colaboraciones.</sub>
</div>
