---
permalink: /
author_profile: true
stylesheets:
  - /assets/css/home.css
redirect_from:
  - /about/
  - /about.html
---

<section class="hero-panel">
  <p class="eyebrow">Jin Li</p>
  <h1 class="main-heading">Multimodal Learning, LLMs, Diffusion Models, and Edge AI</h1>
  <p class="hero-copy">
    I am a B.Eng. student in Electronic Information Engineering at Hangzhou Dianzi University.
    My research spans user-defined keyword spotting, few-shot class-incremental learning,
    inference-time optimization for large language models, controllable virtual try-on evaluation,
    and multimodal environmental sensing.
  </p>
  <div class="hero-actions">
    <a class="action-button" href="files/LI_Jin_CV.pdf">CV</a>
    <a class="action-button" href="https://scholar.google.com/citations?user=SkpNdIoAAAAJ&hl=zh-CN" target="_blank" rel="noopener">Google Scholar</a>
    <a class="action-button" href="https://github.com/Rivflyyy" target="_blank" rel="noopener">GitHub</a>
  </div>
  <div class="research-tags">
    <span>Multimodal Learning</span>
    <span>Large Language Models</span>
    <span>Diffusion Models</span>
    <span>Keyword Spotting</span>
    <span>Intelligent Signal Processing</span>
  </div>
</section>

<h2 id="news">News</h2>
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.03</em></span> Algorithm internship at Hangzhou Renxing Intelligence Technology on ultra-high-resolution controllable image generation and OpenVTON-Bench.</li>
    <li><span class="news-date"><em>2026</em></span> KFC-KWS accepted to Interspeech 2026.</li>
    <li><span class="news-date"><em>2026</em></span> Spectral Logit Sculpting accepted to IEEE ICASSP 2026.</li>
    <li><span class="news-date"><em>2026</em></span> NC-KWS published in Springer LNCS, Man-Machine Speech Communication: NCMMSC 2025.</li>
    <li><span class="news-date"><em>2025</em></span> MRIE published in IEEE Access, Volume 13, pp. 88600-88608.</li>
    <li><span class="news-date"><em>2025</em></span> Research internship at Zhejiang University Binjiang Institute on LLM reasoning optimization.</li>
  </ul>
</div>

<h2 id="education">Education</h2>
<div class="experience-container">
  <div class="experience-card">
    <img src="images/hdu_slogan.png" alt="Hangzhou Dianzi University" class="experience-logo">
    <div class="experience-info">
      <strong>Hangzhou Dianzi University</strong><br>
      <em>Sep 2022 - Jun 2026</em><br>
      B.Eng. in Electronic Information Engineering · GPA: 89.59 / 100<br>
      <span class="muted">Key coursework: Machine Vision, Signal Detection and Processing, DSP and Intelligent Systems, Digital Signal Processing, Microelectronics, and EDA Technology.</span>
    </div>
  </div>
</div>

<h2 id="experience">Research & Internship Experience</h2>
<div class="experience-container">
  <div class="experience-card">
    <div class="experience-logo text-logo">RX</div>
    <div class="experience-info">
      <strong>Hangzhou Renxing Intelligence Technology Co., Ltd.</strong><br>
      <em>Algorithm Intern · Nov 2025 - Mar 2026</em><br>
      Worked on ultra-high-resolution controllable image generation based on diffusion models, pixel-space controlled generation pipelines, and a frequency-domain diffusion framework.
      <span class="muted">Optimized training with DeepSpeed, sequence parallelism, and memory strategies, reducing VRAM usage by about 30% and improving throughput by 1.3x-1.5x.</span>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo text-logo">ZJ</div>
    <div class="experience-info">
      <strong>Zhejiang University Binjiang Institute</strong><br>
      <em>Research Intern · May 2025 - Aug 2025</em><br>
      Designed reinforcement-learning reward functions for multi-turn LLM reasoning and proposed Spectral Logit Sculpting, an entropy-regulated online adaptive inference optimization method.
      <span class="muted">The resulting first-author paper was accepted to ICASSP 2026.</span>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo text-logo">KWS</div>
    <div class="experience-info">
      <strong>User-Defined Voice Command Recognition</strong><br>
      <em>Bachelor's Thesis · Outstanding Graduation Thesis · Sep 2025 - Present</em><br>
      Proposed KFC-KWS, a CTC-guided keyframe fusion framework with audio, phoneme, and text alignment for robust user-defined voice command recognition.
      <span class="muted">Implemented a Qt/FastAPI system supporting real-time detection and custom command management.</span>
    </div>
  </div>
  <div class="experience-card">
    <div class="experience-logo text-logo">RK</div>
    <div class="experience-info">
      <strong>Scalable Edge Command Recognition Systems</strong><br>
      <em>Team Leader / Algorithm Design · Jul 2024 - Sep 2025</em><br>
      Led and implemented keyword spotting systems with online adaptation, multimodal fusion, incremental learning, ONNX optimization, and C++ prefix beam search decoding on RK3588.
      <span class="muted">Reached over 95% accuracy under -5 to 15 dB SNR with sub-200 ms latency in one edge deployment.</span>
    </div>
  </div>
