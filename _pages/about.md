---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<link href="https://fonts.googleapis.com/css2?family=DM+Serif+Display:ital@0;1&family=DM+Mono:wght@400;500&family=Outfit:wght@300;400;500;600&display=swap" rel="stylesheet">

<style>
  :root {
    --ink: #0f0e0c;
    --ink2: #3a3832;
    --ink3: #7a7770;
    --paper: #faf9f6;
    --paper2: #f2f0eb;
    --paper3: #e8e5de;
    --accent: #c84b2f;
    --line: #ddd9d0;
    --serif: 'DM Serif Display', Georgia, serif;
    --sans: 'Outfit', sans-serif;
    --mono: 'DM Mono', monospace;
  }

  .page__content,
  .page__content p,
  .page__content li,
  .page__content a,
  .page__content summary {
    font-family: var(--sans) !important;
  }

  .page__content {
    font-size: 1rem;
    line-height: 1.75;
  }

  .page__content p {
    color: var(--ink2) !important;
    margin: 0 0 1rem;
  }

  .page__content strong, .page__content b {
    color: var(--ink);
    font-weight: 600;
  }

  .page__content a {
    color: var(--ink) !important;
    text-decoration: none !important;
    border-bottom: 1px solid var(--accent);
    padding-bottom: 1px;
    transition: color 0.15s;
  }

  .page__content a:hover {
    color: var(--accent) !important;
  }

  /* Override for tags — no underline border */
  .page__content a.tag-pdf,
  .page__content a.tag-pdf:hover {
    border-bottom: none !important;
    padding-bottom: 0 !important;
  }

  html, body, .layout--single, .page, .page__content {
    background: #faf9f6 !important;
  }

  /* SECTION HEADERS */
  .vr-section {
    display: flex;
    align-items: center;
    gap: 1rem;
    margin: 2.75rem 0 1.75rem;
  }

  .vr-section-num {
    font-family: var(--mono);
    font-size: 0.65rem;
    color: var(--ink3);
    letter-spacing: 0.1em;
  }

  .vr-section-title {
    font-family: var(--serif) !important;
    font-size: 1.7rem !important;
    letter-spacing: -0.02em;
    color: var(--ink) !important;
    margin: 0 !important;
    padding: 0 !important;
    border: none !important;
  }

  .vr-section-line {
    flex: 1;
    height: 1px;
    background: var(--line);
  }

  /* PAPER LIST */
  .vr-papers {
    list-style: none !important;
    padding: 0 !important;
    margin: 0 !important;
  }

  .vr-paper {
    display: grid;
    grid-template-columns: 2.25rem 1fr;
    gap: 0 1.5rem;
    padding: 1.5rem 0 !important;
    border-bottom: 1px solid var(--line);
    margin: 0 !important;
  }

  .vr-papers .vr-paper:first-child {
    border-top: 1px solid var(--line);
  }

  .vr-num {
    font-family: var(--mono);
    font-size: 0.7rem;
    color: var(--ink3);
    padding-top: 0.15rem;
  }

  .vr-title {
    font-family: var(--serif) !important;
    font-size: 1.08rem;
    color: var(--ink) !important;
    letter-spacing: -0.01em;
    line-height: 1.3;
    margin-bottom: 0.3rem;
    display: block;
  }

  .vr-authors {
    font-size: 0.82rem;
    color: var(--ink3);
    margin-bottom: 0.3rem;
    display: block;
    line-height: 1.5;
  }

  /* override link style inside authors */
  .page__content .vr-authors a {
    border-bottom: none !important;
    color: var(--ink3) !important;
    padding-bottom: 0 !important;
  }
  .page__content .vr-authors a:hover {
    color: var(--accent) !important;
  }

  .vr-venue {
    font-size: 0.8rem;
    color: var(--ink2);
    font-style: italic;
    margin-bottom: 0.5rem;
    display: block;
  }

  .vr-tags {
    display: flex;
    gap: 0.4rem;
    flex-wrap: wrap;
    align-items: center;
  }

  .tag {
    font-family: var(--mono) !important;
    font-size: 0.63rem !important;
    letter-spacing: 0.06em;
    padding: 0.18rem 0.55rem;
    border-radius: 2px;
    text-transform: uppercase;
    display: inline-flex;
    align-items: center;
    white-space: nowrap;
  }

  .tag-award {
    background: #fef2eb;
    color: var(--accent) !important;
    border: 1px solid #f5c9b3;
  }

  .tag-pdf {
    background: var(--paper3);
    color: var(--ink2) !important;
    border: 1px solid var(--line);
    text-decoration: none !important;
    transition: background 0.15s, color 0.15s;
    border-bottom: none !important;
    padding-bottom: 0.18rem !important;
  }

  .page__content a.tag-pdf:hover {
    background: var(--ink) !important;
    color: var(--paper) !important;
    border-color: var(--ink) !important;
  }

  /* TABS */
  .vr-tab-nav {
    display: flex;
    flex-wrap: wrap;
    border-bottom: 1px solid var(--line);
    margin-bottom: 0;
    gap: 0;
  }

  .vr-tab-btn {
    font-family: var(--mono) !important;
    font-size: 0.68rem;
    letter-spacing: 0.06em;
    text-transform: uppercase;
    padding: 0.65rem 1rem;
    border: none;
    background: none;
    color: var(--ink3);
    cursor: pointer;
    border-bottom: 2px solid transparent;
    margin-bottom: -1px;
    transition: color 0.15s, border-color 0.15s;
  }

  .vr-tab-btn.active {
    color: var(--ink);
    border-bottom-color: var(--accent);
  }

  .vr-tab-btn:hover { color: var(--ink2); }

  .vr-tab-panel { display: none; }
  .vr-tab-panel.active {
    display: flex;
    flex-direction: column;
  }

  /* Intro badges */
  .vr-badge-row {
    display: flex;
    flex-wrap: wrap;
    gap: 0.45rem;
    margin-top: 1.25rem;
    padding-top: 1.25rem;
    border-top: 1px solid var(--line);
  }

  .vr-badge {
    font-family: var(--mono) !important;
    font-size: 0.65rem;
    letter-spacing: 0.07em;
    padding: 0.28rem 0.7rem;
    border-radius: 2px;
    text-transform: uppercase;
    border: 1px solid var(--ink3);
    color: var(--ink3) !important;
    border-bottom: 1px solid var(--ink3) !important;
  }
