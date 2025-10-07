# Getting Started with the Purple Theme Extension

This document serves as a quickstart guide for developing and publishing the Purple Theme extension for Visual Studio Code.

## Prerequisites

Before you begin, ensure you have the following installed:

- Node.js (version 12 or later)
- npm (comes with Node.js)
- Visual Studio Code

## Setting Up the Extension

1. **Clone the Repository**: If you haven't already, clone the repository to your local machine.

   ```
   git clone <repository-url>
   cd purple-theme-extension
   ```

2. **Install Dependencies**: Navigate to the extension directory and install the necessary dependencies.

   ```
   npm install
   ```

3. **Open in Visual Studio Code**: Open the project folder in Visual Studio Code.

   ```
   code .
   ```

## Developing the Theme

- The theme colors are defined in the `themes/Purple Theme-color-theme.json` file. You can modify this file to customize the colors used in your theme.

- To see your changes in action, press `F5` to launch a new VS Code window with your extension loaded.

## Publishing the Extension

1. **Update the Version**: Before publishing, make sure to update the version number in `package.json`.

2. **Package the Extension**: Use the following command to package your extension:

   ```
   vsce package
   ```

3. **Publish the Extension**: If you have an account on the Visual Studio Code Marketplace, you can publish your extension using:

   ```
   vsce publish
   ```

## Additional Resources

- [Visual Studio Code API](https://code.visualstudio.com/api)
- [Publishing Extensions](https://code.visualstudio.com/api/working-with-extensions/publishing-extension)

## Troubleshooting

If you encounter any issues, check the following:

- Ensure all dependencies are installed correctly.
- Review the output in the terminal for any error messages.
- Consult the documentation for any specific API usage.

Happy coding!