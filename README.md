# Library of Prompts

A collection of working, tested prompts — mostly built and refined with Google Gemini.  
Uses a consistent prompt template wherever possible.

For patent analysis, image generation, research, ideation, technical explanations, and more.

## Philosophy

The hardest part is getting past the blank page.  
The best way to create better outputs is through **iteration**, not through trying to write a perfect prompt on the first try.

Start somewhere good → run it → observe → refine → repeat.

This library exists to give you strong starting points so you can iterate faster and more effectively.

## Prompt Template

Most prompts in this collection follow (or are adapted from) this structure:

```text
You are an expert [ROLE / PERSONA] with deep knowledge and experience in [DOMAIN / FIELD].

Task:
[One clear sentence describing the main goal]

Context / Background / Reference (like few-shot prompts) / Constrains:
[Any important background information, constraints, goals, audience, tone, or previous conversation context]

Instructions:
• [Step or rule 1]
• [Step or rule 2]
• [Step or rule 3]
• Be [precise / creative / concise / exhaustive / critical / etc.]
• Think step-by-step where helpful
• Avoid [things to avoid, if any]

Output format:
• Use clear markdown formatting
• Start with a short summary (1–3 sentences)
• Then main content in well-structured sections
• Use bullet points, numbered lists, tables, or code blocks when appropriate
• End with [next steps / questions / suggestions / critique] if relevant

Now apply this to the following input:

[USER INPUT / DATA / QUESTION / CONTENT GOES HERE]
```

# Reusable Prompt Architect Library

A high-fidelity library of modular, tested prompts for Generative AI. This repository is built for precision, organized for searchability, and equipped with a local-first generation tool.

---

## 🚀 Quick Start

### 1. Using the Prompt Architect Tool
We have included a built-in web tool to help you generate and export prompts in the library's standard format.
* **Live Tool:** [ go to the Prompt Architect Tool](https://jsfiddler.github.io/library-of-prompts/)
* **Manual Use:** Open `index.html` in any modern web browser.
* **Batch Mode:** Paste a list of ideas into the "Batch" section to download a `.zip` containing individual `.md` files for your collection.

### 2. Library Structure
Prompts are categorized by their primary function to ensure the GitHub search bar ($/$) works effectively:
* `/image-prompts`: Photorealistic, 3D, and vector iconography.
* `/patent-analysis`: Legal-tech prompts with strict anti-hallucination protocols.
* `/web-design`: UI/UX layouts using the **[IDEA] [THEME] [CONTENT]** framework.

---

## 🛠️ The Framework: Modular Prompting

This library utilizes a modular variable system. Instead of static paragraphs, we use bracketed identifiers to separate concerns:

- **[IDEA]**: The core subject or business concept.
- **[THEME]**: The visual language, tone, or aesthetic constraints.
- **[CONTENT]**: Specific textual requirements or functional steps.

---

## 📝 Contribution Guide

To add a new prompt to this library:
1. Use the **Prompt Architect Tool** to generate the raw markdown.
2. Save the file using **kebab-case** naming (e.g., `minimalist-running-app.md`).
3. Place the file in the appropriate category folder.
4. Update the **Master Index** table in this README.

---

## ⚖️ License
MIT - Feel free to use, modify, and distribute these prompts.
