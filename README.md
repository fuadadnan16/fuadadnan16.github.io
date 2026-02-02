# Mirza Fuad Adnan

#### Ph.D. Student | Electrical Engineering | University of Maryland, College Park  
**Research Areas:** Computational Imaging, Program Analysis, Reverse Engineering, Malware Provenance  
**Technical Skills:** Python, C/C++, MATLAB, Assembly, PyTorch, TensorFlow, OpenCV, Ghidra, FAISS, Milvus, Git, Linux

<p align="center">
  <img src="headshot.jpg" width="180"/>
</p>

---

## Education
- **Ph.D. in Electrical Engineering** | University of Maryland, College Park (_Expected May 2029_)
- **M.Sc. in Electrical & Electronic Engineering** | Islamic University of Technology, Bangladesh (_March 2019_)
- **B.Sc. in Electrical & Electronic Engineering** | Islamic University of Technology, Bangladesh (_December 2015_)  
  *Rank 1 / 87 — OIC Gold Medalist*

---

## Work Experience

**Graduate Teaching Assistant — University of Maryland, College Park (_Fall 2024 – Present_)**  
Conduct laboratory sessions, grade assignments, and assist with instruction for core ECE courses, while mentoring students on signal processing, systems, and programming fundamentals.

**Assistant Professor — Islamic University of Technology, Bangladesh (_Oct 2019 – Aug 2024_)**  
Led undergraduate courses and laboratory sessions in Electrical and Electronic Engineering, supervised student projects, conducted research, and published in peer-reviewed venues while on study leave for doctoral training.

**Research Assistant — Institute of Energy and Environment, IUT (_Aug 2019 – Nov 2020_)**  
Performed solar panel flash testing, experimental evaluation, and technical report writing, contributing to applied renewable energy research.

---

## Projects

### High Dynamic Range (HDR) Imaging Pipeline  
[GitHub Repository](https://github.com/your-username/hdr-imaging)

<p align="center">
  <img src="HDR_github.PNG" width="650"/>
</p>

This project focuses on building an end-to-end HDR imaging pipeline starting from RAW sensor data and producing perceptually optimized display-ready images. The pipeline includes demosaicing, white balance, exposure normalization, multi-exposure fusion using multiple weighting strategies, Reinhard tone mapping, and sRGB gamma correction. The system was implemented in **Python** using **dcraw**, **ExifRead**, **NumPy**, **OpenCV**, and **Matplotlib**, with extensive parameter sweeps to study the trade-off between visual quality and file size.

---

### Plug-and-Play ADMM for Image Deblurring and Denoising  
[GitHub Repository](https://github.com/your-username/pnp-admm-imaging)

<p align="center">
  <img src="pnp_github.PNG" width="650"/>
</p>

The goal of this project is to explore optimization-based image restoration using a Plug-and-Play ADMM framework that integrates powerful denoisers as implicit priors. A complete ADMM solver was implemented from first principles, incorporating **BM3D** within the iterative optimization loop. The implementation uses **Python**, **FFT-based solvers**, and **conjugate gradient methods**, and was evaluated across multiple blur kernels and noise settings, achieving up to **35–36 dB PSNR** with systematic parameter tuning.

---

### Light Field Imaging and Depth-from-Refocus  
[GitHub Repository](https://github.com/your-username/light-field-imaging)

<p align="center">
  <img src="LF_github.PNG" width="650"/>
</p>

This project investigates depth estimation and synthetic refocusing using plenoptic images without explicit 3D reconstruction. A complete light field pipeline was developed to extract sub-aperture views, generate focal stacks through synthetic refocusing, and estimate depth using sharpness-weighted fusion and depth-from-refocus techniques. The system was implemented in **Python** using **NumPy**, **OpenCV**, and scientific computing tools, producing accurate depth maps and all-in-focus images.

---

### Malware Provenance and Function-Level Similarity Analysis  
[GitHub Repository](https://github.com/your-username/malware-function-similarity)

<p align="center">
  <img src="malware_github.PNG" width="650"/>
</p>

This ongoing research project aims to identify shared source code and authorship across large collections of malware binaries by analyzing similarity at the function level. The system extracts control-flow graphs and intermediate representations using **Ghidra** and **Ghidrathon**, converts functions into vector embeddings, and performs large-scale similarity search and clustering using **FAISS** and **Milvus**. The design targets nation-scale workloads involving millions of binaries and billions of functions, operating without ground truth labels or predefined cluster counts.

---

## Publications

1. **M. Fuad Adnan et al.**, *M.Digitize-HCD: A Dataset for Digitization of Handwritten Circuit Diagrams*,  
   **Data in Brief**, 2025.  
   [https://doi.org/10.1016/j.dib.2025.111315](https://doi.org/10.1016/j.dib.2025.111315)

2. **M. Fuad Adnan et al.**, *Traffic Congestion Prediction using Deep Convolutional Neural Networks: A Color-Coding Approach*,  
   **ICEET 2022**.  
   [https://doi.org/10.1109/ICEET56468.2022.10007425](https://doi.org/10.1109/ICEET56468.2022.10007425)

3. **M. Arafat, M. Adnan, M. Islam**, *AI-based Affordable High-Density Traffic Monitoring System*,  
   **NCIM 2023**.  
   [https://doi.org/10.1109/NCIM59001.2023.10212910](https://doi.org/10.1109/NCIM59001.2023.10212910)

---

## Links
- **LinkedIn:** https://www.linkedin.com/in/mirza-fuad-adnan-951947143  
- **Email:** adnan16@umd.edu
