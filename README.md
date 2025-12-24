
<html lang="en"><head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1">
  <title>Đỗ Đăng Khoa | Profile</title>
  <style>
    :root{
      --bg:#ffffff;
      --text:#111111;
      --muted:#555555;
      --line:#e6e6e6;
      --max: 980px;
      --radius: 14px;
    }
    *{ box-sizing:border-box; }
    body{
      margin:0;
      font-family: ui-sans-serif, system-ui, -apple-system, Segoe UI, Roboto, Helvetica, Arial, "Apple Color Emoji","Segoe UI Emoji";
      background:var(--bg);
      color:var(--text);
      line-height:1.55;
    }
    a{ color:var(--text); text-decoration:none; border-bottom:1px solid var(--line); }
    a:hover{ border-bottom-color: var(--text); }
    .wrap{
      max-width: var(--max);
      margin: 0 auto;
      padding: 44px 18px 80px;
    }
    header{
      display:grid;
      grid-template-columns: 140px 1fr;
      gap: 22px;
      align-items:start;
      padding-bottom: 22px;
      border-bottom:1px solid var(--line);
    }
    .avatar{
      width:140px;
      height:140px;
      border-radius: var(--radius);
      border:1px solid var(--line);
      overflow:hidden;
      background:#fafafa;
      display:flex;
      align-items:center;
      justify-content:center;
      font-size:12px;
      color:var(--muted);
    }
    .avatar img{
      width:100%;
      height:100%;
      object-fit:cover;
      display:block;
    }
    h1{
      margin:0 0 6px 0;
      font-size: 34px;
      letter-spacing: -0.3px;
    }
    .subtitle{
      margin:0 0 12px 0;
      color:var(--muted);
      font-size: 15px;
    }
    .bio{
      margin:0 0 14px 0;
      font-size: 15.5px;
    }
    .links{
      display:flex;
      flex-wrap:wrap;
      gap:10px 14px;
      margin-top: 10px;
      color:var(--muted);
      font-size: 14px;
    }
    .links a{
      border-bottom:1px solid var(--line);
      padding-bottom:2px;
    }
    nav{
      display:flex;
      gap:14px;
      margin: 18px 0 0;
      flex-wrap:wrap;
      font-size:14px;
      color:var(--muted);
    }
    nav a{
      border:0;
      padding:6px 10px;
      border-radius: 999px;
      background: #fff;
      border:1px solid var(--line);
    }
    nav a:hover{ border-color: var(--text); }
    main{
      display:grid;
      grid-template-columns: 1fr 320px;
      gap: 28px;
      margin-top: 26px;
      align-items:start;
    }
    section{
      padding: 18px 0;
      border-bottom:1px solid var(--line);
    }
    section:last-child{ border-bottom:0; }
    h2{
      margin:0 0 10px 0;
      font-size: 18px;
      letter-spacing: -0.2px;
    }
    p{ margin: 0 0 10px 0; }
    .muted{ color:var(--muted); }
    .card{
      border:1px solid var(--line);
      border-radius: var(--radius);
      padding: 14px 14px;
      background:#fff;
    }
    .list{
      list-style:none;
      padding:0;
      margin:0;
      display:flex;
      flex-direction:column;
      gap:10px;
    }
    .item{
      padding:10px 0;
      border-bottom:1px dashed var(--line);
    }
    .item:last-child{ border-bottom:0; }
    .date{
      font-size:12px;
      color:var(--muted);
      margin-bottom:4px;
    }
    .tagrow{
      display:flex;
      flex-wrap:wrap;
      gap:8px;
      margin-top:10px;
    }
    .tag{
      font-size:12px;
      border:1px solid var(--line);
      border-radius:999px;
      padding:4px 10px;
      color:var(--muted);
    }
    footer{
      margin-top: 34px;
      padding-top: 18px;
      border-top:1px solid var(--line);
      color:var(--muted);
      font-size: 13px;
    }
    @media (max-width: 860px){
      header{ grid-template-columns: 110px 1fr; }
      .avatar{ width:110px; height:110px; }
      main{ grid-template-columns: 1fr; }
    }
  </style>
</head>

