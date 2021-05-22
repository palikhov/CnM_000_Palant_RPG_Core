<style>
    .phb{padding-bottom:0.25cm;}
    .phb#p1:after {display:none;}
    .phb code{font-size:8pt;}
</style>

<img src='https://img00.deviantart.net/f717/i/2014/193/d/c/delve_into_madness_by_bonify-d7e46do.jpg' style="height:1750px; width:1245px; position:absolute; right:0px; top:-50px;"/>

<div class='cover-diamond'></div>

<div class='cover-header'>GM Binder Styling Reference</div>

<div class='cover-splotch'></div>

<div class='cover-footer'>A document to be used to create and modify styles or themes for GM Binder</div>

\pagebreak

# Introduction

## Preface
I wrote this guide for those wanting to personalize their documents, beyond the basic styling or the snippets provided by GM Binder. It is meant as an easy reference that can be used to change certain things quickly, as well as a guide for those new to styling! However, this will not be a guide to CSS. 
___
Though you could do this by looking at the CSS stylesheet, I wanted this guide to be a little easier on the eyes. This document provides you with snippets, but also teaches you how to customize them to your own taste. This is why you are here after all!
___
This is however not a guide on formatting, there are already guides on that!
___
If you are interested in how something is made, both Homebrewery and GM Binder can display their source code, which you can play around with to see how certain things are done. 
___
Also useful is looking at the references for CSS, as they explain the syntax, usage and effects of certain snippets. They also have a handy list of the properties you can change. 

##### Snippet Symbols
⍰ = value goes here

<div style='margin-top:25px;'></div>

