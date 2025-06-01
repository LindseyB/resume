https://lindseyb.github.io/resume/

* https://jsonresume.org/
* https://latexresu.me

👩‍💻

The version that is hosted on json resume can be found over there: https://registry.jsonresume.org/LindseyB


## Generating new index.html file

```
npm install jsonresume-theme-flat
npx resume export index.html --theme flat
```

add the following to the HTML

```html
<link rel="stylesheet" href="resume.css">
<link rel="manifest" href="/resume/site.webmanifest" />
<link rel="preconnect" href="https://fonts.googleapis.com">
<link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
<link href="https://fonts.googleapis.com/css2?family=Fira+Mono:wght@400;500;700&display=swap" rel="stylesheet">
<link
  href="https://fonts.googleapis.com/css2?family=Fira+Mono:wght@400;500;700&family=Playfair+Display:ital,wght@0,400..900;1,400..900&display=swap"
  rel="stylesheet">
<link rel="icon" href="/resume/favicon.ico" type="image/x-icon">
```

## Generating new PDFs

Just use latexresu.me or

```
npx resume export resume.pdf --theme short
```

Currently the PDF export is not working well with the professional theme on my laptop likely due to some weirdness around the npm build versions on it, so I use the jsonresume registry and set the theme to `professional` and then print as a PDF from there and it works and I reset the them to `flat` after the fact since I feel like that generally looks better.