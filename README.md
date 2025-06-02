<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>HospitalBanai.com - Project Overview</title>
  <style>
    body { font-family: Arial, sans-serif; line-height: 1.6; padding: 2rem; background: #f9f9f9; color: #333; }
    h1, h2, h3 { color: #0c4a6e; }
    pre { background: #eee; padding: 1rem; overflow-x: auto; }
    code { background: #f1f1f1; padding: 2px 4px; border-radius: 4px; }
    a { color: #2563eb; text-decoration: none; }
    a:hover { text-decoration: underline; }
  </style>
</head>
<body>

  <h1>HospitalBanai.com 🌐</h1>
  <p><strong>HospitalBanai.com</strong> is a modern, responsive healthcare consultancy website built using HTML, CSS, Bootstrap, and JavaScript libraries. It presents the full scope of services for hospital design, planning, and development in Bangladesh.</p>

  <h2>⚙️ Tech Stack</h2>
  <ul>
    <li><code>HTML</code> (partial templates without <code>&lt;html&gt;</code>, <code>&lt;head&gt;</code>, <code>&lt;body&gt;</code> wrappers)</li>
    <li><code>CSS</code> (custom styling)</li>
    <li><code>Bootstrap 5</code> (layout & responsive design)</li>
    <li><code>JavaScript</code> (vanilla)</li>
    <li><code>jQuery</code> (light DOM manipulation)</li>
    <li><code>AOS.js</code> (scroll animations)</li>
    <li><code>Owl Carousel</code> (responsive sliders)</li>
    <li><code>Font Awesome</code> (icons)</li>
  </ul>

  <h2>📁 Project Structure</h2>
  <pre><code>hospitalbanai/
├── css/
│   └── style.css
├── js/
│   ├── main.js
│   ├── aos.js
│   └── owl.carousel.min.js
├── partials/
│   ├── header.html
│   ├── footer.html
│   └── content-sections.html
├── index.html
├── assets/
│   └── images/
└── README.md
</code></pre>

  <blockquote>
    ⚠️ This project uses <strong>HTML fragments</strong> that are designed to be included dynamically (e.g., via PHP includes, Laravel Blade, or JavaScript injection). These files <strong>do not</strong> contain full HTML page structure.
  </blockquote>

  <h2>🚀 How to Use</h2>
  <p>You can integrate these templates into:</p>
  <ul>
    <li>Laravel Blade files</li>
    <li>PHP-based views using <code>include()</code></li>
    <li>Static sites using build tools or manual HTML assembly</li>
  </ul>

  <p>To preview in browser:</p>
  <pre><code>&lt;!DOCTYPE html&gt;
&lt;html lang="en"&gt;
&lt;head&gt;...&lt;/head&gt;
&lt;body&gt;
  &lt;?php include 'partials/header.html'; ?&gt;
  &lt;?php include 'partials/content-sections.html'; ?&gt;
  &lt;?php include 'partials/footer.html'; ?&gt;
&lt;/body&gt;
&lt;/html&gt;
</code></pre>

  <h2>👨‍💻 Author</h2>
  <p><strong>Nowab Shorif Noman</strong><br>
     Web Application Developer<br>
     📧 <a href="mailto:nsanoman@gmail.com">nsanoman@gmail.com</a><br>
     🌐 <a href="https://www.hospitalbanai.com" target="_blank">hospitalbanai.com</a>
  </p>

  <hr>
  <p><em>Feel free to fork, customize, or build upon this project.</em></p>

</body>
</html>
