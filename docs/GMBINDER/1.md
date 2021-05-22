<style>
@import url('https://fonts.googleapis.com/css?family=Crete+Round');
@import url('https://fonts.googleapis.com/css?family=IM+Fell+French+Canon+SC');

.phb{ 
    background-image: url("https://www.gmbinder.com/images/UCIUXyr.jpg");
    font-family: "Crete Round";
    font-size: 11.8px;
}

.phb:after {
    background-image: url(https://www.gmbinder.com/images/7IKHSzy.png); 
    height:79px; 
    content: "This is unofficial Fan Content permitted under the Fan Content Policy. Not approved/endorsed by Wizards. Portions of the materials used are property of Wizards of the Coast. ©Wizards of the Coast LLC. Homebrew and theme by u/AevilokE (Elias Garoufalias)"; 
    padding-top: 60px; 
    font-size:9px; 
    padding-left:75px;
}

.phb:nth-child(even):after {
    background-image: url(https://www.gmbinder.com/images/IwEAlIs.png); 
    padding-top: 60px; 
    font-size:9px; 
    padding-right:75px;
}


.phb h1 { color:#3A19B8; font-size: 36px;}
.phb h2 { color:#3B1AB9 }
.phb h3 { color:#3C1BBA; border-bottom: 2px solid #aaa; }
.phb h4 { color:#3D1CBB }
.phb h5 { color:black }
.phb blockquote h5 { color:#3E1DBC }
.phb h6 { color:#3D1Cbb; margin-left: 20px; margin-top:5px; margin-bottom:5px; }

.phb blockquote {background-color:#DDDDEE;}

/* .phb hr+section blockquote { border-image:url(https://www.gmbinder.com/images/GaPVUC0.png) 66 round; background-image:url(https://www.gmbinder.com/images/CT6GVCH.png);} */


.phb hr+blockquote {
    background-color:#DDDDE0; border-image:url(https://www.gmbinder.com/images/T7Srh57.png)19; border-image-outset: 9px 0;
}

.phb hr+section blockquote {                         
    border-image:url(https://www.gmbinder.com/images/Z6MPBB2.png) 66 round; background-image:url(https://www.gmbinder.com/images/rz9H9fp.png);
}

.phb hr+section blockquote hr {
    background-image:url(https://www.gmbinder.com/images/NrSEA0H.png)
}

.phb hr+section blockquote hr+ul {color: #55119E;}
.phb hr+section blockquote h3 {color: #55119E; border-bottom: 1px solid #0D1858}
.phb hr+section blockquote table {color: #55119E;}

.phb .classTable {
    border-image-source: url(https://www.gmbinder.com/images/7O0I9Uq.png);
}

.phb table tbody tr:nth-child(odd) {background-color:#DDDDF5}

/*color:#9FAEbb; white footnote*/

.phb .footnote {
    position: absolute;
    bottom: 47px;
    width: 50%;
    color:#D5AF00;
    font-size: 9.7px;
}

.left {
    padding-right: 15px;
    z-index: 1000;
}

.right {
    margin-left: 15px;
}

</style>

# Header1

Lorem ipsum dolor sit amet

## Header2

Lorem ipsum dolor sit amet

### Header3

Lorem ipsum dolor sit amet

#### Header4

Lorem ipsum dolor sit amet

##### Header5

Lorem ipsum dolor sit amet

<br>

<div class="footnote">This footnote was created by u/AevilokE</div>


<div class='classTable'>

##### Class Table
| Level | Proficiency Bonus | Features | Some Modifier |
|:---:|:---:|:---|:---:|
| 1st | +2 | Something | — |
| 2nd | ─ | ─ | — |
| ... | ─  | ─ | ─ |
| 20th | ─ | ─ | ─ |

</div>

<br>

<div class='descriptive'>

##### Description Block
Useful information

</div>

<br>

> ##### Note Block
> Useful Information



\columnbreak

___
> ## Monster Statblock
>*Size, Alignment*
> ___
> - **Armor Class** AC
> - **Hit Points** Hitpoints
> - **Speed** Speed
>___
>|STR|DEX|CON|INT|WIS|CHA|
>|:---:|:---:|:---:|:---:|:---:|:---:|
>|Str (Mod)|Dex (Mod)|Con (Mod)|Int (Mod)|Wis (Mod)|Cha (Mod)|
>___
> - **Saving Throws** saving_throws
> - **Skills** skills
> - **Damage Vulnerabilities** damage_vulnerabilities
> - **Damage Resistances** Resistances
> - **Damage Immunities** Damage_Immunities
> - **Condition Immunities** condition_Immunities
> - **Senses** Senses
> - **Languages** Languages
> - **Challenge** Challenge and Xp
> ___
>
> ### Actions
> ***Multiattack.*** The Creature Name makes Number and type of attacks
>
> ***Ability Description.*** *Attack Style:* Attack Bonus to hit, Reach/Range, one target. *Hit:* Damage Damage Type damage
>
> ***General Ability Description.*** General Attack Description

<br>


##### Table
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
