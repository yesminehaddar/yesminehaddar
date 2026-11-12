# Hi, I'm Yesmine 👋

**Final-year AI engineering student at SUP'COM (Tunis)**, Multimodal Information Applications track (Master's level).
I build AI systems that turn messy data into something usable: **LLM agents, RAG pipelines and computer vision**.

🎯 **Looking for a 6-month end-of-studies internship from February 2027**, in AI agents, LLM applications, computer vision or medical imaging, in France or Europe.

## What I bring

- **AI agents in a real industrial setting:** at Sagemcom I build LLM agents for the Android TV engineering teams, orchestrated with LangGraph.
- **End-to-end projects, from raw data to a working tool:** 805,842 images indexed and searchable in milliseconds, 918 CT scans turned into a training-ready dataset, 445,208 video frames turned into a live rep counter.
- **Measured results, honest limits:** every project below reports real numbers, what broke and how it was fixed.

## Experience

| Role | What I do | Stack |
| --- | --- | --- |
| **AI intern, Sagemcom** (09/2026 to present) | 4 LLM agents for the Android TV teams: build-failure debugging, impact analysis, test selection, regression risk, with confidence indicators and multi-agent orchestration | Python, LangGraph, LangChain, Ollama, GitHub Actions |
| **IoT and embedded intern, MakerSkills** (07/2026 to 08/2026) | Off-grid LoRa mesh network (Meshtastic), MQTT gateway, time-series storage, field measurement campaign | ESP32, nRF52, LoRa, MQTT, InfluxDB |
| **Software development intern, TELNET** (07/2025 to 08/2025) | Full-stack tool that generates Gherkin test cases from structured files, tested with the QA team | Python, Flask, React, REST APIs, XML |

## Featured projects

**[AI Workout Coach](https://github.com/yesminehaddar/ai-workout-coach)** (in progress): real-time exercise recognition, rep counting and posture feedback from a webcam, fully local.
MediaPipe pose features from 1,041 videos (445,208 frames) and a self-calibrating rep counter: **88% of clips within ±1 rep, 32 to 41 FPS on a CPU**.
`Python` `MediaPipe` `OpenCV` `pandas` `PyTorch` `Streamlit`

**[Iris](https://github.com/yesminehaddar/iris-cbir)**: content-based image retrieval over 805,842 Flickr images.
5 MPEG-7 descriptors, **exact k-NN in 18 to 67 ms** over the full base, and a benchmark showing why a VP-tree loses to a linear scan above about 64 dimensions.
`Python` `NumPy` `FastAPI` `PostgreSQL` `Docker`

**[Lung nodule segmentation](https://github.com/CHAABEN-Chahin/lung-nodule-nnunet-prep)** (team of 2): from raw LIDC-IDRI CT scans to an nnU-Net v2 dataset of 918 cases.
3D reconstruction in native geometry, consensus nodule masks, QC audits, and **nnU-Net v2 segmentation (Dice 0.72 ± 0.08)**.
`Python` `PyTorch` `nnU-Net` `SimpleITK` `pylidc`

**Agentic RAG study assistant** (in progress): answers questions about lecture PDFs, fully local.
OCR, slide-aware chunking, Weaviate, **Gemma 3 4B through Ollama on a 4 GB GPU**, and an MCP server.
`Python` `Ollama` `Weaviate` `MCP` `Docker`

## Tech stack

| Area | Tools |
| --- | --- |
| **LLMs and agents** | LangGraph, LangChain, Ollama, RAG, MCP, Weaviate, embeddings, Hugging Face, prompt engineering |
| **Computer vision and imaging** | PyTorch, OpenCV, MediaPipe, nnU-Net, YOLO11, ByteTrack, SimpleITK, CT imaging |
| **Data** | Python, NumPy, pandas, Parquet, SQL, PostgreSQL, MongoDB, InfluxDB |
| **Backend and web** | FastAPI, Flask, Spring Boot, Node.js, React, Angular, REST APIs |
| **Tooling and cloud** | Docker, Git, GitHub Actions, Linux, AWS (certification in progress) |
| **IoT and embedded** | ESP32, nRF52, LoRa, MQTT |

**Certifications:** NVIDIA Fundamentals of Deep Learning, NVIDIA Fundamentals of Accelerated Data Science, NVIDIA Enhancing Data Science Outcomes With Efficient Workflow, CCNA-1, 7 MATLAB certifications.

**Languages:** Arabic (native), French (C1), English (C1), German (A2).

## Contact

📫 [LinkedIn](https://www.linkedin.com/in/yesmine-haddar-49517a338) · yesmine.haddar@supcom.tn
