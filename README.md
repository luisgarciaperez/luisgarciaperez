<!-- ──────────────────────────────────────────────────── -->
<style>
  .profile-container {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    max-width: 700px;
    margin: 2rem auto;
    padding: 1.5rem;
    background: linear-gradient(145deg, #f0f4ff, #ffffff);
    border-radius: 12px;
    box-shadow: 0 8px 24px rgba(0, 0, 0, 0.05);
    color: #1a1a1a;
    line-height: 1.6;
  }
  .profile-header {
    text-align: center;
    margin-bottom: 2rem;
  }
  .profile-header h1 {
    margin: 0;
    font-size: 2.2rem;
    background: -webkit-linear-gradient(45deg, #1f6feb, #ff5e62);
    -webkit-background-clip: text;
    -webkit-text-fill-color: transparent;
  }
  .profile-header p {
    margin: 0.5rem 0 0;
    font-style: italic;
    color: #555;
  }
  .skill-badge {
    display: inline-block;
    margin: 0.3rem;
    padding: 0.5rem 0.8rem;
    font-size: 0.9rem;
    border-radius: 20px;
    background: #e6f0ff;
    background-image: linear-gradient(135deg, rgba(255,94,98,0.1), rgba(31,111,235,0.1));
    color: #1f6feb;
    transition: transform 0.2s ease;
  }
  .skill-badge:hover {
    transform: scale(1.1);
    background-image: linear-gradient(135deg, rgba(255,94,98,0.2), rgba(31,111,235,0.2));
  }
  .section {
    margin-bottom: 2rem;
  }
  .section h2 {
    position: relative;
    font-size: 1.4rem;
    margin-bottom: 1rem;
  }
  .section h2:after {
    content: "";
    position: absolute;
    bottom: 0;
    left: 0;
    width: 3rem;
    height: 3px;
    background: linear-gradient(90deg, #ff5e62, #1f6feb);
  }
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(140px, 1fr));
    gap: 1rem;
  }
  .skill-category {
    padding: 1rem;
    border-radius: 8px;
    background: #fff;
    box-shadow: 0 4px 12px rgba(0, 0, 0, 0.03);
    transition: box-shadow 0.2s ease;
  }
  .skill-category:hover {
    box-shadow: 0 6px 20px rgba(0, 0, 0, 0.06);
  }
  .skill-category h3 {
    margin-top: 0;
    font-size: 1.1rem;
    color: #ff5e62;
  }
  .skill-category p {
    margin: 0.5rem 0 0;
    font-size: 0.9rem;
  }
</style>

<div class="profile-container">

  <div class="profile-header">
    <h1>Data &amp; AI Enthusiast</h1>
    <p>Specialized in ML, Cloud &amp; Full-Stack Prototyping</p>
  </div>

  <div class="section">
    <h2>Core Strengths</h2>
    <p>
      Multidisciplinary engineer with hands-on expertise in data modeling, machine learning pipelines, cloud architectures, and UI/UX prototyping. 
      Expert at translating open-ended challenges into scalable, production-ready solutions.
    </p>
  </div>

  <div class="section">
    <h2>Highlighted Skills</h2>
    <div class="skills-grid">
      <div class="skill-category">
        <h3>Data Science &amp; AI</h3>
        <p>Python • scikit-learn • TensorFlow • PyTorch • Streamlit</p>
      </div>
      <div class="skill-category">
        <h3>Data Platforms</h3>
        <p>AWS • Azure • SQL • Spark • NiFi • HDFS</p>
      </div>
      <div class="skill-category">
        <h3>Web &amp; Frontend</h3>
        <p>JavaScript • TypeScript • React • HTML &amp; CSS</p>
      </div>
      <div class="skill-category">
        <h3>Infra &amp; DevOps</h3>
        <p>Docker • Kubernetes • Terraform • GitHub Actions</p>
      </div>
      <div class="skill-category">
        <h3>Audio &amp; Video</h3>
        <p>MATLAB • Logic Pro X • Final Cut Pro</p>
      </div>
    </div>
  </div>

  <div class="section">
    <h2>Language Proficiency</h2>
    <p>
      <span class="skill-badge">Spanish (Native)</span>
      <span class="skill-badge">English (C2)</span>
      <span class="skill-badge">German (A1)</span>
    </p>
  </div>

</div>
