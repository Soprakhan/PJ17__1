<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yourname</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="box__btnVBack">
        <a class="box--btnVBack" href="../index01/index1.html">กลับไปก่อนหน้านี้นะค่ะอิอิ</a>
    </div>
    <div class="navber">
        <div class="Texthead"><h2>เลือก "หมวดหมู่" เลยจร้า</h2></div>
    </div>
    <div class="main">
        <div class="card">
            <div class="card__box">
                <div class="box__btnView">
                    <a class="box--btnView" href="../index02/index2.html">
                        <div class="content">
                            <h1>prop</h1>
                        </div>
                        <div class="img">
                            <img src="../สินค้า/prop03.1.png" alt="">
                        </div>
                    </a>
                </div>
            </div>
        </div>
        <div class="card card--1">
            <div class="card__box">
                <div class="box__btnView box--1">
                    <a class="box--btnView" href="../index02/index2.html">
                        <div class="content">
                            <h1>anim</h1>
                        </div>
                        <div class="img">
                            <img src="../สินค้า/anim03.png" alt="">
                        </div>
                    </a>
                </div>
            </div>
        </div>
        <div class="card">
            <div class="card__box">
                <div class="box__btnView">
                    <a class="box--btnView" href="../index02/index2.html">
                        <div class="content">
                            <h1>eye</h1>
                        </div>
                        <div class="img">
                            <img src="../สินค้า/eye01.png" alt="">
                        </div>
                    </a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>









---------------------------------------------------------------------------









@import url('https://fonts.googleapis.com/css2?family=Noto+Sans+Thai:wght@500&display=swap');
:root {
    --Maincolor : #353535;
    --TagASize : 15px;
}
* {
    margin: 0;
    padding: 0;
    box-sizing: border-box;
    font-family: 'Noto Sans Thai', sans-serif;
    scroll-behavior: smooth;
    list-style: none;
    text-decoration: none;
    color: var(--Maincolor);
}
body {
    overflow: hidden;
}
.navber {
    /* border: 1px solid red; */
    text-align: center;
    margin: 1rem 0 0 0;
    font-size: var(--TagASize);
}
.main {
    /* border: 1px solid rgb(150, 33, 33); */
    height: 83.8vh;
    display: flex;
}
.card {
    padding: 5rem 1rem;
    margin: 0 auto;
}
.card__box {
    /* border: 1px solid brown; */
    width: 25vw;
    height: 55vh;

}
.img {
    width: 25vw;
    /* border: 1px solid black; */
}   .img img {
    width: 100%;
}
.content {
    text-align: center;
}
.box__btnView {
    display: flex;
    /* border: 1px solid red; */
    margin-top: 1rem;
    justify-content: center;
}
.box--btnView {
    font-size: var(--TagASize);
    height: 40vh;
    border: 1px solid var(--Maincolor);
    color: var(--Maincolor);
    padding: 10px 15px;
    border-radius: 10px;
    transition: transform 0.3s ease 0s, color 0.3s, box-shadow 0.3s;
}
.box--btnView:hover {
    transform: translateY(-5px);
    color: #5f0f0f;
    border: 1px solid #5f0f0f;
    box-shadow: 0 0 5px #bd1c1c;
}
.box__btnVBack {
    display: flex;
    /* border: 1px solid red; */
    margin-top: 1rem;
    margin-left: 1rem;
    justify-content: left;
}
.box--btnVBack {
    font-size: var(--TagASize);
    border: 1px solid var(--Maincolor);
    color: var(--Maincolor);
    padding: 10px 15px;
    border-radius: 10px;
    transition: transform 0.3s ease 0s, color 0.3s, box-shadow 0.3s;
}
.box--btnVBack:hover {
    transform: translateY(-5px);
    color: #5f0f0f;
    border: 1px solid #5f0f0f;
    box-shadow: 0 0 5px #bd1c1c;
}

.box--1 img {
    margin-top: 1rem;
}
