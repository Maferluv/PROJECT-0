# PROJECT-0
CS50 PROYECT 0, HARVARD COURSE
<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<link rel="stylesheet" href="inicio.css">
	<title> Beauty Salón </title>
</head>
<body>

	<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg">
		</div>
		
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>
			
		</ul>		
	</div>

   
<div id="mega"> 
		<table >
			<tr >
				<td>
					<div id="izq">
						<img src="fonde.jpg">
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos...">
	  		 <br>
	  		<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>
		
	</div>


</body>
</html>
body
{
	align-content: center;
	overflow: scroll;
	background-color:black; 
}

h1
{
	text-align: center;
}
#menu
{
	border-style: solid;
	border-color: rgb(191,147,13);
	height: 75px;
	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}

#menu li a:hover
{
	background-color: rgb(191,147,13); 
	text-decoration: underline;
	color: white;
}

.logo
{
	height: 0px;
}
#mega
{
	border-style: solid;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}

#izq
{
	width: 1022px;
	height: 576px;
	float: left;
	position: absolute;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 10px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}

<!DOCTYPE html>
<html>
<head>
	<title> Maquillaje </title>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="maquillaje.css">
</head>
<body>

<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg">
		</div>	
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
				<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>	
		</ul>
	</div>

	<div id="mega"> 
		<table >
			<tr >
				<td>

					<div id="izq">
					<img src="maq2.jpg" id="fondo">		<div class="contenido">
						<h1 id="titulo"> Maquillaje </h1>

						<div class="contder"> 
							<img src="maqx.jpg" class="fmaq">
						</div>
						
						<div class="contizq">
						</div>
					</div>
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos...">
	  		 <br>
	  	<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>	
	</div>
</body>
</html>
body
{
	background-color: black;
}
#menu
{
	border-style: solid;
	background-color:black;
	border-color: rgb(191,147,13);
	height: 75px;	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}

#menu li a:hover
{
	background-color: rgb(191,147,13); 
	text-decoration: underline;
	color: white;
}

.logo
{
	height: 0px;
}

#mega
{
	border-style: solid;
	background-color: black;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}

#izq
{
	width: 1022px;
	height: 576px;
	float: left;
	position: absolute;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 10px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}


#izq
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}
#titulo
{
	font-family: segoe script;
	color: white;
	text-align: center;
}
#fondo
{
	width: 1030px;
	height: 500px;
	position: absolute;
}
.contenido
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}

.contder
{
	width: 505px;
	height: 480px;
	position: relative;
	float: right;
}
.contizq
{
	width: 510px;
	height: 480px;
	position: absolute;
	float: left;
}
.fmaq
{
	width: 300px;
	height: 300px;
	border-radius: 100px;
	border: 2px solid #bf930d;
	margin-top: 50px;
	margin-left: 50px;
}

<!DOCTYPE html>
<html>
<head>
	<title> Depilación </title>
	<meta charset="utf-8">
	<link rel="stylesheet" href="depilacion.css">
</head>
<body>

<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg">
		</div>	
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>
		</ul>
	</div>

	<div id="mega"> 
		<table >
			<tr >
				<td>

					<div id="izq">
						<img src="f5.jpg" id="fondo">
						<h1 id="depilacion"> Depilación </h1>

						<div class="cera">
							<h1 id="titc"> Cera </h1>
							<img src="cera.jpg" id="fcera">
							<ul style="color: black; position: absolute; margin-top: -360px; padding-left:80px;padding-top: 15px; font-weight: bolder; font-size: 20px; ">
								<li>Ceja $250</li>
								<li>Naríz $220</li>
								<li>Axila $270</li>
								<li>Media Pierna $320</li>
								<li>Pierna Completa $480</li>
								<li>Bigote $220</li>
								<li>Patilla $320</li>
								<li>Cara Completa $500</li>
							</ul>
							
						</div>

						<div class="hilo">
							<h1 id="tith"> Hilo </h1>
							<img src="dep_ceja_hilo.jpg" id="fhilo">

							<ul id="ulh">
								<li>Patilla $350</li>
								<li>Bigote $250</li>
								<li>Ceja $280</li>
								<li>Cara $600</li>
							</ul>
						</div>
						
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos...">
	  		 <br>
	  		<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>	
	</div>
</body>
</html>
body
{
	background-color: black;
}
#menu
{
	border-style: solid;
	background-color:black;
	border-color: rgb(191,147,13);
	height: 75px;	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}

#menu li a:hover
{
	background-color: rgb(191,147,13); 
	text-decoration: underline;
	color: white;
}

.logo
{
	height: 0px;
}

#mega
{
	border-style: solid;
	background-color: black;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}

#izq
{
	width: 1022px;
	height: 576px;
	float: left;
	position: absolute;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 10px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}

