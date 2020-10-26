# README Practice

Repo working with different README.md conventions

```js
const handleWin = (letter) => {
  gameIsLive = false;
  if (letter === "x") {
    statusDiv.innerHTML = `${letterToSymbol(letter)} has won!`;
  } else {
    statusDiv.innerHTML = `<span>${letterToSymbol(letter)} has won!</span>`;
  }
};
```

## Steps to install on local computer
1. Go to [repo](https://github.com/tcgilbert/README.md-practice) on Github profile and `fork` and `clone` repo


```css
.grid {
    background-color: salmon;
    display: grid;
    grid-template-columns: repeat(3, 1fr);
    grid-template-rows: repeat(3, 1fr);
    gap: 15px;
    margin-top: 50px;
}
```



```html
<div class="grid">
        <div class="box" id="box-1"></div>
        <div class="box" id="box-2"></div>
        <div class="box" id="box-3"></div>
        <div class="box" id="box-4"></div>
        <div class="box" id="box-5"></div>
        <div class="box" id="box-6"></div>
        <div class="box" id="box-7"></div>
        <div class="box" id="box-8"></div>
        <div class="box" id="box-9"></div>
    </div>
```


| Functions | Description |
| ----------- | ----------- |
| Header | Title |
| Paragraph | Text |