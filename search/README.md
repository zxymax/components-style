#### Search style

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <style type="text/css"></style>
    <link href="./input.css" rel="stylesheet" />
    <title>search component style</title>
  </head>
  <body>
    <div class="TagsContainer_TagsContainer__1jG7r">
      <div class="TagsContainer_search__3due6">
        <input type="text" value="PVP" class="" /><svg
          aria-hidden="true"
          focusable="false"
          data-prefix="fas"
          data-icon="search"
          class="svg-inline--fa fa-search fa-w-16"
          role="img"
          xmlns="http://www.w3.org/2000/svg"
          viewBox="0 0 512 512"
          alt="search"
        >
          <path
            fill="currentColor"
            d="M505 442.7L405.3 343c-4.5-4.5-10.6-7-17-7H372c27.6-35.3 44-79.7 44-128C416 93.1 322.9 0 208 0S0 93.1 0 208s93.1 208 208 208c48.3 0 92.7-16.4 128-44v16.3c0 6.4 2.5 12.5 7 17l99.7 99.7c9.4 9.4 24.6 9.4 33.9 0l28.3-28.3c9.4-9.4 9.4-24.6.1-34zM208 336c-70.7 0-128-57.2-128-128 0-70.7 57.2-128 128-128 70.7 0 128 57.2 128 128 0 70.7-57.2 128-128 128z"
          ></path>
        </svg>
      </div>
    </div>
  </body>
</html>
```

```css
@font-face {
  font-family: Shentox;
  font-display: swap;
  src: url(https://web.ccpgamescdn.com/aws/webfonts/shentox/webfonts-2.0/Shentox-SemiBold.woff2)
      format('woff2'), url(https://web.ccpgamescdn.com/aws/webfonts/shentox/webfonts-2.0/Shentox-SemiBold.woff)
      format('woff');
  font-weight: 600;
  font-style: normal;
}

/** svg search icon **/
svg:not(:root).svg-inline--fa {
  overflow: visible;
}

.svg-inline--fa {
  display: inline-block;
  font-size: inherit;
  height: 1em;
  overflow: visible;
  vertical-align: -0.125em;
}
.svg-inline--fa.fa-w-16 {
  width: 1em;
}
/* svg end */

:root {
  --font-family: 'Shentox', 'Rogan', sans-serif;
}

body {
  margin: 0;
  padding: 0;
  background-color: #101010;
}
body,
html {
  min-height: 100vh;
  overflow-x: hidden;
  box-sizing: border-box;
  line-height: 1.5;
  color: #fff;
  font-family: Shentox, Rogan, sans-serif;
  font-family: var(--font-family);
  font-weight: 500;
}

input {
  font-family: inherit;
}

input:focus {
  outline: none;
}

form {
  padding: 0;
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
  line-height: inherit;
  border: 0;
}

svg {
  color: silver;
  position: absolute;
  -webkit-transform: translateY(-50%);
  transform: translateY(-50%);
}

button:focus {
  outline: none;
}

*,
:after,
:before {
  box-sizing: inherit;
}

.TagsContainer_TagsContainer__1jG7r {
  display: flex;
  padding: 0 20px;
  background-color: rgba(33, 33, 33, 0.8);
  width: 100%;
  align-items: center;
  min-height: 60px;
}

.TagsContainer_search__3due6 {
  position: relative;
}

@media only screen and (min-width: 1200px) {
  .TagsContainer_search__3due6 {
    min-width: 260px;
  }
}

.TagsContainer_search__3due6 form,
.TagsContainer_search__3due6 input {
  width: 100%;
}

.TagsContainer_search__3due6 input {
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
  line-height: inherit;
  background: transparent;
  -webkit-appearance: none;
  appearance: none;
  color: #fff;
  background: #29353a;
  border-radius: 24px;
  padding: 5px 35px 5px 15px;
  border: 1px solid transparent;
  font-size: 15px;
  transition: background 0.3s ease;
}

.TagsContainer_search__3due6 input:focus {
  background: #353e42;
}

.TagsContainer_search__3due6 svg {
  right: 20px;
  top: 50%;
}

.TagsContainer_search__3due6 button {
  padding: 0;
  margin: 0;
  font-family: inherit;
  font-size: inherit;
  font-weight: inherit;
  line-height: inherit;
  border: 0;
  background: transparent;
  -webkit-appearance: none;
  appearance: none;
}

.TagsContainer_search__3due6 button:hover {
  cursor: pointer;
}

.TagsContainer_search__3due6 button:hover svg {
  color: #fff;
}

@media only screen and (max-width: 468px) {
  .TagsContainer_TagsContainer__1jG7r {
    flex-direction: column-reverse;
    padding: 10px;
    margin-bottom: 0;
  }

  .TagsContainer_search__3due6 {
    width: 100%;
  }
}
```
