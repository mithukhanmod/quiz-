QuizCreator Studio — Development README

Files added:
- index.html — The complete static app.

How to run locally:
- Option A: Open in browser
  - Open `index.html` directly in your browser (double-click or File → Open).

- Option B: Run a simple local HTTP server (recommended for full features such as font/CORS loading)
  - Python 3:

    python3 -m http.server 8000

    Then visit http://localhost:8000 in your browser.

  - Node.js (if installed):

    npx http-server -c-1

Notes:
- The app is static and uses CDN-hosted Tailwind, Font Awesome, Google Fonts and html2canvas.
- To export an image, customize the card and press the "Export Image" button.