#izq
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}
#fondo
{
	width: 1024px;
	height: 580px;
	position: absolute;
}
#depilacion
{
	font-family: segoe script;
	color: white;
	text-align: center;
	position: relative;
}
.cera
{
	width: 510px;
	height: 530px;
	position: absolute;
	float: left;
}
#fcera
{
	width: 400px;
	height: 350px;
	margin-left: 35px;
	border-color: rgb(191,147,13);
	border-style: solid;
}
.hilo
{
	width: 510px;
	height: 530px;
	position: relative;
	float: right;
}
#fhilo
{
	width: 400px;
	height: 350px;
	margin-left: 35px;
	border-color: rgb(191,147,13);
	border-style: solid;
}
#titc
{
	font-family: segoe script;
	color: white;
	position: relative;
}
#tith
{
	font-family: segoe script;
	color: white;
	text-align: center;
}
#ulh
{
	color: white; 
	position: absolute;
	 margin-top: -300px;
	  padding-left:100px;
	  padding-top: 15px;
	   font-weight: bolder;
	 font-size: 20px;
}
.cera ul li
{
	padding: 5px;
	font-family: segoe script;
}
.hilo ul li
{
	padding: 5px;
	font-family: segoe script;
}

<!DOCTYPE html>
<html>
<head>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="estilo_uñas.css">

	<title> Uñas </title>
	<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg" style="">
		</div>	
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
		<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>		
		</ul>
	</div>

	<div id="mega"> 
		<table >
			<tr >
				<td>

					<div id="izq">
						<img src="fondo_belleza.jpg" class="fondodiv">
						<div id="uñas">
							<h1> Uñas </h1>
							<img src="manicure1.jpg" class="redonda">
							<h2 id="mnormal"> Manicure Normal<br> $270 </h2>

							<img src="pedicure.jpg" class="redonda1">
							<h2 id="pnormal"> Pedicure Normal <br> $320</h2>

							<img src="gelish_manos.jpg" class="redonda2">
							<h2 id="mgelish"> Manicure Gelish <br> $500</h2>
							
							<img src="gelish_pies.png" class="redonda3">
							<h2 id="pgelish"> Pedicure Gelish <br> $550</h2>
						</div>

						
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos..." class="escribe">
	  		 <br>
	  		<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>	
	</div>
		
</head>
<body>

</body>
</html>
body
{
	background-color: black;
}

#menu
{
	border-style: solid;
	background-color:black;
	border-color: rgb(191,147,13);
	height: 75px;	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}
#menu li a:hover
{
	background-color: rgb(234,190,63); 
	text-decoration: underline;
	color: white;
}
.logo
{
	height: 0px;
}
#mega
{
	border-style: solid;
	background-color: black;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 5px;
	padding-bottom: 5px;
}
.escribe
{
	padding-top: 5px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}
#izq
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;	
}
.fondodiv
{
	width: 1030px;
	height: 585px;
	position: absolute;
}
#depilacion
{
	border-style: solid;
	border-color: rgb(191,147,13);
	border-top: none;
	border-left: none;
	border-bottom: none;
	float: left;
	position: absolute;
	width: 520px;
	height: 575px;
}
#uñas
{
	float: right;
	width: 505px;
	height: 575px;
	position: relative;
}
.redonda
{
	width: 150px;
	height: 150px;
	border-radius: 150px;
	margin-left: 50px;
	border: 3px solid #bf930d;
	position: relative;
	top:-20px; 
}
.redonda:hover
{
	width: 300px;
	height: 300px;
	border-radius: 300px;
	margin-left: 30px;
	border: 3px solid #bf930d;
}
#mnormal
{
margin-left: 50px;
}
.redonda1
{
	width: 150px;
	height: 150px;
	border-radius: 150px;
	margin-left: 50px;
	border: 3px solid #bf930d;
	position: relative;	
}
.redonda1:hover
{
	width: 300px;
	height: 300px;
	border-radius: 300px;
	margin-left: 20px;
	border: 3px solid #bf930d;
}
#pnormal
{
	margin-left: 50px;
}
.redonda2
{
	width: 150px;
	height: 150px;
	border-radius: 150px;
	border: 3px solid #bf930d;
	float: right;
	position: relative;
	top: -485px;
	left: -50px;
}
.redonda2:hover
{
	width: 300px;
	height: 300px;
	border-radius: 300px;
	margin-left: 20px;
	border: 3px solid #bf930d;
}
#mgelish
{
	float: right;
	position: relative;
	top: -305px;
	left: 80px;
}
.redonda3
{
	width: 150px;
	height: 150px;
	border-radius: 150px;
	border: 3px solid #bf930d;
	float: right;
	position: relative;
	top: -234px;
	left: 250px;
}
.redonda3:hover
{
    width: 300px;
	height: 300px;
	border-radius: 300px;
	margin-left: 20px;
	border: 4px solid #bf930d;
}
#pgelish
{
	float: right;
	position: relative;
	top: -225px;
	left: -80px;
}
h1
{
	font-family:segoe script;
	color: rgb(191,147,13);
}
h2
{
    font-family:segoe script;
	color: rgb(191,147,13);	
	font-size: 15px;
	margin-left: 15px;
}

