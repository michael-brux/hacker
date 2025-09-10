---
layout: default
---
# 📄 Understanding `index.md` in Jekyll

In **Jekyll**, `index.md` is the Markdown-based equivalent of an `index.html` file.  
It serves as the **default entry point** for a directory or the entire site.

---

## 🔹 Purpose

- **Root-level homepage**  
  If placed in the root folder (`/index.md`), it becomes the homepage of your site (`/`).
- **Section landing page**  
  If placed inside a subfolder (e.g., `/blog/index.md`), it becomes the landing page for that section (`/blog/`).
- **Clean URLs**  
  Jekyll converts `index.md` → `index.html`, allowing URLs without the filename (e.g., `/about/` instead of `/about.html`).

---

## ⚙️ How It Works

1. **YAML Front Matter**  
   Every `index.md` must start with a front matter block so Jekyll processes it:

---
layout: default
title: "index.md"
---



```
Long, single-line code blocks should not wrap. They should horizontally scroll if they are too long. This line should be long enough to demonstrate this.
```

```
The final element.
```
