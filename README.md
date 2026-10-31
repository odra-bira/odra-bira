## Odra Bira

**AI/ML Engineer** · M.S. Computer Science, University at Buffalo (GPA 3.83) · Buffalo, NY

[Portfolio](https://odra-bira.github.io/) · [LinkedIn](https://www.linkedin.com/in/bira-odra/) · [Resume](https://odra-bira.github.io/Odra_Bira_Resume.pdf) · odrabira@gmail.com

I build LLM applications, retrieval systems and computer vision models, and take them from experiment to working software. I'm a Graduate Student Researcher at the University at Buffalo working on safe planning with diffusion models. Before graduate school I worked as a full-stack developer on React, Node.js and SQL applications.

Open to AI/ML Engineer, LLM Application and Research Engineer roles starting December 2026.

---

### Experience

**Graduate Student Researcher**, University at Buffalo · Oct 2025 – Present
- Reproduce and benchmark safety-constrained generative planners (SafeDiffuser, ICLR 2025) as baselines for lab research on safe planning with diffusion and flow-matching models.
- Trained a temporal U-Net diffusion trajectory planner (600-step horizon, 1M iterations) and a value function for guided sampling on D4RL Walker2d, on an NVIDIA RTX 5090 GPU server.
- Benchmarked QP-based vs. closed-form control barrier function enforcement over 100 episodes each: both met the safety constraint, and the closed form cut planning latency 3.2× (0.64 s to 0.20 s).
- Made the research codebase reproducible on Python 3.10.

**Full Stack Developer**, Accentiqa Systems Pvt. Ltd. · Jun 2025 – Aug 2025
- Delivered full-stack features for enterprise workflow applications, owning both the React front end and the RESTful back-end services.
- Designed relational database schemas and built end-to-end CRUD flows across UI, API and data layers.

**Software Developer Intern**, Risposta Software India Pvt. Ltd. · May 2024 – Aug 2024
- Cut API data latency 20% by profiling and rewriting the slow SQL queries behind REST endpoints.
- Cut page-load time 30% by reworking how React/Node.js features fetched and rendered data.

---

### Projects

**LLM and Generative AI**

| Project | Summary | Stack |
|---|---|---|
| [StudyEase](https://github.com/odra-bira/Studyplanner) | Full-stack LLM study planner. Provider-agnostic layer over Claude, Gemini and local Ollama; deterministic validation-and-repair engine for model output with rule-based fallback; 5 typed REST endpoints; PDF and image upload; 35 pytest tests. | FastAPI, React, Pydantic, pytest |
| SkinGPT | RAG assistant: chunking, embedding index, hybrid BM25 + dense retrieval and cross-encoder reranking, with citation-grounded answers. Tuned on a 1,000-question evaluation benchmark to about 75% retrieval precision. | Embeddings, vector search, BM25, LLM APIs |
| Receipt-to-JSON | Fine-tuned Qwen2.5-3B-Instruct with 4-bit QLoRA on CORD-v2 receipts to produce schema-valid JSON on a single T4 GPU. Evaluation harness for JSON validity, field accuracy and item-level F1. | Hugging Face TRL, PEFT, Unsloth, Gradio |
| [Comment Toxicity Classification](https://github.com/odra-bira/comment-toxicity-clean) | Multi-label classifier for six toxicity categories on Jigsaw data using a bidirectional LSTM, with a Gradio demo. | TensorFlow, Keras, Gradio |

**Computer Vision**

| Project | Summary | Stack |
|---|---|---|
| [ShadowFix](https://github.com/odra-bira/ShadowFix) | Compared RGB, residual and mask-guided U-Nets for shadow removal on ISTD. The mask-guided model reached 30.19 dB PSNR / 0.951 SSIM on 540 test images, +9.6 dB over the input. Deployed as a Gradio app with automatic and guided modes. | PyTorch, OpenCV, Gradio |
| [Trash Detection](https://github.com/odra-bira/trash_detection) | Fine-tuned YOLOv8n on the TACO litter dataset (0.78 precision) and turned detections into a 0–100 cleanliness score and density heatmaps. CLI and Gradio app with unit tests. | YOLOv8, OpenCV, pytest |
| [Real-Time Pose Tracking](https://github.com/odra-bira/Real-Time-Pose-Detection-and-Exercise-Tracking-main) | Webcam pose estimation that computes joint angles and counts exercise repetitions. | MediaPipe, OpenCV, NumPy |
| [Fruit Quality Classification](https://github.com/odra-bira/agriculture-project) | MobileNetV2 transfer learning for six fresh/rotten fruit classes, served through a Flask app. Published in IJRASET. | Keras, Flask |

**Deep Learning and Machine Learning**

| Project | Summary | Stack |
|---|---|---|
| Transformers from Scratch | Built a Vision Transformer and a character-level GPT in PyTorch. A 7-configuration ablation on CIFAR-10 showed smaller patches raise accuracy from 40.7% to 50.3%, plus attention-entropy and attention-distance analysis. | PyTorch |
| Reinforcement Learning Agents | Designed custom Gymnasium environments (a 25-state treasure hunt and a warehouse robot) and solved them with SARSA and n-step Double Q-learning. Hyperparameter tuning cut reward variance 35%. | Gymnasium, NumPy |
| Unsupervised Learning in R | K-means, self-organizing maps, hierarchical clustering and PCA, validated with gap statistic and silhouette analysis (0.895 adjusted Rand index). | R, tidyverse |
| Elastic Net from Scratch | Elastic Net regression with gradient descent in NumPy on a 63K-row emissions dataset, with a leakage-safe preprocessing pipeline. | NumPy, pandas |

---

### Publication

Bira, O., et al. [Automated Assessment of Fruit Quality Using Transfer Learning and MobileNetV2](https://doi.org/10.22214/ijraset.2025.68187). IJRASET, 13(4), 2025.

### Education

**University at Buffalo, SUNY** · M.S. Computer Science (AI/ML) · GPA 3.83/4.00 · Aug 2025 – Dec 2026  
Coursework: Machine Learning, Deep Learning, Data-Intensive Computing, Statistical Data Mining, Algorithms, Databases, Operating Systems, Computer Security

**Keshav Memorial Institute of Technology** · B.Tech. Computer Science (AI & ML) · GPA 8.4/10 · 2021 – 2025  
Coursework: NLP with Transformers, Deep Learning for Vision Systems, Big Data with Hadoop and Spark, Data Structures and Algorithms

### Skills

**Languages:** Python, Java, SQL, C/C++, R, JavaScript, Bash  
**Generative AI and LLMs:** Claude and Gemini APIs, Ollama, vLLM, RAG, embeddings, vector search, BM25 hybrid retrieval, cross-encoder reranking, prompt engineering, structured outputs, LLM evaluation, fine-tuning (SFT), LoRA/QLoRA, diffusion models, flow matching  
**Deep Learning:** PyTorch, TensorFlow/Keras, Hugging Face Transformers, TRL, PEFT, Unsloth, Vision Transformers, CNNs, U-Net, LSTMs, transfer learning, mixed-precision training  
**Computer Vision:** OpenCV, YOLOv8, MediaPipe, object detection, image restoration, pose estimation, OCR  
**Machine Learning and RL:** scikit-learn, Optuna, regression and regularization, PCA, clustering, self-organizing maps, model evaluation, SARSA, Q-learning, Gymnasium, D4RL, control barrier functions  
**Backend and Web:** FastAPI, Flask, Pydantic, REST APIs, React, Vite, Node.js, Gradio, Streamlit  
**Data and Databases:** pandas, NumPy, Matplotlib, seaborn, tidyverse, Apache Spark, Hadoop, PostgreSQL, MongoDB, schema design, SQL optimization  
**Tools:** Git, Docker, Linux, CUDA, GPU servers (SSH, tmux), pytest, Weights & Biases, Jupyter, Google Colab
