@import './variables';
@use './header';

html {
width: 100vw;
height: 100vh;
}

body {
@include flexCenter(row);
@extend html;
color: $textColor;
width: 100% - 20%;
outline: 1px solid black;
}
