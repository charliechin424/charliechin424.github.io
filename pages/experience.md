---
layout: default
title: Experience
permalink: /experience/
---

<style>
/* Experience Page Specific Styles */

.experience-container {
  max-width: 1300px;
  margin: 3rem auto 0 auto;
  padding: 0 2rem;
  display: grid;
  grid-template-columns: 280px 1fr;
  /* gap: 3rem; */
}

.experience-sidebar {
  background: white;
  border-radius: 12px;
  padding: 2rem;
  height: fit-content;
  position: sticky;
  top: 120px;
}

.sidebar-profile-pic {
  width: 150px;
  height: 150px;
  border-radius: 20%;
  object-fit: cover;
  display: block;
  margin: 0 auto; /* 水平置中 */
}

.sidebar-profile-name {
  font-size: 1.1rem;
  font-weight: 600;
  margin-bottom: 0.5rem;
  color: #2c3e50;
  font-family: 'Georgia', 'Times New Roman', serif;
}

.sidebar-profile-title {
  color: #666;
  margin-bottom: 2rem;
  font-size: 0.95rem;
  line-height: 1.5;
}

.sidebar-contact-info {
  list-style: none;
  padding: 0;
}

.sidebar-contact-info li {
  margin-bottom: 0.8rem;
  font-size: 0.9rem;
  color: #666;
}

.sidebar-contact-info i {
  width: 20px;
  margin-right: 0.5rem;
  color: #666;
}

.sidebar-contact-info a {
  color: #666;
  text-decoration: none;
}

.sidebar-contact-info a:hover {
  text-decoration: underline;
}

.experience-content {
  background: white;
  border-radius: 12px;
}

.experience-content-header {
  background: #6c757d;
  color: white;
  padding: 1.5rem 2rem;
  border-radius: 12px 12px 0 0;
}

.experience-section-nav {
  background: #f8f9fa;
  padding: 1rem 2rem;
  border-bottom: 1px solid #e9ecef;
}

.experience-section-nav ul {
  list-style: none;
  display: flex;
  gap: 2rem;
  margin: 0;
  padding: 0;
}

.experience-section-nav a {
  text-decoration: none;
  color: #666;
  font-weight: 500;
  padding: 0.5rem 0;
  border-bottom: 2px solid transparent;
  transition: all 0.3s ease;
  cursor: pointer;
}

.experience-section-nav a.active {
  color: #007bff;
  border-bottom-color: #007bff;
}

.experience-section-nav a:hover:not(.active) {
  color: #007bff;
  opacity: 0.7;
}

.experience-section {
  display: none;
  /* padding: 2rem; */
}

.experience-section.active {
  display: block;
}

.experience-section-title {
  font-size: 1.8rem;
  font-weight: 600;
  margin-bottom: 2rem;
  color: #2c3e50;
}

.experience-header {
  margin-bottom: 1rem;
}

.position-title {
  color: #007bff;
  font-weight: 600;
  font-size: 1.2rem;
  margin-bottom: 0.5rem;
}

.company-info {
  color: #666;
  font-style: italic;
  margin-bottom: 0.5rem;
}

.duration {
  color: #28a745;
  font-weight: 500;
  font-size: 0.9rem;
}

.experience-description {
  color: #555;
  line-height: 1.6;
}

ul {
    padding-left: 20px; /* 保持縮排 */
    margin: 0; /* 拿掉不必要的上下外距 */
}

.experience-description ul {
  margin-left: 1.5rem;
  margin-top: 0.5rem;
}

.experience-description li {
  margin-bottom: 0.5rem;
}

/* Teaching Experience specific styles */
.course-title {
  color: #000102fb;
  font-weight: 600;
  font-size: 1.1rem;
  margin-bottom: 0.3rem;
}

.course-code {
  color: #28a745;
  font-weight: 500;
  font-size: 0.9rem;
  margin-bottom: 0.3rem;
}

.semester {
  color: #6c757d;
  font-size: 0.9rem;
  margin-bottom: 0.5rem;
}

.responsibilities {
  margin-top: 0.5rem;
}

/* Responsive Design */
@media (max-width: 768px) {
  .experience-container {
    grid-template-columns: 1fr;
    gap: 2rem;
  }

  .experience-sidebar {
    position: static;
  }

  .hero-title {
    font-size: 2rem;
  }

  .experience-section-nav ul {
    flex-direction: column;
    gap: 0.5rem;
  }
}
</style>

