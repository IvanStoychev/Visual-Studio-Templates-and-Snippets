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
[![Tweet @ivan_stoychev](https://img.shields.io/twitter/url?label=My%20twitter&style=social&url=https%3A%2F%2Ftwitter.com%2Fivan_stoychev)](https://twitter.com/ivan_stoychev)

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
* [Code snippet for WPF MVVM properties][2].
* [Relay command][4] and [viewmodel locator][5] for WPF MVVM.
* [A scaffolded WPF MVVM project, complete with a viewmodel locator and relay command][3].

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
The current documentation repositori is the [Wiki][1].

<br/>

🧙‍ Contribution
-------------
Any ideas for improvement of existing templates or snippets or for addition of new templates and snippets is welcome.

If you think it's useful and people might benefit from it - open an issue or a pull request.


  [1]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki
  [2]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/propwpf
  [3]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/WPF-Starter-project-(.NET-Core-3.1)
  [4]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/RelayCommand
  [5]: https://github.com/IvanStoychev/Visual-Studio-Templates-and-Snippets/wiki/ViewModelLocator
