# Calm-hub
<!doctype html>
<html lang="en">
<head>
<meta charset="utf-8" />
<meta name="viewport" content="width=device-width,initial-scale=1" />
<title>CalmHub — Luxury Emotional Listening & Healing</title>
<meta name="description" content="CalmHub by Sakshi — premium emotional listening, healing sessions and breathing practices. Book via WhatsApp or pay with UPI. Safe, compassionate, confidential." />
<meta name="keywords" content="listener, emotional support, healing, breathing exercises, online listener, spiritual healing, CalmHub, Sakshi" />
<meta name="author" content="Sakshi — CalmHub" />
<link rel="icon" href="data:;base64,iVBORw0KGgo=" />

<!-- Open Graph -->
<meta property="og:type" content="website" />
<meta property="og:title" content="CalmHub — Luxury Emotional Listening & Healing" />
<meta property="og:description" content="CalmHub by Sakshi — premium emotional listening, healing sessions and breathing practices. Book via WhatsApp or pay with UPI." />
<meta property="og:image" content="https://i.imgur.com/liaQwEt.png" />
<meta property="og:url" content="https://yourusername.github.io/CalmHub" />

<!-- JSON-LD structured data -->
<script type="application/ld+json">
{
  "@context": "https://schema.org",
  "@type": "WebSite",
  "name": "CalmHub",
  "url": "https://yourusername.github.io/CalmHub",
  "author": { "@type": "Person", "name": "Sakshi" },
  "description": "Premium emotional listening and healing sessions."
}
</script>

<!-- Fonts & minimal CSS (all inline for single-file) -->
<link href="https://fonts.googleapis.com/css2?family=Poppins:wght@300;400;600&family=Playfair+Display:wght@600&display=swap" rel="stylesheet">

