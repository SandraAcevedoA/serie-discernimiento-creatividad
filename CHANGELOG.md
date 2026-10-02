# Changelog

*English first · [Español más abajo](#español)*

## English

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
| The repository renders correctly on GitHub (tables, anchors, license detection). | A broken table, a heading anchor that does not match, or the license not being detected. | Requires a published repository. | NOT RUN |

---

## Español

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
| El repositorio se ve bien en GitHub (tablas, anchors, detección de la licencia). | Una tabla rota, un anchor que no coincide o que GitHub no detecte la licencia. | Requiere el repositorio publicado. | NOT RUN |
