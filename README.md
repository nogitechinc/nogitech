<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>About Us | Nogitech</title>
  <style>
    @import url('https://fonts.googleapis.com/css2?family=Orbitron:wght@500&family=Segoe+UI&display=swap');

    /* Background Animation: subtle moving gradient overlay */
    body {
      margin: 0;
      padding: 0;
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      color: #e0f7f7;
      background: url('https://images.unsplash.com/photo-1518770660439-4636190af475?auto=format&fit=crop&w=1950&q=80') no-repeat center center fixed;
      background-size: cover;
      position: relative;
      overflow-x: hidden;
    }
    /* Animated gradient overlay */
    body::before {
      content: '';
      position: fixed;
      top: 0; left: 0; right: 0; bottom: 0;
      background: linear-gradient(270deg, #00e6e6, #005050, #00e6e6);
      background-size: 600% 600%;
      animation: gradientShift 20s ease infinite;
      opacity: 0.3;
      pointer-events: none;
      z-index: 0;
    }
    @keyframes gradientShift {
      0% { background-position: 0% 50%; }
      50% { background-position: 100% 50%; }
      100% { background-position: 0% 50%; }
    }

    .overlay {
      background-color: rgba(0, 0, 0, 0.75);
      padding: 50px 30px;
      min-height: 100vh;
      position: relative;
      z-index: 1;
      display: flex;
      justify-content: center;
      align-items: flex-start;
    }
    .container {
      max-width: 900px;
    }

    h1 {
      font-family: 'Orbitron', sans-serif;
      font-size: 56px;
      color: #00e6e6;
      margin-bottom: 10px;
      text-transform: uppercase;
      letter-spacing: 3px;
    }
    h2 {
      font-family: 'Orbitron', sans-serif;
      color: #00e6e6;
      margin-top: 40px;
      font-size: 28px;
      border-bottom: 2px solid #00e6e6;
      padding-bottom: 8px;
    }
    p {
      font-size: 18px;
      line-height: 1.9;
      margin-top: 15px;
      color: #b0ffff;
    }
    ul {
      margin-top: 15px;
      margin-left: 20px;
      color: #b0ffff;
    }
    ul li {
      margin-bottom: 8px;
    }

    /* Contact Section */
    .contact {
      margin-top: 50px;
      border-top: 2px solid #00e6e6;
      padding-top: 25px;
    }
    .contact a {
      color: #00e6e6;
      text-decoration: none;
      font-weight: 600;
    }
    .contact a:hover {
      text-decoration: underline;
    }

    /* Social icons container */
    .socials {
      margin-top: 20px;
      display: flex;
      gap: 20px;
      flex-wrap: wrap;
    }

    .socials a {
      display: inline-flex;
      width: 32px;
      height: 32px;
      fill: #00e6e6;
      transition: fill 0.3s ease;
    }
    .socials a:hover {
      fill: #00ffff;
    }
    .socials svg {
      width: 100%;
      height: 100%;
    }

    /* Responsive */
    @media (max-width: 600px) {
      h1 {
        font-size: 36px;
      }
      h2 {
        font-size: 22px;
      }
      .overlay {
        padding: 30px 20px;
      }
    }
  </style>
</head>
<body>
  <div class="overlay">
    <div class="container">
      <h1>About Nogitech</h1>

      <h2>Who We Are</h2>
      <p>
        Nogitech is a visionary technology powerhouse co-founded by industry leaders Zane Ahmed (CEO) and John Peng, bridging innovation between Pakistan and China.
        We stand at the forefront of tomorrow’s tech revolution, harnessing deep expertise and creative ingenuity to build solutions that transform the way people live and work.
        Our multidisciplinary team unites advanced Chinese engineering precision with the dynamic spirit of Pakistani technological entrepreneurship.
        From breakthrough E-commerce platforms and state-of-the-art GPU manufacturing to intelligent smartwatches, secure VPS hosting, sophisticated surveillance systems, and intricately crafted ship models,
        Nogitech crafts smart, scalable, and reliable products that empower users globally.
      </p>
      <p>
        We are more than a company; we are a movement towards smarter living, seamless connectivity, and intelligent security systems driven by AI.
        Our mission is to deliver cutting-edge technology that is not only high-performing but also affordable and accessible,
        ensuring that innovation has no boundaries and serves every community across continents.
      </p>

      <h2>What We Do</h2>
      <p>
        We specialize in:
        <ul>
          <li>Custom-designed E-commerce gadgets and infrastructure</li>
          <li>Smartwatches and wearable technology</li>
          <li>VPS (Virtual Private Servers) and cloud hosting services</li>
          <li>GPU and high-performance hardware solutions</li>
          <li>Advanced security cameras and monitoring systems</li>
          <li>Precision ship model design and manufacturing</li>
          <li>AI-integrated business solutions and automation</li>
        </ul>
        Proudly serving both Chinese and Pakistani markets, Nogitech delivers performance, security, and affordability to meet your every need.
        Stay ahead with our AI-powered future.
      </p>

      <div class="contact">
        <h2>Contact Us</h2>
        <p>Email: <a href="mailto:nogitechllc@gmail.com">nogitechllc@gmail.com</a></p>
        <p>WhatsApp (Main): +923019551776</p>
        <p>WhatsApp (China): +8613711112233</p>
        <p>WhatsApp (Korea): +821012341234</p>
        <p>WhatsApp (Indonesia): +6281234567890</p>
        <p>WhatsApp (Brazil): +5511987654321</p>
        <p>Website: 
          <a href="https://nogitech.store" target="_blank" rel="noopener">nogitech.store</a> | 
          <a href="https://nogitech.org" target="_blank" rel="noopener">nogitech.org (USA)</a>
        </p>

        <div class="socials" aria-label="Nogitech Social Media Links">
          <a href="https://instagram.com/nogitech.inc" target="_blank" aria-label="Instagram">
            <svg viewBox="0 0 24 24"><path d="M7.75 2h8.5A5.75 5.75 0 0122 7.75v8.5A5.75 5.75 0 0116.25 22h-8.5A5.75 5.75 0 012 16.25v-8.5A5.75 5.75 0 017.75 2zm0 2A3.75 3.75 0 004 7.75v8.5A3.75 3.75 0 007.75 20h8.5a3.75 3.75 0 003.75-3.75v-8.5A3.75 3.75 0 0016.25 4h-8.5zm4.25 3a4.25 4.25 0 110 8.5 4.25 4.25 0 010-8.5zm0 2a2.25 2.25 0 100 4.5 2.25 2.25 0 000-4.5zm4.5-.5a.75.75 0 110 1.5.75.75 0 010-1.5z"/></svg>
          </a>
          <a href="https://facebook.com/nogitech.inc" target="_blank" aria-label="Facebook">
            <svg viewBox="0 0 24 24"><path d="M22 12c0-5.522-4.477-10-10-10S2 6.478 2 12c0 4.991 3.657 9.128 8.438 9.876v-6.987h-2.54v-2.89h2.54v-2.203c0-2.507 1.492-3.89 3.777-3.89 1.094 0 2.238.195 2.238.195v2.46h-1.26c-1.243 0-1.63.771-1.63 1.562v1.876h2.773l-.443 2.89h-2.33v6.987C18.343 21.128 22 16.991 22 12z"/></svg>
          </a>
          <a href="https://linkedin.com/company/nogitech-inc" target="_blank" aria-label="LinkedIn">
            <svg viewBox="0 0 24 24"><path d="M19 3A2 2 0 0121 5v14a2 2 0 01-2 2H5a2 2 0 01-2-2V5a2 2 0 012-2h14zm-9 7v7H7v-7h3zm-1.5-2a1.5 1.5 0 110-3 1.5 1.5 0 010 3zm11 9v-4a2 2 0 00-4 0v4h-3v-7h3v1.22a3.12 3.12 0 016 0V17h-2z"/></svg>
          </a>
          <a href="https://twitter.com/nogitech_inc" target="_blank" aria-label="X (Twitter)">
            <svg viewBox="0 0 24 24"><path d="M23 3a10.9 10.9 0 01-3.14.86 4.48 4.48 0 001.98-2.48 9.1 9.1 0 01-2.88 1.1 4.52 4.52 0 00-7.69 4.13 12.83 12.83 0 01-9.3-4.7 4.5 4.5 0 001.4 6.05 4.5 4.5 0 01-2.05-.57v.06a4.51 4.51 0 003.63 4.43 4.48 4.48 0 01-2.04.08 4.53 4.53 0 004.22 3.13 9.06 9.06 0 01-5.62 1.94A9.32 9.32 0 012 19.54a12.79 12.79 0 006.92 2.03c8.3 0 12.85-6.87 12.85-12.83 0-.2 0-.42-.02-.63A9.22 9.22 0 0023 3z"/></svg>
          </a>
          <a href="https://tiktok.com/@nogitech" target="_blank" aria-label="TikTok">
            <svg viewBox="0 0 24 24"><path d="M12 2v13a4.5 4.5 0 01-4.5-4.5H6a6 6 0 006 6v3h3a6 6 0 006-6V7h-2v5a4 4 0 01-3-3.87V2z"/></svg>
          </a>
          <a href="https://youtube.com/nogitech" target="_blank" aria-label="YouTube">
            <svg viewBox="0 0 24 24"><path d="M10 15l5.19-3L10 9v6zm12-3a3 3 0 01-3 3h-14a3 3 0 01-3-3 3 3 0 013-3h14a3 3 0 013 3z"/></svg>
          </a>
          <a href="https://wa.me/923019551776" target="_blank" aria-label="WhatsApp">
            <svg viewBox="0 0 24 24"><path d="M20.52 3.48a11.36 11.36 0 00-16 0 11.45 11.45 0 000 16 11.37 11.37 0 0016 0 11.37 11.37 0 000-16zm-8.26 15.49a8.1 8.1 0 01-4.42-1.3l-3.01.8.8-3a8.06 8.06 0 1110.45-10.44 8.04 8.04 0 01-3.82 13.94zm4.21-5.66l-1.08-.54a1.29 1.29 0 00-1.2.12l-.57.43a.88.88 0 01-1.3-.57 4.24 4.24 0 01-.4-1.38 1.15 1.15 0 01.53-1.22l.71-.56a.8.8 0 00.32-1 4.1 4.1 0 00-2.24-2.55 3.29 3.29 0 00-3.43.75 9.75 9.75 0 00-2.24 3.13 8.17 8.17 0 003.08 10.5 9.18 9.18 0 001.3.55 2.64 2.64 0 002.27-.39l1.05-.81a1.53 1.53 0 00.56-1.36 4.6 4.6 0 00-1.16-2.48z"/></svg>
          </a>
        </div>
      </div>
    </div>
  </div>
</body>
</html>
