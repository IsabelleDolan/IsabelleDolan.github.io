---
title: "Designing and Simulating Wavelength Shifting Geometry in an Active Helium Target"
header:
  teaser: /assets/images/target.png
excerpt: "I designed and simulated wavelength shifting geometry for a proposed active helium target at the Mainz Microtron in Germany as part of my honours thesis."
order: 1
share: false
layout: single
author_profile: true
classes: wide
---

Scalar polarizabilities are fundamental characteristics closely related to the internal structure of nucleons. While the polarizabilities of the proton have been well studied, the neutron remains elusive due to the lack of a free-neutron target.

Based at the Institute for Nuclear Physics in Germany, the A2 Collaboration has proposed a new active helium target filled with helium isotopes that would allow better access to the neutron. This design would allow for the collection of scintillation light within the active volume, which would reduce backgrounds. The blast of photons emitted from each collision are in the vacuum ultraviolet, while the silicon photomultipliers used only detect in the 200 – 900 nm range. Thus, a wavelength shifting material is needed.

This research examines potential configurations of wavelength shifting fibers to be placed within the target and simulates the light collection and output of each design. Monte Carlo and Geant4 simulations were carried out to compare scintillation light collection between potential wavelength shifter geometries.

The results of this work, along with future analysis, will provide integral insight for building the next prototype. Once the target is built, the neutron scalar polarizabilities can be applied to help explain quantum chromodynamics in the non-perturbative region.


To read the full research, check out the following resources:








<style>
    .shadow-img {
        transition: all 0.3s;
        box-shadow: 3px 3px 15px rgba(0,0,0,0.2);
    }

    .shadow-img:hover {
        box-shadow: 3px 3px 15px rgba(0,0,0,0.4);
    }
</style>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Your Research</title>
    <style>
        .container {
            display: flex;
            justify-content: space-between;
            align-items: center;
            margin-bottom: 20px;
        }
        .title {
            font-weight: bold;
            width: 40%;
        }
        .image-container {
            width: 50%;
            text-align: right;
        }
        img {
            width: 100%;
        }
    </style>
</head>
<body>

<div class="container">
    <div class="title">
        <a href="/assets/files/undergrad_thesis.pdf" target="_blank" > Honours Research Paper</a>
    </div>
    <div class="image-container">
        <a href="/assets/files/undergrad_thesis.pdf" target="_blank">
            <!-- The addition of the shadow-img class -->
            <img class="shadow-img" src="/assets/images/thesis_screenshot.png" alt="undergrad_thesis"/>
        </a>
    </div>
</div>

<div class="container">
    <div class="title">
        <a href="/assets/files/thesis_presentation.pdf" target="_blank" >Presentation</a>
    </div>
    <div class="image-container">
        <a href="/assets/files/thesis_presentation.pdf" target="_blank" >
            <!-- And here as well -->
            <img class="shadow-img" src="/assets/images/thesis_presentation_screenshot.png" alt="thesis_presentation"/>
        </a>
    </div>
</div>


</body>
</html>
