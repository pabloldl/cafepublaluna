# Café Pub La Luna

Web estática independiente en HTML5, CSS3 y JavaScript vanilla. Abrir `index.html` con Live Server. Sin compilación ni dependencias de producción. Fotos y fuentes alojadas localmente.

## Datos y fuentes

Investigación realizada el 30 de octubre de 2026.

- Nombre, actividad y dirección contrastados en [TodoBares](https://www.todobares.com/bar/cafe-pub-la-luna-elbosque/): Café Pub La Luna, bar, Plaza El Andén, 11670 El Bosque, Cádiz. También coincide la ubicación en [LocalityBiz](https://localitybiz.es/andaluc%C3%ADa/servicio-de-bar-y-copas-en-c%C3%A1diz).
- No se ha encontrado carta oficial ni se ha verificado la titularidad de un perfil social. Se omiten teléfono, horarios, precios, carta, terraza, reservas y eventos.
- No existía la carpeta del proyecto ni fotografías locales al comenzar. Las fotos de terceros del establecimiento encontradas en directorios no se utilizan por falta de autorización verificable.

## Fotografías y licencias

Fotografías ilustrativas descargadas de Pexels, inspeccionadas visualmente y señaladas como tales en la web. No muestran La Luna ni prueban productos o servicios del negocio. Uso conforme a la [licencia Pexels](https://www.pexels.com/license/), que permite descarga, modificación y uso comercial gratuito.

| Archivo | Página original |
| --- | --- |
| `imgs/bar-editorial.jpg` | [Interior of a Bar, Rodrigo Chablé](https://www.pexels.com/photo/interior-of-a-bar-14612752/) |
| `imgs/encuentros.jpg` | [Cozy Bar Interior with Warm Lighting in London](https://www.pexels.com/photo/cozy-bar-interior-with-warm-lighting-in-london-28683064/) |
| `imgs/luz-ambar.jpg` | [Cozy Indoor Bar with Decorative Lighting](https://www.pexels.com/photo/cozy-indoor-bar-with-decorative-lighting-31072293/) |

Tipografías Bodoni Moda y Manrope, obtenidas de Google Fonts y alojadas localmente, bajo SIL Open Font License. Ver `fonts/OFL-bodoni.txt` y `fonts/OFL-manrope.txt`.

## Comprobaciones

- Chrome real en modo headless mediante Playwright: 375, 390, 768, 1440 y 1920 px. Sin desbordamiento horizontal, imágenes rotas, anclas inexistentes, respuestas HTTP de error ni errores de JavaScript.
- Navegación móvil: apertura, selección de enlace y cierre. Navegación accesible con JavaScript desactivado.
- Fuentes locales cargadas y exactamente una etiqueta `robots` con `noindex, nofollow`.
- Capturas completas revisadas a 390 y 1440 px. Pruebas de dimensiones ejecutadas con reducción de movimiento activada.
- JavaScript validado con `node --check`. Animaciones desactivadas mediante `prefers-reduced-motion`.
- Enlaces Google Maps implementados con la dirección contrastada. No se ha comprobado un itinerario ni la disponibilidad externa de Google Maps.
- No se ha ejecutado Safari en iPhone real; esa validación queda pendiente.
- Herramientas, capturas y resultados locales en `.qa/`, excluidos mediante `.gitignore`.

Solo se han creado archivos dentro de `cafe-pub-la-luna/`. Sin commits, pushes ni despliegues.
