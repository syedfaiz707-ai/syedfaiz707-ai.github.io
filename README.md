# Syed Faiz — Portfolio

Live site: **https://syedfaiz707-ai.github.io**

Hosted free on GitHub Pages. Every change saved to this repository goes live in about a minute.

## Files

| File | What it is |
|---|---|
| `index.html` | The portfolio home page |
| `resume.html` | The resume as a web page (also the source of the PDF) |
| `Syed-Faiz-Resume.pdf` | Public resume PDF, downloadable from the site (no phone number or date of birth) |

## How to update (from any browser, no software needed)

1. Sign in to GitHub as **syedfaiz707-ai** and open this repository.
2. Click the file you want to change (`index.html` or `resume.html`), then click the **pencil icon**.
3. Edit the text and click **Commit changes**.

Tips:
- **New job:** in `index.html`, copy one `<li class="role-item">` block in the Experience section and paste it at the top. In `resume.html`, copy one `<article class="job">` block.
- **New project or AI skill:** copy one `<article class="card">` block.
- **Never** put your phone number or date of birth in these files. This repository is public.

## Updating the resume PDF

The PDFs are printed from `resume.html` by `make-pdfs.mjs`, which lives in the parent folder on Syed's computer (`OneDrive\Syed Faiz Career`) and not in this repository:

```
node make-pdfs.mjs
```

That script writes two PDFs: the public one in this folder, and a full one with phone and date of birth for sending to employers, which stays on the computer.

Without that script, open `resume.html` in Chrome, click **Save as PDF**, and upload the result here as `Syed-Faiz-Resume.pdf`.
