<!-- 

Welcome to GDB Online.
GDB online is an online compiler and debugger tool for C, C++, Python, Java, PHP, Ruby, Perl,
C#, OCaml, VB, Swift, Pascal, Fortran, Haskell, Objective-C, Assembly, HTML, CSS, JS, SQLite, Prolog.
Code, Compile, Run and Debug online from anywhere in world.

-->
</head>
<body>
<title>Happy New Year 2023</title>
<div class="loading">
  <h2>2022</h2>
  <div class="bar"></div>
  <h2>2023</h2>
</div>
<div class="center">
  <div><h2>Happy New Year</h2></div>
  <div></div>
  <div><h2>2023!</h2></div>
  <div></div>
</div>
<style>body {
  margin: 0;
  padding: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  overflow: hidden;
  font-family: sans-serif;
}
.center {
  position: relative;
  width: 400px;
}
.center div {
  position: relative;
  height: 100px;
  margin: -30px 0;
  z-index: 2;
  transform: skewY(-5deg);
  display: flex;
  align-items: center;
  justify-content: center;
}
.center div:nth-child(2),
.center div:nth-child(4) {
  transform: skewY(14.5deg);
  z-index: 1;
}
.center div:nth-child(4) {
  transform-origin: left;
  transform: skewY(25deg);
  top: -52px;
}
.center div:before {
  content: '';
  position: absolute;
  width: 100%;
  height: 100%;
}
.center div:nth-child(1):before,
.center div:nth-child(3):before {
  background: linear-gradient(-160deg, #ff0058, #673ab7);
  transform: scaleX(0);
}
.center div:nth-child(2):before,
.center div:nth-child(4):before {
  background: linear-gradient(-20deg, #ff0058, #38009c);
  transform: scaleX(0);
}
.center div:nth-child(1):before {
  animation: animate 1s linear forwards;
  transform-origin: right;
  animation-delay: 12s;
}
@keyframes animate {
  0% {
    transform: scaleX(0);
  }
  100% {
    transform: scaleX(1);
  }
}
.center div:nth-child(2):before {
  animation: animate 1s linear forwards;
  transform-origin: left;
  animation-delay: 13s;
}
@keyframes animate {
  0% {
    transform: scaleX(0);
  }
  100% {
    transform: scaleX(1);
  }
}
.center div:nth-child(3):before {
  animation: animate 1s linear forwards;
  transform-origin: right;
  animation-delay: 14s;
}
@keyframes animate {
  0% {
    transform: scaleX(0);
  }
  100% {
    transform: scaleX(1);
  }
}
.center div:nth-child(4):before {
  animation: animate 1s linear forwards;
  transform-origin: left;
  animation-delay: 15s;
  width: 60%;
  left: 0;
}
@keyframes animate {
  0% {
    transform: scaleX(0);
  }
  100% {
    transform: scaleX(1);
  }
}
.center div:nth-child(1):after,
.center div:nth-child(3):after {
  content: '';
  position: absolute;
  bottom: 0;
  left: 0;
  width: 100%;
  height: 50%;
  background: rgba(255, 255, 255, 0.2);
}
.center div h2 {
  position: relative;
  margin: 0;
  padding: 0;
  z-index: 10;
  color: #fff;
  opacity: 0;
}
.center div:nth-child(1) h2 {
  animation: fadeText 0.5s linear forwards;
  animation-delay: 13s;
  font-size: 40px;
}
.center div:nth-child(3) h2 {
  animation: fadeText 0.5s linear forwards;
  animation-delay: 15s;
  font-size: 90px;
  font-weight: 800;
}
@keyframes fadeText {
  0% {
   opacity: 0;
  }
  100% {
   opacity: 1;
  }
}
.loading {
  position: fixed;
  top: 0;
  left:0;
  width: 100%;
  height: 100%;
  background: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
  z-index: 15;
  animation: fadeout 11s linear forwards;
}
@keyframes fadeout {
  0%, 91% {
    opacity: 1;
    visibility: visible;
  }
  100% {
    opacity: 0;
    visibility: hidden;
  }
}
.loading h2 {
  color: #000;
}
.loading .bar {
  position: relative;
  width: 400px;
  height: 40px;
  background: transparent;
  margin: 0 20px;
  border: 2px solid #000;
  box-sizing: border-box;
}
.loading .bar:before {
  content: '';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  background: #000;
  transform-origin: left;
  animation: animate 10s linear forwards;
}
.loading .bar:after {
  content: 'Loading...';
  position: absolute;
  top: 0;
  left: 0;
  width: 100%;
  height: 100%;
  font-weight: 800;
  text-transform: uppercase;
  letter-spacing: 10px;
  text-align: center;
  line-height: 36px;
  color: #fff;
  font-size: 20px;
  mix-blend-mode: difference;
}</style>
</body>
</html>
