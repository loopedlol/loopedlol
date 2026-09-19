# Field Notes / Portfolio visual system

[← Portfolio](../README.md)

A small visual system for documenting engineering experiments. It pairs strong typographic titles with diagrams that explain a project's actual subject.

## Shared conventions

- **Foundation:** warm paper `#f3f2ed` / graphite `#101b22`, with high-contrast text and quiet structural lines.
- **Typography:** local SVG text uses an Arial/Helvetica/sans-serif stack; diagrams remain self-contained without remote fonts.
- **Composition:** numbered project label, large title, concise premise, subject-specific line illustration, compact technical focus line.
- **Geometry:** narrow strokes, restrained rounded corners, explicit connections, and repeated nodes or cells. No animation or external badge widgets.
- **Hierarchy:** two deeper system case studies, then two shorter experiment entries. Long operational detail lives in linked Markdown guides.
- **Navigation:** profile → project → technical reference, with a portfolio return link on each project.
- **Accessibility:** descriptive image alternatives, ordinary text links beside project cards, and readable Markdown explanations for diagrams.
- **Rendering:** GitHub-supported `picture`, `img`, tables, and details. No script, external SVG font, foreignObject, or arbitrary README CSS.

## Project identities

| Project | Accent, light / dark | Motif |
| --- | --- | --- |
| CarVisionAI | `#146975` / `#74ced2` | Occupancy cells, alternative paths, sensing fan |
| Safety Lens | `#536927` / `#c1d789` | Two displays, human confirmation, evidence trail |
| SignLanguageAI | `#9a4936` / `#f3a48e` | Hand geometry, temporal traces, sequence samples |
| RAG Document QA | `#835914` / `#e9c278` | Layered documents, selected chunks, retrieval path |

The profile's loop-and-node mark connects the subjects without presenting itself as a project architecture.

## Asset sizes

- Profile hero: 1200 × 440.
- Project hero: 1200 × 360.
- Flagship profile card: 1200 × 270.
- Focused-experiment profile card: 1200 × 220.
- System diagrams: 1200 wide, height chosen for the content.
- Social previews: 1280 × 640 PNG plus editable SVG.

Heroes and diagrams have opaque backgrounds, so text remains legible in each theme. README `picture` elements select light/dark variants and retain a light fallback. Actual screenshots retain their original colors. This follows [GitHub's picture-element guidance](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax#the-picture-element).

Social-preview PNGs use [GitHub's recommended dimensions](https://docs.github.com/en/repositories/managing-your-repositorys-settings-and-features/customizing-your-repository/customizing-your-repositorys-social-media-preview). Assignment in repository settings is a separate administrative action.

## Editorial standard

A schematic is not a screenshot. A synthetic demo is not a hardware trial. An LLM-graded artifact is not a benchmark guarantee. Use captions to preserve those distinctions and keep claims tied to source or retained evidence.
