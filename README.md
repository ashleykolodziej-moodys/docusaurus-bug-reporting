## Steps to reproduce

1. Create a clean install of Docusaurus using `npx create-docusaurus@3.0.0-alpha.0 my-website classic
`
1. cd to `my-website`
1. `npm install --save @docusaurus/theme-live-codeblock@3.0.0-alpha.0`
1. Add `themes: ['@docusaurus/theme-live-codeblock'],` to `docusaurus.config.js`
1. Add a `test-codeblock.md` file to the docs folder
1. Add the example code from https://docusaurus.io/docs/3.0.0-alpha.0/markdown-features/code-blocks#interactive-code-editor to the file
1. Run `npm start`
1. Expected: A live clock should show below the code snippet on http://localhost:3000/docs/test-codeblock
1. Actual: The live code block does not render on http://localhost:3000/docs/test-codeblock