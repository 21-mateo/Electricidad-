<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8" />
  <title>Quiz de Electricidad</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0; padding: 0;
      background: #f0f0f0;
      color: #222;
    }
    header {
      background: #004080;
      color: white;
      padding: 15px 20px;
      position: sticky;
      top: 0;
      z-index: 1000;
    }
    header h1 {
      margin: 0;
    }
    nav ul {
      list-style: none;
      padding: 0;
      margin: 10px 0 0;
      display: flex;
      gap: 20px;
    }
    nav a {
      color: #a8d0e6;
      text-decoration: none;
      font-weight: bold;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 720px;
      margin: 20px auto;
      background: white;
      padding: 20px;
      border-radius: 8px;
      box-shadow: 0 2px 6px rgba(0,0,0,0.1);
    }
    h2 {
      color: #003366;
      margin-top: 0;
    }
    .quiz-question {
      margin-bottom: 18px;
    }
    .quiz-question h3 {
      margin-bottom: 8px;
    }
    .quiz-options label {
      display: block;
      cursor: pointer;
      margin-bottom: 6px;
      padding: 7px 12px;
      border: 1px solid #ccc;
      border-radius: 5px;
      transition: background 0.3s;
    }
    .quiz-options input[type="radio"] {
      margin-right: 10px;
      cursor: pointer;
    }
    .quiz-options label:hover {
      background: #a8d0e6;
    }
    button {
      background: #004080;
      color: white;
      border: none;
      padding: 12px 20px;
      font-size: 16px;
      border-radius: 8px;
      cursor: pointer;
      transition: background 0.3s;
      margin-top: 20px;
      display: block;
    }
    button:hover {
      background: #002850;
    }
    #result {
      margin-top: 25px;
      font-size: 20px;
      font-weight: 600;
      color: #007f00;
    }
    footer {
      text-align: center;
      font-size: 14px;
      color: #666;
      margin: 50px 0 20px 0;
    }
  </style>
</head>
<body>

<header>
  <h1>Quiz de Electricidad</h1>
  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#interactivo">Quiz</a></li>
      <li><a href="#fuentes">Fuentes</a></li>
    </ul>
  </nav>
</header>

<section id="inicio">
  <h2>Bienvenida</h2>
  <p>Pon a prueba tus conocimientos sobre electricidad con estas 10 preguntas.</p>
</section>

<section id="interactivo">
  <h2>Quiz de Electricidad</h2>
  <form id="quizForm">

    <div class="quiz-question">
      <h3>1. ¿Cuál es la unidad de medida de la resistencia eléctrica?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q1" value="a" required>a) Voltio</label>
        <label><input type="radio" name="q1" value="b">b) Ohmio</label>
        <label><input type="radio" name="q1" value="c">c) Amperio</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>2. La fórmula para calcular la potencia eléctrica es:</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q2" value="a" required>a) P = V / I</label>
        <label><input type="radio" name="q2" value="b">b) P = I x V</label>
        <label><input type="radio" name="q2" value="c">c) P = V + I</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>3. ¿Qué dispositivo protege un circuito eléctrico para evitar sobrecargas?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q3" value="a" required>a) Fusible</label>
        <label><input type="radio" name="q3" value="b">b) Resistencia</label>
        <label><input type="radio" name="q3" value="c">c) Transformador</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>4. ¿Qué representa la letra “I” en electricidad?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q4" value="a" required>a) Intensidad de corriente</label>
        <label><input type="radio" name="q4" value="b">b) Inercia</label>
        <label><input type="radio" name="q4" value="c">c) Inductancia</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>5. Si un circuito tiene un voltaje de 12V y una corriente de 2A, ¿cuál es la potencia?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q5" value="a" required>a) 6 W</label>
        <label><input type="radio" name="q5" value="b">b) 24 W</label>
        <label><input type="radio" name="q5" value="c">c) 14 W</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>6. ¿Cuál es la unidad para medir la corriente eléctrica?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q6" value="a" required>a) Voltio</label>
        <label><input type="radio" name="q6" value="b">b) Amperio</label>
        <label><input type="radio" name="q6" value="c">c) Ohmio</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>7. ¿Qué significa la letra "V" en electricidad?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q7" value="a" required>a) Voltaje</label>
        <label><input type="radio" name="q7" value="b">b) Corriente</label>
        <label><input type="radio" name="q7" value="c">c) Potencia</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>8. ¿Qué es un circuito en serie?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q8" value="a" required>a) Circuito donde todos los componentes están en una sola ruta</label>
        <label><input type="radio" name="q8" value="b">b) Circuito con múltiples caminos</label>
        <label><input type="radio" name="q8" value="c">c) Circuito sin resistencia</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>9. La ley que relaciona voltaje, corriente y resistencia es:</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q9" value="a" required>a) Ley de Newton</label>
        <label><input type="radio" name="q9" value="b">b) Ley de Ohm</label>
        <label><input type="radio" name="q9" value="c">c) Ley de Faraday</label>
      </div>
    </div>

    <div class="quiz-question">
      <h3>10. ¿Qué es un transformador?</h3>
      <div class="quiz-options">
        <label><input type="radio" name="q10" value="a" required>a) Un dispositivo que cambia el voltaje de corriente alterna</label>
        <label><input type="radio" name="q10" value="b">b) Un tipo de resistencia</label>
        <label><input type="radio" name="q10" value="c">c) Un interruptor</label>
      </div>
    </div>

    <button type="submit">Enviar respuestas</button>
  </form>

  <div id="result"></div>
</section>

<section id="fuentes">
  <h2>Fuentes</h2>
  <ul>
    <li><a href="https://es.wikipedia.org/wiki/Electricidad" target="_blank" rel="noopener noreferrer">Wikipedia - Electricidad</a></li>
    <li><a href="https://www.ecured.cu/Electricidad" target="_blank" rel="noopener noreferrer">Ecured - Electricidad</a></li>
  </ul>
</section>

<footer>
  <p>Proyecto desarrollado por estudiante de secundaria técnica &copy; 2026</p>
</footer>

<script>
  const respuestasCorrectas = {
    q1: 'b', q2: 'b', q3: 'a', q4: 'a', q5: 'b',
    q6: 'b', q7: 'a', q8: 'a', q9: 'b', q10: 'a'
  };

  const form = document.getElementById('quizForm');
  const result = document.getElementById('result');

  form.addEventListener('submit', e => {
    e.preventDefault();
    let score = 0;
    for (let i = 1; i <= 10; i++) {
      const userAnswer = form['q'+i].value;
      if (userAnswer === respuestasCorrectas['q'+i]) score++;
    }
    let msg = `Obtuviste ${score} de 10 respuestas correctas. `;
    if (score === 10) msg += "¡Perfecto! Eres experto en electricidad.";
    else if (score >= 7) msg += "Muy buen trabajo.";
    else if (score >= 4) msg += "Está bien, sigue mejorando.";
    else msg += "Necesitas estudiar más.";
    result.textContent = msg;
  });
</script>

</body>
</html>
