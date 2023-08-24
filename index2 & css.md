<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yourname</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="navber">
        <div class="Texthead"><h2>เลือก"หมวดหมู่"เลยจร้า</h2></div>
    </div>
    <div class="main">
        <div class="card">
            <div class="card__box">
                
            </div>
            <div class="card__box">

            </div>
            <div class="card__box">

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
}
/* body {
    overflow: hidden;
} */
.navber {
    border: 1px solid red;
    text-align: center;
    padding: 2rem 0;
    font-size: var(--TagASize);
}
.main {
    border: 1px solid rgb(150, 33, 33);
    height: 83.8vh;
}
.card {
    border: 1px solid black;
    height: 100%;
    display: flex;
    padding: 5rem 10%;
}
.card__box {
    display: flex;
    border: 1px solid brown;
    width: 25vw;
    height: 55vh;
    margin: 0 1rem

}
