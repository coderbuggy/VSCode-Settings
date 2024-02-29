# My VSCode Settings

Here are my vscode settings for Font and Cursor :

Search for **"Cursor"** in VSCode settings and set this for cursor animations:

- **Cursor Style : "line"**
-  **Cursor Blinking : "expand"**

for Font i'm using **"Cascadia Code"** Font Family <a href="https://github.com/microsoft/cascadia-code" target="_blank">Download From Here</a> with 16px Size.

## Settings.json :
{

  

"workbench.colorTheme":  "Github Purple",

  

"workbench.iconTheme":  "vscode-icons",

  

"editor.fontFamily":  "'Cascadia Code', Menlo, Monaco, monospace",

  

"editor.fontSize":  15,

  

"editor.fontLigatures":  "'ss01',",

  

"editor.tokenColorCustomizations":  {

  

"textMateRules":  [

  

{

  

"scope":  [

  

//following will be in italic (=FlottFlott)

  

"comment",

  

"entity.name.type.class",  //class names

  

"keyword",  //import, export, return…

  

"storage.modifier",  //static keyword

  

"storage.type",  //class keyword

  

"support.class.builtin",

  

"keyword.control",

  

"constant.language",

  

"entity.other.attribute-name",

  

"entity.name.method"

  

],

  

"settings":  {

  

"fontStyle":  "italic"

  

}

  

},

  

{

  

"scope":  [

  

//following will be excluded from italics (VSCode has some defaults for italics)

  

"invalid",

  

"keyword.operator",

  

"constant.numeric.css",

  

"keyword.other.unit.px.css",

  

"constant.numeric.decimal.js",

  

"constant.numeric.json"

  

],

  

"settings":  {

  

"fontStyle":  ""

  

}

  

}

  

]

  

},

  

"editor.mouseWheelZoom":  true,

  

"editor.cursorBlinking":  "expand",

  

"vsicons.dontShowNewVersionMessage":  true,

  

"bracket-pair-colorizer-2.depreciation-notice":  false,

  

"[javascript]":  {

  

"editor.defaultFormatter":  "HookyQR.beautify"

  

},

  

"git.enableSmartCommit":  true,

  

"git.confirmSync":  false,

  

"tabnine.experimentalAutoImports":  true,

  

"sap.ux.applicationModeler.disableMigrationPrompt":  true,

"editor.unicodeHighlight.allowedLocales":  {

"tr":  true

},

"editor.unicodeHighlight.includeStrings":  false,

"[javascriptreact]":  {

"editor.defaultFormatter":  "esbenp.prettier-vscode"

},

"terminal.integrated.env.windows":  {},

"console-ninja.featureSet":  "Community",

"reactSnippets.settings.importReactOnTop":  false,

"javascript.updateImportsOnFileMove.enabled":  "always",

"explorer.confirmDragAndDrop":  false,

"explorer.confirmDelete":  false,

"editor.formatOnSave":  true,

"editor.defaultFormatter":  "esbenp.prettier-vscode"

  

}

# Extensions List & Usage

Here are the list on Extensions that i'm using this days (We will update this post if we changed our Extensions) :

1. <a href="https://marketplace.visualstudio.com/items?itemName=HookyQR.beautify" target="_blank">Beautify :</a> Beautify css, sass and less code (extension for Visual Studio Code).

2. <a href="https://marketplace.visualstudio.com/items?itemName=alefragnani.Bookmarks" target="_blank">Bookmarks:</a> Bookmarks for lines.

3. <a href="https://marketplace.visualstudio.com/items?itemName=kamikillerto.vscode-colorize" target="_blank">Colorize:</a> Visualize CSS colors in files.

4. <a href="https://marketplace.visualstudio.com/items?itemName=dsznajder.es7-react-js-snippets" target="_blank">ES7+ React/Redux/React-Native snippets :</a> Extensions for React, React-Native and Redux in JS/TS with ES7+ syntax.

5. <a href="https://marketplace.visualstudio.com/items?itemName=solnurkarim.html-to-css-autocompletion" target="_blank">HTML To CSS Autocompletion :</a> Provides completion suggestions for classes and ids from markup documents to stylesheets.

6. <a href="https://marketplace.visualstudio.com/items?itemName=VisualStudioExptTeam.vscodeintellicode" target="_blank">Intellicode :</a> The Visual Studio IntelliCode extension provides AI-assisted development features for Python, TypeScript/JavaScript and Java developers in Visual Studio Code, with insights based on understanding your code context combined with machine learning.

7. <a href="https://marketplace.visualstudio.com/items?itemName=xabikos.JavaScriptSnippets" target="_blank">JavaScript (ES6) code snippets :</a> Code snippets for JavaScript in ES6 syntax.

8. <a href="https://marketplace.visualstudio.com/items?itemName=esbenp.prettier-vscode" target="_blank">Prettier :</a> Code formatter using prettier

	**.prettier.json :** 
	{

	"tabWidth":  2,

	"semi":  false,

	"singleQuote":  true

	}


9. <a href="https://marketplace.visualstudio.com/items?itemName=dbaeumer.vscode-eslint" target="_blank">ESLint :</a> Integrates ESLint JavaScript into VS Code.

10. <a href="https://github.com/vscode-icons/vscode-icons" target="_blank">VSCode Icons :</a> Icons for Visual Studio Code (files icons).

11. <a href="https://marketplace.visualstudio.com/items?itemName=CoenraadS.bracket-pair-colorizer-2" target="_blank">Bracket Pair Colorizer :</a> A customizable extension for colorizing matching brackets.

12. <a href="https://marketplace.visualstudio.com/items?itemName=WallabyJs.console-ninja" target="_blank">Console Ninja :</a> JavaScript console.log output and runtime errors right next to your code.

13. <a href="https://marketplace.visualstudio.com/items?itemName=pranaygp.vscode-css-peek" target="_blank">CSS Peek :</a> Allow peeking to css ID and class strings as definitions from html files to respective CSS. Allows peek and goto definition.

14. <a href="https://marketplace.visualstudio.com/items?itemName=jasonlhy.hungry-delete" target="_blank">Hungry Delete :</a> To delete an entire block of whitespace or tab, and reduce the time programmers need to press backspace.

15. <a href="https://marketplace.visualstudio.com/items?itemName=styled-components.vscode-styled-components" target="_blank">Styled Components Snippet :</a> Syntax highlighting for styled-components.

## My Live Code Result Extensions

1. <a href="https://github.com/ritwickdey/vscode-live-server" target="_blank">Live Server :</a> Launch a development local Server with live reload feature for static & dynamic pages.

2. <a href="[https://github.com/microsoft/vscode-livepreview](https://github.com/microsoft/vscode-livepreview)" target="_blank">Live Preview :</a> An extension that hosts a local server for you to preview your web projects on! (Updates preview without saving file).

## My Theme Extensions

- <a href="https://marketplace.visualstudio.com/items?itemName=4a454646.github-purple" target="_blank">Github Purple</a>
- <a href="https://marketplace.visualstudio.com/items?itemName=dracula-theme.theme-dracula" target="_blank">Dracula Official</a>