</style>

<p>
I'm a <strong>Research Scientist</strong> at <a href="https://deepmind.google">Google DeepMind</a> working on improving Gemini's fundamental capabilities for generative and agentic retrieval.
</p>

<p>
I completed my Ph.D. in <a href="https://lsa.umich.edu/stats">Statistics</a> at the <a href="https://umich.edu/">University of Michigan</a> in 2025, where I was fortunate to be advised by <a href="https://ambujtewari.github.io">Ambuj Tewari</a>. My Ph.D. was graciously supported by the <a href="https://www.nsfgrfp.org">2022 National Science Foundation Graduate Research Fellowship (NSF GRFP)</a> and the <a href="https://machinelearning.apple.com/updates/apple-scholars-aiml-2025">2025 Apple Scholars in AI/ML PhD Fellowship</a>. Prior to my Ph.D, I double-majored in <a href="https://cse.engin.umich.edu/">Computer Science</a> and <a href="https://che.engin.umich.edu/">Chemical Engineering</a> and worked with <a href="https://mahdi.ch">Mahdi Cheraghchi</a>, <a href="https://web.eecs.umich.edu/~skutty/">Sindhu Kutty</a>, and <a href="https://lenert.engin.umich.edu">Andrej Lenert</a>.
</p>

<p>
My research interests lie in the <strong>Foundations of Machine Learning</strong>. During my Ph.D, I worked on various topics in learning theory, including online learning, adversarial robustness, differential privacy, and language generation. Nowadays, I work broadly in <strong>Post-training</strong> and <strong>Reinforcement Learning</strong> for large language models.
</p>

<p>My <a href="https://ananthsraman.github.io/">younger brother</a> is a classical trumpeter.</p>

<div class="vr-badge-row">
  <span class="vr-badge">Learning Theory</span>
  <span class="vr-badge">Online Learning</span>
  <span class="vr-badge">Differential Privacy</span>
  <span class="vr-badge">Post-training LLMs</span>
  <span class="vr-badge">RL for LLMs</span>
</div>

<!-- SELECTED PUBLICATIONS -->
<div class="vr-section">
  <span class="vr-section-num">01</span>
  <h2 class="vr-section-title">Selected Publications</h2>
  <div class="vr-section-line"></div>
</div>

