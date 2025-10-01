---
layout: page
title: Experience
permalink: /experience/
---

<style>
/* Hero Section */
.experience-hero {
  text-align: center;
  padding: 3rem 1rem;
  background: linear-gradient(135deg, #1b263b, #415a77, #778da9);
  color: #fff;
  border-radius: 1rem;
  margin-bottom: 3rem;
  box-shadow: 0 6px 20px rgba(0,0,0,0.2);
}
.experience-hero h1 {
  font-size: 2.8rem;
  margin-bottom: 0.5rem;
}
.experience-hero p {
  font-size: 1.2rem;
  opacity: 0.95;
}

/* Timeline Layout */
.bubble-timeline {
  position: relative;
  margin: 0 auto;
  padding-left: 50px;
  max-width: 900px;
}
.timeline-line {
  position: absolute;
  top: 0;
  bottom: 0;
  left: 25px;
  width: 4px;
  background: #ccc;
  border-radius: 2px;
}

/* Experience Bubbles */
.experience-bubble {
  position: relative;
  margin-bottom: 3rem;
  animation: fadeInUp 0.8s ease;
}
.experience-bubble::before {
  content: attr(data-year);
  position: absolute;
  left: -70px;
  top: 25px;
  font-weight: bold;
  font-size: 1.1rem;
  color: #415a77;
}

/* Card Styling */
.bubble-content {
  background: #fff;
  padding: 1.75rem;
  border-radius: 1rem;
  box-shadow: 0 4px 14px rgba(0,0,0,0.1);
  transition: transform 0.3s ease, box-shadow 0.3s ease;
}
.bubble-content:hover {
  transform: translateX(10px);
  box-shadow: 0 6px 20px rgba(0,0,0,0.15);
}

/* Header Section */
.bubble-header {
  display: flex;
  align-items: center;
  margin-bottom: 1rem;
}
.bubble-icon {
  width: 55px;
  height: 55px;
  background: #e0e5ec;
  color: #1b263b;
  display: flex;
  align-items: center;
  justify-content: center;
  border-radius: 50%;
  margin-right: 1rem;
  font-size: 1.5rem;
}
.bubble-title h3 {
  margin: 0;
  font-size: 1.3rem;
  color: #1b263b;
}
.bubble-title .company {
  display: block;
  font-weight: 600;
  color: #415a77;
}
.bubble-title .duration {
  display: block;
  font-size: 0.9rem;
  color: #6c757d;
}

/* Achievements */
.bubble-body {
  display: flex;
  flex-wrap: wrap;
  gap: 0.75rem;
}
.achievement-bubble {
  display: flex;
  align-items: center;
  gap: 0.5rem;
  background: #f8f9fa;
  padding: 0.6rem 1rem;
  border-radius: 999px;
  font-size: 0.95rem;
  color: #1b263b;
  transition: background 0.3s, transform 0.2s;
}
.achievement-bubble i {
  color: #415a77;
}
.achievement-bubble:hover {
  background: #e9ecef;
  transform: scale(1.05);
}

/* Animation */
@keyframes fadeInUp {
  from {opacity: 0; transform: translateY(30px);}
  to {opacity: 1; transform: translateY(0);}
}

/* Responsive */
@media (max-width: 768px) {
  .bubble-timeline {
    padding-left: 30px;
  }
  .experience-bubble::before {
    left: -50px;
    font-size: 0.95rem;
  }
  .bubble-title h3 {
    font-size: 1.1rem;
  }
}
</style>

<div class="experience-hero">
  <h1>My Journey</h1>
  <p>Building security solutions and leading teams across diverse industries</p>
</div>

<div class="bubble-timeline">
  <div class="timeline-line"></div>
  
  <!-- 2025 -->
  <div class="experience-bubble current" data-year="2025">
    <div class="bubble-content">
      <div class="bubble-header">
        <div class="bubble-icon"><i class="fas fa-shield-alt"></i></div>
        <div class="bubble-title">
          <h3>Information Security Engineer Intern</h3>
          <span class="company">CIBC US</span>
          <span class="duration">Summer 2025</span>
        </div>
      </div>
      <div class="bubble-body">
        <div class="achievement-bubble"><i class="fas fa-robot"></i> AI & Automation: $50K+ savings</div>
        <div class="achievement-bubble"><i class="fas fa-check-circle"></i> GRC Compliance: NIST 2.0</div>
        <div class="achievement-bubble"><i class="fas fa-chart-line"></i> NYDFS Automation: 150hrs saved</div>
        <div class="achievement-bubble"><i class="fas fa-brain"></i> AI Risk Management: $25K saved</div>
      </div>
    </div>
  </div>

  <!-- 2024 -->
  <div class="experience-bubble" data-year="2024">
    <div class="bubble-content">
      <div class="bubble-header">
        <div class="bubble-icon"><i class="fas fa-chalkboard-teacher"></i></div>
        <div class="bubble-title">
          <h3>Cyber Security Instructor</h3>
          <span class="company">Comtech Telecommunications Inc.</span>
          <span class="duration">Summer 2024</span>
        </div>
      </div>
      <div class="bubble-body