<!DOCTYPE html>
<html>
<head>
	<title> Pestañas </title>
	<meta charset="utf-8">
	<link rel="stylesheet" href="pestañas.css">
</head>
<body>

<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg">
		</div>	
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>
		</ul>
	</div>

	<div id="mega"> 
		<table >
			<tr >
				<td>

					<div id="izq">
						<img src="f9.jpg" class="fondo">
						<div class="contenido">
							<h1 id="titulo"> Pestañas 1x1 </h1>

							<h3 class="t2"> Lifting y Tinte <br> $600</h3>
							<img src="lifting_tinte_pestañas.jpg" class="foto1">

							<h2 class="tecnicas"> Técnicas </h2>

							<h3 class="japonesa"> Japonesa* $1200</h3>
							<img src="pestañas2.jpg" class="f2">

							<h3 class="hibridas"> Híbridas* $1400</h3>
							<img src="pestañas_hibridas.jpg" class="f3">

							<h3 class="volumen"> Volúmen* $1600</h3>
							<img src="pestañas3.jpg" class="f4">
						</div>
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos...">
	  		 <br>
	  		<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>	
	</div>
</body>
</html>
body
{
	background-color: black;
}
#menu
{
	border-style: solid;
	background-color:black;
	border-color: rgb(191,147,13);
	height: 75px;	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}

#menu li a:hover
{
	background-color: rgb(191,147,13); 
	text-decoration: underline;
	color: white;
}

.logo
{
	height: 0px;
}

#mega
{
	border-style: solid;
	background-color: black;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}

#izq
{
	width: 1022px;
	height: 576px;
	float: left;
	position: absolute;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 10px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}

#titulo
{
	font-family: segoe script;
	color: white;
	text-align: center;
}
#izq
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;	
}
.fondo
{
	width: 1030px;
	height: 585px;
	position: absolute;
}
.contenido
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}
.t2
{
	color: white;
	font-family: segoe script;
	margin-left: 40px;
	margin-top: 200px;
}
.foto1
{
	width: 200px;
	height: 150px;
	border: 3px solid #bf930d;
	border-radius: 150px;
	margin-left: 230px;
	margin-top: -100px;
}

.tecnicas
{
	color: white;
	font-family: segoe script;
	margin-top: -340px;
	margin-left: 450px;
	text-decoration: underline;
}
.japonesa
{
    color: white;
	font-family: segoe script;
	margin-left: 680px;
	margin-top: 70px; 
}
.f2
{
	width: 200px;
	height: 150px;
	border: 3px solid #bf930d;
	border-radius: 100px;
	margin-left: 450px;
	margin-top: -110px;
}
.hibridas
{
	color: white;
	font-family: segoe script;
	margin-left: 530px;
	margin-top: 40px;
}
.f3
{
	width: 200px;
	height: 150px;
	border: 3px solid #bf930d;
	border-radius: 100px;
	margin-left: 750px;
	margin-top: -120px;
}
.volumen
{
	color: white;
	font-family: segoe script;
	margin-left: 680px;
	margin-top: 40px;
}
.f4
{
	width: 200px;
	height: 150px;
	border: 3px solid #bf930d;
	border-radius: 100px;
	margin-left: 450px;
	margin-top: -115px;
}

<!DOCTYPE html>
<html>
<head>
	<title> Masajes </title>
	<meta charset="utf-8">
	<link rel="stylesheet" type="text/css" href="masajes.css">
</head>
<body>

