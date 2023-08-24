<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yourname</title>
    <link rel="stylesheet" href="login.css">
</head>
<body>
    <div class="Box">
        <h1>ขอเงิน <section>"หน่อย"</section>ข่าบบบ</h1>
        <div class="InputBox">
            <input class="input" type="text"> <p>มีให้แค่นี้นะ</p>
        </div>
        <div class="box__btnView">
            <a class="box--btnView" href="index01.html">อยากกลับหน้าเดิมก็กดหนูนะ</a>
        </div>
    </div>
    
</body>
</html>









-------------------------------------------------------------------------------------









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
body {
    /* border: 1px solid red; */
    height: 100vh;
    display: flex;
    align-items: center;
    justify-content: center;
}
h1 {
    color: var(--Maincolor);
    display: flex;
}
h1 section {
    color: #bd1c1c;
}
.Box{
    align-items: center;
    justify-content: center;
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
.input {
    justify-content: center;
    display: inline-block;
    border-radius: 5px;
    width: 100px;
    padding: 0 10px;
}
.InputBox {
    color: var(--Maincolor);
    /* border: 1px solid red; */
    display: flex;
    justify-content: center;
}
p {
    margin-left: 1rem;
}
