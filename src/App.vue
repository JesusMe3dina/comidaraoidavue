<template>
  <header>
    <nav>
        <ul>
		<li><a href="#">Hamburgesa</a></li>
		<li><a href="#">Pizza</a></li>
		<li><a href="#">Papas a la francesa</a></li>
        <li><a href="#">Hotdogs</a></li>
		<li><a href="#">Nachos</a></li>
		<li><a href="#">Alitas</a></li>
	 </ul>
    </nav>
</header>
<br>
<br>
<br>
<br>
<br>

<div>
<h1>VUEComida Rápida Jesus Eduardo Meina Contreras 4 °B</h1> 
</div>



<body>
    <div class="container">
        

        <div class="card">
            <img url="https://img.freepik.com/foto-gratis/vista-frontal-hamburguesa-stand_141793-15542.jpg?w=900&t=st=1666318310~exp=1666318910~hmac=e6fb58ff0adb87fc9be684119db855251fda0ae54587ade54aaa3cfa7f41b4ea">
            <h4>Hamburgesa</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: $60</p>
            <a href="#">Leer más</a>
        </div>
    

        <div class="card">
            <img url="https://img.freepik.com/foto-gratis/pizza-hawaiana_1203-2455.jpg?size=626&ext=jpg&ga=GA1.2.1642657468.1666318296&semt=sph">
            <h4>Pizza</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: 110$</p>
            <a href="#">Leer más</a>
        </div>

        <div class="card">
            <img url="https://img2.freepng.es/20171216/60e/fries-png-5a34b8b484dc53.5973590915134045965442.jpg">
            <h4>Papas a la francesa</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: 30</p>
            <a href="#">Leer más</a>
        </div>
        <div class="card">
            <img url="https://i.pinimg.com/originals/60/7a/9b/607a9bc3f86378637f1e8c5e56cd51c8.jpg">
            <h4>Hot dogs</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: $40</p>
            <a href="#">Leer más</a>
        </div>
        <div class="card">
            <img url="https://www.pngfind.com/pngs/m/300-3002185_tacos-de-asada-png-greek-salad-transparent-png.png">
            <h4>Nachos</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: $50</p>
            <a href="#">Leer más</a>
        </div>
        <div class="card">
            <img url="https://img2.freepng.es/20180409/hqe/kisspng-fizzy-drinks-energy-drink-pepsi-fast-food-drink-5acaf916bf2816.082727551523251478783.jpg">
            <h4>Alitas</h4>
            <p>Lorem ipsum dolor sit amet, consectetur adipisicing elit. Vel, excepturi unde?</p>
            <p>costo: $70</p>
            <a href="#">Leer más</a>
        </div>

    </div>

</body>

</template>
<style>
    header {
        background: rgba(202, 62, 19, 0.719);
        width: 100%;
        position: fixed;
        z-index: 100;
    }
    
    nav {
        float: left;
    }
    
    nav ul {
        list-style: none;
        overflow: hidden;
    }
    
    nav ul li {
        float: left;
        font-family: Arial, Helvetica, sans-serif;
        ;
        font-size: 20px;
    }
    
    nav ul li a {
        display: block;
        padding: 20px;
        color: rgb(218, 166, 124);
        text-decoration: none;
    }
    
    nav ul li:hover {
        background: #f57105;
    }
    
    text-decoration none nav ul li:hover {
        background: #eba940ef;
    }
    
    text-decoration none nav ul li:hover {
        background: #daab5f;
    }
    
    text-decoration none nav ul li:hover {
        background: #e4b973;
    }
</style>
<style>
    body {
        margin: 0;
        padding: 0;
    }
    
    body {
        width: 100%;
        height: 100%;
        font-family: sans-serif;
        letter-spacing: 0.03em;
        line-height: 1.6;
        font-family: 'Open Sans', sans-serif;
    }
    
    .title {
        text-align: center;
        font-size: 40px;
        color: #6a6a6a;
        margin-top: 100px;
        font-weight: 100;
        font-family: 'Roboto', sans-serif;
    }
    
    .container {
        width: 100%;
        max-width: 1200px;
        height: 430px;
        display: flex;
        flex-wrap: wrap;
        justify-content: center;
        margin: auto;
    }
    
    .container .card {
        width: 330px;
        height: 430px;
        border-radius: 8px;
        box-shadow: 0 2px 2px rgba(0, 0, 0, 0.2);
        overflow: hidden;
        margin: 20px;
        text-align: center;
        transition: all 0.25s;
    }
    
    .container .card:hover {
        transform: translateY(-15px);
        box-shadow: 0 12px 16px rgba(0, 0, 0, 0.2);
    }
    
    .container .card img {
        width: 330px;
        height: 220px;
    }
    
    .container .card h4 {
        font-weight: 600;
    }
    
    .container .card p {
        padding: 0 1rem;
        font-size: 16px;
        font-weight: 300;
    }
    
    .container .card a {
        font-weight: 500;
        text-decoration: none;
        color: #0e597c;
    }
</style>
<style>
    body {
        background-color: rgb(243, 161, 78);
    }
</style>