</div>

<h2 id="publications">Publications</h2>
<div class="pub-button-container">
  <button class="pub-button active" onclick="filterPublications(event, 'all')">Selected Publications</button>
  <button class="pub-button" onclick="filterPublications(event, 'list')">Full List</button>
</div>

<p class="legend">* equal contribution · &dagger; corresponding author / project lead</p>

<div id="core-publications" class="publication-view" data-publication-view="core">
  <div class="publication-card featured">
    <div class="card-row">
      <div class="pub-media-rotator" data-interval="4000">
        <img src="images/publications/openvton-bench.png" alt="OpenVTON-Bench poster">
      </div>
      <div>
        <strong>OpenVTON-Bench: A Large-Scale High-Resolution Benchmark for Controllable Virtual Try-On Evaluation</strong><br>
        <i>Jin Li*, Tao Chen*, Kai Wen, Siqi Yin, Shuai Jiang, Weijie Wang, Jingwen Luo, Chenhui Wu&dagger;.</i><br>
        A nearly 100K-pair high-resolution virtual try-on benchmark with semantic balancing, dense garment captions, VLM-as-a-Judge evaluation, and representation-based structural metrics aligned with human preference.
        <br>
        <b><i class="venue">arXiv 2026</i></b>
        <a href="https://arxiv.org/abs/2601.22725" target="_blank" rel="noopener"><em>[arXiv]</em></a>
        <a href="https://github.com/Rivflyyy/OpenVTON-Bench" target="_blank" rel="noopener"><em>[project]</em></a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="card-row">
      <div class="pub-media-rotator" data-interval="4000">
        <img src="images/publications/kfc-qbyekws.png" alt="KFC-KWS query-by-example keyword spotting">
      </div>
      <div>
        <strong>KFC-KWS: Keyframe Fusion with CTC for User-Defined Keyword Spotting</strong><br>
        <i>Jin Li, Wenbin Jiang, Ji Hu.</i><br>
        Uses CTC peaky posterior distributions to select phoneme keyframes, aligning audio, phoneme, and text modalities for discriminating highly confusable user-defined keywords.
        <br>
        <b><i class="venue">Interspeech 2026</i></b>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="card-row">
      <div class="pub-media-rotator" data-interval="4000">
        <img src="images/publications/sls-poster.png" alt="Spectral Logit Sculpting overview">
      </div>
      <div>
        <strong>Spectral Logit Sculpting: Adaptive Low-Rank Logit Transformation for Controlled Text Generation</strong><br>
        <i>Jin Li, Zhebo Wang, Tianliang Lu, Mohan Li, Wenpeng Xing, Meng Han.</i><br>
        An inference-time optimization method that uses spectral analysis, entropy statistics, and adaptive low-rank logit transformation to improve controlled text generation without parameter updates.
        <br>
        <b><i class="venue">ICASSP 2026</i></b>
        <a href="https://arxiv.org/pdf/2509.25204" target="_blank" rel="noopener"><em>[pdf]</em></a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="card-row">
      <div class="pub-media-rotator" data-interval="4000">
        <img src="images/publications/mrie-pipeline.png" alt="MRIE multimodal rainfall estimation pipeline">
      </div>
      <div>
        <strong>MRIE: Enhanced Rainfall Intensity Estimation with Two-Stage Multimodal Deep Learning</strong><br>
        <i>Jin Li, Wentao Hu, Zhigang Zhou.</i><br>
        A two-stage multimodal framework that integrates environmental sensor data and audio to improve rainfall intensity estimation through cross-modal guidance and feature aggregation.
        <br>
        <b><i class="venue">IEEE Access 2025</i></b>
        <a href="https://doi.org/10.1109/access.2025.3571440" target="_blank" rel="noopener"><em>[doi]</em></a>
      </div>
    </div>
  </div>

  <div class="publication-card">
    <div class="card-row">
      <div class="pub-media-rotator" data-interval="4000">
        <img src="images/publications/nc-kws.png" alt="NC-KWS few-shot class-incremental keyword spotting">
      </div>
      <div>
        <strong>NC-KWS: Few-Shot Class-Incremental Keyword Spotting Based on Neural Collapse</strong><br>
        <i>Jin Li, Wenbin Jiang, Yitao Tian, Zhuoyang Li.</i><br>
        Introduces neural-collapse-inspired feature-classifier alignment and an equiangular tight frame classifier for few-shot class-incremental keyword spotting.
        <br>
        <b><i class="venue">NCMMSC 2025 / Springer LNCS</i></b>
        <a href="https://doi.org/10.1007/978-981-95-5382-2_21" target="_blank" rel="noopener"><em>[doi]</em></a>
      </div>
    </div>
  </div>
</div>

