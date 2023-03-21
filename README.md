## CSS функции и переменные
- **Подключение CSS файла**
```html
<link
rel="stylesheet"
href="style.css"
/>
```
___
- **Начало CSS-кода**
```css
*{
    margin: 0;
    padding: 0;
    font-family: sans-serif;
    box-sizing: border-box;
}
```
___
- **margin и padding**

![](./011.png "background-size: cover; ")

- **margin** отвечает за отступ от краев сайта, а **padding** за отступ от рамки(**border**) до контента.
```css
.div {
margin: 15px;
padding: 35px;
}
```
___
- **width** и **height**

![](./01.jpg)
- **width** отвечает за высоту, а **height** за ширину блока.
```css
.div {
    width: 50px;
    height: 50px;
}
```
___
- **background-color** - 
Данный тег обозначает, какой цвет будет на фоне блока или сайта.
Цветовая палитра 
rgb- от 0 до 255
hex- от 0 до F.
```css
background-color: aqua;
background-color: rgb(255,255,0)
background-color: hex(000F00)
```
___
 - **border-radius** -
Данный тег отвечает за скругление углов блока.
Например:
```css
border-radius: 100%
border-radius: 50px
```
- А также данный тег строит окружность 
![](02.jpeg)
