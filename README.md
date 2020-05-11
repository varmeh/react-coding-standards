# React App Code Standardization

The intent of this folder is to standardize code across team members in a react based project.

It provides consitency in following:

-   code styling
-   linting
-   testing

Vscode extensions and lint libraries are used to enforce standards.

Extensions Required:

-   [ESLint](https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint)
-   [Prettier](https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode)
-   [Import Cost](https://marketplace.visualstudio.com/items?itemName=wix.vscode-import-cost)

VSCode settings files configured to enforce these extensions across team.

Add these files to your react project to code styling & linting benefits.

## Configuration Files

-   `.prettierrc.json` - prettier extension configuration
-   `.eslintrc.json` - eslint extension configuration
-   `jest.config.js` - jest configuration
-   `.babelrc` - babel configuration
-   `.vscode`
    -   `extension.json` - recommends user to download usefult extensions
    -   `settings.json` - vscode file to enforce prettier as default formatter
