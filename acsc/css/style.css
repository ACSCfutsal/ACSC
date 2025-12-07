/* style.css - Moderne, simple et commenté */
/* Variables couleurs / typographie */
:root{
  --brand:#163059;   /* bleu foncé */
  --accent:#4fc3f7;  /* bleu clair */
  --bg:#f4f6f8;
  --muted:#6b7a90;
  --radius:10px;
  --container:1100px;
  --gap:20px;
}

*{box-sizing:border-box}
html,body{height:100%}
body{
  margin:0;
  font-family: "Inter", system-ui, -apple-system, "Segoe UI", Roboto, "Helvetica Neue", Arial;
  color:var(--brand);
  background:var(--bg);
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  line-height:1.5;
}

.container{max-width:var(--container);margin:0 auto;padding:0 20px}

/* Header */
.site-header{background:var(--brand);color:#fff;position:sticky;top:0;z-index:50;box-shadow:0 2px 6px rgba(0,0,0,0.08)}
.header-inner{display:flex;align-items:center;justify-content:space-between;padding:12px 0}
.brand{display:flex;align-items:center;gap:10px;color:#fff;font-weight:700}
.logo{height:36px;width:auto}
.nav-list{list-style:none;display:flex;gap:18px;margin:0;padding:0}
.nav-list a{color:#fff;text-decoration:none;padding:8px 6px;border-radius:6px;transition:background .18s}
.nav-list a:hover,.nav-list a.active{background:rgba(255,255,255,0.06)}
.nav-toggle{display:none;background:transparent;border:none;color:#fff;font-size:20px}

/* Hero */
.hero{padding:60px 0;background:linear-gradient(90deg,var(--accent),#cfeffd);border-bottom:1px solid rgba(0,0,0,0.04)}
.hero-grid{display:grid;grid-template-columns:1fr 460px;gap:30px;align-items:center}
.hero-text h1{font-size:2.2rem;margin:0 0 10px}
.hero-text p{color:var(--muted);margin-bottom:18px}
.hero-media img{width:100%;border-radius:var(--radius);box-shadow:0 8px 30px rgba(22,48,89,0.12)}

/* Buttons */
.btn{display:inline-block;background:var(--brand);color:#fff;padding:10px 16px;border-radius:8px;text-decoration:none}
.btn-outline{display:inline-block;border:2px solid rgba(22,48,89,0.12);padding:8px 14px;border-radius:8px;color:var(--brand);text-decoration:none;margin-left:10px}

/* Sections & Cards */
.section{padding:44px 0}
.alt{background:#fff;border-top:1px solid rgba(0,0,0,0.03)}
.cards{display:grid;grid-template-columns:repeat(auto-fit,minmax(260px,1fr));gap:18px}
.card{background:#fff;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(22,48,89,0.06)}
.feature-row{display:flex;gap:18px;flex-wrap:wrap}
.feature{flex:1;background:#fff;padding:18px;border-radius:12px;box-shadow:0 6px 18px rgba(22,48,89,0.04)}

/* Table planning */
.table-wrap{overflow:auto}
.planning-table{width:100%;border-collapse:collapse;background:#fff;border-radius:10px;overflow:hidden}
.planning-table th, .planning-table td{padding:12px;border-bottom:1px solid #eef3f8;text-align:center}
.planning-table th{background:var(--accent);color:#08324a;font-weight:600}

/* Gallery */
.gallery{display:grid;grid-template-columns:repeat(auto-fit,minmax(180px,1fr));gap:12px}
.gallery img{width:100%;height:140px;object-fit:cover;border-radius:8px;cursor:pointer;transition:transform .18s}
.gallery img:hover{transform:scale(1.03)}

/* Modal lightbox (hidden by default) */
.lightbox{position:fixed;inset:0;display:none;align-items:center;justify-content:center;background:rgba(0,0,0,0.7)}
.lightbox.active{display:flex}
.lightbox .lb-img{max-width:90%;max-height:80%;border-radius:8px}
.lb-close{position:absolute;top:26px;right:26px;background:#fff;border-radius:6px;padding:8px;border:none}

/* Form */
.form-card{background:#fff;padding:18px;border-radius:12px;max-width:680px;margin:0 auto;box-shadow:0 8px 30px rgba(22,48,89,0.06)}
.form-card input,.form-card textarea{width:100%;padding:10px;margin-top:6px;border:1px solid #e0e6ee;border-radius:8px}

/* Footer */
.site-footer{background:var(--brand);color:#fff;padding:18px 0;margin-top:30px}
.footer-inner{display:flex;justify-content:space-between;align-items:center;gap:10px;flex-wrap:wrap}

/* Responsive */
@media(max-width:980px){
  .hero-grid{grid-template-columns:1fr}
  .hero-media{order:-1}
}
@media(max-width:768px){
  .nav-list{display:none;position:absolute;right:16px;top:62px;background:var(--brand);padding:12px;border-radius:8px;flex-direction:column;width:200px}
  .nav-toggle{display:block}
  .hero{padding:40px 0}
  .hero-text h1{font-size:1.6rem}
  .gallery img{height:120px}
}
