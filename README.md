# Culture Icons SVG

![SVG](https://img.shields.io/badge/SVG-Icons-yellow)
![CSS](https://img.shields.io/badge/CSS-Theming-blue)
![License](https://img.shields.io/badge/License-MIT-green)

A curated collection of SVG icons representing Kerala and Indian cultural symbols. Designed for use in web applications, documentation, and design systems that celebrate South Asian heritage.

## Features

- Hand-crafted SVG icons of Kerala and Indian cultural motifs
- Consistent sizing and viewBox standards across all icons
- CSS theme integration with customizable color variables
- Scalable vector format for crisp rendering at any resolution
- Lightweight and optimized for web performance

## Tech Stack

| Technology | Purpose                 |
|------------|-------------------------|
| SVG        | Vector icon format      |
| CSS3       | Theming and coloring    |
| Make       | Build automation        |

## Quick Start

1. Clone the repository:

```bash
git clone https://github.com/razinahmed/culture-icons-svg.git
cd culture-icons-svg
```

2. Include the theme stylesheet:

```html
<link rel="stylesheet" href="styles/theme.css" />
```

3. Use icons directly in your HTML:

```html
<img src="icons/example-icon.svg" alt="Cultural symbol" width="48" height="48" />
```

Or inline for CSS color control:

```html
<svg class="icon" viewBox="0 0 24 24">
  <!-- icon path data -->
</svg>
```

## Theming

The included theme provides base colors that can be applied to SVG icons via CSS:

```css
.icon {
  fill: var(--primary);      /* #00d4aa */
  background: var(--background); /* #1e1e2e */
}
```

## Build

```bash
make build
make test
```

## Project Structure

```
culture-icons-svg/
  styles/
    theme.css       # Color theming
  Makefile          # Build commands
  LICENSE           # MIT License
```

## Contributing

Contributions of new cultural icons are welcome. Please ensure SVGs follow the existing viewBox and style conventions.

## License

This project is licensed under the MIT License. See [LICENSE](LICENSE) for details.
