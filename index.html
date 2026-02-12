# 14defebrero

<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Para Alguien Especial ❤️</title>
    <style>
        /* ESTILOS GENERALES (Beige y Blanco) */
        body {
            background-color: #f5f5dc; /* Beige suave */
            font-family: 'Poppins', sans-serif; /* Fuente moderna */
            margin: 0;
            display: flex;
            justify-content: center;
            align-items: center;
            height: 100vh;
            overflow: hidden; /* Evita barras de desplazamiento al mover botones */
            color: #5a3e2b; /* Color de texto oscuro para contraste */
            font-size: 1.1em;
        }

        .container {
            background: white;
            padding: 40px;
            border-radius: 20px;
            box-shadow: 0 10px 30px rgba(0,0,0,0.05); /* Sombra suave */
            text-align: center;
            max-width: 450px; /* Ancho máximo para el contenido */
            width: 90%;
            z-index: 10; /* Asegura que esté por encima de los corazones */
            position: relative; /* Para posicionar elementos internos si es necesario */
        }

        .hidden { display: none !important; }

        /* BOTONES */
        button {
            padding: 12px 28px;
            font-size: 17px;
            border-radius: 50px; /* Botones redondos */
            border: none;
            cursor: pointer;
            transition: all 0.3s ease; /* Transición suave para cambios */
            margin: 10px;
            font-weight: bold;
            letter-spacing: 0.5px;
        }

        #btnSi { background-color: #f1c6c1; color: white; } /* Rosa suave para "Sí" */
        #btnNo { background-color: #eeeeee; color: #888; } /* Gris claro para "No" */
        #btnSi:hover { transform: scale(1.05); background-color: #e0b0b0; }
        #btnNo:hover { transform: scale(1.05); }

        input {
            padding: 12px;
            border: 1px solid #ddd;
            border-radius: 10px;
            width: 70%; /* Ancho del input */
            margin-bottom: 20px;
            text-align: center;
            font-size: 1.05em;
            color: #5a3e2b;
        }

        /* LLUVIA DE CORAZONES */
        .heart {
            position: fixed;
            top: -20px; /* Empiezan fuera de la pantalla */
            font-size: 25px;
            animation: fall 3s linear forwards;
            color: #ff7a85; /* Corazones rojos */
            pointer-events: none; /* Para que no interfieran con clics */
            z-index: 5;
        }

        @keyframes fall {
            to { transform: translateY(100vh) rotate(360deg); opacity: 0; }
        }

        /* SOBRE Y CARTA */
        .envelope {
            width: 180px;
            height: 120px;
            background: #f1c6c1; /* Color del sobre */
            margin: 20px auto;
            position: relative;
            cursor: pointer;
            border-radius: 0 0 10px 10px; /* Bordes inferiores redondeados */
            box-shadow: 0 5px 15px rgba(0,0,0,0.1);
        }
        .flap {
            position: absolute;
            top: 0; left: 0;
            border-left: 90px solid transparent; /* Mitad del ancho */
            border-right: 90px solid transparent; /* Mitad del ancho */
            border-top: 60px solid #f5b1aa; /* Color de la solapa ligeramente más oscuro */
            transition: transform 0.6s ease-in-out;
            transform-origin: top;
        }
        .open-flap { transform: rotateX(180deg); } /* Gira la solapa */
        
        .letter-content {
            background: #fff;
            padding: 25px;
            border-radius: 15px;
            border: 1px solid #eee;
            margin-top: 25px;
            font-style: italic;
            line-height: 1.6;
            text-align: left;
            box-shadow: 0 5px 15px rgba(0,0,0,0.05);
        }

        /* IMAGEN DEL CORAZÓN BLANCO */
        #sanValentinImg {
            width: 120px; /* Tamaño de la imagen */
            height: auto;
            margin-bottom: 25px;
        }

        /* Estilos para el botón NO en movimiento */
        #btnNo.moving {
            position: fixed; /* Ojo: 'fixed' para que se mueva por toda la pantalla, no solo el container */
            z-index: 20; /* Asegura que esté por encima de todo */
        }
    </style>
