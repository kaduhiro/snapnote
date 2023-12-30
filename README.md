# SnapNote

Experience the ultimate simplicity with the most user-friendly Editor.

## Installation

1. Copy the code of your favorite note

### Plane

```html:plane.html
data:text/html;charset=utf-8,<html contenteditable><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text x='50%' y='50%' style='dominant-baseline:central;text-anchor:middle;font-size:90px;'>📝</text></svg>"><title>SnapNote.html</title><style>body {background: rgba(0, 0, 0, 0.9);color: white;font-family: monospace;}</style><script>onbeforeunload = () =>true;</script></head></html></html>
```

## Markdown

```html:markdown.html
data:text/html;charset=utf-8,<html><head><meta http-equiv="Content-Type" content="text/html; charset=utf-8" /><title>SnapNote.md</title><link rel="icon" href="data:image/svg+xml,<svg xmlns='http://www.w3.org/2000/svg' viewBox='0 0 100 100'><text x='50%' y='50%' style='dominant-baseline:central;text-anchor:middle;font-size:90px;'>📔</text></svg>"><link rel="stylesheet" href="https://unpkg.com/mvp.css"><style>body {background: rgba(0 0 0 / 0.9);font-family: monospace;}code {color: whitesmoke;}body >main {display: flex;margin: 0;min-height: 100dvh;max-width: none;padding: 0;width: 100dvw;}body >main >* {color: white;flex: 1 1 0%;}body >main >textarea {background: transparent;border: 2px solid silver;margin: 0;max-width: none;padding: 20px;resize: none;}body >main >output {border: 2px solid gray;padding: 0 20px}</style><script src="https://cdn.jsdelivr.net/npm/marked/marked.min.js"></script></head><body><main><textarea></textarea><output></output></main><script>onbeforeunload = () =>true;document.querySelector('textarea').addEventListener('keyup', (event) =>{document.querySelector('output').innerHTML = marked.parse(event.target.value);});</script></body></html></html>
```

2. Paste into URL bar of your browser
3. Bookmark it! (empty title to display only icon)

## Requirement

- Markdown
  - [markedjs/marked](https://github.com/markedjs/marked)
  - [andybrewer/mvp](https://github.com/andybrewer/mvp)

## Author

[Twitter](https://twitter.com/kaduhiro_)

## License

[MIT](https://en.wikipedia.org/wiki/MIT_License)
