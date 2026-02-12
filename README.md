<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Parque Porvenir | Lambaré</title>

<link href="https://fonts.googleapis.com/css2?family=Playfair+Display:wght@500;600&family=Inter:wght@300;400;500&display=swap" rel="stylesheet">

<style>

:root{
    --verde:#2f4f3f;
    --verde-suave:#e8efe9;
    --verde-claro:#4f6f57;
}

*{
    margin:0;
    padding:0;
    box-sizing:border-box;
}

body{
    font-family:'Inter', sans-serif;
    background:var(--verde-suave);
    color:#2f3e2f;
}

/* HERO */

.hero{
    height:100vh;
    background:url("portada.jpg") center/cover no-repeat;
    display:flex;
    align-items:center;
    justify-content:center;
    text-align:center;
    color:white;
    position:relative;
}

.hero::after{
    content:"";
    position:absolute;
    inset:0;
    background:rgba(0,0,0,0.45);
}

.hero-content{
    position:relative;
    z-index:2;
    max-width:800px;
}

.hero h1{
    font-family:'Playfair Display', serif;
    font-size:60px;
    letter-spacing:2px;
}

.hero p{
    margin:20px 0;
    font-size:20px;
}

.btn{
    background:var(--verde);
    padding:14px 32px;
    color:white;
    text-decoration:none;
    border-radius:30px;
    transition:0.3s;
}

.btn:hover{
    background:var(--verde-claro);
}

/* SECCIONES */

section{
    padding:100px 20px;
    max-width:1100px;
    margin:auto;
    text-align:center;
}

section h2{
    font-family:'Playfair Display', serif;
    font-size:38px;
    margin-bottom:30px;
}

section p{
    max-width:700px;
    margin:auto;
    font-size:18px;
    line-height:1.6;
}

/* IMAGEN FULL */

.imagen img{
    width:100%;
    border-radius:16px;
    box-shadow:0 10px 30px rgba(0,0,0,0.1);
}

/* BLOQUE PRECIO */

.precio{
    background:var(--verde);
    color:white;
    padding:80px 20px;
}

.precio h2{
    font-size:42px;
}

.precio p{
    margin:20px 0;
    font-size:18px;
}

/* FOOTER */

footer{
    background:#1b2a20;
    color:#ddd;
    text-align:center;
    padding:30px;
}

/* WHATSAPP */

.whatsapp{
    position:fixed;
    bottom:25px;
    right:25px;
    background:#25D366;
    color:white;
    font-size:22px;
    padding:16px 18px;
    border-radius:50%;
    text-decoration:none;
    box-shadow:0 5px 20px rgba(0,0,0,0.3);
}

/* RESPONSIVE */

@media(max-width:768px){
    .hero h1{
        font-size:38px;
    }
}

</style>
</head>

<body>

<header class="hero">
    <div class="hero-content">
        <h1>Parque Porvenir</h1>
        <p>Tu terreno en el barrio más exclusivo de Lambaré</p>
        <a href="https://wa.me/595XXXXXXXXX" class="btn">Solicitar Información</a>
    </div>
</header>

<section>
    <h2>Un entorno exclusivo</h2>
    <p>
        Un proyecto habitacional pensado para vivir con privacidad,
        tranquilidad y calidad de vida en un entorno consolidado.
    </p>
</section>

<section class="imagen">
    <img src="renderfrente.jpg" alt="Ingreso Parque Porvenir">
</sect
