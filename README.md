<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Daniel Mejía Valencia | Home</title>
  <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.0/css/all.min.css">
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #ffffff;
      color: #2c3e50;
      text-align: center;
      padding: 80px 20px;
    }
    h1 {
      font-size: 36px;
      font-weight: 700;
      margin-bottom: 15px;
    }
    h2 {
      font-size: 22px;
      font-weight: 500;
      margin-bottom: 30px;
    }
    .clickable {
      color: #0366d6;
      font-weight: 600;
      cursor: pointer;
      text-decoration: none;
    }
    .clickable:hover {
      text-decoration: underline;
    }
    .icons a {
      margin: 0 15px;
      font-size: 28px;
      color: #0366d6;
      text-decoration: none;
    }
    .icons a:hover {
      color: #023e7d;
    }
    .hidden-section {
      display: none;
      max-width: 800px;
      margin: 40px auto;
      text-align: left;
      background-color: #f9f9f9;
      padding: 25px 30px;
      border-radius: 10px;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.08);
      font-size: 16px;
      line-height: 1.6;
    }
    section h4 {
      margin-bottom: 10px;
    }
    section a {
      color: #0366d6;
      font-weight: 600;
      text-decoration: none;
    }
    section a:hover {
      text-decoration: underline;
    }
  </style>
