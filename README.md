<!DOCTYPE html>
<html lang="es">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Encuentra Paz y Consuelo</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            text-align: center;
            padding: 50px;
            background-color: #FFC0CB; /* Fondo rosado */
            background-image: url('data:image/svg+xml;utf8,<svg xmlns="http://www.w3.org/2000/svg" viewBox="0 0 100 100"><text x="10" y="20" font-size="20" fill="red">❤️</text><text x="50" y="50" font-size="20" fill="red">❤️</text><text x="20" y="80" font-size="20" fill="red">❤️</text></svg>');
            background-repeat: repeat; /* Repetir corazones rojos dispersos */
        }
        .button {
            display: block;
            margin: 10px auto;
            padding: 10px 20px;
            font-size: 16px;
            color: red; /* Letras rojas */
            background-color: white; /* Botones blancos */
            border: 2px solid black; /* Bordes negros */
            border-radius: 5px;
            cursor: pointer;
            width: 200px;
        }
        .button:hover {
            background-color: #f1f1f1; /* Color más claro al pasar el cursor */
        }
        .content {
            display: none;
            margin: 20px auto;
            padding: 20px;
            border: 1px solid black; /* Borde negro para el mensaje */
            border-radius: 10px;
            max-width: 600px;
            background-color: #f9f9f9;
        }
    </style>
</head>
<body>
    <h1>Encuentra Paz y Consuelo</h1>
    <p>¿Estás enfrentando desafíos emocionales? Haz clic en el botón que mejor describa lo que sientes y encuentra palabras de aliento y guía espiritual.</p>
    
    <button class="button" onclick="showContent('miedo')">Miedo</button>
    <button class="button" onclick="showContent('tristeza')">Tristeza</button>
    <button class="button" onclick="showContent('dolor')">Dolor</button>
    <button class="button" onclick="showContent('ansiedad')">Ansiedad</button>
    <button class="button" onclick="showContent('soledad')">Soledad</button>
    <button class="button" onclick="showContent('desesperanza')">Desesperanza</button>
    <button class="button" onclick="showContent('ira')">Ira</button>
    <button class="button" onclick="showContent('culpa')">Culpa</button>
    
    <div id="miedo" class="content">
        <h2>Miedo</h2>
        <p><strong>Isaías 41:10:</strong> "No temas, porque yo estoy contigo; no te desalientes, porque yo soy tu Dios. Te fortaleceré, ciertamente te ayudaré, sí, te sostendré con la diestra de mi justicia."</p>
        <p>Recuerda que en momentos de miedo, puedes encontrar consuelo y fortaleza en Dios. Ora y confía en su presencia para superar cualquier temor.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="tristeza" class="content">
        <h2>Tristeza</h2>
        <p><strong>Salmos 34:18:</strong> "El Señor está cerca de los quebrantados de corazón y salva a los de espíritu abatido."</p>
        <p>En momentos de tristeza, busca la cercanía del Señor. Él está siempre dispuesto a consolarte y levantarte en tus peores momentos.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="dolor" class="content">
        <h2>Dolor</h2>
        <p><strong>Mateo 11:28:</strong> "Vengan a mí, todos los que están cansados y cargados, y yo les haré descansar."</p>
        <p>En tiempos de dolor, acude a Jesús. Él promete darte descanso y aliviar tus cargas más pesadas.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="ansiedad" class="content">
        <h2>Ansiedad</h2>
        <p><strong>Filipenses 4:6-7:</strong> "No se inquieten por nada; más bien, en toda ocasión, con oración y ruego, presenten sus peticiones a Dios y denle gracias. Y la paz de Dios, que sobrepasa todo entendimiento, cuidará sus corazones y sus pensamientos en Cristo Jesús."</p>
        <p>Cuando la ansiedad te abrume, entrega tus preocupaciones a Dios a través de la oración. Su paz guardará tu corazón y mente.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="soledad" class="content">
        <h2>Soledad</h2>
        <p><strong>Deuteronomio 31:8:</strong> "El Señor mismo va delante de ti y estará contigo; nunca te dejará ni te abandonará. No temas ni te desanimes."</p>
        <p>En momentos de soledad, recuerda que Dios siempre está contigo. Él nunca te abandonará, incluso en tus momentos más oscuros.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="desesperanza" class="content">
        <h2>Desesperanza</h2>
        <p><strong>Jeremías 29:11:</strong> "Porque yo sé muy bien los planes que tengo para ustedes —afirma el Señor—, planes de bienestar y no de calamidad, a fin de darles un futuro y una esperanza."</p>
        <p>Cuando sientas desesperanza, confía en que Dios tiene planes de bienestar y esperanza para ti. Su propósito para ti es bueno.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="ira" class="content">
        <h2>Ira</h2>
        <p><strong>Efesios 4:26:</strong> "Enójense, pero no pequen; no se ponga el sol sobre su enojo."</p>
        <p>La ira puede ser poderosa, pero no permitas que te domine. Busca resolver tus conflictos y encuentra paz antes de que termine el día.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>
    
    <div id="culpa" class="content">
        <h2>Culpa</h2>
        <p><strong>1 Juan 1:9:</strong> "Si confesamos nuestros pecados, Dios, que es fiel y justo, nos los perdonará y nos limpiará de toda maldad."</p>
        <p>Cuando te sientas culpable, recuerda que puedes confesarte a Dios. Él es fiel para perdonarte y limpiarte de toda maldad.</p>
        <button class="button" onclick="hideContent()">Volver</button>
    </div>

    <script>
        function showContent(contentId) {
            var contents = document.querySelectorAll('.content');
            contents.forEach(function(content) {
                content.style.display = 'none';
            });
            document.getElementById(contentId).style.display = 'block';
        }

        function hideContent() {
            var contents = document.querySelectorAll('.content');
            contents.forEach(function(content) {
                content.style.display = 'none';
            });
        }
    </script>
</body>
</html>
