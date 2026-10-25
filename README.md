<!DOCTYPE html>
<html>
<head>
  <base target="_top">
  <meta charset="utf-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <meta name="description" content="Register for the Digital Institute webinar on Basic Computer, Graphic Designing and AI Tools for only ₹30.">
  <script src="https://checkout.razorpay.com/v1/checkout.js"></script>
  <style>
    :root{--navy:#101b3c;--blue:#315be8;--gold:#ffc857;--ink:#19233a;--muted:#667085;--bg:#f4f7ff;--line:#e2e8f0}
    *{box-sizing:border-box}body{margin:0;font-family:Inter,system-ui,-apple-system,Segoe UI,Roboto,Arial,sans-serif;background:var(--bg);color:var(--ink)}
    .hero{background:radial-gradient(circle at 85% 10%,#425fcd 0,transparent 28%),linear-gradient(135deg,#0b1532,#172c65);color:white;padding:34px 18px 72px}
    .wrap{max-width:980px;margin:auto}.brand{font-size:14px;font-weight:800;letter-spacing:.12em;text-transform:uppercase;color:var(--gold)}
    h1{font-size:clamp(32px,6vw,54px);line-height:1.06;margin:16px 0}.hero p{font-size:17px;line-height:1.6;max-width:650px;color:#e2e9ff}
    .pill{display:inline-block;background:#ffffff18;border:1px solid #ffffff33;border-radius:999px;padding:8px 13px;margin:7px 6px 0 0;font-size:13px}
    .price{display:inline-flex;align-items:center;gap:10px;background:var(--gold);color:#15213d;font-weight:900;border-radius:14px;padding:12px 16px;margin-top:16px}
    main{margin:-42px auto 50px;padding:0 16px}.layout{display:grid;grid-template-columns:1fr .95fr;gap:22px;align-items:start}
    .card{background:#fff;border:1px solid var(--line);border-radius:22px;padding:25px;box-shadow:0 16px 45px #12265b0d}
    h2{margin:0 0 14px;font-size:23px}.topics{display:grid;gap:12px;margin:18px 0}
    .topic{display:flex;gap:12px;padding:14px;background:#f8faff;border:1px solid #e9eefb;border-radius:14px}
    .emoji{font-size:24px}.topic strong{display:block;margin-bottom:3px}.topic small{color:var(--muted);line-height:1.45}
    label{display:block;font-weight:700;font-size:13px;margin:15px 0 7px}input{width:100%;padding:13px 14px;border:1px solid #d4dbea;border-radius:11px;font-size:16px;outline:none}
    input:focus{border-color:var(--blue);box-shadow:0 0 0 3px #315be81c}.consent{display:flex;gap:9px;align-items:flex-start;color:#596579;font-size:12px;line-height:1.45;margin:16px 0}.consent input{width:auto;margin-top:2px}
    button{width:100%;border:0;border-radius:12px;background:var(--blue);color:#fff;font-size:16px;font-weight:800;padding:15px;cursor:pointer}
    button:disabled{opacity:.6;cursor:wait}.note{font-size:12px;color:var(--muted);line-height:1.5;margin-top:12px}.status{display:none;margin-top:15px;padding:13px;border-radius:12px;line-height:1.5;font-size:14px}.status.show{display:block}.status.ok{background:#ecfdf3;color:#067647}.status.err{background:#fff1f0;color:#b42318}
    footer{text-align:center;color:#778198;font-size:12px;padding:0 16px 30px}.small-title{color:var(--blue);font-size:12px;font-weight:900;letter-spacing:.1em;text-transform:uppercase}
    @media(max-width:720px){.layout{grid-template-columns:1fr}.hero{padding-bottom:65px}.card{padding:21px}main{margin-top:-38px}}
  </style>
</head>
<body>
  <header class="hero">
    <div class="wrap">
      <div class="brand" id="brand">Digital Institute</div>
      <h1>Build Your Digital Skills.<br><span style="color:#ffc857">Start with AI.</span></h1>
      <p>Join our beginner-friendly live webinar and discover practical digital skills for study, creativity and future opportunities.</p>
      <span class="pill">💻 Basic Computer</span><span class="pill">🎨 Graphic Designing</span><span class="pill">🤖 AI Tools</span>
      <div class="price"><span style="font-size:25px">₹30</span><span>One-time webinar fee</span></div>
    </div>
  </header>
  <main class="wrap">
    <div class="layout">
      <section class="card">
        <div class="small-title">What you'll explore</div>
        <h2>Learn useful skills, step by step</h2>
        <div class="topics">
          <div class="topic"><div class="emoji">💻</div><div><strong>Basic Computer Course</strong><small>Computer fundamentals, files, typing and everyday digital skills.</small></div></div>
          <div class="topic"><div class="emoji">🎨</div><div><strong>Graphic Designing</strong><small>Design basics, creative layouts and tools for social media graphics.</small></div></div>
          <div class="topic"><div class="emoji">🤖</div><div><strong>AI Tools & Practical Uses</strong><small>Explore AI tools for learning, content ideas and productivity.</small></div></div>
        </div>
        <p class="note">This is a webinar registration page. Date, time and joining instructions will be shared after registration confirmation.</p>
      </section>
      <section class="card">
        <div class="small-title">Reserve your seat</div>
        <h2>Register now</h2>
        <form id="regForm">
          <label for="name">Full name *</label>
          <input id="name" name="name" placeholder="Enter your full name" required maxlength="100" autocomplete="name">
          <label for="phone">WhatsApp mobile number *</label>
          <input id="phone" name="phone" type="tel" inputmode="numeric" placeholder="10-digit Indian mobile number" required pattern="[6-9][0-9]{9}" maxlength="10" autocomplete="tel">
          <label for="email">Email (optional)</label>
          <input id="email" name="email" type="email" placeholder="you@example.com" maxlength="120" autocomplete="email">
          <div class="consent"><input id="consent" type="checkbox" required><span>I agree to be contacted about this webinar and understand that my registration details will be stored to manage my seat and payment.</span></div>
          <button id="payBtn" type="submit">Register & Pay ₹30</button>
          <div id="status" class="status" role="status" aria-live="polite"></div>
          <p class="note">Secure checkout is handled by Razorpay when configured. Do not close the page until payment verification finishes. A WhatsApp welcome message can be sent only after WhatsApp Cloud API and an approved message template are configured.</p>
        </form>
      </section>
    </div>
  </main>
  <footer>© <span id="year"></span> Digital Institute · Learn Today. Grow Tomorrow.</footer>
<script>
  const form = document.getElementById('regForm');
  const btn = document.getElementById('payBtn');
  const statusBox = document.getElementById('status');
  document.getElementById('year').textContent = new Date().getFullYear();

  function showStatus(message, type) {
    statusBox.className = 'status show ' + type;
    statusBox.textContent = message;
  }
  function setBusy(busy) {
    btn.disabled = busy;
    btn.textContent = busy ? 'Please wait…' : 'Register & Pay ₹30';
  }

  google.script.run.withSuccessHandler(cfg => {
    if (cfg && cfg.instituteName) document.getElementById('brand').textContent = cfg.instituteName;
    if (!cfg || !cfg.razorpayKeyId) {
      showStatus('Website preview is ready, but payment is not active yet. The owner must add Razorpay API keys in Apps Script settings.', 'err');
      btn.disabled = true;
    }
  }).withFailureHandler(() => {
    showStatus('Configuration could not be loaded. Please try again later.', 'err');
    btn.disabled = true;
  }).getConfig();

  form.addEventListener('submit', function(e) {
    e.preventDefault();
    if (!form.reportValidity()) return;
    if (!document.getElementById('consent').checked) return;
    const student = {
      name: document.getElementById('name').value.trim(),
      phone: document.getElementById('phone').value.trim(),
      email: document.getElementById('email').value.trim()
    };
    setBusy(true);
    showStatus('Creating your registration and secure payment order…', 'ok');
    google.script.run.withSuccessHandler(startCheckout).withFailureHandler(err => {
      setBusy(false);
      showStatus((err && err.message) || 'Could not start registration. Please try again.', 'err');
    }).registerStudent(student);
  });

  function startCheckout(order) {
    if (!order || !order.ok || !order.keyId) {
      setBusy(false);
      showStatus('Payment setup is incomplete. Please contact the institute.', 'err');
      return;
    }
    const options = {
      key: order.keyId,
      amount: order.amount,
      currency: order.currency,
      name: 'Digital Institute',
      description: 'Digital Skills Webinar Registration',
      order_id: order.orderId,
      prefill: {name: order.name, email: order.email, contact: order.phone},
      notes: {registration_id: order.registrationId},
      theme: {color: '#315be8'},
      handler: function(response) {
        showStatus('Payment received by checkout. Verifying payment securely…', 'ok');
        google.script.run.withSuccessHandler(result => {
          setBusy(false);
          if (result && result.ok) {
            showStatus('Payment confirmed! Your Registration ID is ' + result.registrationId + '. WhatsApp welcome status: ' + result.whatsappStatus + '. Please save your Registration ID.', 'ok');
            form.reset();
          } else {
            showStatus('We could not confirm the payment yet. Please contact the institute with your payment ID: ' + response.razorpay_payment_id, 'err');
          }
        }).withFailureHandler(err => {
          setBusy(false);
          showStatus('Payment was submitted but verification needs attention. Keep your payment ID ' + response.razorpay_payment_id + ' and contact the institute. ' + ((err && err.message) || ''), 'err');
        }).verifyPaymentAndWelcome({
          registrationId: order.registrationId,
          razorpay_order_id: response.razorpay_order_id,
          razorpay_payment_id: response.razorpay_payment_id,
          razorpay_signature: response.razorpay_signature
        });
      },
      modal: {ondismiss: function() {
        setBusy(false);
        showStatus('Checkout closed. Your registration may remain pending until you complete payment.', 'err');
      }}
    };
    const checkout = new Razorpay(options);
    checkout.on('payment.failed', function(response) {
      setBusy(false);
      showStatus('Payment failed or was cancelled. Please try again. ' + ((response.error && response.error.description) || ''), 'err');
    });
    checkout.open();
  }
</script>
</body>
</html>
