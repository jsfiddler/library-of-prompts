# Classification & JSON Extraction

## Description
A few-shot classification prompt designed to extract structured JSON data from product descriptions. It enforces a strict schema and limits category selection to a predefined list.

## System Instructions
> Analyze and categorize the input product description. Use JSON Format:
> - **title**: The name of the shoe model; if not provided, then provide a concise, descriptive title; title should be between 3 to 10 words.
> - **classification**: From the specified [shoe type list], select the category that best fits the product description. This must be in English. Selections outside of the [shoe type list] are not allowed.
> 
> Do not add any information that is not included in the product description.

## User Prompt
> **CLASSIFICATION LIST**: [Athletic Shoes, Casual Shoes, Dress Shoes, Boots, Sandals, Specialty Shoes]
>
> **Example 1**:
> Lightweight Shawnson running shoe with breathable mesh upper, responsive foam cushioning, durable rubber outsole for traction on various surfaces. Ideal for daily runs and training sessions.
> `{ "title": "Shawnson", "classification": "Athletic Shoes" }`
>
> **Target**:
> Classic leather upper, lace-up closure, cushioned footbed for comfort, versatile design suitable for both casual and semi-formal wear.

## Metadata
- **Model:** Gemini 3 Flash (Paid Tier)
- **Category:** Classification / Data Extraction
- **Output Format:** JSON
- **Tags:** #few-shot #json #classification #ecommerce
- **Date Created:** 2026-02-11
