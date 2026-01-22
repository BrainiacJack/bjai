# Site Structure & Design System

## 1. Design System
**Theme Mode:** [Light | Dark]

**Color Palette (CSS Variables):**
- `--background`: [Hex/Color Name]
- `--foreground`: [Hex/Color Name]
- `--primary`: [Hex/Color Name]
- `--secondary`: [Hex/Color Name]
- `--accent`: [Hex/Color Name]

**Typography:**
- **Base Font:** [Font Name] (Sans-serif)
- **Heading Font:** [Font Name] (Serif/Display)

---

## 2. Site Configuration
- **Site Name:** [Name]
- **Base URL:** [URL]
- **Navigation Links:** [List of top-level links]

---

## 3. Page Structure

### / (Home)
- **Title:** [Page Title]
- **Description:** [SEO Description]
- **Components:**
  - [Component Name]: [Brief description of purpose]
  - [Component Name]: [Brief description of purpose]
- **Data Source:** `data/home.json`

### /[route]
- **Title:** [Page Title]
- **Description:** [SEO Description]
- **Components:**
  - [Component Name]
- **Data Source:** `data/[route].json`

*(Repeat for all pages)*

---

## 4. Data Architecture
The following JSON files will be created in `data/`:
- `site-config.json`: Global metadata and navigation.
- [List of other JSON files mapped to pages above]
