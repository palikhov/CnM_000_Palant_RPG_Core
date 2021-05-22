<style>
.phb div.credit {
  width: 100%;
  font-family: ScalySans;
  text-align: right;
}

.phb div.signature {
  text-align: right;
  margin-bottom: .2em;
  font-family: ScalySansSmallCaps;
  font-size: .423cm;
  font-weight: 900
}

.phb div.spelldc {
  font-family: ScalySans;
  font-size: 110%;
  text-align: center;
}

.phb div.story::first-line {
  font-style: none;
  font-family: ScalySansSmallCaps;
  font-size: 110%;
}

.phb div.spellList.narrow {
    column-span: none;
    column-count: 2;
}

.phb .left { text-align: left; }
.phb .center { text-align: center; }
.phb .right { text-align: right; }
.phb .justify { text-align: justify; }
.phb .nowrap { white-space: nowrap; }
</style>

# Stay Classy

<div class='signature'>by Alice Witchfire</div>

### What is this?
A collection of CSS classes that can be used with any GMBinder theme (shown here using the UA theme). Created by Alice Witchfire.

### How to Use
1. Disable 'Use Default GMB Theme' for your document, otherwise these won't work.
2. Copy and paste the source code into your document.
3. Apply the appropriate class (or classes) to your divs. You can use these alone or add them to existing class lists.

```
<div class='descriptive story credit'> Here be text weary traveler! </div>
```

### Source Code
Copy and paste the following into your document. It won't steal your credit card number, I swear.

```
<style>
.phb div.credit{width:100%;font-family:ScalySans;text-align:right}.phb div.signature{text-align:right;margin-bottom:.2em;font-family:ScalySansSmallCaps;font-size:.423cm;font-weight:900}.phb div.spelldc{font-family:ScalySans;font-size:110%;text-align:center}.phb div.story::first-line{font-style:none;font-family:ScalySansSmallCaps;font-size:110%}.phb div.spellList.narrow{column-span:none;column-count:2}.phb .left{text-align:left}.phb .center{text-align:center}.phb .right{text-align:right}.phb .justify{text-align:justify}.phb .nowrap{white-space:nowrap}
</style>
```

\columnbreak

### Quick Reference

#### Credits
```
Right aligned:
<div class='credit'>...</div>

Center aligned:
<div class='credit center'>...</div>

Bold and brash:
<div class='signature'>...</div>
```

#### Spell Calculations
```
<div class='spelldc'>...</div>
```

#### First Line Fancy
```
Normal:
<div class='story'>...</div>

Descriptive (Stories):
<div class='descriptive story'></div>

Story credit:
<div class='story credit'></div>
```

#### Single Line (no wrap)
```
<div class='nowrap'></div> 
<span class='nowrap'></span> 

For tables:
| <span class='nowrap'></span> |
```

#### Narrow Spell List
```
<div class='spellList narrow'></div>
```

\pagebreak

### Examples

#### Credit
A quick way to add some credit text.

<div class='credit'>&mdash; Albert Einstein</div>

```
<div class='credit'>&mdash; Albert Einstein</div>
```

#### Signature
This is essentially h4 but right aligned. It's intended as a more prominent version of credit. 

<div class='signature'>Albert Einstein</div>

```
<div class='signature'>Albert Einstein</div>
```

#### Spell DC
This makes the text inside it match the spell save calculations found in the PHB. I recommend bolding the first part, but you need two lines after the opening tag for it to work.

<div class='spelldc'>

**Spell save DC =** 8 + your Proficiency Bonus + your Hunger modifier

</div>

```
<div class='spelldc'>

**Spell save DC =** 8 + your Proficiency Bonus + your Hunger modifier

</div>
```

#### Story (Default)
This is good for stories and quotes. It makes the first line of text look all fancy schmancy. It can be found occasionally throughout the PHB, mostly on stories and short blurbs. I recommend using it with the 'descriptive' and 'credit' classes.


<div class='story'> Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, 'and what is the use of a book,' thought Alice 'without pictures or conversation?' </div>

```
<div class='story'> Alice was beginning to... </div>
```

\columnbreak

#### Story (Descriptive)
This is how it appears when used in a descriptive block. You can apply it to the credits again to make the credits fancy.

<div class='descriptive story'> Alice was beginning to get very tired of sitting by her sister on the bank, and of having nothing to do: once or twice she had peeped into the book her sister was reading, but it had no pictures or conversations in it, 'and what is the use of a book,' thought Alice 'without pictures or conversation?'

<div class='story credit'>

&mdash; Lewis Carroll  
Alice in Wonderland
</div>
</div>

```
<div class='descriptive story'> Alice was beginning to...

<div class='story credit'>

&mdash; Lewis Carroll  
Alice in Wonderland
</div>
</div>
```

#### Narrow
This is used alongside 'spellList' to reduce it from 4 columns to 2. However, it exhibits strange behavior if you use ```\columnbreak``` inside of it.

<div class='spellList narrow'>

