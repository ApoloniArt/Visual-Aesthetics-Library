# ApoGalleria — [Ideogram 4.0] Visual Aesthetics Library

**+20,000 instant styles, subjects & aesthetics — searchable, editable, and ready to run.**

An extensive library of captioned reference images, each paired with a highly detailed, structured JSON aesthetic description. You are not buying the image — the image is a purely visual reference for the JSON. **What you're buying is the description itself**: a precise, reusable breakdown of style, lighting, composition, and subject that you can run instantly or edit to make your own.

Built specifically for **Ideogram 4.0** structured prompting, and designed to be used exclusively together with:

- 🖼️ **[ApoGalleria](#)** — my custom ComfyUI node (Visual aesthetics Library). *Repo link coming soon.*
- 🎨 **[ApoStudio](https://github.com/ApoloniArt/ApoStudio)** — the captioning node suite and custom system prompts used to generate every caption in my library.
- 🧩 **[Kijai's Ideogram4 Prompt Builder](https://github.com/kijai/ComfyUI-KJNodes)** (ComfyUI-KJNodes) — the node my library's JSON schema is built to plug directly into.

All three work together as one pipeline: browse in **ApoGalleria** → edit or lock fields → pass to output, straight into **Kijai's Ideogram4 Prompt Builder** → generate.

---

## 🔍 What's Inside

Every entry in my library is a jpg image + JSON pair:

- **My library covers a multitude of styles, aesthetics, subjects, objects, people, poses, architecture.**
- **The image** — a visual reference only, so you know what the description produces. Images are NOT the product, the product is my captioning!
- **The JSON** — a highly detailed, structured caption describing the exact aesthetic: lighting, color palette, medium, art style, and full compositional breakdown, including all individual elements coordinated within bounding boxes.
- **Usual Caveats** — No captioning/prompting system is 100% perfect, all LLMs still have certain weaknesses with left/right perspectives etc. I can confidently say my captioning system is far better than most, although still not perfect.
**For complete transparency, you can download and test my [Ideogram4 Example Dataset](#) to see the level of image quality my captioning produces. You will not be diappointed!**
Every element in each image's composition is captioned — including any watermarks, signatures and logos — each within their own bounding boxes, unwanted elements can be instantly removed via bbox deletion. That's the beauty of Ideogram 4, and the massive advantage of this model when captioning to this level of detail.

**My libraries are a mixture of my images, and images I have collected from various places over a long, long time. To be clear, you are buying my time, skills and compute that it took to caption the thousands of images, not the images themselves. The images are purely to extract a reference to create a highly descriptive json. I do not sell other people's work, only my own.**

## ✨ Why Use It

- **Never run out of ideas.** Search my colossal library for a style, subject, or mood and you've got a ready-to-run starting point — no blank-page problem.
- **Mix and match.** Like the lighting and color of one image but not the subject? Open it in **[ApoGalleria](#)**, live-edit the JSON fields you want to change, lock the rest, and pass the result straight to output. Done.
- **Run it instantly, or make it yours.** Use any image as-is for a recreation, or treat it as a fully editable starting template, moulding your idea from a seed.

## 🛠️ How It Was Created 

- Captioned using my **[ApoStudio](https://github.com/ApoloniArt/ApoStudio)** nodes and custom system prompts, specifically for Ideogram 4's structured JSON format.
- Every single caption was **manually syntax-checked by me, by hand**, at the point of creation, for correct JSON structure and closing syntax. No automated agents were used to verify the library — this was a fully manual quality pass across the entire set. It's not impossible that something slipped through, but it would genuinely surprise me.
- Scale: ~20,000 images captioned, representing roughly **55 straight hours** of captioning work.

## 📦 Requirements

To use this library as intended, you'll need:

1. **[ApoGalleria](#)** *(link coming soon)* — the node that reads this library and lets you browse, lock, edit, and export entries.
2. **[Kijai's ComfyUI-KJNodes](https://github.com/kijai/ComfyUI-KJNodes)** — specifically the Ideogram4 Prompt Builder node, which this library's JSON schema is built to feed directly.

## 💬 Get the Library

This library is available for purchase directly from me. Join my Discord to get access:

### 👉 [ApoloniArt](https://discord.gg/XDExAUzuZp)

---

*Made by [ApoloniArt](https://github.com/ApoloniArt)*
