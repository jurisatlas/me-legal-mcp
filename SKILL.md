---
name: me-legal-mcp-skill
description: Official Montenegro (ME) legislation, multi-tier court precedent research, and citation verification skill.
version: 2.0.0
author: JurisAtlas
license: MIT
---

# Montenegro Legal Research & Multi-Tier Case Law Skill (`me-legal-mcp`)

Use this skill whenever the user asks a legal question, drafts a pleading or contract, or researches case law across any judicial instance in **Montenegro (ME)**.

## Verification & Research Rules

1. **Citation Verification:** Never fabricate a statutory provision or case citation. Query `search_legislation`, `search_case_law`, `search_tiered_court_decisions`, or `verify_citation` before citing any authority (e.g., `Rev.br. 123/24 or Službeni list CG br. 15/2024`).
2. **Multi-Tier Judicial Coverage:**
   - **First Instance (Trial / Municipal / District):** Osnovni sudovi (15 Basic Courts across Montenegro), Privredni sud Crne Gore & Sudovi za prekršaje
   - **Second Instance (Cantonal / Regional / Appellate):** Viši sud u Podgorici, Viši sud u Bijelom Polju, Apelacioni sud Crne Gore & Upravni sud Crne Gore
   - **Supreme & Constitutional Instance:** Vrhovni sud Crne Gore & Ustavni sud Crne Gore
   - **Primary Tiered Database:** Centralni portal Sudovi Crne Gore - Odluke svih sudova (sudovi.me) (`https://sudovi.me/odluke-sudova`)
