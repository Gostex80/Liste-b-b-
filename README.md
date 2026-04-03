<!DOCTYPE html>
<html lang="fr">
<head>
  <meta charset="UTF-8">
  <title>Calculateur de recharge Tesla Model Y</title>
  <link rel="stylesheet" href="style.css">
</head>
<body>

<h1>🔋 Calculateur de recharge</h1>

<label>Charge actuelle (%) :</label>
<input type="number" id="current" min="0" max="100">

<label>Charge souhaitée (%) :</label>
<input type="number" id="target" min="0" max="100">

<label>Puissance de charge :</label>
<select id="power">
  <option value="3.7">3.7 kW</option>
  <option value="11">11 kW</option>
</select>

<button onclick="calculate()">Calculer</button>

<h2 id="result"></h2>

<script src="script.js"></script>

</body>
</html>