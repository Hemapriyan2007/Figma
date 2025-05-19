# Ex09 Event Registration Web Application
## Date:19.05.2025
## Reg No:212224220055

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
```
Home Page
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<img src="images/android-compact-1-1.png" class="android-compact-1-1" alt="android-compact-1" />

</body>
</html>

CSS

  :root {
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.android-compact-1-1 {
@media (max-width: 1440px) {
  .android-compact-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-compact-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}
```
```
Event Page
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-small-1-1">
<img src="images/image-1-2.png" class="image-1-2" alt="image-1" />
<p class="text-3"><span class="text-black">sports day Events</span></p>
<div class="rectangle-3-4"></div>
<p class="text-5"><span class="text-black">cricket
Football
Handball
Volley ball
Athletes</span></p>
</div>

</body>
</html>

CSS


/* Add font files for Jomolhari */
@font-face {
  font-family: 'Jomolhari';
  src: url('fonts/jomolhari.woff2') format('woff2'),
       url('fonts/jomolhari.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}

/* Add font files for Jost */
@font-face {
  font-family: 'Jost';
  src: url('fonts/jost.woff2') format('woff2'),
       url('fonts/jost.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jomolhari: 'Jomolhari', sans-serif;
  --font-family-jost: 'Jost', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.image-1-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.3499999940395355;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-3-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 249, 249, 1);
}

.text-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jost);
  font-weight: normal;
  font-size: 24px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-small-1-1 {
@media (max-width: 1440px) {
  .android-small-1-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-small-1-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

```
```
Registration Page
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="style.css">
</head>
<body>
<div class="android-small-2-1">
<img src="images/image-3-2.png" class="image-3-2" alt="image-3" />
<div class="rectangle-4-3"></div>
<div class="rectangle-5-4"></div>
<div class="rectangle-6-5"></div>
<div class="rectangle-7-6"></div>
<div class="rectangle-8-7"></div>
<div class="rectangle-9-8"></div>
<p class="text-9"><span class="text-black">Name</span></p>
<p class="text-10"><span class="text-black">reg no</span></p>
<p class="text-11"><span class="text-black">Age</span></p>
<p class="text-12"><span class="text-black">Dept</span></p>
<p class="text-13"><span class="text-black">Mobile no</span></p>
<p class="text-14"><span class="text-black">Event name</span></p>
<div class="rectangle-10-15"></div>
<p class="text-16"><span class="text-black">SUBMIT</span></p>
</div>

</body>
</html>

CSS


/* Add font files for Jomolhari */
@font-face {
  font-family: 'Jomolhari';
  src: url('fonts/jomolhari.woff2') format('woff2'),
       url('fonts/jomolhari.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-jomolhari: 'Jomolhari', sans-serif;
  --text-black: rgba(0, 0, 0, 1);
}

.text-black {
  color: var(--text-black);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.image-3-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.rectangle-4-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 249, 249, 1);
}

.rectangle-5-4 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(249, 247, 247, 1);
}

.rectangle-6-5 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 247, 247, 1);
}

.rectangle-7-6 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 247, 247, 1);
}

.rectangle-8-7 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 247, 247, 1);
}

.rectangle-9-8 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(254, 247, 247, 1);
}

.text-9 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-10 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-11 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-12 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-13 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.text-14 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  opacity: 0.6200000047683716;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 13px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.rectangle-10-15 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(23, 136, 235, 1);
  border: 1px solid rgba(0, 0, 0, 1);
}

.text-16 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-jomolhari);
  font-weight: normal;
  font-size: 15px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-black);
}

.android-small-2-1 {
@media (max-width: 1440px) {
  .android-small-2-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-small-2-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

```
```
End Page
HTML

<!DOCTYPE html>
<html>
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Exported Figma Design</title>
  
  <link rel="stylesheet" href="styles.css">
</head>
<body>
<div class="android-small-3-1">
<img src="images/image-4-2.png" class="image-4-2" alt="image-4" />
<p class="text-3"><span class="text-white">Thank You</span></p>
</div>

</body>
</html>

CSS


/* Add font files for Karantina */
@font-face {
  font-family: 'Karantina';
  src: url('fonts/karantina.woff2') format('woff2'),
       url('fonts/karantina.woff') format('woff');
  font-weight: normal;
  font-style: normal;
}
:root {
  --font-family-karantina: 'Karantina', sans-serif;
  --text-white: rgba(255, 255, 255, 1);
}

.text-white {
  color: var(--text-white);
}


/* CSS Reset */
* {
  margin: 0;
  padding: 0;
  box-sizing: border-box;
}

body {
  width: 100%;
  min-height: 100vh;
  overflow-x: hidden;
}

img {
  max-width: 100%;
  height: auto;
}

.image-4-2 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  width: 100%;
  height: auto;
}

.text-3 {
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  font-family: var(--font-family-karantina);
  font-weight: normal;
  font-size: 48px;
  text-decoration: none;
  text-transform: none;
  color: var(--text-white);
}

.android-small-3-1 {
@media (max-width: 1440px) {
  .android-small-3-1 {
    padding-left: 24px;
    padding-right: 24px;
  }
}

@media (max-width: 768px) {
  .android-small-3-1 {
    padding-left: 16px;
    padding-right: 16px;
  }
}
  flex-grow: 0;
  flex-shrink: 1;
  flex-basis: auto;
  background-color: rgba(255, 255, 255, 1);
}

 

```

## OUTPUT:
![alt text](<Screenshot 2025-05-19 205310.png>)

## RESULT:
The program to design, develop and deploy a web application for event registration is completed successfully.
