# tailwind-normalize

tailwind-normalize is a customized normalize file derived from Tailwind CSS, intended for use in non-Tailwind projects. It provides a clean slate for your projects while incorporating the normalization aspects of Tailwind CSS.

## Usage

To use tailwind-normalize in your project, you have a few options:

1. Install using package manager:

   - Install tailwind-normalize as a dependency in your project:
      ```shell
      pnpm add -D tailwind-normalize
      ```
    - Open your `main.ts` file or the root file where you initialize your app.

    - Import the `normalize.css` file from the `tailwind-normalize` package:
      ```typescript
      import 'tailwind-normalize/normalize.css'
      ```

2. Download the File:
   - Download the [preflight.css](https://github.com/tongrow/tailwind-normalize/raw/master/packages/tailwindcss/preflight.css) file.
   - Place the downloaded file in your project's CSS directory.
   - Link to it in your HTML file:
      ```html
      <link rel="stylesheet" href="path/to/preflight.css">
      ```

## License

tailwind-normalize is released under the [MIT License](LICENSE). Feel free to use and modify it in your projects.

## Contributing

Contributions are welcome! If you have any improvements, bug fixes, or suggestions, please open an issue or submit a pull request.

---

We hope you find tailwind-normalize useful for incorporating the normalization features of Tailwind CSS into your non-Tailwind projects. Enjoy the simplicity and consistency it brings to your styling!

[![License](https://img.shields.io/badge/license-MIT-blue.svg)](LICENSE)