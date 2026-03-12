# aeo-demo-fitness

## Project
AEO (AI-Friendly) Demo template for fitness industry using HTML with Schema.org, llms.txt, FAQ, and AI-friendly markup.

## Conventions
- Use semantic HTML5 elements
- Include Schema.org structured data in JSON-LD format
- Generate llms.txt for AI crawlers
- Add FAQ sections using appropriate schema markup
- Keep markup minimal and clean

## Naming
- Use lowercase with hyphens for file names: `fitness-tips.html`
- Use descriptive class names related to fitness domain
- Name schema files with `-schema` suffix

## Architecture
- Single HTML files with embedded or separate JSON-LD
- Static site approach (no build tools required)
- llms.txt as separate static file
- FAQ implemented as collapsible sections with schema

## Commands
- No build commands needed — static HTML files
- Open HTML files directly in browser for testing

## Do Not
- Don't add unnecessary JavaScript frameworks
- Don't use inline styles — use external CSS files
- Don't omit Schema.org markup on key pages
- Don't forget to include llms.txt for AI accessibility
- Don't use non-semantic div elements where semantic HTML applies