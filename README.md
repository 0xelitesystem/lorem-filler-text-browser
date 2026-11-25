# Lorem Filler Text Browser

Generate lorem ipsum placeholder text in your browser. No server, no tracking, no third-party scripts.

**Live demo:** https://0xelitesystem.github.io/lorem-filler-text-browser/

## Use

Open `index.html` in any modern browser, or visit the GitHub Pages link in the repo description.

1. Set an amount.
2. Choose a unit: paragraphs, sentences, or words.
3. Toggle "Start with Lorem ipsum..." on or off.

The output updates live as you change the options. Click Copy text to put it on your clipboard. A word and character count sits under the output.

## Why this exists

Most lorem ipsum sites are covered in ads and load third-party scripts to generate a few sentences of Latin. This is a single file that does the same thing offline, with a live preview and a copy button.

## Privacy

Everything runs in your browser. The generated text never leaves your machine. There are no network requests, no analytics, and no external scripts. Verify by viewing the page source or watching the network tab in DevTools.

## Run locally

```bash
git clone https://github.com/0xelitesystem/lorem-filler-text-browser
cd lorem-filler-text-browser
# Open index.html in your browser, or:
python -m http.server 8000
```

## Build

There is no build. It is a single HTML file.

## More

Part of a catalog of single-file browser tools and plain-language references, all MIT licensed and dependency-free: [0xelitesystem.github.io](https://0xelitesystem.github.io/). Built by [elitesystem.ai](https://elitesystem.ai).

## License

MIT.

## Related

- [browser-fake-test-data](https://github.com/0xelitesystem/browser-fake-test-data)
- [htaccess-rewrite-rule-builder](https://github.com/0xelitesystem/htaccess-rewrite-rule-builder)
- [jwt-verify-in-browser](https://github.com/0xelitesystem/jwt-verify-in-browser)
