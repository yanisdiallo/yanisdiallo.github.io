---
layout: page
title: "Contact"
permalink: /contact/
---

<div class="contact-content">
    <section class="contact-section">
        <h2 class="section-title">
            <i data-lucide="mail"></i>
            Get in Touch
        </h2>
        <p>Feel free to reach out to me via email or connect with me on professional networks.</p>
        
        <div class="contact-info">
            <p><strong>Email:</strong> <a href="mailto:{{ site.author.email }}" class="inline-link">{{ site.author.email }}</a></p>
            <p><strong>Office:</strong> 3CD3 (ex InfLab)</p>
            <p><strong>Phone:</strong> 049 827 1321</p>
        </div>
    </section>

    <section class="contact-section">
        <h2 class="section-title">
            <i data-lucide="link"></i>
            Online Profiles
        </h2>
        <ul class="online-profiles">
            <li>
                <a href="{{ site.author.academic_profile }}" target="_blank" rel="noopener noreferrer" class="inline-link">
                    Academic Profile (Human Inspired Technology Research Centre) <i data-lucide="external-link"></i>
                </a>
            </li>
            <li>
                <a href="{{ site.author.department_profile }}" target="_blank" rel="noopener noreferrer" class="inline-link">
                    Department Profile (Department of Mathematics "Tullio Levi-Civita") <i data-lucide="external-link"></i>
                </a>
            </li>
            <li>
                <a href="https://www.linkedin.com/in/{{ site.author.linkedin }}/" target="_blank" rel="noopener noreferrer" class="inline-link">
                    LinkedIn <i data-lucide="external-link"></i>
                </a>
            </li>
            <li>
                <a href="https://github.com/{{ site.author.github }}/" target="_blank" rel="noopener noreferrer" class="inline-link">
                    GitHub <i data-lucide="external-link"></i>
                </a>
            </li>
        </ul>
    </section>
</div>

<script>
    document.addEventListener("DOMContentLoaded", function() {
        lucide.createIcons();
    });
</script>


