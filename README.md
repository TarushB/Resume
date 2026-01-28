# Resume hosted using GitHub Pages (PDF)


This repository hosts my resume using **GitHub Pages**.


The key idea is simple:
➡️ **The resume opens directly as a PDF when the link is visited**  
There is no intermediate HTML page or button.


This is intentional and mirrors how static file hosting works on the web.


---


## Folder structure



resume/
├── index.pdf
└── README.md



---


## How this works (web dev explanation)


When a browser visits this URL:



https://tarushb.github.io/resume/



GitHub Pages checks for files in this order:


1. `index.html`
2. `index.pdf`
3. `index.md`


Since this repository **does not contain `index.html`**, GitHub Pages serves:



index.pdf



Modern browsers automatically render PDF files using their built-in PDF viewer, so the resume opens directly.


No redirects.  
No anchor tags.  
No JavaScript.


---


## Live resume link



https://tarushb.github.io/resume/



Direct access to the file also works:



https://tarushb.github.io/resume/index.pdf



Both links open the same resume.


---


## Why this approach


- Extremely simple and reliable
- Works on desktop, mobile, and ATS systems
- No frontend framework required
- Demonstrates how static hosting actually works


---


## How to update the resume


1. Replace `index.pdf` with the updated resume
2. Commit the change
3. Refresh the link (updates usually appear within seconds)


---


## Notes for learning web development


- GitHub Pages is a **static file server**
- HTML is optional; files can be served directly
- Browsers decide how to render content using MIME types
- PDFs are rendered natively by modern browsers
