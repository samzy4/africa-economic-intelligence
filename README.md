# africa-economic-intelligence
An open source economics platform focused on African and the world,providing economics data, market insight and the tools to help people understand economics trends and make better decisions

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <meta name="description" content="Building practical technology and economic solutions for Africa and the world.">
  <title>OpenBridge | Building Economic Solutions</title>

  <style>
    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: Arial, sans-serif;
      background: #f5f7fb;
      color: #172033;
      line-height: 1.6;
    }

    header {
      background: #10233f;
      color: white;
      padding: 20px 8%;
      display: flex;
      justify-content: space-between;
      align-items: center;
      flex-wrap: wrap;
      gap: 12px;
    }

    .logo {
      font-size: 26px;
      font-weight: bold;
      color: #55ddb0;
    }

    nav a {
      color: white;
      text-decoration: none;
      margin-left: 18px;
      font-size: 14px;
    }

    .hero {
      background: linear-gradient(135deg, #10233f, #145b62);
      color: white;
      padding: 90px 8%;
      text-align: center;
    }

    .hero h1 {
      font-size: clamp(34px, 6vw, 56px);
      line-height: 1.15;
      margin-bottom: 22px;
    }

    .hero p {
      max-width: 680px;
      margin: 0 auto 28px;
      color: #e0ebf5;
      font-size: 18px;
    }

    .button {
      display: inline-block;
      background: #55ddb0;
      color: #10233f;
      padding: 13px 24px;
      border-radius: 7px;
      text-decoration: none;
      font-weight: bold;
    }

    section {
      padding: 65px 8%;
    }

    .section-title {
      text-align: center;
      font-size: 32px;
      margin-bottom: 15px;
    }

    .section-intro {
      text-align: center;
      max-width: 700px;
      margin: 0 auto 35px;
      color: #586579;
    }

    .cards {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(220px, 1fr));
      gap: 22px;
    }

    .card {
      background: white;
      padding: 28px;
      border-radius: 12px;
      border: 1px solid #e4e9f0;
      box-shadow: 0 5px 20px rgba(16, 35, 63, 0.05);
    }

    .card h3 {
      color: #145b62;
      margin-bottom: 12px;
    }

    .card p {
      color: #586579;
      font-size: 15px;
    }

    .mission {
      background: white;
      text-align: center;
    }

    .mission p {
      max-width: 800px;
      margin: 15px auto;
      color: #586579;
    }

    .contact {
      text-align: center;
      background: #eaf4f3;
    }

    footer {
      background: #10233f;
      color: #d5dfeb;
      text-align: center;
      padding: 25px 8%;
      font-size: 14px;
    }

    @media (max-width: 600px) {
      header {
        justify-content: center;
        text-align: center;
      }

      nav a {
        margin: 0 7px;
      }

      .hero {
        padding: 65px 6%;
      }

      section {
        padding: 48px 6%;
      }
    }
  </style>
</head>

<body>

  <header>
    <div class="logo">OpenBridge</div>
    <nav>
      <a href="#home">Home</a>
      <a href="#solutions">Solutions</a>
      <a href="#mission">Our Mission</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <main>
    <section class="hero" id="home">
      <h1>Building Solutions.<br>Connecting Opportunities.</h1>
      <p>
        OpenBridge is an emerging technology initiative focused on
        practical economic solutions, digital tools, and opportunities
        that help people and businesses grow across Africa and beyond.
      </p>
      <a class="button" href="#solutions">Explore Our Vision</a>
    </section>

    <section id="solutions">
      <h2 class="section-title">What We Aim to Build</h2>
      <p class="section-intro">
        Our vision is to develop useful, accessible tools that solve
        real problems for individuals, businesses, and communities.
      </p>

      <div class="cards">
        <div class="card">
          <h3>Business Technology</h3>
          <p>
            Simple digital tools to help businesses organize information,
            save time, improve customer service, and work more efficiently.
          </p>
        </div>

        <div class="card">
          <h3>Economic Opportunities</h3>
          <p>
            Connect people with useful knowledge, business opportunities,
            practical resources, and ideas for sustainable growth.
          </p>
        </div>

        <div class="card">
          <h3>AI and Automation</h3>
          <p>
            Explore affordable ways to automate repetitive tasks,
            organize data, and make everyday work easier.
          </p>
        </div>

        <div class="card">
          <h3>Digital Finance and Data</h3>
          <p>
            Develop responsible data tools and educational resources
            that help people understand information and make better decisions.
          </p>
        </div>
      </div>
    </section>

    <section class="mission" id="mission">
      <h2 class="section-title">Our Mission</h2>
      <p>
        We believe useful technology should not be limited to people
        with large budgets. Our mission is to start small, solve real
        problems, and build solutions that can grow from Africa to the world.
      </p>
      <p>
        We are starting with accessible tools, learning through practical
        projects, and working toward solutions that create measurable value.
      </p>
    </section>

    <section class="contact" id="contact">
      <h2 class="section-title">The Journey Starts Here</h2>
      <p class="section-intro">
        OpenBridge is at the beginning of its journey. We welcome ideas
        that can help us understand real problems and build useful solutions.
      </p>
      <a class="button" href="mailto:YOUR_EMAIL@example.com">
        Contact Our Team
      </a>
    </section>
  </main>

  <footer>
    <p>OpenBridge | Building for Africa and the World</p>
    <p>© 2026 OpenBridge. Building step by step.</p>
  </footer>

</body>
</html>
