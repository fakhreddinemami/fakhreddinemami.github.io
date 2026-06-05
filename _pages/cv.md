---
layout: archive
title: "Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Summary
======
FEA Simulation Engineer with experience in computational solid mechanics, high-fidelity finite element analysis, optimization, and data-driven modeling. Skilled in developing large-scale computational and surrogate-modeling platforms using machine learning and high-performance computing to advance the design, analysis, and characterization of complex materials and structural systems.

[Download PDF resume](/files/Fakhreddin-Dean-Emami-resume.pdf)

Core expertise: FEA, nonlinear material modeling, structural/stress analysis, surrogate modeling, optimization, SciML, HPC/GPU workflows, Python, and Abaqus.

Professional Experience
======
**FEA Simulation Researcher, University of South Carolina**  
Columbia, SC | Aug. 2021 - Present

- Led FEA, multi-physics simulation, machine learning, and experimental workflows for DARPA and NASA programs, coordinating graduate and undergraduate researchers and delivering validated simulation models and materials-calibration milestones.
- Executed 1M+ high-fidelity ABAQUS/UMAT/USDFLD simulations using Python and Fortran automation, covering static, dynamic, buckling, modal, and thermal analyses, plus submodeling and mesh-convergence verification.
- Developed scientific ML surrogates, including shared-weight MLPs and GNNs, trained on 27 TB of synthetic FEA data to reduce selected full FEA workflows from about 300 CPU-hours to 5 minutes with GPU-accelerated inference.
- Engineered CPU/GPU-accelerated HPC pipelines with Python, CUDA/CuPy, PyTorch, and ABAQUS for automated submission, analysis, post-processing, license-aware scheduling, and adaptive submission-rate control.
- Developed a DARPA-funded 3D heterogeneous specimen enabling single-test inverse calibration of metal plasticity parameters, replacing 12 conventional tests and reducing calibration time from weeks to hours.
- Performed material and geometry optimization for NASA architected-materials research, including ceramic lattice designs for Venus-level mechanical and thermal loads.
- Contributed to 10+ publications, national conference presentations, and a U.S. patent.

**Structural/Civil Engineer, Saeed Associates Chartered**  
Springfield, VA | Mar. 2020 - Jul. 2021

- Performed structural analysis, calculations, and design for highway and bridge components in compliance with AASHTO, VDOT, AISC, ACI, PCA, and related codes.
- Developed structural and civil CAD drawings using MicroStation for I-66 and HRBT projects in Virginia.
- Completed quantity estimates and reviewed contractor shop drawings to identify discrepancies and support code-compliant construction documentation.

Education
======
- Ph.D. Mechanical Engineering, University of South Carolina, Columbia, SC, USA | Aug. 2021 - May 2026
- M.Sc. Civil Engineering, Michigan State University, East Lansing, MI, USA | Aug. 2018 - Dec. 2019
- B.Sc. Civil Engineering, Azad University Central Tehran Branch, Tehran, Iran | Aug. 2010 - May 2014

Technical Skills
======
- **Technical competencies:** Finite Element Analysis, thermo-mechanical simulation, nonlinear modeling, inverse calibration, surrogate modeling, optimization, uncertainty quantification, computational solid mechanics, static/dynamic/buckling/modal/thermal structural analysis, data-driven modeling, machine learning-driven simulation, material behavior characterization.
- **Programming and HPC:** Python, Fortran, MATLAB, CUDA/CuPy, PyTorch, HPC workflows, parallel computing, GPU-accelerated computing, scripting, and automation.
- **Engineering software:** ABAQUS, UMAT/USDFLD, LS-DYNA, ETABS, SAFE, SolidWorks, Fusion 360, MicroStation, AutoCAD, and Meshmixer.

Patent
======
- Emami & Gross, ["Ceramic kelvin foam with geometry optimized for hydrostatic loading"](https://patentsgazette.uspto.gov/week37/OG/html/1538-3/US12415594-20250916.html), US Patent 12,415,594.

Certification
======
- Fundamentals of Engineering Examination (EIT)

Publications
======
<ul>{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}</ul>
