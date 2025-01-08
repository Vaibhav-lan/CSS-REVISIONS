# CSS-REVISIONS CODES ARE WRITTEN
<!DOCTYPE html>
<html>
<head>
    <title>Color Example</title>
</head>
<body>
    <h1 style="color: red;">Revision of css from technical team</h1>
    <hr>
    <b> SECOND</b>
    <p style="color: red;">This text is red.</p>
    <p style="background-color: yellow;">This background is yellow.</p>
    <p style="color: rgb(0, 128, 0);">This text is green using RGB.</p>
    <p style="background-color: rgb(0, 0, 255, 0.5);">This background is semi-transparent blue.</p>
    <hr>
    <b>THIRD</b>
    <style>
        h1 { color: blue; text-align: center; } 
        .highlight { color: green; text-transform: uppercase; }
        #important { color: red; text-decoration: underline; font-weight: bold; } 
    </style>
</head>
<body>
    <h1>Element Selector 3RD </h1>
    <p class="highlight">Class Selector with Uppercase</p>
    <p id="important">ID Selector with Bold and Underline</p>
    <HR>
    <h2> BOX AND ITS POISIPNING 4TH</h2>
    <style>
        .box {
            width: 75px; height: 100px; 
            margin: 20px; padding: 10px;
            border: 2px solid black; background-color: lightblue;
        }
        .positioned {
            position: absolute; top:265px; left: 200px;  
            background-color: lightgreen;
        }
    </style>
    <div class="box">Box Model ExampLe</div>
    <div class="box positioned">Positioning Example</div>
    <HR>
        <H1>FLEXBOX 5TH TOPIC</H1>
    <style>
        .flex-container {
            display: flex; justify-content: space-around;
            background-color: lightgray; padding: 10px;
        }
        .flex-item {
            width: 100px; height: 100px; background-color: coral;
        }
    </style>
</head>
<body>
    <div class="flex-container">
        <div class="flex-item">1</div>
        <div class="flex-item">2</div>
        <div class="flex-item">3</div>
    </div>
    <hr>
    <hr>
    <p><b>media queries 6th</b> </p>
    <style>
        .box {
            width: 100px; height: 100px;
        }
    </style>
</head>
<body>
    <div class="box"></div>
    <hr>
    <h><b>TRANSITION AND TRANSFORM 7th <BR> (sab boxespe apply ho rha hai)</b></h>
    <style>
        .box {
            width: 100px; height: 100px;
            background-color: coral;
            transition: transform 0.5s ease; 
        }
        .box:hover {
            transform: rotate(45deg) scale(1.2); 
        }
    </style>
</head>
<body>
    <div class="box"></div>
</body>
</html>
