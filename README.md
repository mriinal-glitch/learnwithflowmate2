<!DOCTYPE html>
<html lang="en">
<head>
<meta charset="UTF-8" />
<meta name="viewport" content="width=device-width, initial-scale=1.0" />
<title>LearnWithFlowmate - MVP</title>
<style>
  /* Reset some default styles */
  * {
    box-sizing: border-box;
  }

  body {
    font-family: 'Helvetica Neue', Helvetica, Arial, sans-serif;
    margin: 0;
    padding: 0;
    line-height: 1.6;
    color: #333;
    background-color: #fafafa;
  }

  /* Header styles with a vibrant gradient background */
  header {
    background: linear-gradient(135deg, #4CAF50, #81C784);
    color: #fff;
    padding: 40px 20px;
    text-align: center;
  }

  header h1 {
    margin: 0;
    font-size: 2.5em;
    max-width: 800px;
    margin: 0 auto;
  }

  header p {
    margin-top: 15px;
    font-size: 1.3em;
    max-width: 800px;
    margin: 15px auto 0;
  }

  .cta-button {
    background-color: #fff;
    color: #4CAF50;
    padding: 14px 28px;
    border: none;
    border-radius: 25px;
    font-size: 1.2em;
    font-weight: bold;
    cursor: pointer;
    margin-top: 25px;
    display: inline-block;
    box-shadow: 0 4px 15px rgba(0,0,0,0.2);
    transition: background-color 0.3s, transform 0.2s;
    text-decoration: none;
  }

  .cta-button:hover {
    background-color: #e0f2f1;
    transform: translateY(-2px);
  }

  section {
    padding: 50px 20px;
    max-width: 1000px;
    margin: auto;
    background-color: #fff;
    border-radius: 8px;
    box-shadow: 0 4px 15px rgba(0,0,0,0.05);
    margin-top: -20px;
  }

  h2 {
    text-align: center;
    color: #2e7d32;
    font-size: 2em;
    margin-bottom: 20px;
  }

  ul {
    list-style: none;
    padding: 0;
  }

  li {
    margin: 12px 0;
    font-size: 1.2em;
  }

  /* Features grid */
  .features {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 30px;
  }

  .feature {
    flex: 1 1 180px;
    text-align: center;
    margin: 15px;
    padding: 15px;
    background-color: #f1f8e9;
    border-radius: 8px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .feature:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 20px rgba(0,0,0,0.15);
  }

  .feature-icon {
    font-size: 2.5em;
    margin-bottom: 10px;
  }

  /* Learning steps flow */
  .flow-steps {
    display: flex;
    flex-wrap: wrap;
    justify-content: center;
    margin-top: 30px;
  }

  .step {
    background: #e8f5e9;
    padding: 20px;
    border-radius: 8px;
    width: 180px;
    text-align: center;
    margin: 15px;
    box-shadow: 0 2px 8px rgba(0,0,0,0.1);
    transition: transform 0.2s, box-shadow 0.2s;
  }

  .step:hover {
    transform: translateY(-4px);
    box-shadow: 0 4px 20px rgba(0,0,0,0.15);
  }

  footer {
    background-color: #2e7d32;
    color: #fff;
    padding: 25px 20px;
    text-align: center;
    margin-top: 50px;
  }

  /* Responsive adjustments */
  @media(max-width: 768px){
    .features, .flow-steps {
      flex-direction: column;
      align-items: center;
    }
    .feature, .step {
      width: 80%;
    }
  }

  /* Additional styles for heading emphasis */
  .highlight {
    color: #388E3C;
  }
</style>
</head>
<body>

<header>
  <h1>Struggling to Finish Courses? <span class="highlight">We Have a Solution.</span></h1>
  <p>A behaviour-driven platform that keeps you motivated, builds habits, and ensures steady progress.</p>
  <a href="#beta" class="cta-button">Join the Beta</a>
</header>

<section class="problem">
  <h2>Why Do Learners Drop Out?</h2>
  <ul>
    <li><strong>Lack of visible progress</strong></li>
    <li><strong>No accountability or habit formation</strong></li>
    <li><strong>Monotonous learning experience</strong></li>
  </ul>
</section>

<section class="solution">
  <h2>Our Approach: Ladder-Based Learning with Rewards</h2>
  <p>LearnWithFlowmate breaks learning into small steps, tracks habits, and motivates you with nudges and rewards to keep you on track.</p>
  <div class="features">
    <div class="feature">
      <div class="feature-icon">📈</div>
      <div><strong>Visible progress</strong></div>
    </div>
    <div class="feature">
      <div class="feature-icon">✅</div>
      <div><strong>Small step wins</strong></div>
    </div>
    <div class="feature">
      <div class="feature-icon">📅</div>
      <div><strong>Habit tracking</strong></div>
    </div>
    <div class="feature">
      <div class="feature-icon">💡</div>
      <div><strong>Motivation nudges</strong></div>
    </div>
    <div class="feature">
      <div class="feature-icon">🏆</div>
      <div><strong>Rewards & Certification</strong></div>
    </div>
  </div>
</section>

<section class="how">
  <h2>Your Learning Journey in Simple Steps</h2>
  <div class="flow-steps">
    <div class="step">
      <h3>Start at Bottom</h3>
      <p>Build confidence with small wins</p>
    </div>
    <div class="step">
      <h3>Complete Steps</h3>
      <p>Receive feedback & celebrate progress</p>
    </div>
    <div class="step">
      <h3>Track Habits</h3>
      <p>Stay consistent daily</p>
    </div>
    <div class="step">
      <h3>Earn Rewards</h3>
      <p>Get certified & motivated to continue</p>
    </div>
  </div>
</section>

<section>
  <h2 style="text-align:center;">See the Difference</h2>
  <ul style="max-width:600px; margin:auto; list-style:none; padding:0;">
    <li><strong>30-40% higher course completion</strong></li>
    <li><strong>Steady habit formation</strong></li>
    <li><strong>Increased motivation & engagement</strong></li>
  </ul>
</section>

<section style="text-align:center; padding:50px;">
  <p style="font-size:1.3em;">Help us shape the future of learning. Join the beta now!</p>
  <a href="#beta" class="cta-button">Join the Beta</a>
</section>

<footer>
  &copy; 2024 LearnWithFlowmate. All rights reserved.
</footer>

</body>
</html>
