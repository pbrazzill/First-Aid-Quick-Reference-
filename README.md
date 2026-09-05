<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8">
<meta name="viewport" content="width=device-width, initial-scale=1, maximum-scale=1">
<title>First Aid Quick Reference</title>
<link rel="manifest" href="data:application/json;base64,eyJuYW1lIjoiRmlyc3QgQWlkIFF1aWNrIFJlZmVyZW5jZSIsInNob3J0X25hbWUiOiJGaXJzdCBBaWQiLCJkaXNwbGF5Ijoic3RhbmRhbG9uZSIsInN0YXJ0X3VybCI6Ii4iLCJiYWNrZ3JvdW5kX2NvbG9yIjoiI2ZmZmZmZiIsInRoZW1lX2NvbG9yIjoiIzFCMkE0QSJ9">

<!-- Google tag (gtag.js) -->
<script async src="https://www.googletagmanager.com/gtag/js?id=G-RLE3VYVMM5"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'G-RLE3VYVMM5');
</script>

<style>
  :root{
    --navy:#1B2A4A;
    --navy-dark:#132038;
    --green:#3F8F3F;
    --red:#C0392B;
    --gold:#C89B3C;
    --tile-border:#E3A857;
    --bg:#F5F6F8;
    --text:#1C1C1C;
    --muted:#5B6472;
    --card:#FFFFFF;
  }
  *{box-sizing:border-box;}
  body{
    margin:0;
    font-family:-apple-system,BlinkMacSystemFont,"Segoe UI",Roboto,Helvetica,Arial,sans-serif;
    background:var(--bg);
    color:var(--text);
    -webkit-tap-highlight-color:transparent;
  }
  header.top{
    background:var(--navy);
    color:#fff;
    padding:18px 16px 22px;
    position:sticky;
    top:0;
    z-index:10;
  }
  .brand-row{
    display:flex;
    align-items:center;
    justify-content:space-between;
    gap:10px;
    margin-bottom:14px;
  }
  .brand{
    display:flex;
    align-items:center;
    gap:8px;
    font-weight:800;
    font-size:15px;
    letter-spacing:0.3px;
  }
  .brand .cross{
    width:26px;height:26px;
    background:#fff;
    border-radius:6px;
    display:flex;align-items:center;justify-content:center;
    color:var(--green);
    font-size:16px;
    font-weight:900;
  }
  .emergency-pill{
    background:var(--red);
    color:#fff;
    font-size:11px;
    font-weight:700;
    padding:6px 10px;
    border-radius:8px;
    line-height:1.3;
    text-align:right;
    white-space:nowrap;
  }
  h1.page-title{
    margin:0;
    font-size:26px;
    font-weight:800;
  }
  h1.page-title span{
    display:block;
    color:#8FD98F;
    font-size:16px;
    font-weight:800;
    letter-spacing:1px;
    margin-top:2px;
  }
  .back-btn{
    display:none;
    align-items:center;
    gap:8px;
    background:rgba(255,255,255,0.12);
    border:none;
    color:#fff;
    font-weight:700;
    font-size:14px;
    padding:8px 14px;
    border-radius:20px;
  }
  .subtext{
    padding:16px 18px 4px;
    text-align:center;
    color:var(--muted);
    font-size:14px;
  }
  #home{padding-bottom:30px;}
  .grid{
    display:grid;
    grid-template-columns:1fr 1fr;
    gap:14px;
    padding:14px 16px 24px;
  }
  .tile{
    background:var(--card);
    border:3px solid var(--tile-border);
    border-radius:12px;
    padding:16px 8px;
    display:flex;
    flex-direction:column;
    align-items:center;
    gap:8px;
    box-shadow:0 2px 4px rgba(0,0,0,0.06);
  }
  .tile .icon{font-size:30px; line-height:1;}
  .tile .label{
    font-weight:800;
    font-size:12.5px;
    text-align:center;
    letter-spacing:0.3px;
    color:var(--navy);
  }
  .topic-view{display:none; padding:16px 16px 40px;}
  .topic-view.active{display:block;}
  #home.active{display:block;}
  #home{display:none;}
  .t-header{
    display:flex;
    align-items:flex-start;
    justify-content:space-between;
    gap:10px;
    margin-bottom:14px;
  }
  .t-title{
    display:flex;
    align-items:center;
    gap:10px;
  }
  .t-title .icon-badge{
    width:44px;height:44px;
    border-radius:50%;
    background:var(--navy);
    color:#fff;
    display:flex;align-items:center;justify-content:center;
    font-size:22px;
    flex-shrink:0;
  }
  .t-title h2{margin:0; font-size:22px; color:var(--navy);}
  .t-title p{margin:2px 0 0; font-size:13px; color:var(--muted);}
  .call-box{
    background:var(--red);
    color:#fff;
    border-radius:10px;
    padding:12px 14px;
    display:flex;
    align-items:center;
    gap:12px;
    margin-bottom:14px;
  }
  .call-box .num{
    font-size:20px;
    font-weight:900;
    white-space:nowrap;
  }
  .call-box .txt{font-size:13px; font-weight:600; line-height:1.35;}
  .card{
    background:var(--card);
    border-radius:12px;
    padding:14px 16px;
    margin-bottom:12px;
    box-shadow:0 1px 3px rgba(0,0,0,0.06);
  }
  .card h3{
    margin:0 0 10px;
    font-size:14px;
    text-transform:uppercase;
    letter-spacing:0.5px;
    color:var(--navy);
  }
  .steps{list-style:none; margin:0; padding:0;}
  .steps li{
    display:flex;
    gap:10px;
    margin-bottom:10px;
    font-size:14.5px;
    line-height:1.4;
  }
  .steps li:last-child{margin-bottom:0;}
  .num-badge{
    flex-shrink:0;
    width:24px;height:24px;
    border-radius:50%;
    background:var(--green);
    color:#fff;
    font-weight:800;
    font-size:12.5px;
    display:flex;align-items:center;justify-content:center;
    margin-top:1px;
  }
  ul.signs{list-style:none; margin:0; padding:0;}
  ul.signs li{
    font-size:14.5px;
    line-height:1.4;
    padding:6px 0;
    border-bottom:1px solid #EEE;
  }
  ul.signs li:last-child{border-bottom:none;}
  ul.signs li:before{content:"•  "; color:var(--green); font-weight:900;}
  .two-col{display:grid; grid-template-columns:1fr 1fr; gap:12px;}
  .warn{
    background:#FFF4E5;
    border-left:4px solid var(--gold);
    border-radius:8px;
    padding:10px 12px;
    font-size:13.5px;
    font-weight:600;
    color:#7a5a12;
  }
  .draft-flag{
    background:#EAF2FF;
    border:1px dashed #7EA6E0;
    border-radius:8px;
    padding:8px 10px;
    font-size:12px;
    color:#2A4C7A;
    margin-bottom:12px;
    font-weight:600;
  }
  footer.appfoot{
    text-align:center;
    padding:20px 16px 34px;
    font-size:11.5px;
    color:var(--muted);
  }