<body>
  <div class="wrap">
    <header>
      <div class="avatar">
        <img alt="Do Dang Khoa" src="1756120461383.jpg">
      </div>

      <div>
        <h1>Đỗ Đăng Khoa</h1>
        <p class="subtitle">First-year Computer Science Student • Interested in Computer Vision Applications</p>

        <p class="bio">
          I am currently studying Computer Science at the
          <strong>University of Information Technology, Vietnam National University, Ho Chi Minh City</strong>.
          I focus on learning and exploring practical applications of <strong>Computer Vision</strong>.
          Currently, I am building my foundation in programming and math, and I plan to develop small projects
          that connect vision techniques with real-world problems.
        </p>
        <!-- ADDED: Education in bio -->

        <div class="links">
          <a href="#" title="Google Scholar (placeholder)">Google Scholar</a>
          <a href="https://github.com/KaxA1910">GitHub</a>
          <a href="https://www.linkedin.com/in/khoado1910/">LinkedIn</a>
          <a href="mailto:25520850@gm.uit.edu.vn">Email</a>
        </div>

        <nav>
          <a href="#news">News</a>
          <a href="#about">About</a>
          <a href="#projects">Projects</a>
          <a href="#skills">Skills</a>
        </nav>
      </div>
    </header>

    <main>
      <div>
        <section id="news">
          <h2>News</h2>
          <ul class="list">
            <li class="item">
              <div class="date">Nov 2025</div>
              <div>Started focusing on Computer Vision fundamentals (image processing, CNN basics).</div>
            </li>
            <li class="item">
              <div class="date">Dec 2025</div>
              <div>Planning a small CV project (classification / detection) as a personal learning milestone.</div>
            </li>
            <li class="item">
              <div class="date">2026</div>
              <div>Goal: build a portfolio with 2–3 clear Computer Vision application demos.</div>
            </li>
          </ul>
        </section>

        <section id="about">
          <h2>About</h2>
          <p>
            I am a first-year Computer Science student at the University of Information Technology (UIT),
            Vietnam National University, Ho Chi Minh City.
            My current priority is to learn core knowledge (programming, mathematics, and basic ML concepts)
            and then apply it through small Computer Vision projects.
          </p>
          <!-- ADDED: Education in About -->

          <div class="tagrow">
            <span class="tag">Computer Vision</span>
            <span class="tag">Deep Learning (Basics)</span>
            <span class="tag">Python / C++</span>
            <span class="tag">Image Processing</span>
          </div>
        </section>

        <section id="projects">
          <h2>Projects</h2>
          <p class="muted">Because I am a first-year student, I keep this simple and add projects gradually.</p>
          <ul class="list">
            <li class="item">
              <div><strong>Mini CV Project (Planned)</strong></div>
              <div class="muted">A small demo using a public dataset and a simple baseline model.</div>
            </li>
            <li class="item">
              <div><strong>Learning Notes</strong></div>
              <div class="muted">Structured notes about CNN concepts and practical training tips.</div>
            </li>
          </ul>
        </section>
      </div>

      <aside class="card">
        <h2 id="skills">Quick Info</h2>
        <p><strong>Field:</strong> Computer Science</p>
        <p><strong>Focus:</strong> Applications of Computer Vision</p>
        <p><strong>Level:</strong> First-year student</p>
        <p><strong>Location:</strong> Vietnam</p>

        <div style="height:10px;"></div>
        <h2>Education</h2>
        <p class="muted" style="margin-bottom:4px;">
          University of Information Technology (UIT)
        </p>
        <p class="muted" style="margin-bottom:4px;">
          Vietnam National University, Ho Chi Minh City
        </p>
        <p class="muted" style="margin-bottom:0;">
          B.Sc. in Computer Science (First-year)
        </p>

        <div style="height:10px;"></div>
        <h2>Interests</h2>
        <ul class="list">
          <li class="item">Image classification</li>
          <li class="item">Object detection (later)</li>
          <li class="item">Real-world CV use cases</li>
        </ul>

        <div style="height:10px;"></div>
        <h2>Contact</h2>
        <p class="muted" style="margin-bottom:0;">
          Email: <a href="mailto:25520850@gm.uit.edu.vn">25520850@gm.uit.edu.vn</a>
        </p>
      </aside>
    </main>

    <footer>
      © 2025 Đỗ Đăng Khoa. Simple academic-style personal page.
    </footer>
  </div>
</body>
</html>

