<!DOCTYPE html>
<html>
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
<body>
  
{
  background-color: #f5f5f5;
  font-family: Arial, sans-serif;
}

.header {
  padding: 30px;
  text-align: center;
  background: #1abc9c;
  color: white;
}

.header input[type="text"] {
  margin-right: 10px;
  padding: 10px;
  border: none;
  font-size: 16px;
}

.header input[type="time"] {
  margin-right: 10px;
  padding: 10px;
  border: none;
}

.addBtn {
  padding: 10px;
  width: auto;
  background-color: #d9d9d9;
  color: #555;
}

ul#myUL li {
  margin: 0 auto;
  display: flex;
  justify-content: space-between;
  align-items: center;
  background-color: #ddd;
  padding: 15px;
  margin-bottom: 15px;
}

<h2>Minha Lista de Tarefas</h2>

<div id="myDIV" class="header">
  <input type="text" id="myInput" placeholder="Título...">
  <input type="time" id="myTime">
  <span onclick="newElement()" class="addBtn">Adicionar</span>
</div>

<ul id="myUL">
</ul>

<script src="script.js"></script>

</body>
</html>