</head>
<body>

    <div id="pantalla1" class="container">
        <h2>Ingresa nuestra fecha especial</h2>
        <p>(Formato: DD/MM/AA)</p>
        <input type="text" id="fechaInput" placeholder="19/01/25" maxlength="8">
        <br>
        <button onclick="validarFecha()">Entrar ❤️</button>
    </div>

    <div id="pantalla2" class="container hidden">
        <h1>¿Quieres ser mi San Valentín?</h1>
        <img id="sanValentinImg" src="https://upload.wikimedia.org/wikipedia/commons/4/42/White_heart_icon.png" alt="Corazón blanco">
        <div style="margin-top: 30px; position: relative;">
            <button id="btnSi" onclick="mostrarCarta()">¡SÍ! 😍</button>
            <button id="btnNo" onmouseover="moverNo()" onclick="moverNo()">No 💔</button>
        </div>
    </div>

    <div id="pantalla3" class="container hidden">
        <div class="envelope" onclick="abrirSobre()">
            <div id="flap" class="flap"></div>
        </div>
        <div id="cartaTexto" class="hidden">
            <div class="letter-content">
                <h3>Mi amorcito... ❤️</h3>
                <p>
                    Desde aquel 19 de enero, cada día a tu lado es un regalo.
                    Eres la persona que ilumina mis días y hace mi mundo más bonito.
                    Gracias por cada risa, cada abrazo y cada momento compartido.
                    ¡Espero que este San Valentín sea el primero de muchos!
                    Te quiero con todo mi corazón.
                </p>
                <p>Con todo mi cariño, [Tu Nombre]</p>
            </div>
        </div>
    </div>

    <script>
        let escalaSi = 1; // Escala inicial del botón "Sí"

        // Función para la lluvia de corazones
        function lluvia() {
            for (let i = 0; i < 70; i++) { // Más corazones para un efecto más bonito
                let h = document.createElement("div");
                h.innerHTML = "❤️";
                h.classList.add("heart");
                h.style.left = Math.random() * 100 + "vw"; // Posición horizontal aleatoria
                h.style.animationDuration = (Math.random() * 2 + 2.5) + "s"; // Duración de caída aleatoria
                h.style.fontSize = (Math.random() * 15 + 15) + "px"; // Tamaño aleatorio
                document.body.appendChild(h);
                setTimeout(() => h.remove(), 3000); // Eliminar después de caer
            }
        }

        // Función para validar la fecha
        function validarFecha() {
            const input = document.getElementById("fechaInput").value.trim(); // Elimina espacios
            if(input === "19/01/25") {
                lluvia();
                setTimeout(() => {
                    document.getElementById("pantalla1").classList.add("hidden");
                    document.getElementById("pantalla2").classList.remove("hidden");
                }, 2500); // Espera un poco más para que se vea bien la lluvia
            } else {
                alert("Esa no es la fecha especial... ¡Piensa bien! 😉");
            }
        }

        // Función para mover el botón "No" y crecer el "Sí"
        function moverNo() {
            const btnNo = document.getElementById("btnNo");
            const btnSi = document.getElementById("btnSi");
            
            // Calcula nuevas posiciones aleatorias dentro de la ventana visible
            const newX = Math.random() * (window.innerWidth - btnNo.offsetWidth - 20);
            const newY = Math.random() * (window.innerHeight - btnNo.offsetHeight - 20);

            btnNo.style.position = "fixed"; // Usa 'fixed' para que se mueva por toda la ventana
            btnNo.style.left = newX + "px";
            btnNo.style.top = newY + "px";
            btnNo.classList.add("moving"); // Añade una clase para los estilos de movimiento

            // Aumenta la escala del botón "Sí"
            escalaSi += 0.2; // Incremento más sutil
            btnSi.style.transform = `scale(${escalaSi})`;
        }

        // Función para mostrar la pantalla de la carta
        function mostrarCarta() {
            document.getElementById("pantalla2").classList.add("hidden");
            document.getElementById("pantalla3").classList.remove("hidden");
        }

        // Función para abrir el sobre
        function abrirSobre() {
            document.getElementById("flap").classList.add("open-flap");
            setTimeout(() => {
                document.getElementById("cartaTexto").classList.remove("hidden");
            }, 600); // Tiempo para que la solapa se abra antes de mostrar la carta
        }
    </script>
</body>
</html>
