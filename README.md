# Cut Before Answer · Promo desk

Live desk: https://harshitag2.github.io/cut-before-answer/

A static build of the promo desk, shown on **The Second Will**, an original 3-episode sample show (no client scripts are published here): 20–60 second promo cuts that open strong and stop before the answer, with editor briefs, test versions and exports for Premiere, Resolve, Final Cut, Google Sheets, Slack and calendars.

- `index.html` – the desk (works offline once loaded; installable as an app)
- `cuts.json` – a slim feed of the posting list for the browser extension and other tools
- `extension.zip` – the Chrome / Edge / Brave extension (unzip, open chrome://extensions, turn on Developer mode, Load unpacked)

Built with `python src/build_site.py`. Adding new scripts needs the local app (`python src/serve.py`).
