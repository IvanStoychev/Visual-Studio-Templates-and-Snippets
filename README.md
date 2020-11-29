<h1 align="center">
  <br>
    <img src="https://imgur.com/3lm0J5H.png" alt="Markdownify"></a>
  <br>
    Visual Studio Templates and Code Snippets
  <br>
</h1>

<p align="center">
  <a href="https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/branches">
    <img src="https://img.shields.io/github/last-commit/IvanStoychev/Visual-Studio-Templates-and-Snippets?style=plastic"
         alt="GitHub last commit">
  </a>
  <a href="https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/releases">
    <img src="https://img.shields.io/github/v/release/IvanStoychev/Visual-Studio-Templates-and-Snippets?style=plastic"
         alt="GitHub latest release">
  </a>
  <a href="https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/blob/master/LICENSE">
    <img src="https://img.shields.io/github/license/IvanStoychev/Visual-Studio-Templates-and-Snippets?style=plastic"
         alt="Project license">
  </a>
</p>

<h4 align="center">A collection of templates designed to make starting new projects a breeze.</h4>
<h5 align="center">This repo uses <a href="https://semver.org/#semantic-versioning-200">Semantic Versioning 2.0.0</a></h5>

<p align="center">
  <a href="#-join-the-community">Community</a> •
  <a href="#sparkling_heart-support-the-project">Support</a> •
  <a href="#-introduction">Introduction</a> •
  <a href="#-features">Features</a> •
  <a href="#-installation">Installation</a> •
  <a href="#ℹ-how-to-use">How to use</a> •
  <a href="#-documentation">Documentation</a> •
  <a href="#-contribution">Contribution</a>
</p>

<br/>

# 💬 Join the community
[![Check out the discussion at https://gitq.com/IvanStoychev/Visual-Studio-Templates-and-Snippets](https://gitq.com/badge.svg)](https://gitq.com/IvanStoychev/Visual-Studio-Templates-and-Snippets)
[![Join the chat at https://gitter.im/Visual-Studio-Templates-and-Snippets/community](https://badges.gitter.im/Visual-Studio-Templates-and-Snippets/community.svg)](https://gitter.im/Visual-Studio-Templates-and-Snippets/)

<br/>

# :sparkling_heart: Support the project
[![Support me on Patreon](https://img.shields.io/badge/Patreon-support-orange)](https://www.patreon.com/IvanStoychev)
[![Buy me a ko-fi](https://img.shields.io/badge/Buy%20me%20a-Ko--fi-green)](https://ko-fi.com/U7U31XQ28)
[![Sponsor me with PayPal](https://img.shields.io/badge/PayPal-sponsor-blue)](https://www.paypal.com/paypalme/IvanStoychevProjects)
[![Buy me a coffee](https://img.shields.io/badge/Buy%20me%20a-coffee-brown)](https://www.buymeacoffee.com/IvanStoychev)

<br/>

📣 Introduction
------------
This is a collection of code snippets, item and project templates for Visual Studio that I find useful.
They work by automatically scaffolding widely-used code, classes and project structures when added to your solution.

<br/>

📰 Features
------------
* Methods to keep or remove all special characters, letters and digits from a string.
  * Ex. `"!#%&lorem^@ipsum!@%".KeepOnlyLetters()` will return `"loremipsum"`.
* [`Remove`][6] methods that take a series of strings or characters and clear all their occurrences from the string with a single method call.
  * Ex. `"Lorem ipsum dolor Lorem ipsum sit amet".Remove("Lorem ", "ipsum ", "t")` will return `"dolor si ame"`.
* [`Contains`][7] methods that check if a string contains any of a series of provided values.
  * Ex. `"brake wheel icon number stoic".Contains("keen", "wild", "icon")` will return `true`.
* [`TrimStart`][6] and [`TrimEnd`][6] methods that take a string and remove it from the start or end of the original string.
  * Ex. `"In the beginning there was an end".TrimStart("In the beginning ")` will return `"there was an end"`, while `"In the beginning there was an end".TrimEnd(" an end")` will produce `"In the beginning there was"`.
* [`Replace`][8] methods that take a series of strings or characters and replace all their occurrences in the original string with a provided value.
  * Ex. `"Cucumbers, oranges and apples are vegetables.".Replace("tomatoes", "oranges", "apples")` will return `"Cucumbers, tomatoes and tomatoes are vegetables."`.
* [`Substring`][9] methods that use string arguments to determine a substring's position, instead of a starting index.
  * Ex. `"This is the start bla bladdy blah.".Substring("start ", false)` will return `"bla bladdy blah."`, while `"This is the start bla bladdy blah and this is the end.".Substring("start ", "blah", StringInclusionOptions.IncludeNone)` will return `"bla bladdy "`.

<br/>

🏗 Installation
------------
_**Code snippet**_
<br/>Import the `*.snippet` to Visual Studio by using the "Import" button in the "Code Snippets Manager" (Tools > Code Snippets Manager).
<br/>-or-
<br/>Copy the `*.snippet` file to `%UserProfile%\Documents\Visual Studio {edition}\Code Snippets\{language}`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019") and `{language}` is the language for which the snippet has been written.

<br/>

_**Item template**_
<br/>Copy the item template `*.zip` file to:
`%UserProfile%\Documents\Visual Studio {edition}\Templates\ItemTemplates`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019").
<br/>If Visual Studio is already open you will have to restart it for the templates to populate.

Optionally you may place it in any of the folders located there, for example "Visual C#".
<br/>If you wish to separate your templates by any other way, than the default provided by Visual Studio, you can create additional folders inside "ItemTemplates" which will show up in the "Add New Item" window.

<br/>

_**Project template**_
<br/>Copy the project template `*.zip` file to:
`%UserProfile%\Documents\Visual Studio {edition}\Templates\ProjectTemplates`, where `{edition}` is the edition of Visual Studio for which you want to install the template (e.g. "2019").
<br/>If Visual Studio is already open you will have to restart it for the templates to populate.

Optionally you may place it in any of the folders located there, for example "Visual C#".

<br/>

ℹ How to use
----------
To use a code snippet - make sure you are using the appropriate language then type its shortcut and press "Tab" twice. The code associated with the snipped will replace its shortcut.

To use any template - simply add it to your solution.
<br/>Item templates can be found by adding a new item to a project in the "Add New Item" window, while project templates are found by adding a new project to the solution, in the "Add a new project" window. Once added they are ready-to-use pieces of code.

Detailed desctiption of each template and snippet can be found in the [wiki][1].

<br/>

📖 Documentation
-------------
The current documentation repositori is the [Wiki][3].

<br/>

🧙‍ Contribution
-------------
Any ideas for improvement of existing templates or snippets or for addition of new templates and snippets is welcome.

If you think it's useful and people might benefit from it - open an issue or a pull request.


  [1]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki
  [2]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/releases
  [3]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/
  [4]: https://www.nuget.org/packages/Visual-Studio-Templates-and-Snippets/
  [5]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/packages
  [6]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/Remover
  [7]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/Comparer
  [8]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/Replacer
  [9]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/Selector
