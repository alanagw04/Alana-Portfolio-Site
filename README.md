# Portfolio & "Secure but Simple" Web Prototype

A two-part static website comprising:
1. **Personal Portfolio Site** (`index.html`): A professional homepage showcasing academic background, interests in cyberlaw, security, accessibility, and current project portfolios.
2. **"Secure but Simple" Prototype** (`projects/secure-but-simple.html`): An interactive, highly accessible web application helping older adults, people with disabilities, and caregivers navigate security decisions.

---

## File Structure

```text
/index.html                        → Portfolio homepage
/projects/secure-but-simple.html   → The app prototype
/README.md                         → This setup and documentation file
```

---

## Visual Design System

The visual design system is shared across both pages to present a unified brand identity:
*   **Background**: Warm ivory/khaki paper (`#E3DEC7` base, `#EEEADA` card surfaces).
*   **Text**: Dark ink (`#1B231D` primary, muted olive-gray secondary).
*   **Accents**: Emerald Green (`#2F6B4F`) as primary, Muted Gold (`#8A6A2E`) as secondary.
*   **Typography**: Source Serif 4 (headings) and Inter (body/UI elements).
*   **Shapes**: Sharp corners (`border-radius: 0px`) for a serious, formal/academic aesthetic.
*   **Texture**: Subtle ruled-paper horizontal grid line background.

---

## Deployment & Running Locally

1.  **Running Locally**: Double-click `index.html` to open it directly in a web browser, or serve it using any simple local HTTP server (e.g., `python -m http.server` or VS Code's Live Server extension).
2.  **GitHub Pages Deployment**:
    *   Push this project root directory to a GitHub repository.
    *   Navigate to repository **Settings** → **Pages**.
    *   Under **Build and deployment**, set Source to **Deploy from a branch**.
    *   Choose the branch (e.g. `main`) and folder (`/` root), and save.
