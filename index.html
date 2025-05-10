<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>¿Qué tipo de oblea eres?</title>
  <style>
    body {
      font-family: 'Arial', sans-serif;
      background: url('https://images.unsplash.com/photo-1589987601445-54d4fe4f776b?ixlib=rb-4.0.3&auto=format&fit=crop&w=1500&q=80');
      background-size: cover;
      background-repeat: no-repeat;
      color: #333;
      margin: 0;
      padding: 0;
      overflow-x: hidden;
    }
    .overlay {
      background-color: rgba(255, 240, 245, 0.85);
      min-height: 100vh;
      padding: 30px;
      position: relative;
    }
    h1 {
      text-align: center;
      color: #c71585;
      font-size: 2.5em;
      margin-top: 20px;
    }
    .start-screen, .question-screen, .result {
      max-width: 700px;
      margin: 30px auto;
      background: #fff;
      padding: 30px;
      border-radius: 20px;
      box-shadow: 0 0 15px rgba(199, 21, 133, 0.3);
      display: none;
    }
    .question h3 {
      color: #d63384;
    }
    label {
      display: block;
      margin: 10px 0;
      background: #ffe4e1;
      padding: 10px;
      border-radius: 10px;
      cursor: pointer;
    }
    button {
      background: #ff69b4;
      color: white;
      border: none;
      padding: 12px 25px;
      border-radius: 15px;
      font-size: 16px;
      cursor: pointer;
      display: block;
      margin: 20px auto 0;
    }
    .visible {
      display: block;
    }

  </style>
</head>
<body>
  <div class="overlay">
    <h1>🌷 ¿Qué tipo de oblea eres? 🌷</h1>

    <div class="start-screen visible" id="startScreen">
      <p style="text-align:center; font-size: 1.2em;">Un test dulce para descubrir tu estilo único 🍓🌸</p>
      <button onclick="empezarTest()">Empezar</button>
    </div>

    <form id="quizForm">
      <div class="question-screen" id="q1">
        <h3>1. ¿Qué plan prefieres para un domingo?</h3>
        <label><input type="radio" name="q1" value="a"> Ver pelis con snacks dulces</label>
        <label><input type="radio" name="q1" value="b"> Salir a caminar y tomar fotos</label>
        <label><input type="radio" name="q1" value="c"> Ir a un café con amigos</label>
        <label><input type="radio" name="q1" value="d"> Escuchar música mientras dibujas</label>
      </div>
      <div class="question-screen" id="q2">
        <h3>2. ¿Qué sabor te gusta más?</h3>
        <label><input type="radio" name="q2" value="a"> Arequipe clásico</label>
        <label><input type="radio" name="q2" value="b"> Frutas como mora o guanábana</label>
        <label><input type="radio" name="q2" value="c"> Chocolate</label>
        <label><input type="radio" name="q2" value="d"> Coco o sabores exóticos</label>
      </div>
      <div class="question-screen" id="q3">
        <h3>3. ¿Cómo describirías tu personalidad?</h3>
        <label><input type="radio" name="q3" value="a"> Dulce y amigable</label>
        <label><input type="radio" name="q3" value="b"> Soñadora y creativa</label>
        <label><input type="radio" name="q3" value="c"> Divertida y energética</label>
        <label><input type="radio" name="q3" value="d"> Tranquila pero única</label>
      </div>
      <div class="question-screen" id="q4">
        <h3>4. ¿Qué red social usas más?</h3>
        <label><input type="radio" name="q4" value="a"> Instagram</label>
        <label><input type="radio" name="q4" value="b"> Pinterest</label>
        <label><input type="radio" name="q4" value="c"> TikTok</label>
        <label><input type="radio" name="q4" value="d"> Tumblr</label>
      </div>
      <div class="question-screen" id="q5">
        <h3>5. Si fueras un postre, serías...</h3>
        <label><input type="radio" name="q5" value="a"> Brownie caliente</label>
        <label><input type="radio" name="q5" value="b"> Cheesecake de frutos rojos</label>
        <label><input type="radio" name="q5" value="c"> Helado con toppings</label>
        <label><input type="radio" name="q5" value="d"> Flan con un toque diferente</label>
      </div>
    </form>

    <div class="result" id="resultado"></div>
  </div>

  <script>
    const preguntas = ['q1', 'q2', 'q3', 'q4', 'q5'];
    let preguntaActual = 0;

    function empezarTest() {
      document.getElementById('startScreen').classList.remove('visible');
      mostrarPregunta(preguntas[preguntaActual]);


    }

    function mostrarPregunta(id) {
      document.getElementById(id).classList.add('visible');
      const opciones = document.getElementsByName(id);
      for (let opcion of opciones) {
        opcion.onclick = () => {
          document.getElementById(id).classList.remove('visible');
          preguntaActual++;
          if (preguntaActual < preguntas.length) {
            mostrarPregunta(preguntas[preguntaActual]);
          } else {
            mostrarResultado();
          }
        };
      }
    }

    function mostrarResultado() {
      const form = document.getElementById('quizForm');
      const conteo = { a: 0, b: 0, c: 0, d: 0 };

      for (let r of preguntas) {
        const seleccionada = form[r].value;
        if (seleccionada) conteo[seleccionada]++;
      }

      let mayor = 'a';
      for (let letra in conteo) {
        if (conteo[letra] > conteo[mayor]) {
          mayor = letra;
        }
      }

      const resultado = document.getElementById('resultado');
      resultado.classList.add('visible');
      let mensaje = '';
      switch (mayor) {
        case 'a':
          mensaje = '<strong>🌷 Oblea Clásica de Arequipe:</strong> Eres dulce, confiable y siempre estás para tus amigos. Como el arequipe, todos te quieren cerca.';
          break;
        case 'b':
          mensaje = '<strong>🌸 Oblea Frutal:</strong> Tienes un lado soñador, artístico y te gusta lo natural. Irradias frescura y creatividad.';
          break;
        case 'c':
          mensaje = '<strong>🍫 Oblea Choco-fun:</strong> Energética, divertida y un poco traviesa. Siempre llevas la chispa del grupo.';
          break;
        case 'd':
          mensaje = '<strong>🌼 Oblea Exótica:</strong> Tranquila, especial y profunda. Tienes un estilo único que todos admiran.';
          break;
      }

      resultado.innerHTML = '<h3>¡Resultado del test!</h3><p>' + mensaje + '</p>';
    }
  </script>
</body>
</html>
