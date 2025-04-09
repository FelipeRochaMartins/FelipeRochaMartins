<html>
    <head>
        <link rel="preconnect" href="https://fonts.googleapis.com">
        <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
        <link href="https://fonts.googleapis.com/css2?family=VT323&display=swap" rel="stylesheet">
    </head>

    <body>
        <div class="header"></div>
        <div class="infos">
            <div>
                <h1 class="name vt323-regular">Felipe Rocha Martins</h1>
                <h2>Dev .NET / Python</h2>
            </div>
            <div>
                icones das tecnologias que eu sei
            </div>
            <div>
                email
                linkedin
            </div>
        </div>
    </body>
    
    <style>
        html, body {
            padding: 0;
            margin: 0;
            height: 100%;
            font-size: 16px;
            font-family: 'Arial', sans-serif;
        }
    
        /* Importando a fonte VT323 */
        @import url('https://fonts.googleapis.com/css2?family=VT323&display=swap');
    
        .header {
            position: fixed;  /* Fixa a div no topo */
            top: 0;
            left: 0;
            width: 100%;
            background: linear-gradient(180deg, #2296bd 0%, rgba(34, 150, 189, 0.2) 70%, rgba(34, 150, 189, 0) 100%);
            background-size: 120% 100%;
            height: 40%; /* Altura inicial */
            animation: animateHeader 3s cubic-bezier(1, -1.28, .81, 1.26) infinite;
            display: flex;
            flex-direction: column;
            justify-content: center;
            z-index: -1;
        }
    
        @keyframes animateHeader {
            0%, 100% {
                height: 40%;
                background-size: 120% 100%;
            }
            50% {
                height: 50%;
                background-size: 150% 100%;
            }
        }
    
        .infos {
            display: flex;
            flex-direction: column;
            justify-content: center;
            align-items: center;
            text-align: center;
            padding-top: 50px;
        }
    
        .vt323-regular {
            font-family: "VT323", monospace;
            font-weight: 400;
            font-style: normal;
        }
    
        .name {
            font-size: 4.5rem;
            color: #fff;
            -webkit-text-stroke-width: 1.5px;
            -webkit-text-stroke-color: black;
            overflow: hidden;
            border-right: 4px solid #000; /* Criando o cursor piscante */
            width: 0; /* Inicialmente o texto está oculto */
            white-space: nowrap;
            animation: typing 2s steps(10) 1s 1 normal both, blinkCaret 0.75s step-end infinite, erase 8s steps(30) 2 normal both;
        }
    
        @keyframes typing {
            0% {
                width: 0;
            }
            50% {
                width: 50%;
            }
            100% {
                width: 100%;
            }
        }
    
        @keyframes blinkCaret {
            50% {
                border-color: transparent;
            }
        }
    
        h2 {
            font-size: 24px;
            color: #666;
        }
    </style>
    
</html>