</head>
<body>

  <h1>Daniel Mejía Valencia</h1>
  <h2>
    <span class="clickable" onclick="toggleSection('details')">Financial Engineer</span> |
    <span class="clickable" onclick="toggleSection('projects')">Portfolio</span> |
    <span class="clickable" onclick="toggleSection('resume')">Resume</span> |
    <span class="clickable" onclick="toggleSection('courses')">Courses</span>
  </h2>

  <div class="icons">
    <a href="https://github.com/Danielmejiava" target="_blank"><i class="fab fa-github"></i></a>
    <a href="https://linkedin.com/in/danielmejiava" target="_blank"><i class="fab fa-linkedin"></i></a>
  </div>

  <!-- Financial Engineer Section -->
  <div id="details" class="hidden-section">
    <h3>Occupational Profile</h3>
    <p>The field of action for a Financial Engineer spans all sectors of the economy — including production, mining, banking, financial services, consulting, and more. A Financial Engineer may professionally develop in the following roles:</p>
    <ul>
      <li>Financial management analyst in public and private companies</li>
      <li>Financial analyst in brokerage firms, banks, money desks, cooperatives, and fiduciary entities</li>
      <li>Financial Manager</li>
      <li>Risk Control Manager</li>
      <li>Stock Market Analyst</li>
      <li>Researcher in the finance or insurance sector</li>
      <li>Risk and market strategy analyst</li>
    </ul>

    <h3>Knowledge Areas</h3>
    <ul>
      <li><strong>Broad Field:</strong> Business Administration and Law</li>
      <li><strong>Specific Field:</strong> Business and Commercial Education</li>
      <li><strong>Detailed Field:</strong> Financial Management, Banking, and Insurance Administration</li>
    </ul>
  </div>

  <!-- Portfolio Section -->
  <section id="projects" class="hidden-section">
    <h3>📈 Projects</h3>

    <div>
      <h4>Portfolio Optimization (Markowitz Portfolio)</h4>
      <p>Constructed and analyzed an investment portfolio using Python, calculating returns, risks, and the Sharpe ratio based on the Markowitz portfolio theory.</p>
      <a href="https://colab.research.google.com/drive/1Lh_qpPVOi8x8PykRFM3MEGWzIOGXqI7c?usp=sharing" target="_blank">🚀 Open in Google Colab</a><br>
      <a href="https://github.com/Danielmejiava/PortfolioOptimization" target="_blank">📁 View on GitHub</a>
    </div>

    <div>
      <h4>Analysis of Temporary Student Visas in Australia</h4>
      <p>Analysed trends in student visa arrivals and departures using Python and public data.</p>
      <a href="https://colab.research.google.com/github/Danielmejiava/danielmejiava.github.io/blob/main/studentVisaArDp.ipynb" target="_blank">🚀 Open in Google Colab</a><br>
      <a href="https://github.com/Danielmejiava/danielmejiava.github.io/blob/main/studentVisaArDp.ipynb" target="_blank">📁 View on GitHub</a>
    </div>

    <div>
      <h4>Employment Trends in Greater Brisbane</h4>
      <p>Explores gender participation in full-time and part-time employment trends over time.</p>
      <a href="https://colab.research.google.com/drive/1S84N8RXXXtB9uBbNPcMaP6k3xBp7cIJF?usp=sharing" target="_blank">🚀 Open in Google Colab</a><br>
      <a href="https://github.com/Danielmejiava/danielmejiava.github.io/blob/main/WorkforceBrisbane.ipynb" target="_blank">📁 View on GitHub</a>
    </div>

    <div>
      <h4>Repayment Progress vs Total Principal (Colombia)</h4>
      <p>Scatterplot analysis to evaluate loan repayments and identify key outliers.</p>
      <a href="https://colab.research.google.com/drive/1Eoxe1HY1MP9OlX026hzsxC-JIhgK7fsB?usp=sharing" target="_blank">🚀 Open in Google Colab</a><br>
      <a href="https://github.com/Danielmejiava/danielmejiava.github.io/blob/main/repaymentProgressCol.ipynb" target="_blank">📁 View on GitHub</a>
    </div>
  </section>

  <!-- Resume Section -->
  <section id="resume" class="hidden-section">
    <h3>🧑‍💼 Resume</h3>
    <p><strong>Profile:</strong> Data-driven professional with experience in cost analysis, forecasting, and production efficiency. Skilled in Python, SQL, and data mining, with knowledge in stochastic modelling, financial derivatives, and investment portfolios.</p>

    <h4>Technical Skills</h4>
    <ul>
      <li><strong>Programming:</strong> Python, SQL</li>
      <li><strong>Libraries:</strong> Pandas, Numpy, Matplotlib, Scikit-learn, Excel, Google Colab</li>
      <li><strong>Tools:</strong> Jupyter Notebooks</li>
      <li><strong>Techniques:</strong> Forecasting, Cost Analysis, Portfolio Optimization</li>
      <li><strong>Soft Skills:</strong> Communication, Teamwork, Critical Thinking, Emotional Intelligence</li>
    </ul>

    <h4>Work Experience</h4>
    <p><strong>Freelancer (2019–2021):</strong> Worked with companies like MAQUISER, APL, and NETSTAK to apply programming, forecasting, and data analysis methods to improve business outcomes.</p>

    <p><strong>Unico Interior S.A.S (2017–2019):</strong> Roles in cost analysis and supply management, including budgeting, time optimisation, and operational decision support.</p>

    <p><strong>APL Servicios (2014–2017):</strong> Led data-driven costing implementations and analysis in production systems.</p>
  </section>

  <!-- Courses Section -->
  <section id="courses" class="hidden-section">
    <h3>🎓 Courses</h3>
    <ul>
      <li><a href="https://www.coursera.org/account/accomplishments/verify/CCSOK2FXZEVK" target="_blank">Databases and SQL for Data Science with Python – IBM (Jan 2025)</a></li>
      <li><a href="https://www.coursera.org/account/accomplishments/verify/ZJSLY3NHNGY9" target="_blank">Applied Data Science with Python – University of Michigan (Feb 2025)</a></li>
      <li><a href="https://www.coursera.org/account/accomplishments/verify/9C4HEN8XYUZC" target="_blank">Financial Engineering and Risk Management – Columbia University (Mar 2025)</a></li>
    </ul>
  </section>

  <script>
    function toggleSection(id) {
      const section = document.getElementById(id);
      section.style.display = section.style.display === 'none' || section.style.display === '' ? 'block' : 'none';
    }
  </script>

</body>
</html>
