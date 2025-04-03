<svg viewBox="0 0 600 300" xmlns="http://www.w3.org/2000/svg">
    <style>
        @keyframes typing {
            from { width: 0 }
            to { width: 100% }
        }

        @keyframes blink {
            50% { border-color: transparent }
        }

        .terminal {
            font-family: monospace;
            font-size: 18px;
            white-space: nowrap;
            overflow: hidden;
            width: 0;
            border-right: 2px solid;
            animation: typing 3s steps(40, end) forwards, blink 0.7s step-end infinite;
        }
    </style>

    <rect width="100%" height="100%" fill="#282C34" rx="10"/>
    <text x="20" y="50" fill="#61DAFB" class="terminal">
        Olá! Meu nome é Laura, tenho 18 anos e sou estudante de programação.
    </text>
    <text x="20" y="100" fill="#F8F8F2" class="terminal" style="animation-delay: 3s;">
        Linguagens e tecnologias que estou aprendendo:
    </text>
    
    <image x="20" y="130" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/html5/html5-original.svg"/>
    <image x="70" y="130" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/css3/css3-original.svg"/>
    <image x="120" y="130" width="40" height="40" href="https://cdn.jsdelivr.net/gh/devicons/devicon/icons/javascript/javascript-original.svg"/>
</svg>
