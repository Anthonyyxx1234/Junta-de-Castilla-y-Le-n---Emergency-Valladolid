<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Junta de Castilla y León | Emergency Valladolid</title>
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600;700&display=swap" rel="stylesheet">
<style>
/* ==== BASE GENERAL ==== */
*{margin:0;padding:0;box-sizing:border-box;}
body{
  font-family:'Poppins',sans-serif;
  color:#222;
  background:#f4f4f8;
  overflow-x:hidden;
}

/* ==== HEADER ==== */
header{
  position:fixed;top:0;left:0;width:100%;
  background:rgba(0,0,0,0.7);
  backdrop-filter:blur(6px);
  display:flex;align-items:center;justify-content:space-between;
  padding:1rem 3rem;
  z-index:1000;
  transition:background 0.4s;
}
header h1{
  color:#ffd700;font-size:1.6rem;font-weight:700;
  letter-spacing:1px;
}
nav ul{display:flex;list-style:none;}
nav li{margin-left:2rem;}
nav a{
  color:#fff;text-decoration:none;font-weight:500;
  transition:color 0.3s;
}
nav a:hover{color:#ffd700;}

/* ==== HERO ==== */
.hero{
  height:100vh;
  background:url('https://upload.wikimedia.org/wikipedia/commons/f/f6/Valladolid_cathedral.jpg') center/cover fixed no-repeat;
  display:flex;flex-direction:column;align-items:center;justify-content:center;
  color:white;text-align:center;
  position:relative;
}
.hero::after{
  content:"";position:absolute;inset:0;background:rgba(0,0,0,0.45);
}
.hero h2{
  position:relative;font-size:3rem;font-weight:700;margin-bottom:1rem;z-index:1;
}
.hero p{
  position:relative;max-width:800px;font-size:1.2rem;z-index:1;
}

/* ==== SECCIONES ==== */
section{
  padding:6rem 8%;
}
.section-title{
  font-size:2.6rem;
  color:#7b0000;
  text-align:center;
  margin-bottom:3rem;
  font-weight:700;
  position:relative;
}
.section-title::after{
  content:"";
  width:100px;height:4px;background:#ffd700;
  display:block;margin:0.5rem auto 0;
  border-radius:2px;
}

/* ==== EMERGENCY VALLADOLID ==== */
.ev{
  background:linear-gradient(145deg,#fff,#f3f3f3);
  border-radius:18px;
  box-shadow:0 4px 25px rgba(0,0,0,0.1);
  padding:3rem;
  transition:transform 0.3s;
}
.ev:hover{transform:translateY(-5px);}
.ev h3{color:#7b0000;font-size:1.8rem;margin-bottom:1rem;}
.ev p{line-height:1.7;margin-bottom:1rem;}
.ev ul{margin-left:2rem;list-style:square;color:#333;}

/* ==== GRID GENERAL ==== */
.grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(320px,1fr));
  gap:2.5rem;
}

/* ==== CARD DEPARTAMENTAL ==== */
.card{
  background:white;
  border-radius:16px;
  box-shadow:0 4px 20px rgba(0,0,0,0.1);
  overflow:hidden;
  transition:transform 0.3s,box-shadow 0.3s;
}
.card:hover{
  transform:translateY(-8px);
  box-shadow:0 8px 25px rgba(0,0,0,0.15);
}
.card img{
  width:100%;
  height:220px;
  object-fit:cover;
}
.card-content{
  padding:1.5rem;
}
.card-content h3{
  color:#7b0000;font-size:1.3rem;margin-bottom:0.5rem;
}

/* ==== BIOGRAFÍAS ==== */
.bio-grid{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(280px,1fr));
  gap:2rem;
}
.bio-card{
  background:white;border-radius:16px;text-align:center;
  padding:2rem;box-shadow:0 2px 12px rgba(0,0,0,0.1);
  transition:transform 0.3s;
}
.bio-card:hover{transform:translateY(-6px);}
.bio-card img{
  width:120px;height:120px;border-radius:50%;
  object-fit:cover;margin-bottom:1rem;
}
.bio-card h3{color:#7b0000;font-size:1.2rem;margin-bottom:0.3rem;}

/* ==== GALERÍA ==== */
.gallery{
  display:grid;
  grid-template-columns:repeat(auto-fit,minmax(300px,1fr));
  gap:1rem;
}
.gallery img{
  width:100%;height:230px;object-fit:cover;border-radius:10px;
  transition:transform 0.3s,filter 0.3s;
}
.gallery img:hover{
  transform:scale(1.05);
  filter:brightness(1.1);
}

/* ==== CONTACTO ==== */
.contact{
  text-align:center;
}
.contact p{margin-bottom:1rem;font-size:1rem;}
.contact a{color:#7b0000;font-weight:bold;text-decoration:none;}
.contact a:hover{color:#ffd700;}

/* ==== FOOTER ==== */
footer{
  background:#111;color:white;text-align:center;
  padding:2rem;margin-top:3rem;
  font-size:0.9rem;
}
</style>
</head>
<body>

<header>
  <h1>Junta de Castilla y León | Emergency Valladolid</h1>
  <nav>
    <ul>
      <li><a href="#inicio">Inicio</a></li>
      <li><a href="#emergency">Emergency</a></li>
      <li><a href="#guardia">Guardia Civil</a></li>
      <li><a href="#cnp">CNP</a></li>
      <li><a href="#ffaa">FFAA</a></li>
      <li><a href="#bio">Biografías</a></li>
      <li><a href="#galeria">Galería</a></li>
      <li><a href="#contacto">Contacto</a></li>
    </ul>
  </nav>
</header>

<section id="inicio" class="hero">
  <h2>Protegiendo a Castilla y León</h2>
  <p>Junta de Castilla y León | Emergency Valladolid — Un compromiso conjunto entre Guardia Civil, Cuerpo Nacional de Policía y Fuerzas Armadas por la seguridad y bienestar de todos.</p>
</section>

<section id="emergency">
  <h2 class="section-title">Emergency Valladolid</h2>
  <div class="ev">
    <h3>Unidad Central de Coordinación Regional</h3>
    <p>Emergency Valladolid es el eje principal en situaciones críticas: catástrofes, emergencias médicas, rescates y coordinación táctica entre cuerpos. Está formada por personal altamente capacitado con equipos de última tecnología.</p>
    <ul>
      <li>Unidad Médica Avanzada (UMA)</li>
      <li>Unidad de Rescate Urbano (URU)</li>
      <li>Centro de Coordinación Estratégica (CCE)</li>
      <li>Unidad de Apoyo Táctico (UAT)</li>
      <li>Departamento de Comunicación y Logística</li>
    </ul>
  </div>
</section>

<section id="guardia">
  <h2 class="section-title">Guardia Civil</h2>
  <div class="grid">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/44/Guardia_Civil_Coche.jpg">
      <div class="card-content">
        <h3>Tráfico</h3>
        <p>Supervisión de carreteras, control de accidentes y gestión de emergencias viales.</p>
      </div>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/a/a1/Guardia_Civil_SEPRONA.jpg">
      <div class="card-content">
        <h3>SEPRONA</h3>
        <p>Protección ambiental, control de incendios, fauna y espacios naturales.</p>
      </div>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/7/7a/Guardia_Civil_UEI.jpg">
      <div class="card-content">
        <h3>UEI</h3>
        <p>Unidad de élite en operaciones antiterroristas y de alto riesgo.</p>
      </div>
    </div>
  </div>
</section>

<section id="cnp">
  <h2 class="section-title">Cuerpo Nacional de Policía</h2>
  <div class="grid">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/f/fb/Polic%C3%ADa_Nacional_Espa%C3%B1a_coche.jpg">
      <div class="card-content">
        <h3>UIP</h3>
        <p>Unidad de Intervención Policial: control de disturbios y apoyo en operaciones complejas.</p>
      </div>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/4/41/Policia_Nacional_Espa%C3%B1a.jpg">
      <div class="card-content">
        <h3>Policía Judicial</h3>
        <p>Investigaciones criminales, inteligencia y coordinación judicial.</p>
      </div>
    </div>
  </div>
</section>

<section id="ffaa">
  <h2 class="section-title">Fuerzas Armadas</h2>
  <div class="grid">
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/8/85/Ej%C3%A9rcito_de_Tierra_Espa%C3%B1a.jpg">
      <div class="card-content">
        <h3>Ejército de Tierra</h3>
        <p>Defensa territorial, apoyo humanitario y respuesta ante emergencias.</p>
      </div>
    </div>
    <div class="card">
      <img src="https://upload.wikimedia.org/wikipedia/commons/6/6a/Unidad_Militar_de_Emergencias.jpg">
      <div class="card-content">
        <h3>UME</h3>
        <p>Unidad Militar de Emergencias: primera respuesta ante desastres naturales.</p>
      </div>
    </div>
  </div>
</section>

<section id="bio">
  <h2 class="section-title">Biografías</h2>
  <div class="bio-grid">
    <div class="bio-card">
      <img src="https://randomuser.me/api/portraits/men/40.jpg">
      <h3>Comandante Luis Ortega</h3>
      <p>Director General de Emergency Valladolid. Estratega en coordinación interinstitucional.</p>
    </div>
    <div class="bio-card">
      <img src="https://randomuser.me/api/portraits/women/44.jpg">
      <h3>Capitana Marta Gómez</h3>
      <p>Responsable de la Unidad Médica. 12 años de experiencia en operaciones internacionales.</p>
    </div>
  </div>
</section>

<section id="galeria">
  <h2 class="section-title">Galería Multimedia</h2>
  <div class="gallery">
    <img src="https://upload.wikimedia.org/wikipedia/commons/1/1b/Guardia_Civil_patruya.jpg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/d/d1/Policia_Nacional_Patrulla.jpg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/e/ed/Ejercito_Aire_Espana.jpg">
    <img src="https://upload.wikimedia.org/wikipedia/commons/2/28/UME_Actuacion.jpg">
  </div>
</section>

<section id="contacto">
  <h2 class="section-title">Contacto</h2>
  <div class="contact">
    <p>📍 Sede Central: Valladolid, Castilla y León, España</p>
    <p>📧 <a href="mailto:contacto@emergencyvalladolid.es">contacto@emergencyvalladolid.es</a></p>
    <p>🌐 Síguenos en redes oficiales</p>
  </div>
</section>

<footer>
  <p>© 2025 Junta de Castilla y León | Emergency Valladolid — Todos los derechos reservados.</p>
</footer>

</body>
</html>
