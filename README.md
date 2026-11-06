🇺🇸 English | 🇪🇸 Español — this project is bilingual: each section in English first, then Spanish. / Este proyecto es bilingüe: cada sección en inglés primero y después en español.

# Slashpedia

[![Project Status: WIP](https://www.repostatus.org/badges/latest/wip.svg)](https://www.repostatus.org/#wip)

**Status:** Work in progress — this encyclopedia is a working draft, not yet final. / **Estado:** En desarrollo — esta enciclopedia es un borrador en curso, aún no final.

**The free encyclopedia of AI slash commands**
*La enciclopedia gratuita de comandos slash para IA*

> **Draft / Borrador:** This project is a working draft until its author declares it final. / Este proyecto es un borrador hasta que su autor lo declare final.

---

## What is this?

Slash commands (like `/cinematic`) are community-made prompt shortcuts for AI tools: the slash does not activate anything by itself — the words do the work. Slashpedia collects them in one place, explains each one in plain words, and shows its prompt **only where the source's licence allows it**. Every entry opens as a dropdown: closed, it shows the name and a short description; open, it shows the prompt (when permitted), an example, and its source.

*Los comandos slash (como `/cinematic`) son atajos de prompt creados por la comunidad para herramientas de IA: el slash no activa nada por sí solo — el trabajo lo hacen las palabras. Slashpedia los reúne en un solo lugar, explica cada uno en palabras sencillas y muestra su prompt **solo donde la licencia de la fuente lo permite**. Cada entrada se abre como un desplegable: cerrada muestra el nombre y una descripción breve; abierta muestra el prompt (cuando está permitido), un ejemplo y su fuente.*

**Contents:** [What is this?](#what-is-this) · [The encyclopedia](#the-encyclopedia) · [How entries work](#how-entries-work) · [Content policy](#content-policy) · [The app](#the-app) · [Sources and licences](#sources-and-licences) · [Credits](#credits) · [Legal](#legal) · [License](#license)

## The encyclopedia

- **[Image](IMAGE.md)** — 322 commands, each with its prompt under an open licence.
- **Video** — coming next. / *En construcción.*
- **Text** — coming next. / *En construcción.*
- **Work** — coming next. / *En construcción.*

All entries also live in one machine-readable brain — [commands.json](commands.json) — which the app and the printable PDF will read.

*La enciclopedia: **[Imagen](IMAGE.md)** — 322 comandos, cada uno con su prompt bajo licencia abierta. **Video**, **Texto** y **Trabajo** — en construcción. Todas las entradas viven también en un cerebro legible por máquinas — [commands.json](commands.json) — que leerán la aplicación y el PDF imprimible.*

## How entries work

1. **Name** — the command itself, for example `/cinematic`. Command names are short phrases and are free to list.
2. **Plain explanation** — what the command does, written by Slashpedia in its own words.
3. **Prompt box** — the full prompt appears **only** when the source has a verified open licence that allows reuse. When it does not, the box carries no prompt at all — only this line: *"Think through your prompt and you'll get better results."*
4. **Source** — every entry names and links its source.

*Cómo funciona cada entrada: (1) **Nombre** — el comando en sí, por ejemplo `/cinematic`; los nombres son frases cortas y se pueden listar libremente. (2) **Explicación sencilla** — qué hace el comando, escrita por Slashpedia con sus propias palabras. (3) **Caja de prompt** — el prompt completo aparece **solo** cuando la fuente tiene una licencia abierta verificada que permite reutilizarlo; cuando no, la caja no lleva ningún prompt — solo esta frase: «Piensa en tu prompt y tendrás mejores resultados». (4) **Fuente** — cada entrada nombra y enlaza su fuente.*

## Content policy

Slashpedia follows a strict three-lane policy, designed so the project never causes its author a legal problem:

1. **Verified open licence** (for example MIT or CC BY): the full prompt may be published, with credit and the licence notice that licence requires.
2. **No permission**: only the command name and a short description written by Slashpedia. No one else's prompt, and no paraphrase of it.
3. **When in doubt, we cut**: an entry that cannot be published safely is published without a prompt — or not published at all.

*Política de contenido — tres carriles estrictos, pensados para que el proyecto nunca le cause un problema legal a su autor: (1) **Licencia abierta verificada** (por ejemplo MIT o CC BY): se puede publicar el prompt completo, con crédito y el aviso que esa licencia exige. (2) **Sin permiso**: solo el nombre del comando y una descripción breve escrita por Slashpedia; ningún prompt ajeno, ni siquiera parafraseado. (3) **Ante la duda, se corta**: la entrada que no se puede publicar con seguridad se publica sin prompt — o no se publica.*

The full legal notice is in [LEGAL.md](LEGAL.md).

*El aviso legal completo está en [LEGAL.md](LEGAL.md).*

## The app

This repository is the brain of Slashpedia: the encyclopedia itself. A companion app is planned to read it — a web extension that, when you type `/` in any AI tool's prompt box, opens a menu of categories, then commands, then a plain explanation of each command; and, on the phone, a companion keyboard. One brain, two doors.

*Este repositorio es el cerebro de Slashpedia: la enciclopedia misma. Está planeada una aplicación compañera que la lea — una extensión web que, al escribir «/» en el prompt de cualquier IA, abre un menú de categorías, luego de comandos, luego la explicación sencilla de cada comando; y, en el teléfono, un teclado complementario. Un cerebro, dos puertas.*

## Sources and licences

Every source used is recorded in [SOURCES.md](SOURCES.md) — its name, its link, its licence as verified, and the date it was checked — **before** any of its content is used.

*Toda fuente utilizada queda registrada en [SOURCES.md](SOURCES.md) — su nombre, su enlace, su licencia tal como fue verificada y la fecha de la verificación — **antes** de usar cualquier contenido suyo.*

## Credits

- [visual-commands](https://github.com/natan-webs/visual-commands) by natan-webs — a collection of 322 visual slash commands, published under the MIT License. Recorded in [SOURCES.md](SOURCES.md).
- [SlashAtlas](https://slashatlas.com/en/commands/) — a catalogue of 500+ slash commands, with no licence declared. Under Slashpedia's policy it is used as a linked reference only: names and our own descriptions, never its texts.
- Built with [Muse](https://muse.ai), Meta's personal AI agent.

*Créditos: [visual-commands](https://github.com/natan-webs/visual-commands), de natan-webs — colección de 322 comandos slash visuales, publicada bajo licencia MIT; registrada en [SOURCES.md](SOURCES.md). [SlashAtlas](https://slashatlas.com/en/commands/) — catálogo de más de 500 comandos slash, sin licencia declarada; bajo la política de Slashpedia se usa solo como referencia enlazada: nombres y descripciones propias, nunca sus textos. Construido con [Muse](https://muse.ai), el agente personal de IA de Meta.*

## Legal

See [LEGAL.md](LEGAL.md) — what Slashpedia is, how entries are written, third-party rights, trademarks and no endorsement, and how a rights holder can contact the project.

*Ver [LEGAL.md](LEGAL.md) — qué es Slashpedia, cómo se escriben las entradas, derechos de terceros, marcas y no respaldo, y cómo puede contactar un titular de derechos.*

## License

MIT — see [LICENSE](LICENSE). This licence covers Slashpedia's own original material only; it does not cover any third-party material referred to in an entry.

*Licencia MIT — ver [LICENSE](LICENSE). Esta licencia cubre solo el material original de Slashpedia; no cubre ningún material de terceros mencionado en una entrada.*
