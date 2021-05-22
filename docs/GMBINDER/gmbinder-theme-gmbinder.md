<style>
    /* hide footer on first page of document */
    .gmb:first-child:after { display: none; }
    
    /* hide footer on last page of document */
    .gmb:last-child:after { display: none; }
    
    p.my-special-text {
        position: absolute;
        top: 35%;
        width: 150px;
        left: 20%;
        background-color: #FF8A00;
        padding: 16px;
        color: #fff;
        border-radius: 8px;
        /* this is important to show the triangle! */
        overflow: visible;
    }
    
    p.my-special-text:after {
        content: '';
        position: absolute;
        display: block;
        width: 0;
        height: 0;
        border-width: 10px;
        border-style: solid;
        border-color: transparent transparent transparent #FF8A00;
        right: -20px;
        top: 28%;
    }
</style>

<img src='/assets/img/gmb_wizard_cover.jpg' class='cover-image' style='height: 1066px;'/>

<div class='cover-diamond'></div>

<div class='cover-header'>Welcome to GM Binder</div>

<div class='cover-splotch'></div>

<div class='cover-footer'>Meet our document theme, then modify the s#*! out of it.</div>

\pagebreak

# Here are the basics:

This is your very first document. The intent is for it to be a resource about creating within GM Binder, as well as a showcase of the possibilities using this platform. On the following pages, you'll see everything our theme is capable of—and we hope you'll like it as much as we do.

## Overview on Creating

GM Binder uses Markdown for its primary content. To learn about Markdown and its supporting syntax, [check this out!](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet)

In addition, GM Binder allows for HTML content within your document. However, "User Beware" warnings apply. Using HTML for things like images and links is pretty safe. However, structured HTML like divs, tables, etc, may have undesired consequences.

## GMBinder Specific
### Page Breaks
* Using `\pagebreak` will result in a page break. Or press `Ctrl+;` or `Cmd+;` to insert this.
* Using `\pagebreakNum` will result in a page break with page number. Or press `Ctrl+'` or `Cnd+'` to insert this.

