# WOW JS SCROLLING ANIMATION EFFECT

## Introduction
Wow.js is a JavaScript library designed to add scroll-triggered animations to web pages effortlessly. By simply incorporating it into your project, you can bring elements to life as users scroll, enhancing the overall interactivity and engagement of your website.

[Visit deme](https://vxlrubel.github.io/wowjs/);

## How to use

Here is the boilerplate 

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>WOW JS</title>
    <link rel="stylesheet" href="./assets/css/main.css">
    <link rel="stylesheet" href="./assets/css/animate.css">
</head>
<body>
    <div class="container">
        <h2 class="title">Others Animation</h2>
        <div class="grid">
            <div class="box wow hinge" data-wow-delay="0.25s" data-wow-iteration="1" data-wow-duration="0.5">
                hinge
            </div>
            <div class="box wow rollIn" data-wow-delay="0.25s" data-wow-iteration="1" data-wow-duration="0.5">
                rollIn
            </div>
            <div class="box wow rollOut" data-wow-delay="0.25s" data-wow-iteration="1" data-wow-duration="0.5">
                rollOut
            </div>
        </div>
    </div>

    <script src="./assets/js/wow.js"></script>
    <script>
        new WOW().init();
    </script>
</body>
</html>
```

