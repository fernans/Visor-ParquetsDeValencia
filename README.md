# Visor-ParquetsDeValencia

Interactive floor-samples viewer for **Parquets de Valencia** (`pdv/client project`), developed with Flash 9 / Flash CS-era tooling.

The viewer presents **21 room photographs per scene** through four independent Flash movies — `banyo.swf` (bathroom), `despacho.swf` (office), `habitacion.swf` (bedroom) and `salon.swf` (living room) — that sweep through the `images/` gallery of real interior shots so the parquet flooring can be compared across rooms. A ready-to-open `index.html` (standard Adobe `AC_RunActiveContent.js` wrapper) embebbs the four 660×466 movies side-by-side.

Contents:

| Path | Description |
|---|---|
| `banyo/despacho/habitacion/salon .fla/.swf` | sources + compiled viewers (0,5–3,3 MB FLA sources) |
| `images/` | 84 interior photographs (21 per room, ~6 MB) |
| `index.html` + `AC_RunActiveContent.js` | test page with the four embeds |
| `ajax-loader.gif` | preloader asset |

> **This project is shared ONLY for educational purposes. Its use, direct or derived, for professional or economic purposes is not permitted.**

For security reasons, some parts of the project may have been edited or removed: the duplicate deliverable archive `pdv.rar` is excluded; everything else is published as-is.

## Requirements / How to run

- Any SWF player (standalone Flash Projector or a browser with the Flash Player plugin) or simply open `index.html`.
- To rebuild: open the room `.fla` in Flash Professional (CS era) and publish; each movie references the JPGs in `images/` at runtime.

No warranty of any kind is provided, and no liability is accepted for errors or damages resulting from its use of this software.

Additionally, the use of this project's content (code, documentation or assets) to train artificial intelligence or machine-learning systems is not permitted without the explicit permission of the author. Licensed under [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — see [`LICENSE`](LICENSE).

---

# Visor-ParquetsDeValencia

Visor interactivo de muestras de suelo para **Parquets de Valencia** (proyecto `pdv/increnta`), desarrollado con Flash 9 / herramientas de la era Flash CS.

El visor presenta **21 fotografías por estancia** a través de cuatro películas Flash independientes — `banyo.swf` (cuarto de baño), `despacho.swf` (despacho), `habitacion.swf` (dormitorio) y `salon.swf` (salón) — que recorren la galería `images/` de interiores reales para comparar el parquet en diferentes estancias. Una página `index.html` lista para abrir (environment estándar `AC_RunActiveContent.js` de Adobe) embebe las cuatro películas de 660×466.

Contenido:

| Ruta | Descripción |
|---|---|
| `banyo/despacho/habitacion/salon .fla/.swf` | fuentes + visores compilados (fuentes FLA 0,5–3,3 MB) |
| `images/` | 84 fotografías de interiores (21 por estancia, ~6 MB) |
| `index.html` + `AC_RunActiveContent.js` | página de prueba con los cuatro embebido |
| `ajax-loader.gif` | asset de precarga |

> **Este proyecto se comparte SOLO con valor educativo. No está permitido su uso (directo o derivado) para fines profesionales o económicos.**

Por motivos de seguridad, algunas partes del proyecto pueden encontrarse editadas o eliminadas: el paquete de entrega duplicado `pdv.rar` está excluido; todo lo demás se publica tal cual.

## Requisitos / Cómo ejecutar

- Cualquier reproductor SWF (Flash Projector standalone o navegador con el plugin de Flash Player) o simplemente abrir `index.html`.
- Para recompilar: abrir el `.fla` de cada estancia en Flash Professional (era CS) y publicar; cada película referencia los JPGs de `images/` en tiempo de ejecución.

Este software se suministra sin garantía de ningún tipo, y no se asume ninguna responsabilidad por errores o daños que puedan producirse a partir de su uso.

Adicionalmente, no está permitido el uso del contenido de este proyecto (código, documentación o assets) para entrenar sistemas de inteligencia artificial o de aprendizaje automático sin el permiso explícito del autor. Licenciado bajo [CC BY-NC 4.0](https://creativecommons.org/licenses/by-nc/4.0/) — ver [`LICENSE`](LICENSE).
