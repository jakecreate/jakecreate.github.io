## About Me

I am an M.S. student in Computer Science at **UC San Diego**[cite: 2], having previously earned my B.S. in Data Science at **UC Riverside**[cite: 2]. 

What motivates me most in computer science and machine learning is bridging the gap between **theoretical mathematical foundations** and **real-world scientific and physical systems**. Whether I am designing multi-agent workflows to accelerate materials science research[cite: 2], compressing high-dimensional spatiotemporal trajectories[cite: 2], or deploying computer vision pipelines on edge hardware[cite: 2], I enjoy tackling problems where noisy, real-world data meets rigorous algorithmic design.

---

## My Approach & Philosophy

* **Learning from First Principles:** Modern ML frameworks make it easy to call `.fit()` or chain APIs without understanding what happens under the hood. I strongly believe in stripping away abstractions to understand the core math first—whether that means implementing gradient descent and regularized models from scratch in NumPy to watch how unscaled gradients explode[cite: 2], or inspecting embedding spaces directly to diagnose why a vision model is collapsing[cite: 2].
* **Translating Theory into Production:** Clean math only matters if it runs reliably. I care deeply about the engineering details—data standardization, memory-efficient pipelines, and containerization[cite: 2]—that turn a fragile research notebook into a reproducible system.

---

## Experience

**Data Science Challenge (DSC) Intern** | *Lawrence Livermore National Laboratory (LLNL)* *(June 2026)*[cite: 2]
* Worked at the intersection of agentic AI and materials science[cite: 2]. I designed the multi-agent architecture for **LitBloomer** using Codex CLI and FastMCP servers, building an autonomous Literature Agent that extracts exploratory data analysis (EDA) methodologies from scientific literature and translates them into guided code execution for 3D CT scan structural analysis (such as skeletonization and strut diameter profiling on octet-truss lattices)[cite: 2].

**Research Assistant, Data Science** | *Motion Planning Lab, UC Riverside* *(June 2025 – Oct 2025)*[cite: 2]
* Focused on spatiotemporal representation learning over 5.29M+ NBA player tracking records[cite: 2]. I engineered a custom PyTorch data pipeline and designed a 9-layer symmetric MLP Autoencoder to compress 20-step player trajectories into a compact latent bottleneck, achieving a $1.73 \times 10^{-5}$ test MSE[cite: 2].

---

## Selected Projects

* **Proactive Edge Attendance Tracker (PAT)** *(Python, PyTorch, OpenCV, Docker)*[cite: 2]  
  An edge facial recognition pipeline running on a Raspberry Pi that chains SCRFD detection with MobileFaceNet embeddings[cite: 2]. When early tests suffered from embedding collapse (high false-positive cosine similarities), I diagnosed and resolved the issue at the preprocessing level by calibrating facial landmark alignment in OpenCV to eliminate black-edge padding artifacts[cite: 2].
* **Foundational Machine Learning From Scratch** *(Python, NumPy, Matplotlib)*[cite: 2]  
  A first-principles implementation of object-oriented Perceptron, Linear Regression, and $L_2$-regularized Logistic Regression models using pure NumPy[cite: 2]. Built custom utilities for $Z$-score standardization, polynomial feature expansion, $L_2$ gradient-norm tracking, and divergence safeguards to study optimization dynamics and bias-variance trade-offs firsthand[cite: 2].