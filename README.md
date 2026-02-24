# Theme Assets – Store-Specific CSS Overrides

---

## 📌 Purpose
This repository is designed to manage **store-specific CSS overrides** for individual stores using the theme.  
Its main goals are:

- To provide **quick fixes** for layout or styling issues without modifying the main theme.
- To serve as a **temporary solution framework**, preserving store functionality while ensuring stability.
- To maintain **documentation and traceability** of all store-specific customizations.

> ⚠️ Note: These files are **temporary**. Any changes here are intended only to address urgent problems and will be migrated to the main stylesheet when possible.

---

## 🛠 Workflow

### 1️⃣ Permission Requirement
Before making any CSS changes for a store:  

- The **store owner** must enable the CSS customization option in their theme settings.  
- This **grants explicit permission** to our Custom Support Team to manage temporary CSS overrides safely.  

> Without this permission, no CSS files will be created or modified.

---

### 2️⃣ File Creation Process
Once permission is granted:  

1. A **unique CSS file** is generated for the store.
2. File naming convention:
**Example:**
- Store ID: `822893302` → `store-822893302.css`
- Store ID: `123456789` → `store-123456789.css`

3. This file is **added to the repository** and will be used exclusively for that store.  

> Each store has a dedicated file to avoid conflicts and maintain isolation of fixes.

---

### 3️⃣ Adding and Managing CSS Overrides
- The **Custom Support Team** has **write access** to the repository.  
- They are responsible for adding temporary CSS rules for individual stores to fix layout, styling, or other urgent issues.  
- All changes **must be documented** inside each CSS file using comments that clearly explain:

  - The **purpose of the rule**
  - The **affected elements or sections**
  - The **date and version** of the change

Example snippet inside a store file:

```css
/*
==================================================
Store ID: 822893302
Purpose: Temporary fix for header layout issue
Date: 2026-02-21
==================================================
*/

.header {
    background-color: red !important;
}