<div id="menu">
		<div class="logo">
			<img src="logo_oro.jpg">
		</div>	
		<ul>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/Inicio.html"> Inicio </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/uñas.html#uñas"> Uñas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/depilacion.html"> Depilación </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/pestañas.html#pestañas"> Pestañas </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/masajes.html#masajes"> Masajes </a>
			</li>
			<li>
				<a href="file:///C:/Users/Mayra%20Luviano/Desktop/pag_les/maquillaje.html#maquillaje"> Maquillaje </a>
			</li>		
		</ul>
	</div>

	<div id="mega"> 
		<table >
			<tr >
				<td>

					<div id="izq">
						<img src="f11.jpg" id="fondo">		<div class="contenido">
						<h1 id="titulo"> Masajes </h1>

						<div class="contder"> 
							<h2 class="titulo2"> Facial </h2>
							<img src="facial.jpg" class="ffac">

							<ul>
								<li class="li1"> Facial limpieza profunda/microdermoabrasión  <br>$500</li>

								<li class="li2"> Facial/radio frecuencia <br> $800
								</li>
							</ul>

						</div>

						<div class="contizq">
							<h2 class="titulo2"> Corporal </h2>
							<img src="masaje_celulitits.jpg" class="fcorp">

							<ul id="ul1">
								<li class="li3">Masaje Relajante $650</li>

								<li class="li3">Masaje Descontracturante $750</li>

								<li class="li3">Masaje Reductivo por zona $750</li>

								<li class="li3">Masaje Anticelulitico $750</li>
							</ul>

						</div>
					</div>
				</td>
			</tr>
		</table>

			<tr>
				<td>
					<div id="der">
						 	<form>
	  		<h1> Haz tu cita! </h1>
	  		<h1> Contáctanos </h1>
	  		<label> Nombre </label>
	  		 <br>
	  		<input type="text" name="nombre" placeholder="Nombre"> 
	  		<br>
	  		<label> Correo electronico</label>
	  		 <br>
	  		<input type="email" name="correo" placeholder="Correo electronico">
	  		<br>
	  		<label> Teléfono </label>
	  		 <br>
	  		<input type="number" name="Telefono" placeholder="Telefono"><br>
	  		<label> ¿Cómo te podemos ayudar?</label> 
	  		<br>
	  		<input  style="width: 250px; height: 100px;" type="text" name="ayuda" placeholder="escribenos...">
	  		 <br>
	  	<input id="enviar" style="float: right; background-color:rgb(191,147,13); color: white; padding-top: none"  type="submit" value="Enviar Datos" >
	  	</form>
					</div>
				</td>
			</tr>	
	</div>
</body>
</html>
body
{
	background-color: black;
}
#menu
{
	border-style: solid;
	background-color:black;
	border-color: rgb(191,147,13);
	height: 75px;	
}
#menu a
{
	color: rgb(191,147,13);
	font-family: segoe script;
	text-decoration: none;
	text-align: left;
}
#menu ul
{
	list-style-type: none;
	text-align: center;
	text-decoration: none;
}
#menu li
{
	display: inline;
	text-align: center;
	margin: 10px 10px 10px 10px;
	font-family: segoe script;
	list-style-type: none;
	text-decoration: none;
}

#menu li a:hover
{
	background-color: rgb(191,147,13); 
	text-decoration: underline;
	color: white;
}

.logo
{
	height: 0px;
}

#mega
{
	border-style: solid;
	background-color: black;
	border-color: rgb(191,147,13);
	height: 590px;
	border-top-color: black;
	position: relative;
}

#izq
{
	width: 1022px;
	height: 576px;
	float: left;
	position: absolute;
}
#der
{
	border-color: rgb(191,147,13);
	border-style: solid;
	border-right: none;
	border-spacing: none;
	border-top: none;
	border-bottom: none;
	width: 290px;
	height: 580px;
	float: right;
	position: relative;
}
h1
{
	text-align: center;
}
form
{
	font-family: segoe script;
	color: rgb(191,147,13);
	padding-left: 10px;
}
input
{
	padding-top: 10px;
}
#enviar
{
	margin-top: 10px;
	margin-right: 25px;
}


#izq
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}
#titulo
{
	font-family: segoe script;
	color: white;
	text-align: center;
}
#fondo
{
	width: 1030px;
	height: 500px;
	position: absolute;
}
.contenido
{
	width: 1024px;
	height: 580px;
	float: left;
	position: absolute;
}

.contder
{
	width: 505px;
	height: 480px;
	position: relative;
	float: right;
}
.contizq
{
	width: 510px;
	height: 480px;
	position: absolute;
	float: left;
}
.titulo2
{
	font-family: segoe script;
	color: white;
	text-align: center;
}

.ffac
{
    width: 503px;
	height: 390px;
	border-color: rgb(191,147,13);
	border-style: solid;
	margin-right: 5px;

}
.fcorp
{
	width: 510px;
	height: 390px;
	border-color: rgb(191,147,13);
	border-style: solid;
}
.li1
{
	font-family: segoe script;
	color: black;
	margin-top: -390px;
	font-size: 20px;
	margin-left: 20px;
	font-weight: bolder;
}
.li2
{
	font-family: segoe script;
	color: black;
	position: absolute;
	font-size: 20px;
	margin-left: 20px;
	margin-top: 30px;
	font-weight: bolder;
}
#ul1
{
	margin-top: -380px;
	margin-left: 20px; 
}
.li3
{
	padding-top: 30px;
	color: black;
	font-family: segoe script;
	font-weight: bolder;
	font-size: 23px;
}



