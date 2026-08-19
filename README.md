# Univers du Café

A complete, responsive front-end café website built as a portfolio-ready static project. It uses only HTML, CSS and JavaScript, with local image files and no external runtime dependencies.

## Open and run

1. Open the `univers-du-cafe` folder in Visual Studio Code.
2. Open `index.html` in a browser, or use VS Code's **Live Server** extension for automatic refresh.
3. No install, build, API key, or payment setup is required.

## Structure

```text
univers-du-cafe/
├── index.html              # home page
├── css/style.css           # all design and responsive rules
├── js/script.js            # cart, filters, validation, gallery and menus
├── pages/                  # menu, about, contact and product pages
└── assets/images/          # offline local photographs, grouped by use
```

## Customize

- **Brand and content:** Search for `Univers du Café` and replace text directly in the HTML files.
- **Colors:** Edit the CSS variables at the beginning of `css/style.css`.
- **Menu/prices:** Edit each `menu-card` or `product-card` HTML block. Keep the matching `data-price` on an Add button in sync.
- **Images:** Replace a file in `assets/images/` with your own image using the same filename, or update the image `src` in HTML. Keep images in this folder so the project stays offline-ready.
- **Contact/social links:** Update the clearly marked placeholder values in `pages/contact.html` and footer markup in `js/script.js`.

## Features

- Responsive mobile navigation
- Category-filtered menu
- Product detail example with quantity and size options
- Persistent localStorage shopping bag
- Gallery lightbox
- Front-end contact-form validation
- Scroll reveal effects and back-to-top control, respecting reduced-motion preferences

## Deploy on GitHub Pages

1. Create a GitHub repository and upload this complete folder.
2. In the repository, open **Settings → Pages**.
3. Choose **Deploy from a branch**, select `main` and `/ (root)`, then save.
4. GitHub will provide the public website link.

The included photos were downloaded into the project during creation. Review and replace them with assets you are licensed to use before commercial publication.
