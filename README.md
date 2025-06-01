https://lindseyb.github.io/resume/

* https://jsonresume.org/
* https://latexresu.me

👩‍💻


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