</style>
</head>
<body>

<header class="top">
  <div class="brand-row">
    <button class="back-btn" id="backBtn" onclick="showHome()">&larr; Topics</button>
    <div class="brand" id="brandHome" style="display:none">
      <div class="cross">+</div> ALPHA SAFETY
    </div>
    <div class="emergency-pill">IN AN EMERGENCY<br>CALL 112 OR 999</div>
  </div>
  <h1 class="page-title" id="pageTitle">FIRST AID<span>QUICK REFERENCE</span></h1>
</header>

<div id="home" class="active">
  <p class="subtext">Select a topic below for quick, easy to follow guidance.</p>
  <div class="grid" id="topicGrid"></div>
  <footer class="appfoot">Alpha Safety Training &amp; Consultancy — for guidance only, not a substitute for training or emergency services.</footer>
</div>

<div id="topicContainer"></div>

<script>
const topics = [
  {id:"cpr", icon:"❤️", label:"CPR", real:true},
  {id:"heart-attack", icon:"💚", label:"Heart Attack", real:false},
  {id:"stroke", icon:"🧠", label:"Stroke", real:false},
  {id:"bleeding", icon:"🩸", label:"Severe Bleeding", real:false},
  {id:"meningitis", icon:"🧠", label:"Meningitis", real:true},
  {id:"sepsis", icon:"🦠", label:"Sepsis", real:true},
  {id:"seizures", icon:"⚡", label:"Seizures", real:false},
  {id:"fainting", icon:"🧍", label:"Fainting", real:false},
  {id:"asthma", icon:"🌬️", label:"Asthma", real:false},
  {id:"hyperthermia", icon:"🌡️", label:"Hyperthermia", real:false},
  {id:"hypothermia", icon:"❄️", label:"Hypothermia", real:false},
  {id:"burns", icon:"🔥", label:"Burns", real:false},
  {id:"concussion", icon:"🤕", label:"Concussion", real:false},
  {id:"allergic", icon:"😷", label:"Allergic Reaction", real:false},
  {id:"diabetes", icon:"💉", label:"Diabetes", real:false}
];

