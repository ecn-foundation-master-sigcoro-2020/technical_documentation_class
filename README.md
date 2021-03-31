# Technical documentation

## What is, what for and for whom?
__Technical documentation__ is a set of texts, codes, diagrams, images and plots that describe your solution for a selected technical problem. It serves the following purposes:
* Describe your ideas to the colleagues or successors, so that they can participate or continue your work;
* Describe your project to a wider public and, possibly, future employers.
* Unburden your mind and memory of complex information;
* Organise your ideas, because having them written down is the first step to the implementation;

It is important to __write the documentation continuously__ as you are working, and not at the very end. Consider it your project's diary. It doesn't need to be pretty at the beginning, you may use any text editor or a pen and paper. A lot of what you have written may not end up in the final version, so don't be afraid of writing down all the smallest ideas as they come in.

## README.md file
If you take a look at any actively developing repository (here are a few examples: [1](https://github.com/dotnet/net6-mobile-samples), [2](https://github.com/rust-analyzer/rust-analyzer), [3](https://github.com/DrKLO/Telegram)), you will see that they all have a file called _README.md_ in their root folder. This file contains the documentations and, on GitHub, is automatically shown on the repository page, below the folders.

You can find more information on how to write your own documentation _README.md_ in [README_template.md](./README_template.md) file in this repository. You may use it as a template to initiate your own documentation.

__Note:__ If some subfolders of your project need a separate documentation, they can have a separate README.md file within them.


## Markdown
.md in README.md stands for __M__ark __d__own.

Markdown is a *markup* language, like HTML but simpler, permitting to create formatted documents using only a text editor. A document is then rendered (visualised) by some other software, like Atom or a web browser.

Markdown is one of the standards for documentation in software repositories. In your projects, you will have to provide one or multiple README.md files written in Markdown as a part of your final report.

Markdown is a markup language, which means that you don't see the final view of the document until you *render* it. This is very similar to HTML or LaTeX and opposite to Word, where you see the document the way it will be printed.
For example, the document you are reading now is written in Markdown using Atom, and converted by GitHub into what you are actually seeing.

During the class, we will go through the Markdown syntax together following a great [walkthrough]((https://www.markdownguide.org/basic-syntax/)) available online. You may refer to it later when writing the documentation for your projects. During the class, you may use an [online](https://jbt.github.io/markdown-editor/) Markdown editor. After class, you may find it useful to write thing offline using an Atom *Markdown Preview* package (installation via Atom application, Preferences panel). 

What I would like you to focus on in this class is the outline of your documents. In this repository, I provide a template [README_template.md](README_template.md) for a README.md file. When writing README for your own repository, use it as a starting point.


## draw.io
[__draw.io__](draw.io) is a free online diagram editor. It is a great tool for illustrating your code architecture, program logic, project structure, etc. It doesn't need registration and you can pair it with GitHub, so that your diagrams are saved in your repository.

## Homework
1. In your project repositories, create your own README.md file.
2. Write a short description (Abstract) of your project, about 100-150 words.
3. Outline the rest of the report, according to the template.

From now on, completing this document will be your ongoing task. Its final version will become your project report.

## Where to seek for more?
After your studies at ECN, if you feel that you liked to publish your work and want to have more tools to do it, checkout [Github pages](https://pages.github.com) for general web-site hosting and [LaTeX](https://www.overleaf.com) for professional scientific typesetting.
