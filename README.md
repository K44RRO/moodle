<a href="https://flutter.dev/">
  <h3 align="center">
      <img alt="Flutter" src="https://jasontapar.gnomio.com/pix/moodlelogo.png">
    <p> Course: Creative Web Design 3 </p>
  </h3>
</a>



<h1> Table of Contents </h1>

* [General](#general)
* [CREATE A SIMPLE WEB PAGE](#create-a-simple-web-page)
* [USE ELEMENTS AND ATTRIBUTES](#use-elements-and-attributes)
  * [SELF-CHECK 1.1-1](#self-check-11-1)
  * [SELF-CHECK 1.1-2](#self-check-11-2)
  * [SELF-CHECK 1.1-3](#self-check-11-3)
  * [Task Sheet 1.1-1](#task-sheet-11-1)
  * [SELF-CHECK 1.1-5](#self-check-11-5)
  * [SELF-CHECK 1.1-2](#self-check-11-2)
  * [Collaboration I](#collaboration-i)
  * [Task Sheet 1.1-2](#task-sheet-11-2)
  * [Task Sheet 1.1-3](#task-sheet-11-3)
  * [SVG Project](#svg-project)
  * [Collaboration II](#collaboration-ii)
* [MARKUP A SIMPLE WEB](#markup-a-simple-web)
  * [SELF-CHECK 1.2-1](#self-check-22-1)
  * [SELF-CHECK 1.2-2](#self-check-22-2)
  * [SELF-CHECK 1.2-1](#task-sheet-22-1)
  * [Performance Test](#performance-test)
* [ADD LINKS](#add-links)
  * [SELF-CHECK 1.3-1](#self-check-13-1)
* [ADD IMAGES TO WEB PAGE](#add-images-to-web-page)
  * [SELF-CHECK 1.4-1](#self-check-14-1)
  * [SELF-CHECK 1.4-2](#self-check-14-2)
* [~~CREATE FORMS~~](#create-forms)
* [~~USE CASCADING STYLE SHEET~~](#use-casecading-style-sheet)
* [~~Create document structures~~](#create-document-structures)
* [~~Format Text~~](#format-text)
* [~~Apply colors and backgrounds~~](#apply-colors-and-backgrounds)
* [~~Apply padding, borders, and margin~~](#apply-padding-borders-and-margin)
* [~~Implement floating element~~](#implement-floating-element)
* [~~Apply positioning effectively~~](#apply-positioning-effectively)
* [~~APPLY CASCADING STYLE SHEET TECHNIQUES~~](#apply-cascading-style-sheet-techniques)
* [~~Apply page layout with CSS~~](#apply-page-layout-with-css)
* [~~Implement transitions, transforms, and animation~~](#implement-transitions-transforms-and-animations)
* [~~Utilize CSS techniques~~](#utilize-css-techniques)


##General

## CREATE A SIMPLE WEB PAGE

## USE ELEMENTS AND ATTRIBUTES

### Self-Check 1.1-1

<details>
<summary>View</summary>
  
    Question 1
    
  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-1 [Information Sheet]/Question 1.png">
  
</details>

### Self-Check 1.1-2

<details>
<summary>View</summary>

    Question 1
    
  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 1.png">

    Question 2
    
  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 2.png">

    Question 3
    
  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 3.png">
  
</details>

### Self-Check 1.1-3

<details>
<summary>View</summary>
  
    Question 1

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-3 [HTML Tutorial]/Question 1.png">

    Question 2

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-3 [HTML Tutorial]/Question 2.png">

    Question 3

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-3 [HTML Tutorial]/Question 3.png">

    Question 4

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-3 [HTML Tutorial]/Question 4.png">

    Question 5

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-3 [HTML Tutorial]/Question 5.png">

    
      
</details>

### Task Sheet 1.1-1

<details>
<summary>View</summary>
  
    Enter this URL into your browser. You should see the Jen’s Kitchen web page from Figure 2-3

<img src="USE ELEMENTS AND ATTRIBUTES/Task Sheet 1.1-1/img1.png">

    Select View → Page Source (or View → Source) from the browser menu. On Chrome and Opera, View Source is located in the Developer menu. A window opens showing the source document shown in the figure

<img src="USE ELEMENTS AND ATTRIBUTES/Task Sheet 1.1-1/img2.png">

</details>

### Self-Check 1.1-5

<details>
<summary>View</summary>

    Question 1

  <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-5 [Application Programming Interface]/Question 1.png">
    

</details>

### Self-Check 1.1-2

<details>
<summary>View</summary>
  
    Question 1

 <img alt="Question 1" src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 1.png">

    Question 2

 <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 2.png">

    Question 3

 <img src="USE ELEMENTS AND ATTRIBUTES/Self-Check 1.1-2 [Information Sheet]/Question 3.png">
     
</details>

### Collaboration I

<details>
<summary>View</summary>

    resume.htm

```html
<!DOCTYPE html>
<html>

<head>
    <title>
        Simple web Development Template
    </title>
    <style>
        * {
            margin: 0;
            padding: 0;
        }

        .navbar {
            display: flex;
            align-items: center;
            justify-content: center;
            position: sticky;
            top: 0;
            cursor: pointer;
        }

        .background {
            background: black;
            background-blend-mode: darken;
            background-size: cover;
        }

        .nav-list {
            width: 70%;
            display: flex;
            align-items: center;
        }

        .logo {
            display: flex;
            justify-content: center;
            align-items: center;
        }

        .logo img {
            width: 60px;
            border-radius: 50px;
        }

        .nav-list li {
            list-style: none;
            font-family: Arial, Helvetica, sans-serif;
            padding: 26px 30px;
        }

        .nav-list li a {
            text-decoration: none;
            color: white;
        }

        .nav-list li a:hover {
            color: grey;
        }

        .rightnav {
            width: 30%;
            text-align: right;
        }

        #search {
            padding: 5px;
            font-size: 17px;
            border: 2px solid grey;
            border-radius: 9px;
        }

        .firstsection {
            background-color: black;
            height: 100vh;
            font-family: Arial, Helvetica, sans-serif;

        }

        table {
            border-collapse: collapse;
        }

        table,
        th,
        td {
            border: none;
        }

        th,
        td {
            padding: 5px;
        }

        .secondsection {
            background-color: #006BFF;
            height: 100vh;
        }

        .box-main {
            display: flex;
            justify-content: center;
            align-items: center;
            text-align: center;
            color: white;
        }

        .firsthalf {
            width: 100%;
            justify-content: center;
            align-items: center;
            text-align: center;
        }

        .secondhalf {
            width: 30%;
        }

        .secondhalf img {
            width: 70%;
            border: 4px solid white;
            border-radius: 150px;
            display: block;
            margin: auto;
        }

        .text-big {
            font-family: 'Piazzolla', serif;
            font-weight: bold;
            font-size: 35px;
        }

        .text-small {
            font-size: 18px;
        }

        .btn {
            padding: 8px 20px;
            margin: 7px 0;
            border: 2px solid white;
            border-radius: 8px;
            background: none;
            color: white;
            cursor: pointer;
        }

        .btn-sm {
            padding: 6px 10px;
            vertical-align: middle;
        }

        .section {
            height: 100vh;
            display: flex;
            align-items: center;
            justify-content: left;
            max-width: 90%;
            margin: auto;
        }

        .section-Left {
            flex-direction: row-reverse;
        }

        .paras {
            padding: 0px 0px;
        }

        .thumbnail img {
            width: 250px;
            border: 2px solid black;
            border-radius: 26px;
            margin-top: 19px;
        }

        .center {
            text-align: center;
        }

        .text-footer {
            text-align: center;
            padding: 30px 0;
            font-family: 'Ubuntu', sans-serif;
            display: flex;
            justify-content: center;
            color: white;
        }
    </style>
</head>

<body>
    <nav class="navbar background">
        <ul class="nav-list">
            <div class="logo">
                <img
                    src="https://ww2.freelogovectors.net/wp-content/uploads/2023/05/calendly_logo-freelogovectors.net_.png">
            </div>
            <li><a href="#web">Home</a></li>
            <li><a href="#program">Collab1 </a></li>
            <li><a href="#course">Resume</a></li>
        </ul>
        <div class="rightNav">
            <input type="text" name="search" id="search">
            <button class="btn btn-sm">Search</button>
        </div>
    </nav>
    <section id="web" class="firstsection">
        <div class="box-main">
            <div class="firstHalf">
                <h1 class="w3-jumbo"><span class="w3-hide-small">I'm</span> Clyde Bustamante.</h1>
                <br>
                <p style="font-size: 3;">Animator and Web Designer.</p>
                <br>
                <img style="height: auto;"
                    src="https://64.media.tumblr.com/9d924e85c2ef3b31a3e62c96d2c8c22e/93f854d16b70b838-b3/s540x810/f5a7cbd9846716b3b8df2d29913ee93913895b26.pnj"
                    alt="boy" class="w3-image" width="992" height="1108">
            </div>
        </div>
    </section>
    <section id="program" class="secondsection">
        <div class="box-main">
            <div class="secondHalf">
            </div>
        </div>
    </section>
    <section id="course" class="section">
        <div class="paras">
            <span>Mantalongon, Dalaguete, Cebu</span> <br>
            <span>Mobile: 09956274340</span> <br>
            <span>Email: clydhex@gmail.com</span><br>
            <br>
            <h2>Clyde Bustamante</h2>
            <br>
            <h4>PERSONAL DATA</h3>
                <table>
                    <tr>
                        <td>Date of Birth:</td>
                        <td>September 24, 2000</td>
                    </tr>
                    <tr>
                        <td>Place of Birth:</td>
                        <td>Caleriohan, Dalaguete, Cebu</td>
                    </tr>
                    <tr>
                        <td>Civil Status:</td>
                        <td>Single</td>
                    </tr>
                    <tr>
                        <td>Citizenship:</td>
                        <td>Filipino</td>
                    </tr>
                    <tr>
                        <td>Religion:</td>
                        <td>Roman Catholic</td>
                    </tr>
                    <tr>
                        <td>Height:</td>
                        <td>163</td>
                    </tr>
                    <tr>
                        <td>Weight:</td>
                        <td>55</td>
                    </tr>
                    <tr>
                        <td>Father Name:</td>
                        <td>Hermes Bustamante</td>
                    </tr>
                    <tr>
                        <td>Mother Name:</td>
                        <td>Alfonsa Bustamante</td>
                    </tr>
                </table>
                <br>
                <h4>EDUCATIONAL BACKGROUND</h4>
                <table>
                    <tr>
                        <th style="text-align: left;">Educational Level</th>
                        <th style="text-align: left;">School Name</th>
                        <th style="text-align: left;">Location</th>
                        <th style="text-align: left;">Years Attended</th>
                    </tr>
                    <tr>
                        <td style="text-align: left;">Primary</td>
                        <td style="text-align: left;">Mantalongon Elementary School</td>
                        <td style="text-align: left;">Mantalongon, Dalaguete, Cebu</td>
                        <td style="text-align: left;">2007-2013</td>
                    </tr>
                    <tr>
                        <td style="text-align: left;">Secondary</td>
                        <td style="text-align: left;">Mantalongon National High School</td>
                        <td style="text-align: left;">Mantalongon, Dalaguete, Cebu</td>
                        <td style="text-align: left;">2013-2017</td>
                    </tr>
                    <tr>
                        <td style="text-align: left;">Senior High</td>
                        <td style="text-align: left;">Mantalongon Senior High School</td>
                        <td style="text-align: left;">Mantalongon, Dalaguete, Cebu</td>
                        <td style="text-align: left;">2017-2019</td>
                    </tr>
                    <tr>
                        <td style="text-align: left;">Tertiary</td>
                        <td style="text-align: left;">Cebu Technological University </td>
                        <td style="text-align: left;">Argao Cebu</td>
                        <td style="text-align: left;">2019-Present</td>
                    </tr>
                </table>
        </div>
    </section>
    <footer class="background">
        <p class="text-footer">
            Copyright ©-All rights are reserved
        </p>
    </footer>
</body>
</html>
```

</details>

### Task Sheet 1.1-2

<details>
<summary>View</summary>

    Canvass.htm

```html
<!DOCTYPE html>
<html>
<head>
<style>
h1 {
    font-size: 15px; 
    font-family: Arial, Helvetica, sans-serif;
    font-weight: normal;
}
</style>
</head>
<body>
    <canvas id="myCanvas" width="300" height="300"></canvas>

    <script>
        var canvas = document.getElementById("myCanvas");
        var ctx = canvas.getContext("2d");

        var square1X = 20;
        var square1Y = 20;
        var squareSize1 = 200; 
        var squareSize2 = 200; 

        ctx.fillStyle = "rgba(254, 178, 178, 0.5)";
        ctx.fillRect(square1X, square1Y, squareSize1, squareSize1);

        var square2X = square1X + 60;
        var square2Y = square1Y + 60;

        ctx.fillStyle = "rgba(209, 255, 209, 0.5)";
        ctx.fillRect(square2X, square2Y, squareSize2, squareSize2);
    </script>
</body>
</html>
```

</details>

### Task Sheet 1.1-3

<details>
<summary>View</summary>

    Canvass2.htm

```html
<!DOCTYPE html>
<html lang="en">

<body>
    <canvas id="myCanvas" width="300" height="250"></canvas>

    <script>
      
        var canvas = document.getElementById("myCanvas");
        var ctx = canvas.getContext("2d");

        var centerX = canvas.width / 2;
        var centerY = canvas.height / 2; 
        var radius = 100;

        ctx.fillStyle = "#fe0000";

        ctx.save();

        ctx.scale(1, -1);
        
        ctx.translate(0, -canvas.height);

        ctx.beginPath();

        ctx.arc(centerX, centerY, radius, 0, Math.PI, true);

        ctx.closePath();

        ctx.fill();

        ctx.strokeStyle = "#9acd31";
        ctx.lineWidth = 10; 

        ctx.stroke();

        ctx.restore();
    </script>
</body>
</html>
```

</details>

### SVG Project

<details>
<summary>View</summary>
  
    SVG 1 - STAR

```html
<!DOCTYPE html>
<html>
<head>
  <title>SVG 1 - STAR</title>
</head>
<body>
  <svg width="200" height="200" viewBox="-100 -100 200 200">
    <g transform="translate(0 5)">
      <g>
        <polygon points="0,0 36,-50 0,-100" fill="#EDD8B7" />
        <polygon points="0,0 -36,-50 0,-100" fill="#E5C39C" />
      </g>
      <g transform="rotate(72)">
        <polygon points="0,0 36,-50 0,-100" fill="#EDD8B7" />
        <polygon points="0,0 -36,-50 0,-100" fill="#E5C39C" />
      </g>
      <g transform="rotate(-72)">
        <polygon points="0,0 36,-50 0,-100" fill="#EDD8B7" />
        <polygon points="0,0 -36,-50 0,-100" fill="#E5C39C" />
      </g>
      <g transform="rotate(144)">
        <polygon points="0,0 36,-50 0,-100" fill="#EDD8B7" />
        <polygon points="0,0 -36,-50 0,-100" fill="#E5C39C" />
      </g>
      <g transform="rotate(-144)">
        <polygon points="0,0 36,-50 0,-100" fill="#EDD8B7" />
        <polygon points="0,0 -36,-50 0,-100" fill="#E5C39C" />
      </g>
    </g>
  </svg>
</body>
</html>
```

    SVG 2 - SNOWFLEAKS

```html
<!DOCTYPE html>
<html>
<head>
  <title>SVG 2 - SNOWFLEAKS</title>
</head>
<body>
  <p class="sheesh">Name: <strong>Clyde Bustamante</strong></p>
  <svg width="200" height="200" viewBox="-100 -100 200 200">
    <defs>
      <path
        id="branch"
        d="
          M 0 0 L 0 -90
          M 0 -20 L 20 -34
          M 0 -20 L -20 -34
          M 0 -40 L 20 -54
          M 0 -40 L -20 -54
          M 0 -60 L 20 -74
          M 0 -60 L -20 -74"
        stroke="#E5C39C"
        stroke-width="5"
      />
    </defs>

    <use href="#branch" />
    <use href="#branch" transform="rotate(60)" />
    <use href="#branch" transform="rotate(120)" />
    <use href="#branch" transform="rotate(180)" />
    <use href="#branch" transform="rotate(240)" />
    <use href="#branch" transform="rotate(300)" />
  </svg>
</body>
</html>
```

    SVG 3 - BEAR

```html
<!DOCTYPE html>
<html>
<head>
<head>
  <title>SVG 3 - BEAR</title>
</head>
  <style>
    .gingerbread .body {
      fill: #cd803d;
    }

    .gingerbread .eye {
      fill: white;
    }

    .gingerbread .mouth {
      fill: none;
      stroke: white;
      stroke-width: 2px;
    }

    .gingerbread .limb {
      stroke: #cd803d;
      stroke-width: 35px;
      stroke-linecap: round;
    }

  </style>
</head>
<body>
  <svg class="gingerbread" width="200" height="200" viewBox="-100 -100 200 200">
    <circle class="body" cx="0" cy="-50" r="30" />

    <circle class="eye" cx="-12" cy="-55" r="3" />
    <circle class="eye" cx="12" cy="-55" r="3" />
    <rect class="mouth" x="-10" y="-40" width="20" height="5" rx="2" />

    <line class="limb" x1="-40" y1="-10" x2="40" y2="-10" />
    <line class="limb" x1="-25" y1="50" x2="0" y2="-15" />
    <line class="limb" x1="25" y1="50" x2="0" y2="-15" />

    <circle class="button" cx="0" cy="-10" r="5" />
    <circle class="button" cx="0" cy="10" r="5" />
  </svg>
</body>
</html>
```
</details>

### Collaboration II

<details>
<summary>View</summary>

    collab2.html

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body{
            background-color: #B0E0E6;
        }
        .shit{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 30px;
            background-color: pink;
            color: blue;
        }
        h3{
            font-family: Arial, Helvetica, sans-serif;
            font-size: 20px;
        }
        .yay{
            font-weight: normal;

            font-family: 'Times New Roman';
        }
        .awts{
            font-family: 'Franklin Gothic Medium';
        }
        .aguy{
            background-color: orangered;
            color: white;
        }
        .ats{
            font-size: 20px;
        }
        .umay{
            height: 200px;
        }
        .mama{
            font-size: 30px;
            font-family: Arial;
            font-weight: bold;
            -webkit-text-stroke: 2px #1c87c9;
        }
    </style>
</head>
<body>
    <h2 class="mama">CREATIVE WEB DESIGN</h2>
    <p class="shit">First Use</p>
    <img class="umay" src="https://64.media.tumblr.com/02074ceed07558a5f613e197dcdbbbe9/7b9830738ec7f990-3e/s540x810/8885de2496ced106cb5def82abc4c1c534779ee7.pnj" alt="anime boy">
    <p>PERSONAL INFORMATION</p>
    <h3 class="yay">NAME: <strong class="awts">Clyde Bustamante</stong></h3>
    <h3 class="yay">ADDRESS: <i>Mantalongon, Dalaguete, Cebu</I></i>
    <h3 class="yay">BIRTHDAY: <ins>September 24, 2000</ins></h3>
    <h3 class="yay">BIRTHPLACE: <span class="aguy">Caleriohan, Dalaguete, Cebu</span></h3>
    <h3 class="yay"><a class="ats" href="https://web.facebook.com/docshinn/">Visit my Account</a></h3>
    <h3 class="yay"><a class="ats" href="https://web.facebook.com/FolksKunAlbums">Visit my Page</a></h3>

    
</body>
</html>
```

</details>

## MARKUP A SIMPLE WEB

### Self-Check 1.2-1

<details>
<summary>View</summary>

    Question 1
  
<img src="MARKUP A SIMPLE WEB/Self-Check 1.2-1/Question 1.png">

</details>

### Self-Check 1.2-2

<details>
<summary>View</summary>

    Question 1

<img src="MARKUP A SIMPLE WEB/Self-Check 1.2-2/Question 1.png">

    Question 2

<img src="MARKUP A SIMPLE WEB/Self-Check 1.2-2/Question 2.png">

    Question 3

<img src="MARKUP A SIMPLE WEB/Self-Check 1.2-2/Question 3.png">

</details>

### Task Sheet 1.2-1

<details>
<summary>View</summary>
  
    list.html
  
```html
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
    <style>
        body {
            background-color: transparent;
            display: flex;
            justify-content: center;
            align-items: top;
            margin: 0;
        }

        .wrap {
            padding: 10px 10px;
            width: 18%;
            background-color: white;
            text-align: left;
            text-align: justify;

        }

        .hayst {
            margin-left: 25px;
        }
    </style>
</head>

<body>
    <div class="wrap">
        <h2>Ordered lists</h2>
        <p>Ordered lists are for items that occur in a particular order, such as step-by-step instructions or driving
            directions. They work just like the unordered lists described earlier, except they are defined with the ol
            element (for ordered list, of course). Instead of bullets, the browser automatically inserts numbers before
            ordered list items, so you don't need to number them in the source document. This makes it easy to rearrange
            list items without renumbering them. For example, <br><br> After reading this INFORMATION, YOU MSUT be able
            to:</p>
        <ol>
            <li>Demonstrate entering contents</li>
            <li>Identify the steps of marking up a simple web page</li>
            <li>Use text editors to format the 1-3 ordered list</li>
        </ol>
        <h2>Description lists</h2>
        <p>Description lists are used for any type of name / value pairs, such as terms and their definitions, questions
            and answeres, or other types of terms and their associated information. Their structure is a bit different
            from the other two lists that we just discussed. The whole description list is marked up as a
            <strong>dl</strong> element. The content of a <strong>dl</strong> is some number of <strong>dt</strong>
            elements indicating the names and <strong>dd</strong> elements for their respective values. I find it
            helpful to think of them as "terms" (to remember the "t" in <strong>dt</strong>) and "definitions (for the
            "d" in <strong>dd</strong>), even though that is only one use of description lists in HTML5. For example:
        </p>
        <a href="">beginPath()</a>
        <p class="hayst">Creates a new path. Once created, future drawing commands are directed into the path and used to build the path up.</p>
        <a href="">Path methods()</a>
        <p class="hayst">Methods to set different paths for objects</p>
        <a href="">closePath()</a>
        <p class="hayst">Adds a straight line to the path, going to the current sub-path.</p>
        <h2>Lists</h2>
        <p>  Humans are natural list makers, and HTML provides elements for marking up three types of lists:</p>
        <ol>
            <li>Unordered lists. Collections of items that appear in no particular order.</li>
            <li>Ordered lists. Lists in which the sequence of the items is important.</li>
            <li>Description lists. Lists that consist of name and value pairs, including but not limited to terms and definitions.</li>
        </ol>
        <h2>Unordered Lists</h2>
        <p>
            Identify an unordered list, mark it up as a ul element. The opening &lt;ul&gt; tag goes before the first
            list item, and the closing tag &lt;/ul&gt; goes after the last item. Then, each item in the list gets marked
            up as a list item (li) by enclosing it in opening and closing &lt;li&gt; tags, as shown in this example.
            Notice that there are no bullets in the source document. They are added automatically by the browser. For
            example:
        </p>


        <ul style="list-style-type: disc;">
            <li>Fruits</li>
            <ul style="list-style-type: disc;">
                <li>Mango</li>
                <li>Apple</li>
                <li>Pineapple</li>
            </ul>
            <li>Vegetables</li>
            <ul style="list-style-type: disc;">
                <li>Cabbage</li>
                <li>Lettuce</li>
                <li>Carrot</li>
            </ul>
        </ul>
    </div>
</body>

</html>
```

</details>

### Performance Test

<details>
<summary>View</summary>
  
    Collaboration with your Group is the Key
      
</details>


## ADD LINKS

### Self-Check 1.3-1

<details>
<summary>View</summary>
  
    Question 1

 <img alt="Question 1" src="ADD LINKS/Self-Check 1.3-1/Question 1.png">
     
</details>

## ADD IMAGES TO WEB PAGE

### Self-Check 1.4-1

<details>
<summary>View</summary>
  
    Question 1

 <img alt="Question 1" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-1/Question 1.png">

    Question 2

 <img alt="Question 2" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-1/Question 2.png">

    Question 3

 <img alt="Question 3" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-1/Question 3.png">
 
</details>

### Self-Check 1.4-2

<details>
<summary>View</summary>
  
    Question 1

 <img alt="Question 1" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-2/Question 1.png">

    Question 2

 <img alt="Question 2" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-2/Question 2.png">

    Question 3

 <img alt="Question 3" src="ADD IMAGES TO WEB PAGE/Self-Check 1.4-2/Question 3.png">
     
</details>

## CREATE FORMS

## USE CASCADING STYLE SHEETS

## Create document structures

## Format Text

## Apply colors and backgrounds

## Apply padding, borders, and margin

## Implement floating element

## Apply to positioning effectively

## APPLY CASCADING STYLE SHEET TECHNIQUES

## Apply page layout with CSS

## Implement transitions, transforms and animation

## Utilize CSS techniques

---

## **Thanks For Visiting**

<img src="https://i.gifer.com/origin/85/85a25f50ae5f4939336831d0b902e822_w200.gif" width=130 align=right>

Hope you liked it. Want to help?

- **[Star This Repository](https://github.com/clydebustamante/moodle)**
