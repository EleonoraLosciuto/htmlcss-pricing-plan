# PRICING PLAN HTML/CSS
This project is the fifth exercise in the context of a Web Development Master Course. It is focused on HTML and CSS, including CSS Flexbox, and an advanced focused on object positioning and layout. This includes the use of media queries for a responsive layout for mobile, tablet and desktop.

## TASK
The task is re-creating a web-page, provided by the teacher, by using HTML and CSS. This webpage is landing page showing 3 different price plans and the features included in each "package" &#40;for each price&#41;. The objective is to obtain a finalized page with responsive layout focused on structural CSS and clean HTML architecture:

* Focus: Flexbox/Grid, Media Queries and semantic HTML. The approach used in this case is <strong>Desktop-First</strong>. Than, by using media queries, I added the max-width breakpoints for tablets and mobile.
* Bonus tasks:
1. Tablet view: third card takes the whole space horizontally.
2. Tablet view: third card's list of features in two columns.

## PROJECT STRUCTURE
Htmlcss-pricing-plan/ <br>
├── .gitignore <br>
├── index.html <br>
├── README.md <br>
└── css/ <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── style.css <br>
└── img/ <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── favicon.ico.svg <br>
└── screenshots/ <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── screencapture-desktop.png <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── screencapture-mobile.png <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── screencapture-mq-1.png <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── screencapture-mq-2.png <br>
&nbsp;&nbsp;&nbsp;&nbsp;├── screencapture-tablet.png <br>

## REFERENCE WEBPAGES
### DESKTOP

![Desktop Layout](./screenshots/screencapture-desktop.png)

### TABLET

![Tablet Layout](./screenshots/screencapture-tablet.png) 

### MOBILE

![Mobile Layout](./screenshots/screencapture-mobile.png) 

### CARD ORDER CHANGE

![Change Card Order](./screenshots/screencapture-mq-1.png) 

## TECH STACK

* HTML5: semantic elements
* CSS3: custom properties / variables + Media queries
* VSCode: IDE

## FEATURES

* all elements are nested in main: I consider the title to not be an header because it includes relevant information about the company and the cards shown below.
* .container div to manage layout.
* debug class to show borders and manage styles and layout - only for developer use.
* three main parts &#40;div elements&#41;: title, mobile switches / togglers, and cards. Note: desktop and tablet switches are included inside title container div for position/layout purposes.
* three main parts &#40;div elements&#41;: title, mobile switches / togglers, and cards. Note: desktop and tablet switches are included inside title container &#40;div&#41; for position/layout purposes.