---
layout: page
title: "Contact"
permalink: /contact/
---

<div class="contact-content">
    <div class="contact-grid">
        <!-- Contact Details -->
        <div class="contact-section">
            <h2 class="section-title">
                <i data-lucide="mail"></i>
                Get in Touch
            </h2>
            
            <div class="contact-details">
                <div class="contact-item">
                    <h3 class="contact-label">Primary Email</h3>
                    <a href="mailto:{{ site.author.email }}" class="contact-link">
                        {{ site.author.email }}
                    </a>
                </div>
                
                <div class="contact-item">
                    <h3 class="contact-label">Student Email</h3>
                    <a href="mailto:belkoerrolyanis.diallo@studenti.unipd.it" class="contact-link">
                        belkoerrolyanis.diallo@studenti.unipd.it
                    </a>
                </div>
                
                <div class="contact-item">
                    <h3 class="contact-label">Office</h3>
                    <p class="contact-text">3CD3 (ex InfLab)</p>
                </div>
                
                <div class="contact-item">
                    <h3 class="contact-label">Phone</h3>
                    <p class="contact-text">049 827 1321</p>
                </div>
            </div>
        </div>

        <!-- Academic Profiles -->
        <div class="contact-section">
            <h2 class="section-title">
                <i data-lucide="building"></i>
                Academic Profiles
            </h2>
            
            <div class="profile-links">
                <a href="{{ site.author.academic_profile }}" target="_blank" rel="noopener noreferrer" class="profile-link">
                    <div class="profile-link-content">
                        <div class="profile-link-text">
                            <h3 class="profile-link-title">Human Inspired Technology Research Centre</h3>
                            <p class="profile-link-subtitle">University of Padova</p>
                        </div>
                        <i data-lucide="external-link"></i>
                    </div>
                </a>
                
                <a href="{{ site.author.department_profile }}" target="_blank" rel="noopener noreferrer" class="profile-link">
                    <div class="profile-link-content">
                        <div class="profile-link-text">
                            <h3 class="profile-link-title">Department of Mathematics "Tullio Levi-Civita"</h3>
                            <p class="profile-link-subtitle">University of Padova</p>
                        </div>
                        <i data-lucide="external-link"></i>
                    </div>
                </a>
            </div>
        </div>
    </div>

    <!-- Social Links -->
    <div class="social-section">
        <h2 class="section-title">
            <i data-lucide="users"></i>
            Connect With Me
        </h2>
        
        <div class="social-links">
            <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}" target="_blank" rel="noopener noreferrer" class="social-link linkedin">
                <i data-lucide="linkedin"></i>
                <div class="social-link-text">
                    <h3 class="social-link-title">LinkedIn</h3>
                    <p class="social-link-subtitle">Professional networking</p>
                </div>
                <i data-lucide="external-link"></i>
            </a>
            
            <a href="https://github.com/{{ site.author.github }}" target="_blank" rel="noopener noreferrer" class="social-link github">
                <i data-lucide="github"></i>
                <div class="social-link-text">
                    <h3 class="social-link-title">GitHub</h3>
                    <p class="social-link-subtitle">Code repositories and projects</p>
                </div>
                <i data-lucide="external-link"></i>
            </a>
        </div>
    </div>

    <!-- Location -->
    <div class="location-section">
        <h2 class="section-title">
            <i data-lucide="map-pin"></i>
            Location
        </h2>
        
        <div class="location-details">
            <p class="location-name">{{ site.author.employer }}</p>
            <p class="location-department">Department of Mathematics "Tullio Levi-Civita"</p>
            <p class="location-address">Via Trieste, 63</p>
            <p class="location-address">35121 Padova, Italy</p>
        </div>
    </div>
</div>

<script>
    document.addEventListener('DOMContentLoaded', function() {
        lucide.createIcons();
    });
</script>

