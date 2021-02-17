---
layout: default
title: Useful options
parent: Visual Studio Code
nav_order: 2
---

# Visual Studio Code – useful options


1.	Ctrl+Shift+P – Command preview
2.	Function: *Open preview to decide*. 
    To open preview click the icon in upper-right corner:

    ![Preview](/assets/images/Open_preview_to_decide.png)

    Function *Open preview to decide* is specifically customized to the Markdown. Be sure that the your file is saved as a Markdown (.md extension) file. The preview shows how the content will be displayed in HTML.  
3.	Hints: Ctrl+Space  
4.	Displaying whitespace: [View] tab > Render Whitespace. Shows the spaces.  
For example: it shows a double space that marks the beginning of a new line in the same paragraph.  
5.	Prompting formating, not words: Ctrl+Shift+P > Preferences > Configure Language Specific Settings> Markdown> "editor.suggest.showWords": false  

    * Use the keys Ctrl+Shift+P. Enter the *Preferences* in the command field.   
      The following drop-down list should appear:

      ![Prompting formating](/assets/images/Prompting_formating_01.png)

    * Choose the option *Configure Language Specific Settings*  
      From the drop-down list choose the *Markdown* option as shown below:  

      ![Prompting formating](/assets/images/Prompting_formating_02.png)

    * The following settings.json file should appear:
      
      ![Prompting formating](/assets/images/Prompting_formating_03.png)


      Set "editor.suggest.showWords" to *false*.

6.	Functions for easier navigation.  They allow to navigate between the headings

    * Outline. It allows to navigate between the headings.  
  
      ![Outline](/assets/images/Outline.png)

    * Ctrl+Shift+P > Command preview
  
      ![Ctrl+Shift+P](/assets/images/Command_preview.png)

    * Breadcrumbs.  It allows to navigate between the folder, files and files sections.

      ![Breadcrumbs](/assets/images/Breadcrumbs.png)
 

7.	Extensions installation. Extensions improve the functioning of the program    for specific applications.  
View tab> Extensions> Markdown All In One> Install

    To install *Markdown All in One* extension (and each other) proceed as follows:

    * Click the "View" tab and choose the *Extensions* from the drop-down list.

      ![Extensions](/assets/images/Extensions_01.png)


    * Enter the *Markdown* in the command field on the left side of VS Code desktop, choose the *Markdown All in One* and click the **Install** button.

      ![Extensions](/assets/images/Extensions_02.png)

    * The extension screen appears with table of contents. In this place you have access to all information about *Markdown All in One* extension. 

       ![Extensions](/assets/images/Extensions_03.png)


    * Close the file if you don't need it more. Use the shortcut key Ctrl+F4.  
      You can always come back to this information when you need it step by step:  
      View tab> Extensions> Enter the Markdown in the command field > Choose the Markdown All In One extension.   


## Markdown All In One extension (examples):

* Text format: Ctrl+Shift+P > Markdown All In One > Format Document  
For example: it completes the table to a readable form.
It hasn’t a impact how the table will be visible in HTML but is more readable when we send the file as a “readme document” or as a “release note”.


* Generating a table of contents: Ctrl+Shift+P > Markdown All In One > Create Table of Contents 
or improves the table of contents

For more details about Markdown All In One – go to page:  
[Markdown All in One](https://marketplace.visualstudio.com/items?itemName=yzhang.markdown-all-in-one)


For more details about Visual Studio Code extensions for Markdown go to page:  
[Visual Studio Code extensions for Markdown](https://github.com/mundimark/awesome-markdown)

[Visual Studio Code Extension Marketplace](https://code.visualstudio.com/docs/editor/extension-gallery)