# How I created this app

## Create the React App
```
npx create-react-app .
```
The "." is used to create the React app in the same directory.

---

## Material UI
### Introduction
For full details, see the documentation website:

https://mui.com/material-ui/getting-started/installation/

### Perform the default Material UI installation
```
npm install @mui/material @emotion/react @emotion/styled
```

Material UI uses Emotion as its default styling engine. 
If you want to use styled-components instead, 
run the following command:

```
npm install @mui/material @mui/styled-engine-sc styled-components
```


### Add the Roboto font
Material UI is designed to use the Roboto font by default.
```
npm install @fontsource/roboto
```

Import the font into your entry point as follows:
```
import '@fontsource/roboto/300.css';
import '@fontsource/roboto/400.css';
import '@fontsource/roboto/500.css';
import '@fontsource/roboto/700.css';
```

Or, you can install the Roboto font in your project 
using the Google Web Fonts CDN, add the following 
code snippet inside your project's `<head />` tag:
```
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/css?family=Roboto:300,400,500,700&display=swap"
/>
```

### Add icons
To use the font Icon component or the prebuilt 
SVG Material Icons (such as those found in the icon demos),
you must first install the Material Icons font.

Using NPM:
```
npm install @mui/icons-material
```

Using Google Web Fonts CDN:
```
<link
  rel="stylesheet"
  href="https://fonts.googleapis.com/icon?family=Material+Icons"
/>
```