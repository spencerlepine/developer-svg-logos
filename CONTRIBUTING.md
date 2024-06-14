# Contributing

Contributions, corrections & requests are welcome!

Thank you for considering contributing to our project! Here are the guidelines for adding new logos to our repository.

## How to Contribute

1. **Add the logo file**:
    - Place your logo file in the `logos` folder.
    - The file should be in SVG format and named appropriately (e.g., `logo-name.svg`).
    - Make sure to add `width="56px"` and `height="56px"` attributes to the SVG file.

2. **Update `logos.json`**:
    - Add an entry for your logo in the `logos.json` file.
    - Follow the existing structure to ensure consistency. Here is an example of an entry:
      ```json
      [
        "amazon-web-services",
        "logo-name" // new
      ]
      ```

3. **Update the README file**:
    - Add a line to the README table to include your new logo. Follow this format:
      ```diff
       | Title | Image |
       | ------------- | ------------- |
     + | logo-name | ![Logo](./logos/logo-name.svg) |
      ```

## Submission Guidelines

1. **Fork the repository** and create your branch from `main`.
2. **Commit your changes**:
    - Ensure that the new logo file, the updated `logos.json` file, and the updated README file are included in your commit.
3. **Create a pull request**:
    - Provide a clear title and description for your pull request.
    - Make sure to explain why the logo is being added and any other relevant information.

## Additional Notes

- Ensure your SVG file is optimized for web use.
- Verify that your logo follows any relevant branding guidelines.

Thank you for your contribution!

---

If you have any questions, feel free to reach out by opening an issue in the repository.

Happy contributing!
