---
layout: page
title: GESTRA Mobile
description: An accessibility application translating SIBI sign language into text and speech.
img: assets/img/12.jpg
importance: 1
category: work
related_publications: false
---

Gestra is a mobile and web application built with a core mission: making communication more accessible. Grounded in a comprehensive literature study, the platform is designed to seamlessly translate SIBI (Sistem Isyarat Bahasa Indonesia) sign language into text and speech, bridging the gap between deaf or hard-of-hearing individuals and the wider community.

### Project Scope & Front-End Implementation

During the development cycle, my primary focus was bridging the gap between design and technical execution through front-end UI implementation and Quality Assurance. 

*   **UI/UX Implementation:** Developed the interactive homepage, configurable user settings, and engineered a seamless dark mode toggle to enhance visual accessibility.
*   **Quality Assurance:** Set up and executed autonomous testing protocols to identify interface bugs and ensure UI stability across different application states.
*   **Technical Planning:** Drafted the Work Breakdown Structure (WBS) and comprehensive UML documentation to map out the development pipeline and structural logic.

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gestra-home.jpeg" title="Gestra Homepage UI" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gestra-settings.jpeg" title="Settings Configuration" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/gestra-darkmode.jpeg" title="Dark Mode Feature" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Front-end interfaces designed and implemented for the Gestra application. Left: The interactive homepage. Middle: User settings configuration. Right: The dark mode functionality.
</div>

### Autonomous Testing & Stability

Creating an accessible interface requires rigorous testing. By automating the UI testing protocols, we were able to quickly iterate on the front-end design without manually verifying every state change. This ensured that the application remained stable, preventing UI friction from hindering the core translation features.

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/gestra-testing-result.png" title="Test Files Explorer" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/gestra-testing.png" title="Terminal Output Tests Passed" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Automated testing suite for Gestra. On the left, the structured unit and widget test files. On the right, the terminal output confirming all 42 tests passed successfully.
</div>

### System Architecture

Before writing the front-end code, the architecture was mapped out to ensure the integration of complex AI translation libraries would not disrupt the user experience.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/gestra-uml.png" title="UML Documentation" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    System architecture and project management documentation. Left: UML flow charting user interactions. Right: WBS structuring the development pipeline.
</div>
