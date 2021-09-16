# Alberto Priore - résumé

This is my personal résumé,
it can be displayed as a webpage opening `index.html`
or by opening the pdf `index.pdf` generated as explained below.

# Usage

Just edit the `index.html` and follow the simple design principles I designed in the css file.

Install puppeteer-cli:

```
npm install -g puppeteer-cli
```

Make the pdf:

```
puppeteer print --wait-until=networkidle0 index.html index.pdf
```

# Hire me

Drop me a line at me@albertopriore.com