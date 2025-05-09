<!DOCTYPE html>
<html lang="es">
<head>
  <meta charset="UTF-8">
  <title>Feliz Día Mamá</title>
  <style>
    body {
      background: linear-gradient(to bottom right, #ffe6f0, #e0f7fa);
      font-family: 'Comic Sans MS', cursive;
      text-align: center;
      padding: 30px;
      color: #444;
    }
    h1 {
      color: #e91e63;
      font-size: 2.5em;
    }
    .button {
      background-color: #ffb6c1;
      border: none;
      padding: 15px 25px;
      font-size: 1.2em;
      border-radius: 15px;
      cursor: pointer;
      margin-top: 20px;
      transition: 0.3s;
    }
    .button:hover {
      background-color: #f48fb1;
    }
    .carta {
      display: none;
      background-color: #fff0f5;
      border: 2px dashed #f8bbd0;
      padding: 20px;
      margin-top: 20px;
      border-radius: 15px;
      max-width: 600px;
      margin-left: auto;
      margin-right: auto;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }
    img {
      max-width: 100px;
      margin: 10px;
    }
  </style>
</head>
<body>
  <h1>Feliz Día de la Madre</h1>
  <div>
    <img src="https://i.imgur.com/97EyU0g.png" alt="cupcake">
    <img src="https://i.imgur.com/UqxiWRI.png" alt="torta">
    <img src="https://i.imgur.com/zQSTlVk.png" alt="corazón">
  </div>
  <button class="button" onclick="mostrarCarta()">Abrir mi cartita</button>

  <div class="carta" id="carta">
    <p><strong>Querida mamá:</strong></p>
    <p>Hoy quiero honrarte por todo lo que sos. Eres una mujer trabajadora, valiente y llena de amor. Gracias a tu esfuerzo diario, a tus manos dulces que amasan no solo pasteles sino también esperanza, tenemos alimento en la mesa y alegría en el corazón.</p>
    <p>Sé que muchas veces te cansás, que te preocupás por nosotras y que llevás más peso del que muchos imaginan… pero aun así, nunca dejás de cuidar, de dar, de amar. Sos una madre ejemplar, una esposa fiel, y un reflejo del amor de Dios en nuestras vidas.</p>
    <p>Aunque a veces nos quejamos o no lo decimos tanto como deberíamos, te amamos inmensamente. Valoramos cada pastel que hacés, cada noche que sacrificás, cada enojo que nace del amor y el deseo de vernos bien.</p>
    <p>Como dice Proverbios 31:28: <em>“Se levantan sus hijos y la llaman bienaventurada; y su marido también la alaba.”</em></p>
    <p>Y así hoy, yo me levanto y te digo: gracias, mamá. Sos una bendición que Dios puso en nuestras vidas. Oro para que Él te siga fortaleciendo, guiando y llenando tu corazón de paz y gozo.</p>
    <p><strong>Feliz Día de la Madre. Te amamos con todo el corazón.</strong></p>
    <p>Con amor, <br> Tu familia</p>
  </div>

  <script>
    function mostrarCarta() {
      document.getElementById("carta").style.display = "block";
    }
  </script>
</body>
</html>