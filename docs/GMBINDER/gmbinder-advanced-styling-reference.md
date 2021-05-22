<style>
    /* Background */
    .phb{
        width            : 210mm;
        height           : 297mm;
        background-image : url('https://www.gmbinder.com/images/VXHkQzp.jpg');
        background-size  : 100% 100%;
        filter           : brightness(100%);
    }

    .phb .back-cover-logo{
        background-image : url('https://www.gmbinder.com/images/GrViGdC.png');
        background-size  : 125px;
    }
    
    .phb p.head{
        font-size        : 100%;
    }
    /* End Background */
    
    /* Colors */
    .phb h5{
        font-size        : 154%;
    }
    
    .phb blockquote h5{
        font-size        : 104%;
    }
    
    .phb h4{
        color            : #293f50;
        font-size        : 155%;
    }
    
    .phb h3{
        color            : #293f50;
        border-bottom    : 2px solid black;
        font-size        : 186%;
    }
    
    .phb hr+section blockquote h3{
        font-size        : 120%;
    }
    
    .phb h2{
        color            : #293f50;
        font-size        : 250%;
    }
    
    .phb hr+section blockquote h2{
        color            : #09386d;
        font-size        : 140%;
    }
    
    .phb h1{
        color            : #293f50;
        font-size        : 400%;
    }
    
    .phb p{
        font-size        : 104%;
    }
    
    .phb a{
        color            : #09386d;
    }
    
    code{
        color            : #09386d;
    }
    
    .phb hr + section blockquote table{
        color            : black;
    }
    
    .phb hr + section blockquote hr+ul{
        color            : black;
    }
    /* End Colors */
    
    /* Notes */
    .phb section blockquote{
        background-color : #E8F2F8;
        box-shadow       : 0 0 6px black;
    }
    
    .phb .descriptive{
        background-color : white;
        box-shadow       : 0 0 6px black;
        border-image     : url('https://www.gmbinder.com/images/16uasjU.png');
        border-image-slice: 10;
        border-image-outset: 2px .8;
    }
    
    .phb blockquote{
        border-width: 11px;
        border-image: url('https://www.gmbinder.com/images/4DowZjU.png') 11;
        border-image-outset: 10px 0;
    }
    /* End Notes*/
    
    /* Tables */
    table tr:nth-child(odd) td {
        background-color : #c3d6e2;
    }
    
    .phb hr + section blockquote{
        background-color : white;
        background-image : url('');
        border-image     : url('https://www.gmbinder.com/images/FFpbsDm.png');
        border-image-slice : 20;
        border-image-outset : 7px .12;
    }
    
    .phb hr + section blockquote tr:nth-child(odd) td {
        background-color : transparent;
    }
    
    .phb hr+section blockquote hr{
        background-image : url('https://www.gmbinder.com/images/u2hOd7z.png')
    }
    
    .phb .classTable{
        border-image-source : url('https://www.gmbinder.com/images/K2HdDg9.png')
    }
    /* End Tables*/
    
    /* Table of Contents */
    .toc a
    {
        color                : inherit !important; /* toc specifically wants black text. This resets the headers */
    }
    
    .toc li span:nth-child(2) { /* Allow dot leaders to fill remaining space but not overlap */
        width                : auto;
        overflow             : hidden;
        white-space          : nowrap; 
        display              : block;
    }
    
    .toc li span:nth-child(2):after {
        font-family          : BookSanity; /* Remove any header styles from dot leaders */
        font-size            : 1em;
        font-weight          : normal;
        color                : black;
        content              : " ........................................" "........................................." ".........................................";
    }
    
    .toc li span:first-child { /* Remove any header styles from page numbers */
        float                : right;
        font-family          : BookSanity;
        font-size            : 1em;
        font-weight          : normal;
        color                : black;
        margin-left          : 0.5em; /* Leaves a small space between page numbers and dot leaders */
    }
    
    /*Special cases for headings*/    
    .toc li h3 span:nth-child(2):after {
        content              : " "; /* Remove dot leaders on h3 */
    }
    
    .toc li h3 {
        margin-bottom        : 0.5em !important; /*Special spacing for h3*/
        margin-top           : 1em !important;
        line-height          : initial !important; /* For some reason Multi-line h3 line spacing changed */
    }
    
    .toc li h3 span:first-child {
        line-height          : 2em !important; /* Line page numbers up with Multi-line h3 better */
    }
    
    .toc ul ul {
        margin-left          : 1em !important; /* Original lists indented too much */
    }
    
    .toc>ul>li {
        margin-bottom        : initial !important; /* Margin for list items needs to be removed or 0 */
    }
    /* End Table of Contents */
    
    /* Footers */
    .phb .footnote {
        position         : absolute;
        color            : black;
        font-size        : 12px;
        width            : 100%;
        bottom           : 2.5em;
        left             : 0px !important;
        border           : 1px solid red;
        text-align       : center !important;
    }
    
    .phb:nth-child(odd):after{ 
        content          : '';
        position         : absolute;
        bottom           : -3px;
        left             : -70px;
        z-index          : -1;
        height           : 100%;
        width            : 109%;
        background-image : url('https://www.gmbinder.com/images/HLSzYx9.png');
        background-size  : cover;
    }
    
    .phb:nth-child(even):after{ 
        content          : '';
        position         : absolute;
        bottom           : -2px;
        left             : -2px;
        z-index          : -1;
        height           : 100%;
        width            : 109%;
        background-image : url('https://www.gmbinder.com/images/HLSzYx9.png');
        -webkit-transform : scaleX(-1);
        transform        : scaleX(-1);
    }
    
    .phb p.foot{
        content          : '';
        color            : #09386d;
        position         : absolute;
        bottom           : 10px;
        font-size        : 15.2px;
        text-align       : right;
        margin-top       : .2em;
        margin-bottom    : 0;
        font-family      : MrJeeves;
        font-weight      : 800;
        text-shadow      : 0px 0px 5px white;
    }
    
    .phb:nth-child(even) p.foot{
        left             : 78px;
    }
    
    .phb:nth-child(odd) p.foot{
        right            : 78px;
    }
    
    /* The footer on the left (the back button) */
    .footerBack {
        position             : absolute;
        bottom               : 1.2em;
        left                 : 3.8em;
        width                : 20%;
        padding-top          : 0.5em;
        padding-bottom       : 0.5em;
        text-align           : left;
        text-indent          : 0;
        text-decoration      : none;
        font-size            : 16pt;
        font-family          : 'Bookmania';
        font-weight          : bold;
        font-variant         : small-caps;
        color                : #293f50;
    }
    
    /* The middle footer (the line) */
    .footerMiddle {
        position             : absolute;
        bottom               : 1.5em;
        left                 : 3.7em;
        right                : 3.7em;
        height               : 1em;
        border-bottom        : 3px solid #293f50;
        text-align           : center;
        text-indent          : 0;
        font-size            : 16pt;
        font-family          : 'Bookmania';
        font-weight          : bold;
        font-variant         : small-caps;
        color                : #293f50;
        z-index              : -10;
    }
    
    /* The footer on the right (the contents button) */
    .footerContents {
        position             : absolute;
        bottom               : 1.2em;
        right                : 3.8em;
        width                : 20%;
        padding-top          : 0.5em;
        padding-bottom       : 0.5em;
        text-align           : right;
        text-indent          : 0;
        text-decoration      : none;
        font-size            : 16pt;
        font-family          : 'Bookmania';
        font-weight          : bold;
        font-variant         : small-caps;
        color                : #293f50;
    }
    
    /* Hide the footer on some pages */
    .phb#p1:after, .phb#p6:after, .phb#p8:after {
        display          : none;
    }
    /* End Footers */
    
    /* Page Number */
    .phb .pageNumber{
        position         : absolute;
        bottom           : 29px;
        width            : 48px;
        text-align       : center;
        color            : black;
        text-shadow      : 0px 0px 13px white;
        font-size        : 16px;
        font-weight      : 1000;
    }
    
    .phb:nth-child(even) .pageNumber{
        left             : 17px;
        transform        : rotate(13.5deg);
    }
    
    .phb:nth-child(odd) .pageNumber{
        right            : 17.3px;
        transform        : rotate(-13.5deg);
    }
    
    .phb .pageNumber.auto{
        position         : absolute;
        bottom           : 29px;
        width            : 48px;
        text-align       : center;
        color            : black;
        text-shadow      : 0px 0px 13px white;
        font-size        : 17px;
        font-weight      : 1000;
    }
    /* End Page Number */
</style>

<img src='https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/13f4ad50-d545-4661-bc13-0579425fcf87/d7voduu-ad05c071-d3ec-4437-af61-bc382556af5a.png/v1/fill/w_1600,h_901,q_80,strp/thest_by_tomprante_d7voduu-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9OTAxIiwicGF0aCI6IlwvZlwvMTNmNGFkNTAtZDU0NS00NjYxLWJjMTMtMDU3OTQyNWZjZjg3XC9kN3ZvZHV1LWFkMDVjMDcxLWQzZWMtNDQzNy1hZjYxLWJjMzgyNTU2YWY1YS5wbmciLCJ3aWR0aCI6Ijw9MTYwMCJ9XV0sImF1ZCI6WyJ1cm46c2VydmljZTppbWFnZS5vcGVyYXRpb25zIl19.Maya-xI_nTWjYPYHYDHduTo_vTxiscACvjYtuTS5Dec' class='cover-image' style="left:-760px;width:2000px;height:1125px" id="top" />

<div class='cover-diamond' style="margin-top:6.5em"></div>

<div class='cover-header' style="margin-top:.8em;line-height:1em">Advanced<br>GM Binder Styling Reference</div>

<div class='cover-splotch'></div>

<div class='cover-footer'>A document that shows off what GM Binder can do when you use HTML and CSS</div>