### Links
* Internal Links - Press Ctrl+Space to get a list of all of your document's headers. Press tab on one to insert the link into your document. ie: [Welcome to your next campaign binder!](#welcome-to-your-next-campaign-binder)
* External Links - Using the standard markdown link syntax with an external URL will result in a link that opens a new tab. ie: [Staff of Darkening](https://www.dndbeyond.com/magic-items/29957-staff-of-anti-thunder-and-darkening)
* If you would like the actual URL to show in your external link, a simple solution is to simply wrap it with < and >. ie: <https://www.gmbinder.com>


### Images
There are a couple ways you can place images. If you would like something positioned like you see on this page, you will need to provide the appropriate styles to do so. For example: 

`<img src='https://www.gmbinder.com/assets/img/bottle.png' style='position:absolute;bottom:45px;right:30px;width:380px; mix-blend-mode:multiply;' />`

If you would like to place an image in-line within your content, simply providing an image tag with an external URL will be sufficient. Do be aware that your images should be sized appropriately for the content.

\columnbreak

### Wrapping to Column Two
Sometimes you want your content in column 1 to be cut short and continue on to column 2. The simplest way to accomplish this is to use:

`\columnbreak`
___
You can also press `Ctrl+.` or `Cnd+.` to insert this.

### Footnotes
This is an example of using html and built in styles to get a desired output.

`<div class='footnote'>Part 1 | Introduction</div>`

<img src='/assets/img/bottle.png' style='position:absolute;bottom:30px;right:120px;width:200px; mix-blend-mode:multiply;' />
<div class='footnote'>Part 1 | Introduction</div>

## Basic Editor Shortcuts

### Find and Replace
* `Ctrl+F` or `Cmd+F` - Find
* `Alt+Ctrl+F` or `Alt+Cmd+F` - Find & Replace

### Editing
* `Ctrl+Z` or `Cmd+Z` - Undo
* `Ctrl+Shift+Z` or `Cmd+Shift+Z` - Redo
* `Ctrl+D` or `Cmd+D` - Remove current line
* `Ctrl+U` - Uppercase current selection
* `Ctrl+Shift+U` - Lowercase current selection

### Content Folding
* `F2` - Fold / Unfold a block of content
* `Ctrl+Cmd+Alt+0` Fold everything
* `Shift+Cmd+Alt+0` UnFold everything

### And Much More...
* `Ctrl+Alt+H` or `Cmd+Alt+H` Shows all Editor Shortcuts

\pagebreak

# Headline 1

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

Lye yala onna en' kemen tanya awra! En!. Lirimaerea mereth en draugrim Yallume Elenya. Amin hiraetha quel undome nai uuvanimo turamin cormamin niuve tenna' ta elea lle au'. Yavannie ram en' ondo mereth en draugrim tanka tel' taurnin. Aman tel' Seldarine ram en' templa Amrun'quessir amin khiluva lle a' gurtha ar' thar.

## Headline 2

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

### Headline 3

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

Lye yala onna en' kemen tanya awra! En!. Lirimaerea mereth en draugrim Yallume Elenya. Amin hiraetha quel undome nai uuvanimo turamin cormamin niuve tenna' ta elea lle au'. Yavannie ram en' ondo mereth en draugrim tanka tel' taurnin. Aman tel' Seldarine ram en' templa Amrun'quessir amin khiluva lle a' gurtha ar' thar.

#### Headline 4

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

\columnbreak

##### Headline 5

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

Lye yala onna en' kemen tanya awra! En!. Lirimaerea mereth en draugrim Yallume Elenya. Amin hiraetha quel undome nai uuvanimo turamin cormamin niuve tenna' ta elea lle au'. Yavannie ram en' ondo mereth en draugrim tanka tel' taurnin. Aman tel' Seldarine ram en' templa Amrun'quessir amin khiluva lle a' gurtha ar' thar.

###### Headline 6

Ho mankoi lle uma tanya amin khiluva lle a' gurtha ar' thar quel lome. Shaalth Nuduin amin panta tangwa. Tampa tanya! Naugrim tula uialtum tenna' san'. Aman tel' Seldarine aa' menle nauva calen ar' ta hwesta e' ale'quenle uuma dela amin uuma malia. Gorgaerea rwalaerea atost en' entula orme amin autien rath.

Lye yala onna en' kemen tanya awra! En!. Lirimaerea mereth en draugrim Yallume Elenya. Amin hiraetha quel undome nai uuvanimo turamin cormamin niuve tenna' ta elea lle au'. Yavannie ram en' ondo mereth en draugrim tanka tel' taurnin. Aman tel' Seldarine ram en' templa Amrun'quessir amin khiluva lle a' gurtha ar' thar.

### Type Faces
* **Bold**
* *Italics*
* ~~Strikethrough~~
* ^Super^
* <sup>SuperScript</sup>
* <sub>SubScript</sub>
* [Internal Link](https://www.gmbinder.com)
* [External Link](https://www.reddit.com/r/gmbinder)

1. Item 1
2. Item 2
3. Item 3

* Item 1
* Item 2
* Item 3

<div class="footnote">
Part 2 | Elements
</div>

\pagebreakNum

<div class='classTable'>

##### Class Block Narrow
| Level | Proficiency Bonus | Features | Some Modifier |
|:---:|:---:|:---|:---:|
| 1st | +2 | Something | — |
| 2nd | ─ | ─ | — |
| ... | ─  | ─ | ─ |
| 20th | ─ | ─ | ─ |

</div>

> ##### Catchy Title
> Useful Information that may go longer than expected. It seems this does a good job of expanding thoguh.

<div class='descriptive'>
 
##### Catchy Title
Useful information that may go longer.
 
</div>

## Class Features
As a class_name, you gain the following class features
#### Hit Points
___
- **Hit Dice:** 1d10 per class_name level
- **Hit Points at 1st Level:** something
- **Hit Points at Higher Levels:** something_higher

#### Proficiencies
___
- **Armor:** armor
- **Weapons:** weapons
- **Tools:** tools

___
- **Saving Throws:** saving_throws
- **Skills:** Choose two from skills

#### Equipment
You start with the following equipment, in addition to the equipment granted by your background:
- *(a)* a item1 or *(b)* item2

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

\columnbreak

<div style='column-count:2'>

| d8  | Loot |
|:---:|:-----------:|
|  1  | 100gp |
|  2  | 200gp |
|  3  | 300gp |
|  4  | 400gp |

| d8  | Loot |
|:---:|:-----------:|
|  5  | 500gp |
|  6  | 600gp |
|  7  | 700gp |
|  8  | 1000gp |

</div>

#### Spell Name
*Spell Type*
___
- **Casting Time:** Casting Time
- **Range:** Range
- **Components:** V, S
- **Duration:**  Duration

A description bursts from the caster's fingers and spreads at the speed of the reader's comprehension.



___
> ## Monster Name
>*Size, Alignment*
> ___
> - **Armor Class** AC
> - **Hit Points** Hitpoints
> - **Speed** Speed
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|Str (+Mod)|Dex (+Mod)|Con (+Mod)|Int (+Mod)|Wis (+Mod)|Cha (+Mod)|
>___
> - **Condition Immunities** Some
> - **Senses** Senses
> - **Languages** Languages
> - **Challenge** Senses
> ___
>
> ### Actions
> ***Ability Description.*** *Attack Style:* +4 to hit, reach 5 ft., one target. *Hit* 5 (1d6 + 2)

<div class="footnote">
Part 2 | Elements
</div>

\pagebreakNum

___
___
> ## Monster Name
>*Size, Alignment*
> ___
> - **Armor Class** AC
> - **Hit Points** Hitpoints
> - **Speed** Speed
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|Str (+Mod)|Dex (+Mod)|Con (+Mod)|Int (+Mod)|Wis (+Mod)|Cha (+Mod)|
>___
> - **Condition Immunities** Some
> - **Senses** Senses
> - **Languages** Languages
> - **Challenge** Senses
> ___
>
> ### Actions
> ***Ability Description.*** *Attack Style:* +4 to hit, reach 5 ft., one target. *Hit* 5 (1d6 + 2)


<div class='spellList'>

##### Cantrips (0 Level)
- Cantrip A
- Cantrip B
- Cantrip C

##### 1st Level
- Spell A
- Spell B
- Spell C

##### 2nd Level
- Spell A
- Spell B
- Spell C

\columnbreak

##### 3rd Level
- Spell A
- Spell B
- Spell C

##### 4th Level
- Spell A
- Spell B
- Spell C

##### 5th Level
- Spell A
- Spell B
- Spell C

\columnbreak

##### 6th Level
- Spell A
- Spell B
- Spell C

##### 7th Level
- Spell A
- Spell B
- Spell C

##### 8th Level
- Spell A
- Spell B
- Spell C

\columnbreak

##### 9th Level
- Spell A
- Spell B
- Spell C

</div>

<div class='classTable wide'>

##### Class Block Wide
| Level | Proficiency Bonus | Features | Cantrips Known | Spells Known | 1st | 2nd | 3rd | 4th | 5th | 6th | 7th | 8th | 9th |
|:---:|:---:|:---|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|:---:|
| 1st | +2 | Something | — | — | — | — | — | — | — | — | — | — | — |
| 2nd | ─ | ─ | — | — | — | — | — | — | — | — | — | — | — |
| ... | ─  | ─ | ─ | ─ | ─ | — | — | — | — | — | — | — | — |
| 20th | ─ | ─ | ─ | ─ | ─ | ─ | ─ | ─ | ─ | — | — | — | — |

</div>

<div class="footnote">
Part 2 | Elements
</div>

\pagebreakNum

<div class='partpage'>

# Part 1
##### A Headline Here

</div>

<div class="footnote">
Part 2 | Elements
</div>

\pagebreak

<div class='pageheader'>

# Part 1
##### An alternative design

<img src='/assets/img/gmb_wizard_cover.jpg' style='position:absolute; top: 0px; left: 0px; height: 1066px;'>

</div>

<p class="my-special-text">Do whatever you want, wherever you want, with the power of CSS!</p>

\pagebreak

<img src='/assets/img/gmb_wizard_cover.jpg' style="position: absolute; top: -10%; right: -10%; width: 80%;" />

<div class='blend-corner-topright'></div>


# Easier Blending

To get a beautiful stained edge on your document images (as seen on this page), utilize the convenient built-in classes for applying blend overlays. Please do note: These classes currently only exist in the default GM Binder theme.

<br/>

### Blend Classes

`blend-half-right`<br/>
`blend-half-left`<br/>
`blend-half-top`<br/>
`blend-half-bottom`<br/>
`blend-corner-topright`<br/>
`blend-corner-topleft`<br/>
`blend-corner-bottomright`<br/>
`blend-corner-bottom-left`<br/>
`blend-onethird-top`<br/>
`blend-onethird-bottom`<br/>
`blend-twothirds-top`<br/>
`blend-twothirds-bottom`<br/>

<br/>

### Usage

As seen in the source of this document, blend classes are best applied to `div` elements following the image you would like to blend — like so:

```
<img src="your-image-source.jpg"/>
<div class="blend-half-right"></div>
```

The above code will ensure you have a parchment background on the right side of your page. Simply swapping the class will allow you to quickly see the variations available.

\columnbreak

<div style="height:650px;">
</div>

## By the way!

If you would like to convert your existing document to this theme, please make sure that any instance of `.phb` is replaced with `.gmb`, which is also the new base class for modifying this theme.

<div class="footnote">
Part 3 | Blending Images
</div>

\pagebreak
 
 
 <div class='back-cover-image'></div>
 <div class='blend-half-right'></div>
 
 <div style='margin-top:20px;'></div>
 
 <div class='back-cover-header'>
 
 Practice
 
 Safe
 
 Homebrewing
 
 </div>
 
 <div class='back-cover-text'>
 
 People love to flex their creative muscles while composing new homebrew content. More often than not, the inspiration for your homebrew comes from another source. Sometimes significantly. Other times just as a spark.
 
 What is important for the community is that you share your sources of inspiration. This back cover can serve as an easy to find, easy to read place for you to do just that.
 
 So go ahead, remove this chunk of copy and tell everyone who inspired you.
 
 Cover Art: [Renae](https://www.gmbinder.com/profile/renae)
 
 </div>
 
 <div class='back-cover-diamond' style='top: 640px;'></div>
 
 <div style='margin-top:35px;'></div>
 
 <div class='back-cover-close'>
 
 When you're ready to share with the community, don't forget to mark your document as public so people can find it in the [GM Binder Search](https://www.gmbinder.com/search)
 
 </div>
 
 <div class='back-cover-logo'></div>
 
 <div class='back-cover-logo-link'>
 
 [WWW.GMBINDER.COM](https://www.gmbinder.com)
 
 </div>
 
 \columnbreak
 
 <div class='back-cover-right'>
 
 ##### More Credits
 
 Maybe you have so many people to give credit to that you need a bit more space. Well, you can use this column to do exactly that!
 
 </div>
 
