# Modern Local & Web Search Plugin

A sleek, modern, and fully client-side **search plugin** that lets users search both your local portfolio data and the web seamlessly.

---

## Features

- **Local Search** powered by [Lunr.js](https://lunrjs.com) for lightning-fast client-side indexing and querying.
- **Web Search** using DuckDuckGo's Instant Answer API to fetch live web results without any backend or API keys.
- Clean, minimalistic, and responsive UI with smooth animations and effects.
- Instant highlighting of matched terms in results.
- Easy to embed and customize within any HTML project.
- Accessible and keyboard-friendly search input with button controls.

---

## Demo

Try it live by copying the code into any modern browser. No server or backend needed.

---

## Installation

Simply copy the entire HTML and script block into your project. The plugin relies on:

- [Lunr.js](https://unpkg.com/lunr/lunr.js) (loaded via CDN)
- DuckDuckGo’s public API (no key required)

No build steps or dependencies necessary.

---

## Usage

1. Place the container markup wherever you want the search UI to appear.
2. Add your local documents in the `docs` array within the script, each with:

```js
{
  id: 'unique-id',
  title: 'Document Title',
  body: 'Full text content for search indexing',
  url: 'Link to detailed page or resource'
}
# search
