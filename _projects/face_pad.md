---
layout: page
title: 'Face-PAD-GUI'
description: A GUI based face spoof detector based on spoof detection algorithm with explainability traces. 
img: assets/img/face_pad/face_pad_gui_1.png
importance: 2
category: work
giscus_comments: true
---

<p>In safety-critical biometric systems, <strong>spoof detection</strong> is crucial. Individuals may attempt to evade detection or acquire documents, such as passports or other legal IDs, by posing as someone else. <strong>Face spoof detection</strong> helps prevent attempts to obscure or falsify identity, ensuring the integrity and reliability of biometric verification systems.</p>

<h3>Key Applications of Iris Spoof Detection:</h3>
<ul>
    <li><strong>Border Security and Immigration:</strong> Ensures that travelers are accurately identified, preventing unauthorized entry and impersonation attempts at border control points.</li>
    <li><strong>Identity Verification for Legal Documents:</strong> Helps in verifying the authenticity of identities for passports, driver’s licenses, and other legal documents, ensuring that only legitimate holders can obtain these documents.</li>
    <li><strong>Secure Access Control:</strong> Used in high-security facilities, such as government buildings, research labs, and financial institutions, to prevent unauthorized access through identity spoofing.</li>
    <li><strong>Financial Transactions:</strong> Protects against fraudulent activities in financial institutions by verifying genuine users through iris recognition, reducing identity theft in banking and online transactions.</li>
    <li><strong>Healthcare Access:</strong> Confirms patient identity in secure health systems, ensuring that only authorized individuals receive sensitive medical information and services.</li>
</ul>


    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---


<h3>Application Screenshots: </h3>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    Some of the screenshot of the application. Score: <b style="color:#07e041;">0: Bonafide</b>, and <b style="color:#e00707;">1: Presentation Attack (PA)</b>.
 The first one is a bonafide face which has a very low PA score (0.08). The second one is a transparent mask which has high PA score (0.83) and the third one has a printed face mask which also exhibits high PA score (0.45). 


<h3 style="text-align: left;">Case 1:</h3>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The input here is a real image and the spoof traces on the 2x2 grid on the right side shows a very little activity. 



<h3 style="text-align: left;">Case 2:</h3>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    The input here is a real face with transparent masks with extra eye-brows and mostache. This images shows high PA score and also the traces on the right side shows what are the regions primary contributing to the decision. 



<h3 style="text-align: left;">Case 3:</h3>
</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/face_pad/face_pad_gui_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This face image is a real face with printed face mask on. This also shows a high PA score and the right side shows the traces of the spoof. 












You can also put regular text between your rows of images.
Say you wanted to write a little bit about your project before you posted the rest of the images.
You describe how you toiled, sweated, _bled_ for your project, and then... you reveal its glory in the next row of images.

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm-4 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    You can also have artistically styled 2/3 + 1/3 images, like these.
</div>

The code is simple.
Just wrap your images with `<div class="col-sm">` and place them inside `<div class="row">` (read more about the <a href="https://getbootstrap.com/docs/4.4/layout/grid/">Bootstrap Grid</a> system).
To make images responsive, add `img-fluid` class to each; for rounded corners and shadows use `rounded` and `z-depth-1` classes.
Here's the code for the last row of images above:


