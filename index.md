---
layout: default
title: Home
---

# Dheer Patel

**Master's student in Robotics, Cognition, Intelligence**  
Technical University of Munich, Germany

[Email](mailto:dheer.patel@tum.de) • [LinkedIn](https://www.linkedin.com/in/DheerPatel) • [CV](/assets/cv.pdf)

---

## About Me

I'm a Master's student at TUM specializing in **Control Theory** and **Computer Vision** with hands-on experience in autonomous systems, machine learning, and robotics. Currently working on my thesis: *Three-dimensional Tube Model Predictive Control for Autonomous Racing*.

### Current Focus
- **Control Theory** & Model Predictive Control
- **Computer Vision** & Visual Odometry
- **Machine Learning** & Reinforcement Learning
- **Autonomous Systems** & Robotics

---

## Featured Projects

<div class="project-grid">
{% for project in site.projects limit:3 %}
  <div class="project-card">
    <h3><a href="{{ project.url }}">{{ project.title }}</a></h3>
    <p>{{ project.description }}</p>
    <div class="tech-tags">
      {% for tech in project.technologies %}
        <span class="tech-tag">{{ tech }}</span>
      {% endfor %}
    </div>
  </div>
{% endfor %}
</div>

[View All Projects →](/projects)

---

## Experience Highlights

**Data Science & ML** @ elunic Systems AG *(Oct 2023 - Present)*
- IIoT and Industry 4.0 applications
- Multi-agent RAG systems for condition monitoring

**Testing & Validation** @ EDAG Engineering GmbH *(Nov 2022 - Sep 2023)*
- ADAS lab operations and test automation

**Data Science Intern** @ BMW Group *(Sep 2021 - Feb 2022)*
- Driver attentiveness analysis using CNNs and SVMs

[View Full Experience →](/experience)

---

## Technical Skills

**Programming:** Python, C++, MATLAB  
**Frameworks:** PyTorch, TensorFlow, ROS2, Scikit-Learn  
**Specializations:** Control Systems, Computer Vision, Machine Learning  
**Languages:** English, German (C1), + 5 others
