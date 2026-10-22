# Changelog

*English first · [Español más abajo](#español)*

## English

### 0.1.2 · 2026-10-21

The umbrella repository was reconciled after all three workshops had been produced and published.

- All three chapter repositories now exist publicly and are linked from the README and chapter pages.
- The README no longer describes a fixed three-hour format or future repositories; duration and format are chapter-specific.
- The series summary now reflects the final Chapter 2 framing: functional reasoning and AI-assisted resolving, exploring and adapting under constraint, rather than a generic agency/research-tool framing.
- This repository-only reconciliation does **not** edit HedgeDoc, TMS curriculum data, or class metadata.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| All three public workshop repositories exist and are linked from this repository. | Any chapter repository is missing/private, or a chapter/README link points elsewhere. | GitHub repository state and current links checked 2026-10-21. | PASS |
| The README describes the series as already produced rather than future work. | Future-tense repository language or a universal three-hour claim remains in the README. | Current README text checked 2026-10-21. | PASS |
| Chapter 2 no longer centers the superseded agency/research-tool framing. | Its public chapter page still describes the chapter as carrying “agency” into the material world or limits AI to research. | Current chapter 2 text checked 2026-10-21. | PASS |

### 0.1.1 · 2026-10-12

Chapter 1 now has its repository, [`pensamiento-creatividad`](https://github.com/SandraAcevedoA/pensamiento-creatividad). `README.md` and `chapters/01-pensamiento-creatividad.md` link to it. The repositories for chapters 2 and 3 are still named but not linked.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| The chapter 1 repository is public and its link opens without logging in. | `github.com/SandraAcevedoA/pensamiento-creatividad` returning something other than 200 from an anonymous request. | Anonymous HTTP request, 2026-10-12. | PASS |
| No link points to a workshop repository that does not exist yet. | A link to `github.com/SandraAcevedoA/inventiva-bajo-restriccion` or `software-libre` while that repository is missing. | Scripted search, 2026-10-12. | PASS |

### 0.1.0 · 2026-10-02

First version of the series repository: `README.md`, one page per chapter in `chapters/`, the public `LINEAGE.md` / `LINEAGE.es.md` (draft) and `LICENSE` (CC BY-NC-SA 4.0). The three workshop repositories are named but not linked until they exist.

| Claim | What would disprove it | Check | Result |
|---|---|---|---|
| Every chapter page links to its class on The Multiverse School, and the page opens without logging in. | Any of `themultiverse.school/classes/289`, `/290`, `/291` returning something other than 200 from an anonymous request. | Anonymous HTTP request, 2026-10-02. | PASS |
| Chapter titles match the published class names exactly. | Any difference in wording, capitalization or accents between a chapter page title and the `<h1>` of its TMS class page. | Compared against the TMS database and the public pages, 2026-10-02. | PASS |
| Every relative link and heading anchor in `README.md` and `chapters/` resolves within the repository. | A link to a missing file or a missing heading. | Scripted check of links and anchors, 2026-10-02. | PASS |
| Every external link in `LINEAGE.md` and `LINEAGE.es.md` points to a public source that opens without logging in. | Any of those URLs failing from an anonymous request. | Anonymous HTTP request to every URL, 2026-10-02. | PASS |
| The public `LINEAGE` contains no private repository paths, commit hashes or production-database details. | A vault path (`Curriculum/…`), a commit hash, or a reference to production tables, bindings or pathways. | Scripted search, 2026-10-02. | PASS |
| No link points to a workshop repository that does not exist yet. | A link to `github.com/SandraAcevedoA/pensamiento-creatividad`, `inventiva-bajo-restriccion` or `software-libre` while that repository is missing. | Scripted search, 2026-10-02. | PASS |
| Every table and heading anchor renders correctly on GitHub. | A table rendered as plain text, or an in-repository `#anchor` link with no matching heading in GitHub's rendered HTML. | GitHub-rendered HTML of every file in the private repository, 2026-10-02. | PASS |
| `LICENSE` is the official CC BY-NC-SA 4.0 legal code, unmodified. | Any byte differing from `creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt`. | Byte comparison, 2026-10-02. GitHub lists the license as "Other" because it does not auto-detect NonCommercial licenses. | PASS |

---

## Español

### 0.1.2 · 2026-10-21

El repositorio paraguas se reconcilió después de que los tres workshops fueran producidos y publicados.

- Los tres repositorios de capítulo ya existen públicamente y están enlazados desde el README y las páginas de capítulo.
- El README deja de describir una duración fija de tres horas o repositorios futuros; la duración y el formato dependen de cada capítulo.
- La síntesis de la serie refleja el framing final del capítulo 2: razonamiento funcional y uso de IA para resolver, explorar y adaptar bajo restricción, en vez de un framing genérico de agencia/“herramienta de investigación”.
- Esta reconciliación ocurre sólo en este repositorio: **no** edita HedgeDoc, datos curriculares de TMS ni metadata de las clases.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| Los tres repositorios públicos de workshop existen y están enlazados desde este repositorio. | Que falte o sea privado alguno de los repositorios, o que los links del README/capítulos apunten a otra cosa. | Estado de repositorios y links actuales en GitHub, 2026-10-21. | PASS |
| El README describe la serie como trabajo ya producido y no como trabajo futuro. | Que permanezca lenguaje de repositorios futuros o una duración universal de tres horas. | Texto actual del README revisado el 2026-10-21. | PASS |
| El capítulo 2 ya no centra el framing superado de agencia/“herramienta de investigación”. | Que su página pública siga describiendo el capítulo como traslado de la “agencia” al mundo material o limite la IA a investigación. | Texto actual del capítulo 2 revisado el 2026-10-21. | PASS |

### 0.1.1 · 2026-10-12

El capítulo 1 ya tiene su repositorio, [`pensamiento-creatividad`](https://github.com/SandraAcevedoA/pensamiento-creatividad). `README.md` y `chapters/01-pensamiento-creatividad.md` lo enlazan. Los repositorios de los capítulos 2 y 3 siguen nombrados, pero sin enlace.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| El repositorio del capítulo 1 es público y su link abre sin iniciar sesión. | Que `github.com/SandraAcevedoA/pensamiento-creatividad` responda algo distinto de 200 a una petición anónima. | Petición HTTP anónima, 2026-10-12. | PASS |
| Ningún link apunta a un repositorio de workshop que todavía no existe. | Un link a `github.com/SandraAcevedoA/inventiva-bajo-restriccion` o `software-libre` mientras ese repositorio no exista. | Búsqueda automatizada, 2026-10-12. | PASS |

### 0.1.0 · 2026-10-02

Primera versión del repositorio de la serie: `README.md`, una página por capítulo en `chapters/`, los `LINEAGE.md` / `LINEAGE.es.md` públicos (borrador) y `LICENSE` (CC BY-NC-SA 4.0). Los tres repositorios de workshop se nombran, pero no se enlazan hasta que existan.

| Claim | Qué lo desmentiría | Verificación | Resultado |
|---|---|---|---|
| Cada página de capítulo enlaza a su clase en The Multiverse School, y la página abre sin iniciar sesión. | Que `themultiverse.school/classes/289`, `/290` o `/291` respondan algo distinto de 200 a una petición anónima. | Petición HTTP anónima, 2026-10-02. | PASS |
| Los títulos de los capítulos coinciden exactamente con los nombres de las clases publicadas. | Cualquier diferencia de palabras, mayúsculas o acentos entre el título de una página de capítulo y el `<h1>` de su clase en TMS. | Comparado contra la base de datos de TMS y las páginas públicas, 2026-10-02. | PASS |
| Todos los links relativos y anchors de `README.md` y `chapters/` resuelven dentro del repositorio. | Un link a un archivo que no existe o a un encabezado que no existe. | Revisión automatizada de links y anchors, 2026-10-02. | PASS |
| Todos los links externos de `LINEAGE.md` y `LINEAGE.es.md` apuntan a fuentes públicas que abren sin iniciar sesión. | Que alguna de esas URLs falle en una petición anónima. | Petición HTTP anónima a cada URL, 2026-10-02. | PASS |
| El `LINEAGE` público no contiene rutas de repositorios privados, hashes de commits ni detalles de la base de datos de producción. | Una ruta del vault (`Curriculum/…`), un hash de commit o una referencia a tablas, bindings o pathways de producción. | Búsqueda automatizada, 2026-10-02. | PASS |
| Ningún link apunta a un repositorio de workshop que todavía no existe. | Un link a `github.com/SandraAcevedoA/pensamiento-creatividad`, `inventiva-bajo-restriccion` o `software-libre` mientras ese repositorio no exista. | Búsqueda automatizada, 2026-10-02. | PASS |
| Todas las tablas y anchors de encabezados se ven bien en GitHub. | Una tabla que aparece como texto plano, o un link `#anchor` interno sin encabezado correspondiente en el HTML que genera GitHub. | HTML renderizado por GitHub de cada archivo en el repositorio privado, 2026-10-02. | PASS |
| `LICENSE` es el texto legal oficial de CC BY-NC-SA 4.0, sin modificar. | Cualquier byte distinto de `creativecommons.org/licenses/by-nc-sa/4.0/legalcode.txt`. | Comparación byte a byte, 2026-10-02. GitHub muestra la licencia como "Other" porque no detecta automáticamente las licencias NoComercial. | PASS |
