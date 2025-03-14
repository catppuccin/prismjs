<h3 align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/logos/exports/1544x1544_circle.png" width="100" alt="Logo"/><br/>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
	Catppuccin for <a href="https://prismjs.com">Prism.js</a>
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/misc/transparent.png" height="30" width="0px"/>
</h3>

<p align="center">
	<a href="https://github.com/catppuccin/prismjs/stargazers"><img src="https://img.shields.io/github/stars/catppuccin/prismjs?colorA=363a4f&colorB=b7bdf8&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/prismjs/issues"><img src="https://img.shields.io/github/issues/catppuccin/prismjs?colorA=363a4f&colorB=f5a97f&style=for-the-badge"></a>
	<a href="https://github.com/catppuccin/prismjs/contributors"><img src="https://img.shields.io/github/contributors/catppuccin/prismjs?colorA=363a4f&colorB=a6da95&style=for-the-badge"></a>
</p>

<p align="center">
	<img src="assets/preview.webp"/>
</p>

## Previews

<details>
<summary>🌻 Latte</summary>
<img src="assets/latte.webp"/>
</details>
<details>
<summary>🪴 Frappé</summary>
<img src="assets/frappe.webp"/>
</details>
<details>
<summary>🌺 Macchiato</summary>
<img src="assets/macchiato.webp"/>
</details>
<details>
<summary>🌿 Mocha</summary>
<img src="assets/mocha.webp"/>
</details>

## Usage

> [!NOTE]
> The theme does not contain styling for the layout/padding of the highlighted code.

### Remote stylesheet

Include the theme/stylesheet (`https://prismjs.catppuccin.com/<flavor>.css`) in your page. For example:

```html
<!DOCTYPE html>
<html>
  <head>
    ...
    <link href="https://prismjs.catppuccin.com/mocha.css" rel="stylesheet" />
  </head>
  <body>
    ...
    <script src="prism.js"></script>
  </body>
</html>
```

### Local CSS
```bash
# due to prismjs & this repository having the same name, an alias is used 
yarn add catppuccin-prismjs@https://github.com/catppuccin/prismjs.git
```

#### SCSS
```scss
@import "catppuccin-prismjs/themes/macchiato";

// Apply the theme only to selector
main {
    @import "catppuccin-prismjs/themes/latte";
}
```
> Depending on your scss config, you might have to use "node_modules/catppuccin-prismjs/themes/macchiato";


## 💝 Thanks to

- [uncenter](https://github.com/uncenter)

&nbsp;

<p align="center">
	<img src="https://raw.githubusercontent.com/catppuccin/catppuccin/main/assets/footers/gray0_ctp_on_line.svg?sanitize=true" />
</p>

<p align="center">
	Copyright &copy; 2021-present <a href="https://github.com/catppuccin" target="_blank">Catppuccin Org</a>
</p>

<p align="center">
	<a href="https://github.com/catppuccin/catppuccin/blob/main/LICENSE"><img src="https://img.shields.io/static/v1.svg?style=for-the-badge&label=License&message=MIT&logoColor=d9e0ee&colorA=363a4f&colorB=b7bdf8"/></a>
</p>