> ## Word of Warning
> If you are completely unfamiliar with html and css, it is strongly recommended to at least get a grasp of the basics before proceeding. [Codecademy](https://www.codecademy.com/) is a great place to learn the languages we will be using in this document. [CSS Validators](https://jigsaw.w3.org/css-validator/) can be useful for finding mistakes, but remember that you are overwriting an existing style. 
>___
>If you do go ahead and want to play around with this, try it on a test document first. You could use the [Theme Tester](https://www.gmbinder.com/share/-L13H3wiyO_BKKfL6bqp) provided by /u/iveld. 
>___
>When changing these things, it can happen that some features of GM Binder don't work as intended. For example, changing the page size doesn't necessarily result in a printable document. Keep this in mind when using these types of modifications. Certain snippets, like "notes" might no longer work when you change text sizes drastically. 
>___
>**If you are about to report a bug**, *try your basic formatting (without any styling) in a different testing document first. It could very well be your styling responsible for the bug!*

\columnbreak

## Chapter 0: The Style Tag
To change anything, first you have to know where to put any of these changes. To write your documents, you use Markdown. But, when you want to change the colors of headers for example you use the `<style>` and `</style>` HTML tags. Between those tags you can put your CSS style changes. These will override the standard stylesheet. I recommend putting these at the start of your document. 

### Document or Page Style?
Sometimes you want to change styling for the entire document, but every so often you'll want to change just a single page. 

If you'd to change the color of the h5 header `#####` for the entire document, you would use the following code:


```    
<style>.phb h5{color:#c9ad6a;}</style>
```

But when you would want to change the size of the h1 header (`#`) for only the front page, just to increase the size of your cover title, you can't use the code found above, as this will change h1 for the entire document. Instead, you would use the following code:


```
<style>.phb#p1 h1{font-size: 200px;}
</style>
```

You could replace `#p1` with any page number by just changing the 1 (`#pXYZ`). 

### Div Styling
It is also possible to change some of the styling within the html `<div>` tag. If you'd want to make a paragraph of text red:


```
<div style="color:red">This text will be red.</div>
```

As you can see here: 

<div style="color:red">This text will be red.</div>

<div style="margin-top:10px;"></div>

*Let's look at changing the look of things commonly used in D&D 5E homebrew content!*

\pagebreakNum

<style>/*ToC Styling*/
  .toc a {color: inherit !important;}
  .toc li span:nth-child(2){width: auto;overflow: hidden;white-space: nowrap;display: block;}
  .toc li span:nth-child(2):after{font-family:BookSanity;font-size:0.317cm;font-weight:normal;color:black;content:" ........................................""........................................."".........................................";}
  .toc li span:first-child{float:right;font-family:BookSanity;font-size:0.317cm;font-weight:normal;color:black;margin-left:1px;}
  .toc li h3 span:nth-child(2):after{content: " ";}
  .toc li h3 {margin-bottom: 4px !important;margin-top: 10px !important;line-height: initial !important;}
  .toc li h5 {margin-bottom: 0.5px !important;margin-top: 2px !important;line-height: initial !important;}
  .toc li h3 span:first-child{line-height: 2.3em !important;}
  .toc ul ul {margin-left: 10px !important;}
  .toc>ul>li {margin-bottom: initial !important;}
  .phb#p3:after{display:none;}
</style>

<div class='wide' style="text-align: center">

### 
# Contents
###

</div>



<div class='toc'>

- ### [<span>4</span><span>Chapter 1: Common Questions</span>](#chapter-1-common-questions)
  - [<span>4</span><span>Hide Footer</span>](#chapter-1-common-questions-hide-footer)
  - [<span>4</span><span>Change Footer</span>](#chapter-1-common-questions-change-footer)
  - [<span>4</span><span>Display Page Number on Last Page</span>](#chapter-1-common-questions-display-page-number-on-last-page)
  - [<span>4</span><span>Start Page Numbering at 'X'</span>](#chapter-1-common-questions-start-page-numbering-at-x)
  - [<span>4</span><span>Columnbreak Fix</span>](#chapter-1-common-questions-columnbreak-fix)
  - [<span>4</span><span>Color Change</span>](#chapter-1-common-questions-color-change)
  - [<span>4</span><span>Hue Shifting</span>](#chapter-1-common-questions-hue-shifting)
  - [<span>5</span><span>Variables</span>](#chapter-1-common-questions-variables)
  - [<span>5</span><span>Fancy Table of Contents</span>](#chapter-1-common-questions-fancy-table-of-contents)
  - [<span>5</span><span>Multi Page Styling</span>](#chapter-1-common-questions-multi-page-styling)
- ### [<span>6</span><span>Appendix A: Defaults</span>](#appendix-a-defaults)
- ##### [<span>6</span><span>Text</span>](#appendix-a-defaults-text)
  - [<span>6</span><span>Headers</span>](#appendix-a-defaults-text-headers)
  - [<span>7</span><span>Paragraphs</span>](#appendix-a-defaults-text-paragraphs)
  - [<span>7</span><span>Lists</span>](#appendix-a-defaults-text-lists)
- ##### [<span>8</span><span>Snippets</span>](#appendix-a-defaults-snippets)
  - [<span>8</span><span>Tables</span>](#appendix-a-defaults-snippets-tables)
  - [<span>8</span><span>Spell Lists</span>](#appendix-a-defaults-snippets-spell-lists)
  - [<span>8</span><span>Class Table</span>](#appendix-a-defaults-snippets-class-table)
  - [<span>9</span><span>Notes</span>](#appendix-a-defaults-snippets-notes)
  - [<span>9</span><span>Desciptive Text Box</span>](#appendix-a-defaults-snippets-descriptive-text-box)
  - [<span>10</span><span>Monster Stat Block</span>](#appendix-a-defaults-snippets-monster-stat-block)
  - [<span>10</span><span>Wide Monster Stat Block</span>](#appendix-a-defaults-snippets-wide-monster-stat-block)
  - [<span>11</span><span>Images</span>](#appendix-a-defaults-snippets-images)
  - [<span>11</span><span>Cover (Front)</span>](#appendix-a-defaults-snippets-cover-front)
  - [<span>12</span><span>Cover (Back)</span>](#appendix-a-defaults-snippets-cover-back)
  - [<span>13</span><span>Part Header</span>](#appendix-a-defaults-snippets-part-header)
- ##### [<span>14</span><span>Page Elements</span>](#appendix-a-defaults-page-elements)
  - [<span>14</span><span>Document</span>](#appendix-a-defaults-page-elements-document)
  - [<span>14</span><span>Footer</span>](#appendix-a-defaults-page-elements-footer)
  - [<span>14</span><span>Page number</span>](#appendix-a-defaults-page-elements-page-number) 
  - [<span>14</span><span>Footnote</span>](#appendix-a-defaults-page-elements-footnote)
- ##### [<span>15</span><span>Other</span>](#appendix-a-defaults-other)
  - [<span>15</span><span>Table of Contents</span>](#appendix-a-defaults-other-table-of-contents)

\columnbreak

<div align="right">

## Credits
**Written** by *[Rhaenon](https://reddit.com/user/rhaenon)*.
___
**Special Thanks** to 

*[CobaltZephyr](https://reddit.com/user/CobaltZephyr)*

*[Iveld](https://reddit.com/user/iveld)*,

*[metaBot](https://reddit.com/user/metaBot)*, 

& *[SwordMeow](https://reddit.com/user/swordmeow)*.



<div style='margin-top:335px;'></div>

**Cover Art:** 

*[Delve Into Madness](https://bonify.deviantart.com/art/Delve-Into-Madness-446972748)* by Bonify <br>[CC BY-NC-ND 3.0]

<img src='https://img00.deviantart.net/f717/i/2014/193/d/c/delve_into_madness_by_bonify-d7e46do.jpg' style="width:320px;position:absolute;right:0px;bottom:-40px;"/>

<img 
  src='https://www.gmbinder.com/images/cPPYV7h.png' 
  style='position:absolute; top:0px; right:30px; height:1056px; width:1056px; transform:rotate(-90deg)' />

<img 
  src='https://www.gmbinder.com/images/cPPYV7h.png' 
  style='position:absolute; bottom:120px; right:0px; height:1056px; width:816px;' />

</div>

</div>

\pagebreak

# Chapter 1: Common Questions
___
After trying out the style snippets provided by GM Binder you were still not satisfied with the existing styles or were inspired to create your own. A good place to start is modifying and studying the existing snippets. If you're not familiar with CSS, I would recommend you do a little research into that. It is not as difficult as it might seem!

Below are some common things you might want to change, as snippets. 

<div class="descriptive">

**General Advice for GMB Styling**<br>
Only include as much as it would take to get your style across. If you like the look of PHB but with only a few changes, such as font and heading customization, only do that. If you want to overhaul it, keep the css streamlined and make sure it doesn't have unintended effects (such as making statblocks look weird). Basically do enough to achieve how you want it to look, but don't go overboard for the sake of doing it.

</div>

### Hide footer
On some pages, you'll want the footer to be gone. 


```
.phb#p⍰:after{display:none;}
```

### Change Footer
You can set a new footer using:

```
.phb:after{background-image:url(⍰);}
```

### Display Page Number on Last Page
You have two ways of displaying a page number on the last page. At the end of your last page include one of these snippets. These don't update automatically, so add these last. I have included one here:

```
<div class="pageNumber">⍰</div>
```

### Start Page Numbering at 'X'
If you want the page numbers to start at something else as 1, you can use the following snippet, where X is the page you want to start the numbering at, and Y the page number you want to start with minus 1. 

```
.phb#pX {counter-reset: phb-page-numbers Y;}

```

\columnbreak


### Columnbreak Fix
When you are having trouble fitting your content on a page, columnbreak can be a little bit of a hassle sometimes. Here is a hack that enables you to break your columns where you want. Keep in mind text or content might run into the footer. 

```
.phb{padding-bottom:0.5cm;}
```

### Color Change
Easily change colors in normal D&D5e styling with this snippet. Place the desired color codes or rgba in place of the question boxes. 


```
:root{
--header: ⍰; /* Headercolors for h1 - h4 */
--subheader: ⍰; /* H5 */
--accent: ⍰; /* Underline, footnote, pagenumber, links*/
--backing: ⍰;} /* tables, notes, etc */
}
.phb h1, .phb h2, .phb h3, .phb h4{color:var(--header);}
.phb h3{border-bottom: 2px solid var(--accent);}
.phb h5{color:var(--subheader);}
.phb .pageNumber{color:var(--accent);}
.phb .footnote{color:var(--accent);}
.phb blockquote {background-color:var(--backing);}
.phb table tbody tr:nth-child(odd){background-color:var(--backing);}
.phb hr+section blockquote tr:nth-child(odd) td {background-color:transparent;}
.phb a, .phb .footnote a:hover, .phb a:active, .phb a:focus{color: var(--accent);}
```

### Hue Shifting
You can use `filter:hue-rotate(0deg);` to change the hues of images used in your docs. For example, to change the color of the cover splotch. Keep in mind this will affect the entire class. If you hue-rotate `.classTable` for example, the table rows inside will rotate with it. Using variables will greatly reduce the number changing. 

```
.cover-splotch{
  filter: hue-rotate(90deg);
  filter: saturate(5);
  -webkit-filter: hue-rotate(90deg) saturate(5);
  -moz-filter: hue-rotate(90deg) saturate(5);
  -o-filter: hue-rotate(90deg) saturate(5);
}
```

\pagebreakNum

### Variables
As you can see in the colors section, you can use variables to make the process easier. Declaring variables is done within the root selector, and you can use a variable by using `var(--name)`. This will make playing around with colors a lot easier.

### Fancy Table of Contents
If you'd like to use a fancy table of contents, like the one found in this document, scroll down to *Appendix A: Table of Contents* for the snippet. 

### Multi Page Styling
When wanting to change the styling for multiple changes at once, you can use the following selectors:

```
.phb#p1,.phb#p2,.phb#p3,...
```

However, if you are going to change 50 pages, this is not efficient. [CobaltZephyr](https://reddit.com/user/CobaltZephyr) has worked on an [Alternative PHB Styles](https://www.gmbinder.com/share/-L4GbrHNjIuuE2D2eopi) document where each part has their own accent colors. CobaltZephyr found the following alternative to the aforementioned selection method. 

<div style="color:#58180D;font-weight:bold;">
This is an advanced method, which works best for footers, but can cause some issues when used with tables for example. 
</div>

If you wanted a style to start on page 4, you'd use the following snippet. You can use `:nth-child(odd/even)` as well. For a more indepth look, I will refer you to the aformentioned fantastic document by CobaltZephyr. 

```
.phb:nth-child(n+4){ }
```

\pagebreakNum

# Appendix A: Defaults
## Text
### Headers
Headers are used a lot throughout your content. They provide the structure that makes your homebrew easy on the eyes. Before changing the values, you'd first have to know what the default is. 

##### H1 - H2 - H3 - H4
These properties and values apply for all of these headers. Change these values by using `.phb h1, h2, h3, h4{;}`
```
.phb h1, .phb h2, .phb h3, .phb h4{
margin-top:         .2em;               
margin-bottom:      .2em;
font-family:        MrJeeves;
font-weight:        800;
color:              #58180D;}
```
##### H1
```
.phb h1{
column-span:        all;                
font-size:          .987cm;
-webkit-column-span:all;
-moz-column-span:   all;}
```

##### H2
```
.phb h2{
font-size:          .705cm;             
}
```

##### H3
```
.phb h3{
font-size:          .529cm;
border-bottom:      2px solid #c9ad6a   
}
```

##### H4
```
.phb h4{
margin-bottom:      0;                  
font-size:          .458cm
}
```

\columnbreak

##### H5
```
.phb h5{
margin-bottom:      .2em;               
font-family:        ScalySansSmallCaps;
font-size:          .423cm;
font-weight:        900
}
```

##### H6

```
.phb h6{}
```

\pagebreakNum

### Paragraphs

##### P
```
.phb p{
line-height:        1.3em;}             
```

##### P+P
```
.phb p+p{
margin-top:         -0.8em;}            
```

##### Text Indentation
```
.phb p+p,                               
.phb ul+p,
.phb ol+p {
    text-indent:    1em
}
```

##### Text Decoration
```
.phb strong {
    font-weight:    bold;               
    letter-spacing: .03em
}
.phb em {
    font-style:     italic
}
.phb sup {
    vertical-align: super;
    font-size:      xx-small;
    line-height:    0
}
.phb sub {
    vertical-align: sub;
    font-size:      smaller;
    line-height:    0
}
```

##### First Letter after H1
```
.phb h1+p::first-letter {
    float:          left;
    font-family:    Solberry;
    font-size:      10em;
    color:          #222;
    line-height:    .8em
}
```

\columnbreak

### Lists

##### UL
```
.phb ul{
margin-bottom:      .8em;               
padding-left:       1.4em;
line-height:        1.3em;
list-style-position:outside;
list-style-type:    disc;
}
```

##### OL
```
margin-bottom:      .8em;               
padding-left:       1.4em;
line-height:        1.3em;
list-style-position:outside;
list-style-type:    decimal
```

\pagebreakNum

## Snippets
### Tables

```
.phb table {                            
    font-family: ScalySans;
    width: 100%;
    margin-bottom: 1em;
    font-size: 10pt;
    line-height: 1.1em
}
.phb table em {
    font-family: ScalySans;
    font-style: italic
}
.phb table strong {
    font-family: ScalySans;
    font-weight: 800;
    letter-spacing: -0.02em
}
.phb table thead {
    font-weight: 800
}
.phb table thead th {
    vertical-align: bottom;
    padding-bottom: .3em;
    padding-right: .1em;
    padding-left: .1em
}
.phb table tbody tr td {
    padding: .3em .1em
}
.phb table tbody tr:nth-child(odd) {
    background-color: #e0e5c1
}
```

### Spell Lists

```
.phb .spellList{
 font-family:ScalySans;
 column-count:4;
 column-span:all;
 -webkit-column-span:all;
 -moz-column-span:all}
.phb .spellList em{font-family:ScalySans;font-style:italic}
.phb .spellList strong{font-family:ScalySans;font-weight:800;letter-spacing:-0.02em}
.phb .spellList ul+h5{margin-top:15px}
.phb .spellList p,.phb .spellList ul{font-size:.352cm;line-height:1.3em}
.phb .spellList ul{margin-bottom:.5em;padding-left:1em;text-indent:-1em;list-style-type:none;-webkit-column-break-inside:auto;column-break-inside:auto}
```

\columnbreak

### Class Table
```
.phb .classTable{
    margin-top:25px;
    margin-bottom:40px;
    border-collapse:separate;
    background-color:white;
    border:initial;
    border-style:solid;
    border-image-outset:25px 17px;
    border-image-repeat:round;
    border-image-slice:150 200 150 200;
    border-image-source:url('/assets/img/table-wrap.png');
    border-image-width:47px
}
.phb .classTable h5{
    margin-bottom:10px
}
```

\pagebreakNum

### Notes

 

> <center> Note </center>

```
.phb blockquote {
    font-family: ScalySans;
    box-sizing: border-box;
    margin-bottom: 1em;
    margin-top: 9px;
    padding: 5px 10px;
    background-color: #e0e5c1;
    border-style: solid;
    border-width: 11px;
    border-image: url('/assets/img/note-wrap.png') 11;
    border-image-outset: 9px 0;
    box-shadow: 1px 4px 14px #888
}
.phb blockquote em {
    font-family: ScalySans;
    font-style: italic
}
.phb blockquote strong {
    font-family: ScalySans;
    font-weight: 800;
    letter-spacing: -0.02em
}
.phb blockquote p,
.phb blockquote ul {
    font-size: .352cm;
    line-height: 1.1em
}
.phb pre+blockquote,
.phb h2+blockquote,
.phb h3+blockquote,
.phb h4+blockquote,
.phb h5+blockquote {
    margin-top: 13px}
.phb blockquote h5 {
    margin-top: 0}
```

\columnbreak

### Descriptive Text Box

 

<div class='descriptive'>
 
 ##### Catchy Title
 Useful information
 
 </div>
 
```
.phb .descriptive{
    display:block-inline;
    margin-bottom:1em;
    background-color:#faf7ea;
    font-family:ScalySans;
    border-style:solid;
    border-width:7px;
    border-image:url('/assets/img/sidebars.png') 12 round;
    border-image-outset:4px;
    box-shadow:0 0 6px #faf7ea
}
.phb .descriptive p{
    display:block;
    padding-bottom:0;
    line-height:1.5em
}
.phb .descriptive p+p{
    padding-top:.8em
}
.phb .descriptive em{
    font-family:ScalySans;
    font-style:italic
}
.phb .descriptive strong{
    font-family:ScalySans;
    font-weight:800;
    letter-spacing:-0.02em
}
.phb pre+.descriptive{
    margin-top:8px
}
```

\pagebreakNum

### Monster Stat Block

```
.phb hr+section blockquote {
    position: relative;
    padding-top: 15px;
    background-color: #FDF1DC;
    border-style: solid;
    background-image: url('/assets/img/blockquote-bg.png');
    border-image: url('/assets/img/blockquote-wrap.png');
    background-position: center;
    border-width: 8px;
    border-image-slice: 20
}
.phb hr+section blockquote h2 {
    margin-top: -8px;
    margin-bottom: 0
}
.phb hr+section blockquote h2+p {
    padding-bottom: 0
}
.phb hr+section blockquote h3 {
    font-family: ScalySans;
    font-weight: 400;
    border-bottom: 1px solid #58180D
}
.phb hr+section blockquote hr+ul {
    color: #58180D
}
.phb hr+section blockquote ul {
    font-family: ScalySans;
    padding-left: 1em;
    font-size: .352cm
}
.phb hr+section blockquote ul em {
    font-family: ScalySans;
    font-style: italic
}
.phb hr+section blockquote ul strong {
    font-family: ScalySans;
    font-weight: 800;
    letter-spacing: -0.02em
}
```

\columnbreak

```
.phb hr+section blockquote hr+table {
    margin: 0;
    column-span: 1;
    background-color: transparent;
    border-style: none;
    border-image: none;
    -webkit-column-span: 1
}
.phb hr+section blockquote hr+table tbody tr:nth-child(odd),
.phb hr+section blockquote hr+table tbody tr:nth-child(even) {
    background-color: transparent
}
.phb hr+section blockquote table {
    color: #58180D
}
.phb hr+section blockquote p+p {
    margin-top: 0;
    text-indent: 0;
    margin-bottom: 7px
}
.phb hr+section blockquote hr {
    visibility: visible;
    height: 6px;
    margin: 4px 0;
    background-image: url('/assets/img/arrow-right.png');
    background-size: 100% 100%;
    border: none
```

### Wide Monster Stat Block
```
.phb hr+hr+section blockquote {
    column-count: 2;
    column-fill: auto;
    column-gap: 1cm;
    column-width: 7.68cm;
    -webkit-column-count: 2;
    -moz-column-count: 2;
    -webkit-column-width: 7.68cm;
    -moz-column-width: 7.68cm;
    -webkit-column-gap: 1cm;
    -moz-column-gap: 1cm
}
```

\pagebreakNum

### Images
```
.phb .image-top{
    position:absolute;
    left:0;
    top:0;
    width:824px
}
.phb .image-right{
    position:absolute;
    right:0;
    top:0;
    height:1066px
}
.phb .image-bottom{
    position:absolute;
    left:0;
    bottom:0;
    width:824px
}
.phb .image-left{
    position:absolute;
    left:0;
    top:0;
    height:1066px
}
.phb .image-top-left{
    position:absolute;
    left:0;
    top:0
}
.phb .image-top-right{
    position:absolute;
    right:0;
    top:0
}
.phb .image-bottom-right{
    position:absolute;
    right:0;
    bottom:0
}
.phb .image-bottom-left{
    position:absolute;
    left:0;
    bottom:0
}
.phb img{
    z-index:-1
}
```

\columnbreak

### Cover (Front)
```
.phb .cover-header{
    position:absolute;
    font-family:NodestoCaps,nodesto,sans-serif;
    transform:scale(2, 2) !important;
    font-weight:normal;
    font-size:36px;
    color:white;
    width:700px;
    text-shadow:1px 1px 2px #000000,-1px 1px 2px #000000,1px -1px 2px #000000,-1px -1px 2px #000000;
    transform:scaleY(3) scaleX(1);
    top:50px;
    text-align:center
}
.phb .cover-image{
    position:absolute;
    top:0;
    left:0;
    width:824px
}
.phb .cover-diamond{
    background-image:url('/assets/img/DiamondDD.png');
    background-size:400px;
    background-repeat:no-repeat;
    position:absolute;
    left:210px;
    top:115px;
    width:400px;
    height:12px
}
.phb .cover-splotch{
    background-image:url('/assets/img/UNR8ilF.png');
    background-size:350px;
    position:absolute;
    left:0;
    bottom:180px;
    width:345px;
    height:56px
}
.phb .cover-footer{
    position:absolute;
    font-family:ScalySans;
    font-size:20px;
    color:white;
    bottom:50px;
    right:55px;
    width:700px;
    text-shadow:1px 1px 2px #000000,-1px 1px 2px #000000,1px -1px 2px #000000,-1px -1px 2px #000000;
    filter:opacity(100%);
    text-align:center
```

\pagebreakNum

### Cover (Back)

```
.phb .back-cover-image{
    position:absolute;
    height:1066px;
    left:0;
    top:0;
    width:475px;
    background-image:url('/assets/img/backcover-bg.png');
    background-size:475px 1066px;
    z-index:-1
}
.phb .back-cover-diamond{
    background-image:url('/assets/img/DiamondDD.png');
    background-size:280px;
    background-repeat:no-repeat;
    position:absolute;
    left:90px;
    top:110px;
    width:280px;
    height:8px
}
.phb .back-cover-logo{
    background-image:url('https://www.gmbinder.com/assets/img/logo-stacked-light.png');
    background-size:120px;
    position:absolute;
    left:165px;
    bottom:95px;
    width:120px;
    height:74px
}
.phb .back-cover-logo-link{
    text-align:center;
    font-family:sans-serif;
    position:absolute;
    bottom:30px;
    left:145px
}
.phb .back-cover-logo-link p{
    font-family:ScalySans,sans-serif;
    line-height:1.6em !important;
    font-size:16px;
    padding-bottom:25px
}
.phb .back-cover-logo-link a{
    color:#fff;
    text-decoration:none
}
```

\columnbreak

```
.phb .back-cover-header{
    color:#ff2a1a;
    font-family:NodestoCaps,sans-serif;
    font-size:64px;
    text-align:center;
    text-shadow:1px 1px 2px #000000,-1px 1px 2px #000000,1px -1px 2px #000000,-1px -1px 2px #000000
}
.phb .back-cover-header p{
    text-indent:0;
    padding-bottom:15px
}
.phb .back-cover-header p+p{
    text-indent:0
}
.phb .back-cover-text{
    color:#fff;
    font-family:sans-serif
}
.phb .back-cover-text a{
    color:#AC8F66
}
.phb .back-cover-text p{
    font-family:ScalySans,sans-serif;
    line-height:1.6em !important;
    font-size:16px;
    padding-bottom:25px
}
.phb .back-cover-text p+p{
    text-indent:0
}
.phb .back-cover-close{
    color:#fff;
    text-align:center;
    font-family:sans-serif
}
.phb .back-cover-close a{
    color:#AC8F66
}
.phb .back-cover-close p{
    font-family:ScalySans,sans-serif;
    line-height:1.6em !important;
    font-size:16px;
    padding-bottom:25px
}
.phb .back-cover-close p+p{
    text-indent:0
}
.phb .back-cover-right{
    padding-left:60px
}
```

\pagebreakNum

### Part header

#### PHB Part page

```
.phb .partpage{
    text-align:center;
    position:absolute;
    top:0;
    left:0;
    right:0;
    background-image:url('/assets/img/pph.png');
    background-size:cover;
    background-position:center;
    height:217px
}
.phb .partpage h1{
    font-family:NodestoCaps;
    font-size:64pt;
    font-weight:normal;
    letter-spacing:-2px;
    margin:12px 0 -17.5px 0
}
.phb .partpage h5{
    font-family:ScalaSans;
    font-size:13pt;
    color:#58180D
}
```

\columnbreak

#### DMG Part page

```
.phb .partpage-dmg{
    text-align:center;
    position:absolute;
    top:0;
    left:0;
    right:0;
    background-image:url('/assets/img/pph-dmg.png');
    background-size:cover;
    background-position:center;
    height:206px
}
.phb .partpage-dmg h1{
    font-family:NodestoCaps;
    font-size:64pt;
    font-weight:normal;
    letter-spacing:-2px;
    margin:12px 0 -12.5px 0
}
.phb .partpage-dmg h5{
    font-family:ScalaSans;
    font-size:13pt;
    color:black
}
```

\pagebreakNum

## Page Elements
### Document
```
.phb{
    color:#000;
    column-count:2;
    column-fill:auto;
    column-gap:1cm;
    column-width:8cm;
    -webkit-column-count:2;
    -moz-column-count:2;
    -webkit-column-width:8cm;
    -moz-column-width:8cm;
    -webkit-column-gap:1cm;
    -moz-column-gap:1cm;
    counter-increment:phb-page-numbers;
    position:relative;
    z-index:15;
    box-sizing:border-box;
    overflow:hidden;
    height:279.4mm;
    width:215.9mm;
    padding:1cm 1.7cm;
    padding-bottom:1.5cm;
    background-color:#EEE5CE;
    background-image:url('/assets/img/phb_bg.png');
    font-family:BookSanity;
    font-size:.317cm;
    text-rendering:optimizeLegibility;
    page-break-before:always;
    page-break-after:always;
    margin:30px auto;
    box-shadow:1px 4px 14px #000
}
```

### Footer
```
.phb:after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    height: 55px;
    width: 100%;
    background-image: url('/assets/img/footer.png');
    background-size: cover
}
.phb:nth-child(even):after {transform: scaleX(-1)}
.phb:nth-child(even) .pageNumber {left: 2px}
.phb:nth-child(even) .footnote {
    left: 80px;
    text-align: left
}
```

\columnbreak

### Page Number
```
.phb .pageNumber{
    position:absolute;
    right:2px;
    bottom:23px;
    width:50px;
    font-size:.9em;
    color:#c9ad6a;
    text-align:center
}
```

### Footnote

```
.phb .footnote{
    position:absolute;
    right:80px;
    bottom:37px;
    width:200px;
    font-size:.8em;
    color:#c9ad6a;
    text-align:right
}
```

\pagebreakNum

## Other
### Table of Contents

```
.phb .toc{
    -webkit-column-break-inside:avoid;
    column-break-inside:avoid
}
.phb .toc a{
    color:black;
    text-decoration:none
}
.phb .toc a:hover{
    text-decoration:underline
}
.phb .toc ul{
    padding-left:0;
    list-style-type:none
}
.phb .toc>ul>li{
    margin-bottom:10px
```

\columnbreak

#### Popular override by /u/calculuschild:
```
.toc a {
 color: inherit !important;	/*toc specifically wants black text. This resets the headers*/}
.toc li span:nth-child(2){ /*Allow dot leaders to fill remaining space but not overlap*/
 width: auto;
 overflow: hidden;
 white-space: nowrap; 
 display: block;}
.toc li span:nth-child(2):after{
 font-family: BookSanity; /*Remove any header styles from dot leaders*/
 font-size: 0.317cm;
 font-weight: normal;
 color: black;
 content:" ........................................" "........................................." ".........................................";}
.toc li span:first-child{ /*Remove any header styles from page numbers*/
 float: right;
 font-family: BookSanity;
 font-size: 0.317cm;
 font-weight: normal;
 color: black;
 margin-left: 1px; /*Leaves a small space between page numbers and dot leaders*/}
/*Special cases for headings*/    
.toc li h3 span:nth-child(2):after{content: " ";/*Remove dot leaders on h3*/}
.toc li h3 {
 margin-bottom: 4px !important;	/*Special spacing for h3*/
 margin-top: 10px !important;
 line-height: initial !important; /*For some reason Multi-line h3 line spacing changed*/}
.toc li h3 span:first-child{line-height: 1.8em !important;  	/*Line page numbers up with Multi-line h3 better*/}
.toc ul ul {margin-left: 10px !important; /*Original lists intented too much*/}
.toc>ul>li {margin-bottom: initial !important; /*margin for list items needs to be removed or 0*/}
```

\pagebreakNum
 
 <style>
   /** Change the p2 to whatever page number is the last page in your document **/
   .phb#p16:after { display:none; }
 </style>
 
 <img src='https://img00.deviantart.net/f717/i/2014/193/d/c/delve_into_madness_by_bonify-d7e46do.jpg' class='cover-image' style="height:1656px; width:1245px; position:absolute; left:387px; top:-50px;"/>
 
 <div class='back-cover-image'></div>
 
 <div style='margin-top:20px;'></div>
 
 <div class='back-cover-header'>
 
Add a

touch

of style

 </div>
 
 <div class='back-cover-text'>
 
People love to see pretty documents when searching for new homebrew content. With the power of a dark magic known to Earth as CSS, you create beautiful templates to use for your content. 
 
Use this reference to personalize your documents for your game and needs. Practice good practices, like useful naming conventions and not repeating yourself. Smaller is faster. 
 
 </div>
 
 <div class='back-cover-diamond' style='top: 679px;'></div>
 
 <div class='back-cover-close'>
 
 When you're ready to share with the community, don't forget to mark your document as public so people can find it in the [GM Binder Search](https://www.gmbinder.com/search)
 
 </div>
 
 <div class='back-cover-logo'></div>
 
 <div style='margin-top:185px;'></div>
 
 <div class="back-cover-text" align="center">
 
 Created for  
 
 </div>
 
 <div class='back-cover-logo-link'>
 
 [WWW.GMBINDER.COM](https://www.gmbinder.com)
 
 </div>