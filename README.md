
<html>
<head>
	<meta charset="utf-8">
	<meta name="viewport" content="width=device-width, initial-scale=1">
	<title>Cuatro cajas dentro de un contenedor</title>
	<style>
		.contenedor{
			width: 80%;
			padding: 20px;
			border: 2px solid #808b96;
			box-shadow: 0px 4px 8px rgba(0, 0, 0, 0.1);
			margin: 0 auto;
			display: grid;
			grid-template-columns: repeat(2, 1fr);
		}
		.caja{
			width: 100%;
			height: 150px;
			padding: 1px;
			margin: 10px;
			border: 1px solid #ccc;
			text-align: center;
			line-height: 150px;
		}
		.caja1{
			background-color: #f3fa20;
		}
		.caja2{
			background-color: #2afa20;
		}
		.caja3{
			background-color: #3ff7f4;
		}
		.caja4{
			background-color: #fc55ff;
		}
	</style>
</head>
<body>
	<div class="contenedor">
        <div class="caja caja1">Caja 1</div>
        <div class="caja caja2">Caja 2</div>
        <div class="caja caja3">Caja 3</div>
        <div class="caja caja4">Caja 4</div>
    </div>
</body>
</html>
