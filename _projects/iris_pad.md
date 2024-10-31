---
layout: page
title: 'Iris-PAD-GUI' 
description: A Python-based GUI for detecting presentation attacks in iris biometrics, featuring D-Net-PAD (by Renu Sharma, MSU) and GradCAM visualization for images and labels.
img: assets/img/iris_pad/irispadgui_0.png
importance: 1
category: work
related_publications: true
---

### Project Repository
[<i class="fab fa-github"></i> View on GitHub](https://github.com/redwankarimsony/Iris-PAD-GUI)



<h3>Features:</h3>
<ul>
    <li><strong>A Python-based GUI application</strong> for detecting presentation attacks in iris images for biometric recognition.</li>
    <li><strong>Features D-Net-PAD detection</strong> (developed by <a href="https://www.linkedin.com/in/renusharma-msu/" target="_blank">Renu Sharma</a> at MSU) and GradCAM visualization for input images and labels.</li>
    <li>Supports Linux operating systems.</li>
    <li>Provides options for single-image <strong>segmentation</strong> and batch processing for both manual and automatic segmentation.</li>
    <li>Includes visualization capabilities for enhanced analysis of spoofs with GradCAM and <strong>patch-wise importance map</strong>.</li>
</ul>



 
 To give your project a background in the portfolio page, just add the img tag to the front matter like so:

    ---
    layout: page
    title: project
    description: a project with a background image
    img: /assets/img/12.jpg
    ---

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/iris_pad/irispadgui_1.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/iris_pad/irispadgui_2.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/iris_pad/irispadgui_3.png" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    From the left, the first one is the Iris Segmenter which includes both manual segmentation and automatic segmeantation capability. The second one is the evaluation where it gives the score between [0,1] where 0: Bonafide, and 1: Presentation Attack. It also shows the pixelwise importance score (in red heatmap). The third one shows the GradCAM visualization of the decision.  


</div>
<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/5.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    This image can also have a caption. It's like magic.
</div>

You can also put regular text between your rows of images, even citations {% cite einstein1950meaning %}.
Say you wanted to write a bit about your project before you posted the rest of the images.
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

{% raw %}

```html
<div class="row justify-content-sm-center">
  <div class="col-sm-8 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/6.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
  <div class="col-sm-4 mt-3 mt-md-0">
    {% include figure.liquid path="assets/img/11.jpg" title="example image" class="img-fluid rounded z-depth-1" %}
  </div>
</div>
```

{% endraw %}
