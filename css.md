# CSS Properties Guide

## Box Model Properties
- margin
  - Outside space
  - `margin: 10px;`
  - `margin: 10px 20px 15px 25px;`
- padding
  - Inside space
  - `padding: 15px;`
  - `padding-left: 20px;`
- border
  - Border styling
  - `border: 1px solid black;`
  - `border-bottom: 2px dashed red;`
  - border-radius
    - Rounded corners
    - `border-radius: 5px;`
    - `border-radius: 50%;`
- dimensions
  - width: `width: 200px;` or `width: 50%;`
  - height: `height: 100px;` or `height: 100vh;`
  - min-width: `min-width: 300px;`
  - max-width: `max-width: 1200px;`

## Typography Properties
- font
  - font-family: `font-family: Arial, sans-serif;`
  - font-size: `font-size: 16px;` or `font-size: 1.2rem;`
  - font-weight: `font-weight: bold;` or `font-weight: 700;`
- text
  - color: `color: #FF0000;` or `color: rgb(255, 0, 0);`
  - text-align: `text-align: center;` or `text-align: justify;`
  - line-height: `line-height: 1.5;` or `line-height: 20px;`
  - text-decoration: `text-decoration: underline;` or `text-decoration: none;`

## Layout Properties
- display: `display: flex;` or `display: grid;`
- position: `position: relative;` or `position: absolute;`
- flex properties
  - flex: `flex: 1;` or `flex: 1 1 auto;`
  - flex-direction: `flex-direction: row;` or `flex-direction: column;`
  - justify-content: `justify-content: center;` or `justify-content: space-between;`
  - align-items: `align-items: center;` or `align-items: stretch;`
  - flex-wrap: `flex-wrap: wrap;` or `flex-wrap: nowrap;`
  - gap: `gap: 10px;` or `gap: 1rem;`
- grid properties
  - grid-template-columns: `grid-template-columns: 1fr 2fr 1fr;`
  - grid-template-rows: `grid-template-rows: auto 200px auto;`
  - grid-gap: `grid-gap: 20px;`
  - grid-area: `grid-area: 1 / 1 / 3 / 3;`
- float: `float: left;` or `float: right;`
- clear: `clear: both;` or `clear: left;`

## Visual Properties
- background
  - background-color: `background-color: #f0f0f0;`
  - background-image: `background-image: url('image.jpg');`
- effects
  - opacity: `opacity: 0.8;`
  - box-shadow: `box-shadow: 2px 2px 5px rgba(0,0,0,0.3);`
  - transform: `transform: rotate(45deg);` or `transform: scale(1.2);`
  - filter: `filter: blur(5px);` or `filter: brightness(150%);`
  - backdrop-filter: `backdrop-filter: blur(10px);`

## Animation Properties
- transition: `transition: all 0.3s ease;`
- animation: `animation: slide 2s ease infinite;`
- @keyframes:
```css
@keyframes slide {
  from { transform: translateX(0); }
  to { transform: translateX(100px); }
}
```

## Responsive Design
- @media: `@media screen and (max-width: 768px) { ... }`
- viewport units: `height: 100vh;` or `width: 50vw;`

## Miscellaneous Properties
- cursor: `cursor: pointer;` or `cursor: not-allowed;`
- overflow: `overflow: hidden;` or `overflow: scroll;`
- visibility: `visibility: hidden;` or `visibility: visible;`
- object-fit: `object-fit: cover;` or `object-fit: contain;`
