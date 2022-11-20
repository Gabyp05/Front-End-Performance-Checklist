<h1 align="center">
<br>
  <a href="https://github.com/dagerzuga/Front-End-Performance-Checklist">
    <img src="https://raw.githubusercontent.com/dagerzuga/Front-End-Performance-Checklist/master/images/logo-front-end-performance-checklist.jpg" alt="" width="170">
  </a>
  <br>
  <br>
    Check list para rendimento Front-End
  <br>
</h1>

<h4 align="center">🎮 La lista de requerimientos más rápida de todas</h4>
<p align="center">Una simple regla: "Diseñe y programe teniendo en cuenta el rendimiento"</p>

<p align="center">
  <a href="http://makeapullrequest.com">
    <img src="https://img.shields.io/badge/PRs-bienvenidas-brightgreen.svg?style=flat-square" alt="Se aceptan PRs">
  </a>
  <a href="https://discord.gg/btHQRkm">
    <img src="https://img.shields.io/badge/chat-en_discord-4837E2.svg?style=flat-square" alt="Chat en Discord">
  </a>
  <a href="https://opensource.org/licenses/MIT">
    <img src="https://img.shields.io/badge/licencia-MIT-blue.svg?style=flat-square" alt="Licencia MIT">
  </a>
</p>

<p align="center">
  <a href="#cómo-se-usa">¿Cómo se usa?</a> • <a href="#contribuir">Contribuir</a> • <a href="https://www.producthunt.com/posts/front-end-performance-checklist">Product Hunt</a>
</p>

<p align="center">
  <a href="https://github.com/thedaviddias/Front-End-Performance-Checklist">🇺🇸</a>
  <a href="https://github.com/JohnsenZhou/Front-End-Performance-Checklist">🇨🇳</a>
  <a href="https://github.com/WilliamDASILVA/Front-End-Performance-Checklist">🇫🇷</a>
  <a href="https://github.com/ParkSB/Front-End-Performance-Checklist">🇰🇷</a>
  <a href="https://github.com/fernandofawkes/Front-End-Performance-Checklist">🇵🇹</a>
  <a href="https://github.com/lex111/Front-End-Performance-Checklist">🇷🇺</a>
  <a href="https://github.com/GameWith/Front-End-Performance-Checklist">🇯🇵</a>
  <a href="https://github.com/ms-fadaei/Front-End-Performance-Checklist">🇮🇷</a>
  <a href="https://github.com/huynhan147/FrontEnd-Performance-Checklist">🇻🇳</a>
  <a href="https://github.com/mbiesiad/Front-End-Performance-Checklist">🇵🇱</a>
</p>

<p align="center">
    <span>Otros checklists (en inglés):</span>
    <br>
    🗂 <a href="https://github.com/thedaviddias/Front-End-Checklist#---------front-end-checklist-">Front-End checklist</a> • 💎 <a href="https://github.com/thedaviddias/Front-End-Design-Checklist#front-end-design-checklist">Front-End checklist para diseño</a>
</p>

## Nota de traducción
Este projecto fue originalmente hecho en inglés, por lo cual, muchos enlaces y referencias - como con los articulos, plugins u otras recomendaciones - apuntan a sitios que están en inglés. Por favor, tomar esto en cuenta al momento de utilziar esta versión traducida al español. Asimismo, los nombres propios de sitios, herramientas y algunos otros elementos no serán traducidos al español y así evitar dar una falsa imagen de que dichos productos están también en español.

## Introducción

El rendimiento es un tema amplio, pero no es siempre un tema del lado del back-end o del administrador. También es responsabilidad del front-end. Este checklist contiene una exhaustiva recopilación de elementos que deberías revisar, o al menos ser consciente de ellos como desarrollador front-end y aplicarla a tu proyecto (personal y profesional).

### ¿Cómo se usa?

Para cada regla, habrá un párrafo explicando *el porqué* de la importancia de esta regla y *cómo* se puede arreglar. Para más información, se encontrarán links que redirigirán a 🛠 herramientas, 📖 artículos, o 📹 contenido multimedia que puede completar la lista de requerimientos.

Todos los elementos de este checklist son esenciales para lograr el mayor porcentaje de rendimiento, pero habrán indicadores para ayuadar a eventualmente priorizar unas reglas sobre otras:

* ![baja][low] Significa que tiene una prioridad **baja**.
* ![media][medium] Significa que tiene un prioridad **media**. No se debería evitar abordar este elemento.
* ![alta][high] Significa que el elemento tiene una prioridad **alta**. No se puede evitar seguir la regla e implementar las correciones recomendadas.

### Herramientas para rendimiento