\pagebreak

<h1 id="introduction">Introduction</h1>

## Preface

I wrote this guide to provide some advanced formatting tips and tricks to those who want or need to get that extra little bit of fanciness and functionality into their documents. This document assumes you are familiar with the general ins-and-outs of using GM Binder, in addition to the content covered in Rhaenon's [GM Binder Styling Reference](https://www.gmbinder.com/share/-L0WUSjJyFHG7PDyIFta). If you're not, then that's still ok! There may be terms or content covered that you're unfamiliar with, but don't fret - practice some things and you'll get there!

It may also help if you have a reasonable understanding of HTML and CSS (as these languages are used throughout this document).

<h2 id="contents">Contents</h2>

<div class='toc'>

  - [<span>2</span><span>Introduction</span>](#introduction)
  - [<span>2</span><span>Contents</span>](#contents)
  - [<span>2</span><span>Credits</span>](#credits)
  - [<span>3</span><span>Let's Get Fancy</span>](#lets-get-fancy)
    - [<span>3</span><span>Back Buttons</span>](#back-buttons)
    - [<span>3</span><span>Custom Fonts</span>](#custom-fonts)
    - [<span>3</span><span>Fancy Page Numbers</span>](#fancy-page-numbers)
    - [<span>4</span><span>Fancy Table Colours</span>](#fancy-table-colours)
    - [<span>5</span><span>Fancy Table Content</span>](#fancy-table-content)
    - [<span>5</span><span>Links to Sections</span>](#links-to-sections)
    - [<span>6</span><span>Scale Images to Fit On the Page</span>](#scale-images-to-fit)
    - [<span>7</span><span>Scale Images to Hang Off the Page</span>](#scale-images-to-hang-off)
  - [<span>8</span><span>Conclusion</span>](#conclusion)

</div>

\columnbreak

<h3 id="credits">Credits</h3>

**Written by** *[Raspilicious](https://reddit.com/user/raspilicious)*.

___
**Special thanks** to *[Rhaenon](https://reddit.com/user/rhaenon)*, *[CobaltZephyr](https://reddit.com/user/CobaltZephyr)*, *[Iveld](https://reddit.com/user/iveld)*, *[metaBot](https://reddit.com/user/metaBot)* and *[SwordMeow](https://reddit.com/user/swordmeow)* for helping work on and create the original [GM Binder Styling Reference](https://www.gmbinder.com/share/-L0WUSjJyFHG7PDyIFta).

___
**Theme:** *[Discord of Many Things & /r/UnearthedArcana Theme](https://www.gmbinder.com/share/-LGLxo9KaSGhvTG1NE7O/-Lp_kbluv3gY9jqD3lfZ)* by Eiti3.

___
**Cover art:** *[Thest](https://www.deviantart.com/tomprante/art/Thest-476469030)* by TomPrante.

___
**Page 7 art:** *[White dragon_2014](https://www.deviantart.com/markus-art-design/art/White-dragon-2014-450945927)* by Markus-Art-Design.

___
**Back cover art:** *[Reflections](https://www.deviantart.com/markus-art-design/art/REFLECTIONS-390960432)* by Markus-Art-Design.

<a class="footerBack" href="#" onclick="history.back()">Back</a>

<a class="footerContents" href="#contents">Contents</a>

<div class="footerMiddle"></div>

\pagebreakNum

<h1 id="lets-get-fancy">Let's Get ~Fancy~</h1>

## 

You'll find a variety of code snippets here. You can use most of them between two `<style>` tags - usually placed at the start or end of your document - and some in your document's body text.

If you are using them in your document's style tags, try not to spread them throughout your document unless you need to; you may have a hard time trying to work out why your style is not working only to find that you've redefined it somewhere else in your document. The latest `<style>` tag always overwrites previous ones, so even if you've placed it at the end of your document, your entire document will follow that style.

<h3 id="back-buttons">Back Buttons</h3>

You can add functionality to your documents by using the `href` and `id` tags. A `href` is a kind of hyperlink that jumps the user's page to the specified `id` tag when it is clicked on. It's a similar concept to a Bookmark in a PDF. We can use this functionality to allow users to navigate around documents quickly and with but a few clicks.

A back button will allow users to jump backwards one step in their web browser's history. It works great in most web browsers, but unfortunately not in a PDF, because PDFs don't track navigation history.

Use this snippet to create a back button:

```
<a href="#" onclick="history.back()">Back</a>
```

To get even more fancy, you can assign this to a particular class in your `<style>` - then whenever you use it throughout your document, every instance of that style will be a back button! Pop this in your `<style>` to see it in action:

```
<a class="MyClass" href="#" onclick="history.back()"></a>
```

\columnbreak

<h3 id="custom-fonts">Custom Fonts</h3>

If you want to add extra fanciness to your documents in the form of fonts, you can use [Google Fonts](https://fonts.google.com/) to do so. Put this in your `<style>`, filling in the font that you want.

```
@import url('https://fonts.googleapis.com/css?family=Montserrat');
```

Now, you can use Google fonts by adding the following to your `.phb`, `.h1`, `.footnote` etc. tags:

```
font-family: 'Montserrat', sans-serif;
```

If you want to use a font that isn't on Google Fonts, [this guide](https://www.gmbinder.com/share/-LhNzcwJeRzNIlrwrlc9) by Tsuramah covers it very well. Check it out!

<h3 id="fancy-page-numbers">Fancy Page Numbers</h3>

Sometimes, you may want to get fancy with your page numbers. You can center your page number with this snippet:

```
.phb .pageNumber {
    position   : center;
    left       : 0px;
    right      : 0px;
    bottom     : 1em;
    width      : 100%;
    text-align : center;
}
```

...and add content before or after it using this snippet:

```      
.phb .pageNumber:before {
    content : "✦ ";
}

.phb .pageNumber:after {
    content : " ✦";
}
```

You can also use this snippet to center text in general:

```
<div class='wide' style="text-align: center" id="top">
```

<a class="footerBack" href="#" onclick="history.back()">Back</a>

<a class="footerContents" href="#contents">Contents</a>

<div class="footerMiddle"></div>

\pagebreakNum

<h3 id="fancy-table-colours">Fancy Table Colours</h3>

Tables can be formatted in many fancy ways. When you use HTML to make a table you can easily change its colour - even for multiple tables on the same page or multiple cells in the same table.

##### Default Markdown Table

| d8  | Loot |
|:---:|:-----------:|
|  1  | 100gp |
|  2  | 200gp |
|  3  | 300gp |
|  4  | 400gp |
|  5  | 500gp |
|  6  | 600gp |
|  7  | 700gp |
|  8  | 1000gp |

___
The table above uses the format you would probably be most familiar with when using GM Binder: markdown (a text formatting language). Markdown tables use colours specified by your document's theme, or colours from Part 1 of the *Player's Handbook* if you don't specify a theme at all.

##### PHB-Coloured HTML Table

<table style="width:100%; text-align:center">
  <tr style="background-color:transparent; line-height:1.35em">
    <th style="text-align:center">d8</th>
    <th style="text-align:center">Loot</th>
  </tr>
  <tr style="background-color:#e0e5c1">
    <td>1</td>
    <td>100gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">2</td>
		<td style="background-color:transparent">200gp</td>
  </tr>
  <tr style="background-color:#e0e5c1">
    <td>3</td>
    <td>300gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">4</td>
		<td style="background-color:transparent">400gp</td>
  </tr>
  <tr style="background-color:#e0e5c1">
    <td>5</td>
    <td>500gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">6</td>
		<td style="background-color:transparent">600gp</td>
  </tr>
  <tr style="background-color:#e0e5c1">
    <td>7</td>
    <td>700gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">8</td>
		<td style="background-color:transparent">1000gp</td>
  </tr>
</table>

___
The table above is constructed using HTML and is styled to use the same colours as you'd see in Part 1 of the *Player's Handbook*. You can check out the code in the page source, but if you'd like some more information on how to format a table using HTML (such as what `<tr>`, `<th>` and `<td>` are and how to use them), I recommend checking out the [HTML Tables](https://www.w3schools.com/html/html_tables.asp) page on [w3schools.com](w3schools.com). W3schools is a website and superb reference and resource for learning HTML and CSS.

The tables on the right are simply additional examples of what you can do with HTML tables.

> *Forgive me for going up to d14 on the Rainbow HTML Table; I felt I had to use all the colours from the ROYGBIV spectrum! Just pretend that you are rolling 2d4 + 1d6 for your treasure. :P*

\columnbreak

##### More Coloured HTML Tables

<table style="width:100%; text-align:center">
  <tr style="background-color:transparent; line-height:1.35em">
    <th style="text-align:center">d8</th>
    <th style="text-align:center">Loot</th>
  </tr>
  <tr style="background-color:#deb1b5">
    <td>1</td>
    <td>100gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">2</td>
		<td style="background-color:transparent">200gp</td>
  </tr>
  <tr style="background-color:#deb1b5">
    <td>3</td>
    <td>300gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">4</td>
		<td style="background-color:transparent">400gp</td>
  </tr>
  <tr style="background-color:#deb1b5">
    <td>5</td>
    <td>500gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">6</td>
		<td style="background-color:transparent">600gp</td>
  </tr>
  <tr style="background-color:#deb1b5">
    <td>7</td>
    <td>700gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">8</td>
		<td style="background-color:transparent">1000gp</td>
  </tr>
</table>

<table style="width:100%; text-align:center">
  <tr style="background-color:transparent; line-height:1.35em">
    <th style="text-align:center">d8</th>
    <th style="text-align:center">Loot</th>
  </tr>
  <tr style="background-color:#b1deb1">
    <td>1</td>
    <td>100gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">2</td>
		<td style="background-color:transparent">200gp</td>
  </tr>
  <tr style="background-color:#b1deb1">
    <td>3</td>
    <td>300gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">4</td>
		<td style="background-color:transparent">400gp</td>
  </tr>
  <tr style="background-color:#b1deb1">
    <td>5</td>
    <td>500gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">6</td>
		<td style="background-color:transparent">600gp</td>
  </tr>
  <tr style="background-color:#b1deb1">
    <td>7</td>
    <td>700gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">8</td>
		<td style="background-color:transparent">1000gp</td>
  </tr>
</table>

<table style="width:100%; text-align:center">
  <tr style="background-color:transparent; line-height:1.35em">
    <th style="text-align:center">d8</th>
    <th style="text-align:center">Loot</th>
  </tr>
  <tr style="background-color:#b1d7de">
    <td>1</td>
    <td>100gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">2</td>
		<td style="background-color:transparent">200gp</td>
  </tr>
  <tr style="background-color:#b1d7de">
    <td>3</td>
    <td>300gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">4</td>
		<td style="background-color:transparent">400gp</td>
  </tr>
  <tr style="background-color:#b1d7de">
    <td>5</td>
    <td>500gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">6</td>
		<td style="background-color:transparent">600gp</td>
  </tr>
  <tr style="background-color:#b1d7de">
    <td>7</td>
    <td>700gp</td>
  </tr>
  <tr style="background-color:transparent">
		<td style="background-color:transparent">8</td>
		<td style="background-color:transparent">1000gp</td>
  </tr>
</table>

##### Rainbow HTML Table

<table style="width:100%; text-align:center">
    <tr style="background-color:transparent; line-height:1.35em">
	    <th style="text-align:center">d14</th>
		<th style="text-align:center">Loot</th>
	</tr>
	<tr style="background-color:lightcoral">
		<td>1</td>
		<td>100gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">2</td>
		<td style="background-color:transparent">200gp</td>
	</tr>
	<tr style="background-color:darksalmon">
		<td>3</td>
		<td>300gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">4</td>
		<td style="background-color:transparent">400gp</td>
	</tr>
	<tr style="background-color:khaki">
		<td>5</td>
		<td>500gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">6</td>
		<td style="background-color:transparent">600gp</td>
	</tr>
	<tr style="background-color:lightgreen">
		<td>7</td>
		<td>700gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">8</td>
		<td style="background-color:transparent">1,000gp</td>
	</tr>
	<tr style="background-color:skyblue">
		<td>9</td>
		<td>2,000gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">10</td>
		<td style="background-color:transparent">3,500gp</td>
	</tr>
	<tr style="background-color:mediumslateblue">
		<td>11</td>
		<td>6,000gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">12</td>
		<td style="background-color:transparent">10,000gp</td>
	</tr>
	<tr style="background-color:orchid">
		<td>13</td>
		<td>15,000gp</td>
	</tr>
	<tr style="background-color:transparent">
		<td style="background-color:transparent">14</td>
		<td style="background-color:transparent">30,000gp</td>
	</tr>
</table>

<a class="footerBack" href="#" onclick="history.back()">Back</a>

<a class="footerContents" href="#contents">Contents</a>

<div class="footerMiddle"></div>

\pagebreakNum

<h3 id="fancy-table-content">Fancy Table Content</h3>

Tables can be used for more than just standard text. Try out putting a class in a table's cell to see what happens!

I have used `<div class="descriptive">` in some cells of the following table, but as you can see the cells don't have an equal width. This is because there is much more text in the left column than the right, so GM Binder averages it out over the two columns. Normally this is fine, and we could leave it as so...

##### DC 12 Wisdom (Perception) Check
| | |
|:----:|:-------------:|
| **Success** | **Failure** |
| <div class='descriptive' style="width:100%">**DM:** You spot leaves and a rope lying on the path ahead. Stopping the convoy, you tell them this is a snare trap. There is a loop of rope on the ground leading to a weighted log that hangs on the lowermost branch of a tree just off the path.</div>  | <div class='descriptive' style="width:100%">**DM:** You feel a snap underfoot and the ground beneath your feet start to shift. Quick - roll a Dexterity saving throw!</div> |

...but let's see what it looks like if we make the two columns equal in width.

##### DC 12 Wisdom (Perception) Check
<table style="width:100%">
  <tr>
    <td style="font-weight:bold;text-align:center;width:50%">Success</td>
    <td style="font-weight:bold;text-align:center;width:50%">Failure</td>
  </tr>
  <tr>
    <td><div class='descriptive' style="height:12.6em"><b>DM:</b> You spot leaves and a rope lying on the path ahead. Stopping the convoy, you tell them this is a snare trap. There is a loop of rope on the ground leading to a weighted log that hangs on the lowermost branch of a tree just off the path.</div></td>
    <td><div class='descriptive' style="height:12.6em"><b>DM:</b> You feel a snap underfoot and the ground beneath your feet start to shift. Quick - roll a Dexterity saving throw!</div></td>
  </tr>
</table>

___
The second table above is defined using HTML. I've done this to show that a) you can do it, and b) that you can add extra fanciness in tables by doing so (such as in this particular example where I have set the column's width).

> *This looks neat in some ways, but that depends on your document. If you have many tables in your document that use two cells like the one above, it may be very useful to be able to make their width equal on each side; at the least, it will be easier to skim down and quicky find something you're looking for if you have a whole column of them.*

\columnbreak

<h3 id="links-to-sections">Links to Sections</h3>

Add an `id` tag to a heading (or word, or anything, really) to allow you to jump to it with a single click from another element.

```
<h3 id="items">Items</h3>
```

Once you have specified an `id`, you can do this:

```
<a href=#items>Click to go to Items!</a>
```

You don't have to use exactly the same `#tag` as what is written in the heading, but it will make it easier for readers (and yourself) to understand what is happening if you keep them similar. Using `#tag7` to go to a heading called "Armies" is just lazy. Don't be lazy!

> *It's a good idea if you're using tags to have `id="top"` at the start of your document and `id="contents"` on your contents page to quickly get around if you need to.*

<a class="footerBack" href="#" onclick="history.back()">Back</a>

<a class="footerContents" href="#contents">Contents</a>

<div class="footerMiddle"></div>

\pagebreakNum

<img src='https://www.gmbinder.com/images/QHtLOiG.jpg' style='position:absolute;bottom:0px;right:0px;width:100%;height:100%;mix-blend-mode:multiply;' />

<div style='margin-top:800px;'></div>

<div class="wide">

<div class="descriptive">

<h3 id="scale-images-to-fit">Scale Images to Fit on the Page</h3>

You can make an image (such as the border art on this page) fill a page to its exact size. We can use this code to do so:

```
<img src="https://www.gmbinder.com/images/QHtLOiG.jpg" style="position:absolute; bottom:0px; right:0px; width:100%; height:100%; mix-blend-mode:multiply" />
```

The code above anchors an image to the bottom-right of the page and sets its width and height to 100% of the page. It also uses `mix-blend-mode:multiply` to blend the image with the page background so that it becomes textured and looks like it is part of the page. Without it, the image seems to float above the page.

</div>

</div>

\pagebreak

<img src='https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/76c9a119-c2f6-4c62-8ac4-3948ae81fef7/d7ghc3r-08697989-11d2-47ba-ba2f-a1d12382e569.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7InBhdGgiOiJcL2ZcLzc2YzlhMTE5LWMyZjYtNGM2Mi04YWM0LTM5NDhhZTgxZmVmN1wvZDdnaGMzci0wODY5Nzk4OS0xMWQyLTQ3YmEtYmEyZi1hMWQxMjM4MmU1NjkuanBnIn1dXSwiYXVkIjpbInVybjpzZXJ2aWNlOmZpbGUuZG93bmxvYWQiXX0.lxkOk0Gpb4l4vVHeUfL5ayiGXpX_heI46T0CqjoANHY' style='position:absolute;bottom:0px;right:-210px;height:110%;mix-blend-mode:multiply;' />

<div class="wide">

<div style='margin-top:640px;'></div>

<div class="descriptive">

<h3 id="scale-images-to-hang-off">Scale Images to Hang off the Page</h3>

The image on this page is much larger than the page and if we fill it to exactly the right size, it will appear squished. In this case, we want the character to fill the majority of the page but don't mind if the rest of the image hangs off the page. Using the code at the bottom of this box, we do the following things:
- We force the image to 'stick' to a position on the page by using `position:absolute` (as opposed to `position:relative`, which allows it to move along with other objects on the page).
- We use `bottom:0px` to position the bottom of the image at the bottom of the page and `right:-210px` to move the image to the left, resulting in our character being positioned near the middle of the page.
- We scale the image up to fill the page height by using `height:100%`. The left and right edges of the image now 'hang' off the edges of the page, but that's fine because in this case we only care about the character on the image.
- Lastly, we apply `mix-blend-mode: multiply` to the image so it looks like it's part of the page.

Here's the code to achieve this:

```
<img src='Your Source Here' style='position:absolute; bottom:0px; right:-210px;         height:110%; mix-blend-mode:multiply'/>
```

</div>

</div>

<a class="footerBack" href="#" onclick="history.back()">Back</a>

<a class="footerContents" href="#contents">Contents</a>

<div class="footerMiddle"></div>

\pagebreakNum

<img src='https://images-wixmp-ed30a86b8c4ca887773594c2.wixmp.com/f/76c9a119-c2f6-4c62-8ac4-3948ae81fef7/d6grn00-b1a9ae6d-12e1-441d-935c-a6407ad349a3.jpg/v1/fill/w_1024,h_2187,q_75,strp/reflections_by_markus_art_design_d6grn00-fullview.jpg?token=eyJ0eXAiOiJKV1QiLCJhbGciOiJIUzI1NiJ9.eyJzdWIiOiJ1cm46YXBwOjdlMGQxODg5ODIyNjQzNzNhNWYwZDQxNWVhMGQyNmUwIiwiaXNzIjoidXJuOmFwcDo3ZTBkMTg4OTgyMjY0MzczYTVmMGQ0MTVlYTBkMjZlMCIsIm9iaiI6W1t7ImhlaWdodCI6Ijw9MjE4NyIsInBhdGgiOiJcL2ZcLzc2YzlhMTE5LWMyZjYtNGM2Mi04YWM0LTM5NDhhZTgxZmVmN1wvZDZncm4wMC1iMWE5YWU2ZC0xMmUxLTQ0MWQtOTM1Yy1hNjQwN2FkMzQ5YTMuanBnIiwid2lkdGgiOiI8PTEwMjQifV1dLCJhdWQiOlsidXJuOnNlcnZpY2U6aW1hZ2Uub3BlcmF0aW9ucyJdfQ.3nLLbC3ccuK-ApHYho-aAusUWF5xPw9N_KokiHOaiX0' class='cover-image' style="width:551px;height:1176px;left:350px" id="conclusion" />

<div class='back-cover-image' style="height:100%;background-size:cover" id="credits"></div>

<div style='margin-top:20px;'></div>

<div class='back-cover-header'>

Make your

documents

~ fancy ~

</div>

<div class='back-cover-text'>

People love to see beautiful documents, but beautiful documents with extra fanciness and functionality? What a great idea.

Use this document to help you imbue some HTML and CSS magic into your documents, and you may even find out by the end of it that you've learned some programming. Huzzah!

</div>

<div class='back-cover-diamond' style='top: 679px;'></div>

<div style='margin-top:35px;'></div>

<div class='back-cover-close'>

When you're ready to share with the community, don't forget to mark your document as public so people can find it in the [GM Binder Search](https://www.gmbinder.com/search)

</div>

<div class='back-cover-logo'></div>

<div class='back-cover-logo-link'>

[WWW.GMBINDER.COM](https://www.gmbinder.com)

</div>
