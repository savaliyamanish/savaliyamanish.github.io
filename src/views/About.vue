<template>
  <div style="margin-bottom: 80px;">
    <div class="hero-section">
      <div class="hero-content">
        <h1 class="hero-title">
            <span class="greeting">Hello, I am</span>
            <span class="name">Manish Savaliya</span>
          </h1>
        <div class="hero-description">
          <p>
              I’m a passionate <strong>Unity Game Developer</strong> with over 8 years of experience creating engaging mobile and PC games. I specialize in gameplay programming, performance optimization, and smooth user experiences that bring ideas to life.
            </p>
          <p class="hero-cta">
            Open to work — feel free to
            <router-link to="/contact" class="contact-link">contact me</router-link>,
            or connect on
            <a class="contact-link" href="https://www.linkedin.com/in/savaliyamanish/" target="_blank" rel="noopener">
              LinkedIn
            </a>.
          </p>
        </div>
      </div>
      <div class="hero-photo">
        <div class="photo-wrapper">
          <div class="photo-border"></div>
          <img :src="`img/avatar.png`" alt="Avatar of Mohit" class="avatar-image" />
          <div class="photo-glow"></div>
        </div>
      </div>
    </div>

    <div class="full-content">
      <h2 id="skills">Skills</h2>

        <div class="skills-grid" role="list" aria-labelledby="skills">
          <!-- Game Development -->
          <div class="skill-category" role="listitem">
            <div class="skill-head">
              <span class="skill-icon" aria-hidden="true">🕹️</span>
              <h3>Game Development</h3>
            </div>
            <ul class="skill-list">
              <li><span class="pill">Unity Engine (C#)</span></li>
              <li><span class="pill">Gameplay programming</span></li>
              <li><span class="pill">Physics, AI, pathfinding (NavMesh)</span></li>
              <li><span class="pill">Animation (Mecanim, blend trees)</span></li>
              <li><span class="pill">Input: mobile · controller · PC</span></li>
              <li><span class="pill">UI/UX (UI Toolkit, UGUI)</span></li>
              <li><span class="pill">Shader Graph (basic)</span></li>
              <li><span class="pill">Scripting & debugging</span></li>
              <li><span class="pill">Multiplayer (Photon, Mirror, Socket.IO)</span></li>
              <li><span class="pill">Optimization & profiling</span></li>
              <li><span class="pill">Addressables & asset bundles</span></li>
              <li><span class="pill">Monetization: IAP & Ads</span></li>
            </ul>
          </div>

          <!-- Game Design -->
          <div class="skill-category" role="listitem">
            <div class="skill-head">
              <span class="skill-icon" aria-hidden="true">🎮</span>
              <h3>Game Design</h3>
            </div>
            <ul class="skill-list">
              <li><span class="pill">Level design & flow</span></li>
              <li><span class="pill">Systems (combat, economy, progression)</span></li>
              <li><span class="pill">Core gameplay loop</span></li>
              <li><span class="pill">Camera & player feedback</span></li>
              <li><span class="pill">Puzzle & mission structure</span></li>
              <li><span class="pill">Rapid prototyping & iteration</span></li>
              <li><span class="pill">Balance & analytics‑driven tuning</span></li>
              <li><span class="pill">Onboarding & retention</span></li>
            </ul>
          </div>

          <!-- Tools -->
          <div class="skill-category" role="listitem">
            <div class="skill-head">
              <span class="skill-icon" aria-hidden="true">🧰</span>
              <h3>Development &amp; Design Tools</h3>
            </div>
            <ul class="skill-list">
              <li><span class="pill">Unity</span></li>
              <li><span class="pill">GitHub</span></li>
              <li><span class="pill">Plastic SCM</span></li>
              <li><span class="pill">Visual Studio Code</span></li>
              <li><span class="pill">Rider</span></li>
              <li><span class="pill">Cursor</span></li>
              <li><span class="pill">Blender</span></li>
              <li><span class="pill">Photoshop</span></li>
              <li><span class="pill">Illustrator</span></li>
              <li><span class="pill">Figma</span></li>
              <li><span class="pill">Trello</span></li>
              <li><span class="pill">Firebase</span></li>
              <li><span class="pill">Unity Analytics</span></li>
              <li><span class="pill">Ads SDKs</span></li>
              <li><span class="pill">Gradle</span></li>
              <li><span class="pill">Xcode</span></li>
              <li><span class="pill">Android Studio</span></li>
            </ul>
          </div>
        </div>
      <h2>Work experience</h2>

      <div class="experience-timeline">
         
        <div class="experience-card">
  <div class="experience-header">
    <div>
      <h3>Senior Game Developer</h3>
      <div class="company-name">Narqubis Games Private Limited</div>
    </div>
    <div class="status-badge current">Current</div>
  </div>
  <div class="experience-meta">
    <span class="date-range">Jan 2023 – Present</span>
    <span class="separator">•</span>
    <span>Full-time</span>
    <span class="separator">•</span>
    <span>Rajkot</span>
  </div>
  <div class="experience-description">
    Working on <strong>NARQUBIS – Mini Battle Royale</strong>, a tactical shooting and resource‑collection game. Responsible for core gameplay systems, combat logic, and performance optimization across mobile and PC. Contributed to multiplayer, UI/UX polish, and monetization systems (IAP & ads) while improving stability and player experience for live updates.
  </div>
  <div class="tech-stack">
  <span class="tech-tag">Unity (C#)</span>
  <span class="tech-tag">Multiplayer (Photon / Socket.IO)</span>
  <span class="tech-tag">Gameplay Systems</span>
  <span class="tech-tag">Combat Mechanics</span>
  <span class="tech-tag">UI/UX Implementation</span>
  <span class="tech-tag">Optimization & Profiling</span>
  <span class="tech-tag">Asset Bundles</span>
  <span class="tech-tag">Monetization (IAP & Ads)</span>
  <span class="tech-tag">Firebase / Analytics</span>
</div>

</div>

 <div class="experience-card">
  <div class="experience-header">
    <div>
      <h3>Senior Game Developer</h3>
      <div class="company-name">Freebird App Studio LLP</div>
    </div>
  </div>
  <div class="experience-meta">
    <span class="date-range">Jan 2016 – Dec 2022</span>
    <span class="separator">•</span>
    <span>Full-time</span>
  </div>
  <div class="experience-description">
    Developed and maintained multiple commercial mobile games from concept to launch. Built core gameplay systems, live-ops tools, and analytics integrations. Collaborated with design, art, and QA teams to deliver polished, high-performance game experiences across various genres and platforms.
  </div>
  <div class="tech-stack">
  <span class="tech-tag">Unity (C#)</span>
  <span class="tech-tag">2D / 3D Game Development</span>
  <span class="tech-tag">Gameplay Systems</span>
  <span class="tech-tag">UI/UX Implementation</span>
  <span class="tech-tag">Animation & Effects</span>
  <span class="tech-tag">Level Design & Tools</span>
  <span class="tech-tag">Asset Bundles & Addressables</span>
  <span class="tech-tag">Audio Integration</span>
  <span class="tech-tag">Firebase / Analytics</span>
  <span class="tech-tag">Monetization (IAP & Ads)</span>
  <span class="tech-tag">Store Integrations (Google Play / App Store)</span>
  <span class="tech-tag">Live-Ops & Remote Config</span>
  <span class="tech-tag">Optimization & Profiling</span>
  <span class="tech-tag">Build Pipeline & Automation</span>
  <span class="tech-tag">Performance Debugging</span>
</div>

</div>
</div>

<h2>Education</h2>

<div class="education-timeline">
  <div class="education-card">
    <div class="education-icon">🎓</div>
    <div class="education-content">
      <h3>Master of Computer Application (MCA)</h3>
      <div class="institution-name">Department of Computer Science, Saurashtra University, Rajkot</div>
      <div class="education-year">March 2016</div>
      <div class="education-description">
        Specialized in software engineering, systems design, and application development.
      </div>
    </div>
  </div>

  <div class="education-card">
    <div class="education-icon">🎯</div>
    <div class="education-content">
      <h3>Bachelor of Computer Application (BCA)</h3>
      <div class="institution-name">Harivandana College, Saurashtra University, Rajkot</div>
      <div class="education-year">March 2014</div>
      <div class="education-description">
        Focused on computer programming, database management, and software development.
      </div>
    </div>
  </div>

  <div class="education-card">
    <div class="education-icon">📘</div>
    <div class="education-content">
      <h3>Higher Secondary Certificate (HSC)</h3>
      <div class="institution-name">Gujarat Secondary and Higher Secondary Education Board</div>
      <div class="education-year">March 2011</div>
      <div class="education-description">
        Completed higher secondary education with a focus on mathematics and computer science.
      </div>
    </div>
  </div>
</div>

      <h2>Languages</h2>

      <div class="languages-grid">
        <div class="language-card">
          <div class="language-icon">🌐</div>
          <div class="language-content">
            <h3>English</h3>
            <div class="proficiency-badge professional">Professional</div>
            <div class="proficiency-text">Professional working proficiency</div>
          </div>
        </div>

        <div class="language-card">
          <div class="language-icon">🗣️</div>
          <div class="language-content">
            <h3>Hindi</h3>
            <div class="proficiency-badge professional">Professional</div>
            <div class="proficiency-text">Professional working proficiency</div>
          </div>
        </div>

        <div class="language-card">
          <div class="language-icon">🏠</div>
          <div class="language-content">
            <h3>Gujarati</h3>
            <div class="proficiency-badge native">Native</div>
            <div class="proficiency-text">Mother tongue</div>
          </div>
        </div>
      </div>
      
      <div class="divider"></div>
      
      <p class="hero-cta">
            <router-link to="/contact" class="contact-link">contact me</router-link>,
            or connect on
            <a class="contact-link" href="https://www.linkedin.com/in/savaliyamanish/" target="_blank" rel="noopener">
              LinkedIn
            </a>.
          </p>
    </div>

  </div>
</template>

<script lang="ts">
import { defineComponent } from "vue";

export default defineComponent({
  name: "AboutView"
});
</script>

<style scoped>
/* Hero Section Styling */
.hero-section {
  display: flex;
  flex-direction: column;
  gap: 40px;
  margin-bottom: 60px;
  padding: 40px 0;
}

@media only screen and (min-width: 768px) {
  .hero-section {
    flex-direction: row;
    align-items: center;
    gap: 60px;
    padding: 60px 0;
  }
}

.hero-content {
  flex: 1;
  max-width: 100%;
}

@media only screen and (min-width: 768px) {
  .hero-content {
    max-width: 600px;
  }
}

.hero-title {
  margin: 0 0 16px 0;
  line-height: 1.2;
  display: flex;
  flex-direction: column;
  gap: 8px;
}

.greeting {
  font-size: 1.5rem;
  font-weight: 400;
  color: rgba(255, 255, 255, 0.7);
  display: block;
}

@media only screen and (min-width: 768px) {
  .greeting {
    font-size: 1.75rem;
  }
}

.name {
  font-size: 2.5rem;
  font-weight: 700;
  color: #fff;
  background: linear-gradient(135deg, #3b82f6 0%, #8b5cf6 100%);
  -webkit-background-clip: text;
  -webkit-text-fill-color: transparent;
  background-clip: text;
  display: block;
}

@media only screen and (min-width: 768px) {
  .name {
    font-size: 3.5rem;
  }
}

.hero-subtitle {
  font-size: 1.25rem;
  color: #3b82f6;
  font-weight: 600;
  margin-bottom: 24px;
  display: inline-block;
  padding: 6px 16px;
  background: rgba(59, 130, 246, 0.1);
  border-radius: 8px;
  border: 1px solid rgba(59, 130, 246, 0.2);
}

.hero-description {
  line-height: 1.8;
  color: rgba(255, 255, 255, 0.85);
  font-size: 1.05rem;
}

.hero-description p {
  margin: 0 0 16px 0;
}

.hero-cta {
  margin-top: 8px;
  color: rgba(255, 255, 255, 0.9);
}

.contact-link {
  color: #3b82f6;
  font-weight: 600;
  text-decoration: underline;
  text-decoration-thickness: 2px;
  text-decoration-color: rgba(96, 165, 250, 0.7);
  transition: all 0.3s ease;
  background: rgba(59, 130, 246, 0.12);
  padding: 2px 6px;
  border-radius: 6px;
}

.contact-link:hover {
  color: #60a5fa;
  text-decoration-color: #60a5fa;
  background: rgba(59, 130, 246, 0.2);
}

/* Hero Contact Info */
.hero-contact-info {
  margin-top: 32px;
  display: flex;
  flex-direction: column;
  gap: 20px;
}

.email-text {
  display: flex;
  align-items: center;
  gap: 8px;
  font-size: 1.05rem;
  color: rgba(255, 255, 255, 0.9);
}

.email-label {
  font-weight: 600;
  color: rgba(255, 255, 255, 0.7);
}

.email-address {
  color: #3b82f6;
  font-weight: 500;
  font-family: monospace;
  letter-spacing: 0.5px;
}

/* Hero Action Buttons */
.hero-action-buttons {
  display: flex;
  gap: 12px;
  flex-wrap: wrap;
}

.action-btn {
  display: inline-flex;
  align-items: center;
  gap: 8px;
  padding: 12px 24px;
  border-radius: 10px;
  font-weight: 600;
  font-size: 1rem;
  text-decoration: none;
  transition: all 0.3s ease;
  border: 2px solid transparent;
  cursor: pointer;
}

.action-btn svg {
  flex-shrink: 0;
  transition: transform 0.3s ease;
}

.action-btn:hover svg {
  transform: translateY(-2px);
}

.linkedin-btn {
  background: linear-gradient(135deg, #0a66c2 0%, #004182 100%);
  color: #fff;
  box-shadow: 0 4px 12px rgba(10, 102, 194, 0.3);
}

.linkedin-btn:hover {
  background: linear-gradient(135deg, #004182 0%, #003d7a 100%);
  transform: translateY(-2px);
  box-shadow: 0 6px 20px rgba(10, 102, 194, 0.4);
}

@media only screen and (min-width: 640px) {
  .hero-contact-info {
    flex-direction: row;
    align-items: center;
    gap: 32px;
  }
}

@media only screen and (max-width: 480px) {
  .email-text {
    flex-direction: column;
    align-items: flex-start;
    gap: 4px;
  }
  
  .hero-action-buttons {
    width: 100%;
  }
  
  .action-btn {
    width: 100%;
    justify-content: center;
  }
}

/* Hero Photo Styling */
.hero-photo {
  display: flex;
  justify-content: center;
  align-items: center;
  flex-shrink: 0;
}

@media only screen and (min-width: 768px) {
  .hero-photo {
    justify-content: flex-end;
  }
}

.photo-wrapper {
  position: relative;
  width: 200px;
  height: 200px;
  border-radius: 50%;
}

@media only screen and (min-width: 768px) {
  .photo-wrapper {
    width: 280px;
    height: 280px;
  }
}

.avatar-image {
  width: 100%;
  height: 100%;
  object-fit: cover;
  border-radius: 50%;
  position: relative;
  z-index: 2;
  border: 4px solid rgba(255, 255, 255, 0.1);
  transition: all 0.4s ease;
}

.photo-wrapper:hover .avatar-image {
  transform: scale(1.05);
  border-color: rgba(59, 130, 246, 0.5);
}

.photo-border {
  position: absolute;
  top: -8px;
  left: -8px;
  right: -8px;
  bottom: -8px;
  border-radius: 50%;
  background: linear-gradient(135deg, #3b82f6, #8b5cf6, #ec4899);
  opacity: 0.3;
  z-index: 1;
  transition: all 0.4s ease;
  animation: rotate 8s linear infinite;
}

@keyframes rotate {
  from {
    transform: rotate(0deg);
  }
  to {
    transform: rotate(360deg);
  }
}

.photo-wrapper:hover .photo-border {
  opacity: 0.6;
  animation-duration: 4s;
}

.photo-glow {
  position: absolute;
  top: 50%;
  left: 50%;
  transform: translate(-50%, -50%);
  width: 120%;
  height: 120%;
  border-radius: 50%;
  background: radial-gradient(circle, rgba(59, 130, 246, 0.2) 0%, transparent 70%);
  z-index: 0;
  opacity: 0;
  transition: opacity 0.4s ease;
}

.photo-wrapper:hover .photo-glow {
  opacity: 1;
}

.full-content h2 { margin-top: 60px; margin-bottom: 24px; }

/* Work Experience Styling */
.experience-timeline {
  display: flex;
  flex-direction: column;
  gap: 24px;
}

.experience-card {
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 12px;
  padding: 28px;
  transition: all 0.3s ease;
  position: relative;
}

.experience-card:hover {
  background: rgba(255, 255, 255, 0.05);
  border-color: rgba(59, 130, 246, 0.3);
  transform: translateX(4px);
}

.experience-card::before {
  content: "";
  position: absolute;
  left: 0;
  top: 0;
  bottom: 0;
  width: 3px;
  background: linear-gradient(to bottom, #3b82f6, transparent);
  border-radius: 12px 0 0 12px;
  opacity: 0;
  transition: opacity 0.3s ease;
}

.experience-card:hover::before {
  opacity: 1;
}

.experience-header {
  display: flex;
  justify-content: space-between;
  align-items: flex-start;
  margin-bottom: 12px;
  gap: 16px;
}

.experience-header h3 {
  font-size: 1.35rem;
  font-weight: 600;
  margin: 0;
  color: rgba(255, 255, 255, 0.95);
}

.company-name {
  font-size: 1.05rem;
  color: #3b82f6;
  margin-top: 4px;
  font-weight: 500;
}

.status-badge {
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  white-space: nowrap;
}

.status-badge.current {
  background: rgba(34, 197, 94, 0.15);
  color: #22c55e;
  border: 1px solid rgba(34, 197, 94, 0.3);
}

.experience-meta {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  font-size: 0.9rem;
  color: rgba(255, 255, 255, 0.6);
  margin-bottom: 16px;
  align-items: center;
}

.date-range {
  font-weight: 500;
  color: rgba(255, 255, 255, 0.75);
}

.separator {
  color: rgba(255, 255, 255, 0.3);
}

.experience-description {
  line-height: 1.7;
  color: rgba(255, 255, 255, 0.85);
  margin-bottom: 16px;
}

.tech-stack {
  display: flex;
  flex-wrap: wrap;
  gap: 8px;
  margin-top: 16px;
}

.tech-tag {
  background: rgba(59, 130, 246, 0.1);
  border: 1px solid rgba(59, 130, 246, 0.2);
  color: #93c5fd;
  padding: 6px 12px;
  border-radius: 6px;
  font-size: 0.85rem;
  font-weight: 500;
  transition: all 0.2s ease;
}

.tech-tag:hover {
  background: rgba(59, 130, 246, 0.15);
  border-color: rgba(59, 130, 246, 0.4);
  transform: translateY(-1px);
}

/* Skills Grid Styling */
.skills-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 24px;
  margin-top: 24px;
}

@media only screen and (min-width: 768px) {
  .skills-grid {
    grid-template-columns: repeat(2, 1fr);
  }
}
.skills-grid { display: grid; grid-template-columns: 1fr; gap: 24px; margin-top: 24px; }
@media only screen and (min-width: 900px) { .skills-grid { grid-template-columns: repeat(3, 1fr); } }
.skill-category { background: rgba(255, 255, 255, 0.03); border: 1px solid rgba(255, 255, 255, 0.08); border-radius: 14px; padding: 22px; transition: all 0.3s ease; }
.skill-category:hover { background: rgba(255, 255, 255, 0.05); border-color: rgba(59, 130, 246, 0.3); transform: translateY(-2px); }
.skill-head { display: flex; align-items: center; gap: 10px; margin-bottom: 12px; }
.skill-icon { font-size: 1.4rem; }
.skill-category h3 { font-size: 1.1rem; font-weight: 700; margin: 0; color: #8fb4ff; letter-spacing: 0.2px; }
.skill-list { list-style: none; margin: 0; padding: 0; display: flex; flex-wrap: wrap; gap: 10px; }
.pill { display: inline-flex; align-items: center; padding: 6px 10px; border-radius: 999px; font-size: 0.88rem; line-height: 1; background: rgba(255,255,255,0.06); border: 1px solid rgba(255,255,255,0.12); color: rgba(255,255,255,0.92); }
.pill:hover { background: rgba(59,130,246,0.14); border-color: rgba(59,130,246,0.35); }
.education-card {
  display: flex;
  gap: 20px;
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 12px;
  padding: 24px;
  transition: all 0.3s ease;
  position: relative;
}

.education-card:hover {
  background: rgba(255, 255, 255, 0.05);
  border-color: rgba(139, 92, 246, 0.3);
  transform: translateY(-2px);
  box-shadow: 0 8px 16px rgba(0, 0, 0, 0.2);
}

.education-icon {
  font-size: 2.5rem;
  display: flex;
  align-items: center;
  justify-content: center;
  min-width: 60px;
  height: 60px;
  background: rgba(139, 92, 246, 0.1);
  border-radius: 12px;
  transition: transform 0.3s ease;
}

.education-card:hover .education-icon {
  transform: scale(1.1) rotate(5deg);
}

.education-content {
  flex: 1;
}

.education-content h3 {
  font-size: 1.25rem;
  font-weight: 600;
  margin: 0 0 8px 0;
  color: rgba(255, 255, 255, 0.95);
}

.institution-name {
  color: #8b5cf6;
  font-weight: 500;
  margin-bottom: 6px;
  font-size: 1rem;
}

.education-year {
  color: rgba(255, 255, 255, 0.6);
  font-size: 0.9rem;
  margin-bottom: 12px;
  font-weight: 500;
}

.education-description {
  line-height: 1.6;
  color: rgba(255, 255, 255, 0.75);
  font-size: 0.95rem;
}

@media only screen and (max-width: 640px) {
  .education-card {
    flex-direction: column;
    align-items: center;
    text-align: center;
  }
  
  .education-icon {
    margin-bottom: 8px;
  }
}

/* Languages Styling */
.languages-grid {
  display: grid;
  grid-template-columns: 1fr;
  gap: 16px;
}

@media only screen and (min-width: 640px) {
  .languages-grid {
    grid-template-columns: repeat(3, 1fr);
  }
}

.language-card {
  background: rgba(255, 255, 255, 0.03);
  border: 1px solid rgba(255, 255, 255, 0.08);
  border-radius: 12px;
  padding: 24px;
  text-align: center;
  transition: all 0.3s ease;
}

.language-card:hover {
  background: rgba(255, 255, 255, 0.05);
  border-color: rgba(236, 72, 153, 0.3);
  transform: translateY(-4px);
  box-shadow: 0 8px 20px rgba(0, 0, 0, 0.2);
}

.language-icon {
  font-size: 3rem;
  margin-bottom: 12px;
  transition: transform 0.3s ease;
}

.language-card:hover .language-icon {
  transform: scale(1.2);
}

.language-content h3 {
  font-size: 1.2rem;
  font-weight: 600;
  margin: 0 0 12px 0;
  color: rgba(255, 255, 255, 0.95);
}

.proficiency-badge {
  display: inline-block;
  padding: 4px 12px;
  border-radius: 20px;
  font-size: 0.8rem;
  font-weight: 600;
  margin-bottom: 8px;
}

.proficiency-badge.professional {
  background: rgba(59, 130, 246, 0.15);
  color: #3b82f6;
  border: 1px solid rgba(59, 130, 246, 0.3);
}

.proficiency-badge.native {
  background: rgba(236, 72, 153, 0.15);
  color: #ec4899;
  border: 1px solid rgba(236, 72, 153, 0.3);
}

.proficiency-text {
  color: rgba(255, 255, 255, 0.6);
  font-size: 0.9rem;
}

.divider { height: 1px; background: rgba(255,255,255,0.08); margin: 32px 0; }
.cta-row { display: flex; gap: 12px; }
.btn-primary { padding: 10px 16px; border-radius: 10px; background: #3b82f6; color: #fff; text-decoration: none; }
.btn-secondary { padding: 10px 16px; border-radius: 10px; background: rgba(255,255,255,0.08); color: #fff; text-decoration: none; }

</style>