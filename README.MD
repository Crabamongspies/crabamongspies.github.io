# Crabs Grotto

Welcome to my repository! Here’s the HTML code for the Crabs Grotto website.

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="icon" type="image/gif" href="favicon.gif">
    <title>Crabs Grotto</title>
    <style>
        @font-face {
            font-family: 'Undertale Sans';
            src: url('font.ttf') format('truetype');
            font-display: swap;
        }

        body {
            font-family: 'Undertale Sans';
            font-size: 32px;
            background-color: #000000;
            margin: 0;
            padding: 20px;
            color: #ffffff;
            display: flex;
            justify-content: flex-start;
            align-items: flex-start;
            flex-direction: column;
            -webkit-user-select: none;
            -moz-user-select: none;
            -ms-user-select: none;
            user-select: none;
        }

        .text-container {
            display: inline-block;
            padding: 0 2em;
            text-align: center;
            margin-right: 20px;
            margin-bottom: 20px;
            flex-shrink: 0;
            box-sizing: border-box;
        }

        .text-container h2,
        .text-container p,
        .text-container a,
        .text-container .category {
            margin: 0.5em 0;
        }

        .text-container a {
            text-decoration: none;
        }

        .text-container a.black {
            color: mediumpurple;
        }

        .youtube-link {
            color: red;
            margin-right: 10px;
        }

        .archive {
            color: skyblue;
        }

        .links-container {
            display: inline-block;
            text-align: center;
        }
    </style>
</head>
<body>

    <div class="text-container">
        <p>Crabs Grotto</p>
        <p>Welcome to my website, where I showcase my artwork and video games!</p>
        <br>
        <p class="links-container">
            <a href="https://crabamongspies.github.io" class="youtube-link" target="_blank">OPEN WEBSITE</a>
        </p>
    </div>
</body>
</html>