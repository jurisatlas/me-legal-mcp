# Montenegro Legal Research MCP Server (`me-legal-mcp`)

**[Crnogorski](#lang-cnr) | [Srpski](#lang-sr) | [English Documentation](#english-documentation)**

---

<a id="lang-cnr"></a>
## Pravni MCP Server za Crnu Goru (`me-legal-mcp`) — Crnogorski

### O ovom repozitorijumu

Ovaj repozitorijum omogućava povezivanje vaše AI aplikacije (Claude Desktop, Cursor, Windsurf, VS Code, Antigravity) sa Službenim listom Crne Gore (`sluzbenilist.me`) i centralnom bazom sudskih odluka (`sudovi.me`) koja obuhvata osnovne sudove, Privredni sud, više sudove u Podgorici i Bijelom Polju, Apelacioni sud, Upravni sud, Vrhovni sud i Ustavni sud Crne Gore.

### Brza instalacija (Izbor AI aplikacije)

1. **Preuzimanje:** Kliknite na **`<> Code` -> `Download ZIP`** i raspakujte fasciklu.
2. **Pokretanje:** Pokrenite **`Click_Here_To_Install_Windows.bat`** (Windows) ili **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Izbor AI aplikacije:** Označite AI aplikacije koje koristite, kliknite na instalaciju i restartujte odabrani AI program.

**Sigurnosna napomena:** Alat ne pristupa vašim ličnim dokumentima na računaru; pretražuje isključivo javne pravne registre.

### Sudske instance i izvori

| Stepen suda | Obuhvaćeni sudovi u Crnoj Gori |
|:---|:---|
| **Prvostepeni sudovi (Osnovni i Privredni sud)** | Osnovni sudovi (15 Basic Courts across Montenegro), Privredni sud Crne Gore & Sudovi za prekršaje |
| **Viši sudovi, Apelacioni i Upravni sud** | Viši sud u Podgorici, Viši sud u Bijelom Polju, Apelacioni sud Crne Gore & Upravni sud Crne Gore |
| **Vrhovni i Ustavni sud Crne Gore** | Vrhovni sud Crne Gore & Ustavni sud Crne Gore |

- **Službeni list Crne Gore (sluzbenilist.me) & Gov.me Legislation:** [https://www.sluzbenilist.me](https://www.sluzbenilist.me) (`sluzbenilist.me`, `gov.me`, `skupstina.me`, `paragraf.me`)
- **Centralni portal Sudovi Crne Gore - Odluke svih sudova (sudovi.me):** [https://sudovi.me/odluke-sudova](https://sudovi.me/odluke-sudova) (`sudovi.me`, `ustavnisud.me`, `gov.me`, `paragraf.me`)

---

<a id="lang-sr"></a>
## Pravni MCP Server (`me-legal-mcp`) — Srpski

### O ovom repozitorijumu

Ovaj repozitorijum sadrži Model Context Protocol (MCP) server koji povezuje vašu AI aplikaciju (Claude Desktop, Cursor, Windsurf, VS Code / Copilot, Cline ili Antigravity) sa službenim glasnicima i bazama sudske prakse za **Montenegro** (prvostepeni osnovni/opštinski i privredni sudovi, drugostepeni apelacioni/okružni/kantonalni i viši sudovi, kao i vrhovni i ustavni sudovi).

### Brza instalacija (Izbor AI aplikacije)

1. **Preuzimanje:** Kliknite na **`<> Code` -> `Download ZIP`** i raspakujte arhivu na računaru.
2. **Pokretanje:** Dvokliknite na **`Click_Here_To_Install_Windows.bat`** (Windows) ili **`Click_Here_To_Install_Mac.command`** (macOS).
3. **Izbor AI klijenta:** U instalacionom prozoru izaberite AI aplikacije koje koristite (Claude, Cursor, Windsurf, VS Code, Antigravity), kliknite na dugme za instalaciju i ponovo pokrenite izabranu AI aplikaciju.

**Bezbednosna napomena:** Program radi u izolovanom režimu čitanja (read-only) i ne pristupa niti menja vaše lične datoteke na računaru.

### Sudske instance i službeni izvori

| Sudska instanca | Obuhvaćeni sudovi |
|:---|:---|
| **1. Stepen (Prvostepeni sudovi)** | Osnovni sudovi (15 Basic Courts across Montenegro), Privredni sud Crne Gore & Sudovi za prekršaje |
| **2. Stepen (Apelacioni, okružni, kantonalni i viši sudovi)** | Viši sud u Podgorici, Viši sud u Bijelom Polju, Apelacioni sud Crne Gore & Upravni sud Crne Gore |
| **3. Stepen (Vrhovni i Ustavni sud)** | Vrhovni sud Crne Gore & Ustavni sud Crne Gore |

- **Službeni list Crne Gore (sluzbenilist.me) & Gov.me Legislation:** [https://www.sluzbenilist.me](https://www.sluzbenilist.me) (`sluzbenilist.me`, `gov.me`, `skupstina.me`, `paragraf.me`)
- **Centralni portal Sudovi Crne Gore - Odluke svih sudova (sudovi.me):** [https://sudovi.me/odluke-sudova](https://sudovi.me/odluke-sudova) (`sudovi.me`, `ustavnisud.me`, `gov.me`, `paragraf.me`)

---

<a id="english-documentation"></a>
## English Documentation

Model Context Protocol (MCP) server providing live, read-only access to **Montenegro (ME)** legislation, official gazettes, multi-tier judicial decisions (First Instance, Regional/Cantonal/Appellate, and Supreme/Constitutional courts, including HTML and PDF full-text extraction), and statutory citation verification across all major AI clients (**ChatGPT Desktop, OpenAI Codex CLI, Claude Desktop, Claude Code CLI, Cursor, Windsurf, VS Code / GitHub Copilot / Cline / Roo Code, Google Antigravity / Gemini CLI, Perplexity, and Continue.dev**).

---

### Interactive Desktop Setup (Select Your AI Assistant)

This package includes a graphical installer for legal practitioners and non-technical users that lets you select which AI application(s) you use:

1. **Download:** Click **`<> Code`** at the top right of this repository, select **`Download ZIP`**, and extract the folder to your computer.
2. **Run the Setup Utility:**
   - **Windows:** Double-click `Click_Here_To_Install_Windows.bat`
   - **macOS:** Double-click `Click_Here_To_Install_Mac.command`
3. **Select Your AI Client(s) & Connect:** Check the box(es) for the AI assistant(s) installed on your computer (**ChatGPT Desktop & OpenAI Codex CLI**, **Claude Desktop & Claude Code CLI**, **Cursor**, **Windsurf**, **VS Code / GitHub Copilot / Cline / Roo Code**, **Google Antigravity / Gemini CLI**, or **Perplexity / Continue.dev**), click **Install to Selected AI Clients**, and restart your selected AI application.

**System Integrity Note:** The setup utility operates strictly in read-only mode with respect to your personal files and documents. It installs an isolated Python runtime inside the extracted folder and registers the server entry only in the AI client configuration files you select.

---

### Multi-Tier Judicial Hierarchy & Live Indexed National Archives

This server performs live queries across the full judicial hierarchy and official legal archives of **Montenegro**, extracting full text from both HTML pages and official court/gazette PDF judgments:

| Judicial Tier | Covered Courts & Tribunals |
|:---|:---|
| **Tier 1 — First Instance** | Osnovni sudovi (15 Basic Courts across Montenegro), Privredni sud Crne Gore & Sudovi za prekršaje |
| **Tier 2 — Regional / Cantonal / Appellate** | Viši sud u Podgorici, Viši sud u Bijelom Polju, Apelacioni sud Crne Gore & Upravni sud Crne Gore |
| **Tier 3 — Supreme & Constitutional** | Vrhovni sud Crne Gore & Ustavni sud Crne Gore |

#### Official Portals & Live Indexed Domains

- **National Legislation & Official Gazette:** Službeni list Crne Gore (sluzbenilist.me) & Gov.me Legislation — [https://www.sluzbenilist.me](https://www.sluzbenilist.me)
  - *Indexed Legislation Domains:* `sluzbenilist.me`, `gov.me`, `skupstina.me`, `paragraf.me`
- **Court Decisions & Jurisprudence Archives:** Centralni portal Sudovi Crne Gore - Odluke svih sudova (sudovi.me) — [https://sudovi.me/odluke-sudova](https://sudovi.me/odluke-sudova)
  - *Indexed Judicial & Open Case Law Domains:* `sudovi.me`, `ustavnisud.me`, `gov.me`, `paragraf.me`

---

### Available MCP Tools

| Tool | Description |
|:---|:---|
| `search_legislation` | Searches enacted statutes, codes, decrees, and official gazette publications in Montenegro. |
| `search_case_law` | Searches national jurisprudence and open judicial archives for Montenegro. |
| `search_tiered_court_decisions` | Filters case law specifically by judicial instance (`first_instance`, `appellate_regional`, `supreme_constitutional`) or specific regional/cantonal/district court. |
| `list_court_hierarchy` | Returns the complete 3-tier court structure and supported regional court filters for Montenegro. |
| `get_legal_document_markdown` | Retrieves full statutory or judicial texts (both HTML and official `.pdf` court judgments) and converts them into clean Markdown. |
| `verify_citation` | Validates statutory and case law citations against official registries. |

---

<details>
<summary><b>Manual Configuration for Developers (Optional)</b></summary>

```json
{
  "mcpServers": {
    "me-legal-mcp": {
      "command": "uvx",
      "args": [
        "--from",
        "https://github.com/jurisatlas/me-legal-mcp/archive/refs/heads/main.zip",
        "me-legal-mcp"
      ]
    }
  }
}
```
</details>
