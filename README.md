# GitHub Profile README + Attractive HTML/CSS Profile

This canvas contains three files you can copy/use directly in your GitHub profile repository (`README.md`) and a small static profile landing page (`index.html` + `styles.css`) that matches the "vibecoder + problem-solving enthusiast" tone.

---

## 1) README.md

````markdown
# 👋 Hey there, I'm Mayank!

💡 Robotics & AI student | 💻 Problem Solver | 🌐 Tech Explorer | 🎵 Vibecoder

---

## 🚀 About Me
- 🎓 Pursuing **B.E. in Robotics & AI** at **Bangalore Institute of Technology**
- ⚡ Passionate about **coding, algorithms, and building impactful projects**
- 🌱 Currently exploring **AI/ML, Full-Stack Development, and Sustainable Tech**
- 🎯 Believer in **community + collaboration** (Joint Secretary @ Rotaract Club of BIT)
- ✨ A perfect blend of **tech + creativity + vibes**

---

## 🛠️ Tech Stack
```yaml
Languages: Python, C++, JavaScript
Web Dev: HTML, CSS, React, Node.js, Express, MongoDB
AI/ML: Scikit-Learn, TensorFlow, OpenCV, MobileNet, Streamlit
Tools: Git, GitHub, LabVIEW, MySQL, n8n
````

---

## 🌟 Featured Projects

* 🤖 **ASL Gesture Recognition** – Built using **MobileNet** + Streamlit demo
* 🛒 **FreshPrice** – Dynamic pricing engine for perishables (AI + rules-based logic)
* 📄 **AI Resume Analyzer Bot** – Resume insights using **n8n + LLMs**
* 🔥 **Fire Detection & Alarm System** – Built with **LabVIEW** for real-time safety

---

## 📊 Problem-Solving

* 🚀 Actively solving **DSA (Striver’s A2Z)** in **C++**
* 🧠 Strong interest in **algorithms, optimization, and system design**
* 💡 Loves cracking coding challenges and exploring alternative approaches

---

## 🌐 Connect With Me

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?logo=linkedin\&logoColor=white)](https://www.linkedin.com/in/mayank-raj-084258228/)
[![GitHub](https://img.shields.io/badge/GitHub-black?logo=github\&logoColor=white)](https://github.com/your-username)
[![Portfolio](https://img.shields.io/badge/Portfolio-green?logo=firefox\&logoColor=white)](your-portfolio-link)

---

### 🎵 Vibecoder’s Motto:

*"Code hard, vibe harder, and keep solving problems that matter."*

---

> *Tip:* Replace `your-username` and `your-portfolio-link` with your actual links. Add project links under **Featured Projects** for direct navigation.

````

---

## 2) index.html (Static profile page)

html
<!doctype html>
<html lang="en">
<head>
  <meta charset="utf-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Mayank — Vibecoder & Problem Solver</title>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;400;600;800&display=swap" rel="stylesheet">
  <link rel="stylesheet" href="styles.css">
</head>
<body>
  <main class="container">
    <header class="hero">
      <div class="avatar">MJ</div>
      <div class="intro">
        <h1>Hey, I'm <span class="accent">Mayank</span> 👋</h1>
        <p class="sub">Robotics & AI • Vibecoder • Problem-solving enthusiast</p>
        <p class="bio">I build cool ML demos, tackle algorithms in C++, and craft full-stack projects that solve real problems. Currently exploring AI & sustainable tech — all while keeping the vibes high.</p>
        <div class="links">
          <a class="btn" href="https://github.com/your-username" target="_blank">GitHub</a>
          <a class="btn outline" href="https://www.linkedin.com/in/mayank-raj-084258228/" target="_blank">LinkedIn</a>
          <a class="btn" href="your-portfolio-link" target="_blank">Portfolio</a>
        </div>
      </div>
    </header>

    <section class="cards">
      <article class="card">
        <h3>🎯 Focus Areas</h3>
        <ul>
          <li>Robotics & Control</li>
          <li>Machine Learning & CV</li>
          <li>Full-stack (MERN)</li>
          <li>Algorithmic problem solving (C++)</li>
        </ul>
      </article>

      <article class="card">
        <h3>🛠️ Top Projects</h3>
        <ol>
          <li>ASL Gesture Recognition — MobileNet + Streamlit</li>
          <li>FreshPrice — Dynamic pricing for perishables</li>
          <li>AI Resume Analyzer — n8n + LLMs</li>
        </ol>
      </article>

      <article class="card">
        <h3>📈 Quick Stats</h3>
        <p>DSA Progress: <strong>Arrays, Strings, Linked Lists, Stacks & Queues</strong></p>
        <p>Preferred Language: <strong>C++</strong></p>
      </article>
    </section>

    <footer class="footer">
      <p>🎵 Vibecoder's motto: <em>Code hard, vibe harder, and keep solving problems that matter.</em></p>
    </footer>
  </main>
</body>
</html>


---

## 3) styles.css

```css
:root{
  --bg: #0f1724;
  --card: #0b1220;
  --muted: #9aa7b2;
  --accent: #7c5cff;
  --glass: rgba(255,255,255,0.03);
  --radius: 14px;
  --fw-sans: 'Inter', system-ui, -apple-system, 'Segoe UI', Roboto, 'Helvetica Neue', Arial;
}

