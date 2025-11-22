---
layout: default
title: "Home"
---



<!-- ---

## 🎓 About Me {#about}

BASc in Engineering Science @ University of Toronto

---

## 💼 Experience {#experience}

- **Unversity of Toronto** - Research Assistant
    Conducted Research on diffusion video generation and its robots applications.
- **AMD** – Analog Design Intern
    Developed internal workflows capitalizing on machine learning techniques for silicon layout.
- **University of Toronto** – Research Assistant  
    Conducted research on novel structural sensing techniques.
- **Diversio** - Software Engineering Intern
    Developed MVP using React and Node.js, developed internal tooling for data transformations.

---

## 🧰 Skills {#skills}

**Languages**: Python, Perl, C/C++, Verilog, MATLAB, TCL, Java, Javascript
**Tools**: Cadence Virtuoso, Calibre, HSpice, Git, LaTeX, Atlassian Tools

---

## 📫 Contact {#contact}

- **Email**: roderick.wu@mail.utoronto.ca
- **GitHub**: [Roderick-Wu](https://github.com/Roderick-Wu)  
- **LinkedIn**: [Roderick Wu](https://www.linkedin.com/in/roderick--wu)
 -->

<!-- <div id="nav" class="navigation"> -->
<nav class="nav-links">
    <!-- <a href="#about">About Me</a> |
    <a href="#experience">Experience</a> |
    <a href="#skills">Skills</a> |
    <a href="#contact">Contact</a> -->
    <button class="nav-title" onclick="location.href='#title-card'">Roderick Wu</button>
    <div class="nav-buttons">
        <button onclick="location.href='#about'">About</button>
        <button onclick="location.href='#experience'">Experience</button>
        <button onclick="location.href='#skills'">Skills</button>
        <button onclick="location.href='#contact'">Contact</button>
    </div>
</nav>

<div class="page-content">

<div class="nav-spacer"></div>

<section id="title-card" class="section-fullscreen">
    <div>
        <h1 class="title-heading">Hi, I'm Roderick</h1>
        <h2 class="title-subheading">Welcome to my personal website.</h2>
    </div>
</section>

<section id="about" class="section-fullscreen">
    <div>
        <h1>About Me</h1>
    </div>
    <div id="about-content" class="content">
        <p>I'm currently a fourth year Engineering Student at the University of Toronto.</p>
        <p>I am interested in machine learning at the most abstracted level, as well its execution on hardware. Previously, I was working at AMD on a project aiming to use machine learning for analog design. </p>
        <p>Currently, I am working with Prof. Zhijing Jin and Prof. Roger Grosse for my bachelor's thesis on mechanistic interpretability and causality. I am also working with Prof. Igor Gilitschenski for a project on using video diffusion models for robot planning. </p>
    </div>
</section>

<section id="experience" class="section-fullscreen">
    <div>
        <h1>Experience</h1>
    </div>
    <div id="experience-content" class="content">
        <ul>
            <li><strong>University of Toronto</strong>: Research Assistant</li>
            <li><strong>Advanced Micro Devices (AMD)</strong>: Analog Design Intern - Developed internal workflows capitalizing on machine learning techniques for silicon layout.</li>
            <li><strong>University of Toronto</strong>: Research Assistant - Conducted research on novel structural sensing techniques.</li>
            <li><strong>Diversio</strong>: Software Engineering Intern - Developed MVP using React and Node.js, developed internal tooling for data transformations.</li>
        </ul>
    </div>
</section>

<!-- <section id="experience" class="section-fullscreen">
    <div>
        <h1>Experience</h1>
    </div>
    <div id="experience-content" class="content">
        <div onclick="toggleSection('exp_content_1')">
            <h2><strong>University of Toronto</strong>: Research Assistant - Studying diffusion model models and its robotic applications</h2>
            <div id="exp_content_1" class="content">
                <li>Studying video generation for robotics applications. Investigating Diffusion/Consistency models with novel methods for refinement.</li>
                <li>Extracting information from latent embeddings</li>
            </div>
        </div>
        <div onclick="toggleSection('exp_content_2')">
            <h2><strong>Advanced Micro Devices (AMD)</strong>: Analog Design Intern - Working on internal workflows capitalizing on machine learning techniques for silicon layout</h2>
            <div id="exp_content_2" class="content">
                <li></li>
            </div>
        </div>
        <div onclick="toggleSection('exp_content_3')">
            <h2><strong>University of Toronto</strong>: Research Assistant - Conducted research on novel structural sensing techniques</h2>
            <div id="exp_content_3" class="content">
                <li></li>
            </div>
        </div>
        <div onclick="toggleSection('exp_content_4')">
            <h2><strong>Diversio</strong>: Software Engineering Intern - Built products to advance AI applications</h2>
            <div id="exp_content_4" class="content">
                <li></li>
            </div>
        </div>
    </div>
</section> -->

<section id="skills" class="section-fullscreen">
    <div>
        <h1>Skills</h1>
    </div>
    <div id="skills-content" class="content">
        <p><strong>Languages:</strong></p>
        <ul class="skills-list">
        <li>
            <svg viewBox="0 0 24 24" fill="#3776AB">
                <title>Python</title>
                <path d="M14.25.18l.9.2.73.26.59.3.45.32.34.34.25.34.16.33.1.3.04.26.02.2-.01.13V8.5l-.05.63-.13.55-.21.46-.26.38-.3.31-.33.25-.35.19-.35.14-.33.1-.3.07-.26.04-.21.02H8.77l-.69.05-.59.14-.5.22-.41.27-.33.32-.27.35-.2.36-.15.37-.1.35-.07.32-.04.27-.02.21v3.06H3.17l-.21-.03-.28-.07-.32-.12-.35-.18-.36-.26-.36-.36-.35-.46-.32-.59-.28-.73-.21-.88-.14-1.05-.05-1.23.06-1.22.16-1.04.24-.87.32-.71.36-.57.4-.44.42-.33.42-.24.4-.16.36-.1.32-.05.24-.01h.16l.06.01h8.16v-.83H6.18l-.01-2.75-.02-.37.05-.34.11-.31.17-.28.25-.26.31-.23.38-.2.44-.18.51-.15.58-.12.64-.1.71-.06.77-.04.84-.02 1.27.05zm-6.3 1.98l-.23.33-.08.41.08.41.23.34.33.22.41.09.41-.09.33-.22.23-.34.08-.41-.08-.41-.23-.33-.33-.22-.41-.09-.41.09zm13.09 3.95l.28.06.32.12.35.18.36.27.36.35.35.47.32.59.28.73.21.88.14 1.04.05 1.23-.06 1.23-.16 1.04-.24.86-.32.71-.36.57-.4.45-.42.33-.42.24-.4.16-.36.09-.32.05-.24.02-.16-.01h-8.22v.82h5.84l.01 2.76.02.36-.05.34-.11.31-.17.29-.25.25-.31.24-.38.2-.44.17-.51.15-.58.13-.64.09-.71.07-.77.04-.84.01-1.27-.04-1.07-.14-.9-.2-.73-.25-.59-.3-.45-.33-.34-.34-.25-.34-.16-.33-.1-.3-.04-.25-.02-.2.01-.13v-5.34l.05-.64.13-.54.21-.46.26-.38.3-.32.33-.24.35-.2.35-.14.33-.1.3-.06.26-.04.21-.02.13-.01h5.84l.69-.05.59-.14.5-.21.41-.28.33-.32.27-.35.2-.36.15-.36.1-.35.07-.32.04-.28.02-.21V6.07h2.09l.14.01zm-6.47 14.25l-.23.33-.08.41.08.41.23.33.33.23.41.08.41-.08.33-.23.23-.33.08-.41-.08-.41-.23-.33-.33-.23-.41-.08-.41.08z"/>
            </svg>
            Python
        </li>
        <li>
            <svg viewBox="0 0 24 24" fill="#02569B" xmlns="http://www.w3.org/2000/svg">
                <title>Perl</title>
                <path d="M12 0A12 12 0 0 0 0 12a12 12 0 0 0 12 12 12 12 0 0 0 12-12A12 12 0 0 0 12 0m.157 1.103a10.91 10.91 0 0 1 9.214 5.404c-1.962.152-3.156 1.698-5.132 3.553-2.81 2.637-4.562.582-5.288-.898-.447-1.004-.847-2.117-1.544-2.769A.4.4 0 0 1 9.3 6.02l.08-.37a.083.083 0 0 0-.074-.1c-.33-.022-.601.093-.84.368a2.5 2.5 0 0 0-.375-.064c-.863-.093-1.036.345-1.873.345H5.81c-.758 0-1.391.361-1.7.892-.248.424-.257.884.15.93-.126.445.292.62 1.224.192 0 0 .733.421 1.749.421.549 0 .712.087.914.967.486 2.138 2.404 5.655 6.282 5.655l.118.166c.659.934.86 2.113.48 3.184-.307.867-.697 1.531-.697 1.531q.01.178.01.349c0 .81-.175 1.553-.387 2.23a10.91 10.91 0 0 1-11.989-6.342A10.91 10.91 0 0 1 7.608 2.01a10.9 10.9 0 0 1 4.55-.907M7.524 6.47c.288 0 .575.231.477.272a.4.4 0 0 1-.1.02.38.38 0 0 1-.375.327.384.384 0 0 1-.378-.326.4.4 0 0 1-.101-.02c-.098-.042.19-.273.477-.273m10.193 10.49q.05 0 .101.007.326.054.694.096.135.01.269.026a13.4 13.4 0 0 0 2.846-.007 10.9 10.9 0 0 1-2.007 2.705c-.11-.23-.547-1.19-.573-2.196q-.156-.01-.313-.026-.13-.014-.256-.022a18 18 0 0 1-.735-.102h-.003c-.032 0-.06.01-.074.035l-.003.012q-.081.265-.182.544c.428 1.084.652 2.078.652 2.078.14.22.258.432.363.64a11 11 0 0 1-2.168 1.264 11 11 0 0 1-1.205.426 13.3 13.3 0 0 1 1.055-2.531s.678-1.445 1.027-2.564v-.004a.55.55 0 0 1 .512-.38"/>
            </svg>
            Perl
        </li>
        <li>
            <svg viewBox="0 0 24 24" fill="#00599C">
                <title>C++</title>
                <path d="M22.394 6c-.167-.29-.398-.543-.652-.69L12.926.22c-.509-.294-1.34-.294-1.848 0L2.26 5.31c-.508.293-.923 1.013-.923 1.6v10.18c0 .294.104.62.271.91.167.29.398.543.652.69l8.816 5.09c.508.293 1.34.293 1.848 0l8.816-5.09c.254-.147.485-.4.652-.69.167-.29.27-.616.27-.91V6.91c.003-.294-.1-.62-.268-.91zM12 19.11c-3.92 0-7.109-3.19-7.109-7.11 0-3.92 3.19-7.11 7.11-7.11a7.133 7.133 0 016.156 3.553l-3.076 1.78a3.567 3.567 0 00-3.08-1.78A3.56 3.56 0 008.444 12 3.56 3.56 0 0012 15.555a3.57 3.57 0 003.08-1.778l3.078 1.78A7.135 7.135 0 0112 19.11zm7.11-6.715h-.79v.79h-.79v-.79h-.79v-.79h.79v-.79h.79v.79h.79v.79zm2.962 0h-.79v.79h-.79v-.79h-.79v-.79h.79v-.79h.79v.79h.79v.79z"/>
            </svg>
            C / C++
        </li>
        <li>
            <svg viewBox="0 0 32 32" fill="#b2b7f8" xmlns="http://www.w3.org/2000/svg">
                <title>Verilog</title>
                <path d="M16 4.5L6 10v12l10 5.5 10-5.5V10L16 4.5zm0 1.82L23.18 10 16 13.82 8.82 10 16 6.32zM8 11.5l7 4.05v10.2l-7-4.05V11.5zm16 0v10.2l-7 4.05V15.55l7-4.05z"/>
            </svg>
            Verilog
        </li>
        <li>
            <svg viewBox="0 0 32 32" xmlns="http://www.w3.org/2000/svg">
                <title>MATLAB</title>
                <defs>
                    <linearGradient id="matlab-a" x1="16.803" x2="15.013" y1="16.631" y2="22.411" gradientTransform="matrix(1 0 0 -1 0 32)" gradientUnits="userSpaceOnUse">
                        <stop offset="0" stop-color="#512"/>
                        <stop offset=".23" stop-color="#523"/>
                        <stop offset=".36" stop-color="#534"/>
                        <stop offset=".51" stop-color="#645"/>
                        <stop offset=".66" stop-color="#568"/>
                        <stop offset=".84" stop-color="#29d"/>
                    </linearGradient>
                    <linearGradient id="matlab-b" x1="29.71" x2="11.71" y1="18.983" y2="14.563" gradientUnits="userSpaceOnUse">
                        <stop offset=".081" stop-color="#c33"/>
                        <stop offset=".189" stop-color="#de5239"/>
                        <stop offset=".313" stop-color="#f06e3e"/>
                        <stop offset=".421" stop-color="#fa8042"/>
                        <stop offset=".5" stop-color="#fe8643"/>
                        <stop offset=".58" stop-color="#fa7f42"/>
                        <stop offset=".696" stop-color="#ef6c3e"/>
                        <stop offset=".833" stop-color="#dc4c37"/>
                        <stop offset=".916" stop-color="#cf3633"/>
                    </linearGradient>
                </defs>
                <path d="M2 17.55l7.97-3.22a20.7 20.7 0 0 1 2.72-2.95c.66-.35 1.9-.16 4.17-2.98 2.2-2.75 2.9-5.1 3.93-5.1 1.63 0 2.83 3.52 4.65 8.85A115.629 115.629 0 0 0 30 24.12c-1.9-1.77-3.52-3.68-5.37-3.63-1.72.04-3.63 2.08-5.72 4.7-1.66 2.1-3.86 3.54-4.72 3.51 0 0-2.22-6.28-4.08-7.3a2.641 2.641 0 0 0-2.39.2L2 17.54z" fill="#49d"/>
                <path d="M19.8 4.02c-.67.9-1.48 2.55-2.94 4.38-2.27 2.82-3.5 2.63-4.17 2.98a19.674 19.674 0 0 0-2.72 2.95l3.3 2.41c2.8-3.82 4.3-7.96 5.47-10.64a13.579 13.579 0 0 1 1.06-2.08z" fill="url(#matlab-a)"/>
                <path d="M20.8 3.3c-2.18 0-3.67 11.48-11.72 17.89 2.26-.37 4.22 5.24 5.12 7.51 4-.68 7.2-8.33 10.43-8.21 1.85.07 3.47 1.86 5.37 3.63C25.66 15 23.63 3.3 20.8 3.3z" fill="url(#matlab-b)"/>
            </svg>
            MATLAB
        </li> 
        <li>
            <svg viewBox="0 0 24 24" fill="#3178C6" xmlns="http://www.w3.org/2000/svg">
                <title>TypeScript</title>
                <path d="M1.125 0C.502 0 0 .502 0 1.125v21.75C0 23.498.502 24 1.125 24h21.75c.623 0 1.125-.502 1.125-1.125V1.125C24 .502 23.498 0 22.875 0zm17.363 9.75c.612 0 1.154.037 1.627.111a6.38 6.38 0 0 1 1.306.34v2.458a3.95 3.95 0 0 0-.643-.361 5.093 5.093 0 0 0-.717-.26 5.453 5.453 0 0 0-1.426-.2c-.3 0-.573.028-.819.086a2.1 2.1 0 0 0-.623.242c-.17.104-.3.229-.393.374a.888.888 0 0 0-.14.49c0 .196.053.373.156.529.104.156.252.304.443.444s.423.276.696.41c.273.135.582.274.926.416.47.197.892.407 1.266.628.374.222.695.473.963.753.268.279.472.598.614.957.142.359.214.776.214 1.253 0 .657-.125 1.21-.373 1.656a3.033 3.033 0 0 1-1.012 1.085 4.38 4.38 0 0 1-1.487.596c-.566.12-1.163.18-1.79.18a9.916 9.916 0 0 1-1.84-.164 5.544 5.544 0 0 1-1.512-.493v-2.63a5.033 5.033 0 0 0 3.237 1.2c.333 0 .624-.03.872-.09.249-.06.456-.144.623-.25.166-.108.29-.234.373-.38a1.023 1.023 0 0 0-.074-1.089 2.12 2.12 0 0 0-.537-.5 5.597 5.597 0 0 0-.807-.444 27.72 27.72 0 0 0-1.007-.436c-.918-.383-1.602-.852-2.053-1.405-.45-.553-.676-1.222-.676-2.005 0-.614.123-1.141.369-1.582.246-.441.58-.804 1.004-1.089a4.494 4.494 0 0 1 1.47-.629 7.536 7.536 0 0 1 1.77-.201zm-15.113.188h9.563v2.166H9.506v9.646H6.789v-9.646H3.375z"/>
            </svg>
            Typescript/JavaScript
        </li>
        </ul>
        <p><strong>Tools:</strong> Linux, Git, Cadence Virtuoso, Calibre, HSpice, LaTeX, Atlassian Tools</p>
        <p>For machine learning work, I have experience using Pytorch, JAX, Scikit-learn, and Tensorflow. I have also written CUDA kernels for acceleration. </p>
    </div>
</section>

<section id="contact" class="section-fullscreen">
    <div>
        <h1>Contact</h1>
    </div>
    <div id="contact-content" class="content">
        <div class="contact-item">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="#EA4335">
                <path d="M20 4H4c-1.1 0-1.99.9-1.99 2L2 18c0 1.1.9 2 2 2h16c1.1 0 2-.9 2-2V6c0-1.1-.9-2-2-2zm0 4l-8 5-8-5V6l8 5 8-5v2z"/>
            </svg>
            <a href="mailto:roderick.wu@mail.utoronto.ca" target="_blank" class="contact-link email-link">roderick.wu@mail.utoronto.ca</a>
        </div>
        <div class="contact-item">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="#181717">
                <path d="M12 0c-6.626 0-12 5.373-12 12 0 5.302 3.438 9.8 8.207 11.387.599.111.793-.261.793-.577v-2.234c-3.338.726-4.033-1.416-4.033-1.416-.546-1.387-1.333-1.756-1.333-1.756-1.089-.745.083-.729.083-.729 1.205.084 1.839 1.237 1.839 1.237 1.07 1.834 2.807 1.304 3.492.997.107-.775.418-1.305.762-1.604-2.665-.305-5.467-1.334-5.467-5.931 0-1.311.469-2.381 1.236-3.221-.124-.303-.535-1.524.117-3.176 0 0 1.008-.322 3.301 1.23.957-.266 1.983-.399 3.003-.404 1.02.005 2.047.138 3.006.404 2.291-1.552 3.297-1.23 3.297-1.23.653 1.653.242 2.874.118 3.176.77.84 1.235 1.911 1.235 3.221 0 4.609-2.807 5.624-5.479 5.921.43.372.823 1.102.823 2.222v3.293c0 .319.192.694.801.576 4.765-1.589 8.199-6.086 8.199-11.386 0-6.627-5.373-12-12-12z"/>
            </svg>
            <a href="https://github.com/Roderick-Wu" target="_blank" class="contact-link github-link">GitHub</a>
        </div>
        <div class="contact-item">
            <svg class="contact-icon" viewBox="0 0 24 24" fill="#0A66C2">
                <path d="M20.447 20.452h-3.554v-5.569c0-1.328-.027-3.037-1.852-3.037-1.853 0-2.136 1.445-2.136 2.939v5.667H9.351V9h3.414v1.561h.046c.477-.9 1.637-1.85 3.37-1.85 3.601 0 4.267 2.37 4.267 5.455v6.286zM5.337 7.433c-1.144 0-2.063-.926-2.063-2.065 0-1.138.92-2.063 2.063-2.063 1.14 0 2.064.925 2.064 2.063 0 1.139-.925 2.065-2.064 2.065zm1.782 13.019H3.555V9h3.564v11.452zM22.225 0H1.771C.792 0 0 .774 0 1.729v20.542C0 23.227.792 24 1.771 24h20.451C23.2 24 24 23.227 24 22.271V1.729C24 .774 23.2 0 22.222 0h.003z"/>
            </svg>
            <a href="https://www.linkedin.com/in/roderick--wu/" target="_blank" class="contact-link linkedin-link">LinkedIn</a>
        </div>
    </div>
</section>

<!-- <section id="test_chatbot" class="section-fullscreen">
    <div>
        <h1>Chat with Bot</h1>
    </div>
  <textarea id="input" rows="4" cols="50"></textarea><br>
  <button onclick="sendMessage()">Send</button>
  <p><strong>Response:</strong> <span id="response"></span></p>

  <script>
    async function sendMessage() {
      const message = document.getElementById("input").value;
      const res = await fetch("https://f5e704e4cc74.ngrok-free.app/chat", {
        method: "POST",
        headers: { "Content-Type": "application/json" },
        body: JSON.stringify({ message })
      });
      const data = await res.json();
      document.getElementById("response").innerText = data.response;
    }
  </script>
</section> -->
