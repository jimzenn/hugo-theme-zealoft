# Contributing to Zealoft

Thank you for your interest in contributing to our project! We welcome all contributions, but we ask that you please follow these guidelines to ensure a smooth and collaborative process.

## How to Contribute

We welcome contributions of all kinds, from bug fixes to new features. To get started, please follow these steps:

### Development Workflow

1.  **Set up your environment:**
    *   Fork the repository.
    *   Clone your fork locally: `git clone https://github.com/your-username/hugo-theme-zealoft.git`
    *   Make sure you have Hugo installed. If not, see the [Hugo installation guide](https://gohugo.io/getting-started/installing/).
    *   Navigate into the theme's `exampleSite` directory: `cd hugo-theme-zealoft/exampleSite`
    *   The theme is set up as a Hugo module in the example site. To use your local version for development, you need to tell the module system to use the local directory instead of the one from the internet. Run the following command from the `exampleSite` directory:
        ```bash
        hugo mod vendor
        ```
    *   You can now run the development server: `hugo server`. Changes you make in the theme's root directory will now be reflected in the example site.

2.  **Making Changes:**
    *   Create a new branch for your changes: `git checkout -b my-awesome-feature`
    *   Most of the theme's code is in the following directories:
        *   `assets/css`: The theme's stylesheets.
        *   `layouts`: The theme's templates.
        *   `archetypes`: The theme's content archetypes.
    *   Make your changes, and test them by running the Hugo server in the `exampleSite` directory.

3.  **Submitting a Pull Request:**
    *   Once you're happy with your changes, commit them with a clear and descriptive commit message.
    *   Push your branch to your fork: `git push origin my-awesome-feature`
    *   Open a pull request from your fork to the main repository.

### Types of Contributions

*   **Bug fixes:** If you find a bug, please open an issue first to discuss it. Then, you can submit a pull request with the fix.
*   **New features:** If you have an idea for a new feature, please open an issue to discuss it before you start working on it. This will help to ensure that the feature is a good fit for the theme.
*   **Documentation:** We welcome improvements to the documentation. If you find something that is unclear or could be improved, please submit a pull request.

## Naming Conventions

We follow the BEM (Block, Element, Modifier) naming convention for our CSS classes. This helps to keep our stylesheets organized and maintainable.

### BEM Basics

- **Block:** A standalone component that is meaningful on its own (e.g., `header`, `menu`).
- **Element:** A part of a block that has no standalone meaning (e.g., `menu__item`, `header__title`).
- **Modifier:** A flag on a block or element that changes its appearance or behavior (e.g., `menu--fixed`, `menu__item--active`).

### Example

```css
/* Block */
.menu {
  /* ... */
}

/* Element */
.menu__item {
  /* ... */
}

/* Modifier */
.menu__item--active {
  /* ... */
}
```

Please follow this naming convention for all new CSS classes.

## Other Conventions

- **Commit messages:** Please write clear and concise commit messages.
- **Code style:** Follow the existing code style and formatting.
- **Testing:** If you are adding a new feature, please also add a corresponding test.

Thank you for your contributions!
