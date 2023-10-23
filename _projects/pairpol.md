---
title: " A Time-Walk Correction Method for the Glasgow Pair Polarimeter"
header:
  teaser: /assets/images/pairpol.png
excerpt: "Time-walk correction method for the data obtained by the Glasgow Pair Polarimeter, a device used to measure photon beam polarization."
order: 2
share: false
layout: single
author_profile: true
classes: wide
---

The A2 collaboration at the Institute for Nuclear Physics in Mainz, Germany, collides real photons with nuclei in the photon-energy range of 40 MeV to 1.6 GeV. They focus on experimentally determining polarization observables called polarizabilities via Compton scattering.

However, when measuring these polarizabilities, a linearly polarized photon beam is needed. Detectors and experimental methods have reached a level of sophistication such that the photon beam polarization measurement is now the limiting source of systematic error. To remedy this, a team of physicists, led by the University of Glasgow, developed the Glasgow Pair Polarimeter. This new detector can reach a systematic error of 2% or less after calibration. For comparison, current methods cannot get below 5%. However, this device has the characteristic where one particle can cause multiple hits.

This research focused on the methods used to correct for this phenomenon, called the time-walk effect. The time-walk correction can be done with the Timepix3 chip by taking advantage of the simultaneous measurement of the threshold crossing time and the event energy. The results for the corrections done on data from beam times in Mainz have provided encouraging results. Once completed, the Pair Polarimeter would be used at the A2 Collaboration and other similar facilities.



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
        <a href="/assets/files/pairpol_presentation.pdf">Presentation</a>
    </div>
    <div class="image-container">
        <a href="/assets/files/pairpol_presentation.pdf">
            <!-- Here's the addition of the shadow-img class -->
            <img class="shadow-img" src="/assets/images/pairpol_screenshot.png" alt="pairpol"/>
        </a>
    </div>
</div>


</body>
</html>