##### Cantrips (0 Level)
- Cantrip A
- Cantrip B
- Cantrip C
- Cantrip D

##### 1st Level
- Spell A
- Spell B
- Spell C
- Spell D

##### 2nd Level
- Spell A
- Spell B
- Spell C
- Spell D

</div>


```
<div class='spellList narrow'> Your spells here </div>
```

\pagebreak

#### Utility Classes
The following classes are meant for utility, and are simply shortcuts for specific CSS properties. They can be used alone or alongside other classes (space separated).

| <div style='width:100px;'>Class</div> | CSS |
|:--|:--|
| left | ```text-align: left;``` |
| center | ```text-align: center;``` |
| right | ```text-align: right;``` |
| justify | ```text-align: justify;``` |
| nowrap | ```white-space: nowrap;``` |

#### The Em-Dash (&mdash;)
Wizards of the Coast uses these very heavily, most notably as placeholders in class tables. The quickest way to add an emdash is to type ```&mdash;```.

| Caster Level | 1st | 2nd | 3rd | 4th | 5th |
|:-:|:-:|:-:|:-:|:-:|:-:|
| 1st | 2 | &mdash; | &mdash; | &mdash; | &mdash; |
| 2nd | 3 | &mdash; | &mdash; | &mdash; | &mdash; |
| 3rd | 4 | 2 | &mdash; | &mdash; | &mdash; |
| 4th | 4 | 3 | &mdash; | &mdash; | &mdash; |
| 5th | 4 | 3 | 2 | &mdash; | &mdash; |

##### Other Useful Escapes
Here are a few other useful escape sequences worth memorizing.

| Sequence | Looks Like | Notes |
|:-:|:--|:--|
| ```&nbsp;``` | No-Break&nbsp;Space | This looks like a normal space but prevents word wrap from wrapping on it. It's good for headers |
| ```&amp;``` | Ampersand (&amp;) | |
| ```&ast;``` | Asterisk (&ast;) | Helps prevent accidental formatting mishaps |
| ```&lt;``` | Less Than (&lt;) | Helps prevent accidental formatting mishaps |
| ```&gt;``` | Greater&nbsp;Than&nbsp;(&gt;) | Helps prevent accidental formatting mishaps |
| ```&dash;``` | Dash (&dash;) | |
| ```&ndash;``` | Daash (&ndash;) | |
| ```&mdash;``` | Daaash (&mdash;) | |


<style>
/* background image*/
 .phb{ background : white;} 
/* Text */
 .phb { font-family: Cambria; font-size: 10,8pt}
 .phb h1+p::first-letter {float:none;font-family:Cambria;font-size:9.84pt;color:#000;line-height:1.3em;font-weight:normal;}
 .phb h4, .phb h3, .phb h2, .phb h1{font-family: Cambria;color: #000;font-weight: normal;}
 .phb h1{font-size:30pt;}
 .phb h2{font-size:21,84pt;}
 .phb h3{font-size:18pt; border-bottom:1pt solid #000}
 .phb h4{font-size:14,88pt;}
 .phb h5{font-family: Calibri;color:#000;font-size: 12pt;font-weight: normal;}
/* Tables */
 .phb table{font-family: Calibri;font-size: 9.84pt;}
 .phb table tbody tr:nth-child(odd){background-color:#f2f2f2;}/*change backing of rows*/
/* Class Table */  
 .phb .classTable{border-image-source: none;border: none;}
 .phb .classTable h5{font-family: Calibri;font-weight: bold;}
 .phb .classTable table tbody tr:nth-child(odd){background-color:#FFF;}
/* Description block */
 .phb .descriptive { padding-left:3px;background-color: #e6e6e6;border-image: none;border: none;font-family: Calibri;}
 .phb .descriptive p{font-size:9.84pt;}
 .phb .descriptive em{font-family:Calibri;}
 .phb .descriptive strong{font-family: Calibri;}
/* Note */
 .phb blockquote{font-family: Calibri;font-size:
 9.84pt;background-color:#e6e6e6;border-width:5px;border-image-outset:5px 0px; box-shadow:0px 1px 5px;}/* Stat Block */
 .phb hr+section blockquote{background: white;border: 3px solid #e6e6e6;box-shadow: none;}
 .phb hr+section blockquote h3{font-family:Calibri;border-bottom:1px solid #000;}
 .phb hr+section blockquote hr+ul{color: #000;}
 .phb hr+section blockquote table{color: #000;}
 .phb hr+section blockquote hr{background-image: url(https://gmbinder.com/images/MS0gM8Z.png)}
/* footer */
 .phb:after{display:none;} 
 .phb .pageNumber{color:#000;font-size:9.84pt;bottom:14mm;right:1.7cm}
 .phb .footnote{color:#000;font-size:9.84pt;bottom:14mm;left:1.7cm;text-align:left;width:600px;}
 .phb:nth-child(even) .pageNumber{left:18.19cm;}
 .phb:nth-child(even) .footnote{left:1.7cm;}
 .phb a{color:black;}
</style>

