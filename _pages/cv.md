---
layout: archive
title: "CV / Resume"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

# Technical Highlights

- 3 years of AI research experience in deep learning, neural rendering, computer vision and 3D reconstruction.
- Designed a 3D damage inspection pipeline using deep learning for real-world environment.
- Hands-on experience in collecting over 100,000 images for training segmentation model and 3D reconstruction.
- Published research papers in high-impact journals related to deep learning in applied science.

# Work experience

- Research Assistant

  - University of Manitoba (2022 - 2024)
  - Integrated deep learning models for object detection (YOLOv7), segmentation (STRNet & U-Net), and neural rendering (NeRF) into a unified pipeline.
  - Enhanced a damage segmentation model, increasing MIoU from 80% to 91.6% on a new dataset using semi-supervised learning, image synthesis augmentation, and test-time augmentation.
  - Developed a neural rendering model, ABM-Nerfacto, by applying attention modules and tuning hyperparameters, improving PSNR from 22.42 to 29.12, SSIM from 0.8069 to 0.8083, and reducing MSE from 0.00672 to 0.00195.
  - Localized 3D damage coordinates by converting 2D object detections using camera extrinsic parameters.
  - Conducted data preparation, including annotation (bounding box, segmentation), augmentation, and image enhancement (deblurring, super-resolution).

- Data Annotator – SDMENC (Contract) (2021)
  - Performed polygon labeling for AI training datasets.
  - Classified image data into 10 categories of industrial waste for detection and classification models.

- Robotics Research Engineer (Intern)
  - Korea Institute of Science and Technology (KIST) (2020)
  - Conducted environment setup and testing of Cartographer and ORB-SLAM2 over ROS on a TurtleBot3 equipped with Raspberry Pi, OpenCR, and Intel RealSense RGB-D camera for navigation simulation testing.
  - Optimized computational efficiency by pre-processing input images, removing irrelevant upper-view data.
  - Converted 3D point cloud data to a 2D occupancy grid map, enabling real-time navigation for mobile robots.

# Education

<!-- - Ph.D in Version Control Theory, GitHub University, 2018 (expected) -->

- M.S. in Civil Engineering,University of Manitoba, Winnipeg, Canada, 2024
- B.S. in Mechanical and Automotive Engineering, Seoul National University of Science and Technology (SeoulTech), 2021

# Publications

  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

# Projects

<ul>{% for post in site.portfolio %}
  {% include archive-single.html %}
 {% endfor %}</ul>
 
# Skills

- Programming Languages: Python, C, MATLAB, JavaScript, HTML, CSS
- Frameworks & Libraries: PyTorch, TensorFlow, Scikit-learn, OpenCV, FFmpeg, Numpy, Node.js, React
- Platforms & Tools: Linux, Git, Docker, ROS, Blender, Metashape
- Databases: MongoDB, SQL
- Cloud Services: AWS (EC2, S3)

# Certificates

- Machine Learning Specialization – Coursera
- Full Stack Development - Nomad Coders Bootcamp

<!-- Talks

  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul> -->

<!-- Teaching

  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul> -->

<!-- Service and leadership

- Currently signed in to 43 different slack teams -->
