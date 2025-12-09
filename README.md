# Hero-with-Blueprint-Animation

Description

Reusable SVG blueprint animation showing the 4-pillar growth architecture:
Strategy: C-suite advisory
Data: Built-in, unified API, no vendor lock-in
Teams: 30+ clients
Compliance: GDPR, HIPAA, PCI DSS compliant

Complete hero section featuring

Left column: Headline, subheadline, benefits, CTAs
Right column: Animated SVG blueprint (Strategy → Data → Teams → Compliance)

Branding

Color: #d6ff3f (Lime Yellow)
Background boxes: rgba(13, 60, 112, 0.4) (Navy Blue transparent)
Grid pattern: Subtle lime yellow overlay

Features

Pure SVG with CSS animations (no JavaScript dependencies)
Transparent background (integrates anywhere)
Sequential reveal animations
Hover effects reveal subtitle stats
Pulse dots flowing through connections
Glow effect on hover
~5KB total weight

Usage

Copy hero-ultranoir-style.html content
Paste into Custom Code section
Adjust CTA links as needed
Deploy

Method 1: Direct Embed
html<!-- Copy the entire <svg> element from blueprint-standalone.html -->
<!-- Paste into Custom Code section -->

Method 2: iFrame
html<iframe src="path-to-blueprint-standalone.html" 
        style="width: 100%; max-width: 500px; height: 600px; border: none;">
</iframe>

Method 3: Inline in Hero
Wrap the blueprint SVG in your hero layout:
html<div style="display: grid; grid-template-columns: 1fr 1fr;">
  <div>Your text content here</div>
  <div><!-- Paste SVG here --></div>
</div>

Linguistic Solution
This blueprint is language-agnostic since box labels are in English universally understood in B2B tech.

Works on EN pages
Stats in hover tooltips are technical (GDPR, API, etc.)
Translation needed

Customization
To change subtitle text, edit the <text class="stat-text"> elements:

Line 95-98: Strategy subtitle
Line 109-114: Data subtitle (multi-line)
Line 125-128: Teams subtitle
Line 139-144: Compliance subtitle (multi-line)

Author
Florian Nègre - Fractional Chief Growth Officer
https://www.negreflorian.com

License
Proprietary - For Florian Nègre use only
