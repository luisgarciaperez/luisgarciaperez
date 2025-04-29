
<!-- ──────────────────────────────────────────────────── -->
<style>
  /* Container */
  .profile-container {
    font-family: -apple-system, BlinkMacSystemFont, "Segoe UI", Helvetica, Arial, sans-serif;
    max-width: 800px;
    margin: auto;
    color: #333;
    line-height: 1.6;
  }
  /* Section titles */
  .profile-section h2 {
    border-bottom: 2px solid #1f6feb;
    padding-bottom: 0.3em;
    margin-top: 2em;
    color: #1f6feb;
  }
  /* Lists */
  .profile-list {
    list-style: none;
    padding: 0;
  }
  .profile-list li {
    margin-bottom: 0.5em;
    padding-left: 1.2em;
    position: relative;
  }
  .profile-list li:before {
    content: "►";
    position: absolute;
    left: 0;
    color: #1f6feb;
  }
  /* Education & experience rows */
  .profile-row {
    display: flex;
    justify-content: space-between;
    margin-bottom: 0.5em;
  }
  .profile-row .institution {
    font-weight: 600;
  }
  .profile-row .dates {
    color: #666;
  }
  /* Skills grid */
  .skills-grid {
    display: grid;
    grid-template-columns: repeat(auto-fit, minmax(180px, 1fr));
    gap: 1em;
  }
  .skill-category {
    background: #f6f8fa;
    padding: 1em;
    border-radius: 6px;
  }
  .skill-category h4 {
    margin-top: 0;
    color: #1f6feb;
  }
</style>

<div class="profile-container">

  <!-- PROFESSIONAL SUMMARY -->
  <div class="profile-section">
    <h2>Professional Summary</h2>
    <p>
      Sound &amp; Image engineer with a strong interest in emerging technology trends (Machine Learning, AI, Cloud…). 
      Versatile and adaptable, applying a multidisciplinary approach to projects by combining technical knowledge, creativity, and Design Thinking. 
      Seeking a junior role in Data Science.
    </p>
    <p>
      Eager to work both independently and within teams. Background in telecommunications (physics, mathematics, statistics, programming, signal processing, computer science), 
      with a specialization in digital sound processing, auralization, video systems, noise control, and sound design.
    </p>
  </div>

  <!-- EDUCATION -->
  <div class="profile-section">
    <h2>Education</h2>
    <div class="profile-row">
      <span class="institution">Universidad Carlos III de Madrid</span>
      <span class="dates">Sep 2018 – Mar 2024</span>
    </div>
    <p>BSc in Sound and Image Engineering</p>
    <div class="profile-row">
      <span class="institution">IE University</span>
      <span class="dates">Apr 2024 – Mar 2025</span>
    </div>
    <p>MSc in Business Analytics &amp; Data Science<br>
      <em>Concentration:</em> Advanced AI<br>
      <em>Advanced Tech Track Program</em>
    </p>
  </div>

  <!-- PROFESSIONAL EXPERIENCE -->
  <div class="profile-section">
    <h2>Professional Experience</h2>
    <div class="profile-row">
      <span class="institution">Deloitte (Intern – Communication)</span>
      <span class="dates">Nov 2022 – Jun 2023</span>
    </div>
    <ul class="profile-list">
      <li>Produced, composed, edited, and mixed music and sound for internal audiovisuals.</li>
      <li>Provided technical supervision for live streaming events.</li>
    </ul>
  </div>

  <!-- LANGUAGES -->
  <div class="profile-section">
    <h2>Languages</h2>
    <ul class="profile-list">
      <li>English (C2)</li>
      <li>Spanish (Native)</li>
      <li>German (A1)</li>
    </ul>
  </div>

  <!-- TECHNICAL SKILLS -->
  <div class="profile-section">
    <h2>Technical Skills</h2>
    <div class="skills-grid">
      <div class="skill-category">
        <h4>Data Science &amp; AI</h4>
        <p>Python, scikit-learn, Skforecast, PyTorch, TensorFlow, Streamlit, Tableau, Looker</p>
      </div>
      <div class="skill-category">
        <h4>Cloud &amp; Data</h4>
        <p>AWS, Azure, SQL, NiFi, HDFS, Spark</p>
      </div>
      <div class="skill-category">
        <h4>Development</h4>
        <p>Git, HTML, CSS, React, Xcode, Android Studio, Swift, Java</p>
      </div>
      <div class="skill-category">
        <h4>Audio &amp; Video</h4>
        <p>MATLAB, Logic Pro X, Final Cut Pro, EASE 4.0</p>
      </div>
    </div>
  </div>

  <!-- OTHER INFORMATION -->
  <div class="profile-section">
    <h2>Other Interests</h2>
    <ul class="profile-list">
      <li>18+ years of piano study</li>
      <li>Enthusiast of music, film, TV, and sports</li>
    </ul>
  </div>

</div>
