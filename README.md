index.html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Major-Ready Mix | Afro, Hip-Hop & R&B</title>
  <style>
    body { margin:0; font-family: 'Arial', sans-serif; line-height:1.6; color:#222; }
    header { background:#111; color:#fff; text-align:center; padding:100px 20px; }
    header h1 { font-size:2.5rem; margin-bottom:10px; }
    header p { font-size:1.2rem; margin-bottom:20px; }
    header a { background:#ff0055; color:#fff; padding:15px 30px; text-decoration:none; font-weight:bold; border-radius:5px; }
    section { padding:60px 20px; max-width:1000px; margin:0 auto; }
    .pricing { display:flex; flex-wrap:wrap; gap:20px; justify-content:center; }
    .card { border:1px solid #ddd; padding:20px; border-radius:10px; width:250px; text-align:center; }
    .card h3 { margin-bottom:10px; }
    .card p { margin-bottom:10px; }
    .testimonials { display:flex; flex-direction:column; gap:20px; }
    .testimonial { background:#f9f9f9; padding:20px; border-radius:10px; }
    form { display:flex; flex-direction:column; gap:15px; max-width:500px; margin:0 auto; }
    input, textarea { padding:10px; border-radius:5px; border:1px solid #ccc; width:100%; }
    button { background:#ff0055; color:#fff; padding:15px; font-weight:bold; border:none; border-radius:5px; cursor:pointer; }
    footer { background:#111; color:#fff; text-align:center; padding:20px; }
    @media (max-width:600px){ .pricing{flex-direction:column;} }
  </style>
</head>
<body>

  <header>
    <h1>Turn Your Track Into a Major-Ready Record</h1>
    <p>Professional Mixing & Mastering for Afro, Hip-Hop, and R&B Artists</p>
    <a href="#upload">Upload Your Track</a>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I specialize in giving independent Afro, Hip-Hop, and R&B artists a polished, radio-ready sound. With fast turnaround, premium quality, and personalized attention, your tracks will hit streaming platforms like a major release.</p>
  </section>

  <section id="samples">
    <h2>Before & After Samples</h2>
    <p>Audio samples will be added here soon. For now, this section is a placeholder.</p>
  </section>

  <section id="pricing">
    <h2>Pricing</h2>
    <div class="pricing">
      <div class="card">
        <h3>Pro Mix</h3>
        <p>$900–$1,200</p>
        <p>7–10 day delivery</p>
        <p>2 revisions included</p>
      </div>
      <div class="card">
        <h3>Premium Mix</h3>
        <p>$1,500</p>
        <p>5-day delivery</p>
        <p>Unlimited minor revisions</p>
        <p>Radio edit included</p>
      </div>
    </div>
  </section>

  <section id="testimonials">
    <h2>Testimonials</h2>
    <div class="testimonials">
      <div class="testimonial">
        <p>“The mix completely transformed my track — it sounds radio-ready!” – Artist A</p>
      </div>
      <div class="testimonial">
        <p>“Fast, professional, and the sound is insane. Highly recommend.” – Artist B</p>
      </div>
    </div>
  </section>

  <section id="upload">
    <h2>Upload Your Track / Contact</h2>
    <form action="#" method="POST">
      <input type="text" name="name" placeholder="Your Name" required>
      <input type="email" name="email" placeholder="Your Email" required>
      <textarea name="notes" placeholder="Any notes for the mix"></textarea>
      <button type="submit">Send Your Track</button>
    </form>
  </section>

  <footer>
    <p>Follow me on <a href="#" style="color:#ff0055;">Instagram</a>, <a href="#" style="color:#ff0055;">TikTok</a>, <a href="#" style="color:#ff0055;">YouTube</a></p>
    <p>© 2026 Major-Ready Mix</p>
  </footer>

</body>
Add initial website code
