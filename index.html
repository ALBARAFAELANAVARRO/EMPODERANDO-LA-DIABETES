<!DOCTYPE html>
<html lang="es">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
<title>Mi Dulce Control - Diabetes</title>
<style>
*{box-sizing:border-box;font-family:'Segoe UI',sans-serif}
body{margin:0;background:#f0f7ff;color:#222;padding-bottom:90px}
header{background:#0d6efd;color:white;padding:18px;text-align:center;border-radius:0 0 20px 20px}
header h1{margin:0;font-size:22px}
header p{margin:4px 0 0;opacity:.9;font-size:13px}
.card{background:white;margin:12px;border-radius:16px;padding:16px;box-shadow:0 2px 10px rgba(0,0,0,.08)}
h2{font-size:17px;margin:0 0 10px;color:#0d6efd}
label{font-size:13px;font-weight:600;display:block;margin-top:10px}
input,select,textarea{width:100%;padding:11px;border:1px solid #ddd;border-radius:10px;margin-top:4px;font-size:15px}
button{border:none;border-radius:12px;padding:13px;width:100%;font-weight:700;font-size:15px;cursor:pointer;margin-top:10px}
.btn-blue{background:#0d6efd;color:white}
.btn-green{background:#198754;color:white}
.btn-red{background:#dc3545;color:white}
.btn-orange{background:#fd7e14;color:white}
.row{display:flex;gap:10px}
.row>*{flex:1}
table{width:100%;font-size:13px;border-collapse:collapse;margin-top:10px}
th,td{padding:8px;border-bottom:1px solid #eee;text-align:left}
.badge{padding:3px 8px;border-radius:20px;font-size:11px;color:white}
.low{background:#198754}.normal{background:#0d6efd}.high{background:#dc3545}
.sos{position:fixed;bottom:14px;left:12px;right:12px;background:#dc3545;color:white;text-align:center;padding:15px;border-radius:50px;font-weight:800;box-shadow:0 5px 15px rgba(220,53,69,.4);z-index:99}
/* Respiracion */
.breath-wrap{text-align:center;padding:10px}
#breathCircle{width:150px;height:150px;border-radius:50%;background:#0dcaf0;margin:15px auto;display:flex;align-items:center;justify-content:center;color:white;font-weight:800;font-size:18px;transition:all 1s ease;box-shadow:0 0 30px rgba(13,202,240,.5)}
#breathText{font-size:20px;font-weight:800}
#breathCount{font-size:38px;font-weight:900;color:#0d6efd}
/* Agua */
.water-wrap{text-align:center}
#glass{font-size:80px}
#waterCount{font-size:28px;font-weight:800}
.mantra{background:#fff3cd;border-left:5px solid #ffc107;padding:14px;border-radius:10px;font-style:italic;text-align:center}
nav{position:fixed;bottom:0;left:0;right:0;background:white;display:flex;justify-content:space-around;padding:10px;border-top:1px solid #ddd;z-index:100}
nav button{background:none;width:auto;padding:5px 10px;font-size:12px;color:#666}
nav button.active{color:#0d6efd}
.page{display:none}.page.active{display:block}
</style>
</head>
<body>

<header>
<h1>💙 Mi Dulce Control</h1>
<p>Control de Diabetes • Glicemia • Insulina • Bienestar</p>
</header>

<!-- INICIO -->
<div id="page-inicio" class="page active">
  <div class="card">
    <div class="mantra" id="mantraBox">“Hoy me cuido con amor, mi salud es mi prioridad.”</div>
    <button class="btn-orange" onclick="nuevaFrase()">✨ Nueva frase de inspiración</button>
    <label>Escribe tu propio mantra de hoy</label>
    <input id="miMantra" placeholder="Ej: Yo puedo con todo...">
    <button class="btn-blue" onclick="guardarMantra()">Guardar mi mantra</button>
  </div>

  <div class="card breath-wrap">
    <h2>🌬️ Respiración Profunda 4 - 4 - 6</h2>
    <p>Inhala 4s • Sostén 4s • Exhala 6s</p>
    <div id="breathCircle">RESPIRA</div>
    <div id="breathText">Pulsa Iniciar</div>
    <div id="breathCount">--</div>
    <button class="btn-green" onclick="iniciarRespiracion()">▶ Iniciar Respiración</button>
    <button onclick="detenerRespiracion()" style="background:#eee">⏹ Detener</button>
  </div>

  <div class="card water-wrap">
    <h2>💧 Tomar Agua</h2>
    <div id="glass">🥤</div>
    <div id="waterCount">0 / 8 vasos hoy</div>
    <p>Meta: 8 vasos al día</p>
    <button class="btn-blue" onclick="tomarAgua()">+ Tomé un vaso 💧</button>
    <button onclick="resetAgua()" style="background:#eee">Reiniciar día</button>
  </div>
</div>

<!-- GLICEMIA -->
<div id="page-glicemia" class="page">
  <div class="card">
    <h2>📊 Registrar Glicemia</h2>
    <label>Valor mg/dL</label>
    <input type="number" id="glicemia" placeholder="Ej: 120">
    <label>Momento</label>
    <select id="momento">
      <option>En ayunas</option><option>Antes de comer</option>
      <option>Después de comer</option><option>Antes de dormir</option><option>Me sentí mal</option>
    </select>
    <label>Nota</label>
    <input id="notaG" placeholder="Ej: Comí mucho arroz">
    <button class="btn-blue" onclick="guardarGlicemia()">Guardar Glicemia</button>
    <table><thead><tr><th>Fecha</th><th>Valor</th><th>Momento</th></tr></thead><tbody id="tablaGlicemia"></tbody></table>
  </div>

  <div class="card">
    <h2>💉 Insulina y Medicinas</h2>
    <label>Tipo de Insulina / Medicina</label>
    <input id="medNombre" placeholder="Ej: Insulina Rápida / Metformina">
    <label>Cantidad / Dosis</label>
    <input id="medDosis" placeholder="Ej: 10 unidades / 500mg">
    <label>Lugar de aplicación</label>
    <select id="medLugar"><option>Brazo</option><option>Abdomen</option><option>Pierna</option><option>Oral / Pastilla</option></select>
    <button class="btn-green" onclick="guardarMedicina()">Guardar Aplicación</button>
    <table><thead><tr><th>Hora</th><th>Medicina</th><th>Dosis</th></tr></thead><tbody id="tablaMed"></tbody></table>
  </div>
</div>

<!-- PACIENTE -->
<div id="page-paciente" class="page">
  <div class="card">
    <h2>🪪 Identificación del Paciente</h2>
    <label>Nombre completo</label><input id="pNombre" placeholder="Nombre completo">
    <label>Edad</label><input id="pEdad" type="number" placeholder="Edad">
    <label>Tipo de Diabetes</label>
    <select id="pTipo"><option>Tipo 1</option><option>Tipo 2</option><option>Gestacional</option></select>
    <label>Tipo de sangre / Alergias</label><input id="pAlergias" placeholder="Ej: O+, Alergia a penicilina">
    <label>Peso / Condición</label><input id="pPeso" placeholder="Ej: 75kg, Hipertenso">
    <button class="btn-blue" onclick="guardarPaciente()">Guardar Datos del Paciente</button>
  </div>
  <div class="card">
    <h2>🚨 Contactos de Emergencia</h2>
    <label>Nombre Médico</label><input id="dNombre" placeholder="Dr. ...">
    <label>Teléfono del Médico</label><input id="dTel" placeholder="809-...">
    <label>Contacto 1 - Nombre y Teléfono</label><input id="e1" placeholder="Ej: María - 809-...">
    <label>Contacto 2 - Nombre y Teléfono</label><input id="e2" placeholder="Ej: Juan - 829-...">
    <button class="btn-red" onclick="guardarEmergencia()">Guardar Emergencia</button>
    <p id="emergenciaInfo" style="font-size:13px"></p>
  </div>
</div>

<div class="sos" onclick="llamarSOS()">🚨 SOS - LLAMAR A EMERGENCIA</div>

<nav>
  <button class="active" onclick="showPage('inicio',this)">🏠<br>Inicio</button>
  <button onclick="showPage('glicemia',this)">📊<br>Glicemia</button>
  <button onclick="showPage('paciente',this)">🪪<br>Paciente</button>
</nav>

<script>
let frases=["“Hoy me cuido con amor, mi salud es mi prioridad.”","“Cada día que me controlo, me regalo vida.”","“No soy mi diabetes, soy más fuerte que ella.”","“Respiro, me calmo y sigo adelante.”","“Pequeños pasos todos los días me hacen más fuerte.”","“Mi cuerpo merece cuidado, paciencia y amor.”"];
let vasos=parseInt(localStorage.getItem('vasos')||0);
function showPage(id,btn){document.querySelectorAll('.page').forEach(p=>p.classList.remove('active'));document.getElementById('page-'+id).classList.add('active');document.querySelectorAll('nav button').forEach(b=>b.classList.remove('active'));btn.classList.add('active')}
function nuevaFrase(){document.getElementById('mantraBox').innerText=frases[Math.floor(Math.random()*frases.length)]}
function guardarMantra(){let v=document.getElementById('miMantra').value;if(v) document.getElementById('mantraBox').innerText='“'+v+'”';alert('Mantra guardado 💛')}
function actualizarAgua(){document.getElementById('waterCount').innerText=vasos+' / 8 vasos hoy';localStorage.setItem('vasos',vasos)}
function tomarAgua(){vasos++;actualizarAgua();if(vasos>=8) alert('¡Felicidades! Meta de agua cumplida 💧');else alert('¡Bien! Vaso '+vasos+' tomado 💧')}
function resetAgua(){vasos=0;actualizarAgua()}
actualizarAgua();

// RESPIRACION 4-4-6
let breathTimer=null;
function iniciarRespiracion(){
  detenerRespiracion();
  let fases=[{t:'INHALA',s:4,color:'#0d6efd',scale:1.4},{t:'SOSTÉN',s:4,color:'#ffc107',scale:1.4},{t:'EXHALA',s:6,color:'#198754',scale:0.8}];
  let fi=0, seg=fases[0].s;
  function paso(){
    let f=fases[fi];
    document.getElementById('breathText').innerText=f.t;
    document.getElementById('breathCount').innerText=seg;
    let c=document.getElementById('breathCircle');
    c.innerText=f.t; c.style.background=f.color; c.style.transform='scale('+f.scale+')';
    seg--;
    if(seg<0){fi=(fi+1)%3; seg=fases[fi].s;}
  }
  paso(); breathTimer=setInterval(paso,1000);
}
function detenerRespiracion(){clearInterval(breathTimer);document.getElementById('breathText').innerText='Pulsa Iniciar';document.getElementById('breathCount').innerText='--';document.getElementById('breathCircle').style.transform='scale(1)';document.getElementById('breathCircle').innerText='RESPIRA'}

// DATOS
function guardarGlicemia(){
  let v=document.getElementById('glicemia').value; if(!v) return alert('Pon el valor');
  let m=document.getElementById('momento').value; let n=document.getElementById('notaG').value;
  let lista=JSON.parse(localStorage.getItem('glicemias')||'[]'); lista.unshift({fecha:new Date().toLocaleString(),v,m,n}); localStorage.setItem('glicemias',JSON.stringify(lista));
  mostrarGlicemias(); document.getElementById('glicemia').value=''; alert('Glicemia guardada ✅');
}
function mostrarGlicemias(){
  let lista=JSON.parse(localStorage.getItem('glicemias')||'[]');
  document.getElementById('tablaGlicemia').innerHTML=lista.slice(0,10).map(x=>{
    let cls=x.v<70?'low':x.v<=140?'normal':'high';
    return `<tr><td>${x.fecha}</td><td><span class="badge ${cls}">${x.v} mg/dL</span></td><td>${x.m}</td></tr>`
  }).join('');
}
function guardarMedicina(){
  let nom=document.getElementById('medNombre').value; let dos=document.getElementById('medDosis').value; let lug=document.getElementById('medLugar').value;
  if(!nom||!dos) return alert('Completa medicina y dosis');
  let lista=JSON.parse(localStorage.getItem('meds')||'[]'); lista.unshift({hora:new Date().toLocaleString(),nom,dos,lug}); localStorage.setItem('meds',JSON.stringify(lista));
  mostrarMeds(); alert('Aplicación guardada 💉');
}
function mostrarMeds(){
  let lista=JSON.parse(localStorage.getItem('meds')||'[]');
  document.getElementById('tablaMed').innerHTML=lista.slice(0,10).map(x=>`<tr><td>${x.hora}</td><td>${x.nom} (${x.lug})</td><td>${x.dos}</td></tr>`).join('');
}
function guardarPaciente(){
  let d={n:document.getElementById('pNombre').value,e:document.getElementById('pEdad').value,t:document.getElementById('pTipo').value,a:document.getElementById('pAlergias').value,p:document.getElementById('pPeso').value};
  localStorage.setItem('paciente',JSON.stringify(d)); alert('Paciente guardado 🪪');
}
function guardarEmergencia(){
  let d={med:document.getElementById('dNombre').value,tel:document.getElementById('dTel').value,e1:document.getElementById('e1').value,e2:document.getElementById('e2').value};
  localStorage.setItem('emergencia',JSON.stringify(d));
  document.getElementById('emergenciaInfo').innerHTML=`<b>Médico:</b> ${d.med} - ${d.tel}<br><b>Contacto 1:</b> ${d.e1}<br><b>Contacto 2:</b> ${d.e2}`;
  alert('Contactos guardados 🚨');
}
function llamarSOS(){
  let d=JSON.parse(localStorage.getItem('emergencia')||'{}');
  if(d.tel) window.location.href='tel:'+d.tel;
  else alert('Guarda primero el número de tu médico en la pestaña Paciente');
}
mostrarGlicemias(); mostrarMeds();
let em=JSON.parse(localStorage.getItem('emergencia')||'null'); if(em) document.getElementById('emergenciaInfo').innerHTML=`<b>Médico:</b> ${em.med} - ${em.tel}<br><b>Contacto 1:</b> ${em.e1}<br><b>Contacto 2:</b> ${em.e2}`;
</script>
</body>
</html>
