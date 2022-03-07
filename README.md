#   🍉 Loading Page Template
<p> css y html 100% Personalizable </p>
⬇️Visita La Demo⬇️ 
<div> </div>

[Loading Page](https://9s8f8eg8347y4h.glitch.me/)

---

<h2 align="center"> 💻 Código </h2>

<div> </div>
<h3 align="center"> HTML </h3>

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <div class="ring"></div>
        <div class="ring"></div>
        <div class="ring"></div>
        <p>
            <span style="--i:1;">C</span>
            <span style="--i:2;">a</span>
            <span style="--i:3;">r</span>
            <span style="--i:4;">g</span>
            <span style="--i:5;">a</span>
            <span style="--i:6;">n</span>
            <span style="--i:7;">d</span>
            <span style="--i:8;">o</span>
            <span style="--i:9;">.</span>
            <span style="--i:10;">.</span>
            <span style="--i:10;">.</span>
        </p>
    </div>
</body>
</html>
<style>
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #111;
}
.container{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container .ring{
    position: relative;
    width: 150px;
    height: 150px;
    margin: -30px;
    border-radius: 50%;
    border:4px solid transparent;
    border-top:4px solid #24ecff;
    animation:animate 4s linear infinite;
}
@keyframes animate {
    0%{
        transform:rotate(0deg)
    }
    100%{
        transform:rotate(360deg)
    }
    
}
@keyframes animate2 {
    0%{
        transform:rotate(360deg)
    }
    100%{
        transform:rotate(0deg)
    }
    
}
.container .ring::before{
    content:'';
    position: absolute;
    top:12px;
    right: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #24ecff;
    box-shadow: 0 0 0 5px #24ecff33,
    0 0 10px #24ecff22,
    0 0 20px #24ecff11,
    0 0 20px #24ecff,
    0 0 20px #24ecff;
}

.container .ring:nth-child(2){
    animation : animate2 4s linear infinite;
    animation-delay: -1s;
    border-top: 4px solid transparent;
    border-left: 4px solid #93ff2d;
}
.container .ring:nth-child(2)::before{
    content:'';
    position: absolute;
    top:initial;
    top:12px;
    left: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #93ff2d;
    box-shadow: 0 0 0 5px #93ff2d33,
    0 0 10px #93ff2d22,
    0 0 20px #93ff2d11,
    0 0 20px #93ff2d,
    0 0 20px #93ff2d;
}

.container .ring:nth-child(3){
    animation : animate2 4s linear infinite;
    animation-delay: -3s;
    position: absolute;
    top: -66.66px;
    border-top: 4px solid transparent;
    border-left: 4px solid #e11cf8;
}
.container .ring:nth-child(3)::before{
    content:'';
    position: absolute;
    top:initial;
    top:12px;
    left: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #e11cf8;
    box-shadow: 0 0 0 5px #e11cf833,
    0 0 10px #e11cf822,
    0 0 20px #e11cf811,
    0 0 20px #e11cf8,
    0 0 20px #e11cf8;
}
.container p{
    position: absolute;
    color: #fff;
    font-size: 1.5em;
    font-family: consolas;
    bottom: -80px;
    letter-spacing: 0.2em;
}
p span{
    animation: animate3 5s linear infinite;
    animation-delay: calc(0.3s * var(--i));
}
@keyframes animate3 {
    0%{
        color: #fff;
        filter:blur(0) hue-rotate(0deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff,
        0 0 300px #00b3ff,
        0 0 400px #00b3ff;
    }
    30%,70%{
        color: #fff;
        filter:blur(0.5px) hue-rotate(360deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff;
    }
    100%{
        color: transparent;
        box-shadow: none;
        filter:blur(1px) hue-rotate(360deg);
        
    }
}
</style>
```

<h3 align="center">  CSS </h3>

```css
*{
    margin: 0;
    padding: 0;
    box-sizing: border-box;
}
body{
    display: flex;
    justify-content: center;
    align-items: center;
    min-height: 100vh;
    background: #111;
}
.container{
    position: relative;
    width: 100%;
    display: flex;
    justify-content: center;
    align-items: center;
}
.container .ring{
    position: relative;
    width: 150px;
    height: 150px;
    margin: -30px;
    border-radius: 50%;
    border:4px solid transparent;
    border-top:4px solid #24ecff;
    animation:animate 4s linear infinite;
}
@keyframes animate {
    0%{
        transform:rotate(0deg)
    }
    100%{
        transform:rotate(360deg)
    }
    
}
@keyframes animate2 {
    0%{
        transform:rotate(360deg)
    }
    100%{
        transform:rotate(0deg)
    }
    
}
.container .ring::before{
    content:'';
    position: absolute;
    top:12px;
    right: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #24ecff;
    box-shadow: 0 0 0 5px #24ecff33,
    0 0 10px #24ecff22,
    0 0 20px #24ecff11,
    0 0 20px #24ecff,
    0 0 20px #24ecff;
}

.container .ring:nth-child(2){
    animation : animate2 4s linear infinite;
    animation-delay: -1s;
    border-top: 4px solid transparent;
    border-left: 4px solid #93ff2d;
}
.container .ring:nth-child(2)::before{
    content:'';
    position: absolute;
    top:initial;
    top:12px;
    left: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #93ff2d;
    box-shadow: 0 0 0 5px #93ff2d33,
    0 0 10px #93ff2d22,
    0 0 20px #93ff2d11,
    0 0 20px #93ff2d,
    0 0 20px #93ff2d;
}

.container .ring:nth-child(3){
    animation : animate2 4s linear infinite;
    animation-delay: -3s;
    position: absolute;
    top: -66.66px;
    border-top: 4px solid transparent;
    border-left: 4px solid #e11cf8;
}
.container .ring:nth-child(3)::before{
    content:'';
    position: absolute;
    top:initial;
    top:12px;
    left: 12px;
    border-radius: 50%;
    width: 15px;
    height: 15px;
    background: #e11cf8;
    box-shadow: 0 0 0 5px #e11cf833,
    0 0 10px #e11cf822,
    0 0 20px #e11cf811,
    0 0 20px #e11cf8,
    0 0 20px #e11cf8;
}
.container p{
    position: absolute;
    color: #fff;
    font-size: 1.5em;
    font-family: consolas;
    bottom: -80px;
    letter-spacing: 0.2em;
}
p span{
    animation: animate3 5s linear infinite;
    animation-delay: calc(0.3s * var(--i));
}
@keyframes animate3 {
    0%{
        color: #fff;
        filter:blur(0) hue-rotate(0deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff,
        0 0 300px #00b3ff,
        0 0 400px #00b3ff;
    }
    30%,70%{
        color: #fff;
        filter:blur(0.5px) hue-rotate(360deg);
        text-shadow: 0 0 10px #00b3ff,
        0 0 20px #00b3ff,
        0 0 40px #00b3ff,
        0 0 80px #00b3ff,
        0 0 120px #00b3ff,
        0 0 200px #00b3ff;
    }
    100%{
        color: transparent;
        box-shadow: none;
        filter:blur(1px) hue-rotate(360deg);
        
    }
}
```