Lista de herramientas que puede utilizar para probar o monitorear el sitio o aplicación:

 * 🛠 [WebPagetest - Website Performance and Optimization Test](https://www.webpagetest.org/)
 * 🛠 ☆ [Dareboost: Website Speed Test and Website Analysis](https://www.dareboost.com/)
 * 🛠 [Treo: Page Speed Monitoring](https://treo.sh/?ref=perfchecklist)
 * 🛠 [GTmetrix | Website Speed and Performance Optimization](https://gtmetrix.com/)
 * 🛠 [PageSpeed Insights](https://developers.google.com/speed/pagespeed/insights/)
 * 🛠 [Web.dev](https://web.dev/measure)
 * 🛠 [Pingdom Website Speed Test](https://tools.pingdom.com)
 * 📖 [Make the Web Faster | Google Developers](https://developers.google.com/speed/)
 * 🛠 [Sitespeed.io - Welcome to the wonderful world of Web Performance](https://www.sitespeed.io/)
 * 🛠 [Calibre](https://calibreapp.com/)
 * 🛠 [Website Speed Test | Check Web Performance &raquo; Dotcom-Tools](https://www.dotcom-tools.com/website-speed-test.aspx)
 * 🛠 [Website and Server Uptime Monitoring - Pingdom](https://www.pingdom.com/product/uptime-monitoring/) ([Free Signup Link](https://www.pingdom.com/free))
 * 🛠 [Uptime Robot](https://uptimerobot.com)
 * 🛠 [SpeedCurve: Monitor front-end performance](https://speedcurve.com)
 * 🛠 [PWMetrics - CLI tool and lib to gather performance metrics](https://github.com/paulirish/pwmetrics)
 * 🛠 [Varvy - Page speed optimization]( https://varvy.com/pagespeed/)
 * 🛠 [Lighthouse - Google]( https://developers.google.com/web/tools/lighthouse/#devtools)
 * 🛠 [Checkbot browser extension - Checks for web performance best practices](https://www.checkbot.io/)
 * 🛠 [Yellow Lab Tools | Online test to help speeding up heavy web pages](https://yellowlab.tools/)
 * 🛠 [Speedrank - Web Performance Monitoring](https://speedrank.app/)
 * 🛠 [DebugBear - Monitor website performance and Lighthouse scores](https://www.debugbear.com/)
 * 🛠 [packtracker.io - Check your webpack bundle size on every pull request.](https://packtracker.io/)
 * 🛠 [Exthouse - Analyze the impact of a browser extension on web performance](https://github.com/treosh/exthouse)
 * 🛠 [LogRocket - Measure front-end performance in production apps](https://logrocket.com)

### Referencias

 * 📹 [The Cost Of JavaScript - YouTube](https://www.youtube.com/watch?v=_bzqF05xsC4) ([text version](https://medium.com/@addyosmani/the-cost-of-javascript-in-2018-7d8950fbb5d4))
 * [AddyOsmani.com - Start Performance Budgeting](https://addyosmani.com/blog/performance-budgets/)
 * 📖 [Get Started With Analyzing Runtime Performance  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/evaluate-performance/)
 * 📖 [State of the Web | 2018_01_01](https://httparchive.org/reports/state-of-the-web?start=2018_01_01)
 * 📖 [Page Weight Doesn't Matter](https://www.speedshop.co/2015/11/05/page-weight-doesnt-matter.html)
 * 📖 [Front-End Performance Checklist 2021 [PDF, Apple Pages, MS Word]](https://www.smashingmagazine.com/2021/01/front-end-performance-2021-free-pdf-checklist/)
 * 📖 [Designing for Performance Weighing Aesthetics and Speed - By Lara Callender Hogan [eBook, Print]](http://designingforperformance.com/index.html)
 * 📖 [Varvy - Web performance glossary](https://varvy.com/performance/)
 * 📖 [fabkrum/web-performance-resources: Up to date collection of valuable web performance resources](https://github.com/fabkrum/web-performance-resources)
 * 📖 [Checkbot - Web Speed Best Practices](https://www.checkbot.io/guide/speed/)
 * 🛠 [Progressive Tooling - A list of community-built, third-party tools that can be used to improve page performance](https://progressivetooling.com/)

---

## HTML

![html]

- [ ] **Minificar el HTML:** ![medium] El código HTML se minimiza, los comentarios, espacios en blanco y las nuevas líneas se eliminan de los archivos de producción.

    *¿Por qué?:*
    > Remover espacios innecesarios, comentarios, y atributos reduce el tamaño del HTML y acelera el tiempo de carga de la página.

    *¿Cómo?:*
    > La mayoría de los frameworks tienen plugins para facilitar la minificación de las páginas web. Puedes utilizar un montón de módulos de NPM que pueden hacer el trabajo por ti automáticamente.

    * 🛠 [HTML minifier | Minify Code](http://minifycode.com/html-minifier/)
    * 🛠 [Online HTML Compressor](http://refresh-sf.com)
    * 📖 [Experimenting with HTML minifier — Perfection Kills](http://perfectionkills.com/experimenting-with-html-minifier/#use_short_doctype)
   
- [ ] **Siempre colocar las etiquetas CSS antes que las etiquetas Javascript:** ![high] Asegúrese que tu CSS siempre carga antes que el código Javascript.

    ```html
    <!-- No recomendado -->
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    <link rel="stylesheet" href="foo.css"/>

    <!-- Recomendado -->
    <link rel="stylesheet" href="foo.css"/>
    <script src="jquery.js"></script>
    <script src="foo.js"></script>
    ```

   *¿Por qué?:*
    > Tener las etiquetas CSS antes que el Javascript permite una mejor descarga paralela, lo que optimiza el tiempo de carga del navegador.

    *¿Cómo?:*
    > Asegúrese que las etiquetas `<link>` y `<style>` en `<head>`siempre vayan antes que `<script>`.

    * 📖 [Ordering your styles and scripts for pagespeed](https://varvy.com/pagespeed/style-script-order.html)

- [ ] **Minimiza el número de los iframes:** ![high] Usa iframes solo si no tienes otra posibilidad técnica. Intenta evitar iframes tanto como puedas.

- [ ] **Optimizar la pre-carga con prefetch, dns-prefetch y prerender:** ![low] Los navegadores populares pueden usar la directiva en la etiqueta `<enlace>` y el atributo "rel" con ciertas palabras clave para precargar URL específicas.

   *¿Por qué?:*
    > La captación previa permite que un navegador obtenga silenciosamente los recursos necesarios para mostrar contenido al que un usuario podría acceder en un futuro próximo. El navegador puede almacenar estos recursos en su caché y acelerar la forma en que se cargan las páginas web cuando utilizan diferentes dominios para los recursos de la página. Cuando una página web ha terminado de cargarse y ha pasado el tiempo de inactividad, el navegador comienza a descargar otros recursos. Cuando un usuario ingresa a un enlace en particular (ya precargado), el contenido se servirá instantáneamente.

    *¿Cómo?:*
    > Asegúrate de que `<link>` esté en tu sección `<head>`.

    * 📖 [What Is Prefetching and Why Use It](https://www.keycdn.com/support/prefetching)
    * 📖 [Prefetching, preloading, prebrowsing](https://css-tricks.com/prefetching-preloading-prebrowsing/)
    * 📖 [What is Preload, Prefetch, and Preconnect](https://www.keycdn.com/blog/resource-hints)

**[⬆ Regresar al inicio](#introducción)**

## CSS

![css]

- [ ] **Minification:** ![high] Todos los archivos CSS se minimizan, los comentarios, los espacios en blanco y las nuevas líneas se eliminan de los archivos de producción.

   *¿Por qué?:*
    > Cuando se minimizan los archivos CSS, el contenido se carga más rápido y se envían menos datos al cliente. Es importante minimizar siempre los archivos CSS en producción. Es beneficioso para el usuario como lo es para cualquier empresa que desee reducir los costos de ancho de banda y reducir el uso de recursos.

    *¿Cómo?:*
    > Use herramientas para minimizar sus archivos automáticamente antes o durante su compilación o implementación.

    * 🛠 [cssnano: A modular minifier based on the PostCSS ecosystem. - cssnano](https://cssnano.co/)
    * 🛠 [CSS Minfier](https://goonlinetools.com/css-minifier/)
    * 🛠 [@neutrinojs/style-minify - npm](https://www.npmjs.com/package/@neutrinojs/style-minify)
    * 🛠 [Online CSS Compressor](http://refresh-sf.com)


- [ ] **Concatenación:** ![medium] Los archivos CSS se concatenan en un solo archivo *(No siempre es válido para HTTP/2)*.

    ```html

    <!-- No recomendado -->
    <link rel="stylesheet" href="foo.css"/>
    <link rel="stylesheet" href="bar.css"/>

    <!-- Recomendado -->
    <link rel="stylesheet" href="foobar.css"/>
    ```

   *¿Por qué?:*
    > Si aún usa HTTP/1, es posible que deba concatenar sus archivos, es menos cierto si su servidor usa HTTP/2 (se deben realizar pruebas).

    *¿Cómo?:*
    > ⁃ Use una herramienta en línea o cualquier complemento antes o durante su compilación o su implementación para concatenar sus archivos. <br>
    ⁃ Asegúrese, por supuesto, de que la concatenación no rompa su proyecto.

    * 📖 [HTTP: Optimizing Application Delivery - High Performance Browser Networking (O'Reilly)](https://hpbn.co/optimizing-application-delivery/#optimizing-for-http2)
    * 📖 [Performance Best Practices in the HTTP/2 Era](https://deliciousbrains.com/performance-best-practices-http2/)

- [ ] **No-bloqueadores:** ![high] Los archivos CSS no deben bloquear para evitar que el DOM tarde en cargarse.

    ```html
    <link rel="preload" href="global.min.css" as="style" onload="this.rel='stylesheet'">
    <noscript><link rel="stylesheet" href="global.min.css"></noscript>
    ```

   *¿Por qué?:*
    > Los archivos CSS pueden bloquear la carga de la página y retrasar la visualización de su página. El uso de `preload` puede cargar los archivos CSS antes de que el navegador comience a mostrar el contenido de la página.

    *¿Cómo?:*
    > Debe agregar el atributo `rel` con el valor `preload` y agregar `as="style"` en el elemento `<link>`.

    * 🛠 [loadCSS by filament group](https://github.com/filamentgroup/loadCSS)
    * 📖 [Example of preload CSS using loadCSS](https://gist.github.com/thedaviddias/c24763b82b9991e53928e66a0bafc9bf)
    * 📖 [Preloading content with rel="preload"](https://developer.mozilla.org/en-US/docs/Web/HTML/Preloading_content)
    * 📖 [Preload: What Is It Good For? — Smashing Magazine](https://www.smashingmagazine.com/2016/02/preload-what-is-it-good-for/)

- [ ] **CSS sin usar:** ![medium] Elimina los selectores de CSS no utilizados.

   *¿Por qué?:*
    > Eliminar los selectores de CSS no utilizados puede reducir el tamaño de sus archivos y luego acelerar la carga de sus activos.

    *¿Cómo?:*
    > ⁃ ⚠️ Siempre verifique si el framework CSS que desea usar aún no tiene un código de reinicio / normalización incluido (un normalize o reset en inglés). A veces es posible que no necesite todo lo que está dentro de su archivo de reinicio.

    * 🛠 [UnCSS Online](https://uncss-online.com/)
    * 🛠 [PurifyCSS](https://github.com/purifycss/purifycss)
    * 🛠 [PurgeCSS](https://github.com/FullHuman/purgecss)
    * 🛠 [Chrome DevTools Coverage](https://developers.google.com/web/updates/2017/04/devtools-release-notes#coverage)

* [ ] **CSS crítico:** ![high] El CSS crítico (o "sobre el pliegue") recopila todo el CSS utilizado para mostrar la parte visible de la página. Está incrustado antes de su llamada CSS principal y entre `<style></style>` en una sola línea (minimizado si es posible).

   *¿Por qué?:*
    > La integración de CSS crítico ayuda a acelerar la representación de las páginas web, lo que reduce la cantidad de solicitudes al servidor.

    *¿Cómo?:*
    > Genere el CSS crítico con herramientas en línea o usando un complemento como el que desarrolló Addy Osmani.

    * 📖 [Understanding Critical CSS](https://www.smashingmagazine.com/2015/08/understanding-critical-css/)
    * 🛠 [Critical by Addy Osmani on GitHub](https://github.com/addyosmani/critical) automates this.
    * 📖 [Inlining critical CSS for better web performance | Go Make Things](https://gomakethings.com/inlining-critical-css-for-better-web-performance/)
     * 🛠 [Critical Path CSS Generator - Prioritize above the fold content :: SiteLocity](https://www.sitelocity.com/critical-path-css-generator)
     * 📖 [Reduce the size of the above-the-fold content
](https://developers.google.com/speed/docs/insights/PrioritizeVisibleContent)

- [ ] **CSS incrustado o en línea:** ![high] Evite usar CSS incrustado o en línea dentro de su `<body>` *(No es válido para HTTP/2)*

   *¿Por qué?:*
    > Una de las primeras razones es porque es una buena práctica **separar el contenido del diseño**. También lo ayuda a tener un código más fácil de mantener y mantener su sitio accesible. Pero en cuanto al rendimiento, es simplemente porque disminuye el tamaño de archivo de sus páginas HTML y el tiempo de carga.

    *¿Cómo?:*
    > Utilice siempre hojas de estilo externas o incruste CSS en su `<head>` (y siga las demás reglas de rendimiento de CSS)

    * 📖 [Observe CSS Best Practices: Avoid CSS Inline Styles](https://www.lifewire.com/avoid-inline-styles-for-css-3466846)

- [ ] **Analice la complejidad de las hojas de estilo:** ![high] El análisis de sus hojas de estilo puede ayudarlo a señalar problemas, redundancias y selectores de CSS duplicados.

   *¿Por qué?:*
    > A veces puede tener redundancias o errores de validación en su CSS, analizar sus archivos CSS y eliminar estas complejidades puede ayudarlo a acelerar sus archivos CSS (porque su navegador los leerá más rápido)

    *¿Cómo?:*
    > Su CSS debe estar organizado, usar un preprocesador de CSS puede ayudarlo con eso. Algunas herramientas en línea que se enumeran a continuación también pueden ayudarlo a analizar y corregir su código.

    * 🛠 [TestMyCSS | Optimize and Check CSS Performance](http://www.testmycss.com/)
    * 🛠 [CSS Stats](https://cssstats.com/)
    * 🛠 [macbre/analyze-css: CSS selectors complexity and performance analyzer](https://github.com/macbre/analyze-css)
    * 🛠 [Project Wallace](https://www.projectwallace.com/) is like CSS Stats but stores stats over time so you can track your changes

**[⬆ Regresar al inicio](#introducción)**

## Fuentes

![fonts]

* 📖 [A Book Apart, Webfont Handbook](https://abookapart.com/products/webfont-handbook)

- [ ] **formatos Webfont:** ![medium] Está utilizando WOFF2 en su proyecto o aplicación web.

   *¿Por qué?:*
    > Según Google, el formato de compresión WOFF 2.0 Web Font ofrece una ganancia promedio del 30 % sobre WOFF 1.0. Entonces es bueno usar WOFF 2.0, WOFF 1.0 como respaldo y TTF.

    *¿Cómo?:*
    > Comprueba antes de comprar tu nueva fuente que el proveedor te dé el formato WOFF2. Si está utilizando una fuente gratuita, siempre puede usar Font Squirrel para generar todos los formatos que necesita.

    * 📖 [WOFF 2.0 – Learn more about the next generation Web Font Format and convert TTF to WOFF2](https://gist.github.com/sergejmueller/cf6b4f2133bcb3e2f64a)
    * 🛠 [Create Your Own @font-face Kits » Font Squirrel](https://www.fontsquirrel.com/tools/webfont-generator)
    * 🛠 [IcoMoon App - Icon Font, SVG, PDF & PNG Generator](https://icomoon.io/app/)
    * 📖 [Using @font-face | CSS-Tricks](https://css-tricks.com/snippets/css/using-font-face/?ref=frontendchecklist)
    * 📖 [Can I use... WOFF2](https://caniuse.com/#feat=woff2)

- [ ] **Use `preconnect` para cargar las fuentes más rápido:** ![medium]

    ```html
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    ```

   *¿Por qué?:*
    > Cuando llega a un sitio web, su dispositivo necesita averiguar dónde se encuentra su sitio y con qué servidor necesita conectarse. Su navegador tuvo que ponerse en contacto con un servidor DNS y esperar a que se completara la búsqueda antes de obtener el recurso (fuentes, archivos CSS...). Las precargas y las preconexiones permiten que el navegador busque la información de DNS y comience a establecer una conexión TCP con el servidor que aloja el archivo de fuente. Esto proporciona un aumento de rendimiento porque para cuando el navegador analice el archivo css con la información de la fuente y descubra que necesita solicitar un archivo de fuente del servidor, ya habrá resuelto previamente la información de DNS y tendrá una conexión abierta. al servidor listo en su conjunto de conexiones.

    *¿Cómo?:*
    > ⁃ Antes de precargar sus fuentes web, use webpagetest para evaluar su sitio web <br>
    ⁃ Busque búsquedas de DNS de color verde azulado y observe el host que se solicita <br>
    ⁃ Precarga tus fuentes web en tu `<head>` y agrega eventualmente estos nombres de host que también deberías precargar

    * 📖 [Faster Google Fonts with Preconnect - CDN Planet](https://www.cdnplanet.com/blog/faster-google-webfonts-preconnect/)
    * 📖 [Make Your Site Faster with Preconnect Hints | Viget](https://www.viget.com/articles/make-your-site-faster-with-preconnect-hints/)
    * 📖 [Ultimate Guide to Browser Hints: Preload, Prefetch, and Preconnect - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/guide-to-browser-hints-preload-preconnect-prefetch/)
    * 📖 [A Comprehensive Guide to Font Loading Strategies—zachleat.com](https://www.zachleat.com/web/comprehensive-webfonts/#font-face)
    * 🛠 [typekit/webfontloader: Web Font Loader gives you added control when using linked fonts via @font-face.](https://github.com/typekit/webfontloader)

- [ ] **El tamaño del Webfont:** ![medium] Los tamaños de fuente web no superan los 300 kb (todas las variantes incluidas)

 * 📖 [Font Bytes - Page Weight](https://httparchive.org/reports/page-weight#bytesFont)

- [ ] **Evitar texto invisible o flash:** ![medium] Evite el texto transparente hasta que se cargue Webfont

 * 📖 [`font-display` for the Masses](https://css-tricks.com/font-display-masses/)
 * 📖 [CSS font-display: The Future of Font Rendering on the Web](https://www.sitepoint.com/css-font-display-future-font-rendering-web/)

**[⬆ Regresar al inicio](#introducción)**

## Imágenes

![images]

 * 📖 [Image Bytes in 2018](https://httparchive.org/reports/page-weight#bytesImg)

* [ ] **Optimización de imágenes:** ![high] Sus imágenes están optimizadas, comprimidas sin impacto directo para el usuario final.

   *¿Por qué?:*
    > Las imágenes optimizadas se cargan más rápido en su navegador y consumen menos datos.

    *¿Cómo?:*
    > ⁃ Intente usar efectos CSS3 cuando sea posible (en lugar de una imagen pequeña) <br>
    ⁃ Cuando sea posible, use fuentes en lugar de texto codificado en sus imágenes <br>
    ⁃ Use SVG <br>
    ⁃ Use una herramienta y especifique un nivel de compresión por debajo de 85.

    * 📖 [Image Optimization | Web Fundamentals | Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/image-optimization)
    * 📖 [Essential Image Optimization - An eBook by Addy Osmani](https://images.guide/)
    * 🛠 [TinyJPG – Compress JPEG images intelligently](https://tinyjpg.com/)
    * 🛠 [Kraken.io - Online Image Optimizer](https://kraken.io/web-interface)
    * 🛠 [Compressor.io - optimize and compress JPEG photos and PNG images](https://compressor.io/compress)
    * 🛠 [Cloudinary - Image Analysis Tool](https://webspeedtest.cloudinary.com)
    * 🛠 [ImageEngine - Image Webpage Loading Test](https://demo.imgeng.in)
    * 🛠 [SVGOMG - Optimize SVG vector graphics files](https://jakearchibald.github.io/svgomg/)


* [ ] **Formato de imágenes:** ![high] Elija su formato de imagen apropiadamente.

   *¿Por qué?:*
    > Para asegurarse de que sus imágenes no ralenticen su sitio web, elija el formato que corresponderá a su imagen. Si se trata de una foto, JPEG suele ser más apropiado que PNG o GIF. Pero no olvide buscar los formatos de próxima generación que pueden reducir el tamaño de sus archivos. Cada formato de imagen tiene pros y contras, es importante conocerlos para hacer la mejor elección posible.

    *¿Cómo?:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) para identificar qué imágenes pueden eventualmente usar **formatos de siguiente-generación** (como JPEG 2000m JPEG XR o WebP) <br>
    ⁃ Compare diferentes formatos, a veces usar PNG8 es mejor que PNG16, a veces no lo es.

    * 📖 [Serve Images in Next-Gen Formats  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/lighthouse/audits/webp)
    * 📖 [What Is the Right Image Format for Your Website? — SitePoint](https://www.sitepoint.com/what-is-the-right-image-format-for-your-website/)
    * 📖 [PNG8 - The Clear Winner — SitePoint](https://www.sitepoint.com/png8-the-clear-winner/)
    * 📖 [8-bit vs 16-bit - What Color Depth You Should Use And Why It Matters - DIY Photography](https://www.diyphotography.net/8-bit-vs-16-bit-color-depth-use-matters/)

- [ ] **Usar imagen vectorial vs ráster/mapa de bits:** ![medium] Prefiere usar imágenes vectoriales en lugar de imágenes de mapa de bits (cuando sea posible).

   *¿Por qué?:*
    > Las imágenes vectoriales (SVG) tienden a ser más pequeñas que las imágenes y los SVG responden y escalan perfectamente. Estas imágenes pueden ser animadas y modificadas por CSS.

* [ ] **Dimensiones de imagen:** ![medium] Agregue los atributos `width` y `height` en el tag `<img>` si se conoce el tamaño final de la imagen.

   *¿Por qué?:*
    > Si se establecen alto y ancho, el espacio requerido para la imagen se reserva cuando se carga la página. Sin embargo, sin estos atributos, el navegador no conoce el tamaño de la imagen y no puede reservarle el espacio adecuado. El efecto será que el diseño de la página cambiará durante la carga (mientras se cargan las imágenes).

* [ ] **Evite el uso de imágenes Base64:** ![medium] Eventualmente podría convertir imágenes diminutas a base64, pero en realidad no es la mejor práctica.

    * 📖 [Base64 Encoding & Performance, Part 1 and 2 by Harry Roberts](https://csswizardry.com/2017/02/base64-encoding-and-performance/)
    * 📖 [A closer look at Base64 image performance – The Page Not Found Blog](http://www.andygup.net/a-closer-look-at-base64-image-performance/)
    * 📖 [When to base64 encode images (and when not to) | David Calhoun](https://www.davidbcalhoun.com/2011/when-to-base64-encode-images-and-when-not-to/)
   * 📖 [Base64 encoding images for faster pages | Performance and seo factors](https://varvy.com/pagespeed/base64-images.html)

* [ ] **Lazy loading:** ![medium] Las imágenes fuera de pantalla se cargan con el enfoque lazy loading.

   *¿Por qué?:*
    > Mejorará el tiempo de respuesta de la página actual y luego evitará cargar imágenes innecesarias que el usuario puede no necesitar.

    *¿Cómo?:*
    > ⁃ Use [Lighthouse](https://developers.google.com/web/tools/lighthouse/) para identificar **imágenes fuera de pantalla**. <br>
    ⁃ Use un plugin de JavaScript como el siguiente para cargar sus imágenes de forma diferida. Asegúrate de apuntar solo a imágenes fuera de pantalla. <br>
    ⁃ También asegúrese de cargar de forma diferida las imágenes alternativas que se muestran al pasar el mouse por encima o en otras acciones del usuario.

    * 🛠 [verlok/lazyload: GitHub](https://github.com/verlok/lazyload)
    * 🛠 [aFarkas/lazysizes: GitHub](https://github.com/aFarkas/lazysizes/)
    * 🛠 [mfranzke/loading-attribute-polyfill: GitHub](https://github.com/mfranzke/loading-attribute-polyfill/)
    * 📖 [Lazy Loading Images and Video  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/lazy-loading-guidance/images-and-video/)
    * 📖 [5 Brilliant Ways to Lazy Load Images For Faster Page Loads - Dynamic Drive Blog](http://blog.dynamicdrive.com/5-brilliant-ways-to-lazy-load-images-for-faster-page-loads/)

* [ ] **Imágenes responsivas:** ![medium] Asegúrese de publicar imágenes que se acerquen al tamaño de su pantalla.

   *¿Por qué?:*
    > Los dispositivos pequeños no necesitan imágenes más grandes que su ventana gráfica. Es Recomendado tener múltiples versiones de una imagen en diferentes tamaños.

    *¿Cómo?:*
    > ⁃ Cree diferentes tamaños de imagen para los dispositivos a los que desea dirigirse. <br>
    ⁃ Use `srcset` y `picture` para entregar múltiples variantes de cada imagen.

     * 📖 [Responsive images - Learn web development | MDN](https://developer.mozilla.org/en-US/docs/Learn/HTML/Multimedia_and_embedding/Responsive_images)

**[⬆ Regresar al inicio](#introducción)**

## JavaScript

![javascript]

- [ ] **Minificación:** ![high] Todos los archivos JavaScript se minimizan, los comentarios, los espacios en blanco y las nuevas líneas se eliminan de los archivos de producción *(aún válido si se usa HTTP/2)*.

   *¿Por qué?:*
    > Eliminar todos los espacios, comentarios y pausas innecesarios reducirá el tamaño de sus archivos JavaScript y acelerará los tiempos de carga de la página de su sitio y, obviamente, aligerará la descarga para su usuario.

    *¿Cómo?:*
    > Utilice las herramientas sugeridas a continuación para minimizar sus archivos automáticamente antes o durante su compilación o implementación.

    * 🛠 [uglify-js - npm](https://www.npmjs.com/package/uglify-js)
    * 🛠 [Online JavaScript Compressor](http://refresh-sf.com)
    * 📖 [Short read: How is HTTP/2 different? Should we still minify and concatenate?](https://scaleyourcode.com/blog/article/28)

* [ ] **JavaScript dentro del HTML:** ![medium] *(Solo válido para sitio web)* Evite tener múltiples códigos JavaScript incrustados en el medio de su cuerpo. Reagrupa tu código JavaScript dentro de archivos externos o eventualmente en `<head>` o al final de tu página (antes de `</body>`).

   *¿Por qué?:*
    > Colocar el código incrustado de JavaScript directamente en su `<cuerpo>` puede ralentizar su página porque se carga mientras se construye el DOM. La mejor opción es usar archivos externos con `async` o `defer` para evitar bloquear el DOM. Otra opción es colocar algunos scripts dentro de su `<head>`. La mayoría de las veces, el código de análisis o el pequeño script deben cargarse antes de que el DOM llegue al procesamiento principal.

    *¿Cómo?:*
    > Asegúrese de que todos sus archivos se carguen usando `async` o `defer` y decida sabiamente el código que necesitará inyectar en su `<head>`.

     * 📖 [11 Tips to Optimize JavaScript and Improve Website Loading Speeds](https://www.upwork.com/hiring/development/11-tips-to-optimize-javascript-and-improve-website-loading-speeds/)

* [ ] **JavaScript no bloqueante:** ![high] Los archivos de JavaScript se cargan de forma asíncrona usando `async` o se difieren usando el atributo `defer`.

    ```html
    <!-- usando el atributo "Defer" -->
    <script defer src="foo.js"></script>

    <!-- usando el atributo "Async" -->
    <script async src="foo.js"></script>
    ```

   *¿Por qué?:*
    > JavaScript bloquea el análisis normal del documento HTML, por lo que cuando el analizador llega a una etiqueta `<script>` (particularmente está dentro de `<head>`), se detiene para buscarlo y ejecutarlo. Agregar `async` o `defer` es muy recomendable si sus scripts se colocan en la parte superior de su página, pero es menos valioso si se encuentra justo antes de la etiqueta `</body>`. Pero es una buena práctica usar siempre estos atributos para evitar cualquier problema de rendimiento.

    *¿Cómo?:*
    > Agregue `async` (si el script no se basa en otros scripts) o `defer` (si el script depende de un script asíncrono) como un atributo a la etiqueta script. <br>
     ⁃ Si tiene scripts pequeños, tal vez, usar script inline arriba de los script async sea buena idea.

    * 📖 [Remove Render-Blocking JavaScript](https://developers.google.com/speed/docs/insights/BlockingJS)
    * 📖 [Defer loading JavaScript](https://varvy.com/pagespeed/defer-loading-javascript.html)

* [ ] **Bibliotecas JS optimizadas y actualizadas:** ![medium] Todas las bibliotecas de JavaScript utilizadas en su proyecto son necesarias (prefiera JavaScript Vanilla para funcionalidades simples), actualizadas a su última versión y no abrume su JavaScript con métodos innecesarios.

   *¿Por qué?:*
    > La mayoría de las veces, las nuevas versiones vienen con optimización y corrección de seguridad. Debe usar el código más optimizado para acelerar su proyecto y asegurarse de no ralentizar su sitio web o aplicación sin un complemento desactualizado.

    *¿Cómo?:*
    > Si tu proyecto usa paquetes de NPM, [npm-check](https://www.npmjs.com/package/npm-check) es una biblioteca bastante interesante para actualizar / actualizar sus bibliotecas.
    > [Greenkeeper](https://greenkeeper.io/) puede buscar automáticamente sus dependencias y sugerir una actualización cada vez que sale una nueva versión.

    * 📖 [You may not need jQuery](http://youmightnotneedjquery.com/)
    * 📖 [Vanilla JavaScript for building powerful web applications](https://plainjs.com/)

- [ ] **Check dependencies size limit:** ![low] Asegúrese de usar sabiamente bibliotecas externas, la mayoría de las veces, puede usar una biblioteca más ligera para una misma funcionalidad.

   *¿Por qué?:*
    > Puede sentirse tentado a usar uno de los 745 000 paquetes que puede encontrar en [npm](https://www.npmjs.com/), pero debe elegir el mejor paquete para sus necesidades. Por ejemplo, MomentJS es una biblioteca increíble pero con muchos métodos que quizás nunca uses, por eso se creó Day.js. Son solo 2kB frente a 16,4kB gz para Moment.

    *¿Cómo?:*
    > Compare y elija siempre la biblioteca mejor y más ligera para sus necesidades. También puede usar herramientas como [npm Trends](http://www.npmtrends.com/) para comparar los recuentos de descargas de paquetes de NPM o [Bundlephobia](https://bundlephobia.com/) para conocer el tamaño de sus dependencias.

    * 🛠 [ai/size-limit: Prevent JS libraries bloat. If you accidentally add a massive dependency, Size Limit will throw an error.](https://github.com/ai/size-limit)
    * 🛠 [webpack-bundle-analyzer - npm](https://www.npmjs.com/package/webpack-bundle-analyzer)
    * 🛠 [js-dependency-viewer - npm](https://www.npmjs.com/package/js-dependency-viewer)
    * 📖 [Size Limit: Make the Web lighter — Martian Chronicles, Evil Martians’ team blog](https://evilmartians.com/chronicles/size-limit-make-the-web-lighter)

- [ ] **Profiling en JavaScript:** ![medium] Compruebe si hay problemas de rendimiento en sus archivos JavaScript (y también en CSS).

   *¿Por qué?:*
    > La complejidad de JavaScript puede ralentizar el rendimiento del tiempo de ejecución. Identificar estos posibles problemas es esencial para ofrecer la experiencia de usuario más fluida.

    *¿Cómo?:*
    > Use la herramienta Línea de tiempo en la Herramienta para desarrolladores de Chrome para evaluar los eventos de los scripts y encontrar el que puede llevar demasiado tiempo.

     * 📖 [Speed Up JavaScript Execution  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/rendering-tools/js-execution)
    * 📖 [JavaScript Profiling With The Chrome Developer Tools — Smashing Magazine](https://www.smashingmagazine.com/2012/06/javascript-profiling-chrome-developer-tools/)
    * 📖 [How to Record Heap Snapshots  |  Tools for Web Developers  |  Google Developers](https://developers.google.com/web/tools/chrome-devtools/memory-problems/heap-snapshots)
    * 📖 [Chapter 22 - Profiling the Frontend - Blackfire](https://blackfire.io/docs/book/22-frontend-profiling)
    * 📖 [30 Tips To Improve Javascript Performance](http://www.monitis.com/blog/30-tips-to-improve-javascript-performance/)

- [ ] **Utilice Service Workers:** ![medium] Está utilizando Service Workers en su PWA para almacenar datos en caché o ejecutar posibles tareas pesadas sin afectar la experiencia del usuario de su aplicación.
   
    * 📖 [Service Workers: an Introduction  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/primers/service-workers/)
    * 📖 [Measuring the Real-world Performance Impact of Service Workers  |  Web  |  Google Developers](https://developers.google.com/web/showcase/2016/service-worker-perf)
    * 📖 [What Are Service Workers and How They Help Improve Performance](https://www.keycdn.com/blog/service-workers/)
    * 📹 [How does a service worker work? - YouTube](https://www.youtube.com/watch?v=__xAtWgfzvc)

**[⬆ Regresar al inicio](#introducción)**

## Servidor

![server-side]

- [ ] **El sitio está utilizando HTTPS:** ![high]

   *¿Por qué?:*
    > HTTPS no es solo para sitios web de comercio electrónico, sino para todos los sitios web que intercambian datos. Datos compartidos por un usuario o datos compartidos con una entidad externa. Los navegadores modernos de hoy limitan las funcionalidades de los sitios que no son seguros. Por ejemplo: la geolocalización, las notificaciones push y los trabajadores del servicio no funcionan si su instancia no usa HTTPS. Y hoy es mucho más fácil configurar un proyecto con un certificado SSL que antes (y gratis, gracias a [Let's Encrypt](https://letsencrypt.org/)).

 * 📖 [Why Use HTTPS? | Cloudflare](https://www.cloudflare.com/learning/security/why-use-https/)
 * 📖 [Enabling HTTPS Without Sacrificing Your Web Performance - Moz](https://moz.com/blog/enabling-https-without-sacrificing-web-performance)
 * 📖 [How HTTPS Affects Website Performance](https://wp-rocket.me/blog/https-affects-website-performance/)
 * 📖 [HTTP versus HTTPS versus HTTP2 - The real story | Tune The Web](https://www.tunetheweb.com/blog/http-versus-https-versus-http2/)
 * 📖 [HTTP vs HTTPS — Test them both yourself](https://www.httpvshttps.com/)

- [ ] **Peso del sitio < 1500 KB (idealmente < 500 KB):** ![high] Reduce el tamaño de tu página + recursos tanto como puedas.

   *¿Por qué?:*
    > Idealmente, debería intentar apuntar a < 500 KB, pero el estado de la web muestra que la mediana de Kilobytes es de alrededor de 1500 KB (incluso en dispositivos móviles). Dependiendo de sus usuarios objetivo, conexión de red, dispositivos, es importante reducir tanto como sea posible su total de Kilobytes para tener la mejor experiencia de usuario posible.

    *¿Cómo?:*
    > ⁃ Todas las reglas dentro de la Lista de verificación de rendimiento de front-end lo ayudarán a reducir tanto como sea posible sus recursos y su código.

    * 📖 [Page Weight](https://httparchive.org/reports/page-weight#bytesTotal)
    * 🛠 [What Does My Site Cost?](https://whatdoesmysitecost.com/)
    * 🛠 [web - Measure full page size in Chrome DevTools - Stack Overflow](https://stackoverflow.com/questions/38239980/measure-full-page-size-in-chrome-devtools)

- [ ] **Tiempo de carga de la página < 3 segundos:** ![high] Reduzca al máximo los tiempos de carga de su página para entregar rápidamente su contenido a sus usuarios.

   *¿Por qué?:*
    > Cuanto más rápido sea su sitio web o aplicación, menor será la probabilidad de que aumente el rebote, en otros términos, tendrá menos posibilidades de perder a su usuario o futuro cliente. Suficientes investigaciones sobre el tema prueban ese punto.

    *¿Cómo?:*
    > Utilizando herramientas como [Page Speed Insight](https://developers.google.com/speed/pagespeed/insights/) o [WebPageTest](https://www.webpagetest.org/) para analizar qué podría estar ralentizándolo, también puede usar este projecto para optimizar el rendimiento en general.

    * 🛠 [Compare your mobile site speed](https://www.thinkwithgoogle.com/feature/mobile/)
    * 🛠 [Test Your Mobile Website Speed and Performance - Think With Google](https://testmysite.thinkwithgoogle.com/intl/en-us)
    * 📖 [Average Page Load Times for 2018 - How does yours compare? - MachMetrics Speed Blog](https://www.machmetrics.com/speed-blog/average-page-load-times-websites-2018/)

- [ ] **Tiempo para el primer byte < 1,3 segundos:** ![high] Reduzca al máximo el tiempo de espera de su navegador antes de recibir datos.

    * 📖 [What is Waiting (TTFB) in DevTools, and what to do about it](https://scaleyourcode.com/blog/article/27)
    * 📖 [Monitoring your servers with free tools is easy](https://scaleyourcode.com/blog/article/7)
    * 📖 [Time to First Byte (TTFB)](https://varvy.com/pagespeed/ttfb.html)
    * 🛠 [Global latency testing tool](https://latency.apex.sh)

* [ ] **Tamaño de los cookies:** ![medium] Si está utilizando cookies, asegúrese de que cada cookie no supere los 4096 bytes y que su nombre de dominio no tenga más de 20 cookies.

   *¿Por qué?:*
    > Las cookies se intercambian en los encabezados HTTP entre los servidores web y los navegadores. Es importante mantener el tamaño de las cookies lo más bajo posible para minimizar el impacto en el tiempo de respuesta del usuario.

    *¿Cómo?:*
    > Elimine cookies que no sean necesarias.

    * 📖 [Cookie specification: RFC 6265](https://tools.ietf.org/html/rfc6265)
    * 📖 [Cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
    * 🛠 [Browser Cookie Limits](http://browsercookielimits.squawky.net/)
    * 📖 [Website Performance: Cookies Don't Taste So Good - Monitis Blog](http://www.monitis.com/blog/website-performance-cookies-dont-taste-so-good/)
    * 📖 [Google's Web Performance Best Practices #3: Minimize Request Overhead - GlobalDots Blog](https://www.globaldots.com/googles-web-performance-best-practices-3-minimize-request-overhead/)

- [ ] **Minimizar las solicitudes HTTP:** ![high] Asegúrese siempre de que todos los archivos solicitados sean esenciales para su sitio web o aplicación.

 * 📖 [Combine external CSS](https://varvy.com/pagespeed/combine-external-css.html)
 * 📖 [Combine external JavaScript](https://varvy.com/pagespeed/combine-external-javascript.html)

- [ ] **Use un CDN para entregar sus activos:** ![medium] Utilice una CDN para entregar más rápido su contenido en todo el mundo.

 * 📖 [10 Tips to Optimize CDN Performance - CDN Planet](https://www.cdnplanet.com/blog/10-tips-optimize-cdn-performance/)
 * 📖 [HTTP Caching  |  Web Fundamentals  |  Google Developers](https://developers.google.com/web/fundamentals/performance/optimizing-content-efficiency/http-caching)

- [ ] **Servir archivos desde el mismo protocolo:** ![high] Evite que su sitio web sirva archivos provenientes de una fuente usando HTTP en su sitio web que usa HTTPS, por ejemplo. Si su sitio web usa HTTPS, los archivos externos deben provenir del mismo protocolo.

- [ ] **Servir archivos accesibles:** ![high] Evite solicitar archivos inalcanzables (404).
 * 📖 [How to avoid bad requests](https://varvy.com/pagespeed/avoid-bad-requests.html)

- [ ] **Establecer encabezados de caché HTTP correctamente:** ![high] Establezca encabezados HTTP para evitar una costosa cantidad de viajes de ida y vuelta entre su navegador y el servidor.
 * 📖 [Using cache-control for browser caching](https://varvy.com/pagespeed/cache-control.html)

- [ ] **La compresión GZIP / Brotli está habilitada:** ![high] Utilice un método de compresión como Gzip o Brotli para reducir el tamaño de sus archivos JavaScript. Con un archivo de menor tamaño, los usuarios podrán descargar el activo más rápido, lo que resultará en un mejor rendimiento.

 * 🛠 [Check GZIP compression](https://checkgzipcompression.com/)
 * 🛠 [Check Brotli Compression](https://tools.keycdn.com/brotli-test)
 * 📖 [Can I use... Brotli](https://caniuse.com/#feat=brotli)

**[⬆ Regresar al inicio](#introducción)**

---
## Rendimiento y frameworks de JavaScript

### Angular
 * 📖 [Angular Performance Checklist](https://github.com/mgechev/angular-performance-checklist)

### React

 * 📖 [Optimizing Performance - React](https://reactjs.org/docs/optimizing-performance.html)
 * 📖 [React image manipulation | Cloudinary](https://cloudinary.com/documentation/react_image_manipulation)
 * 📖 [Debugging React performance with React 16 and Chrome Devtools.](https://building.calibreapp.com/debugging-react-performance-with-react-16-and-chrome-devtools-c90698a522ad)
  * 📖 [Build Performant - React](https://web.dev/react/)

### Vue
 * 📖 [Vue - Useful Links|Style Guide and Performance](https://learn-vuejs.github.io/vue-patterns/useful-links/)

## Rendimiento y CMS

### WordPress

* 🛠 [Test Your Website Speed | WordPress Hosting by @WPEngine](https://wpengine.com/speed-tool/)

#### Artículos

 * 📖 [19 Tips to Speed Up WordPress Performance (Updated)](https://www.wpbeginner.com/wordpress-performance-speed/)
 * 📖 [Speed Up Your WordPress - How to Save Images Optimized for Web](https://www.wpbeginner.com/beginners-guide/speed-wordpress-save-images-optimized-web/)

#### Plugins recomendados

* 🛠 [Caching Plugin for WordPress - Speed up your website with WP Rocket](https://wp-rocket.me/)
* 🛠 [WP-Sweep | WordPress.org](https://wordpress.org/plugins/wp-sweep/)
* 🛠 [Imagify Image Optimizer | WordPress.org](https://wordpress.org/plugins/imagify/)

---

## Traducciones

Este projecto quiere estar disponible en más idiomas! No dudes en enviar tu contribución!

* 🇺🇸 Inglés: [thedaviddias/Front-End-Performance-Checklist](https://github.com/thedaviddias/Front-End-Performance-Checklist)
* 🇵🇹 Portugués: [fernandofawkes/Front-End-Performance-Checklist](https://github.com/fernandofawkes/Front-End-Performance-Checklist)
* 🇨🇳 Chino: [JohnsenZhou/Front-End-Performance-Checklist](https://github.com/JohnsenZhou/Front-End-Performance-Checklist)
* 🇷🇺 Ruso: [lex111/Front-End-Performance-Checklist](https://github.com/lex111/Front-End-Performance-Checklist)
* 🇫🇷 Francés: [WilliamDASILVA/Front-End-Performance-Checklist](https://github.com/WilliamDASILVA/Front-End-Performance-Checklist)
* 🇰🇷 Coreano: [ParkSB/Front-End-Performance-Checklist](https://github.com/ParkSB/Front-End-Performance-Checklist)
* 🇻🇳 Vietnamita: [huynhan147/Front-End-Performance-Checklist](https://github.com/huynhan147/FrontEnd-Performance-Checklist)
* 🇯🇵 Japonés: [GameWith/Front-End-Performance-Checklist](https://github.com/GameWith/Front-End-Performance-Checklist)
* 🇵🇱 Polaco: [mbiesiad/Front-End-Performance-Checklist](https://github.com/mbiesiad/Front-End-Performance-Checklist)
* 🇮🇷 Persa: [ms-fadaei/Front-End-Performance-Checklist](https://github.com/ms-fadaei/Front-End-Performance-Checklist)

## Contribuir

**Puede abrir un issue o un pull request para sugerir cambios o adiciones.**

## Soporte

Si tiene alguna pregunta o sugerencia, no dude en usar Discord o Twitter:

* [Chat en Discord](https://discord.gg/btHQRkm)
* [Facebook](https://www.facebook.com/frontendchecklist/)
* [Twitter](https://twitter.com/thedaviddias)

## Autor

**Hecho con ❤️ por [David Dias](https://github.com/thedaviddias)

## Colaboradores

Este proyecto existe gracias a todas las personas que contribuyen. [[Contribuir]](.github/CONTRIBUTING.md).
<a href="https://github.com/thedaviddias/Front-End-Performance-Checklist/graphs/contributors">
    <img src="https://opencollective.com/front-end-checklist/contributors.svg?width=890" />
</a>


## Padrinos

Gracias a todos los padrinos (backers)! 🙏 [[Conviertete en un padrino](https://opencollective.com/front-end-checklist#backer)]

<a href="https://opencollective.com/front-end-checklist#backers" target="_blank"><img src="https://opencollective.com/front-end-checklist/backers.svg?width=890"></a>


## Patrocinadores

Apoya este proyecto convirtiéndote en un patrocinador. Tu logo aparecerá aquí con un enlace a tu sitio web. [[Conviértete en patrocinador](https://opencollective.com/front-end-checklist#sponsor)]

<a href="https://opencollective.com/front-end-checklist/sponsor/0/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/0/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/1/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/1/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/2/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/2/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/3/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/3/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/4/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/4/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/5/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/5/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/6/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/6/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/7/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/7/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/8/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/8/avatar.svg"></a>
<a href="https://opencollective.com/front-end-checklist/sponsor/9/website" target="_blank"><img src="https://opencollective.com/front-end-checklist/sponsor/9/avatar.svg"></a>

## Licencia

[MIT](LICENSE)

Todos los iconos son provistos por [Icons8](https://icons8.com/)

**[⬆ Regresar al inicio](#introducción)**

[logo]: images/logo-front-end-performance-checklist.jpg
[html]: images/html.png
[css]: images/css.png
[fonts]: images/fonts.png
[images]: images/images.png
[javascript]: images/javascript.png
[server-side]: images/server-side.png

[low]: images/priority/low.svg
[medium]: images/priority/medium.svg
[high]: images/priority/high.svg
