<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Yourname</title>
    <link rel="stylesheet" href="style.css">
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
    <link href="https://fonts.googleapis.com/css2?family=Quicksand:wght@300;400;500;600;700&display=swap" rel="stylesheet">
</head>
<body>
    <div class="Box">
        <div class="Contents_box">
            <div class="baby__box">
                <b>
                    <p class="main--p">
                        Hello, welcome to
                    </p>
                    <h1 class="main--h1">
                        Your <section class="h1--sec">name</section>
                    </h1>
                    <div class="main__a">
                        <a class="main--a" href="index2.html">View to stock</a>
                    </div>
                </b>
            </div>
        </div>
    </div>
</body>
</html>









--------------------------------------------------------------------------------------------------









* {
    box-sizing: border-box;
    font-family: 'Quicksand', sans-serif;
    text-decoration: none;
    margin: 0;
    padding: 0;
}

.Box {
    /* border:  1px solid black; */
    display: flex;
    justify-content: center;
    margin: 5% auto;
}
.Contents_box {
    /* border: 1px solid red; */
    width: 500px;
    height: 500px;
    display: flex;
    justify-content: center;
    align-items: center;
}
.baby__box {
    /* border: 1px solid violet; */
    text-align: center;
    padding: 5rem;
    border-radius: 30px;
    width: 500px;
    /* box-shadow: 0 0 10px black; */
}   .main--h1 {
    display: flex;
    align-items: center; justify-content: center;
}   .h1--sec {
    color: green;
}   .main__a {
    display: flex;
    margin-top: 1rem;
    /* padding-top: 1rem; */
    border-radius: 10px;
    justify-content: center;
    align-items: center;
    /* box-shadow: 0 0 5px black; */
}   .main--a {
    color: black;
    border: 1px solid rgb(0, 0, 0);
    border-radius: 10px;
    padding: 15px 40px;
    transition: transform 0.3s ease 0s, color 0.3s, box-shadow 0.3s;
}   .main--a:hover {
    transform: translateY(-5px);
    color: #5f0f0f;
    border: 1px solid #5f0f0f;
    box-shadow: 0 0 5px #bd1c1c;
}
