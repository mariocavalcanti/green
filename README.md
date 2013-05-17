Green Framework v1.0a - 2013
==============================================

**A simple CSS framework for responsive websites  
Created by Mario Cavalcanti (@mariocavalcanti)**

Green Framework is a simple grid system for responsive websites. It brings a collection of CSS classes and uses grids based on percentages. These grids are adaptable to the desktop, tablet and smartphone screens. You can use it in any project, whether personal or commercial.

How to use the framework?
--------------------------

The first thing to do is to download the Green framework CSS and load it in your page. Inside of your project's ```<head>```, you must also include a special meta tag, as shown below. This meta tag basically tells the browsers that the scale of the viewport must be 1. In the case of mobile devices such as iPhone, the browser displays the page in its natural size. See the documentation to know about the Green classes list.

    <link href='css/green.css' rel='stylesheet' type='text/css'>
    <meta name="viewport" content="width=device-width, initial-scale=1, minimum-scale=1, maximum-scale=1" />

See below some code examples:

To create two columns with the same width:
-------------------------------------------

    <div class="container">
        <div class="grid-50"></div>
        <div class="grid-50"></div>
    </div>

To create a contect area with a sidebar:
-----------------------------------------

    <div class="container">
        <div class="grid-70">Área de Conteúdo</div>
        <div class="grid-30">Lateral</div>
    </div>

To create three columns with the same width:
----------------------------------------------

    <div class="container">
        <div class="grid-33"></div>
        <div class="grid-33"></div>
        <div class="grid-33"></div>
    </div>

A full grid inside a green panel and with centered text:
-------------------------------------------------------------------------

    <div class="pnl-green">
        <div class="container">
            <div class="grid-100 txt-center">This is an example</div>
        </div>
    </div>

To create two grids visible only on desktop:
---------------------------------------------

    <div class="container only-desktop">
        <div class="grid-40"></div>
        <div class="grid-60"></div>
    </div>

To create two grids visible only on mobile devices:
----------------------------------------------------

    <div class="container only-mobile">
        <div class="grid-40"></div>
        <div class="grid-60"></div>
    </div>
