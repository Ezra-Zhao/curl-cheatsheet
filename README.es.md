# Hoja de referencia de curl · curl Cheatsheet

> 🌍 [中文](README.md) · [Português](README.pt.md)

Una **hoja de referencia de una sola página** con comandos curl: 29 comandos reales, y cada entrada responde solo tres preguntas — **qué hace, un comando listo para copiar y pegar, y etiquetas de uso**. Sin parámetros inventados ni sintaxis improvisada.

## Para quién es

Para desarrolladores backend, ingenieros de operaciones (SRE/DevOps), quienes integran APIs y cualquiera que trabaje a diario con APIs HTTP. Si todavía pruebas tus endpoints haciendo clic en una herramienta gráfica, esta hoja te permite lanzar una petición desde la terminal en tres segundos.

## Cómo usarla

1. Ve directo a **[CHEATSHEET.md](CHEATSHEET.md)** — el cuerpo de la referencia, legible para desarrolladores de cualquier idioma.
2. Verifica tu entorno: curl viene instalado en casi todos los sistemas; ejecuta `curl --version` (la versión 7.68+ cubre todos los comandos de esta hoja).
3. Reemplaza `https://example.com` en los ejemplos con tu URL real y prueba cada entrada: en una hora lo tendrás dominado.

## Qué incluye

| Categoría | Contenido |
|---|---|
| 🌐 Peticiones básicas | GET / POST / PUT / DELETE / PATCH / HEAD (6) |
| 🔑 Cabeceras y autenticación | Cabeceras propias, Bearer Token, Basic Auth, User-Agent (4) |
| 📤 Enviar datos | JSON, codificación URL, subida multipart (3) |
| 📥 Manejar respuestas | Ver cabeceras, guardar a archivo, modo silencioso, medir tiempos (5) |
| 🐞 Depuración | Detalle con -v, trace, versión HTTP, omitir certificado ⚠️ (4) |
| ⬇️ Descargas y límite de velocidad | Reanudar descarga, limitar velocidad, reintentos (3) |
| 🍪 Cookies y sesión | Guardar / enviar cookies (2) |
| 🔀 Proxy | Proxy HTTP, proxy SOCKS5 (2) |

Todos los comandos usan sintaxis curl real (verificada con curl 8.5.0). Documentación oficial: https://curl.se/docs/.

## Por qué estos 29

- **Cubren todo el flujo de integración con APIs**: desde enviar la petición, autenticarse y mandar datos, hasta leer respuestas, depurar problemas y descargar archivos — el 95 % del día a día en una sola hoja.
- **Cada comando funciona de verdad**: nada de pseudocódigo; copia, cambia la URL y ejecútalo. Las opciones peligrosas (como `-k`, que omite la verificación del certificado) están marcadas con ⚠️ y son solo para depuración.

## Contribuciones bienvenidas

¿Un comando incorrecto, un parámetro obsoleto o una traducción mejorable? Los *pull requests* son bienvenidos. Mantén el formato de cada entrada (qué hace / comando / etiquetas) y **verifica cada comando con un curl real antes de enviarlo**.

## Licencia

MIT © 2026 Guangyi Zhao. Ver [LICENSE](LICENSE).
