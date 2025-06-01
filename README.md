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
```

## Generating new PDFs

Just use latexresu.me or

```
npx resume export resume.pdf --theme short
```