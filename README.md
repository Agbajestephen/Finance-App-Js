# Finance App (Frontend)

A client-side finance dashboard built with plain HTML, CSS and JavaScript. It provides pages for accounts, cards, dashboard, investments, loans, transfers, settings, login and signup. The project is a static frontend suitable for demos and UI development.

## Features

- Multiple pages: accounts, cards, dashboard, investments, loans, transfers, settings
- Client-side UI with separate HTML/CSS/JS per screen
- Lightweight and framework-free for easy modification

## Technology

- HTML, CSS, JavaScript
- Uses LocalStorage or mock/static data for demo purposes (no backend required)

## Quick Start

Open the app in your browser by opening `index.html`, or run a simple local HTTP server from the project root:

```bash
# Python 3
python -m http.server 8000
# then open http://localhost:8000 in your browser

# Or using Node (if you have 'serve')
npx serve .
```

## File overview

- HTML pages:
  - [index.html](index.html) — Landing / main entry
  - [dashboard.html](dashboard.html) — Main dashboard
  - [accounts.html](accounts.html)
  - [cards.html](cards.html)
  - [investments.html](investments.html)
  - [loans.html](loans.html)
  - [transfers.html](transfers.html)
  - [settings.html](settings.html)
  - [login.html](login.html)
  - [signup.html](signup.html)

- JavaScript:
  - [app.js](app.js)
  - [script.js](script.js)
  - [dashboard.js](dashboard.js)
  - [accounts.js](accounts.js)
  - [cards.js](cards.js)
  - [investments.js](investments.js)
  - [loans.js](loans.js)
  - [transfers.js](transfers.js)
  - [settings.js](settings.js)
  - [auth.js](auth.js)

- CSS:
  - [style.css](style.css)
  - [styles.css](styles.css)
  - [dashboard.css](dashboard.css)
  - [auth.css](auth.css)

- Assets:
  - `img/` — image assets used by the UI

## Usage

- Navigate between pages by opening the HTML files or using the UI links.
- For development, run a local server so static imports and any fetch/XHR requests behave correctly.

## Contributing

- Open an issue or submit a pull request. Keep changes focused and include screenshots for UI changes.

## License

No license specified. Add a `LICENSE` file if you plan to publish or share this project publicly.
