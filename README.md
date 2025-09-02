# Generative Adversarial Networks (GANs) – GDG GenAI Phase 2

This repository contains notes, assignments, and Jupyter notebooks created as part of **GDG GenAI Phase 2** learning project.  
The focus is on understanding **Generative Adversarial Networks (GANs)** and their variants, including **Vanilla GANs, FCGAN, DCGAN, Wasserstein GANs (WGANs), and Conditional GANs (cGANs)**.

---

## 📂 Repository Structure

├── 📁 Reading Docs/                # Reference reading materials (PDFs)  
│   ├── Info on GANs.pdf            # Basics of GANs, minimax game, BCE loss  
│   ├── Classification Problem.pdf  # Binary Cross Entropy (BCE) explained  
│   ├── Additional Type of GANs.pdf # WGANs, cGANs, CycleGANs, SRGANs overview  

├── 📁 IPYNBs/                      # Jupyter notebooks with implementations  
│   ├── Vanilla GANs.ipynb          # Intro GAN implementation  
│   ├── GAN_Assignment.ipynb        # Assignment: FCGAN vs DCGAN  
│   ├── Wasserstein GANs.ipynb      # Implementation of WGAN with gradient penalty  
│   ├── Conditional GANs.ipynb      # Implementation of cGAN on MNIST  

├── GDG GenAI Phase 2.pdf           # Project outline & roadmap  



---

## 📝 Project Breakdown (from GDG Phase 2)

### **Week 1 – Introduction to GANs**
- Understand Generator and Discriminator.
- Learn **Binary Cross Entropy loss** and the **minimax game**.
- Train Vanilla GANs using TensorFlow/Keras.  
📄 *Docs*: `Info on GANs.pdf`, `Classification Problem.pdf`  
📓 *Notebooks*: `Vanilla GANs.ipynb`

---

### **Week 1–2 – FCGAN and DCGAN**
- Build and compare **Fully Connected GAN (FCGAN)** and **Deep Convolutional GAN (DCGAN)**.  
📓 *Assignment*: `GAN_Assignment.ipynb`

---

### **Week 2 – Wasserstein GANs**
- Learn the concept of **Earth Mover’s Distance (Wasserstein distance)**.
- Implement **WGAN with Gradient Penalty** for stable training.  
📄 *Docs*: `Additional Type of GANs.pdf`  
📓 *Notebook*: `Wasserstein GANs.ipynb`

---

### **Week 3 – Conditional GANs (cGANs)**
- Understand how to control GAN outputs using **labels/conditions**.
- Extend to **Text-to-Image GANs** (embedding-based).  
📄 *Docs*: `Additional Type of GANs.pdf`  
📓 *Notebook*: `Conditional GANs.ipynb`

---

## 🎯 Learning Outcomes
By the end of this project, you should be able to:
- Understand the **mathematical foundation** and **loss functions** behind GANs.
- Implement **Vanilla, DCGAN, FCGAN, WGAN, and cGANs** from scratch.
- Compare GAN variants and evaluate their stability & performance.
- Read and understand **research papers** related to GANs.

---

## 🔗 References & Resources
- 📹 [YouTube Playlist](https://youtube.com/playlist?list=PLZsOBAyNTZwboR4_xj-n3K6XBTweC4YVD&si=662KeSmPi4TVw0b_) – GDG GenAI GANs Sessions 
---

## 🛠️ Requirements
- Python 3.8+
- TensorFlow / Keras
- NumPy, Matplotlib
- Jupyter Notebook
