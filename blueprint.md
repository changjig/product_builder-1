# Project Blueprint

## Overview
This project aims to optimize a website for AI search (GEO) based on provided articles, focusing on content, structured data, E-E-A-T, and user experience. It's a framework-less web project (HTML, CSS, JavaScript) within the Firebase Studio environment.

## Implemented Features

### Initial Version
- Basic website structure with `index.html`, `about.html`, `shop-registration.html`, `correction-report.html`, `privacy-policy.html`, `robots.txt`, `sitemap.xml`.
- Placeholder content for various sections.

### GEO Optimization Phase 1 (Initial AI Agent Task)
- **`index.html`:**
    - Updated `<h1>` and `<p class="subtitle">` to be more conversational.
    - Added a "Jini's Tips for Choosing Delicious Dubai Cookies!" section for expertise.
    - Implemented a top navigation bar for improved user experience.
    - Replaced generic `ItemList` structured data with detailed `Bakery` schema for each shop.
    - Added `FAQPage` schema for the FAQ section.
    - Updated the "Last Updated" date in the footer to 2026.02.05.
- **`about.html`:**
    - Rewritten to build E-E-A-T, introducing a persona "Jini" and explaining the site's mission.
    - Updated `title` and `meta description`.
    - Added `Person` schema to structured data.
- **`robots.txt`:** Reviewed and confirmed to be correctly configured.
- **Performance:** Identified `cookie-logo.png` (902KB) as a performance issue, noted that `cookie-logo.webp` (9.1KB) is an efficient alternative in use.

### Current Changes (User Request)
- **`index.html`:**
    - Corrected the `div.shop-links` for "초심 베이커리" to include a single "📦 택배 사이트" link (https://smartstore.naver.com/chosimbakery), a single "📷 인스타" link (https://www.instagram.com/chosim.bakery/), and the existing "🗺️ 네이버 플레이스" link.

## Plan for Current Request

The user wants the changes to be deployed directly to the GitHub repository: `https://github.com/changjig/product_builder-1`.

**Steps:**
1.  **Confirm with User:** Explain that direct pushes to a remote repository require explicit confirmation.
2.  **Request Commit Message:** Ask the user for a commit message.
3.  **Perform Git Operations (if approved):**
    - `git add .`
    - `git commit -m "User provided commit message"`
    - `git push origin main` (assuming `main` is the target branch, will confirm if needed)

**Note:** The agent will not proceed with Git operations without explicit user approval and a commit message.
