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
