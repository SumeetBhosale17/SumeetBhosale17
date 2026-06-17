# Sumeet Bhosale

Final-year B.Tech Computer Science. I build ML systems end to end and care about what's *under* the model — numerical linear algebra, optimization, and compiler/parser design are my base, and I'm deliberately building from there toward ML systems and inference.

I'd rather ship one thing that actually runs and understand it fully than collect frameworks.

### What I've built

- **[churn-predictor](https://github.com/SumeetBhosale17/churn-predictor)** — end-to-end ML service: 5-fold stratified CV, model selection on F1-for-the-minority-class (not accuracy), FastAPI + Pydantic validation, Docker, deployed live with request logging and a `/metrics` endpoint. → [live demo](https://churn-predictor-jubh.onrender.com)
- **[mini-code-assistant](https://github.com/SumeetBhosale17/mini-code-assistant)** — a code-RAG assistant: AST-based chunking → embeddings → FAISS → LLM, built to understand the retrieval-augmented-generation pipeline stage by stage, with a why/how/when/what write-up for each stage.
- **[least-squares-spectral-tour](https://github.com/SumeetBhosale17/least-squares-spectral-tour)** — eight least-squares solvers benchmarked and the textbook "Gradient Descent vs Normal Equation" binary dismantled via the condition number κ. Reproducible experiments + a full write-up. → [read it](https://sumeetbhosale17.github.io/least-squares-spectral-tour/)
- **[fastbowling-analysis](https://github.com/SumeetBhosale17/fastbowling-analysis)** — computer-vision pipeline (MediaPipe pose) for cricket fast-bowling biomechanics; config-driven, streaming, QA-gated. *In active development — currently the video-ingest + pose-estimation foundation.*
- **Offline-First Manufacturing & Billing System** *(private, deployed)* — a Java 21 / JavaFX / SQLite desktop ERP running a real RCC-pipe manufacturer's full business cycle: GST-compliant invoicing, inventory, production tracking, party ledgers, and P&L — shipped as a one-click Windows installer for a non-technical operator.

### Tools

Python · scikit-learn · NumPy / Pandas · FastAPI · Docker · FAISS · MediaPipe / OpenCV · Java · C / C++ · SQL · Git / Linux

*Currently going deeper into deep learning + PyTorch, and ML systems / inference.*

### Writing

I write about ML topics where the math meets the experiment — the least-squares solver tour above is the first. More in the same vein coming.

### Reach me

[LinkedIn](https://www.linkedin.com/in/sumeetbhosale17) · [GitHub](https://github.com/SumeetBhosale17)