<!-- Main Container -->
<div class="experience-container">
  <!-- Sidebar -->
  <aside class="experience-sidebar">
    <img src="{{ site.baseurl }}/assets/img/profile.png" alt="Profile photo" class="sidebar-profile-pic">
    <h3 class="sidebar-profile-name">Chia-Yi (Charlie) Chin</h3>
    <p class="sidebar-profile-title">Undergraduate student at National Taiwan University, specializing in Hardware & Software Co-Design for ML Accelerators, ASIC/FPGA VLSI Circuit Design, Distributed Computing for LLM Systems</p>
    
    <ul class="sidebar-contact-info">
      <li><i class="fa-solid fa-building"></i> {{ site.author.employer }}</li>
      <li><i class="fa-solid fa-location-dot"></i> {{ site.author.location }}</li>
      <li><i class="fa-solid fa-envelope"></i> <a href="mailto:{{ site.author.email }}">{{ site.author.email }}</a></li>
      <li><i class="fa-brands fa-github"></i> <a href="https://github.com/{{ site.author.github }}">GitHub</a></li>
      <li><i class="fa-brands fa-linkedin"></i> <a href="{{ site.author.linkedin }}">LinkedIn</a></li>
    </ul>
  </aside>

  <!-- Main Content -->
  <main class="experience-content">
    <div class="experience-content-header">
      <h2><i class="fa-solid fa-briefcase"></i> Research & Teaching & Working Experience</h2>
    </div>

    <!-- <nav class="experience-section-nav">
      <ul>
        <li><a href="#research" class="nav-link active" data-target="research">Research Experience</a></li>
        <li><a href="#teaching" class="nav-link" data-target="teaching">Teaching Experience</a></li>
        <li><a href="#working" class="nav-link" data-target="working">Working Experience</a></li>
      </ul>
    </nav> -->

    <!-- Research Experience Section -->
    <h3 class="experience-section-title">Research Experience</h3>

    <ul>
        <li>
            <div class="experience-item">
                <div class="experience-header">
                    <h4 class="position-title">Elsa Lab @ National Taiwan University</h4>
                    <p class="company-info">Undergraduate Researcher (Advisor: Prof. Chun-Yi Lee)</p>
                    <p class="duration">(Feb. 2025 – Present)</p>
                </div>
                <div class="experience-description">
                    <ul>
                        <li class="project-item"><strong>Project</strong>: Distributed Inference of LLM on Heterogeneous CPU/GPU Clusters</li>
                    </ul>
                </div>
            </div>
        </li>

        <li>
            <div class="experience-item">
                <div class="experience-header">
                    <h4 class="position-title">Digital Circuits and Systems Lab (DCS Lab) @ National Taiwan University</h4>
                    <p class="company-info">Research Scholarship Recipients (Advisor: Prof. Chia-Hsiang Yang)</p>
                    <p class="duration">(Jan. 2024 – Jun. 2025)</p>
                </div>
                <div class="experience-description">
                    <ul>
                        <li class="project-item"><strong>Project of National Science and Technology Council (NSTC)</strong>: Design and implementation of a generative AI processor system integrated with High-Bandwidth-Memory architecture</li>
                    </ul>
                </div>
            </div>
        </li>

        <li>
            <div class="experience-item">
                <div class="experience-header">
                    <h4 class="position-title">Digital Image and Signal Processing Lab (DISP Lab) @ National Taiwan University</h4>
                    <p class="company-info">Undergraduate Researcher (Advisor: Prof. Jian-Jiun Ding)</p>
                    <p class="duration">(Mar. 2024 – Dec. 2024)</p>
                </div>
                <div class="experience-description">
                    <ul>
                        <li class="project-item"><strong>Project</strong>: Time-Frequency Analysis of Music Signal with Color Noise</li>
                    </ul>
                </div>
            </div>
        </li>
    </ul>

    <!-- Working Experience Section
    <h3 class="experience-section-title">Working Experience</h3>

    <ul>
        <li>
            <div class="experience-item">
                <div class="experience-header">
                    <h4 class="position-title">Academia Sinica Research Center</h4>
                    <p class="company-info">Research Scholarship Recipients in Information Technology Innovation Research Center (Mentor: Dr. Hsiang-Yun Cheng)</p>
                    <p class="duration">(Sep. 2025 – Present)</p>
                </div>
                <div class="experience-description">
                    <ul>
                        <li class="project-item"><strong>Project of National Science and Technology Council (NSTC)</strong>: Transcending Intelligence with Transformer Acceleration using Near-Storage and In-Memory Chiplet-based Computing</li>
                    </ul>
                </div>
            </div>
        </li>
    </ul> -->

    <!-- Teaching Experience Section -->
    <h3 class="experience-section-title">Teaching Experience (Teaching Assistant)</h3>
    <ul>
      <li class="course-title">CSIE5213 Parallel Programming (Fall 2025), National Taiwan University</li>
    </ul>

  </main>
</div>

<script>
document.addEventListener('DOMContentLoaded', function() {
  const navLinks = document.querySelectorAll('.nav-link');
  const sections = document.querySelectorAll('.experience-section');
  
  navLinks.forEach(link => {
    link.addEventListener('click', function(e) {
      e.preventDefault();
      
      // Remove active class from all links and sections
      navLinks.forEach(l => l.classList.remove('active'));
      sections.forEach(s => s.classList.remove('active'));
      
      // Add active class to clicked link
      this.classList.add('active');
      
      // Show corresponding section
      const targetId = this.getAttribute('data-target');
      const targetSection = document.getElementById(targetId);
      if (targetSection) {
        targetSection.classList.add('active');
      }
      
      console.log('Switched to:', targetId);
    });
  });
});
</script>