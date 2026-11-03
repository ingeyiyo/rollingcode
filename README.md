# Mis proyectos del curso de RollingCode

Hola, soy Juan Pablo Rearte (Yiyo), de Tucumán. Acá subí todo lo que fui haciendo en el curso de desarrollo web de RollingCode School.

Arranqué en 2022 sin saber ni qué era una etiqueta, lo dejé un tiempo, lo retomé en 2023 y en 2025 volví a meterle con un proyecto propio. Por eso hay de todo: cosas muy básicas del principio y otras más armadas. Las dejé todas a propósito, porque la idea es que se vea cómo fui avanzando.

Si abrís el `index.html` tenés una página con todos los proyectos ordenados, lo que aprendí en cada uno y lo que haría distinto hoy.

## Los proyectos

| # | Proyecto | Carpeta | Qué practiqué |
|---|----------|---------|---------------|
| 1 | Primera clase de HTML | `modulo-1/clase-html` | Etiquetas básicas, listas, tablas e imágenes |
| 2 | Página del portón automático (mi desafío final de Arduino) | `modulo-1/clase-html/automatismo.html` | Tablas, anclas y video |
| 3 | Página de Valorant | `modulo-1/practica-html` | Primeros estilos y formularios, después pasada a Bootstrap |
| 4 | Mi primera web | `mi-primera-web` | Una plantilla de varias páginas con Flexbox |
| 5 | Listado de compras de electrónica | `listado-compras` | Formularios, position, Bootstrap y un poco de JavaScript |
| 6 | Galería de Funkos | `galeria-funkos` | Flexbox, filtros y media queries |
| 7 | Bootstrap y tienda de ropa | `bootstrap`, `tienda-ropa` | Bootstrap 5, navbar con menú hamburguesa, login |

## Los que más me gustan

**El portón automático.** Fue el desafío final de un curso de Arduino que hice al mismo tiempo, y en RollingCode armé la página para presentarlo. En Tinkercad hice un portón que se abre y se cierra con un control remoto: un Arduino, un servo que mueve el portón, un sensor infrarrojo para el control, dos interruptores que hacen de fines de carrera (Tinkercad no tiene fines de carrera, así que los simulé así) y una pantalla LCD que te dice si está abriendo o cerrando. La página explica cómo funciona el código y tiene un video de la simulación. Los programas de ese curso están en mi repo [automatismo-programacion](https://github.com/ingeyiyo/automatismo-programacion).

**El listado de compras.** Lo usé de verdad: es la lista de materiales que tenía que comprar para el TP de Laboratorio de Electrónica 1, con una página para cada componente que explica para qué sirve. En la lista podés ir marcando lo que ya compraste y se va llenando una barra. Ahí también practiqué un formulario de registro con casi todos los tipos de input.

**La galería de Funkos.** Las fotos arrancan borrosas y se enfocan cuando pasás el mouse por arriba. En el celular se acomodan de a dos por fila.

## Cómo está organizado

```
index.html            la portada
pages/proyectos.html  todos los proyectos, se pueden filtrar por html, css o bootstrap
pages/bitacora.html   lo que fui aprendiendo y lo que haría distinto
css/estilos.css       los estilos de esas 3 páginas (lo demás lo hace Bootstrap)
apuntes/              apuntes sueltos de las clases
```

Cada proyecto tiene su carpeta con su `index.html`, su `css` y sus imágenes, así que también se pueden abrir por separado.

## Para verlo

Lo más fácil es abrirlo con Live Server en VS Code. Todas las rutas son relativas, así que también anda con GitHub Pages (Settings → Pages → rama `main`, carpeta raíz).

## Con qué está hecho

HTML, CSS y Bootstrap 5. La portada también la hice con Bootstrap, como la tienda de ropa.

---

Si tenés alguna sugerencia o ves algo para mejorar, avisame.
