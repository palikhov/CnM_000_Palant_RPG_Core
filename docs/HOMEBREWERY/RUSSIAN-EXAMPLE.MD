<style>
  .phb{
    width : 210mm;
    height : 297mm;
  }
  
/* #'s */
.phb h6 { color:#FFFFFF; text-shadow: -3px 0 black, 0 1px black, -2px 0 black, 0 -1px black}
  
/* Background */
  .phb{ background-image: url("http://i.imgur.com/UCIUXyr.jpg") }
  .phb{ background-size: cover }

/* Notes */
  .phb blockquote { background-color: #d0dded }
  .phb hr + blockquote tr:nth-child(odd) td {background-color: #FDF1DC;}

/* Tables */
  table tr:nth-child(odd) td {background-color: #98b2d1}
  /* новый - #c3d5eb */
  /* оригинал - #ebcec3 */
  /* новый v2 - #98b2d1*/

/* Footer */
  .phb .pageNumber { color: #7e735c }
  .phb .footnote {
     color: #7e735c;
     font-family: "EB Garamond";
     font-variant: small-caps;
     letter-spacing: 0.02em;}
  .phb:after { background-image:url("https://i.imgur.com/F1CyPqu.png") }
  
  .phb .footnote{
    position   : absolute;
    bottom     : 24px;
    width      : 150px;
    text-align : center;
    }
  .phb:nth-child(even) .footnote{
    left      : 65px;
    }
  .phb:nth-child(odd) .footnote{
    right      : 55px;
    }

  .phb .footnote.auto{
    position   : absolute;
    bottom     : 24px;
    width      : 150px	;
    text-align : center;
    }
  .phb:nth-child(even) .footnote{
    left      : 65px;
    }
  .phb:nth-child(odd) .footnote{
    right      : 55px;
    }

/* Footer for magic items */
  .phb .footnoteMAG {
     color: #7e735c;
     font-family: "EB Garamond";
     font-variant: small-caps;
     letter-spacing: 0.02em;}
  .phb:after { background-image:url("https://i.imgur.com/F1CyPqu.png") }
  .phb .footnoteMAG{
    position   : absolute;
    bottom     : 24px;
    width      : 220px;
    text-align : center;
    }
  .phb:nth-child(even) .footnoteMAG{
    left      : 65px;
    }
  .phb:nth-child(odd) .footnoteMAG{
    right      : 55px;
    }
  
  .phb .footnoteMAG.auto{
    position   : absolute;
    bottom     : 24px;
    width      : 150px	;
    text-align : center;
    }
  .phb:nth-child(even) .footnote{
    left      : 65px;
    }
  .phb:nth-child(odd) .footnote{
    right      : 55px;
    }

/*Fonts*/
  .phb h1 {
    font-family: "EB Garamond";
    font-variant: small-caps;
    letter-spacing: 0.02em; }
  .phb h2 {
    font-family: "EB Garamond";
    font-variant: small-caps;
    letter-spacing: 0.02em; }
  .phb h3 {
    font-family: "EB Garamond";
    font-variant: small-caps;
    letter-spacing: 0.02em; }
  .phb h4 {
    font-family: "EB Garamond";
    font-variant: small-caps;
    letter-spacing: 0.02em; }
  .phb {
    font-family: "Calibri";
    font-size: 12.5px;
	font-weight: 540;
    font-variant: regular;
    letter-spacing: 0.015em; }

/* Statblocks */
  .phb hr + blockquote tr:nth-child(odd) td { background-color: transparent; }
  .phb hr+blockquote {
    background-color: transparent;
    background-image: url(https://i.imgur.com/2fpZqkh.jpg);
    background-position: center center; 
    border-width: 6px;
    border-image: url(https://i.imgur.com/gtHyLi6.png);
    border-image-slice: 20 }

/* Unique page style */
  .phb#p1:after{ display:none; }


/* Fine tables*/
  .toc a {
    color: inherit !important;	/*toc specifically wants black text. This resets the headers*/
  }

  .toc li span:nth-child(2){	/*Allow dot leaders to fill remaining space but not overlap*/
    width: auto;
    overflow: hidden;
    white-space: nowrap;
    display: block;
  }

  .toc li span:nth-child(2):after{
    font-family		: BookSanity;	/*Remove any header styles from dot leaders*/
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    content:
      " ........................................"
      "........................................."
      "........................................."; 
  }
  
  .toc li span:first-child{
    float: right;
    font-family		: BookSanity;	/*Remove any header styles from page numbers*/
    font-size   	: 0.317cm;
    font-weight		: normal;
    color			: black;
    margin-left		: 1px;	/*Leaves a small space between page numbers and dot leaders*/
  }
  
/*Special cases for headings*/    
  .toc li h3 span:nth-child(2):after{
  	content: " ";						/*Remove dot leaders on h3*/
  }
  
  .toc li h3 {
    margin-bottom: 4px !important;		/*Special spacing for h3*/
    margin-top: 10px !important;
    line-height: initial !important;	/*For some reason Multi-line h3 line spacing changed*/
  }
  
  .toc li h3 span:first-child{
  	line-height: 1.8em !important;  	/*Line page numbers up with Multi-line h3 better*/
  }
  
  .toc ul ul {
  	margin-left: 10px !important;		/*Original lists intented too much*/
  }
  
  .toc>ul>li {
    margin-bottom: initial !important;	/*margin for list items needs to be removed or 0*/
  }
  
  
  /* Nice notes*/
  .phb .authornotes {
       color: #800000;
       font-family:Mistral;
       letter-spacing: 0.03em;
       font-size: 12pt
  }
</style>

<img 
src='https://cdnb.artstation.com/p/assets/images/images/010/435/147/large/felipe-fesbra-escobar-mtg-dragon.jpg' 
  style='position:absolute; top:-40px; right:0px; width:100%;
  mix-blend-mode:multiply' />
  `https://www.deviantart.com/000fesbra000/art/Red-Dragon-Mount-733106342`
  
<img 
  src='https://i.imgur.com/rNOAD8A.png' 
  style='position:absolute; top:40px; right:-50px; width:795px;
  filter: grayscale(90%);-webkit-transform: rotate(-20deg);' />

<img 
  src='https://i.imgur.com/pEJl0m5.png' 
  style='position:absolute; top:140px; left:-400px; width:545px;
  filter: grayscale(90%);-webkit-transform: rotate(-15deg);' />

<img 
  src='https://i.imgur.com/pEJl0m5.png' 
  style='position:absolute; top:140px; right:-430px; width:545px;
  filter: grayscale(90%);-webkit-transform: rotate(15deg);' />

<img 
  src='https://i.imgur.com/pEJl0m5.png' 
  style='position:absolute; top:-490px; right:0px; width:545px;
  filter: grayscale(90%);-webkit-transform: rotate(-75deg);' />

<img 
  src='https://i.imgur.com/pEJl0m5.png' 
  style='position:absolute; top:-520px; right:-270px; width:545px;
  filter: grayscale(90%);-webkit-transform: rotate(-50deg);' />

<img 
  src='https://i.imgur.com/6caZrpw.png' 
  style='position:absolute; top:520px; right:0px; width:795px;
  filter: grayscale(90%);' />
  
  

<div style='margin-top:375px'>
## Виверны
</div>

Виверны, обитающие<br>
в разных уголках мира, отличаются<br>
зачастую друг от друга размерами, окраской чешуи, повадками и смертоностностью яда. В Подземье, в Пепельных Пустошах, обитает уникальный подвид виверн - дымчатая виврена

### Дымчатая виврена

Пепельные Пустоши - регион подземья, расположенный неподалёку от Глэкстью, - являются домом для уникальной разновидности виверн, приспособленной к вечной жаре. Выбирающие в качестве гнездища углубления в породе практически под самым потолком высоких пещер, дымчатые виверны высматривают передвигающихся по поверхности одиноких путников или живность.

***Раскалённое дыхание.*** Хоть дымчатые виверны и способны использовать собственное дыхание для атаки существ, нельзя назвать его особо смертоносным - в отличии от потока огня красных драконов, дыхание виверны представляет собой раскалённую смесь дыма и искр, способную не столько поджарить цель, сколько ослепить. Некоторые алхимики дуэргаров, используя чешую или яйца думчатых виверн, способны создать аналог такого дыхания - флягу дымчатого тумана.
 
***Территориальные хищники.*** Несмотря на то, что думчатые виверны обладают интеллектом, чуть большим чем свои нащемные родичи, они всё ещё немногим отличаются от простых животных. Дымчатые виверны занимают определённую территорию, бдительно следя за нарушителями границ. Иногда, дуэргары используют эту особенность для создания "природных" стражей важных маршрутов или точек.


```
```

<div style='margin-top:220px'><br></div>

___
> ## Дымчатая виверна
>*Большой дракон, Без мировоззрения*
> ___
> - **Класс доспеха** 17 (природная броня)
> - **Хиты** 142 (15d12 + 45)
> - **Скорость** 25 фт., карабкаясь 25фт., летая 60фт.
>___
>|  СИЛ  |  ЛОВ  |  ТЕЛ  |  ИНТ  |  МДР  |  ХАР  |
>|:-----:|:-----:|:-----:|:-----:|:-----:|:-----:|
>| 17(+3)| 10(+0)| 18(+4)| 6(-2) | 12(+1)| 6(-2) |
>___
> - **Навыки**  Внимательность +4, Скрытность +7
> - **Сопротивление к урону** огонь
> - **Чувства** Темное зрение 90 фт., Пассивная внимательность 14
> - **Языки** —
> - **Опасноть**  7 (2300 опыта)
> ___
> ### Действия
> ***Мультиатака.*** Виверна совершает две атаки укусом. Во время полета она может использовать когти вместо одной другой атаки.
>
> ***Укус.*** *Рукопашная атака оружием*: +6 к попаданию, досягаемость 10 фт., одно существо. *Попадание:* 10 (2d6 + 3) колющего урона.
>
> ***Когти.*** *Рукопашная атака оружием:* +6 к попаданию, досягаемость 5 фт., одна цель. Попадание: 12 (2d8 + 3) рубящего урона.
>
> ***Дымчатое дыхание (перезарядка 5–6).*** Виверна выдыхает дум и искры пламени 30-фт.ой линией шириной 5 фт. Все существа в этой линии должны совершить спасбросок Ловкости со Сл 15, получая при провале 22 (4d10) огненного урона и становясь ослеплённым до начала своего следующего хода. В случае провала, существо получает только половину урона.
>
> ### Реакции
> ***Дым и искры.*** Если существо выбирает целью своей атаки в ближнем бою виврену, виверна может выдохнуть в него сноп искр. Цель должна совершить спасбросок Телосложения со Сл 15, совершая в случае провала все свои атаки с помехой до начала своего следующего хода.