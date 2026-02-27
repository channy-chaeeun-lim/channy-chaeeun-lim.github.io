---
layout: page
title: 'The "Lying" Eye: Biases in 3D Perception'
description: Identifying and mitigating systematic bias in 3D perception tasks.
img: assets/img/proj1_thumb.jpg
importance: 2
category: research
featured: true
---

**Brown University \| PhD Researcher (Vision Science)**

**Do you trust your own perception of 3D space?** We interact with the 3D world constantly and effortlessly. However, my research asks a critical question: _Is our perception actually accurate?_ For example, that building you are looking at might not be as far as you perceive, or the apple in the tree might not be as big as you think.

**I developed an "Ecological Metric" to reveal hidden biases.** Traditional studies often rely on verbal reports or relative measurements, which are prone to conscious guessing and often lack ecological validity. To overcome this, I designed a **sensorimotor adaptation task** in a haptic-enabled VR environment. By asking participants to naturally reach for and grasp virtual objects, I measured the _true_ perceptual bias experienced by the sensory system—capturing the "unconscious" error that occurs before the brain corrects for it.

<div class="row justify-content-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/proj2_photo.jpg" title="Experimental stimuli" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

**Findings: Our perception is biased, but our actions adapt.** My data provided conclusive evidence of two systematic errors:

1. **Overestimation:** We consistently perceive objects in near-space as farther and deeper (more elongated) than they physically are.
2. **The Realism Paradox:** Surprisingly, adding realistic cues like shading and texture _increased_ this perceptual error.

<div class="row justify-content-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid loading="eager" path="assets/img/proj2_result.png" title="Research results" class="img-fluid rounded z-depth-1" %}
  </div>
</div>

**Impact: Design for Adaptation, not just Geometry.** Crucially, I found that despite these biases, users can still perform successful actions because our motor system automatically adapts via **online correction**. This implies that achieving "natural" interaction isn't about rendering perfect physical geometry. Instead, systems should prioritize **sensory feedback loops** (like visual cursors or haptic confirmation) that allow users to leverage their natural adaptation mechanisms to close the gap between what they see and what they touch.

---

**Related Publications & Presentations:**

- [Lim, C., Vishwanath, D., & Domini, F. (2025). Sensorimotor adaptation reveals systematic biases in 3D perception. Scientific Reports, 15(1), 3847.](https://www.nature.com/articles/s41598-025-88214-x)
- <a href="https://www.nature.com/articles/s41598-025-88214-x.pdf" target="_blank" rel="noopener">Lim, C., Vishwanath, D., & Domini, F. (2025). Sensorimotor adaptation reveals systematic biases in 3D perception. Scientific Reports, 15(1), 3847.</a>
- <a href="{{ '/assets/pdf/proj2_poster.pdf' | absolute_url }}" target="_blank" rel="noopener">Lim, C., Vishwanath, D., & Domini, F. (2024). Interplay of exocentric and egocentric information in distance perception for visuomotor tasks. Vision Sciences Society Annual Meeting, FL, United States.</a>
