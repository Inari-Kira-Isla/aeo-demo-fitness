<think>The user wants me to create a `GEMINI.md` file for a project called "aeo-demo-fitness" based on provided `AGENTS.md` content.

**Analysis of input:**
*   **Project Name:** aeo-demo-fitness
*   **Description:** AEO Demo — fitness industry template with Schema.org, llms.txt, FAQ, AI-friendly markup
*   **Topics:** aeo, ai-friendly, demo, schema-org, template
*   **Language:** HTML

**Requirements for output:**
1.  Start with `# Project Name` title.
2.  ## Overview - 2-3 sentences about the project.
3.  ## Tech Stack - List technologies.
4.  ## Architecture - Key directories and architecture description.
5.  ## Commands - Dev/build/deploy instructions.
6.  ## Coding Style - Code style guidelines.
7.  ## Important Rules - Key rules and prohibitions.
8.  Keep it concise, under 80 lines.
9.  Preserve Chinese if present, otherwise English (Input seems to be English).

**Drafting content:**
*   **Overview:** This is a demo template for the fitness industry designed for AEO (AI Engine Optimization). It focuses on making content friendly for LLMs and AI agents using Schema.org, llms.txt, and semantic HTML.
*   **Tech Stack:** HTML5, Schema.org (JSON-LD), CSS (likely simple, maybe inline or small files), llms.txt generation.
*   **Architecture:** It's a static HTML site. Likely a single page or a few pages demonstrating the schema. Key files: `index.html`, `llms.txt`, schema tags.
*   **Commands:** Since it's raw HTML, "commands" might just be "Open index.html" or a simple static server command (e.g., `python3 -m http.server`). Let's assume a standard static site structure.
*   **Coding Style:** Semantic HTML, proper meta tags, JSON-LD structure for SEO.
*   **Important Rules:** Must adhere to AEO principles, ensure Schema.org validation, maintain AI-friendly content structure.

**Refining for the specific format:**
The user explicitly asked for the content of the GEMINI.md file based on the AGENTS.md provided.

**Structure:**
1.  `# aeo-demo-fitness`
2.  `## Overview`: A demo template for the fitness industry focusing on AI Engine Optimization (AEO). It utilizes Schema.org, llms.txt, and semantic markup to make content easily accessible and interpretable by LLMs and AI agents.
3.  `## Tech Stack`: HTML5, JSON-LD (Schema.org), CSS (Standard/Responsive).
4.  `## Architecture`: Static HTML structure. Contains specific files for AI crawling (llms.txt) and structured data (Schema.org JSON-LD).
5.  `## Commands`: Serve the static files.
    *   `python3 -m http.server 8000` (or similar)
    *   No complex build steps mentioned in AGENTS.md, implying raw HTML deployment.
6.  `## Coding Style`: Semantic HTML5, clear commenting, strict JSON-LD syntax.
7.  `## Important Rules`: Ensure all pages have valid Schema.org data. Do not remove AI-friendly markup. Maintain llms.txt.

**Language check:** The AGENTS.md content is English, so I will use English.

Let's assemble the markdown.

```markdown
# aeo-demo-fitness

## Overview
AEO Demo template for the fitness industry. It demonstrates how to structure web content using Schema.org, llms.txt, and semantic HTML to be fully optimized for AI agents and LLMs (AI Engine Optimization).

## Tech Stack
- HTML5 (Semantic Markup)
- JSON-LD (Schema.org)
- llms.txt (AI discovery)

## Architecture
- Single-page or multi-page static HTML structure.
- Contains `llms.txt` for AI crawler discovery.
- Embedded or dedicated JSON-LD scripts for Schema.org data.

## Commands
- Serve locally: `python3 -m http.server` or `npx serve`
- Validate Schema: Use Google Rich Results Test / Schema Markup Validator
- Check AI accessibility: Ensure `llms.txt` is accessible

## Coding Style
- Use semantic HTML tags (`<article>`, `<section>`, `<main>`).
- JSON-LD must be valid and embedded in `<head>`.
- Clear, descriptive content structure.

## Important Rules
- Strictly adhere to AEO principles.
- Do not obscure Schema.org data with heavy JS that blocks rendering.
- Maintain valid `llms.txt` format.
```

I need to check line count. Looks fine.

Let's finalize the output.</think>

# aeo-demo-fitness

## Overview
AEO Demo template for the fitness industry. It demonstrates how to structure web content using Schema.org, llms.txt, and semantic HTML to be fully optimized for AI agents and LLMs (AI Engine Optimization).

## Tech Stack
- HTML5 (Semantic Markup)
- JSON-LD (Schema.org)
- llms.txt (AI discovery)

## Architecture
- Static HTML structure (likely single or multi-page).
- Key file `llms.txt` for AI crawler discovery.
- Embedded JSON-LD scripts for structured data (Schema.org).

## Commands
- **Serve Local**: `python3 -m http.server` or `npx serve`
- **Validate Schema**: Use Google Rich Results Test / Schema Markup Validator
- **Check AI Access**: Verify `llms.txt` is reachable and parseable

## Coding Style
- Semantic HTML5 tags (`<main>`, `<article>`, `<section>`).
- JSON-LD must be valid and placed in `<head>`.
- Clean, descriptive content for LLM readability.

## Important Rules
- Strictly adhere to AEO principles (AI-friendly markup).
- Do not use aggressive JS that hides semantic content.
- Ensure `llms.txt` is always valid and up-to-date.