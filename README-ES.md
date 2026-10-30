# Generador de Difusores Acústicos QRD — versión en español

**Publicación:** https://app.consultoria-sso.cl/acus/QRD/
**Entidad responsable de la plataforma:** CONSULTORIA NANCY MARCA ROJAS E.I.R.L.
**Índice de herramientas acústicas:** https://app.consultoria-sso.cl/acus/

---

## Qué es esto

Un generador de paneles difusores acústicos de residuos cuadráticos (QRD)
imprimibles en 3D. Incluye dos herramientas:

1. **Difusores QRD** — serie profunda 1D (N = 7) y serie de bloques 2D.
2. **Trampas de graves** — resonadores de cuarto de onda plegados, afinados a
   un modo de sala concreto.

Todo se calcula en el navegador: no se envía nada a ningún servidor.

## Licencia

**GPL-3.0.** Este fork está derivado del generador original de
**Soundblooms** (Chronosaur), publicado bajo GPL-3.0. Al ser un trabajo
derivado:

- El código permanece bajo GPL-3.0.
- Se conservan los créditos originales.
- Cualquier distribución debe incluir esta licencia y el código fuente.
- El código fuente completo de este fork está en
  https://github.com/liloalfa/diffuser-generator-es

## Repositorio

- **Fecha de publicación del código:** 30 de octubre de 2026.

- **Este fork (español):** https://github.com/liloalfa/diffuser-generator-es
- **Upstream original (inglés):** https://github.com/Chronosauros/diffuser-generator

El historial de commits original se conserva completo: este repositorio es el
upstream más un commit de traducción, no un producto separado.

Las fórmulas provienen de:
T. J. Cox y P. D'Antonio, *Acoustic Absorbers and Diffusers: Theory, Design
and Application*, 3ª ed., CRC Press, 2016.

## Créditos originales

- Generador original: https://github.com/Chronosauros/diffuser-generator
- Sitio del autor: https://soundblooms.com
- Paneles listos para imprimir: https://www.printables.com/model/1887298
- Geometría: [manifold-3d](https://github.com/elalish/manifold) (MIT)
- Vista previa 3D: [three.js](https://threejs.org) (MIT)
- Tipografía original: Geom, SIL Open Font License 1.1

## Modificaciones de Consultoría SSO

- Traducción completa al español (interfaz, textos, mensajes de estado).
- Metadatos SEO, canonical y Open Graph.
- Capa de traducción en tiempo de render (`es-i18n`) que deja intactos los
  núcleos geométricos y físicos, conforme a `CONTRACT.md` del upstream.
- Tema claro por defecto con conmutador claro/oscuro y persistencia.
- Separación visual de módulos en tarjetas numeradas.
- Nueva escala tipográfica sobre pila de sistema (Inter / Segoe UI).
- Bloque institucional con aviso de uso y licencias.

## Advertencia técnica

**Los resultados son calculados, no medidos.** La banda de frecuencia que
muestra la herramienta es intención de diseño calculada a partir de la
geometría. Ninguna de estas piezas ha sido validada en sala contra
ISO 17497-2. Sirve para diseñar y prototipar; no para certificar.

El propio proyecto original pide que especialistas en acústica revisen las
matemáticas. Corrections y datos de medición son bienvenidos.

## Verificación

- Suite del proyecto original: **307 pruebas, 0 fallos**.
- Los tres núcleos canónicos (`diffuser-core`, `bass-physics`,
  `bass-geometry`) se mantienen sin modificar.