<ul class="vr-papers">
  <li class="vr-paper">
    <span class="vr-num">S1</span>
    <div>
      <span class="vr-title">Missing Mass for Differentially Private Domain Discovery</span>
      <span class="vr-authors">with <a href="https://www.majos.net">Matthew Joseph</a>, <a href="https://travisbarrydick.github.io">Travis Dick</a></span>
      <span class="vr-venue">International Conference on Learning Representations (ICLR), 2026</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Oral</span>
        <a href="http://arxiv.org/abs/2603.14016" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">S2</span>
    <div>
      <span class="vr-title">Generation through the lens of learning theory</span>
      <span class="vr-authors">with <a href="https://jiaxun-li.github.io">Jiaxun Li</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Conference on Learning Theory (COLT), 2025</span>
      <div class="vr-tags">
        <a href="https://arxiv.org/abs/2410.13714" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">S3</span>
    <div>
      <span class="vr-title">Apple Tasting: Combinatorial Dimensions and Minimax Rates</span>
      <span class="vr-authors">with <a href="https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en">Ananth Raman</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Conference on Learning Theory (COLT), 2024</span>
      <div class="vr-tags">
        <a href="https://arxiv.org/abs/2310.19064" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
</ul>

<!-- IN SUBMISSION -->
<div class="vr-section">
  <span class="vr-section-num">02</span>
  <h2 class="vr-section-title">In Submission</h2>
  <div class="vr-section-line"></div>
</div>

<ul class="vr-papers">
  <li class="vr-paper">
    <span class="vr-num">W1</span>
    <div>
      <span class="vr-title">GroupDPO: Memory Efficient Group-wise Direct Preference Optimization</span>
      <span class="vr-authors">with Jixuan Leng, <a href="https://springdaisy.github.io/">Si Si</a>, <a href="https://www.cs.utexas.edu/~rofuyu/">Hsiang-Fu Yu</a>, <a href="https://www.cs.utexas.edu/~inderjit/">Inderjit S Dhillon</a></span>
      <span class="vr-venue">In Submission, 2026</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2604.15602" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">W2</span>
    <div>
      <span class="vr-title">On Generation in Metric Spaces</span>
      <span class="vr-authors">with <a href="https://jiaxun-li.github.io">Jiaxun Li</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">In Submission, 2026</span>
      <div class="vr-tags"><a href="https://www.arxiv.org/abs/2602.07710" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">W3</span>
    <div>
      <span class="vr-title">Optimal Stopping vs Best-of-N for Inference Time Optimization</span>
      <span class="vr-authors">with <a href="https://yhkalayci.github.io">Yusuf Kalayci</a>, <a href="https://viterbi-web.usc.edu/~shaddin/">Shaddin Dughmi</a></span>
      <span class="vr-venue">In Submission, 2026</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2510.01394" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<!-- PREPRINTS -->
<div class="vr-section">
  <span class="vr-section-num">03</span>
  <h2 class="vr-section-title">Preprints</h2>
  <div class="vr-section-line"></div>
</div>

<ul class="vr-papers">
  <li class="vr-paper">
    <span class="vr-num">P1</span>
    <div>
      <span class="vr-title">Estimating the (Un)seen: Sample-dependent Mass Estimation</span>
      <span class="vr-authors">with <a href="https://vtaly.net">Vitaly Feldman</a>, <a href="https://www.satyenkale.com">Satyen Kale</a>, <a href="http://kunaltalwar.org">Kunal Talwar</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Preprint, 2025</span>
      <div class="vr-tags"><a href="https://drive.google.com/file/d/18z-DqgBSlZ8jpujniqn3MedjLYBvT4Zp/view?usp=share_link" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">P2</span>
    <div>
      <span class="vr-title">AdaBoN: Adaptive Best-of-N Alignment</span>
      <span class="vr-authors">with <a href="https://web.stanford.edu/~asi/">Hilal Asi</a>, <a href="https://www.satyenkale.com">Satyen Kale</a></span>
      <span class="vr-venue">Preprint, 2026</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2505.12050" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">P3</span>
    <div>
      <span class="vr-title">Transductive and Learning-Augmented Online Regression</span>
      <span class="vr-authors">with <a href="https://sites.google.com/view/shenghaoxie/">Shenghao Xie</a>, <a href="https://samsonzhou.github.io">Samson Zhou</a></span>
      <span class="vr-venue">Preprint, 2025</span>
      <div class="vr-tags"><a href="http://arxiv.org/abs/2510.03917" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">P4</span>
    <div>
      <span class="vr-title">Online Boosting for Multilabel Ranking with Top-k Feedback</span>
      <span class="vr-authors">with Daniel T. Zhang, Young Hun Jung, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Preprint, 2020</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/1910.10937" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<!-- ALL PUBLICATIONS -->
<div class="vr-section">
  <span class="vr-section-num">04</span>
  <h2 class="vr-section-title">All Publications</h2>
  <div class="vr-section-line"></div>
</div>