const grid = document.getElementById('topicGrid');
topics.forEach(t=>{
  const div = document.createElement('div');
  div.className='tile';
  div.onclick=()=>showTopic(t.id);
  div.innerHTML = `<div class="icon">${t.icon}</div><div class="label">${t.label}</div>`;
  grid.appendChild(div);
});

function showHome(){
  document.getElementById('home').classList.add('active');
  document.querySelectorAll('.topic-view').forEach(v=>v.classList.remove('active'));
  document.getElementById('backBtn').style.display='none';
  document.getElementById('brandHome').style.display='flex';
  document.getElementById('pageTitle').innerHTML = 'FIRST AID<span>QUICK REFERENCE</span>';
  window.scrollTo(0,0);
  if (typeof gtag === 'function') { gtag('event', 'page_view', { page_title: 'Home' }); }
}
function showTopic(id){
  document.getElementById('home').classList.remove('active');
  document.querySelectorAll('.topic-view').forEach(v=>v.classList.remove('active'));
  document.getElementById(id).classList.add('active');
  document.getElementById('backBtn').style.display='flex';
  document.getElementById('brandHome').style.display='none';
  const t = topics.find(x=>x.id===id);
  document.getElementById('pageTitle').textContent = t.label.toUpperCase();
  window.scrollTo(0,0);
  if (typeof gtag === 'function') { gtag('event', 'view_topic', { topic_id: id, topic_label: t.label }); }
}

