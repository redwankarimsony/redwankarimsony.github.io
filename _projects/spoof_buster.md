---
layout: page
title: MSU Fingerprint Spoof Buster 
description: A Python-based GUI application for fingerprint spoof detection, featuring the Spoof Buster algorithm by Tarang et. al (2018)
img: assets/img/spoof_buster/1.png
importance: 1
category: work
---

### Project Repository
[<i class="fab fa-github"></i> View on GitHub](https://github.com/redwankarimsony/MSU-SpoofBuster-GUI-FingerPrint)

This project was initially developed by  <a href="https://ieeexplore.ieee.org/abstract/document/8306930" target="_blank"> Tarang et al (2018) </a> and partially completed by me in 2022. My contribution focused on the final stages, where I developed a GUI to demonstrate the effectiveness of the algorithm visually. Mostly implemented the single mode and batch mode of operation. 

<br>
<h3>Applications of a Fingerprint Spoof Detector</h3>
<ul>
    <li><strong>Access Control Systems:</strong> Enhances security in sensitive facilities by detecting spoofed fingerprints, ensuring only authorized personnel gain access.</li>
    <li><strong>Banking and Financial Services:</strong> Provides secure biometric authentication, reducing the risk of identity fraud in banking transactions.</li>
    <li><strong>Mobile Device Security:</strong> Protects user data on smartphones and tablets by preventing spoofed fingerprint access attempts.</li>
    <li><strong>Law Enforcement:</strong> Assists in verifying the authenticity of fingerprint evidence in forensic investigations.</li>
    <li><strong>Healthcare:</strong> Ensures secure access to patient information in medical facilities, safeguarding sensitive health data.</li>
</ul>

<br>
<h3>Key Features of the Fingerprint Spoof Buster</h3>
<ul>
    <li><strong>Capable of loading multiple models:</strong> Supports both CrossMatch_InceptionV3 and Limidigm_InceptionV3 models.</li>
    <li><strong>Minutiae detection, counting, and plotting:</strong> Detects, counts, and plots minutiae points for detailed fingerprint analysis.</li>
    <li><strong>Liveness detection scoring:</strong> Displays minutiae points and their scores in terms of liveness detection.</li>
    <li><strong>Flexible processing options:</strong> Supports batch processing as well as single-image processing.</li>
</ul>


<br>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spoof_buster/1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/spoof_buster/2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The left case is a bonafide case where it has 56 minutiae points and all of them are live points. The right side case has only 36 detected cases all of which are PAs. 

<p>For more, please see the <a href="https://github.com/redwankarimsony/MSU-SpoofBuster-GUI-FingerPrint" target="_blank">GitHub Page</a>.</p>
