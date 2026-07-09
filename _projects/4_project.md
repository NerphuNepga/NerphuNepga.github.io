---
layout: page
title: LowKos
description: A user-centered UI/UX design project focusing on Human-Computer Interaction principles for property management and student housing.
img: assets/img/imk-logo.png
importance: 4
category: academic
---

LowKos was developed as part of an Interaksi Manusia dan Komputer (IMK) study, focusing heavily on user-centered design methodologies. The core objective was to bridge the gap between students seeking strategic, well-facilitated boarding houses (kos) and property owners needing efficient digital management tools.

### User Research & Personas

Before opening Figma, the project began with comprehensive user research. By conducting questionnaires and direct interviews, data was gathered on the primary pain points of both demographics. This led to the creation of distinct user personas—such as students prioritizing flexible payments and close proximity to campus, and owners needing streamlined communication and automated financial tracking.

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-user-persona-penghuni.png" title="Tenant Persona" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-user-persona-pemilik.png" title="Landlord Persona" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Synthesizing research from the IMK report into actionable user personas. The data highlighted the conflicting needs of both sides of the platform, requiring a dual-focused design approach.
</div>

### Task Analysis & System Architecture

To ensure the interface minimized cognitive load, the system's logic was mapped out before any visual design began. A Hierarchical Task Analysis (HTA) isolates core activities, while a comprehensive user flow diagram dictates the logical pathways and system decisions required to complete those tasks. 

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-hta.png" title="Hierarchical Task Analysis" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-12 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-user-flow.jpg" title="System User Flow" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Mapping the system architecture. Top: The HTA isolating the critical tenant journeys (Searching and Payment). Bottom: The business process flowchart dictating the system logic from search to reservation and payment.
</div>

### Design System & High-Fidelity UI

Applying HCI principles, the final interface was designed with a strong focus on accessibility and intuitive navigation. The visual style utilizes a primary "Light Blue" and "Soft Gray" color palette to evoke a calming and modern aesthetic, ensuring a sense of security for students. For typography, the interface relies on Roboto and Helvetica to maintain clean readability across different screen sizes.

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-search-hifi.png" title="Search UI" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-desc-hifi.png" title="Property Detail UI" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-payment-hifi.png" title="Payment Interface" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The high-fidelity UI design. The interface prioritizes clear iconography, responsive bottom navigation, and intuitive forms for seamless transactions.
</div>

### Usability Evaluation

A critical phase of the IMK methodology is evaluating the design. On-site usability testing sessions were conducted to observe how users interacted with the prototype across four main scenarios. 

The evaluation yielded highly positive results: task completion rates for navigating the homepage, updating profiles, and searching for locations reached **100%** without errors. The testing also successfully identified a navigational bottleneck in the payment layout (which saw an 80% completion rate), providing clear, actionable data for the next iteration of the UI design.

<div class="row justify-content-sm-center align-items-center">
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-sus-efektivitas.png" title="Effectiveness Metrics" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/imk-sus-efisiensi.png" title="Efficiency Metrics" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Quantitative usability testing results. Left: The effectiveness table showing the 100% success rate on core tasks. Right: The efficiency table tracking the average time and steps taken per task.
</div>
