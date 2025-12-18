# Ex08 Event Registration Web Application
## Date:18-12-2025

## AIM:
To design, develop and deploy a web application for event registration using Figma UI tool.

## UI DESIGN TOOL:
Figma

## DESIGN STEPS:

### Step 1:
Use frames to represent screens or sections.

### Step 2:
Add column grids for consistent spacing and alignment.

### Step 3:
Insert shapes, text, buttons, and icons.

### Step 4:
Use Auto Layout for flexible, responsive design.

### Step 5:
Define color, text, and effect styles globally for consistency.

### Step 6:
Name layers logically and group related elements.

### Step 6:
Link frames to show navigation or interactions.

### Step 7:
Select the specific frame while generating code using Anima plugin.

## CODE:
```
page-1
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <img class="image" src="img/image-2.png" />
      <div class="rectangle"></div>
      <img class="logoreal" src="img/logoreal-1.png" />
      <div class="div"></div>
      <img class="LOGIN" src="img/LOGIN.png" />
      <div class="rectangle-2"></div>
      <img class="REGISTER" src="img/REGISTER.png" />
      <img class="FASHION-SHOW-EVENTS" src="img/FASHION-SHOW-EVENTS.png" />
    </div>
  </body>
</html>

globals.css
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
style.css
.android-medium {
  background-color: #d7afb3;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .image {
  position: absolute;
  top: 0;
  left: 0;
  width: 700px;
  height: 840px;
  aspect-ratio: 0.66;
  object-fit: cover;
}

.android-medium .rectangle {
  top: 448px;
  left: 115px;
  width: 517px;
  height: 88px;
  position: absolute;
  background-color: #000000;
}

.android-medium .logoreal {
  position: absolute;
  top: 0;
  left: 23px;
  width: 653px;
  height: 131px;
  aspect-ratio: 4.97;
  object-fit: cover;
}

.android-medium .div {
  top: 578px;
  left: 207px;
  width: 306px;
  height: 56px;
  position: absolute;
  background-color: #000000;
}

.android-medium .LOGIN {
  position: absolute;
  top: 590px;
  left: 306px;
  width: 117px;
  height: 32px;
}

.android-medium .rectangle-2 {
  top: 678px;
  left: 140px;
  width: 440px;
  height: 66px;
  position: absolute;
  background-color: #000000;
}

.android-medium .REGISTER {
  position: absolute;
  top: 695px;
  left: 276px;
  width: 188px;
  height: 32px;
}

.android-medium .FASHION-SHOW-EVENTS {
  position: absolute;
  top: 477px;
  left: 143px;
  width: 472px;
  height: 32px;
}

page-2
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <img class="FASHION-SHOW-EVENTS" src="img/FASHION-SHOW-EVENTS.png" />
      <div class="div"></div>
      <img class="star" src="img/star-2.svg" />
      <img class="img" src="img/star-3.svg" />
      <img class="star-2" src="img/star-5.svg" />
      <img class="star-3" src="img/star-6.svg" />
      <img class="star-4" src="img/star-7.svg" />
      <img class="star-5" src="img/star-4.svg" />
      <img class="star-6" src="img/star-1.svg" />
      <img class="image" src="img/image-1.png" />
    </div>
  </body>
</html>

globals.css
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
style.css
.android-medium {
  background-color: #d7afb3;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .rectangle {
  top: 41px;
  left: 74px;
  height: 100px;
  position: absolute;
  width: 551px;
  background-color: #d9d9d9;
}

.android-medium .FASHION-SHOW-EVENTS {
  position: absolute;
  top: 76px;
  left: 115px;
  width: 472px;
  height: 32px;
}

.android-medium .div {
  top: 169px;
  left: 75px;
  height: 375px;
  position: absolute;
  width: 551px;
  background-color: #d9d9d9;
}

.android-medium .star {
  top: 254px;
  left: 75px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .img {
  top: 352px;
  left: 76px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .star-2 {
  top: 399px;
  left: 76px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .star-3 {
  top: 492px;
  left: 76px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .star-4 {
  top: 449px;
  left: 76px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .star-5 {
  top: 303px;
  left: 76px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .star-6 {
  top: 205px;
  left: 75px;
  position: absolute;
  width: 35px;
  height: 32px;
}

.android-medium .image {
  position: absolute;
  top: 552px;
  left: 105px;
  width: 489px;
  height: 274px;
  aspect-ratio: 1.79;
  object-fit: cover;
}

page-3
index.html
<!DOCTYPE html>
<html>
  <head>
    <meta name="viewport" content="width=device-width, initial-scale=1" />
    <meta charset="utf-8" />
    <link rel="stylesheet" href="globals.css" />
    <link rel="stylesheet" href="style.css" />
  </head>
  <body>
    <div class="android-medium">
      <div class="rectangle"></div>
      <div class="frame"><img class="image" src="img/image-3.png" /></div>
      <img class="img" src="img/rectangle-4.svg" />
      <img class="EVENT-REGISTRATION" src="img/EVENT-REGISTRATION-FORM.png" />
      <div class="div"></div>
      <img class="SUMBIT" src="img/SUMBIT.png" />
    </div>
  </body>
</html>

globals.css
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

style.css
.android-medium {
  background-color: #d7afb3;
  overflow: hidden;
  width: 100%;
  min-width: 700px;
  min-height: 840px;
  position: relative;
}

.android-medium .rectangle {
  position: absolute;
  top: 143px;
  left: 45px;
  width: 277px;
  height: 369px;
  background-color: #d9d9d9;
}

.android-medium .frame {
  display: flex;
  width: 779px;
  height: 1392px;
  align-items: center;
  gap: 10px;
  padding: 10px;
  position: absolute;
  top: -119px;
  left: 132px;
}

.android-medium .image {
  position: relative;
  width: 557px;
  height: 542px;
  aspect-ratio: 1;
  object-fit: cover;
}

.android-medium .img {
  position: absolute;
  top: 27px;
  left: 42px;
  width: 639px;
  height: 89px;
}

.android-medium .EVENT-REGISTRATION {
  position: absolute;
  top: 57px;
  left: 87px;
  width: 550px;
  height: 32px;
}

.android-medium .div {
  position: absolute;
  top: 732px;
  left: 246px;
  width: 404px;
  height: 80px;
  background-color: #d3a9a9;
}

.android-medium .SUMBIT {
  position: absolute;
  top: 757px;
  left: 363px;
  width: 151px;
  height: 32px;
}
```


## OUTPUT:
![alt text](<Screenshot (30).png>)

## RESULT:
The program to design, develop and deploy a web application for event registration using Figma UI tool is completed successfully.
