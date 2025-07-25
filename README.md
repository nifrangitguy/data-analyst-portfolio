# data-analyst-portfolio
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Data Analyst Portfolio</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      margin: 0;
      padding: 0;
      background: linear-gradient(135deg, #e0eafc, #cfdef3);
      color: #333;
    }
    header {
      background: #0f2027;
      background: linear-gradient(to right, #2c5364, #203a43, #0f2027);
      color: white;
      padding: 2rem;
      text-align: center;
    }
    nav a {
      color: #ddd;
      margin: 0 1rem;
      text-decoration: none;
    }
    section {
      padding: 2rem;
      max-width: 1000px;
      margin: auto;
    }
    h2 {
      color: #203a43;
    }
    .project, .skill {
      background: white;
      border-radius: 10px;
      padding: 1.5rem;
      margin-bottom: 1.5rem;
      box-shadow: 0 4px 10px rgba(0,0,0,0.1);
    }
    footer {
      text-align: center;
      background: #203a43;
      color: white;
      padding: 1rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Data Analyst Portfolio</h1>
    <p>Projects | Skills | Experience | Healthcare & Finance Analytics</p>
    <nav>
      <a href="#about">About</a>
      <a href="#skills">Skills</a>
      <a href="#projects">Projects</a>
    </nav>
  </header>

  <section id="about">
    <h2>About Me</h2>
    <p>I'm a passionate problem-solver with a strong ability to understand data beyond the surface. I specialize in uncovering insights and translating them into meaningful, actionable visuals using Power BI, SQL, and Python. Whether it's automating tasks or identifying inefficiencies, I drive clarity and better decision-making.</p>
  </section>

  <section id="skills">
    <h2>Skills & Tools</h2>
    <div class="skill">
      <ul>
        <li>Python (pandas, Prophet)</li>
        <li>Power BI & DAX</li>
        <li>SQL (Data querying & transformations)</li>
        <li>Data Cleaning & Automation</li>
        <li>Time Series Forecasting</li>
        <li>Visualization & Dashboards</li>
      </ul>
    </div>
  </section>

  <section id="projects">
    <h2>Projects</h2>

    <div class="project">
      <h3>IBM Stock Forecasting with Prophet</h3>
      <p>This project applies advanced time series forecasting on IBM’s historical stock closing prices using the Prophet library. It includes two core analyses:</p>
      <ol>
        <li>Long-Term Monthly Forecasting (10 years)</li>
        <li>Short-Term Daily Forecasting with Weekly Seasonality (6 months)</li>
      </ol>
      <p>Together, these models uncover both macro-level trends and micro-level seasonal patterns in IBM’s stock behavior.</p>
    </div>

    <div class="project">
      <h3>IBM Stock Performance Analysis</h3>
      <p>Used classification with bar and pie charts to evaluate IBM’s stock performance based on absolute thresholds and average-based categorization. Helped interpret consistency and trend direction.</p>
    </div>

    <div class="project">
      <h3>SA Health – Contract Forecasting (Power BI)</h3>
      <p>Developed interactive Power BI dashboards to forecast price indices in healthcare procurement. Integrated time series forecasting with 90% confidence intervals for budgeting and vendor negotiations.</p>
    </div>

    <div class="project">
      <h3>Inactive Items Forecast – SA Health</h3>
      <p>Forecasted trends in inactive items using time series models. Analyzed procurement inefficiencies and supported catalog rationalization strategies with seasonality analysis.</p>
    </div>

    <div class="project">
      <h3>Data Cleaning Automation – HCA Healthcare</h3>
      <p>Built a Python pipeline to clean and classify healthcare spend data. Reduced processing time from hours to seconds and ensured scalable, traceable data preparation across 20+ suppliers.</p>
    </div>
  </section>

  <footer>
    <p>Connect on LinkedIn | GitHub | Email</p>
  </footer>
</body>
</html>
