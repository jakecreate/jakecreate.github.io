---
permalink: /
title: "Hi, I'm Jake 👋"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

How do state-of-the-art models capture complex patterns and relationships to exhibit intelligent behavior? This question drives my curiosity about **representation learning** and my desire to explore the field of **mechanistic interpretability**.

As a first-year Computer Science M.S. student at **UC San Diego** (B.S. in Data Science, **UC Riverside**), I am focused on strengthening my foundations in deep learning and probabilistic reasoning. I aim to develop the research and engineering skills necessary to satisfy my intellectual curiosity and build impactful, real-world AI systems.

In my free time, I love to play chess, read books on human psychology, hike, and sing.

---

## 🧠 Learning from First Principles

With modern libraries, it is easy to train models without ever looking under the hood. What I enjoy most about machine learning is slowing down to study it from **first principles**. Outside of class and research, I spend time working through ML/math textbooks and going down rabbit holes in technical articles—tracing the linear algebra, probability, and optimization mechanics that actually make these models work. For me, the most rewarding part of the field is when a mathematical derivation finally clicks and explains *why* a model succeeds or fails in practice.

---

## 💼 Experience

<table>
  <tr>
    <td width="28%" align="center">
      <img src="/images/presentation_at_llnl.jpeg" alt="LLNL Presentation Photo" width="100%">
    </td>
    <td width="72%">
      <h3>Data Science Challenge (DSC) Intern</h3>
      <h4>Lawrence Livermore National Laboratory &nbsp;|&nbsp; June 2026</h4>
      <p>During an intensive challenge in Livermore, I collaborated in a team of three to automate the structural analysis of additively manufactured lattice geometries (such as octet-truss structures). Working with 3D CT scan data from the Additive Manufacturing Laboratory (AML), I designed the multi-agent architecture for <b>LitBloomer</b>—an autonomous pipeline built with Codex CLI and FastMCP servers that retrieves relevant scientific literature and translates exploratory data analysis (EDA) methodologies into guided code execution for 3D skeletonization and strut diameter profiling. We concluded the program by presenting and defending our validation results to LLNL staff scientists across the computing and materials divisions.</p>
      <p><b>Tools & Tech:</b> <i>Python, Codex CLI, FastMCP, Agentic Workflows, 3D CT Analysis</i></p>
    </td>
  </tr>
</table>

<table>
  <tr>
    <td width="28%" align="center">
      <img src="/images/mpl_ucr.png" alt="Motion Planning Lab Experience" width="100%">
    </td>
    <td width="72%">
      <h3>Research Assistant, Data Science</h3>
      <h4>Motion Planning Lab @ UC Riverside &nbsp;|&nbsp; June 2025 – October 2025</h4>
      <p>Under the mentorship of Prof. Ioannis Karamouzas, I investigated low-dimensional representations for multi-agent spatiotemporal motion. I engineered a custom PyTorch data pipeline over 5.29M+ NBA tracking records (8,415 plays) and designed a 9-layer symmetric MLP Autoencoder (40-D input to 20-D latent bottleneck) to perform non-linear dimensionality reduction on 20-step player trajectories, achieving a <code>1.73e-5</code> test MSE. Projecting these sequences into the latent space revealed distinct clusters of movement patterns, directly motivating follow-up PhD research in latent-space trajectory clustering.</p>
      <p><b>Tools & Tech:</b> <i>PyTorch, Python, Autoencoders, Pandas, NumPy, Matplotlib</i></p>
    </td>
  </tr>
</table>

---

## 🚀 Featured Projects

<table>
  <!-- Project 1: Proactive Edge Attendance Tracker -->
  <tr>
    <td width="35%" align="center">
      <a href="https://github.com/jakecreate/proactive-edge-attendance-tracker">
        <img src="/images/PAT_thumbnail.png" alt="Proactive Edge Attendance Tracker Preview" width="100%">
      </a>
    </td>
    <td width="65%">
      <h3><a href="https://github.com/jakecreate/proactive-edge-attendance-tracker">Proactive Edge Attendance Tracker (PAT)</a></h3>
      <p>An edge facial recognition pipeline deployed on a Raspberry Pi that automates classroom and workplace attendance while preserving user privacy and reducing network latency. The pipeline chains SCRFD detection and MobileFaceNet to project normalized image tensors into 256-D embeddings, classifying faces via KNN and weighted-average cosine similarity. To resolve early embedding collapse (false-positive cosine similarities above 0.9), I expanded bounding-box margins and calibrated facial landmark alignment using OpenCV to eliminate black-edge padding artifacts.</p>
      <p><b>Tech Stack:</b> <i>Python, PyTorch, OpenCV, Docker, Raspberry Pi, MobileFaceNet</i></p>
    </td>
  </tr>

  <!-- Project 2: Machine Learning From Scratch -->
  <tr>
    <td width="35%" align="center">
      <a href="https://github.com/jakecreate/machine-learning-from-scratch">
        <img src="/images/logistic_regression_model.png" alt="Machine Learning From Scratch Preview" width="100%">
      </a>
    </td>
    <td width="65%">
      <h3><a href="https://github.com/jakecreate/machine-learning-from-scratch">Foundational Machine Learning From Scratch</a></h3>
      <p>A first-principles implementation of object-oriented Perceptron, Linear Regression, and L2-regularized Logistic Regression models built without high-level ML frameworks. Includes batch gradient descent with convergence tolerance thresholds, L2 gradient-norm tracking, divergence safeguards, and custom utilities for Z-score standardization and polynomial feature expansion (up to degree 5) to resolve unscaled gradient explosion and visualize decision boundaries.</p>
      <p><b>Tech Stack:</b> <i>Python, NumPy, Matplotlib, Optimization, Linear Algebra</i></p>
    </td>
  </tr>

  <!-- Project 3: YouTube Data Analysis -->
  <tr>
    <td width="35%" align="center">
      <a href="https://github.com/jakecreate/youtube_data_analysis">
        <img src="/images/anomalies.png" alt="Outdoor Boys YouTube Data Analysis Preview" width="100%">
      </a>
    </td>
    <td width="65%">
      <h3><a href="https://github.com/jakecreate/youtube_data_analysis">YouTube Data Analysis: Outdoor Boys</a></h3>
      <p>An exploratory data analysis (EDA) project examining view counts, video length, anomalies, and upload patterns across the Outdoor Boys YouTube channel. Built as a foundational exploration into automated data extraction, cleaning, and statistical visualization.</p>
      <p><b>Tech Stack:</b> <i>Python, Pandas, Matplotlib, Exploratory Data Analysis</i></p>
    </td>
  </tr>
</table>

---

## 📬 Let's Connect

I welcome discussions on machine learning research, representation learning, engineering opportunities, and technical projects.

Feel free to reach out via [Email](mailto:developjake@gmail.com) (or [jak098@ucsd.edu](mailto:jak098@ucsd.edu)) or connect with me on [LinkedIn](https://www.linkedin.com/in/jake-j-kim).