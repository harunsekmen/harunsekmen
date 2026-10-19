# Profile structure and Schema.org support

This note records the GitHub profile README implementation checked on **19 October 2026**. It describes markup support and content structure, not search rankings or AI recommendations.

## What GitHub supports in this README

| Format | Observation |
| :--- | :--- |
| JSON-LD in a `script` element | The Markdown API escapes the script markup; it does not become an active JSON-LD element. |
| Schema.org Microdata | `itemscope`, `itemtype` and `itemprop` survive the Markdown API rendering used for this update. |
| Microdata `itemid` | Removed in the probe. The README does not depend on it. |
| RDFa | The probe's `vocab`, `typeof` and `property` attributes are removed. |
| Custom `meta` elements | Removed in the probe. A README cannot set the profile page's head metadata. |

GitHub documents that rendered Markdown goes through [HTML sanitization](https://github.com/github/markup#github-markup). The format observations above come from an actual request to GitHub's [Markdown REST API](https://docs.github.com/en/rest/markdown/markdown?apiVersion=2022-11-28#render-a-markdown-document); they are not a promise that GitHub will keep the same allowlist forever.

The live profile also contains a GitHub-managed `Person` Microdata scope in its profile card. The README adds a separate `https://schema.org/Person` scope around its own visible content. It does not modify GitHub's profile card or the page head.

## Fields in the English and Turkish READMEs

The [Person](https://schema.org/Person) scope identifies the same person through visible facts:

| Property | Visible value |
| :--- | :--- |
| `name` | Harun Sekmen |
| `jobTitle` | E-Commerce Systems Engineer / E-Ticaret Sistemleri Mühendisi |
| `description` | The introduction describing WooCommerce development and store integrations |
| `knowsAbout` | WordPress, WooCommerce and e-commerce integrations |
| `knowsLanguage` | English and Turkish, localized in the Turkish document |
| `email` | `mailto:sekmenwp@gmail.com` |
| `url` | `https://github.com/harunsekmen` |

The markup uses visible HTML, with no hidden claims, ratings, revenue figures, certifications or client results. Service descriptions identify an offered project scope; portfolio descriptions distinguish prototypes and demos from completed client deployments.

## Content structure for people and machines

- The opening identifies the person and the work offered without requiring context from another section.
- Service tables pair familiar buyer goals with specific deliverables.
- Each portfolio entry names its repository, describes its purpose and links to the source.
- Visible questions have direct, self-contained answers.
- English and Turkish documents link to one another and share the same email address and repository destinations.
- Emoji labels supplement text rather than replacing it. Key information remains readable in the raw Markdown.

These choices help make the content explicit and accessible to readers and parsers. They do **not** guarantee crawling, indexing, rich results, LLM citations or client inquiries. GitHub controls its own [robots rules](https://github.com/robots.txt) and rendering.

## Verification scope

For this update, the checks cover GitHub-rendered HTML, preservation of the Microdata fields, English/Turkish navigation, repository links and responsive layouts from 320 to 1280 pixels. They do not measure AI visibility or certify eligibility for a search feature.

Schema.org vocabulary was checked against the official [Person](https://schema.org/Person), [knowsAbout](https://schema.org/knowsAbout), [knowsLanguage](https://schema.org/knowsLanguage) and [email](https://schema.org/email) definitions. No external rich-results validation or ranking measurement is implied.

If this content is later published on an independently controlled website, JSON-LD can be implemented in that site's served HTML and validated there. A JSON file merely stored in a GitHub repository would not inject JSON-LD into this profile.