<div class="vr-tab-nav" id="vr-tabs">
  <button class="vr-tab-btn active" data-tab="llm">LLMs</button>
  <button class="vr-tab-btn" data-tab="gen">Generation</button>
  <button class="vr-tab-btn" data-tab="dp">Diff. Privacy</button>
  <button class="vr-tab-btn" data-tab="robust">Robustness</button>
  <button class="vr-tab-btn" data-tab="online">Online Learning</button>
  <button class="vr-tab-btn" data-tab="partial">Partial Feedback</button>
  <button class="vr-tab-btn" data-tab="multi">Multioutput</button>
  <button class="vr-tab-btn" data-tab="other">Other</button>
</div>

<ul class="vr-papers vr-tab-panel active" id="vr-tab-llm">
  <li class="vr-paper">
    <span class="vr-num">1</span>
    <div>
      <span class="vr-title">AI-rithmetic</span>
      <span class="vr-authors">with <a href="https://alexbie98.github.io/">Alex Bie</a>, <a href="https://travisbarrydick.github.io/">Travis Dick</a>, <a href="https://scholar.google.com/citations?user=2OUGYFAAAAAJ&hl=en">Alex Kulesza</a>, <a href="https://research.google/people/prabhakarraghavan/?&type=google">Prabhakar Raghavan</a>, <a href="https://theory.stanford.edu/~sergei/">Sergei Vassilvitskii</a></span>
      <span class="vr-venue">ICLR Workshop on I Can't Believe It's Not Better (ICBINB), 2026</span>
      <div class="vr-tags"><a href="https://www.arxiv.org/abs/2602.10416" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-gen">
  <li class="vr-paper">
    <span class="vr-num">2</span>
    <div>
      <span class="vr-title">Learning to Choose or Choosing to Learn: Best-of-N vs. Supervised Fine-Tuning for Bit String Generation</span>
      <span class="vr-authors">with <a href="https://somerstep.github.io">Seamus Somerstep</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://yuekai.github.io">Yuekai Sun</a></span>
      <span class="vr-venue">AISTATS 2026 · DeepMath 2025</span>
      <div class="vr-tags"><a href="http://arxiv.org/abs/2505.17288" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">3</span>
    <div>
      <span class="vr-title">Generation through the lens of learning theory</span>
      <span class="vr-authors">with <a href="https://jiaxun-li.github.io">Jiaxun Li</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Conference on Learning Theory (COLT), 2025</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2410.13714" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">4</span>
    <div>
      <span class="vr-title">Representative Language Generation</span>
      <span class="vr-authors">with <a href="https://cpeale.github.io">Charlotte Peale</a>, <a href="https://omereingold.wordpress.com">Omer Reingold</a></span>
      <span class="vr-venue">International Conference on Machine Learning (ICML), 2025</span>
      <div class="vr-tags"><a href="http://arxiv.org/abs/2505.21819" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">5</span>
    <div>
      <span class="vr-title">Generation from Noisy Examples</span>
      <span class="vr-authors">with <a href="https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en">Ananth Raman</a></span>
      <span class="vr-venue">International Conference on Machine Learning (ICML), 2025</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2501.04179" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-dp">
  <li class="vr-paper">
    <span class="vr-num">6</span>
    <div>
      <span class="vr-title">Missing Mass for Differentially Private Domain Discovery</span>
      <span class="vr-authors">with <a href="https://www.majos.net">Matthew Joseph</a>, <a href="https://travisbarrydick.github.io">Travis Dick</a></span>
      <span class="vr-venue">ICLR, 2026</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Oral</span>
        <a href="http://arxiv.org/abs/2603.14016" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">7</span>
    <div>
      <span class="vr-title">Tracking the Best Expert Privately</span>
      <span class="vr-authors">with <a href="https://web.stanford.edu/~asi/">Hilal Asi</a>, <a href="https://aadirupa.github.io">Aadirupa Saha</a></span>
      <span class="vr-venue">ICML, 2025</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2503.09889" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">8</span>
    <div>
      <span class="vr-title">Faster Rates for Private Adversarial Bandits</span>
      <span class="vr-authors">with <a href="https://web.stanford.edu/~asi/">Hilal Asi</a>, <a href="http://kunaltalwar.org">Kunal Talwar</a></span>
      <span class="vr-venue">ICML, 2025</span>
      <div class="vr-tags"><a href="http://arxiv.org/abs/2505.21790" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-robust">
  <li class="vr-paper">
    <span class="vr-num">9</span>
    <div>
      <span class="vr-title">Online Classification with Predictions</span>
      <span class="vr-authors">with <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">NeurIPS, 2024</span>
      <div class="vr-tags"><a href="http://arxiv.org/abs/2405.14066" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">10</span>
    <div>
      <span class="vr-title">Smoothed Online Classification can be Harder than Batch Classification</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">NeurIPS, 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/pdf/2405.15424" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">11</span>
    <div>
      <span class="vr-title">Multiclass Transductive Online Learning</span>
      <span class="vr-authors">with <a href="https://stevehanneke.com">Steve Hanneke</a>, <a href="https://scholar.google.com/citations?user=nRTM5b8AAAAJ&hl=en">Amirreza Shaeiri</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a></span>
      <span class="vr-venue">NeurIPS, 2024</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Spotlight</span>
        <a href="http://arxiv.org/abs/2411.01634" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">12</span>
    <div>
      <span class="vr-title">On Proper Learnability between Average- and Worst-case Robustness</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">NeurIPS, 2023</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2211.05656" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-online">
  <li class="vr-paper">
    <span class="vr-num">13</span>
    <div>
      <span class="vr-title">The Complexity of Sequential Prediction in Dynamical Systems</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">L4DC, 2025</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Oral</span>
        <a href="https://arxiv.org/abs/2402.06614" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">14</span>
    <div>
      <span class="vr-title">A Unified Theory of Supervised Online Learnability</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">ALT, 2025</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Outstanding Paper</span>
        <a href="https://arxiv.org/abs/2307.03816" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">15</span>
    <div>
      <span class="vr-title">Online Learning with Set-Valued Feedback</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">COLT, 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2306.06247" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">16</span>
    <div>
      <span class="vr-title">Online Infinite-Dimensional Regression: Learning Linear Operators</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">ALT, 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2309.06548" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">17</span>
    <div>
      <span class="vr-title">Multiclass Online Learning and Uniform Convergence</span>
      <span class="vr-authors">with <a href="https://stevehanneke.com">Steve Hanneke</a>, <a href="https://csaws.cs.technion.ac.il/~shaymrn/">Shay Moran</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">COLT, 2023</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2303.17716" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">18</span>
    <div>
      <span class="vr-title">Online Agnostic Multiclass Boosting</span>
      <span class="vr-authors">with <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">NeurIPS, 2022</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2205.15113" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-partial">
  <li class="vr-paper">
    <span class="vr-num">19</span>
    <div>
      <span class="vr-title">Apple Tasting: Combinatorial Dimensions and Minimax Rates</span>
      <span class="vr-authors">with <a href="https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en">Ananth Raman</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">COLT, 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2310.19064" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">20</span>
    <div>
      <span class="vr-title">Multiclass Online Learnability under Bandit Feedback</span>
      <span class="vr-authors">with <a href="https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en">Ananth Raman</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://idanmehalel.wordpress.com">Idan Mehalel</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">ALT, 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2308.04620" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-multi">
  <li class="vr-paper">
    <span class="vr-num">21</span>
    <div>
      <span class="vr-title">A Characterization of Multioutput Learnability</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">Journal of Machine Learning Research (JMLR), 2024</span>
      <div class="vr-tags"><a href="https://arxiv.org/abs/2301.02729" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
  <li class="vr-paper">
    <span class="vr-num">22</span>
    <div>
      <span class="vr-title">On the Learnability of Multilabel Ranking</span>
      <span class="vr-authors">with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a></span>
      <span class="vr-venue">NeurIPS, 2023</span>
      <div class="vr-tags">
        <span class="tag tag-award">★ Spotlight</span>
        <a href="https://arxiv.org/abs/2304.03337" class="tag tag-pdf">PDF</a>
      </div>
    </div>
  </li>
</ul>

<ul class="vr-papers vr-tab-panel" id="vr-tab-other">
  <li class="vr-paper">
    <span class="vr-num">23</span>
    <div>
      <span class="vr-title">Design of thermophotovoltaics for tolerance of parasitic absorption</span>
      <span class="vr-authors">with Tobias Burger, <a href="https://lenert.engin.umich.edu">Andrej Lenert</a></span>
      <span class="vr-venue">Optics Express, 2019</span>
      <div class="vr-tags"><a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-22-31757&id=422403" class="tag tag-pdf">PDF</a></div>
    </div>
  </li>
</ul>

<script>
document.getElementById('vr-tabs').addEventListener('click', function(e) {
  var btn = e.target.closest('.vr-tab-btn');
  if (!btn) return;
  document.querySelectorAll('.vr-tab-btn').forEach(function(b) { b.classList.remove('active'); });
  document.querySelectorAll('.vr-tab-panel').forEach(function(p) { p.classList.remove('active'); });
  btn.classList.add('active');
  document.getElementById('vr-tab-' + btn.dataset.tab).classList.add('active');
});
</script>
