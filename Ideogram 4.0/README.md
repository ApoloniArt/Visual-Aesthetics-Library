# ApoGalleria — Ideogram 4.0 Visual Aesthetics Library

**+20,000 instant styles, subjects & aesthetics — searchable, editable, and ready to run.**

This repository is a library of captioned reference images, each paired with a highly detailed, structured JSON aesthetic description. You are not buying the image — the image is a purely visual reference for the JSON. **What you're buying is the description itself**: a precise, reusable breakdown of style, lighting, composition, and subject that you can run instantly or edit to make your own.

Built specifically for **Ideogram 4.0** structured prompting, and designed to be used exclusively together with:

- 🖼️ **[ApoGalleria](#)** — my custom ComfyUI node (visual library manager). *Repo link coming soon.*
- 🎨 **[ApoStudio](https://github.com/ApoloniArt/ApoStudio)** — the captioning node suite and custom system prompts used to generate every entry in this library.
- 🧩 **[Kijai's Ideogram4 Prompt Builder](https://github.com/kijai/ComfyUI-KJNodes)** (ComfyUI-KJNodes) — the node this library's JSON schema is built to plug directly into.

All three work together as one pipeline: browse in **ApoGalleria** → edit or lock fields → pass straight into **Kijai's Ideogram4 Prompt Builder** → generate.

---

## 🔍 What's Inside

Every entry in this library is an image + JSON pair:

- **The image** — a visual reference only, so you know what the description produces. Image quality is not the product.
- **The JSON** — a detailed, structured caption describing the exact aesthetic: lighting, color palette, medium, art style, and full compositional breakdown, including individual elements, signatures, logos, and watermarks with bounding boxes.

Because every element — including watermarks and signatures — is captioned with its own bounding box, unwanted elements can be instantly removed via bbox deletion in Ideogram 4. That's the advantage of captioning to this level of detail.

## ✨ Why Use It

- **Never run out of ideas.** Search the library for a style, subject, or mood and you've got a ready-to-run starting point — no blank-page problem.
- **Mix and match.** Like the lighting and color of one image but not the subject? Open it in ApoGalleria, live-edit the JSON fields you want to change, lock the rest, and pass the result straight to output. Done.
- **Run it instantly, or make it yours.** Use any entry as-is, or treat it as a fully editable starting template.

## 🛠️ How It Was Made

- Captioned using my **[ApoStudio](https://github.com/ApoloniArt/ApoStudio)** nodes and custom system prompts, built specifically for Ideogram 4's structured JSON format.
- Every single caption was **manually syntax-checked by me, by hand**, at the point of creation, for correct JSON structure and closing syntax. No automated agents were used to verify the library — this was a fully manual quality pass across the entire set. It's not impossible that something slipped through, but it would genuinely surprise me.
- Scale: ~20,000 images captioned, representing roughly **55 straight hours** of captioning work.

## 📦 Requirements

To use this library as intended, you'll need:

1. **[ApoGalleria](#)** *(link coming soon)* — the node that reads this library and lets you browse, lock, edit, and export entries.
2. **[Kijai's ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)** — specifically the Ideogram4 Prompt Builder node, which this library's JSON schema is built to feed directly.

## 💬 Get the Library

This library is available for purchase directly from me. Join my Discord to get access:

### 👉 [discord.gg/XDExAUzuZp](https://discord.gg/XDExAUzuZp)

---

*Made by [ApoloniArt](https://github.com/ApoloniArt)*
