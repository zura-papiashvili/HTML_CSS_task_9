# HTML_CSS_task_9


## Topic: CSS @media rule


[Preview Page (@media rule)](https://zura-papiashvili.github.io/HTML_CSS_task_9/) 

#### Tree Structure:
```bash
├── HTML_CSS_Task_9
│   ├── css
│   │   ├── **/*.css
│   ├── fonts
│   │   ├── **/*.ttf/eot/otf/svg/woff
│   ├── images
│   │   ├── **/*.png/jpg/svg
│   ├── index.html
│   ├── README.md
```


#### CSS @media Rule
The @media rule is used in media queries to apply different styles for different media types/devices.

Media queries can be used to check many things, such as:

* width and height of the viewport
* width and height of the device
* orientation (is the tablet/phone in landscape or portrait mode?)
* resolution

# Examples


``` css
/* Change the background color of the <body> element to "lightblue" when the browser window is 600px wide or less: */
@media only screen and (max-width: 600px) {
  body {
    background-color: lightblue;
  }
}
}

/* On screens that are 992px wide or less, go from four columns to two columns */
@media screen and (max-width: 992px) {
  .column {
    width: 50%;
  }
}

/* On screens that are 600px wide or less, make the columns stack on top of each other instead of next to each other */
@media screen and (max-width: 600px) {
  .column {
    width: 100%;
  }
}
```

### Source:[www.w3schools.com](https://www.w3schools.com/cssref/css3_pr_mediaquery.asp)




