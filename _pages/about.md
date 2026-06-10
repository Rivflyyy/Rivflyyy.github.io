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
  <h1 class="main-heading">Multimodal Learning, Large Language Models, and Diffusion Models</h1>
  <p class="hero-copy">
    My research began with intelligent signal processing and edge-oriented voice interaction,
    where I worked on robust command recognition and multimodal sensing systems.
    I then moved toward large language model reasoning, inference-time optimization,
    and multimodal generation evaluation. Looking ahead, I am especially interested in
    reliable multimodal intelligence, controllable diffusion models, and efficient LLM systems.
  </p>
  <div class="hero-actions">
    <a class="action-button" href="https://scholar.google.com/citations?user=SkpNdIoAAAAJ&hl=zh-CN" target="_blank" rel="noopener">Google Scholar</a>
    <a class="action-button" href="https://github.com/Rivflyyy" target="_blank" rel="noopener">GitHub</a>
  </div>
  <div class="research-tags">
    <span>Multimodal Learning</span>
    <span>Large Language Models</span>
    <span>Diffusion Models</span>
  </div>
</section>

<h2 id="news">News</h2>
<div class="news-box">
  <ul class="news-list">
    <li><span class="news-date"><em>2026.06</em></span> <strong>KFC-KWS</strong> was accepted to <em>Interspeech 2026</em>. This work studies user-defined keyword spotting with CTC-guided keyframe fusion.</li>
    <li><span class="news-date"><em>2026.05</em></span> <strong>OpenVTON-Bench</strong> was submitted to the <em>NeurIPS 2026 Datasets & Benchmarks Track</em>, focusing on high-resolution controllable virtual try-on evaluation.</li>
    <li><span class="news-date"><em>2026.01</em></span> <strong>Spectral Logit Sculpting</strong> was accepted to <em>IEEE ICASSP 2026</em>. The paper explores inference-time optimization for controlled text generation.</li>
    <li><span class="news-date"><em>2025.08</em></span> <strong>NC-KWS</strong> was accepted to <em>NCMMSC 2025</em>, bringing neural-collapse-inspired ideas to few-shot class-incremental keyword spotting.</li>
    <li><span class="news-date"><em>2025.05</em></span> <strong>MRIE</strong> was accepted to <em>IEEE Access</em>. This work investigates two-stage multimodal learning for rainfall intensity estimation.</li>
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
    <img src="images/bjy_slogan.jpeg" alt="Zhejiang University Binjiang Institute" class="experience-logo">
    <div class="experience-info">
      <strong>Zhejiang University Binjiang Institute</strong><br>
      <em>Research Intern · May 2025 - Aug 2025</em><br>
      Research on LLM reasoning and inference-time optimization.
    </div>
  </div>
  <div class="experience-card">
    <img src="images/iipl_slogan.png" alt="Intelligent Information Processing Lab" class="experience-logo">
    <div class="experience-info">
      <strong>Intelligent Information Processing Lab, Hangzhou Dianzi University</strong><br>
      <em>Undergraduate Researcher · Dec 2023 - Sep 2025</em><br>
      Research on edge intelligent signal processing and multimodal command recognition.
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
        <i><strong>Jin Li*</strong>, Tao Chen*, Kai Wen, Siqi Yin, Shuai Jiang, Weijie Wang, Jingwen Luo, Chenhui Wu&dagger;.</i><br>
        A nearly 100K-pair high-resolution virtual try-on benchmark with semantic balancing, dense garment captions, VLM-as-a-Judge evaluation, and representation-based structural metrics aligned with human preference.
        <br>
        <b><i class="venue">NeurIPS 2026 D&B Submission</i></b>
        <a href="https://arxiv.org/abs/2601.22725" target="_blank" rel="noopener"><em>[arXiv]</em></a>
        <a href="https://github.com/Rivflyyy/OpenVTON-Bench" target="_blank" rel="noopener"><em>[code]</em></a>
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
        <i><strong>Jin Li</strong>, Wenbin Jiang, Ji Hu.</i><br>
        Uses CTC peaky posterior distributions to select phoneme keyframes, aligning audio, phoneme, and text modalities for discriminating highly confusable user-defined keywords.
        <br>
        <b><i class="venue">Interspeech 2026</i></b>
        <a href="https://arxiv.org/abs/2606.10365" target="_blank" rel="noopener"><em>[arXiv]</em></a>
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
        <i><strong>Jin Li</strong>, Zhebo Wang, Tianliang Lu, Mohan Li, Wenpeng Xing, Meng Han.</i><br>
        An inference-time optimization method that uses spectral analysis, entropy statistics, and adaptive low-rank logit transformation to improve controlled text generation without parameter updates.
        <br>
        <b><i class="venue">ICASSP 2026</i></b>
        <a href="https://arxiv.org/pdf/2509.25204" target="_blank" rel="noopener"><em>[arXiv]</em></a>
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
        <i><strong>Jin Li</strong>, Wentao Hu, Zhigang Zhou.</i><br>
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
        <i><strong>Jin Li</strong>, Wenbin Jiang, Yitao Tian, Zhuoyang Li.</i><br>
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
      <span class="pub-list-badge"><em>ICASSP 2026</em></span>
      <span class="pub-list-title">Spectral Logit Sculpting: Adaptive Low-Rank Logit Transformation for Controlled Text Generation</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Zhebo Wang, Tianliang Lu, Mohan Li, Wenpeng Xing, Meng Han.</span>
      <span class="pub-list-note">Accepted.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2509.25204" target="_blank" rel="noopener">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge"><em>Interspeech 2026</em></span>
      <span class="pub-list-title">KFC-KWS: Keyframe Fusion with CTC for User-Defined Keyword Spotting</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wenbin Jiang, Ji Hu.</span>
      <span class="pub-list-note">Accepted.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2606.10365" target="_blank" rel="noopener">[arXiv]</a></span>
    </li>
    <li>
      <span class="pub-list-badge"><em>NeurIPS 2026 D&B</em></span>
      <span class="pub-list-title">OpenVTON-Bench: A Large-Scale High-Resolution Benchmark for Controllable Virtual Try-On Evaluation</span><br>
      <span class="pub-list-authors"><strong>Jin Li*</strong>, Tao Chen*, Kai Wen, Siqi Yin, Shuai Jiang, Weijie Wang, Jingwen Luo, Chenhui Wu&dagger;.</span>
      <span class="pub-list-links"><a href="https://arxiv.org/abs/2601.22725" target="_blank" rel="noopener">[arXiv]</a><a href="https://github.com/Rivflyyy/OpenVTON-Bench" target="_blank" rel="noopener">[code]</a></span>
    </li>
    <li>
      <span class="pub-list-badge"><em>NCMMSC 2025</em></span>
      <span class="pub-list-title">NC-KWS: Few-Shot Class-Incremental Keyword Spotting Based on Neural Collapse</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wenbin Jiang, Yitao Tian, Zhuoyang Li.</span>
      <span class="pub-list-links"><a href="https://doi.org/10.1007/978-981-95-5382-2_21" target="_blank" rel="noopener">[doi]</a></span>
    </li>
    <li>
      <span class="pub-list-badge"><em>IEEE Access 2025</em></span>
      <span class="pub-list-title">MRIE: Enhanced Rainfall Intensity Estimation with Two-Stage Multimodal Deep Learning</span><br>
      <span class="pub-list-authors"><strong>Jin Li</strong>, Wentao Hu, Zhigang Zhou.</span>
      <span class="pub-list-links"><a href="https://doi.org/10.1109/access.2025.3571440" target="_blank" rel="noopener">[doi]</a></span>
    </li>
  </ul>
</div>

<h2 id="projects">Projects</h2>
<div class="project-card">
  <div class="card-row">
    <div class="pub-media-rotator project-media" data-interval="4000">
      <img src="images/projects/happytorch.png" alt="HappyTorch platform screenshot">
    </div>
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

<h2 id="skills">Selected Skills</h2>
<div class="research-tags skill-tags">
  <span>Python</span>
  <span>PyTorch</span>
  <span>LLM Inference</span>
  <span>Multimodal Evaluation</span>
</div>
