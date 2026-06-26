<html lang="en">
<head>
<meta charset="UTF-8"/>
<meta name="viewport" content="width=device-width, initial-scale=1.0"/>
<title>SIN HENG Machinery & Engineering Works</title>
<style>
  *{margin:0;padding:0;box-sizing:border-box;}
  body{font-family:'Segoe UI',sans-serif;color:#222;background:#f9f9f9;}
  a{text-decoration:none;}

  /* NAV */
  nav{background:#fff;padding:16px 40px;display:flex;align-items:center;justify-content:space-between;box-shadow:0 2px 8px rgba(0,0,0,.08);position:sticky;top:0;z-index:100;}
  .logo{display:flex;align-items:center;gap:12px;}
  .logo-icon{width:42px;height:42px;background:#1a3c5e;border-radius:8px;display:flex;align-items:center;justify-content:center;}
  .logo-icon svg{width:24px;height:24px;fill:#fff;}
  .logo-text h1{font-size:15px;font-weight:700;color:#1a3c5e;line-height:1.2;}
  .logo-text p{font-size:11px;color:#666;}
  .nav-wa{background:#25D366;color:#fff;padding:9px 18px;border-radius:6px;font-size:13px;font-weight:600;display:flex;align-items:center;gap:6px;transition:.2s;}
  .nav-wa:hover{background:#1ebe5d;}
  .nav-wa svg{width:16px;height:16px;fill:#fff;}

  /* HERO */
  .hero{background:linear-gradient(135deg,#1a3c5e 0%,#2d6a9f 100%);color:#fff;padding:80px 40px;text-align:center;}
  .hero h2{font-size:38px;font-weight:700;margin-bottom:14px;line-height:1.2;}
  .hero p{font-size:16px;opacity:.88;max-width:520px;margin:0 auto 32px;}
  .hero-btns{display:flex;gap:14px;justify-content:center;flex-wrap:wrap;}
  .btn-primary{background:#25D366;color:#fff;padding:13px 28px;border-radius:7px;font-size:15px;font-weight:600;display:flex;align-items:center;gap:8px;transition:.2s;}
  .btn-primary:hover{background:#1ebe5d;transform:translateY(-1px);}
  .btn-primary svg{width:18px;height:18px;fill:#fff;}
  .btn-outline{background:transparent;color:#fff;border:2px solid rgba(255,255,255,.6);padding:13px 28px;border-radius:7px;font-size:15px;font-weight:600;transition:.2s;}
  .btn-outline:hover{border-color:#fff;background:rgba(255,255,255,.1);}

  /* ABOUT */
  .about{background:#fff;padding:60px 40px;text-align:center;}
  .section-tag{display:inline-block;background:#e8f0f8;color:#1a3c5e;font-size:12px;font-weight:700;letter-spacing:1px;padding:5px 14px;border-radius:20px;margin-bottom:14px;text-transform:uppercase;}
  .about h3{font-size:26px;font-weight:700;color:#1a3c5e;margin-bottom:14px;}
  .about p{font-size:15px;color:#555;max-width:600px;margin:0 auto 30px;}
  .stats{display:flex;justify-content:center;gap:40px;flex-wrap:wrap;}
  .stat{text-align:center;}
  .stat .num{font-size:32px;font-weight:700;color:#1a3c5e;}
  .stat .lbl{font-size:12px;color:#888;margin-top:2px;}

  /* PRODUCTS */
  .products{padding:60px 40px;background:#f4f7fb;}
  .products h3{text-align:center;font-size:26px;font-weight:700;color:#1a3c5e;margin-bottom:6px;}
  .products .sub{text-align:center;color:#666;font-size:15px;margin-bottom:36px;}
  .grid{display:grid;grid-template-columns:repeat(auto-fill,minmax(260px,1fr));gap:24px;max-width:1100px;margin:0 auto;}
  .card{background:#fff;border-radius:12px;overflow:hidden;box-shadow:0 2px 12px rgba(0,0,0,.07);transition:.25s;}
  .card:hover{transform:translateY(-4px);box-shadow:0 8px 24px rgba(0,0,0,.12);}
  .card-img{width:100%;height:180px;object-fit:cover;background:#e8f0f8;display:flex;align-items:center;justify-content:center;}
  .card-img svg{width:64px;height:64px;fill:#2d6a9f;opacity:.4;}
  .card-body{padding:20px;}
  .card-body h4{font-size:15px;font-weight:700;color:#1a3c5e;margin-bottom:6px;}
  .card-body p{font-size:13px;color:#666;margin-bottom:16px;line-height:1.5;}
  .card-wa{display:flex;align-items:center;gap:7px;background:#25D366;color:#fff;padding:9px 16px;border-radius:6px;font-size:13px;font-weight:600;transition:.2s;width:fit-content;}
  .card-wa:hover{background:#1ebe5d;}
  .card-wa svg{width:15px;height:15px;fill:#fff;}

  /* CONTACT */
  .contact{background:#1a3c5e;color:#fff;padding:60px 40px;text-align:center;}
  .contact h3{font-size:26px;font-weight:700;margin-bottom:10px;}
  .contact p{opacity:.8;font-size:15px;margin-bottom:28px;}
  .contact-info{display:flex;justify-content:center;gap:36px;flex-wrap:wrap;margin-bottom:32px;}
  .info-item{display:flex;align-items:center;gap:10px;font-size:14px;}
  .info-item svg{width:18px;height:18px;fill:#25D366;}

  /* FOOTER */
  footer{background:#0f2540;color:#aaa;text-align:center;padding:20px;font-size:13px;}
  footer span{color:#fff;font-weight:600;}

  @media(max-width:600px){
    .hero h2{font-size:26px;}
    .hero,nav,.about,.products,.contact{padding-left:20px;padding-right:20px;}
    .stats{gap:24px;}
  }
</style>
</head>
<body>

<!-- NAV -->
<nav>
  <div class="logo">
    <img src="sh logo.png" alt="SIN HENG Logo" style="height:50px; width:auto;">
    <div class="logo-text">
      <h1>SIN HENG</h1>
      <p>Machinery & Engineering Works</p>
    </div>
  </div>
  <a class="nav-wa" href="https://wa.me/+60127093316" target="_blank">
    <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.554 4.116 1.526 5.845L.057 23.571a.5.5 0 0 0 .604.637l5.94-1.56A11.94 11.94 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.94 9.94 0 0 1-5.072-1.38l-.363-.216-3.767.988.999-3.657-.236-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
    WhatsApp Us
  </a>
</nav>

<!-- HERO -->
<section class="hero">
  <h2>Quality Food Machinery<br>You Can Trust</h2>
  <p>Supplying reliable food processing and machinery solutions for businesses across Malaysia.</p>
  <div class="hero-btns">
    <a class="btn-primary" href="https://wa.me/+60127093316?text=Hello%2C%20I%20am%20interested%20in%20your%20food%20machinery.%20Can%20you%20provide%20more%20details%3F" target="_blank">
      <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.554 4.116 1.526 5.845L.057 23.571a.5.5 0 0 0 .604.637l5.94-1.56A11.94 11.94 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.94 9.94 0 0 1-5.072-1.38l-.363-.216-3.767.988.999-3.657-.236-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
      Enquire on WhatsApp
    </a>
    <a class="btn-outline" href="#products">View Our Products</a>
  </div>
</section>

<!-- ABOUT -->
<section class="about">
  <div class="section-tag">About Us</div>
  <h3>SIN HENG Machinery & Engineering Works</h3>
  <p>We specialise in providing high-quality food processing machinery and engineering solutions. With years of experience, we help businesses find the right equipment to boost productivity and efficiency.</p>
  <div class="stats">
    <div class="stat"><div class="num">10+</div><div class="lbl">Years Experience</div></div>
    <div class="stat"><div class="num">200+</div><div class="lbl">Happy Customers</div></div>
    <div class="stat"><div class="num">5</div><div class="lbl">Product Categories</div></div>
  </div>
</section>

<!-- PRODUCTS -->
<section class="products" id="products">
  <div class="section-tag">Our Products</div>
  <h3>Our Product Range</h3>
  <p class="sub">Browse our selection of food machinery — click to enquire directly via WhatsApp.</p>
  <div class="grid" id="product-grid"></div>
</section>

<!-- CONTACT -->
<section class="contact">
  <h3>Get In Touch</h3>
  <p>Have a question or need a quote? Reach us directly on WhatsApp — we respond fast!</p>
  <div class="contact-info">
    <div class="info-item">
      <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.554 4.116 1.526 5.845L.057 23.571a.5.5 0 0 0 .604.637l5.94-1.56A11.94 11.94 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.94 9.94 0 0 1-5.072-1.38l-.363-.216-3.767.988.999-3.657-.236-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
      +60 11-1899 3616
    </div>
    <div class="info-item">
      <svg viewBox="0 0 24 24"><path d="M12 2C8.13 2 5 5.13 5 9c0 5.25 7 13 7 13s7-7.75 7-13c0-3.87-3.13-7-7-7zm0 9.5c-1.38 0-2.5-1.12-2.5-2.5s1.12-2.5 2.5-2.5 2.5 1.12 2.5 2.5-1.12 2.5-2.5 2.5z"/></svg>
      Johor Bahru, Malaysia
    </div>
  </div>
  <a class="btn-primary" href="https://wa.me/+60127093316?text=Hello%2C%20I%20would%20like%20to%20enquire%20about%20your%20products." target="_blank" style="display:inline-flex;margin:0 auto;">
    <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.554 4.116 1.526 5.845L.057 23.571a.5.5 0 0 0 .604.637l5.94-1.56A11.94 11.94 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.94 9.94 0 0 1-5.072-1.38l-.363-.216-3.767.988.999-3.657-.236-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
    Chat With Us Now
  </a>
</section>

<footer>
  &copy; 2024 <span>SIN HENG Machinery & Engineering Works</span>. All rights reserved. | Johor Bahru, Malaysia
</footer>

<script>
const WA = "++60127093316";
const products = [
  {
    name: "Meat Mincer Machine",
    desc: "Heavy-duty electric meat mincer suitable for commercial food processing. Durable stainless steel blades for hygiene and longevity.",
    icon: "M3 3h18v4H3zm0 5h18v4H3zm0 5h18v4H3z"
  },
  {
    name: "Dough Mixer Machine",
    desc: "Commercial spiral dough mixer ideal for bakeries and food manufacturers. Consistent mixing results with variable speed control.",
    icon: "M12 2a10 10 0 1 0 0 20A10 10 0 0 0 12 2zm0 18a8 8 0 1 1 0-16 8 8 0 0 1 0 16zm-1-13h2v6h-2zm0 8h2v2h-2z"
  },
  {
    name: "Food Slicing Machine",
    desc: "Precision food slicer for meats, vegetables, and cheese. Adjustable thickness settings for consistent cuts every time.",
    icon: "M7 2v11h3v9l7-12h-4l4-8z"
  },
  {
    name: "Noodle Making Machine",
    desc: "Automated noodle maker for producing fresh noodles efficiently. Adjustable noodle thickness and high output capacity.",
    icon: "M12 3C7 3 3 7 3 12s4 9 9 9 9-4 9-9-4-9-9-9zm0 16c-3.86 0-7-3.14-7-7s3.14-7 7-7 7 3.14 7 7-3.14 7-7 7z"
  },
  {
    name: "Food Sealing Machine",
    desc: "Reliable heat sealing machine for packaging food products. Ensures freshness and extends shelf life for packaged goods.",
    icon: "M20 6h-2.18c.07-.44.18-.88.18-1a3 3 0 0 0-6 0c0 .12.11.56.18 1H6a2 2 0 0 0-2 2v12a2 2 0 0 0 2 2h14a2 2 0 0 0 2-2V8a2 2 0 0 0-2-2z"
  }
];

const grid = document.getElementById("product-grid");
products.forEach(p => {
  const msg = encodeURIComponent(`Hello, I am interested in your *${p.name}*. Can you provide more details and pricing?`);
  grid.innerHTML += `
    <div class="card">
      <div class="card-img">
        <svg viewBox="0 0 24 24"><path d="${p.icon}"/></svg>
      </div>
      <div class="card-body">
        <h4>${p.name}</h4>
        <p>${p.desc}</p>
        <a class="card-wa" href="https://wa.me/${WA}?text=${msg}" target="_blank">
          <svg viewBox="0 0 24 24"><path d="M17.472 14.382c-.297-.149-1.758-.867-2.03-.967-.273-.099-.471-.148-.67.15-.197.297-.767.966-.94 1.164-.173.199-.347.223-.644.075-.297-.15-1.255-.463-2.39-1.475-.883-.788-1.48-1.761-1.653-2.059-.173-.297-.018-.458.13-.606.134-.133.298-.347.446-.52.149-.174.198-.298.298-.497.099-.198.05-.371-.025-.52-.075-.149-.669-1.612-.916-2.207-.242-.579-.487-.5-.669-.51-.173-.008-.371-.01-.57-.01-.198 0-.52.074-.792.372-.272.297-1.04 1.016-1.04 2.479 0 1.462 1.065 2.875 1.213 3.074.149.198 2.096 3.2 5.077 4.487.709.306 1.262.489 1.694.625.712.227 1.36.195 1.871.118.571-.085 1.758-.719 2.006-1.413.248-.694.248-1.289.173-1.413-.074-.124-.272-.198-.57-.347z"/><path d="M12 0C5.373 0 0 5.373 0 12c0 2.123.554 4.116 1.526 5.845L.057 23.571a.5.5 0 0 0 .604.637l5.94-1.56A11.94 11.94 0 0 0 12 24c6.627 0 12-5.373 12-12S18.627 0 12 0zm0 22a9.94 9.94 0 0 1-5.072-1.38l-.363-.216-3.767.988.999-3.657-.236-.376A9.944 9.944 0 0 1 2 12C2 6.477 6.477 2 12 2s10 4.477 10 10-4.477 10-10 10z"/></svg>
          Enquire on WhatsApp
        </a>
      </div>
    </div>`;
});
</script>
</body>
</html>
