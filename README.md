# Visual Studio Templates and Code Snippets

## Introduction
This is a collection of code snippets, item and project templates for Visual Studio that I find useful.
<br/>They work by automatically scaffolding widely-used code, classes and project structures when added to your solution.

<br/>

# Join the community
[![GitQ](https://gitq.com/badge.svg)](https://gitq.com/IvanStoychev/IvanStoychev.StringExtensions) [![Join the chat at https://gitter.im/Visual-Studio-Templates-and-Snippets/community](https://badges.gitter.im/Visual-Studio-Templates-and-Snippets/community.svg)](https://gitter.im/Visual-Studio-Templates-and-Snippets/community?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

<br/>

## Installation
_**Code snippet**_
<br/>Import the `*.snippet` to Visual Studio by using the "Import" button in the "Code Snippets Manager" (Tools > Code Snippets Manager).
<br/>-or-
<br/>Copy the `*.snippet` file to `%UserProfile%\Documents\Visual Studio {edition}\Code Snippets\{language}`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019") and `{language}` is the language for which the snippet has been written.

_**Item template**_
<br/>Copy the item template `*.zip` file to:
`%UserProfile%\Documents\Visual Studio {edition}\Templates\ItemTemplates`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019").
<br/>If Visual Studio is already open you will have to restart it for the templates to populate.

<br/>Optionally you may place it in any of the folders located there, for example "Visual C#".
<br/>If you wish to separate your templates by any other way, than the default provided by Visual Studio, you can create additional folders inside "ItemTemplates" which will show up in the "Add New Item" window.

<br/>

_**Project template**_
<br/>Copy the project template `*.zip` file to:
`%UserProfile%\Documents\Visual Studio {edition}\Templates\ProjectTemplates`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019").
<br/>If Visual Studio is already open you will have to restart it for the templates to populate.

<br/>Optionally you may place it in any of the folders located there, for example "Visual C#".

<br/>**Note!** Be advised that as of Visual Studio 2019 16.4.0 searching for project templates using the search box does not seem to function as expected. You can locate the templates by filtering by language, platform and project type or by scrolling to the bottom of the unfiltered list.

## How to use
To use a code snippet - make sure you are using the appropriate language then type its shortcut and press "Tab" twice. The code associated with the snipped will replace its shortcut.

To use any template - simply add it to your solution.
<br/>Item templates can be found by adding a new item to a project in the "Add New Item" window, while project templates are found by adding a new project to the solution, in the "Add a new project" window. Once added they are ready-to-use pieces of code.

Detailed desctiption of each template and snippet can be found in the [wiki][1].

## Contributing
Any ideas for improvement of existing templates or snippets or for addition of new templates and snippets is welcome.

If you think it's useful and a lot of people might benefit from it - open an issue of a pull request.

[1]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki
