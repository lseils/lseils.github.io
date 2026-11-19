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
            Architecture / Computation - M.S. Architecture (Computational Design), Georgia Tech
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
            I am an <strong>M.S. in Architecture</strong> candidate at Georgia Tech and hold a <strong>B.Arch</strong> from Rensselaer Polytechnic Institute.
            My work explores design and research workflows in generative design tools, AI model training, automation, and sustainability.
            My current research looks at the potential of balcony plug-and-play (PnP) solar panel systems in Atlanta's underserved communities and computational generators for collective housing layouts.
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
            <span style="font-family: monospace; color: var(--text-muted);">2025 - Expected Dec 2026</span>
            <div>
                <strong>M.S. Arch (Computational Design)</strong><br>
                <span style="color: var(--text-muted);">Georgia Institute of Technology</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2020 - 2025</span>
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
            <span style="font-family: monospace; color: var(--text-muted);">May 2026 - Pres</span>
            <div>
                <strong>Georgia Institute of Technology - Researcher</strong><br>
                <span style="color: var(--text-muted);">-Train and evaluate a YOLO-based object detection model on Google Street View tiles to identify balconies</span>
                <span style="color: var(--text-muted);">-Test 3D generation models (Depth Anything V2, SAM) for reconstructing facade conditions from imagery</span>
                <span style="color: var(--text-muted);">-Conduct a literature review on photogrammetry-driven methods in urban studies</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">Aug 2025 - Pres</span>
            <div>
                <strong>Georgia Institute of Technology - Graduate Teaching Assistant</strong><br>
                <span style="color: var(--text-muted);">-Support 60+ students with design and technical questions</span>
                <span style="color: var(--text-muted);">-Assist faculty with course logistics and operations</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">May - Aug 2026</span>
            <div>
                <strong>THW Design - Intern</strong><br>
                <span style="color: var(--text-muted);">-Produced drawing sets and 3D models for Senior Living</span>
                <span style="color: var(--text-muted);">-Coordinated with clients and consultants about design strategies</span>
            </div>
        </div>

        <!-- Item 4 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">Summers 2024 &amp; 2025</span>
            <div>
                <strong>BCA Architects &amp; Engineers - Intern</strong><br>
                <span style="color: var(--text-muted);">-Developed Dynamo scripts for automation tasks</span>
                <span style="color: var(--text-muted);">-Built Revit models and drawing sets from LiDAR scan data for secondary schools</span>
                <span style="color: var(--text-muted);">-Conducted existing-conditions surveys and field verifications</span>
            </div>
        </div>

        <!-- Item 5 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">Jun - Aug 2023</span>
            <div>
                <strong>Chicago Dept. of Planning and Development - Intern</strong><br>
                <span style="color: var(--text-muted);">-Created digital record models and public facing graphics</span>
                <span style="color: var(--text-muted);">-Designed massing models to support RFQs for city-owned sites</span>
            </div>
        </div>
    </div>



    <!-- 7. Selected Computational Projects -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Selected Computational Projects</h2>

        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2026</span>
            <div>
                <strong>PV Placement Tool</strong><br>
                <span style="color: var(--text-muted);">-Generates multiple rooftop solar layouts in under a minute, avoiding obstructions and optimizing panel stringing</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2025</span>
            <div>
                <strong>Spatial Configuration Generator</strong><br>
                <span style="color: var(--text-muted);">-Shape-grammar tool that generates collective housing layouts to test how density, access, and shared space vary across cultural contexts</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2024</span>
            <div>
                <strong>Adjacency Matrix Optimizer</strong><br>
                <span style="color: var(--text-muted);">-Scores program adjacency requirements and iteratively optimizes room placement, producing layouts in seconds</span>
            </div>
        </div>
    </div>



    <!-- 8. Technical Skills -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Technical Skills</h2>

        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">      </span>
            <div>
                <strong>Design:</strong><br>
                <span style="color: var(--text-muted);">Rhino3D, Adobe Suite, Revit, Grasshopper &amp; plug-ins, Dynamo, Laser Cutting, 3D printing</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">      </span>
            <div>
                <strong>Programming:</strong><br>
                <span style="color: var(--text-muted);">Python, Java, GitHub, YOLO, AnyLabeling, Depth Anything V2, SAM, HPC clusters</span>
            </div>
        </div>
    </div>

    <!-- 9. Awards -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Awards</h2>

        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2026</span>
            <div>
                <strong>Dean's List</strong><br>
                <span style="color: var(--text-muted);">High Scholastic Attainment</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2025</span>
            <div>
                <strong>Faculty Award</strong><br>
                <span style="color: var(--text-muted);">High Scholastic Attainment</span>
            </div>
        </div>

        <!-- Item 3 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2024</span>
            <div>
                <strong>Faculty Award</strong><br>
                <span style="color: var(--text-muted);">High Scholastic Attainment</span>
            </div>
        </div>

        <!-- Item 4 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);">2021</span>
            <div>
                <strong>Honors Review</strong><br>
                <span style="color: var(--text-muted);">Architecture Design Studio</span>
            </div>
        </div>
    </div>

    <!-- 10. References -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">References</h2>

        <!-- Item 1 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);"></span>
            <div>
                <strong>Dennis Shelden</strong><br>
                <span style="color: var(--text-muted);">Director, CASE, RPI</span>
                <span style="color: var(--text-muted);">sheldd@rpi.edu</span>
            </div>
        </div>

        <!-- Item 2 -->
        <div style="display: grid; grid-template-columns: 150px 1fr; margin-bottom: 1.5rem;">
            <span style="font-family: monospace; color: var(--text-muted);"></span>
            <div>
                <strong>Athanassios Economou</strong><br>
                <span style="color: var(--text-muted);">Director, Shape Computation Lab</span>
                <span style="color: var(--text-muted);">thanos.economou@design.gatech.edu</span>
            </div>
        </div>

        <!-- Item 3 -->
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
