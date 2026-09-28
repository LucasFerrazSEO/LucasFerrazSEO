### Lucas Ferraz

SEO, website development and Generative Engine Optimization specialist,
based in Belo Horizonte, Brazil. I have worked professionally with SEO since
2007 and founded [Lucas Ferraz SEO](https://lucasferrazseo.com), an agency
that serves companies across Brazil. My work sits on two layers: being found
on Google and being the name an AI assistant recommends.

- Technical notes, studies and research logs at [lucasferraz.com](https://lucasferraz.com)
- Author of [*A Empresa que a IA Recomenda*](https://lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/) (Brazilian Portuguese, 2026, ISBN 978-65-02-23078-7)
- Open data from my studies at [lucasferraz.com/estudos](https://lucasferraz.com/estudos/), under CC BY 4.0
- The tools below are the same ones I use in my own audits, published as they are

**Links.** [Website](https://lucasferraz.com) ·
[Blog](https://lucasferraz.com/blog/) ·
[Press](https://lucasferraz.com/imprensa/) ·
[Agency](https://lucasferrazseo.com) ·
[LinkedIn](https://www.linkedin.com/in/lucasferrazseo/) ·
[YouTube](https://www.youtube.com/@lucasferrazseo) ·
[X](https://x.com/lucasferrazseo) ·
[Instagram](https://www.instagram.com/lucasferraztec/)

---

#### GEO and AI search

| Repository | What it does |
|---|---|
| [citability-lint](https://github.com/LucasFerrazSEO/citability-lint) | Mechanical citability check for text: length band, vague openings, unsourced numbers, AI clichés |
| [chunk-boundary-lint](https://github.com/LucasFerrazSEO/chunk-boundary-lint) | Checks whether the first paragraph of each section stands on its own when extracted |
| [page-to-ai-markdown](https://github.com/LucasFerrazSEO/page-to-ai-markdown) | Shows what an AI crawler reads from a page without JavaScript, as markdown |
| [llms-txt-lint](https://github.com/LucasFerrazSEO/llms-txt-lint) | Validates the structure of an llms.txt file |
| [anti-citation-directives-check](https://github.com/LucasFerrazSEO/anti-citation-directives-check) | Scans HTML for nosnippet, max-snippet:0, noarchive and data-nosnippet |
| [ai-bots-list](https://github.com/LucasFerrazSEO/ai-bots-list) | Open, versioned list of AI bots (search and training) plus a robots.txt checker |
| [ai-crawler-log-parser](https://github.com/LucasFerrazSEO/ai-crawler-log-parser) | Finds and classifies AI bot hits in server access logs |
| [citation-round-logger](https://github.com/LucasFerrazSEO/citation-round-logger) | Logs AI citation rounds and calculates brand share of voice |
| [ai-readiness-check](https://github.com/LucasFerrazSEO/ai-readiness-check) | Scores a site's technical readiness for AI search: llms.txt, AI bots in robots.txt, entity schema, edge probes |
| [geo-lint-action](https://github.com/LucasFerrazSEO/geo-lint-action) | GitHub Action that runs these GEO checks on every pull request |

#### Technical SEO and structured data

| Repository | What it does |
|---|---|
| [jsonld-graph-check](https://github.com/LucasFerrazSEO/jsonld-graph-check) | Validates JSON-LD `@graph` integrity: duplicate `@id`, dangling references, isolated nodes |
| [faq-schema-parity-check](https://github.com/LucasFerrazSEO/faq-schema-parity-check) | Compares the visible FAQ in the HTML with the FAQPage JSON-LD |
| [structured-data-json-ld](https://github.com/LucasFerrazSEO/structured-data-json-ld) | LocalBusiness JSON-LD template for structured data |
| [heading-structure-lint](https://github.com/LucasFerrazSEO/heading-structure-lint) | Heading hierarchy with no skipped levels and a single H1 |
| [snippet-pixel-measure](https://github.com/LucasFerrazSEO/snippet-pixel-measure) | Estimates title and meta description width in pixels, not characters |
| [og-image-check](https://github.com/LucasFerrazSEO/og-image-check) | Checks that a URL's og:image exists and reports its real dimensions |
| [keyword-density-report](https://github.com/LucasFerrazSEO/keyword-density-report) | Keyword density and most frequent n-grams for Brazilian Portuguese text |
| [entity-sameas-check](https://github.com/LucasFerrazSEO/entity-sameas-check) | Audits Organization and Person sameAs: dead profiles, Wikidata cross-check, `@id` consistency |
| [internal-link-audit](https://github.com/LucasFerrazSEO/internal-link-audit) | Internal link crawler: orphans, click depth, repeated links per text, generic anchors, nofollow |
| [sitemap-similarity-check](https://github.com/LucasFerrazSEO/sitemap-similarity-check) | Finds near-duplicate pages, repeated sections and similar titles across a sitemap |
| [sitemap-lastmod-audit](https://github.com/LucasFerrazSEO/sitemap-lastmod-audit) | Checks whether sitemap lastmod dates are real or generated at build time |

#### Measurement

| Repository | What it does |
|---|---|
| [ab-test-significance](https://github.com/LucasFerrazSEO/ab-test-significance) | Statistical significance of an A/B test with a small sample |
| [gsc-cannibalization-finder](https://github.com/LucasFerrazSEO/gsc-cannibalization-finder) | Finds Search Console queries split across two or more URLs of the same site |
| [ai-referrer-report](https://github.com/LucasFerrazSEO/ai-referrer-report) | GA4 sessions and conversions from AI assistants, by real referrer only |

#### Guides, lists and templates

| Repository | What it does |
|---|---|
| [awesome-generative-engine-optimization](https://github.com/LucasFerrazSEO/awesome-generative-engine-optimization) | Curated, verified list of primary sources on GEO: AI crawler docs, standards, papers, tools and datasets |
| [free-open-source-seo-tools](https://github.com/LucasFerrazSEO/free-open-source-seo-tools) | Free and open source SEO tools by task, with license, last activity and honest limits |
| [geo-measurement-protocol](https://github.com/LucasFerrazSEO/geo-measurement-protocol) | Open protocol to measure brand citation across AI search surfaces: prompts, rounds, refusals, share of voice |
| [schema-org-templates-br](https://github.com/LucasFerrazSEO/schema-org-templates-br) | JSON-LD templates for Brazilian service businesses: clinics, law, accounting, real estate and more |
| [a-empresa-que-a-ia-recomenda](https://github.com/LucasFerrazSEO/a-empresa-que-a-ia-recomenda) | Companion materials for my book: checklists, llms.txt, robots.txt and entity JSON-LD (not the book text) |

#### WordPress

| Repository | What it does |
|---|---|
| [wordpress-functions](https://github.com/LucasFerrazSEO/wordpress-functions) | Snippets for a theme's functions.php: cleanup, image optimization, reCAPTCHA v3 on login |
| [wordpress-security-tips](https://github.com/LucasFerrazSEO/wordpress-security-tips) | Hardening snippets: functions.php, .htaccess and Cloudflare WAF rules |
| [privacy-policy-disclaimer-without-wordpress-plugin](https://github.com/LucasFerrazSEO/privacy-policy-disclaimer-without-wordpress-plugin) | Cookie consent for WordPress in one file for functions.php, no plugin: LGPD, GDPR, CCPA/CPRA, Google Consent Mode v2, embed blocking and consent log |
| [facilitated-routines-wordpress-plugin](https://github.com/LucasFerrazSEO/facilitated-routines-wordpress-plugin) | Planned WordPress plugin to automate repetitive maintenance tasks (no code yet) |

Every repository has a README in English and in Brazilian Portuguese. Bug
reports and suggestions are welcome through each repository's Issues.

For SEO, GEO or website projects, the way in is the agency,
[Lucas Ferraz SEO](https://lucasferrazseo.com).

<details>
<summary><strong>Português (Brasil)</strong></summary>

<br>

### Lucas Ferraz

Especialista em SEO, criação de sites e Generative Engine Optimization,
sediado em Belo Horizonte. Atuo profissionalmente com SEO desde 2007 e fundei
a [Lucas Ferraz SEO](https://lucasferrazseo.com), agência que atende
empresas de todo o Brasil. Meu trabalho tem duas camadas: ser encontrado no
Google e ser o nome que um assistente de IA recomenda.

- Notas técnicas, estudos e registros de pesquisa em [lucasferraz.com](https://lucasferraz.com)
- Autor de [*A Empresa que a IA Recomenda*](https://lucasferraz.com/livros/a-empresa-que-a-ia-recomenda/) (2026, ISBN 978-65-02-23078-7)
- Dados abertos dos meus estudos em [lucasferraz.com/estudos](https://lucasferraz.com/estudos/), sob CC BY 4.0
- As ferramentas acima são as mesmas que uso nas minhas auditorias, publicadas como estão

**Links.** [Site](https://lucasferraz.com) ·
[Blog](https://lucasferraz.com/blog/) ·
[Imprensa](https://lucasferraz.com/imprensa/) ·
[Agência](https://lucasferrazseo.com) ·
[LinkedIn](https://www.linkedin.com/in/lucasferrazseo/) ·
[YouTube](https://www.youtube.com/@lucasferrazseo) ·
[X](https://x.com/lucasferrazseo) ·
[Instagram](https://www.instagram.com/lucasferraztec/)

#### Repositórios por tema

- **GEO e busca com IA.**
  [citability-lint](https://github.com/LucasFerrazSEO/citability-lint),
  [chunk-boundary-lint](https://github.com/LucasFerrazSEO/chunk-boundary-lint),
  [page-to-ai-markdown](https://github.com/LucasFerrazSEO/page-to-ai-markdown),
  [llms-txt-lint](https://github.com/LucasFerrazSEO/llms-txt-lint),
  [anti-citation-directives-check](https://github.com/LucasFerrazSEO/anti-citation-directives-check),
  [ai-bots-list](https://github.com/LucasFerrazSEO/ai-bots-list),
  [ai-crawler-log-parser](https://github.com/LucasFerrazSEO/ai-crawler-log-parser),
  [citation-round-logger](https://github.com/LucasFerrazSEO/citation-round-logger),
  [ai-readiness-check](https://github.com/LucasFerrazSEO/ai-readiness-check) e
  [geo-lint-action](https://github.com/LucasFerrazSEO/geo-lint-action) (GitHub Action que roda essas checagens em pull request).
- **SEO técnico e dados estruturados.**
  [jsonld-graph-check](https://github.com/LucasFerrazSEO/jsonld-graph-check),
  [faq-schema-parity-check](https://github.com/LucasFerrazSEO/faq-schema-parity-check),
  [structured-data-json-ld](https://github.com/LucasFerrazSEO/structured-data-json-ld),
  [heading-structure-lint](https://github.com/LucasFerrazSEO/heading-structure-lint),
  [snippet-pixel-measure](https://github.com/LucasFerrazSEO/snippet-pixel-measure),
  [og-image-check](https://github.com/LucasFerrazSEO/og-image-check),
  [keyword-density-report](https://github.com/LucasFerrazSEO/keyword-density-report),
  [entity-sameas-check](https://github.com/LucasFerrazSEO/entity-sameas-check),
  [internal-link-audit](https://github.com/LucasFerrazSEO/internal-link-audit),
  [sitemap-similarity-check](https://github.com/LucasFerrazSEO/sitemap-similarity-check) e
  [sitemap-lastmod-audit](https://github.com/LucasFerrazSEO/sitemap-lastmod-audit).
- **Medição.**
  [ab-test-significance](https://github.com/LucasFerrazSEO/ab-test-significance),
  [gsc-cannibalization-finder](https://github.com/LucasFerrazSEO/gsc-cannibalization-finder) e
  [ai-referrer-report](https://github.com/LucasFerrazSEO/ai-referrer-report).
- **Guias, listas e modelos.**
  [awesome-generative-engine-optimization](https://github.com/LucasFerrazSEO/awesome-generative-engine-optimization) (fontes primárias de GEO, verificadas),
  [free-open-source-seo-tools](https://github.com/LucasFerrazSEO/free-open-source-seo-tools) (ferramentas abertas de SEO por tarefa),
  [geo-measurement-protocol](https://github.com/LucasFerrazSEO/geo-measurement-protocol) (protocolo de medição de citação por IA),
  [schema-org-templates-br](https://github.com/LucasFerrazSEO/schema-org-templates-br) (modelos de JSON-LD por segmento brasileiro) e
  [a-empresa-que-a-ia-recomenda](https://github.com/LucasFerrazSEO/a-empresa-que-a-ia-recomenda) (materiais de apoio do livro, sem o texto dele).
- **WordPress.**
  [wordpress-functions](https://github.com/LucasFerrazSEO/wordpress-functions),
  [wordpress-security-tips](https://github.com/LucasFerrazSEO/wordpress-security-tips),
  [privacy-policy-disclaimer-without-wordpress-plugin](https://github.com/LucasFerrazSEO/privacy-policy-disclaimer-without-wordpress-plugin) (consentimento de cookies com LGPD, GDPR, CCPA/CPRA e Consent Mode v2, sem plugin) e
  [facilitated-routines-wordpress-plugin](https://github.com/LucasFerrazSEO/facilitated-routines-wordpress-plugin) (plugin planejado, ainda sem código).

Todo repositório tem README em inglês e em português do Brasil. Relatos de
erro e sugestões são bem-vindos pelas Issues de cada repositório.

Para projetos de SEO, GEO ou criação de sites, o caminho é a agência,
[Lucas Ferraz SEO](https://lucasferrazseo.com).

</details>
