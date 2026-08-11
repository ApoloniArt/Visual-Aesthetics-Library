# ApoGalleria-Libraries

I adore Ideogram 4, I'm also a purist and control freak.....I want complete creative license on every level.
So I created **[ApoGalleria](#)** as a personal project to fill my exact needs. To satiate ApoGalleria, this behemoth was born. 
**The largest image aesthetics library I ever created.**
My entire 25.000 image Library contains the highest descriptive level of structured json captions currently possible, at an unmatched level of intricate detail. 
You can then filter down to other architectures, to output captions in their format using my **[ApoGalleria](#)** add-on 'convert output to' nodes.

**Instant styles, subjects & aesthetics — searchable, editable, and ready to run.**

This repository is a growing collection of captioned reference-image libraries. Each library targets a specific image-generation architecture and pairs images with a highly detailed aesthetic description, written in whichever format that architecture actually reads best. You are not buying the images — they're purely a visual reference for the caption. **What you're buying is the description itself**: a precise, reusable breakdown of style, lighting, composition, and subject that you can run instantly or edit to make your own.

Every library is built to be used together with:

- 🖼️ **[ApoGalleria](#)** — my custom ComfyUI node (visual aesthetics library manager). *Repo link coming soon.*
- 🎨 **[ApoStudio](https://github.com/ApoloniArt/ApoStudio)** — my captioning node suite and custom system prompts, used to generate every caption across all of these libraries.

Browse in **ApoGalleria** → edit or lock fields → pass to output, straight into the matching prompt-builder node for that architecture → generate.

---

## 📚 Libraries in This Repo

Each folder below is a self-contained library with its own README, covering the exact caption format, node pairing, and details for that architecture.

| Library | Caption Format | Status |
|---|---|---|
| [Ideogram 4.0](./Ideogram%204.0) | Structured JSON | ✅ Available |
| Flux2 | Structured JSON | 🔜 Planned |
| Qwen-Image | Natural language | 🔜 Planned |
| Z-Image Turbo | Natural language | 🔜 Planned |
| Krea2 | Natural language (JSON-capable) | 🔜 Planned |
| Flux (1) | Natural language | 🔜 Planned |

## 🔍 What's Inside Each Library

- **Image + caption pairs** — the image is a visual reference only; the caption is the product. The exact caption format (structured JSON, natural-language prose, or both) is whatever that architecture was actually trained to read — see each library's own README for specifics.
- **Highly detailed captions** — lighting, color palette, medium, art style, and full compositional breakdown, down to individual elements where the format and architecture support it (e.g. bounding boxes for JSON-based schemas).
- **Manually quality-checked** — every caption is hand-verified for correct structure and syntax at the point of creation. No automated agents used for QA.
- **Example datasets** — most libraries include a non-cherry-picked sample folder so you can preview caption quality before purchasing.

## ✨ Why Use These Libraries

- **Never run out of ideas.** Search for a style, subject, or mood and you've got a ready-to-run starting point.
- **Mix and match.** Like the lighting of one image but not the subject? Open it in ApoGalleria, live-edit the parts you want, keep the rest, and pass it straight to output.
- **Run it instantly, or make it yours.** Use any entry as-is, or treat it as a fully editable starting template.

## 🛠️ How They're Made

- Captioned using my **ApoStudio** nodes and custom system prompts, tailored to each architecture's specific prompting format — structured JSON where the model supports it, natural language where that's what it was trained on.
- Each library represents a large, dedicated captioning effort — see the individual library README for exact scale and time invested.
- My libraries are a mix of my own images and images collected over a long time. You're buying my time, skills, and the captioning work — not the images themselves. I don't sell other people's work, only my own.

## 📦 Requirements

To use any library as intended, you'll need:

1. **[ApoGalleria](#)** *(link coming soon)* — the node that reads these libraries and lets you browse, lock, edit, and export entries.
2. The matching prompt-builder or text-encode node for that library's architecture (e.g. Kijai's Ideogram4 Prompt Builder from ComfyUI-KJNodes for the Ideogram 4.0 library — see that library's own README for details).

## 💬 Get a Library

These libraries are available for purchase directly from me. Join my Discord and hit me up to get access:

### 👉 [ApoloniArt Discord](https://discord.gg/XDExAUzuZp)

---

*Made with love by [ApoloniArt](https://github.com/ApoloniArt) because I wanted inspiration on tap.* With **ApoGalleria** and these libraries, I never have to worry again.
Neither will you 💜
