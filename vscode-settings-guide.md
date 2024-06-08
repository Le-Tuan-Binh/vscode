## Getting Started

This guide provides recommendations for configuring and optimizing Visual Studio Code ([VS Code](https://code.visualstudio.com/)) to enhance your coding experience. Each setting can be adjusted to suit your preferences and workflow, making VS Code a powerful and efficient tool for development. These settings are part of the Evondev custom configuration for Visual Studio Code, which includes additional features like tab customization and more.

## Get involved

**Smooth Caret Animation**

`The smooth caret animation setting` in Visual Studio Code controls the visual smoothness of the cursor movement within the editor. Enabling smooth caret animation makes the cursor transition between positions more fluid, resulting in a more visually appealing and less straining experience.

    Setting -> Editor: Cursor Smooth Caret Animation -> On

**Show Abbreviation Suggestions**

`The Emmet: Show Abbreviation Suggestions` setting in Visual Studio Code is a powerful feature that enhances your coding efficiency by providing real-time abbreviation suggestions. Emmet, a toolkit for web developers, significantly speeds up the process of writing HTML, XML, and CSS by allowing you to type short, concise abbreviations that expand into full-fledged code snippets.

    Setting -> Emmet: Show Abbreviation Suggestions -> Tick

**Emmet: Include Languages**

The Emmet: Include Languages setting in Visual Studio Code is a crucial customization that allows you to specify the list of languages where Emmet abbreviations are enabled.

```js
Setting -> Emmet: Include Languages -> Add a JSON

"emmet.includeLanguages": {
	"javascript": "javascriptreact",
	"vue-html": "html",
	"smarty": "html",
	"typescript": "typescriptreact"
},
```

**Emmet: Trigger Expansion On Tab**

`Enabling the Emmet`: Trigger Expansion On Tab setting in Visual Studio Code is a powerful way to enhance your coding efficiency and streamline your workflow. By allowing the tab key to trigger Emmet abbreviation expansions, you can write code faster, reduce errors, and maintain a consistent and intuitive coding process. Customize this setting to fit your specific needs and enjoy a more productive and enjoyable development experience.

    Setting -> Emmet: Trigger Expansion On Tab -> Tick

**Editor: Cursor Style**

The Editor: `Cursor Style setting` in Visual Studio Code allows users to specify the appearance and behavior of the cursor in the code editor. This customization can enhance the coding experience by making the cursor more visible and easier to track, which is particularly beneficial during extended coding sessions or when working with complex codebases. The cursor style can be adjusted to suit personal preferences, aiding in comfort and efficiency.

**Editor: Cursor Blinking**

The Editor: `Cursor Blinking` setting in Visual Studio Code controls the blinking behavior of the cursor in the editor. This setting allows users to customize how the cursor appears and blinks, providing flexibility to match individual preferences and improve the coding experience.

    Setting -> Editor: Cursor Blinking -> expand

**Visual Code Font Ligatures**

The `Visual Code Font Ligatures` setting in Visual Studio Code enables or disables font ligatures in the editor. Font ligatures are special characters that combine multiple characters into a single glyph, providing a more visually appealing and readable representation of certain character combinations. Enabling font ligatures can enhance the appearance of your code by replacing common character combinations with ligature glyphs, making the code more aesthetically pleasing and easier to read.

**Suggest Selection**

The `Editor: Suggest Selection`setting in Visual Studio Code controls how selections are suggested in the editor. This setting affects the behavior of code suggestions, including autocomplete suggestions, parameter hints, and snippet suggestions. By customizing the suggest selection behavior, you can tailor the editor to your coding preferences and optimize your workflow for

    Setting -> Editor: Suggest Selection -> Vsintellicode -> automaticallyOverrodeDefaultValue

**Editor: Match Brackets**

The `Editor: Match Brackets` setting in Visual Studio Code specifies whether matching brackets are highlighted in the editor. When enabled, this feature highlights matching opening and closing brackets, parentheses, or braces when the cursor is positioned adjacent to them. This visual cue helps improve code readability and aids in identifying code blocks and nested structures more easily.

    Setting -> Editor: Match Brackets -> near

**Unknown At Rules**

The `Lint: Unknown At Rules` setting in Visual Studio Code controls linting for unknown at-rules in your CSS or SCSS files. At-rules are special instructions in CSS that start with an "@" symbol, such as @media, @font-face, or @keyframes. When enabled, this setting triggers linting warnings or errors when the editor encounters unknown or unsupported at-rules in your stylesheets.

    Setting -> Lint: Unknown At Rules -> All is Ignore

**Editor: Quick Suggestions**

In addition to enabling quick suggestions globally, you have the option to specify whether suggestions are shown for strings. Enabling suggestions for strings allows the editor to provide auto-completion options when you are typing within string literals, such as HTML attributes, JavaScript string arguments, or CSS property values.

Specifies whether quick suggestions are shown in the editor. You can enable suggestions for strings by setting `strings: true`.

**Bracket Pairs**

The "Editor › Guides: Bracket Pairs" setting in Visual Studio Code determines how bracket pairs are displayed in the editor. Bracket pairs, such as parentheses (), square brackets [], and curly braces {}, are essential components of many programming languages and markup formats. Properly displaying bracket pairs enhances code readability and aids in understanding the structure of nested elements within your code.

    Setting -> Editor › Guides: Bracket Pairs

**Render Whitespace**

The `Editor: Render Whitespace` setting in Visual Studio Code offers flexible options for customizing how whitespace characters are displayed in the editor. By choosing the appropriate whitespace rendering option, you can enhance code readability, maintain consistent formatting practices, and identify whitespace-related issues more effectively.

    Setting -> Editor: Render Whitespace

**Tree Indent**

The `Tree Indent` setting in Visual Studio Code specifies the indentation style for the tree view in the workbench. The tree view is a hierarchical representation of files and folders within your project, commonly displayed in the Explorer or File Explorer pane. Indentation enhances the visual hierarchy of items in the tree view, making it easier to understand the folder structure and navigate through project files.

    Setting -> Workbench > Tree: Indent

**Compact Folders**

The `Compact Folders` setting in Visual Studio Code controls whether folders are displayed in a compact style in the Explorer view. The Explorer view provides a hierarchical representation of files and folders within your project, allowing you to navigate and manage project assets efficiently. Compact folder display optimizes space utilization and enhances the readability of the file tree, especially in projects with deeply nested folder structures.

    Setting -> Explorer: Compact Folders

**Snippet Suggestions**

The `Snippet Suggestions` setting in Visual Studio Code controls whether snippet suggestions are shown in the editor. Snippets are predefined code templates that can be inserted into your code files to expedite common coding tasks, such as creating loops, functions, or HTML elements. Enabling snippet suggestions enhances your coding efficiency by providing quick access to these reusable code snippets directly within the editor.

    Setting -> Editor: Snippet Suggestions

```

```
