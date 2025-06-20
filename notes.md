
# Internals

https://code.visualstudio.com/api/extension-guides/color-theme#create-a-new-color-theme

```bash
# Generate empty project
npm install yo generator-code
npx yo code

# Package the theme
npx vsce package

# Install the theme
code --install-extension your-theme-name.vsix
```
