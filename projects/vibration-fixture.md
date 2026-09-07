---
title: 3D-Printed Vibration Test Fixture
---

<p class="eyebrow">DESIGN · ADDITIVE MANUFACTURING · TEST ENGINEERING</p>

# 3D-Printed Vibration Test Fixture

<p class="project-lead">A design-and-test investigation into whether an additively manufactured fixture could provide a faster, lighter alternative to a conventional machined vibration-test fixture.</p>

<div class="notice-card"><strong>Public project overview:</strong> This page intentionally excludes proprietary geometry, controlled test data, customer information, and the full technical report. It describes only my role, methods, and transferable engineering skills.</div>

## The engineering question

Vibration-test fixtures must transfer energy from a shaker to the device under test without introducing excessive damping or resonance into the test band. Machined metal fixtures offer excellent stiffness, but they can also be costly and slow to produce. I investigated whether a carefully designed, fiber-reinforced polymer fixture could be useful for rapid, lower-fidelity test applications.

## My contribution

- Defined performance criteria for fixture stiffness, transmissibility, strength, mass, manufacturability, and printer compatibility.
- Compared candidate polymers using mechanical properties, damping behavior, temperature limits, anisotropy, cost, and available equipment.
- Designed a print-oriented fixture with stiffness-enhancing ribs, distributed clamping loads, and metal threaded interfaces where repeated assembly was required.
- Selected print orientation and process parameters around the primary vibration loading direction.
- Planned and conducted controlled comparisons against a machined baseline using consistent mounting conditions and accelerometer placement.
- Reduced and interpreted sine-sweep and random-vibration data to compare transmissibility, resonance, and attenuation.
- Documented conclusions, limitations, and recommended use cases in a formal engineering viability report.

<div class="metric-grid">
  <div class="metric"><strong>Material trade study</strong><span>Stiffness, damping, strength, cost, and printability</span></div>
  <div class="metric"><strong>Design for AM</strong><span>Load paths, ribs, inserts, clamping, and layer orientation</span></div>
  <div class="metric"><strong>Instrumented testing</strong><span>Controlled sine-sweep and random-vibration comparisons</span></div>
  <div class="metric"><strong>Data analysis</strong><span>Transmissibility, resonances, attenuation, and limitations</span></div>
</div>

## Development process

### 1. Establish a baseline

I first compared a simple printed replica against an existing machined fixture. This preliminary test showed where polymer compliance and damping changed the response and established which design characteristics needed improvement.

### 2. Select an engineering material

I evaluated common and engineering-grade printable polymers, then selected a carbon-fiber-reinforced material that offered the best practical balance of stiffness, damping, strength, temperature capability, printer compatibility, and cost.

### 3. Redesign for the manufacturing process

Instead of duplicating the metal part, I redesigned the fixture around additive manufacturing. The final approach used geometry to reinforce likely bending regions, distributed fastener loads over the polymer, and introduced durable metal interfaces at repeated mounting points.

### 4. Validate experimentally

The printed and machined fixtures were evaluated under matched setups. Multiple test configurations separated unloaded fixture behavior from the coupled response of a fixture and representative payload. Comparing control and response accelerometers made it possible to see how faithfully each fixture transmitted the commanded environment.

## Result

The final printed fixture demonstrated that additive manufacturing can be a viable option for selected vibration-test applications where rapid iteration, lower mass, and reduced manufacturing lead time are more important than machined-fixture fidelity. Testing also identified clear limitations—including greater high-frequency compliance and damping—which define when a printed fixture should and should not be used.

## What I learned

This project strengthened my ability to connect **material selection, structural design, manufacturing constraints, instrumentation, and test data** into a single engineering decision. It also reinforced an important lesson: a successful prototype is not merely a part that survives—the measured response must be understood well enough to define its valid operating envelope.

<div class="button-row">
  <a class="button" href="{{ '/' | relative_url }}">← Back to portfolio</a>
</div>
