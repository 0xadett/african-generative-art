# African Generative Art

A `p5.js` generative art collection translating West African textiles, sacred symbols, and geometry—including Asante Kente, Akan Adinkra, Yoruba Adire, Aso-Oke, Ọṣun sacred curves, and Ìbejì duality—into interactive algorithmic compositions.

- **Interactive Visualizer (GitHub Pages):** [0xadett.github.io/african-generative-art](https://0xadett.github.io/african-generative-art/)

## Sketches & Algorithms

Each link opens the sketch directly in the live browser visualizer with an on-screen switcher and control bar:

| Sketch | Title & Cultural Focus | Generative Techniques | Controls | Live Preview |
| :--- | :--- | :--- | :--- | :--- |
| `kente_cloth_generator.js` | **Day 1: Asante Kente Cloth** | Grid loops, `push`/`pop` local transforms, seeded strip palettes | `R` Seed, `S` Save PNG | [Open](https://0xadett.github.io/african-generative-art/?sketch=kente_cloth_generator.js) |
| `adinkra_symbol_field.js` | **Day 2: Adinkra Symbol Field** | Custom polygons & `arc()` geometry (*Dwennimmen*, *Gye Nyame*, *Sankofa*, *Nyame Dua*, *Fawohodie*) | `R` Seed, `S` 2400px PNG, `1–6` Palettes | [Open](https://0xadett.github.io/african-generative-art/?sketch=adinkra_symbol_field.js) |
| `adinkra_offset_gutter_grid.js` | **Day 2B: Adinkra Offset + Gutter Grid** | Proportional outer offset, inner cell gutters, tinted backgrounds | `R` Seed, `S` 2400px PNG, `1–6` Palettes | [Open](https://0xadett.github.io/african-generative-art/?sketch=adinkra_offset_gutter_grid.js) |
| `adire_resist_dye_noise.js` | **Day 3: Yoruba Adire Resist-Dye** | Continuous 3D Perlin `noise()` simulating *Eleko* wax & *Oniko* tie-dye | `Space` Pause, `R` Seed, `S` PNG, `1–4` Styles, `↑/↓` Zoom | [Open](https://0xadett.github.io/african-generative-art/?sketch=adire_resist_dye_noise.js) |
| `asooke_flow_field.js` | **Day 4: Yoruba Aso-Oke Flow Field** | OOP `Particle` threads steered by a Perlin noise vector field | `Space` Pause, `R` Seed, `S` PNG, `1–5` Palettes, `↑/↓` Density, `Click` Burst | [Open](https://0xadett.github.io/african-generative-art/?sketch=asooke_flow_field.js) |
| `osun_rose_curve_mandala.js` | **Day 5: Ọṣun Sacred Geometry** | Parametric rose curves and layered spirals | `Space` Pause, `R` Random, `S` PNG, `1–5` Palettes, `←/→` Petals, `↑/↓` Speed, `Click` Center | [Open](https://0xadett.github.io/african-generative-art/?sketch=osun_rose_curve_mandala.js) |
| `ibeji_dumbbell_mandala.js` | **Sketch 8: Ìbejì Dumbbell Mandala** | Concentric polar rings, Perlin wobble, twin dumbbell motif | `Space` Spin, `R` Seed, `S` PNG, `1–4` Palettes | [Open](https://0xadett.github.io/african-generative-art/?sketch=ibeji_dumbbell_mandala.js) |
| `geometric_dumbbell_grid.js` | **Sketch 9: Geometric Dumbbell Grid** | Tiled motif grid, Tweakpane v3 panel, `P5Capture` MP4 recording | `A` Animate, `C` Capture MP4, `S` PNG, `1–4` Palettes | [Open](https://0xadett.github.io/african-generative-art/?sketch=geometric_dumbbell_grid.js) |
| `inspo.js` | **Grid Study: Offset & Inner Margins** | 8×8 proportional grid in HSB mode with grainy paper texture | Auto-redraw (`0.7 fps`) | [Open](https://0xadett.github.io/african-generative-art/?sketch=inspo.js) |

## Workflow & Reference Files

- **`svg_workflow.js`** — Reference template and Canvas API → `p5.js` translation table (`beginShape`/`bezierVertex`/`arc`) for converting Affinity Designer SVGs exported via `svg2canvas`.
- **`source_canvas.js`** — Raw Canvas path reference exported from vector artwork used to measure motifs for the dumbbell sketches.

## Libraries Used

Loaded via CDN in `index.html`: `p5.js` (1.11.1), `p5.sound`, `chroma.js`, `p5.capture`, and `Tweakpane`.
