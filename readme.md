<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <meta http-equiv="X-UA-Compatible" content="ie=edge">
    <style>
        * {
            font-family: Arial, sans-serif; /* Typeface set to Arial */
        }
        body {
            margin: 0;
            font-size: 14px; /* Font size set to 14px */
            line-height: 1.4; /* Line height set to 1.4 */
            overflow-x: hidden; /* Disable horizontal scrolling */
        }
        a, a:visited {
            color: black;
            text-decoration: underline; /* Underline links */
        }
        .information {
            z-index: 1000;
            margin: 1.2em;
            position: absolute;
            font-size: 12px; /* Font size set to 12px */
            line-height: 1.2; /* Tight line height */
            max-width: 100%; /* Ensure content does not overflow */
        }
        .container {
            z-index: 1;
            width: 100vw;
            height: 100vh;
            margin: auto;
            position: relative;
            overflow: hidden; /* Ensure no overflow */
        }
        .image_container {
            width: 100%;
            height: auto;
            display: flex;
            justify-content: center;
            align-items: center;
        }
    </style>
</head>
<body>
    <div class="information">
        Alex Shelley<br>
        ashell.info@gmail.com<br>
        Portland, OR.<br>
        <br>
        Eric Schroeder - High Low, 2025<br>
        DP and editor. Camera operated by Ethan Van der Merwe. Freya Kargard as Eric Schroeder. Additional filming by Dylan Hayes<br>
        <br>
        Shallow Basin, 2024<br>
        Curation and visual identity. Gallery Install with help from Sid Pai<br>
        <br>
        Portrait World, 2024<br>
        Visual identity, web design, merch and photography<br>
        <br>
        No Pressure, 2024<br>
        Design, layout and copy<br>
        Featuring work and interviews from Chris Eurick, Joe Garlic and Travis Spinks<br>
        <br>
        Specialized Rockhopper, 2023<br>
        Design, layout and copy<br>
        <br>
        Plum Books, 2021<br>
        Founder and creative director. Co operated with Ali Mehraban<br>
    </div>
    <div class="container" style="pointer-events: auto;">
        <div class="image_container">
            <div class="image_1"></div>
            <div class="image_2"></div>
        </div>
    </div>
</body>
</html>
