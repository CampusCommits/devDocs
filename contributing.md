# ✍️ How to Contribute to DevDocs (Markdown-Only Guide)

Welcome! 👋  
If you're a developer, student, or enthusiast who wants to **contribute documentation** using just **Markdown (`.md`) files**, you're in the right place.

You **do NOT** need to know React, Docusaurus, or any build tools.  
Just follow this step-by-step guide and submit your `.md` file — we’ll handle the rest.

---

## ✅ What You Can Contribute

You can contribute:
- ✏️ Tutorial or guide on a dev topic (Node.js, Docker, Git, etc.)
- 🛠️ Code explanation
- 🧠 Tips and best practices
- ❓ FAQs or how-tos
- 📖 Improvements to existing docs (typo fixes, clearer examples, etc.)

---

## 📁 Folder Structure

All docs are placed in the `docs/` folder and organized by topic:
```
docs/
├── nodejs/
├── docker/
├── git/
├── kubernetes/
└── ...
```

Each folder has a `README.md` as its index.  
You can either **edit existing files** or **create new ones** inside these folders.

---

## ✨ Step-by-Step Markdown Contribution Guide

### 1. **Fork the Repository**

Click the **"Fork"** button at the top-right of the repo page.

### 2. **Clone Your Fork (or use GitHub web editor)**

```bash
git clone https://github.com/your-username/devdocs.git
cd devdocs
```

> Alternatively, you can press `.` on the GitHub page to open the web editor.

---

### 3. **Add or Edit Markdown Files**

- Navigate to the relevant folder under `docs/`
- Either **edit an existing `.md` file** or **create a new file**

#### 📄 Example: `docs/docker/docker-volumes.md`

```markdown
# Docker Volumes

Docker volumes are used to persist data in containers.

## Creating a Volume
\`\`\`bash
docker volume create my-volume
\`\`\`

## Mounting a Volume
\`\`\`bash
docker run -v my-volume:/app/data my-container
\`\`\`
```

---

### 4. **Commit Your Changes**

```bash
git add docs/docker/docker-volumes.md
git commit -m "Added guide for Docker Volumes"
git push origin your-branch-name
```

---

### 5. **Open a Pull Request**

1. Visit your fork on GitHub  
2. Click **"Compare & Pull Request"**  
3. Add a title and description (what the doc is about)  
4. Click **"Create Pull Request"**

✅ You're done!

---

## 🧠 Markdown Style Guidelines

- Use `#` for main title, `##` for sections, `###` for subsections
- Use triple backticks (```) and specify language for code blocks
- Write short, clear paragraphs and break long text into sections
- File names should be in **kebab-case**, e.g., `git-rebase.md`

---

## ❓ Not Sure Where to Place Your File?

Just put it in the `docs/` folder, and we’ll organize it!  
You can leave a note in your pull request like:

> _“Wasn’t sure where this belongs — please help place it in the right section.”_

---

## 🙌 Need Help?

- Open an [Issue](https://github.com/your-org/devdocs/issues)
- Ask in the **Discussions** tab
- Or leave a note in your pull request — we’ll help you out!

---

## 🎉 Thank You!

Your contributions make this open-source project better for everyone.  
Even a single Markdown file can help someone learn something new.

**Let’s build DevDocs together! 🚀**