document.getElementById('topicContainer').innerHTML = `

<!-- CPR & AED -->
<div class="topic-view" id="cpr">
  <div class="t-header">
    <div class="t-title">
      <div class="icon-badge">❤️</div>
      <div><h2>CPR &amp; AED</h2><p>Act quickly — it can save a life</p></div>
    </div>
  </div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Start CPR straight away.<br>Use an AED as soon as it is available.</div></div>
  <div class="card">
    <h3>When to use CPR</h3>
    <ul class="signs">
      <li>The person is unresponsive</li>
      <li>Not breathing normally or not breathing at all</li>
      <li>No signs of life</li>
    </ul>
  </div>
  <div class="card">
    <h3>How to perform CPR</h3>
    <ol class="steps">
      <li><span class="num-badge">1</span>Tap the person on the shoulder and shout "Are you OK?" No response?</li>
      <li><span class="num-badge">2</span>Call 112 or 999. Ask someone to get an AED if available.</li>
      <li><span class="num-badge">3</span>Look, listen and feel for normal breathing for no more than 10 seconds. Not normal breathing?</li>
      <li><span class="num-badge">4</span>Place hands in the centre of the chest. Push hard and fast: 30 compressions.</li>
      <li><span class="num-badge">5</span>Open the airway. Give 2 rescue breaths. Chest should rise. Repeat cycle.</li>
      <li><span class="num-badge">6</span>Continue 30 compressions and 2 breaths. Keep going until help arrives or the person starts breathing.</li>
    </ol>
  </div>
  <div class="card">
    <h3>Using an AED</h3>
    <ol class="steps">
      <li><span class="num-badge">1</span>Turn on the AED and follow the voice prompts.</li>
      <li><span class="num-badge">2</span>Attach pads to the bare chest as shown.</li>
      <li><span class="num-badge">3</span>Step back and let the AED analyse the rhythm.</li>
      <li><span class="num-badge">4</span>If a shock is advised, press the shock button. Then resume CPR.</li>
    </ol>
  </div>
  <div class="card">
    <h3>Signs of cardiac arrest</h3>
    <ul class="signs">
      <li>Sudden collapse</li><li>Unresponsive</li><li>Not breathing normally or not breathing</li><li>No pulse</li><li>No signs of life</li>
    </ul>
  </div>
  <div class="two-col">
    <div class="card"><h3>What not to do</h3><ul class="signs"><li>Do not delay — start CPR immediately</li><li>Do not stop unless the person starts breathing or help arrives</li><li>Do not be afraid to use an AED</li></ul></div>
    <div class="card"><h3>Who is at risk?</h3><ul class="signs"><li>Heart disease</li><li>Older adults</li><li>Lack of exercise</li><li>High blood pressure</li></ul></div>
  </div>
  <div class="card"><h3>Remember</h3><ul class="signs"><li>Early CPR can double or triple survival chances</li><li>An AED is safe and easy to use</li><li>Be prepared. Learn. Act. Save a life.</li></ul></div>
  <div class="card"><h3>Aftercare</h3><p style="font-size:14.5px; margin:0;">If the person starts breathing, place them in the recovery position and monitor closely.</p></div>
</div>

<!-- MENINGITIS -->
<div class="topic-view" id="meningitis">
  <div class="t-header">
    <div class="t-title">
      <div class="icon-badge">🧠</div>
      <div><h2>Meningitis</h2><p>Inflammation of the membranes around the brain and spinal cord. Can be life-threatening. Act quickly.</p></div>
    </div>
  </div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Early treatment can save lives and prevent serious complications.</div></div>
  <div class="card">
    <h3>Recognise the signs and symptoms</h3>
    <ul class="signs">
      <li>High fever — sudden onset of high temperature</li>
      <li>Severe headache — different from usual headaches</li>
      <li>Nausea and vomiting</li>
      <li>Stiff neck — difficulty bending the neck forward</li>
      <li>Confusion or drowsiness, disorientation</li>
      <li>Sensitivity to light — bright lights cause discomfort</li>
      <li>Rash that doesn't fade when pressed (see glass test below)</li>
    </ul>
  </div>
  <div class="card">
    <h3>Rash test (glass test)</h3>
    <ol class="steps">
      <li><span class="num-badge">1</span>Press the side of a clear glass firmly against the rash.</li>
      <li><span class="num-badge">2</span>If the spots do NOT fade or disappear, seek immediate medical help.</li>
    </ol>
  </div>
  <div class="warn">Seek immediate medical help if they have: any of the above symptoms, a rash that does not fade when pressed, seizures or fits, difficulty breathing, or symptoms getting worse quickly.</div>
  <div class="card" style="margin-top:12px;">
    <h3>What to do</h3>
    <ol class="steps">
      <li><span class="num-badge">1</span>Stay calm — call 112 or 999 immediately.</li>
      <li><span class="num-badge">2</span>Help them rest — keep them lying down in a quiet, dimly lit room.</li>
      <li><span class="num-badge">3</span>Keep them comfortable — do not give food. Offer small sips of water if fully alert and not vomiting.</li>
      <li><span class="num-badge">4</span>Monitor closely — keep checking their condition and be ready to give information to emergency services.</li>
      <li><span class="num-badge">5</span>Do not delay — early treatment is crucial.</li>
      <li><span class="num-badge">6</span>Get medical help immediately or go to hospital.</li>
    </ol>
  </div>
  <div class="card"><h3>More common in</h3><ul class="signs"><li>Babies and children</li><li>Teenagers and young adults</li><li>People with weakened immune systems</li></ul></div>
</div>

<!-- SEPSIS -->
<div class="topic-view" id="sepsis">
  <div class="t-header">
    <div class="t-title">
      <div class="icon-badge">🦠</div>
      <div><h2>Sepsis</h2><p>A life-threatening reaction to an infection. Can lead to organ failure and death if not treated early. Anyone can get sepsis.</p></div>
    </div>
  </div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Early treatment saves lives. Do not wait.</div></div>
  <div class="card">
    <h3>Know the signs</h3>
    <p style="font-size:13px;color:var(--muted);margin-top:-4px;">Sepsis can start like flu, gastroenteritis or a chest infection. Look for any of these signs — especially if they get worse quickly.</p>
    <ul class="signs">
      <li>High or very low temperature (shivering or feeling hot)</li>
      <li>Shivering, feeling very cold or disoriented</li>
      <li>Rapid breathing or shortness of breath</li>
      <li>Fast heartbeat</li>
      <li>Confusion, slurred speech or drowsiness</li>
      <li>Extreme pain or discomfort</li>
    </ul>
  </div>
  <div class="warn">If you are worried about an infection and think sepsis is possible, act fast.</div>
  <div class="card" style="margin-top:12px;">
    <h3>What to do — act fast</h3>
    <ol class="steps">
      <li><span class="num-badge">1</span>Call 112 or 999 immediately. Early treatment in hospital is vital. Do not delay.</li>
      <li><span class="num-badge">2</span>Keep them warm and comfortable. Keep them calm and resting. Do not give food or drink unless advised.</li>
      <li><span class="num-badge">3</span>Share important information — tell the healthcare team about symptoms, medical conditions and medicines.</li>
      <li><span class="num-badge">4</span>Do not delay — sepsis can get worse very quickly. Trust your instincts and seek help early.</li>
    </ol>
  </div>
  <div class="two-col">
    <div class="card"><h3>Who is more at risk?</h3><ul class="signs"><li>Older adults (esp. over 65)</li><li>Babies and young children</li><li>People with long-term conditions</li><li>Weakened immune systems</li><li>Recently in hospital or treatment</li></ul></div>
    <div class="card"><h3>Help prevent infections</h3><ul class="signs"><li>Wash hands regularly</li><li>Keep vaccinations up to date</li><li>Keep cuts and wounds clean</li><li>Cover coughs and sneezes</li><li>Seek medical help for infections</li></ul></div>
  </div>
  <div class="warn" style="margin-top:12px;">Sepsis is a medical emergency. Acting quickly can save lives. Spot it. Treat it. Save lives.</div>
</div>

<!-- HEART ATTACK (draft) -->
<div class="topic-view" id="heart-attack">
  <div class="t-header"><div class="t-title"><div class="icon-badge">💚</div><div><h2>Heart Attack</h2><p>Occurs when blood flow to the heart is blocked. Act fast.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call immediately — do not drive them yourself.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>Signs and symptoms</h3><ul class="signs"><li>Chest pain or pressure, may spread to arm, jaw, neck or back</li><li>Shortness of breath</li><li>Nausea, sweating, light-headedness</li><li>Sense of impending doom</li></ul></div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Call 112 or 999 immediately.</li>
    <li><span class="num-badge">2</span>Sit them down in a comfortable position, leaning slightly forward.</li>
    <li><span class="num-badge">3</span>Loosen tight clothing.</li>
    <li><span class="num-badge">4</span>If they have prescribed medication (e.g. GTN spray/aspirin), assist as trained.</li>
    <li><span class="num-badge">5</span>Monitor closely — be ready to start CPR if they become unresponsive and stop breathing normally.</li>
  </ol></div>
</div>

<!-- STROKE (draft) -->
<div class="topic-view" id="stroke">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🧠</div><div><h2>Stroke</h2><p>A medical emergency caused by interrupted blood flow to the brain. Use FAST.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Time lost is brain lost — call immediately.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>FAST test</h3><ul class="signs"><li><b>F</b>ace — has their face fallen on one side? Can they smile?</li><li><b>A</b>rms — can they raise both arms and keep them there?</li><li><b>S</b>peech — is speech slurred or garbled?</li><li><b>T</b>ime — time to call 112/999 if you see any of these signs</li></ul></div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Call 112 or 999 immediately, note the time symptoms started.</li>
    <li><span class="num-badge">2</span>Keep them calm and still. Do not give food or drink.</li>
    <li><span class="num-badge">3</span>If unconscious but breathing, place in the recovery position.</li>
    <li><span class="num-badge">4</span>Monitor breathing and responsiveness until help arrives.</li>
  </ol></div>
</div>

<!-- SEVERE BLEEDING (draft) -->
<div class="topic-view" id="bleeding">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🩸</div><div><h2>Severe Bleeding</h2><p>Control blood loss quickly to prevent shock.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call immediately for severe or uncontrolled bleeding.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Apply firm, direct pressure to the wound with a clean dressing or cloth.</li>
    <li><span class="num-badge">2</span>If possible, raise the injured area above heart level.</li>
    <li><span class="num-badge">3</span>Do not remove any embedded object — pad around it.</li>
    <li><span class="num-badge">4</span>Keep applying pressure and add more dressings on top if blood soaks through — do not remove the first layer.</li>
    <li><span class="num-badge">5</span>Lay them down and treat for shock (keep warm) while waiting for help.</li>
  </ol></div>
  <div class="warn">Use a tourniquet only if trained and bleeding is catastrophic and uncontrolled.</div>
</div>

<!-- SEIZURES (draft) -->
<div class="topic-view" id="seizures">
  <div class="t-header"><div class="t-title"><div class="icon-badge">⚡</div><div><h2>Seizures</h2><p>Keep the person safe until it passes.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call if it's their first seizure, lasts over 5 mins, or repeats.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Protect them from injury — clear the area of hazards.</li>
    <li><span class="num-badge">2</span>Do not restrain them or put anything in their mouth.</li>
    <li><span class="num-badge">3</span>Cushion their head if possible.</li>
    <li><span class="num-badge">4</span>Time the seizure.</li>
    <li><span class="num-badge">5</span>Once it stops, place in the recovery position and stay with them until fully recovered.</li>
  </ol></div>
</div>

<!-- FAINTING (draft) -->
<div class="topic-view" id="fainting">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🧍</div><div><h2>Fainting</h2><p>A brief loss of consciousness from reduced blood flow to the brain.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call if they don't recover quickly or you're unsure why they fainted.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Lay them flat and raise their legs to improve blood flow.</li>
    <li><span class="num-badge">2</span>Loosen tight clothing.</li>
    <li><span class="num-badge">3</span>Ensure fresh air, do not crowd them.</li>
    <li><span class="num-badge">4</span>Once recovered, help them sit up slowly.</li>
    <li><span class="num-badge">5</span>If they don't regain consciousness quickly, treat as unresponsive and check breathing.</li>
  </ol></div>
</div>

<!-- ASTHMA (draft) -->
<div class="topic-view" id="asthma">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🌬️</div><div><h2>Asthma Attack</h2><p>Airways narrow, making breathing difficult.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call if the inhaler isn't helping or symptoms are severe.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Keep them calm and sitting upright — do not lie them down.</li>
    <li><span class="num-badge">2</span>Help them use their reliever inhaler (usually blue), one puff at a time.</li>
    <li><span class="num-badge">3</span>If no improvement in a few minutes, call 112/999.</li>
    <li><span class="num-badge">4</span>Continue giving puffs of inhaler while waiting for help.</li>
  </ol></div>
</div>

<!-- HYPERTHERMIA (draft) -->
<div class="topic-view" id="hyperthermia">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🌡️</div><div><h2>Hyperthermia / Heat Illness</h2><p>Overheating of the body, from heat exhaustion to heat stroke.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call immediately if confused, not sweating, or unresponsive — signs of heat stroke.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Move them to a cool place.</li>
    <li><span class="num-badge">2</span>Remove excess clothing.</li>
    <li><span class="num-badge">3</span>Cool the skin — sponge with cool water, fan them.</li>
    <li><span class="num-badge">4</span>Give sips of water if fully alert.</li>
    <li><span class="num-badge">5</span>If no improvement or symptoms worsen, call 112/999.</li>
  </ol></div>
</div>

<!-- HYPOTHERMIA (draft) -->
<div class="topic-view" id="hypothermia">
  <div class="t-header"><div class="t-title"><div class="icon-badge">❄️</div><div><h2>Hypothermia</h2><p>Dangerously low body temperature.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call for severe or worsening hypothermia.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Move them somewhere warm and sheltered.</li>
    <li><span class="num-badge">2</span>Remove wet clothing, wrap in dry blankets/layers.</li>
    <li><span class="num-badge">3</span>Warm gradually — do not use direct heat (hot water bottles, fires) on the skin.</li>
    <li><span class="num-badge">4</span>Give warm (not hot) sweet drinks if fully alert. No alcohol.</li>
    <li><span class="num-badge">5</span>Handle gently — rough movement can trigger cardiac issues in severe cases.</li>
  </ol></div>
</div>

<!-- BURNS (draft) -->
<div class="topic-view" id="burns">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🔥</div><div><h2>Burns</h2><p>Cool the burn, protect the area.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call for large, deep burns or burns to face/hands/airway.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Cool the burn under cool running water for 20 minutes.</li>
    <li><span class="num-badge">2</span>Remove jewellery/clothing near the burn (unless stuck to skin).</li>
    <li><span class="num-badge">3</span>Cover loosely with cling film or a clean, non-fluffy dressing.</li>
    <li><span class="num-badge">4</span>Do not use ice, creams, or burst blisters.</li>
    <li><span class="num-badge">5</span>Treat for shock and monitor.</li>
  </ol></div>
</div>

<!-- CONCUSSION (draft) -->
<div class="topic-view" id="concussion">
  <div class="t-header"><div class="t-title"><div class="icon-badge">🤕</div><div><h2>Concussion</h2><p>A mild traumatic brain injury from a knock to the head.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call if they lose consciousness, vomit repeatedly, or seem confused.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Stop what they're doing and keep them still.</li>
    <li><span class="num-badge">2</span>Apply a cold pack to any swelling (wrapped, not direct on skin).</li>
    <li><span class="num-badge">3</span>Watch closely for worsening symptoms — confusion, vomiting, drowsiness, unequal pupils.</li>
    <li><span class="num-badge">4</span>Do not let them return to activity that day. Seek medical review.</li>
  </ol></div>
</div>

<!-- ALLERGIC REACTION (draft) -->
<div class="topic-view" id="allergic">
  <div class="t-header"><div class="t-title"><div class="icon-badge">😷</div><div><h2>Allergic Reaction</h2><p>From mild reactions to life-threatening anaphylaxis.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call immediately for signs of anaphylaxis.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>Signs of anaphylaxis</h3><ul class="signs"><li>Swelling of face, lips, tongue or throat</li><li>Difficulty breathing or wheezing</li><li>Widespread rash or hives</li><li>Dizziness, collapse</li></ul></div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>Call 112 or 999 immediately.</li>
    <li><span class="num-badge">2</span>If they have an auto-injector (e.g. EpiPen), help them use it as trained.</li>
    <li><span class="num-badge">3</span>Lay them flat, raise legs (sit up if breathing difficulty). Do not stand or walk them.</li>
    <li><span class="num-badge">4</span>A second dose may be given after 5-15 mins if no improvement and a second injector is available.</li>
    <li><span class="num-badge">5</span>Start CPR if they become unresponsive and stop breathing normally.</li>
  </ol></div>
</div>

<!-- DIABETES (draft) -->
<div class="topic-view" id="diabetes">
  <div class="t-header"><div class="t-title"><div class="icon-badge">💉</div><div><h2>Diabetic Emergency</h2><p>Low blood sugar (hypoglycaemia) needs quick action.</p></div></div></div>
  <div class="call-box"><div class="num">112 / 999</div><div class="txt">Call if they become unresponsive or won't improve.</div></div>
  <div class="draft-flag">Draft content — please review/edit against your own material.</div>
  <div class="card"><h3>Signs of a hypo</h3><ul class="signs"><li>Shaking, sweating, confusion</li><li>Pale, hunger, irritability</li><li>Drowsiness, slurred speech</li></ul></div>
  <div class="card"><h3>What to do</h3><ol class="steps">
    <li><span class="num-badge">1</span>If alert and able to swallow, give a fast-acting sugar (glucose tablets, sugary drink).</li>
    <li><span class="num-badge">2</span>Follow with a longer-acting carbohydrate once they improve.</li>
    <li><span class="num-badge">3</span>If they lose consciousness, do not give anything by mouth — call 112/999 and place in the recovery position.</li>
    <li><span class="num-badge">4</span>Monitor closely until fully recovered or help arrives.</li>
  </ol></div>
</div>

`;
</script>
</body>
</html>
