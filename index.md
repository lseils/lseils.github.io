---
layout: default
title: Home
---

<!-- BENTO GRID START -->
<div class="bento-grid">

    <!-- 1. HEADER TITLE -->
    <div class="box span-12 header-hero">
        <h1>Lydia Seils</h1>
        <div class="subtitle">
            M.S. Architecture (Computational Design) // Georgia Tech
        </div>
    </div>

    <!-- 2. PHOTO (Update 'me.jpg' to your actual image filename in assets/img/) -->
    <div class="box span-4 photo-box">
        <img src="{{ '/assets/img/home/Headshot-BlackWhite.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 3. BIO -->
    <div class="box span-8">
        <h2 style="color: var(--highlight); margin-bottom: 1rem;">About</h2>
        <p style="color: var(--text-muted); font-size: 1.1rem;">
            I am currently pursuing an <strong>M.S. in Architecture</strong> at Georgia Tech. 
            Previously, I earned my B.Arch from RPI. This collection includes contemporary architectural projects and custom design tools.
        </p>
    </div>

    <!-- 4. BIG NAV LINKS (The visual boxes) -->
    <!-- Note: We use Liquid tags for links to keep them working -->
    <a href="{{ '/architecture-projects/' | relative_url }}" class="box span-4" style="display:flex; align-items:center;">
        <h3>Architecture Projects</h3>
        <span class="arrow-icon">↗</span>
    </a>

    <a href="{{ '/computation-projects/' | relative_url }}" class="box span-4" style="display:flex; align-items:center;">
        <h3>Computation Projects</h3>
        <span class="arrow-icon">↗</span>
    </a>

    <a href="mailto:lydiamseils@gmail.com" class="box span-4" style="display:flex; align-items:center;">
        <h3>Get in Touch</h3>
        <span class="arrow-icon">@</span>
    </a>

    <!-- 5. TIMELINE / RESUME -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Education & Experience</h2>
        
        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2025-Pres</span>
            <div>
                <strong>M.S. Arch (Computational Design)</strong><br>
                <span style="color: var(--text-muted);">Georgia Institute of Technology</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2020-2025</span>
            <div>
                <strong>B.Arch</strong><br>
                <span style="color: var(--text-muted);">Rensselaer Polytechnic Institute</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr;">
            <span style="font-family: monospace; color: var(--text-muted);">2023</span>
            <div>
                <strong>Internship</strong><br>
                <span style="color: var(--text-muted);">Chicago Dept. of Planning and Development</span>
            </div>
        </div>
    </div>

</div>
<!-- BENTO GRID END -->