<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yourname</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="Box">
        <div class="Box__1 box--btn">
            <a class="btn--tagA" href="login.html">Login</a>
        </div>  
        <div class="Box__2 box--welcome">
            <div class="contents__box">
                <p>Hello, Welcome to</p>
                <h2 class="box--texth2">Your<section>name</section> </h2>
                <div class="box__btnView">
                    <a class="box--btnView" href="../index2.html/index2.html">View to stock</a>
                </div>
            </div>
        </div>
    </div>
</body>
</html>









--------------------------------------------------------------------------------------------------









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
}

.Box {
    position: relative;
    /* border: 1px solid red; */
    height: 10vh;
}
.Box__1 {
    display: flex;
    /* border: 1px solid violet; */
    z-index: 999;
}   .box--btn {
    justify-content: end;
    padding-right: 2rem;
    padding-top: 2rem;
}
.btn--tagA {
    font-size: var(--TagASize);
    border: 1px solid var(--Maincolor);
    color: var(--Maincolor);
    padding: 5px 10px;
    border-radius: 10px;
    transition: transform 0.3s ease 0s, color 0.3s, box-shadow 0.3s;
}
.btn--tagA:hover {
    transform: translateY(-5px);
    color: #5f0f0f;
    /* border: 1px solid #5f0f0f; */
    box-shadow: 0 0 5px #bd1c1c;
}

.Box__2 {
    position: absolute;
    /* border: 1px solid brown; */
    top: 0;
    height: 100vh;
    width: 100vw;
    display: flex;
    align-items: center;
    justify-content: center;
    z-index: -1;
}
.contents__box {
    /* border: 1px solid blue; */
    text-align: center;
    color: var(--Maincolor);
}
.box--texth2 {
    display: flex;
    justify-content: center;
}   .box--texth2 section {
        color:#8d1919
}

.box__btnView {
    display: flex;
    /* border: 1px solid red; */
    margin-top: 1rem;
    justify-content: center;
}
.box--btnView {
    font-size: var(--TagASize);
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