*{box-sizing:border-box;margin:0;padding:0}
html,body{height:100%}
body{
  font-family:var(--fw-sans);
  background: linear-gradient(180deg, #071223 0%, #07182a 100%);
  color:#e6eef6;
  -webkit-font-smoothing:antialiased;
  -moz-osx-font-smoothing:grayscale;
  padding:32px;
}

.container{
  max-width:1000px;
  margin:0 auto;
}

.hero{
  display:flex;
  gap:28px;
  align-items:center;
  background: linear-gradient(180deg, rgba(255,255,255,0.02), rgba(255,255,255,0.01));
  padding:28px;
  border-radius:var(--radius);
  box-shadow: 0 8px 30px rgba(2,6,23,0.6);
}

.avatar{
  width:120px;
  height:120px;
  border-radius:20px;
  background: linear-gradient(135deg, rgba(124,92,255,0.18), rgba(0,200,255,0.08));
  display:flex;
  align-items:center;
  justify-content:center;
  font-weight:800;
  font-size:36px;
  color:var(--accent);
  border:1px solid rgba(124,92,255,0.18);
}

.intro h1{font-size:28px;margin-bottom:6px}
.intro .accent{color:var(--accent)}
.sub{color:var(--muted);margin-bottom:10px}
.bio{color:#cfe6ff;margin-bottom:14px;max-width:680px}

.links{display:flex;gap:12px}
.btn{
  text-decoration:none;
  padding:10px 14px;
  border-radius:10px;
  background:linear-gradient(90deg,var(--accent),#5ad0ff);
  color:#051025;
  font-weight:600;
}
.btn.outline{background:transparent;border:1px solid rgba(255,255,255,0.06);color:var(--muted)}

.cards{
  display:grid;
  grid-template-columns: repeat(auto-fit,minmax(220px,1fr));
  gap:18px;
  margin-top:20px;
}
.card{
  background:var(--card);
  padding:18px;
  border-radius:12px;
  box-shadow:0 6px 20px rgba(6,10,20,0.6);
}
.card h3{margin-bottom:8px}
.card ul, .card ol{color:var(--muted);padding-left:16px}

.footer{margin-top:18px;text-align:center;color:var(--muted);font-size:14px}

@media (max-width:700px){
  .hero{flex-direction:column;align-items:flex-start}
  .avatar{width:96px;height:96px}
}
```

---

### How to use

1. Copy the `README.md` content into your GitHub profile repository's `README.md` (replace placeholders with real links).
2. Optionally create a small repo or use GitHub Pages to host `index.html` + `styles.css` for a personal landing page.
3. Tell me if you want an SVG avatar, animations, or a dark/light toggle — I can update the HTML/CSS accordingly.

---

If you'd like, I can now:

* Generate an SVG avatar for your page,
* Produce a version tailored to mobile-first design,
* Or convert the landing page into a single-file markdown preview for GitHub pages.

Tell me which of those (if any) you want next.
