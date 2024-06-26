<div align="center">
	<a href="https://kahuak.vercel.app/" target="_blank">
  		<img alt="version" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Flgneves-dev%2Fkahuak%2Fmain%2Fpackage.json&query=%24.version&label=version" />
	</a>
	<a href="https://github.com/lgneves-dev/kahuak/blob/main/LICENSE" target="_blank">
  		<img alt="license" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Flgneves-dev%2Fkahuak%2Fmain%2Fpackage.json&query=%24.license&label=license&labelColor=%235d5d5d&color=green" />
	</a>
	<a href="https://github.com/lgneves-dev" target="_blank">
  		<img alt="author" src="https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fraw.githubusercontent.com%2Flgneves-dev%2Fkahuak%2Fmain%2Fpackage.json&query=%24.author&label=author&labelColor=%235d5d5d&color=%23caa631" />
	</a>
  <br/>
  <br/>
  <a href="https://github.com/lgneves-dev/kahuak">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="docs/images/kahuak-horizontal-logo-800x177-dark.png">
    <source media="(prefers-color-scheme: light)" srcset="docs/images/kahuak-horizontal-logo-800x177-light.png">
    <img alt="Kahuak logo" src="docs/images/kahuak-horizontal-logo-800x177-light.png" width="800" height="177">
  </picture>
  </a>
</div>

## Description

Kahuak is a web UI component library developed in vanilla JavaScript. This library aims to provide a collection of reusable and customizable components to facilitate the development of modern and appealing user interfaces.

## Features

-   **Reusable Components**: Kahuak offers a variety of ready-to-use components, from buttons and cards to progress bars and forms, which you can easily integrate into your project.

-   **Vanilla JavaScript**: The library is written entirely in vanilla JavaScript, meaning there are no external dependencies. This makes it lightweight and easy to integrate into any web project.

-   **Highly Customizable**: Each component is highly customizable to fit the specific needs of your project. You can easily modify styles, colors, and behaviors.

## Screenshots

<div align="center">
<img src="docs/images/screenshot.jpg" alt="Web Components samples" width="590" height="499">
</div>

## Basic Usage

```html
<!DOCTYPE html>
<html lang="en">
	<head>
		<meta charset="UTF-8" />
		<meta name="viewport" content="width=device-width, initial-scale=1.0" />
		<title>Kahuak UI Components</title>
		<!-- Include the library -->
		<script src="kahuak.all.js"></script>
		<!-- Initialize the component -->
		<script>
			let myComponent = new Autocomplete("my-component", {
				dataSource: ["Apple", "Banana", "Orange", "Kiwi", "Peach"],
				value: "Orange",
				placeholder: "Please select a fruit...",
			});
		</script>
	</head>
	<body>
		<!-- Use the components in your project -->
		<div id="my-component" class="kc-autocomplete"></div>
	</body>
</html>
```

## License

Licensed under the [MIT](LICENSE.txt) license.

---

**Note**: This project is under development. It is recommended to regularly check for updates and new features. Thank you for using this web components library!
