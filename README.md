# Ex09 Event Registration Web Application
## Date:23/12/2025
## Ref No: 25003349
## Name: POOJA A

## AIM:
To design, develop and deploy a web application for event registration.

## DESIGN STEPS:

### Step 1:
Create a new frame.

### Step 2:
Select any one preset size of your choice.

### Step 3:
Select the shapes you need.

### Step 4:
Import images as needed.

### Step 5:
Create pages based on your need and link them.

### Step 6:

Validate the HTML and CSS code.

### Step 6:

Publish the website in the given URL.

## DESIGN TOOL:
Figma

## CODE:
~~~
PAGE 1 (index.html)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-23-160856-1.png" />
      <img class="whatsapp-image" src="img/whatsapp-image-2025-12-23-at-9-11-18-PM-1.png" />
      <img class="text-on-a-path" src="img/text-on-a-path.png" />
      <div class="QUIZ-BOWL">QUIZ&nbsp;&nbsp;BOWL</div>
      <img class="img" src="img/screenshot-2025-12-23-212432-1.png" />
      <p class="text-wrapper">guessing is easy . knowing is hard</p>
      <div class="rectangle"></div>
      <div class="div">RIGISTER NOW</div>
    </div>
  </body>
</html>

PAGE 1 (globals.css)
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

PAGE 1 (style.css)
.iphone-pro {
  background-color: #ffffff;
  overflow: hidden;
  width: 100%;
  min-width: 540px;
  min-height: 980px;
  position: relative;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 0;
  left: 348px;
  width: 192px;
  height: 326px;
  aspect-ratio: 0.66;
}

.iphone-pro .whatsapp-image {
  position: absolute;
  top: 13px;
  left: 0;
  width: 540px;
  height: 84px;
  aspect-ratio: 6.67;
  object-fit: cover;
}

.iphone-pro .text-on-a-path {
  position: absolute;
  top: 639px;
  left: 672px;
  width: 656px;
  height: 661px;
  object-fit: cover;
}

.iphone-pro .QUIZ-BOWL {
  position: absolute;
  top: 116px;
  left: 138px;
  width: 292px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 96px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .img {
  position: absolute;
  top: 623px;
  left: 14px;
  width: 513px;
  height: 357px;
  aspect-ratio: 0.99;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 446px;
  left: 14px;
  width: 567px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #ee28d0;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle {
  position: absolute;
  top: 623px;
  left: 52px;
  width: 408px;
  height: 94px;
  background-color: #80e1e8;
}

.iphone-pro .div {
  position: absolute;
  top: 648px;
  left: 138px;
  width: 318px;
  font-family: "Amaranth-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

PAGE 2(index.html)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-23-210325-1.png" />
      <div class="text-wrapper">NAME :</div>
      <div class="rectangle"></div>
      <div class="div">EMAIL :</div>
      <div class="rectangle-2"></div>
      <div class="text-wrapper-2">PHONE NO :</div>
      <div class="rectangle-3"></div>
      <div class="text-wrapper-3">PARTICIPATION TYPE :</div>
      <div class="ellipse"></div>
      <div class="text-wrapper-4">SOLO</div>
      <div class="ellipse-2"></div>
      <div class="text-wrapper-5">GROUP</div>
      <div class="rectangle-4"></div>
      <div class="text-wrapper-6">CONFIRM PARTICIPATION</div>
    </div>
  </body>
</html>

PAGE 2 (globals.css)
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

PAGE 2(style.css)
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 599px;
  min-height: 975px;
  position: relative;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 599px;
  height: 975px;
  aspect-ratio: 0.57;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 84px;
  left: 31px;
  width: 161px;
  font-family: "IM FELL French Canon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle {
  top: 84px;
  left: 192px;
  width: 270px;
  height: 42px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .div {
  position: absolute;
  top: 168px;
  left: 31px;
  width: 141px;
  font-family: "IM FELL French Canon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-2 {
  top: 168px;
  left: 188px;
  width: 274px;
  height: 42px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-2 {
  position: absolute;
  top: 246px;
  left: 31px;
  width: 215px;
  font-family: "IM FELL French Canon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 36px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-3 {
  top: 246px;
  left: 261px;
  width: 285px;
  height: 54px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-3 {
  position: absolute;
  top: 356px;
  left: 31px;
  width: 368px;
  font-family: "Keania One-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .ellipse {
  top: 428px;
  height: 31px;
  border-radius: 18.5px / 15.5px;
  position: absolute;
  left: 112px;
  width: 37px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-4 {
  position: absolute;
  top: 424px;
  left: 192px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .ellipse-2 {
  top: 513px;
  height: 29px;
  border-radius: 18.5px / 14.5px;
  position: absolute;
  left: 112px;
  width: 37px;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-5 {
  position: absolute;
  top: 510px;
  left: 192px;
  font-family: "Kavoon-Regular", Helvetica;
  font-weight: 400;
  color: #ffffff;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .rectangle-4 {
  top: 791px;
  left: 31px;
  width: 533px;
  height: 96px;
  position: absolute;
  background-color: #d9d9d9;
}

.iphone-pro .text-wrapper-6 {
  position: absolute;
  top: 820px;
  left: 91px;
  width: 417px;
  font-family: "Kaushan Script-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 32px;
  letter-spacing: 0;
  line-height: normal;
}

PAGE 3(index.html)
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="iphone-pro">
      <img class="screenshot" src="img/screenshot-2025-12-23-210906-1.png" />
      <div class="text-wrapper">REGISTRATION SUCCESSFUL</div>
      <div class="div">GET READY...</div>
    </div>
  </body>
</html>

PAGE 3(globals.css)
@import url("https://cdnjs.cloudflare.com/ajax/libs/meyer-reset/2.0/reset.min.css");
* {
  -webkit-font-smoothing: antialiased;
  box-sizing: border-box;
}
html,
body {
  margin: 0px;
  height: 100%;
}
/* a blue color as a generic focus style */
button:focus-visible {
  outline: 2px solid #4a90e2 !important;
  outline: -webkit-focus-ring-color auto 5px !important;
}
a {
  text-decoration: none;
}

PAGE 3 (style.css)
.iphone-pro {
  background-color: #ffffff;
  width: 100%;
  min-width: 551px;
  min-height: 973px;
  position: relative;
}

.iphone-pro .screenshot {
  position: absolute;
  top: 0;
  left: 0;
  width: 551px;
  height: 973px;
  aspect-ratio: 0.88;
  object-fit: cover;
}

.iphone-pro .text-wrapper {
  position: absolute;
  top: 62px;
  left: 11px;
  font-family: "Kokoro-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}

.iphone-pro .div {
  position: absolute;
  top: 216px;
  left: 167px;
  font-family: "Lalezar-Regular", Helvetica;
  font-weight: 400;
  color: #000000;
  font-size: 40px;
  letter-spacing: 0;
  line-height: normal;
}
~~~


## OUTPUT:

<img width="1291" height="824" alt="Screenshot 2025-12-23 225850" src="https://github.com/user-attachments/assets/1a6b5510-93a3-48dd-aa85-4d24616f69e4" />



## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
