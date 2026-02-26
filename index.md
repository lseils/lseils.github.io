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
            M.S. Architecture (Computational Design) - Georgia Tech
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

    <!-- DOWNLOAD PORTFOLIO LINK -->
    <a href="{{ '/assets/pdf/Portfolio_Seils_lydia.pdf' | relative_url }}" class="box span-12" style="display:flex; align-items:center;" target="_blank">
        <h3>Download Portfolio</h3>
        <span class="arrow-icon">↗</span>
    </a>



    <!-- 5. Education -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Education</h2>
        
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
    </div>



    <!-- 6. Experience -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Experience</h2>
        
        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">August 2025 - Pres</span>
            <div>
                <strong>Graduate Teaching Assistant</strong><br>
                <span style="color: var(--text-muted);">-Conducted desk critiques with constructive feedback</span>
                <span style="color: var(--text-muted);">-Supported 60+ students with design and technical questions</span>
                <span style="color: var(--text-muted);">-Assisted faculty with course logistics and operations</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">May - August 2025</span>
            <div>
                <strong>BCA Architects & Engineers</strong><br>
                <span style="color: var(--text-muted);">-Developed Dynamo scripts for automation tasks</span>
                <span style="color: var(--text-muted);">-Generated drawing sets and 3D models</span>
                <span style="color: var(--text-muted);">-Conducted existing condition surveys</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">May - August 2024</span>
            <div>
                <strong>BCA Architects & Engineers</strong><br>
                <span style="color: var(--text-muted);">-Generated drawing sets and 3D models from Lidar scans</span>
                <span style="color: var(--text-muted);">-Conducted field verifications</span>
            </div>
        </div>

        <!-- Item 4 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">June - August 2023</span>
            <div>
                <strong>Chicago Dept. of Planning and Development</strong><br>
                <span style="color: var(--text-muted);">-Created digital models for records</span>
                <span style="color: var(--text-muted);">-Designed massing models for RFQs</span>
                <span style="color: var(--text-muted);">-Produced informative graphics and drawings</span>
            </div>
        </div>
    </div>



    <!-- 7. Technical Skills -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Technical Skills</h2>
        


        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">      </span>
            <div>
                <strong>Design:</strong><br>
                <span style="color: var(--text-muted);">Rhino3D, Adobe Suite, Revit, Grasshopper, Climate Studio, Ladybug, Dynamo, Laser Cutting, 3D printing</span>
            </div>
            
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">      </span>
            <div>
                <strong>Programming</strong><br>
                <span style="color: var(--text-muted);">Python, Java, html, Github</span>
            </div>
        </div>
    </div>

    <!-- 8. Awards -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Awards</h2>
        
        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2025</span>
            <div>
                <strong>Faculty Award</strong><br>
                <span style="color: var(--text-muted);">High Scholastic Attainment</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2024</span>
            <div>
                <strong>Faculty Award</strong><br>
                <span style="color: var(--text-muted);">High Scholastic Attainment</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">Spring 2021</span>
            <div>
                <strong>Honors Review</strong><br>
                <span style="color: var(--text-muted);">Architecture Design Studio</span>
            </div>
        </div>
    </div>

        <!-- 9. References -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">References</h2>
        
        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);"></span>
            <div>
                <strong>Dennis Shelden</strong><br>
                <span style="color: var(--text-muted);">Director, CASE</span>
                <span style="color: var(--text-muted);">sheldd@rpi.edu</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);"></span>
            <div>
                <strong>Athanassios Economou</strong><br>
                <span style="color: var(--text-muted);">Professor; Director, Shape Computation Lab</span>
                <span style="color: var(--text-muted);">thanos.economou@design.gatech.edu</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);"></span>
            <div>
                <strong>Fleet Hower</strong><br>
                <span style="color: var(--text-muted);">Professor; Director, Web Services</span>
                <span style="color: var(--text-muted);">howerj@rpi.edu</span>
            </div>
        </div>

    </div>

</div>
<!-- BENTO GRID END -->