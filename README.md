# Hi, I'm Kazi Hafiz Md. Asad 👋

![Typing SVG](https://readme-typing-svg.demolab.com/?lines=Efficient+and+Trustworthy+Machine+Learning;NLP+and+LLM+Compression+Researcher;Higher-Order+Representation+Learning;Reproducible+AI+Research&center=true&width=760&height=50)

## Research Profile

I am an **M.S. researcher in Computer Science and Engineering at North South University**, working at the intersection of **efficient and trustworthy natural language processing, large language model adaptation, model compression, and higher-order representation learning**.

My research asks a recurring question: **how much model capacity is actually necessary, and how can that claim be demonstrated through rigorous evidence?** I study this question through knowledge distillation, parameter-efficient fine-tuning, quantization, controlled benchmarking, ablation studies, leakage prevention, and reproducible experimentation.

My current work includes:

- Distilling BERT into a **29M-parameter student model**, achieving a **3.8× parameter reduction** while retaining competitive task performance.
- Fine-tuning a **7B-parameter LLM under constrained VRAM** using 4-bit quantization, QLoRA, adaptive rank scheduling, gradient checkpointing, and controlled compression strategies.
- Comparing graph and hypergraph representations for protein-complex recovery across **nine interaction datasets** under strict leakage control.
- Conducting interdisciplinary research in computational biology, sustainable AI, software security, and digital phenotyping.

I value research that is **reproducible, compute-aware, statistically grounded, and transparent about the trade-off between efficiency and predictive quality**.

<div align="center">
  <img src="https://go-skill-icons.vercel.app/api/icons?i=python,pandas,numpy,jupyter,matplotlib,scikitlearn,pytorch,tensorflow,opencv,git,github,linux&perline=12" />
  <br/>
  <img src="https://go-skill-icons.vercel.app/api/icons?i=huggingface,langchain,llamaindex,pinecone,qdrant,ollama,chatgpt&perline=12" />
</div>

---

## 🎓 Education

### [North South University](https://www.northsouth.edu), Dhaka, Bangladesh

**M.S. in Computer Science and Engineering**  
*July 2024 – Present*

- GPA: **3.55/4.00**; 24 of 30 credits completed.
- Supervisor: **Dr. Mohammad Ashrafuzzaman Khan**.
- Thesis: **Ultra-Efficient Fine-Tuning of 7B-Parameter Large Language Models under Constrained VRAM using Dynamic Progressive Compression and Adaptive Stride Training**.

**B.S. in Computer Science and Engineering**  
*May 2019 – June 2023*

- GPA: **3.53/4.00**.
- Graduated **Cum Laude**.
- Thesis: **BERT Knowledge Distillation for NLP Tasks**, later extended into a 2025 PLOS ONE article.

**Relevant graduate coursework:** Machine Learning, Deep Learning, Natural Language Processing, Computer Vision, Advanced Algorithms, Graph Theory, Digital Image Processing, Computer Security, Probability and Statistics, Databases, Software Engineering, and Advanced VLSI Design.

---

## 🔬 Research Experience

### M.S. Thesis Researcher
**Department of Electrical and Computer Engineering, North South University**  
*2024 – Present*

**Ultra-Efficient Fine-Tuning of 7B-Parameter LLMs under Constrained VRAM**

- Built a memory-efficient framework for fine-tuning **Qwen2.5-7B-Instruct** on a single consumer-class GPU.
- Combined **4-bit quantized loading, QLoRA, gradient checkpointing, adaptive rank scheduling with SVD warm-start, gradient-noise-gated control, and GPU isolation**.
- Conducted **27 controlled experiments** measuring model quality, peak GPU memory, wall-clock runtime, convergence stability, and sensitivity to the compression schedule.
- Used ablation studies to determine which components produced meaningful gains and which were redundant.
- Engineered a reproducible experimentation pipeline with pinned environments, controlled random seeds, configuration logging, and per-experiment result tracking.

### Research Collaborator : Efficient NLP Group
**North South University**  
*2023 – Present*

- Conduct research with **Dr. Mohammad Ashrafuzzaman Khan** on knowledge distillation, efficient NLP, experimental validation, and scientific writing.
- Contributed to two peer-reviewed papers covering transformer compression and computationally efficient misinformation detection.
- Participated across the research lifecycle, including problem formulation, experiment design, statistical validation, visualization, manuscript preparation, and camera-ready submission.

---

## 📝 Publications and Preprints

### 1. Larger Models Yield Better Results? Streamlined Severity Classification of ADHD-Related Concerns Using BERT-Based Knowledge Distillation

**Ahmed Akib Jawad Karim, Kazi Hafiz Md. Asad, and Md. Golam Rabiul Alam**  
*PLOS ONE, 20(2), e0315829, 2025 : Q1 Journal*

[Journal Article](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0315829) · [LastBERT Model Card](https://huggingface.co/Peraboom/LastBERT)

- Introduced **LastBERT**, a 29M-parameter student distilled from BERT-base with a **3.8× reduction in parameter count**.
- Evaluated the model across GLUE tasks and ADHD concern-severity classification using social-media text.
- Led formal analysis, validation, and visualization supporting the paper's central argument that scale is not always a prerequisite for task competence.

### 2. Strengthening False Information Propagation Detection: Leveraging SVM and Sophisticated Text Vectorization Techniques in Comparison to BERT

**Ahmed Akib Jawad Karim, Kazi Hafiz Md. Asad, and Aznur Azam**  
*2025 IEEE International Conference on Quantum Photonics, Artificial Intelligence, and Networking (QPAIN), pp. 1–6*

[IEEE Xplore](https://ieeexplore.ieee.org/document/11171942)

- Benchmarked BERT against SVM classifiers using **TF-IDF, Word2Vec, and bag-of-words representations** under matched resource budgets.
- Demonstrated that a carefully specified classical pipeline can approach transformer-level performance while requiring substantially less computation.
- Emphasized resource-aware model selection for low-resource deployment settings.

### 3. When Does Higher-Order Representation Improve Protein-Complex Recovery? A Leakage-Controlled, Matched-*k* Comparison of Graph and Penalized Hypergraph Spectral Clustering

**Kazi Hafiz Md. Asad, Rafi Majid, Md. Tanjeelur Rahman Labib, and Ahsanur Rahman**  
*Preprint under review, 2026 : First Author*  
**DOI:** https://doi.org/10.5281/zenodo.21651589

- Designed and implemented a leakage-free benchmark across **nine IntAct MITAB datasets** with held-out evaluation.
- Compared graph and penalized hypergraph spectral clustering using matched-*k* evaluation, significance testing, null models, and Gene Ontology enrichment.
- Characterized the empirical conditions under which higher-order incidence structure improves protein-complex recovery over pairwise graph projection.

---

## 📚 Manuscripts and Reviews in Preparation

### Sustainable Intelligence: Environmental Trade-offs of Cloud-Based Machine Learning

- Conducting a **PRISMA-guided critical review** of energy, carbon, water, and hardware-lifecycle impacts across model training, inference, and data-center operation.
- Examining inconsistencies in environmental measurement and reporting.
- Assessing mitigation strategies including carbon-aware scheduling, algorithmic efficiency, efficient hardware use, and low-carbon deployment.

### Naturalistic Behavioural Prognosis in Autistic Children

- Synthesizing longitudinal evidence from naturalistic audio, video, wearable, and behavioral data used to forecast language and adaptive-functioning outcomes.
- Identifying limitations in external validation, uncertainty quantification, fairness, clinical utility, and cross-population generalization.
- Developing a research roadmap for trustworthy digital phenotyping and developmental forecasting.

---

## 🚧 Current Research Projects

### Ultra-Efficient LLM Adaptation under Constrained VRAM

- Investigating dynamic progressive compression and adaptive training strategies for 7B-scale language models.
- Evaluating the efficiency-quality trade-off through controlled experiments, ablations, memory profiling, and convergence analysis.
- Primary methods include **QLoRA, 4-bit quantization, adaptive low-rank updates, gradient checkpointing, and reproducible GPU benchmarking**.

### Graph vs. Hypergraph Protein-Complex Recovery

- Modeling multi-protein experimental interactions as both pairwise co-complex graphs and incidence-based hypergraphs.
- Developing and evaluating a tunable penalized hypergraph Laplacian.
- Testing whether higher-order representations provide measurable benefits under leakage-controlled and statistically matched conditions.

### Automated Vulnerable-Code Detection with CodeBERT and Distillation

- Building a CodeBERT-based pipeline for classifying secure and vulnerable source-code snippets using the **DiverseVul** dataset.
- Exploring knowledge distillation to reduce inference cost for practical code-scanning workflows.
- Studying how model efficiency affects software-security performance and deployment feasibility.

---

## 🚀 Selected Technical Projects

### [Stack Overflow Question Quality Classification](https://github.com/donnowhattodo/classification-on-stackOverflowQuestion)

- Built an end-to-end multi-class NLP pipeline using **60,000 Stack Overflow questions**.
- Classified questions into High Quality, Low Quality with Community Edits, and Low Quality Closed categories.
- Applied text preprocessing, feature engineering, model training, and comparative evaluation for content-quality assessment.

### [Bone Fracture Detection using Vision Transformer](https://github.com/donnowhattodo/Bone_fracture_ViT-)

- Fine-tuned a pre-trained **ViT-B/16** model for binary fracture detection using the **MURA v1.1** radiographic dataset.
- Evaluated model generalization using **5-fold cross-validation**.
- Implemented data preprocessing, transfer learning, training, and validation workflows.

### [Fake-News Detection with SVM Kernels](https://github.com/donnowhattodo/SVMFakeNews)

- Compared linear and nonlinear SVM kernels across multiple text representations.
- Reported accuracy and F1-score to distinguish predictive performance from computational cost.
- Explored efficient classical alternatives to transformer-based text classification.

### [RoBERTa Knowledge Distillation](https://github.com/donnowhattodo/DistillationOFRoberta)

- Fine-tuned RoBERTa-based models for sentiment analysis, MRPC, and CoLA.
- Explored teacher-student training strategies for reducing model size while maintaining task performance.
- Developed reusable training and evaluation components for efficient transformer experimentation.

### [Hyperspectral Image Reconstruction using PCA and Residual U-Net](https://github.com/donnowhattodo/HSI_reconstruction)

- Developed a hyperspectral image reconstruction pipeline using PCA and a Residual U-Net with spectral normalization.
- Reduced 31 spectral bands to three principal components and reconstructed the original spectral representation.
- Evaluated reconstruction quality using PSNR, SSIM, and Spectral Angle Mapper.

### [Object Detection using YOLOv3 and YOLOv4](https://github.com/donnowhattodo/ODA_YOLOv3)

- Developed an object-detection pipeline using pretrained YOLOv3 and YOLOv4 models on the COCO label space.
- Implemented image and video inference for real-time detection across 80 object categories.

### [Aid-NSU : Django Platform Prototype](https://github.com/donnowhattodo/Aid-NSU)

- Developed a moderated campus social-platform prototype using Django.
- Implemented authentication, posting, real-time comments, and chat functionality.
- The application remained a prototype and was not publicly released.

---

## 💼 Professional and Teaching Experience

### AI Evaluation and Pilot Task Contributor
**MindriftAI : Remote**  
*November 2025 – Present*

- Design, review, and validate evaluation scenarios for autonomous AI agents.
- Assess logical soundness, behavioral alignment, realism, and policy adherence in multi-step agent workflows.
- Improve model behavior through prompt refinement, curated exemplars, structured feedback, and iterative validation.

### Teaching Assistant
**North South University, Dhaka, Bangladesh**  
*December 2022 – October 2023*

- Conducted tutorials and office hours for undergraduate computer-science courses.
- Prepared course materials, designed assignments, graded student work, and provided detailed feedback.
- Explained technical concepts to mixed-ability cohorts and contributed to curriculum-development activities.

---

## 🧠 Research Interests

- **Efficient and Trustworthy NLP**
- **Large Language Model Compression and Adaptation**
- **Knowledge Distillation, Quantization, Pruning, and LoRA/QLoRA**
- **Parameter-Efficient and Compute-Aware Machine Learning**
- **Higher-Order, Graph, and Hypergraph Representation Learning**
- **Automated Software-Vulnerability Detection**
- **Computational Biology and Digital Phenotyping**
- **Sustainable AI and Environmental Evaluation**
- **Multimodal and Longitudinal Modeling**

---

## 🛠️ Technical Skills

**Programming:** Python, SQL, PHP, object-oriented programming, data structures, algorithms, and scripting.  

**Machine Learning and NLP:** PyTorch, Hugging Face Transformers, scikit-learn, spaCy, Pandas, NumPy, SciPy, TensorFlow, JAX/Flax (basic), BERT, RoBERTa, GPT-family models, Mistral, Qwen, classification, regression, segmentation, RAG, LangChain, and vector databases.  

**Model Efficiency:** Knowledge distillation, 4-bit quantization, LoRA/QLoRA, gradient checkpointing, adaptive rank scheduling, pruning, efficient evaluation, and GPU-memory profiling.  

**Research Methods:** Controlled baselines, ablation studies, matched comparisons, leakage prevention, significance testing, null models, F1/ROC-AUC evaluation, cross-validation, and PRISMA-guided literature synthesis.  

**Systems and Tooling:** CUDA, Linux, Git/GitHub, reproducible environments, LaTeX, n8n, Tableau, and Microsoft Office.

---

## 🏅 Honours and Academic Development

- **Cum Laude**, B.S. in Computer Science and Engineering, North South University, 2023.
- Active on **LeetCode** and **Deep-ML** for algorithmic problem solving, implementation practice, and applied machine-learning exercises.
- Experienced in independent experimental design, reproducible engineering, scientific visualization, and first-author manuscript preparation.

---

## 🤝 Open to Research Collaboration

I am interested in collaborating on research involving:

- Efficient and trustworthy NLP
- LLM compression and parameter-efficient fine-tuning
- AI for software engineering and cybersecurity
- Graph and hypergraph machine learning
- Computational biology and healthcare AI
- Sustainable and resource-aware machine learning

I am especially interested in projects that combine **methodological rigor, reproducible implementation, controlled evaluation, and practical computational constraints**.

---

## 🌐 Connect with Me

- **Email:** [kazi.asad@northsouth.edu](mailto:kazi.asad@northsouth.edu)
- **LinkedIn:** [kaziasadcse](https://linkedin.com/in/kaziasadcse)
- **GitHub:** [donnowhattodo](https://github.com/donnowhattodo)
- **Google Scholar:** [Kazi Hafiz Md. Asad](https://scholar.google.com/citations?user=24zDLJMAAAAJ&hl=en)
- **Twitter/X:** [@ImKaziAsad](https://twitter.com/ImKaziAsad)
- **LeetCode:** [ImMasterPutin](https://leetcode.com/u/ImMasterPutin/)
- **Deep-ML:** [Kazi Asad](https://www.deep-ml.com/profile/7ysd47LWjIM21Ng2NGWvlmxS0Du1)

---

<div align="center">
  <img src="https://github-profile-summary-cards.vercel.app/api/cards/profile-details?username=donnowhattodo&theme=tokyonight" />
  <br/><br/>
  <a href="https://github-profile-svg.vercel.app/api/profile?username=donnowhattodo&mode=terminal&theme=dark">
    <img src="https://github-profile-svg.vercel.app/api/profile?username=donnowhattodo&mode=terminal&theme=dark" height="170" />
  </a>
  <img src="https://streak-stats.demolab.com/?user=donnowhattodo&theme=tokyonight" height="170" />
  <br/><br/>
  <img src="https://visitor-badge.laobi.icu/badge?page_id=donnowhattodo.donnowhattodo" />
  <img src="https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Research-Efficient%20%26%20Trustworthy%20AI-blue" />
</div>

---

*Last updated: August 2026*
