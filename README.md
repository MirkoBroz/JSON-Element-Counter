# JSON Element Counter

A lightweight, single-file web application to quickly analyze JSON data right in your browser.  
Paste JSON, **count elements**, **prettify formatting**, **copy to clipboard**, and see detailed statistics — all offline, no server required.

---

## Features

- **Paste & Count** – Instantly see:
  - Root type (Object / Array / Primitive)
  - Number of top-level elements
  - Total objects, keys, arrays, array items, primitives, and total nodes
- **Prettify JSON** – Reformat JSON with indentation for easier reading
- **Copy to Clipboard** – One click to copy the current (optionally prettified) JSON
- **Insert Example** – Quickly try with a built-in example
- **Error Display** – Clear feedback when JSON is invalid
- **Offline Use** – Works entirely in your browser
- **Self-Test Harness** – Built-in test cases to verify behavior

---

## Installation

No installation needed — just download and open the HTML file.

1. Save [`index.html`](./index.html) locally.
2. Double-click the file to open in your browser.
3. Paste JSON, click **Count**, and view stats.

---

## Deploy Options

You can host this anywhere that serves static files:

- **GitHub Pages** – Free for public repos
- **Netlify** – Drag & drop or Git-connected deploy
- **Vercel** – One-command deploy
- **Cloudflare Pages** – Unlimited free static hosting
- **Surge** – Quick CLI publish

Example (Netlify drag & drop):

1. Go to [Netlify Drop](https://app.netlify.com/drop)
2. Drag your `index.html` file into the page
3. Get your live HTTPS URL instantly

---

## Running Self-Tests

Click the **Run tests** button in the "Self-test" section to verify core logic.

Test cases cover:
- Array root length counting
- Object root with nested structures
- Primitive roots
- Mixed arrays of objects
- Boolean, null, and empty object handling

---

## License

MIT License — feel free to use, modify, and distribute.

---

**Author:** Mirko Broz  
**Demo:** _(Add URL after deployment)_