<style>
  :root{
    --deep:#072a1f;        /* dark emerald */
    --emerald:#0f5f46;     /* primary emerald */
    --soft:#eaf7ef;        /* pale mint background */
    --gold:#c9a035;        /* gold accent */
    --muted:#334244;
    --card:#ffffff;
    --glass: rgba(255,255,255,0.7);
    --maxw:1100px;
  }
  *{box-sizing:border-box}
  html,body{height:100%}
  body{
    margin:0;
    font-family: "Poppins", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
    background: linear-gradient(180deg,var(--soft),#fbfffb);
    color:var(--muted);
    -webkit-font-smoothing:antialiased;
    -moz-osx-font-smoothing:grayscale;
  }

  /* ---------- Top header & navigation ---------- */
  .topbar{
    background: linear-gradient(90deg, rgba(255,255,255,0.85), rgba(255,255,255,0.6));
    backdrop-filter: blur(6px);
    border-bottom:1px solid rgba(15,20,15,0.04);
    position:sticky; top:0; z-index:120;
    padding:12px 18px;
    display:flex; align-items:center; justify-content:center;
    box-shadow: 0 2px 8px rgba(10,10,10,0.03);
  }
  .topbar-inner{max-width:var(--maxw); width:100%; display:flex; align-items:center; gap:18px; justify-content:space-between}
  .brand {
    display:flex; align-items:center; gap:14px;
  }
  .logo-wrap{
    width:58px; height:58px; border-radius:10px; overflow:hidden;
    background:linear-gradient(135deg,var(--emerald),var(--deep));
    display:flex;align-items:center;justify-content:center;
    box-shadow:0 6px 20px rgba(15,40,30,0.12);
  }
  .logo-wrap img{width:42px;height:42px;object-fit:cover;border-radius:6px}
  .title {font-family:'Playfair Display', serif; font-weight:600; color:var(--deep); font-size:18px; letter-spacing:0.4px}
  .subtitle {font-size:12px;color:var(--emerald); opacity:0.95}

  nav.topnav{display:flex; gap:14px; align-items:center}
  nav.topnav a{
    text-decoration:none;color:var(--deep);padding:8px 12px;border-radius:8px;font-weight:600;
  }
  nav.topnav a.cta{
    background:linear-gradient(90deg,var(--emerald),#0a7a5f);color:white; box-shadow:0 6px 18px rgba(10,90,60,0.12)
  }
  nav.topnav a:hover{transform:translateY(-2px);transition:all .18s ease}

  /* More space between brand and header content */
  .header-spacer{height:22px}

  /* ---------- Hero / Welcome ---------- */
  .hero{
    max-width:var(--maxw); margin:26px auto; display:flex; gap:28px; align-items:center; padding:36px;
    border-radius:18px; background:linear-gradient(180deg, rgba(255,255,255,0.85), rgba(255,255,255,0.7));
    box-shadow: 0 20px 60px rgba(8,34,20,0.08);
  }
  .hero-left{flex:1; padding:12px 6px}
  .hero-right{flex:0 0 360px; display:flex;align-items:center;justify-content:center}
  .hero h1{font-family:'Playfair Display',serif;color:var(--deep);margin:0;font-size:34px;line-height:1.02}
  .hero p{margin:12px 0 18px; color: #3b4b46; font-size:16px; max-width:52ch}
  .kicker{display:inline-block;padding:6px 10px;border-radius:12px;background:linear-gradient(90deg,#f6fff6,#e7f7ef);color:var(--emerald);font-weight:700;margin-bottom:14px}
  .hero-ctas{display:flex; gap:12px; flex-wrap:wrap}
  .btn {
    display:inline-flex;align-items:center;gap:8px;padding:11px 16px;border-radius:10px;border:0;background:var(--emerald);color:white;font-weight:700;
    text-decoration:none;box-shadow:0 10px 30px rgba(15,90,60,0.08);
  }
  .btn.secondary{background:transparent;color:var(--deep);border:2px solid rgba(15,90,60,0.08);font-weight:600}
  .hero-image{width:320px;height:320px;border-radius:14px;overflow:hidden; box-shadow:0 10px 40px rgba(10,30,24,0.08)}
  .hero-image img{width:100%;height:100%;object-fit:cover}

  /* ---------- Main content layout ---------- */
  .container{max-width:var(--maxw);margin:26px auto;padding:0 18px}
  .section {margin:34px 0}
  .section h2{margin-bottom:14px}

  /* SINGLE SERVICE CARD (merged options inside) */
  .service-card{
    background:var(--card); padding:22px; border-radius:12px; box-shadow:0 8px 30px rgba(12,35,28,0.06);
    display:flex; gap:20px; align-items:center;
  }
  .service-left{flex:1}
  .service-right{flex:0 0 260px; text-align:center}
  .package{
    background:linear-gradient(180deg, #fff, #fbfffb); padding:12px; border-radius:10px; margin-bottom:10px;
    border-left:6px solid var(--emerald);
    box-shadow: 0 6px 20px rgba(10,70,50,0.04);
  }
  .package .price{font-weight:800;color:var(--deep); font-size:18px}

  /* breathing area */
  .breath {
    display:flex; gap:18px; align-items:center; justify-content:center; flex-direction:column;
    padding:30px; background: linear-gradient(90deg, rgba(15,95,70,0.04), rgba(13,75,57,0.02)); border-radius:12px;
  }
  .breath-circle{
    width:160px;height:160px;border-radius:50%; display:flex;align-items:center;justify-content:center;
    background: radial-gradient(circle at 30% 30%, rgba(255,255,255,0.14), rgba(255,255,255,0.02));
    box-shadow: 0 10px 40px rgba(12,40,30,0.07);
    position:relative; overflow:visible;
  }
  .breath-anim{
    width:110px;height:110px;border-radius:50%; background:linear-gradient(135deg,var(--emerald),var(--deep));
    animation: none; display:flex;align-items:center;justify-content:center;color:white;font-weight:700;
  }
  @keyframes expand {
    0%{transform:scale(.85); opacity:.85}
    50%{transform:scale(1.2); opacity:1}
    100%{transform:scale(.85); opacity:.85}
  }

  /* testimonials */
  .testimonials {display:grid; grid-template-columns:1fr; gap:12px}
  .testimonial {background:var(--card); padding:16px; border-radius:10px; box-shadow:0 6px 18px rgba(6,30,20,0.04);}

  /* Chatbot widget */
  .chatbot {
    position:fixed; bottom:24px; left:24px; width:360px; max-width:calc(100% - 48px); border-radius:12px; overflow:hidden;
    box-shadow:0 18px 50px rgba(8,20,16,0.18); transform:translateY(10px); transition:transform .2s ease;
  }
  .chatbot .header{background:linear-gradient(90deg,var(--emerald),var(--deep)); color:white; padding:10px 12px; display:flex;align-items:center;gap:10px}
  .chatbot .header .title{font-weight:700}
  .chatbot .messages{background:linear-gradient(180deg,#fbfff9,#f7fff7); padding:12px; max-height:320px; overflow:auto}
  .chatbot .msg {padding:8px 10px; margin:8px 0; border-radius:10px; max-width:78%}
  .chatbot .msg.user {background:#e6f2ff; margin-left:auto; text-align:right}
  .chatbot .msg.bot {background:#fff; box-shadow:0 6px 20px rgba(10,70,50,0.04)}
  .chatbot .composer{display:flex; gap:10px; padding:10px; background:linear-gradient(180deg,#fff,#fbfff9)}
  .chatbot input{flex:1;padding:10px;border-radius:8px;border:1px solid #e6efe9}

  /* floating quick actions */
  .float-actions{position:fixed; right:22px; bottom:22px; display:flex;flex-direction:column; gap:12px; z-index:140}
  .float-actions a{display:inline-flex;align-items:center;gap:8px;padding:10px 12px;border-radius:10px;color:white;text-decoration:none;font-weight:700}
  .wa {background:#25D366}
  .pay {background:var(--gold); color:#0b2a1f}

  /* responsive tweaks */
  @media (max-width:820px){
    .hero{flex-direction:column; padding:20px}
    .hero-right{display:none}
    .service-card{flex-direction:column}
    .service-right{width:100%}
    .chatbot{left:10px; right:10px; width:auto}
  }
  /* focus states */
  a:focus, button:focus, input:focus {outline:3px solid rgba(15,95,70,0.15); outline-offset:2px}
</style>
</head>
<body>

<!-- TOPBAR -->
<div class="topbar" role="banner">
  <div class="topbar-inner">
    <div class="brand" aria-label="CalmHub brand">
      <div class="logo-wrap" aria-hidden="true">
        <!-- small icon: replace with your logo.png if you upload -->
        <img src="https://i.imgur.com/liaQwEt.png" alt="CalmHub logo">
      </div>
      <div>
        <div class="title">CalmHub</div>
        <div class="subtitle">Luxury Healing & Listening</div>
      </div>
    </div>

    <nav class="topnav" role="navigation" aria-label="Main navigation">
      <a href="#home">Home</a>
      <a href="#services">Sessions</a>
      <a href="#breath">Breath</a>
      <a href="#contact">Contact</a>
      <a class="cta" href="https://wa.me/919598243010" target="_blank" rel="noopener">Book via WhatsApp</a>
    </nav>
  </div>
</div>

<!-- spacer between brand and header -->
<div class="header-spacer" aria-hidden="true"></div>

<!-- HERO -->
<section class="hero" id="home" role="region" aria-label="Welcome">
  <div class="hero-left">
    <span class="kicker">Calm Presence</span>
    <h1>You're welcome here — <span style="color:var(--gold)">be heard</span>, be <span style="color:var(--emerald)">gentle</span>.</h1>
    <p>CalmHub offers heart-led emotional listening, gentle guidance and practical grounding tools. Short sessions, clear support—designed to help you breathe again.</p>

    <div class="hero-ctas">
      <a class="btn" href="https://wa.me/919598243010" target="_blank">Book on WhatsApp</a>
      <a class="btn secondary" href="#services">View Sessions</a>
    </div>
  </div>

  <div class="hero-right">
    <div class="hero-image" aria-hidden="true">
      <img src="https://images.unsplash.com/photo-1501004318641-b39e6451bec6?auto=format&fit=crop&w=800&q=60" alt="Calm space image">
    </div>
  </div>
</section>

<div class="container">

  <!-- SINGLE MERGED SERVICE CARD -->
  <section id="services" class="section" role="region" aria-labelledby="services-heading">
    <h2 id="services-heading">Core Healing Session</h2>

    <div class="service-card" role="article">
      <div class="service-left">
        <p style="margin-top:0">A single, carefully held session structure with three ways to receive support — choose what you need today. Each session begins with listening, then grounding, then optional guidance if you ask.</p>

        <div class="package">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div>
              <div style="font-weight:700">Express — 20 min</div>
              <div style="opacity:.8;font-size:14px">Quick release & immediate calm</div>
            </div>
            <div class="price" style="font-weight:800;color:var(--emerald)">₹99</div>
          </div>
        </div>

        <div class="package">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div>
              <div style="font-weight:700">Deep — 40 min</div>
              <div style="opacity:.8;font-size:14px">Listening + grounding + simple practices</div>
            </div>
            <div class="price" style="font-weight:800;color:var(--emerald)">₹199</div>
          </div>
        </div>

        <div class="package">
          <div style="display:flex;justify-content:space-between;align-items:center">
            <div>
              <div style="font-weight:700">Transformative — 60 min</div>
              <div style="opacity:.8;font-size:14px">Deep healing, clarity & next steps</div>
            </div>
            <div class="price" style="font-weight:800;color:var(--emerald)">₹299</div>
          </div>
        </div>

        <p style="margin-top:12px; font-size:14px; color:#3b4b46">Payments via UPI: <strong>ritushasingh.5@okicici</strong>. After payment, send screenshot on WhatsApp to confirm booking.</p>
      </div>

      <div class="service-right" aria-hidden="true">
        <div style="background:linear-gradient(120deg,#fff,#fbfff9); padding:18px; border-radius:12px">
          <div style="font-weight:700; margin-bottom:8px">Ready to book?</div>
          <a class="btn" href="https://wa.me/919598243010" target="_blank" style="width:100%; display:inline-block; text-align:center">Book on WhatsApp</a>
          <a class="btn secondary" href="#contact" style="width:100%; display:inline-block; text-align:center; margin-top:10px">Contact & Pay</a>
          <div style="margin-top:12px; font-size:13px; color:#55625a">Cancellation: refund if cancelled 12+ hours before session.</div>
        </div>
      </div>
    </div>
  </section>

  <!-- BREATHING -->
  <section id="breath" class="section" role="region" aria-labelledby="breath-heading">
    <h2 id="breath-heading">Breathing Practice</h2>
    <div class="breath">
      <div class="breath-circle" aria-hidden="true">
        <div id="anim" class="breath-anim">Breathe</div>
      </div>
      <div style="text-align:center; max-width:700px">
        <p style="margin:0 0 8px">A simple 1-minute practice: <strong>Inhale 4s — Hold 2s — Exhale 6s</strong>. Click start and follow the circle.</p>
        <div style="display:flex;gap:10px;justify-content:center;margin-top:12px">
          <button class="btn" id="start-breath">Start</button>
          <button class="btn secondary" id="stop-breath">Stop</button>
        </div>
      </div>
    </div>
  </section>

  <!-- TESTIMONIALS -->
  <section id="social" class="section" role="region" aria-labelledby="social-heading">
    <h2 id="social-heading">Stories from People</h2>
    <div class="testimonials" id="testimonials">
      <div class="testimonial">"Sakshi's listening helped me breathe again after weeks of stress." — Priya</div>
      <div class="testimonial">"CalmHub is my safe place. Gentle and clear." — Manish</div>
      <div class="testimonial">"I feel clearer and more steady after one session." — Aastha</div>
    </div>
  </section>

  <!-- CONTACT -->
  <section id="contact" class="section" role="region" aria-labelledby="contact-heading">
    <h2 id="contact-heading">Contact & Booking</h2>
    <p style="max-width:760px;margin:auto">Book a session directly on WhatsApp or pay via UPI. For group circles and corporate calls, message for rates.</p>

    <div style="display:flex;gap:18px;flex-wrap:wrap;justify-content:center;margin-top:18px">
      <a class="btn wa-action" href="https://wa.me/919598243010" target="_blank">Chat on WhatsApp</a>
      <a class="btn pay-action" href="upi://pay?pa=ritushasingh.5@okicici&pn=Sakshi&tn=CalmHub+Session&am=199" title="UPI Pay (mobile)">Pay UPI</a>
      <a class="btn secondary" href="mailto:ritushasingh.5@gmail.com">Email</a>
    </div>
  </section>

</div> <!-- /.container -->

<footer role="contentinfo" style="margin-top:28px">
  <div style="max-width:var(--maxw);margin:0 auto;padding:18px;text-align:center;color:white;background:linear-gradient(90deg,var(--deep),var(--emerald));border-radius:8px 8px 0 0">
    <div style="font-weight:700">CalmHub — Healing Conversations</div>
    <div style="font-size:13px;opacity:0.9;margin-top:6px">© 2025 CalmHub • Not a substitute for professional mental health care</div>
  </div>
</footer>

<!-- Floating quick actions -->
<div class="float-actions" aria-hidden="true">
  <a class="wa" href="https://wa.me/919598243010" target="_blank">WhatsApp</a>
  <a class="pay" href="upi://pay?pa=ritushasingh.5@okicici&pn=Sakshi">Pay (UPI)</a>
</div>

<!-- Chatbot widget (client-side demo). Replace connectAI() with server AI integration -->
<div id="chatbot" class="chatbot" aria-hidden="false" style="display:none">
  <div class="header">
    <div style="width:36px;height:36px;border-radius:8px;background:rgba(255,255,255,0.2);display:flex;align-items:center;justify-content:center;color:white">AI</div>
    <div class="title">CalmBot — I'm here to listen</div>
    <div style="margin-left:auto"><button id="closebot" style="background:transparent;border:0;color:white;font-weight:700">✕</button></div>
  </div>
  <div class="messages" id="messages" role="log" aria-live="polite"></div>
  <div class="composer">
    <input id="userInput" placeholder="Type how you feel — or ask 'help' " aria-label="Chat input" />
    <button id="sendBtn" class="btn" style="padding:8px 12px">Send</button>
  </div>
</div>

<!-- Chat minimized button -->
<button id="openbot" aria-label="Open chat" style="position:fixed; left:24px; bottom:24px; z-index:150; background:linear-gradient(90deg,var(--gold),#e6c859); border:0; padding:12px 14px; border-radius:10px; box-shadow:0 8px 30px rgba(8,24,12,0.14); font-weight:700">Chat with CalmBot</button>

<script>
/* ---------- Animations & interactions ---------- */
/* Smooth scroll for same-page links */
document.querySelectorAll('a[href^="#"]').forEach(a=>{
  a.addEventListener('click', e=>{
    const target = document.querySelector(a.getAttribute('href'));
    if(target){ e.preventDefault(); target.scrollIntoView({behavior:'smooth', block:'start'}); }
  });
});

/* breathing animation controls */
const anim = document.getElementById('anim');
const startBtn = document.getElementById('start-breath');
const stopBtn = document.getElementById('stop-breath');
let breathTimer = null;

startBtn && startBtn.addEventListener('click', ()=>{
  anim.style.animation = 'expand 6s infinite';
  // audible guidance (optional)
  if(breathTimer) clearInterval(breathTimer);
  let step = 0;
  breathTimer = setInterval(()=>{
    step = (step+1)%12;
    // 0-3 inhale, 4-5 hold, 6-11 exhale in a 12-step cycle
    if(step<4) anim.textContent = 'Inhale';
    else if(step<6) anim.textContent = 'Hold';
    else anim.textContent = 'Exhale';
  }, 500);
});
stopBtn && stopBtn.addEventListener('click', ()=>{
  if(breathTimer) clearInterval(breathTimer);
  anim.style.animation = 'none';
  anim.textContent = 'Breathe';
});

/* Testimonials simple auto-rotate */
(function rotateTestimonials(){
  const t = document.querySelectorAll('.testimonial');
  if(!t || t.length<2) return;
  let i=0;
  setInterval(()=>{
    t.forEach((el,idx)=> el.style.display = (idx===i ? 'block' : 'none'));
    i = (i+1) % t.length;
  }, 4000);
})();

/* Chatbot UI (client-side demo) */
const chatbot = document.getElementById('chatbot');
const openbot = document.getElementById('openbot');
const closebot = document.getElementById('closebot');
const messages = document.getElementById('messages');
const userInput = document.getElementById('userInput');
const sendBtn = document.getElementById('sendBtn');

function addMessage(text, who='bot'){
  const el = document.createElement('div');
  el.className = 'msg ' + (who==='user' ? 'user' : 'bot');
  el.textContent = text;
  el.style.margin = '6px 0';
  el.style.padding = '10px';
  el.style.borderRadius = '10px';
  messages.appendChild(el);
  messages.scrollTop = messages.scrollHeight;
}

/* Simple rule-based empathic responses — replace with real AI server call */
function botReply(userText){
  userText = (userText||'').toLowerCase();
  if(userText.includes('sad')||userText.includes('depress')||userText.includes('alone')){
    return "I hear that you're feeling low. Would you like to tell me more about what's been heavy for you today?";
  }
  if(userText.includes('anx')||userText.includes('panic')||userText.includes('worried')){
    return "Breathing with me might help. Try slow inhales and exhales. Would you like a short breathing guide now?";
  }
  if(userText.includes('help')||userText.includes('book')){
    return "I can help you book a session or share calming exercises. To book quickly, click the WhatsApp button.";
  }
  if(userText.trim().length===0){
    return "I'm here — you can say anything, even a single word.";
  }
  // default reflective reply
  return "Thank you for sharing. That sounds important. Would you like to explore how that affects your daily life, or practice a small grounding now?";
}

/* Open / close handlers */
openbot.onclick = ()=>{ chatbot.style.display='block'; openbot.style.display='none'; addMessage("Hi — I'm CalmBot. How can I support you today?", 'bot'); }
closebot && (closebot.onclick = ()=>{ chatbot.style.display='none'; openbot.style.display='inline-block'; messages.innerHTML=''; });

sendBtn && sendBtn.addEventListener('click', ()=>{
  const txt = userInput.value.trim();
  if(!txt) return;
  addMessage(txt,'user');
  userInput.value='';
  // simulate thinking
  addMessage('…','bot');
  setTimeout(()=>{
    // remove last '...'
    const nodes = messages.querySelectorAll('.msg.bot');
    if(nodes.length) nodes[nodes.length-1].remove();
    const reply = botReply(txt);
    addMessage(reply,'bot');
  }, 700);
});

/* keyboard send */
userInput && userInput.addEventListener('keydown', (e)=>{
  if(e.key==='Enter'){ e.preventDefault(); sendBtn.click();}
});

/* Accessibility: focus first interactive */
window.addEventListener('load', ()=> {
  const first = document.querySelector('a.btn');
  if(first) first.setAttribute('tabindex','0');
});

/* Intersection animations */
const io = new IntersectionObserver((items)=>{
  items.forEach(item=>{
    if(item.isIntersecting){
      item.target.style.transition='transform 0.8s cubic-bezier(.2,.9,.2,1), opacity .7s';
      item.target.style.transform='translateY(0)';
      item.target.style.opacity='1';
      io.unobserve(item.target);
    }
  });
},{threshold:0.12});
document.querySelectorAll('.service-box, .package, .testimonial, .hero-left, .hero-right').forEach(el=>{
  el.style.transform='translateY(12px)'; el.style.opacity='0';
  io.observe(el);
});

/* SEO-friendly: set canonical (change to your real site) */
const link = document.createElement('link'); link.rel='canonical'; link.href='https://yourusername.github.io/CalmHub'; document.head.appendChild(link);

/* Notes on adding real AI:
   - For security, do NOT place API keys in client JS.
   - Create a small server endpoint (Node/Python) that accepts user input and calls the AI service.
   - Then replace botReply() with fetch('/api/ai', {method:'POST', body: JSON.stringify({text:txt})}) and handle response.
*/
</script>

</body>
</html>