<div id="full-publications" class="publication-view" data-publication-view="list" hidden>
  <ul class="full-publication-list">
    <li>
      <span class="pub-list-badge">ICASSP 2026</span>
      <span class="pub-list-title">Spectral Logit Sculpting: Adaptive Low-Rank Logit Transformation for Controlled Text Generation</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Zhebo Wang, Tianliang Lu, Mohan Li, Wenpeng Xing, Meng Han.</span>
      <span class="pub-list-note">Accepted.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2509.25204" target="_blank" rel="noopener">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">Interspeech 2026</span>
      <span class="pub-list-title">KFC-KWS: Keyframe Fusion with CTC for User-Defined Keyword Spotting</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wenbin Jiang, Ji Hu.</span>
      <span class="pub-list-note">Accepted.</span>
    </li>
    <li>
      <span class="pub-list-badge">arXiv 2026</span>
      <span class="pub-list-title">OpenVTON-Bench: A Large-Scale High-Resolution Benchmark for Controllable Virtual Try-On Evaluation</span><br>
      <span class="pub-list-authors"><strong>Jin Li*</strong>, Tao Chen*, Kai Wen, Siqi Yin, Shuai Jiang, Weijie Wang, Jingwen Luo, Chenhui Wu&dagger;.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2601.22725" target="_blank" rel="noopener">[arXiv]</a><a href="https://github.com/Rivflyyy/OpenVTON-Bench" target="_blank" rel="noopener">[project]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">NCMMSC 2025</span>
      <span class="pub-list-title">NC-KWS: Few-Shot Class-Incremental Keyword Spotting Based on Neural Collapse</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wenbin Jiang, Yitao Tian, Zhuoyang Li.</span>
      <span class="pub-list-links"><a href="https://doi.org/10.1007/978-981-95-5382-2_21" target="_blank" rel="noopener">[doi]</a></span>
    </li>
    <li>
      <span class="pub-list-badge">IEEE Access 2025</span>
      <span class="pub-list-title">MRIE: Enhanced Rainfall Intensity Estimation with Two-Stage Multimodal Deep Learning</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wentao Hu, Zhigang Zhou.</span>
      <span class="pub-list-links"><a href="https://doi.org/10.1109/access.2025.3571440" target="_blank" rel="noopener">[doi]</a></span>
    </li>
  </ul>
</div>

<h2 id="projects">Projects</h2>
<div class="project-card">
  <div class="card-row">
    <div class="project-media code-tile">torch</div>
    <div>
      <strong>HappyTorch</strong><br>
      <i>A LeetCode-style, self-hosted PyTorch practice platform.</i><br>
      Provides a focused environment for practicing PyTorch implementation tasks and building intuition for deep learning code.
      <br>
      <a href="https://github.com/Rivflyyy/HappyTorch" target="_blank" rel="noopener"><em>[code]</em></a>
    </div>
  </div>
</div>
<div class="project-card">
  <div class="card-row">
    <div class="pub-media-rotator project-media" data-interval="4000">
      <img src="images/publications/openvton-pipeline.png" alt="OpenVTON-Bench construction pipeline">
    </div>
    <div>
      <strong>OpenVTON-Bench</strong><br>
      <i>High-resolution benchmark and evaluation protocol for controllable virtual try-on.</i><br>
      Builds a large-scale VTON benchmark with semantic clustering, dense captions, multi-dimensional VLM scoring, and structural metrics for human-aligned evaluation.
      <br>
      <a href="https://github.com/Rivflyyy/OpenVTON-Bench" target="_blank" rel="noopener"><em>[code]</em></a>
    </div>
  </div>
</div>

<h2 id="awards">Selected Awards</h2>
<ul class="compact-list">
  <li>Bronze Award, 15th Zhejiang Province "Challenge Cup" College Students' Entrepreneurship Plan Competition, 2026.</li>
  <li>Third Prize, National Undergraduate Physics Experiment Innovation Competition, 2025.</li>
  <li>Third Prize, China College Service Outsourcing Innovation and Entrepreneurship Competition, 2025.</li>
  <li>Zhejiang Provincial Government Scholarship, 2025 & 2024.</li>
  <li>Second Prize, First National ICT Industry-Education Integration Innovation Competition, 2024.</li>
  <li>National Encouragement Scholarship, 2023.</li>
</ul>

<h2 id="patents">Patents</h2>
<ul class="compact-list">
  <li><strong>Fundus Image Recognition Method, System and Device Based on Deep Learning</strong>, CN119444719A, 2025.</li>
  <li><strong>Multimodal Multi-language Custom Instruction Recognition Method and System</strong>, CN120690187A, 2025.</li>
  <li><strong>Instruction Recognition Method and System Based on Online Unsupervised Learning</strong>, CN118366442A, 2024.</li>
</ul>

<h2 id="skills">Skills</h2>
<div class="research-tags skill-tags">
  <span>Python</span>
  <span>C/C++</span>
  <span>Java</span>
  <span>PyTorch</span>
  <span>TensorFlow</span>
  <span>ONNX</span>
  <span>FastAPI</span>
  <span>Qt</span>
  <span>DeepSpeed</span>
</div>
