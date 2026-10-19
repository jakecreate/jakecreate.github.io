---
permalink: /
title: "Hi, I'm Jake 👋"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

I am a first-year M.S. student in Computer Science at **UC San Diego** (B.S. in Data Science, **UC Riverside**). I came to graduate school driven by two things: an intellectual curiosity about how modern AI systems actually work under the hood, and a desire to do purposeful work that applies these systems to high-impact problems in science and society.

Specifically, I am fascinated by **representation learning**—how models capture complex structure from raw data, and how we can interpret and leverage those learned representations for downstream tasks across domains like biology, healthcare, and other high-impact fields. Lately, I have been working with **Hidden Markov Models (HMMs)** to infer latent states in sequential data, while exploring **mechanistic interpretability** as a lens to better understand and steer what models learn internally. 

Whether through research or engineering, my goal is to build a deep, adaptable toolkit for designing reliable AI systems that solve meaningful real-world problems.

In my free time, I love playing chess, reading books on human psychology, hiking, and singing.

---

## 🧠 Learning from First Principles

With modern libraries, it is easy to train models without ever looking under the hood. However, I believe that reasoning from first principles is not only essential for truly understanding a system, but also the best catalyst for coming up with novel solutions to computational problems and advancing the field. Beyond that, I simply love the feeling of being awe-inspired by the mathematics behind today's state-of-the-art AI.

Outside of class, I spend my free time going down mathematical rabbit holes—whether that means tracing the proof for why the Gaussian distribution satisfies the second axiom of probability, or deriving the forward-backward dynamics of Hidden Markov Models from scratch. For me, the most rewarding part of machine learning is when a mathematical derivation finally clicks and informs how we design, debug, or apply a model in practice.

---

## 💼 Experience

<table>
  <tr>
    <td width="28%" align="center">
      <img src="/images/presentation_at_llnl.jpeg" alt="LLNL Presentation Photo" width="100%">
    </td>
    <td width="72%">
      <h3>Data Science Challenge (DSC) Intern</h3>
      <h4>Lawrence Livermore National Laboratory &nbsp;|&nbsp; July 2026</h4>
      <p>During an intensive challenge in Livermore, I collaborated in a team of three to automate the structural analysis of additively manufactured lattice geometries (such as octet-truss structures). Working with 3D CT scan data from the Additive Manufacturing Laboratory (AML), I designed the multi-agent architecture for <b>LitBloomer</b>—an autonomous pipeline built with Codex CLI and FastMCP servers that retrieves relevant scientific literature and translates exploratory data analysis (EDA) methodologies into guided code execution for 3D skeletonization and strut diameter profiling. We concluded the program by presenting and defending our validation results to LLNL staff scientists across the computing and materials divisions.</p>
      <p><b>Tools & Tech:</b> <i>Python, Codex CLI, FastMCP</i></p>
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
      <p>Under the mentorship of Prof. Ioannis Karamouzas, I explored representation learning for multi-agent motion. I built a custom PyTorch autoencoder to perform non-linear dimensionality reduction on spatiotemporal sequence data from normalized NBA player trajectories. By projecting these sequences into the latent space, I discovered clusters of distinct movement patterns, directly motivating a PhD student in the lab to pursue latent-space clustering for her research.</p>
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
