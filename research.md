---
layout: page
permalink: /research
---

<html>
<head>
  <style>
    #side-panel {
      width: 200px;
      height: 100%;
      position: fixed;
      top: 0;
      left: 0;
      background-color: #f1f1f1;
      overflow-x: hidden;
      padding-top: 20px;
    }
    
    #side-panel a {
      display: block;
      padding: 10px;
      text-decoration: none;
      color: #333;
    }
    
    #side-panel a:hover {
      background-color: #ddd;
    }
    
    #side-panel .active {
      background-color: #4CAF50;
      color: white;
    }
    
    #main {
      margin-left: 200px; /* Same width as the side panel */
      padding: 20px;
    }
  </style>
</head>
<body>
  <div id="side-panel">
    <ul>
      <li><a href="#section1">Dataset 1: CQAW Challenge</a></li>
      <li><a href="#section2">Dataset 2: CQAW Challenge</a></li>
      <li><a href="#section3">Dataset 3: CQAW Challenge</a></li>
    </ul>
  </div>
  
  <div id="main">
    <section id="section1">
      <h2>Dataset 1: CQAW Challenge</h2>
      <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit.</p>
    </section>
    
    <section id="section2">
      <h2>Dataset 2: CQAW Challenge</h2>
      <p>Sed do eiusmod tempor incididunt ut labore et dolore magna aliqua.</p>
    </section>
    
    <section id="section3">
      <h2>Dataset 3: CQAW Challenge</h2>
      <p>Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat.</p>
    </section>
  </div>
</body>
</html>


<script type='text/javascript' src='/js/jquery.js'></script>
<script type='text/javascript' src='/js/moment.js'></script>
<script type='text/javascript' src='/js/bibtex.js'></script>

<bibtex src='/papers/pub.bib'></bibtex>

