<head>
    <link rel="preconnect" href="https://fonts.googleapis.com">
    <link href="https://fonts.googleapis.com/css2?family=Caprasimo&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Oswald:wght@200..700&display=swap" rel="stylesheet">
    <link href="https://fonts.googleapis.com/css2?family=Anton+SC&display=swap" rel="stylesheet">
    <style>
        .container{
            display:flex;
            justify-content: center;
            align-items: center;
            flex-direction: column;
            background-color: #4f4fff;
            width: 100vw;
            height: 100vh;
            position: relative;
        }
        h1{
            font-family: "Anton SC", sans-serif;
            color:#07062b;
            font-size: 82px;
            padding-bottom: 2px;
            position:absolute;
            top:21%;
        }
        .waveContainer{
            display:flex;
            transform: rotateZ(-2deg);
            right:31%;
            top:45%;
        }
        .waveText span {
            display: inline-block;
            font-family: "Caprasimo", serif;
            font-size: 110px;
            color:white;
            animation: wave 1.3s ease-in-out infinite;
        }
        .waveText span:nth-child(1) {
            animation-delay: 0s;
        }
        .waveText span:nth-child(2) {
            animation-delay: 0.1s;
        }
        .waveText span:nth-child(3) {
            animation-delay: 0.2s;
        }
        .waveText span:nth-child(4) {
            animation-delay: 0.3s;
        }
        .waveText span:nth-child(5) {
            animation-delay: 0.4s;
        }
        .waveText span:nth-child(6) {
            animation-delay: 0.5s;
        }
        @keyframes wave {
            0%, 100% {
                transform: translateY(0);
            }
            50% {
                transform: translateY(-15px);
            }
        }
        p{
            color:white;
            font-family: "Oswald", sans-serif;
            font-size: 20px;
        }
    </style>
</head>
<div class="container">
        <h1>Hi! My name is</h1>
        <div class="waveContainer">
            <p class="waveText">
                <span>M</span><span>O</span><span>Z</span><span>Z</span><span>E</span><span>R</span>
            </p>
        </div>
        <p>
            Meu nome é Heitor e eu sou graphic designer e programador.
        </p>
        <img src="./assets/casagrandeBLob.svg" alt="" id="casagrandeBlob" width="20%">
        <p align='center'>E essa é minha criatura <br> Kate Casagrande</p>
    </div>