# Amazon Clone v1

A static front-end clone of the Amazon home page built with plain HTML and CSS.

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Customization](#customization)
- [Known Limitations](#known-limitations)

## Overview
This repository contains a single-page UI mockup that recreates the visual layout of Amazon-style navigation, header menus, and product sections.

## Features
- Sticky top navigation bar with logo, location, search bar, language selector, account links, and cart
- Category header menu
- Hero banner area
- Product section cards with images and labels
- Styling implemented with a CSS reset and custom layout rules

## Project Structure
```text
amazon-clone-v1/
├── index.html
├── app.css
└── pictures/
    ├── nav/
    └── products/
```

## Getting Started
No build step or dependencies are required.

1. Clone the repository.
2. Open `index.html` directly in your browser.

Optional (recommended for local serving):
```bash
python3 -m http.server 8000
```
Then open `http://localhost:8000`.

## Customization
- Update layout and styles in `app.css`.
- Modify content structure in `index.html`.
- Replace image assets inside `pictures/nav` and `pictures/products`.

## Known Limitations
- Static only (no JavaScript functionality or backend integration)
- Not fully responsive for all screen sizes
- Content is sample/demo content
