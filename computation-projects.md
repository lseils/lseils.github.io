---
layout: default
title: Computation Projects
permalink: /computation-projects/
---


<style>
  /* Mobile First: Stack them on top of each other */
  .project-split {
    display: grid;
    grid-template-columns: 1fr; 
    gap: 2rem;
  }

  /* Desktop (Computers): Split 1/3 and 2/3 [min-width was 768px]*/
  @media (min-width: 758px) {
    .project-split {
      grid-template-columns: 1fr 2fr; 
    }
  }
</style>


<!-- BENTO GRID START -->
<div class="bento-grid">

    <!-- 1. HEADER TITLE -->
    <div class="box span-12 header-hero">
        <h1>Computation Projects</h1>
        <div class="subtitle">
            Adjacency Matrix / Spatial Configuration / Automatic Egress / PV Placement
        </div>
    </div>

    <!-- PROJECT 1 -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Adjacency Matrix</h2>

        <div class="project-split">
            <div style="font-size: 0.95rem; line-height: 1.8;">
                <div style="margin-bottom: 1rem;">
                    <span style="color: var(--text-muted); display:block; font-size: 0.8rem; text-transform:uppercase;">Professor</span>
                    <strong>Sheldon, Dennis</strong>
                </div>
            </div>

            <!-- Right Column: The Story (Takes up 2/3 width) -->
            <div>
                <p style="color: var(--text-muted); font-size: 1.1rem; margin-top: 0;">
                  This project involved assigning weighted scores to the proximity needs of different school programs. Putting some rooms near eachother, that would make most sense and creating heirchay of what proximities were more important. The created Python script generated a simple rectangular layout with a single corridor. The script iteratively optimized the location of each program, with a self-evaluation score to understand how well it’s iteration aligned with the adjacency matrix. This allows for one to plan programatic layouts to one’s desires, within seconds rather than manually iterating.
                </p>
            </div>
        </div>
    </div>


    <!-- 1. PHOTO 1 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Flowchart.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 1. PHOTO 2 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Matrix.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 1. PHOTO 3 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Outputs1.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 1. PHOTO 4 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Outputs2.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 1. PHOTO 5 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Outputs3.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 1. PHOTO 6 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/am/Outputs5.jpg' | relative_url }}" alt="Lydia Seils">
    </div>


    <!-- PROJECT 2 -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Spatial Configuration</h2>
        
        <div class="project-split">
            <!-- Left Column: The Stats -->
            <div style="font-size: 0.95rem; line-height: 1.8;">
                <div style="margin-bottom: 1rem;">
                    <span style="color: var(--text-muted); display:block; font-size: 0.8rem; text-transform:uppercase;">Professor</span>
                    <strong>Leita, Carla</strong>
                </div>
            </div>

            <!-- Right Column: The Story -->
            <div>
                <p style="color: var(--text-muted); font-size: 1.1rem; margin-top: 0;">
                  Environments, cultures, and technologies are constantly changing. As designers, how do we deal and plan with ongoing changes in spatial conditions. Can a Space-Grammar tool be created that may help design collective housing layouts for different cultures of use of semi-public space within varying density demands? Applying Space-Grammar’s processes of inquiry to collective housing layouts could help manage/mediate spatial relationships between public and private space between units, across different cultural and/or density contexts. This thesis aims to explore the different valuable shared spaces that could exist in collective housing, using basic geometry and orientations. Different organizations, densities, and access points can dramatically affect the residents how experience these spaces. Some of these spaces may bring the feeling of belonging, the creation of community connections via direct interaction, giving one a sense of belonging. Some of these spaces give the feeling of safety as there are others viewing the area. Other spaces feel as spill over or an extension of space, shared spaces reduce the need for excessive private infrastructure. A spatial configuration tool allows us to quickly test and analyze these spaces, allowing us to explore the values of shared space.
                </p>
            </div>
        </div>
    </div>

    <!-- 2. PHOTO 1 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sg/Output.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 2. PHOTO 2 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sg/Psuedo_Code2.jpg' | relative_url }}" alt="Lydia Seils">
    </div>
    
    <!-- 2. PHOTO 4 -->
    <div class="box span-12 photo-box">
        <img src="{{ '/assets/img/comp/sg/P2.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 2. PHOTO 5 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sg/P3.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 2. PHOTO 6 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sg/P4.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 2. PHOTO 7 -->
    <div class="box span-12 photo-box">
        <img src="{{ '/assets/img/comp/sg/Render.png' | relative_url }}" alt="Lydia Seils">
    </div>


    <!-- PROJECT 3 -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">Automatic Egress</h2>

        <div class="project-split">
            <div style="font-size: 0.95rem; line-height: 1.8;">
                <div style="margin-bottom: 1rem;">
                    <span style="color: var(--text-muted); display:block; font-size: 0.8rem; text-transform:uppercase;">Professor</span>
                    <strong>Sheward, Hugo</strong>
                </div>
            </div>

            <!-- Right Column: The Story (Takes up 2/3 width) -->
            <div>
                <p style="color: var(--text-muted); font-size: 1.1rem; margin-top: 0;">
                  In every building, egress stairs are a key part of safety and must follow strict building code requirements. When designing, room layouts and occupancies change, thus requiring recalculations for the stairs, over and over again. This tool updates stairs instantly as the building changes, ensuring that saftey, and design work together from the start. The Automatic Egress Stair Tool solves this by linking building data to code rules. It calculates occupancy loads, stair widths, and floor heights, then automatically generates code-compliant stairs inside the digitial model. This saves time, reduces mistakes, and keeps the design process focused on creativity instead of repetitive math.
                </p>
            </div>
        </div>
    </div>

    <!-- 3. PHOTO 1 -->
    <div class="box span-4 photo-box">
        <img src="{{ '/assets/img/comp/fs/Pseudo_Code.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 3. PHOTO 2 -->
    <div class="box span-8 photo-box">
        <img src="{{ '/assets/img/comp/fs/B2-Plan.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 3. PHOTO 3 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/fs/B2-Stairs.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 3. PHOTO 4 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/fs/B2-Egress.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 3. PHOTO 5 -->
    <div class="box span-12 photo-box">
        <img src="{{ '/assets/img/comp/fs/B2-FinalOutput.jpg' | relative_url }}" alt="Lydia Seils">
    </div>


    <!-- PROJECT 4 -->
    <div class="box span-12">
        <h2 style="border-bottom: 1px solid #333; padding-bottom: 0.5rem; margin-bottom: 1.5rem;">PV Placement</h2>

        <div class="project-split">
            <div style="font-size: 0.95rem; line-height: 1.8;">
                <div style="margin-bottom: 1rem;">
                    <span style="color: var(--text-muted); display:block; font-size: 0.8rem; text-transform:uppercase;">Professor</span>
                    <strong>Economou, Athanassios</strong>
                </div>
            </div>

            <!-- Right Column: The Story (Takes up 2/3 width) -->
            <div>
                <p style="color: var(--text-muted); font-size: 1.1rem; margin-top: 0;">
                  Today, energy demands are on the rise with the need for Data Centers, Crypto Mining, Commercial Uses, and much more. Solar panels provide an efficent, cheaper, and greener energy option and can take advantage of unused roof top spaces. However, populating rooftops with solar panels is not as easy as it sounds, as there are obstacles that the panels must avoid, like mechanical equipment and skylights. Furthermore, solar panels work much more efficently if they are strung together in a specifc series. Currently to figure out an efficent layout for a large rooftop can take multiple hours. This solar panel placement tool however can give multiple viable solutions within a minute. 
                </p>
            </div>
        </div>
    </div>


    <!-- 4. PHOTO 1 -->
    <div class="box span-8 photo-box">
        <img src="{{ '/assets/img/comp/sp/Roof_Iters_Crop.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 4. PHOTO 2 -->
    <div class="box span-4 photo-box">
        <img src="{{ '/assets/img/comp/sp/Psuedo_Flow_Crop.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 4. PHOTO 3 -->
    <div class="box span-12 photo-box">
        <img src="{{ '/assets/img/comp/sp/Layouts.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 4. PHOTO 4 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sp/Iso_A.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 4. PHOTO 5 -->
    <div class="box span-6 photo-box">
        <img src="{{ '/assets/img/comp/sp/Iso_B.jpg' | relative_url }}" alt="Lydia Seils">
    </div>

    <!-- 4. PHOTO 4 -->
    <div class="box span-12 photo-box">
        <img src="{{ '/assets/img/comp/sp/Iso_C.jpg' | relative_url }}" alt="Lydia Seils">
    </div>




</div>
<!-- BENTO GRID END -->