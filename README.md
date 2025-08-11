<!DOCTYPE html>
<html lang="pt-BR">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Alumividros - Vidraçaria e Metalúrgica</title>
<style>
body { margin:0; font-family: Arial, sans-serif; background:#111; color:#eee; }
header { background:#000; padding:15px; text-align:center; position:sticky; top:0; }
header h1 { color:#d4af37; }
nav a { margin:0 15px; color:#d4af37; text-decoration:none; }
.hero { background:url('data:image/jpeg;base64,/9j/4AAQSkZJRgABAQAAAQABAAD...') center/cover; height:60vh; display:flex; align-items:center; justify-content:center; color:white; }
section { padding:40px 20px; max-width:1200px; margin:auto; }
h2 { color:#d4af37; text-align:center; margin-bottom:20px; }
.services, .gallery, .testimonials { display:grid; grid-template-columns:repeat(auto-fit,minmax(250px,1fr)); gap:20px; }
.service-card, .testimonial { background:#1c1c1c; padding:15px; border-radius:8px; text-align:center; }
.service-card img, .gallery img { width:100%; height:200px; object-fit:cover; border-radius:8px; }
.testimonial img { width:60px; height:60px; border-radius:50%; margin-bottom:10px; }
.btn { background:#d4af37; padding:10px 20px; color:black; text-decoration:none; border-radius:5px; }
.whatsapp-btn { position:fixed; bottom:20px; right:20px; background:#25D366; padding:15px; border-radius:50%; color:white; font-size:24px; text-decoration:none; }
</style>
</head>
<body>
<header>
    <h1>Alumividros</h1>
    <nav>
        <a href="#servicos">Serviços</a>
        <a href="#galeria">Galeria</a>
        <a href="#depoimentos">Depoimentos</a>
        <a href="#contato">Contato</a>
    </nav>
</header>
<div class="hero">
    <h2>Excelência em Vidraçaria e Metalúrgica</h2>
</div>
<section id="servicos">
    <h2>Nossos Serviços</h2>
    <div class="services">
        <div class="service-card"><img src="data:image/jpeg;base64,..."><h3>Portões de Vidro</h3></div>
        <div class="service-card"><img src="data:image/jpeg;base64,..."><h3>Janelas e Esquadrias</h3></div>
        <div class="service-card"><img src="data:image/jpeg;base64,..."><h3>Coberturas de Vidro</h3></div>
        <div class="service-card"><img src="data:image/jpeg;base64,..."><h3>Box para Banheiro</h3></div>
    </div>
</section>
<section id="galeria">
    <h2>Galeria</h2>
    <div class="gallery">
        <img src="data:image/jpeg;base64,...">
        <img src="data:image/jpeg;base64,...">
        <img src="data:image/jpeg;base64,...">
        <img src="data:image/jpeg;base64,...">
        <img src="data:image/jpeg;base64,...">
    </div>
</section>
<section id="depoimentos">
    <h2>O que dizem nossos clientes</h2>
    <div class="testimonials">
        <div class="testimonial"><img src="data:image/jpeg;base64,..."><p>"Serviço excelente, recomendo muito a Alumividros!"</p><strong>Cliente 1</strong></div>
        <div class="testimonial"><img src="data:image/jpeg;base64,..."><p>"Atendimento rápido e profissional."</p><strong>Cliente 2</strong></div>
        <!-- Repete até Cliente 17 -->
    </div>
</section>
<section id="contato">
    <h2>Fale Conosco</h2>
    <a class="btn" href="https://wa.me/555596599930?text=Ol%C3%A1%2C%20gostaria%20de%20fazer%20um%20or%C3%A7amento" target="_blank">WhatsApp</a>
</section>
<a class="whatsapp-btn" href="https://wa.me/555596599930?text=Ol%C3%A1%2C%20gostaria%20de%20fazer%20um%20or%C3%A7amento" target="_blank">💬</a>
</body>
</html>
