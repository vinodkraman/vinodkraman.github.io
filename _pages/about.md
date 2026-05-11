---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

<style>
  :root {
    --text: #111827;
    --muted: #4b5563;
    --soft: #6b7280;
    --line: #e5e7eb;
    --surface: #ffffff;
    --surface-soft: #f8fafc;
    --accent: #2563eb;
    --accent-soft: #eff6ff;
    --award: #b91c1c;
    --award-soft: #fef2f2;
    --shadow: 0 10px 30px rgba(15, 23, 42, 0.06);
  }

  body, h1, h2, h3, h4, h5, h6, p, li, a, summary {
    font-family: Inter, ui-sans-serif, system-ui, -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Helvetica, Arial, sans-serif;
    color: var(--text);
  }

  .page__content {
    font-size: 0.98rem;
    line-height: 1.75;
  }

  .page__content p {
    color: var(--muted) !important;
    margin: 0 0 1.05rem;
  }

  .page__content strong,
  .page__content b {
    color: var(--text);
    font-weight: 700;
  }

  .page__content a {
    color: var(--text) !important;
    text-decoration: none !important;
    text-underline-offset: 3px;
    transition: color 160ms ease, background-color 160ms ease, border-color 160ms ease, transform 160ms ease;
  }

  .page__content p a,
  .page__content li a:not(.paper-badge) {
    border-bottom: 1px solid rgba(37, 99, 235, 0.25);
  }

  .page__content p a:hover,
  .page__content li a:not(.paper-badge):hover {
    color: var(--accent) !important;
    border-bottom-color: rgba(37, 99, 235, 0.65);
  }

  .page__content details {
    margin: 1.25rem 0;
    padding: 1.05rem 1.15rem;
    background: linear-gradient(180deg, var(--surface), var(--surface-soft));
    border: 1px solid var(--line);
    border-radius: 18px;
    box-shadow: var(--shadow);
  }

  .page__content details details {
    margin: 0.85rem 0 0.85rem 0 !important;
    padding: 0.85rem 0.95rem;
    border-radius: 14px;
    box-shadow: none;
    background: rgba(255, 255, 255, 0.72);
  }

  .page__content summary {
    cursor: pointer;
    list-style: none;
  }

  .page__content summary::-webkit-details-marker {
    display: none;
  }

  .page__content summary::before {
    content: "▸";
    display: inline-block;
    margin-right: 0.55rem;
    color: var(--accent);
    font-size: 0.9rem;
    transform: translateY(-1px);
    transition: transform 160ms ease;
  }

  .page__content details[open] > summary::before {
    transform: rotate(90deg) translateX(1px);
  }

  .page__content summary h1,
  .page__content summary h3 {
    display: inline-block !important;
    margin: 0 !important;
    color: var(--text) !important;
    letter-spacing: -0.025em;
  }

  .page__content summary h1 {
    font-size: clamp(1.25rem, 2vw, 1.65rem);
  }

  .page__content summary h3 {
    font-size: 1.02rem;
    color: var(--muted) !important;
  }

  .page__content ol,
  .page__content ul {
    margin-top: 1rem;
    padding-left: 1.35rem;
  }

  .page__content li {
    margin: 0.85rem 0;
    padding-left: 0.25rem;
    color: var(--muted);
  }

  .page__content li::marker {
    color: var(--soft);
    font-weight: 600;
  }

  .page__content li b:first-child {
    font-size: 1.01rem;
  }

  .page__content i {
    color: var(--soft);
  }

  .paper-badge, .award-badge {
    display: inline-flex;
    align-items: center;
    gap: 0.25rem;
    padding: 0.18rem 0.55rem;
    margin-left: 0.35rem;
    border-radius: 999px;
    border: 1px solid transparent;
    font-size: 0.72rem;
    font-weight: 700;
    line-height: 1.2;
    vertical-align: middle;
    white-space: nowrap;
  }

  .paper-badge {
    color: var(--accent) !important;
    background: var(--accent-soft);
    border-color: #bfdbfe;
  }

  .paper-badge:hover {
    background: #dbeafe;
    transform: translateY(-1px);
  }

  .award-badge {
    color: var(--award);
    background: var(--award-soft);
    border-color: #fecaca;
  }



  /* Keep this page light even if the site/browser is in dark mode.
     The original theme does not fully support dark mode, so forcing dark
     variables created white text on a white page. */
  html, body, .layout--single, .page, .page__content {
    background: #ffffff !important;
  }

  .page__content {
    color-scheme: light;
  }
</style>

<p>
I'm a <strong>Research Scientist</strong> at <b><a href="https://deepmind.google">Google DeepMind</a></b> working on improving Gemini's fundamental capabilities for generative and agentic retrieval.
</p>

<p>
I completed my Ph.D. in <b><a href="https://lsa.umich.edu/stats">Statistics</a></b> at the <b><a href="https://umich.edu/">University of Michigan</a></b> in 2025, where I was fortunate to be advised by <b><a href="https://ambujtewari.github.io">Ambuj Tewari</a></b>. My Ph.D. was graciously supported by the <b><a href="https://www.nsfgrfp.org"> 2022 National Science Foundation Graduate Research Fellowship (NSF GRFP)</a></b> and the <b><a href="https://machinelearning.apple.com/updates/apple-scholars-aiml-2025"> 2025 Apple Scholars in AI/ML PhD Fellowship</a></b>. Prior to my Ph.D, I double-majored in <b><a href="https://cse.engin.umich.edu/">Computer Science</a></b> and <b><a href="https://che.engin.umich.edu/">Chemical Engineering</a></b> and worked with <b><a href="https://mahdi.ch">Mahdi Cheraghchi</a></b>, <b><a href="https://web.eecs.umich.edu/~skutty/">Sindhu Kutty</a></b>, and <b><a href="https://lenert.engin.umich.edu">Andrej Lenert</a></b>. 
</p>

<p>
My research interests lie in the <strong>Foundations of Machine Learning</strong>. During my Ph.D, I worked on various topics in learning theory, including online learning, adversarial robustness, differential privacy, and language generation, among other things. Nowadays, I work broadly in <strong>post-training</strong> and <strong>RL</strong> for large language models. 
</p>

<p>
Apart from research, I am a fan of bodybuilding and actively keep up with the <b><a href="https://mrolympia.com">Mr. Olympia</a></b>.
</p>

<details open>
<summary><h1>Selected Publications</h1></summary>
<ol>
<li><b>Missing Mass for Differentially Private Domain Discovery</b> <span class="award-badge">Oral</span> <a href="http://arxiv.org/abs/2603.14016" class="paper-badge">PDF</a><br>
     with <a href="https://www.majos.net"> Matthew Joseph </a>, <a href="https://travisbarrydick.github.io"> Travis Dick </a><br>
      <i>International Conference on Learning Representations (ICLR)</i>, 2026.</li>
<li><b>Generation through the lens of learning theory</b> <a href="https://arxiv.org/abs/2410.13714" class="paper-badge">PDF</a><br>
      with <a href="https://jiaxun-li.github.io"> Jiaxun Li </a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Learning Theory (COLT)</i>, 2025.</li>
<li><b>A Unified Theory of Supervised Online Learnability</b> <span class="award-badge">Outstanding Paper</span><a href="https://arxiv.org/abs/2307.03816" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Algorithmic Learning Theory (ALT)</i>, 2025.</li>
</ol>
</details>


<details>
<summary><h1>Preprints</h1></summary>
<ol>
<li><b>Estimating the (Un)seen: Sample-dependent Mass Estimation</b> <a href="https://drive.google.com/file/d/18z-DqgBSlZ8jpujniqn3MedjLYBvT4Zp/view?usp=share_link" class="paper-badge">PDF</a><br>
    with <a href="https://vtaly.net">Vitaly Feldman</a>, <a href="https://www.satyenkale.com">Satyen Kale</a>, <a href="http://kunaltalwar.org">Kunal Talwar</a>, and <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
    <i>Preprint</i>, 2025.</li>
<li><b>Transductive and Learning-Augmented Online Regression</b> <a href="http://arxiv.org/abs/2510.03917" class="paper-badge">PDF</a><br>
   with <a href="https://sites.google.com/view/shenghaoxie/"> Shenghao Xie </a>, <a href="https://samsonzhou.github.io"> Samson Zhou </a><br>
    <i>Preprint</i>, 2025.</li>
<li><b>Online Boosting for Multilabel Ranking with Top-k Feedback</b> <a href="https://arxiv.org/abs/1910.10937" class="paper-badge">PDF</a><br>
    with Daniel T. Zhang, Young Hun Jung, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
    <i>Preprint</i>, 2020.</li>
</ol>
</details>

<details open>
<summary><h1>In Submission</h1></summary>
<ol>
<li><b>GroupDPO: Memory efficient Group-wise Direct Preference Optimization</b><a href="https://arxiv.org/abs/2604.15602" class="paper-badge">PDF</a><br>
    with Jixuan Leng, <a href="https://springdaisy.github.io/"> Si Si </a>, <a href="https://www.cs.utexas.edu/~rofuyu/"> Hsiang-Fu Yu </a>, <a href="https://www.cs.utexas.edu/~inderjit/"> Inderjit S Dhillon</a><br>
    <i>In Submission</i>, 2026.</li>
<li><b>On Generation in Metric Spaces</b> <a href="https://www.arxiv.org/abs/2602.07710" class="paper-badge">PDF</a><br>
    with <a href="https://jiaxun-li.github.io"> Jiaxun Li </a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
    <i>In Submission</i>, 2026.</li>
 <li><b>Optimal Stopping vs Best-of-N for Inference Time Optimization</b> <a href="https://arxiv.org/abs/2510.01394" class="paper-badge">PDF</a><br>
   with <a href="https://yhkalayci.github.io"> Yusuf Kalayci </a>, <a href="https://viterbi-web.usc.edu/~shaddin/"> Shaddin Dughmi </a><br>
    <i>In Submission</i>, 2026.</li>
 <li><b>AdaBoN: Adaptive Best-of-N Alignment</b> <a href="https://arxiv.org/abs/2505.12050" class="paper-badge">PDF</a><br>
    with <a href="https://web.stanford.edu/~asi/"> Hilal Asi </a>, <a href="https://www.satyenkale.com"> Satyen Kale </a><br>
    <i>In Submission</i>, 2026.</li>
</ol>
</details>

<details open>
<summary><h1>All Publications</h1></summary>

  <details open>
  <summary><h3>Large Language Models</h3></summary>
  <ol>
  <li><b>AI-rithmetic</b> <a href="https://www.arxiv.org/abs/2602.10416" class="paper-badge">PDF</a><br>
    with <a href="https://alexbie98.github.io/">Alex Bie</a>, <a href="https://travisbarrydick.github.io/">Travis Dick</a>, <a href="https://scholar.google.com/citations?user=2OUGYFAAAAAJ&hl=en">Alex Kulesza</a>, <a href="https://research.google/people/prabhakarraghavan/?&type=google">Prabhakar Raghavan</a>, <a href="https://theory.stanford.edu/~sergei/">Sergei Vassilvitskii</a> <br>
    <i>ICLR Workshop on I Can't Believe It's Not Better (ICBINB)</i>, 2026.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Language Generation</h3></summary>
  <ol start="2">
  <li><b>Learning to Choose or Choosing to Learn: Best-of-N vs. Supervised Fine-Tuning for Bit String Generation</b> <a href="http://arxiv.org/abs/2505.17288" class="paper-badge">PDF</a><br>
     with <a href="https://somerstep.github.io"> Seamus Somerstep </a>, <a href="https://unique-subedi.github.io"> Unique Subedi </a>,<a href="https://yuekai.github.io"> Yuekai Sun </a><br>
      <i>Conference on Artificial Intelligence and Statistics (AISTATS)</i>, 2026.<br>
     also at <i>Conference on the Mathematical Theory of Deep Neural Networks (DeepMath)</i>, 2025.</li>
      
  <li><b>Generation through the lens of learning theory</b> <a href="https://arxiv.org/abs/2410.13714" class="paper-badge">PDF</a><br>
      with <a href="https://jiaxun-li.github.io"> Jiaxun Li </a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Learning Theory (COLT)</i>, 2025.</li>
     
  <li><b>Representative Language Generation</b> <a href="http://arxiv.org/abs/2505.21819" class="paper-badge">PDF</a><br>
      with <a href="https://cpeale.github.io"> Charlotte Peale </a>, <a href="https://omereingold.wordpress.com">Omer Reingold</a><br>
      <i>International Conference on Machine Learning (ICML)</i>, 2025.</li>
      
  <li><b>Generation from Noisy Examples</b> <a href= "https://arxiv.org/abs/2501.04179" class="paper-badge">PDF</a><br>
      with <a href= "https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en"> Ananth Raman </a><br>
      <i>International Conference on Machine Learning (ICML)</i>, 2025.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Differential Privacy</h3></summary>
  <ol start="6">
  <li><b>Missing Mass for Differentially Private Domain Discovery</b> <span class="award-badge">Oral</span> <a href="http://arxiv.org/abs/2603.14016" class="paper-badge">PDF</a><br>
     with <a href="https://www.majos.net"> Matthew Joseph </a>, <a href="https://travisbarrydick.github.io"> Travis Dick </a><br>
      <i>International Conference on Learning Representations (ICLR)</i>, 2026.</li>
     
  <li><b>Tracking the Best Expert Privately</b> <a href="https://arxiv.org/abs/2503.09889" class="paper-badge">PDF</a><br>
      with <a href="https://web.stanford.edu/~asi/"> Hilal Asi </a>, <a href="https://aadirupa.github.io">Aadirupa Saha</a><br>
      <i>International Conference on Machine Learning (ICML)</i>, 2025.</li>
     
  <li><b>Faster Rates for Private Adversarial Bandits</b> <a href="http://arxiv.org/abs/2505.21790" class="paper-badge">PDF</a><br>
      with <a href="https://web.stanford.edu/~asi/">Hilal Asi</a>, <a href="http://kunaltalwar.org">Kunal Talwar</a><br>
      <i>International Conference on Machine Learning (ICML)</i>, 2025.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Beyond Worst-case Guarantees for Learning</h3></summary>
  <ol start="9">
  <li><b>Online Classification with Predictions</b> <a href="http://arxiv.org/abs/2405.14066" class="paper-badge">PDF</a><br>
      with <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2024.</li>
     
  <li><b>Smoothed Online Classification can be Harder than Batch Classification</b> <a href="https://arxiv.org/pdf/2405.15424" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2024.</li>
     
  <li><b>Multiclass Transductive Online Learning</b> <span class="award-badge">Spotlight</span> <a href="http://arxiv.org/abs/2411.01634" class="paper-badge">PDF</a><br>
      with <a href="https://stevehanneke.com">Steve Hanneke</a>, <a href="https://scholar.google.com/citations?user=nRTM5b8AAAAJ&hl=en">Amirreza Shaeiri</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2024.</li>
  
  <li><b>On Proper Learnability between Average- and Worst-case Robustness</b> <a href="https://arxiv.org/abs/2211.05656" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2023.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Online Learning</h3></summary>
  <ol start="13">
  <li><b>The Complexity of Sequential Prediction in Dynamical Systems</b> <span class="award-badge">Oral</span> <a href="https://arxiv.org/abs/2402.06614" class="paper-badge">PDF</a><br>
     with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
     <i>Conference on Learning for Dynamics and Control (L4DC)</i>, 2025.</li>
     
  <li><b>A Unified Theory of Supervised Online Learnability</b> <span class="award-badge">Outstanding Paper</span><a href="https://arxiv.org/abs/2307.03816" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Algorithmic Learning Theory (ALT)</i>, 2025.</li>
      
  <li><b>Online Learning with Set-Valued Feedback</b> <a href="https://arxiv.org/abs/2306.06247" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Learning Theory (COLT)</i>, 2024.</li>
      
  <li><b>Online Infinite-Dimensional Regression: Learning Linear Operators</b> <a href="https://arxiv.org/abs/2309.06548" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Algorithmic Learning Theory (ALT)</i>, 2024.</li>
      
  <li><b>Multiclass Online Learning and Uniform Convergence</b> <a href="https://arxiv.org/abs/2303.17716" class="paper-badge">PDF</a><br>
     with <a href="https://stevehanneke.com">Steve Hanneke</a>, <a href="https://csaws.cs.technion.ac.il/~shaymrn/">Shay Moran</a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Learning Theory (COLT)</i>, 2023.</li>
      
  <li><b>Online Agnostic Multiclass Boosting</b> <a href="https://arxiv.org/abs/2205.15113" class="paper-badge">PDF</a><br>
      with <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2022.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Partial Feedback</h3></summary>
  <ol start="19">
  <li><b>Apple Tasting: Combinatorial Dimensions and Minimax Rates</b> <a href="https://arxiv.org/abs/2310.19064" class="paper-badge">PDF</a><br>
      with <a href= "https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en"> Ananth Raman </a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Learning Theory (COLT)</i>, 2024.</li>
      
  <li><b>Multiclass Online Learnability under Bandit Feedback</b> <a href="https://arxiv.org/abs/2308.04620" class="paper-badge">PDF</a><br>
      with <a href= "https://scholar.google.com/citations?user=GpisoW8AAAAJ&hl=en"> Ananth Raman </a>, <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://idanmehalel.wordpress.com">Idan Mehalel</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Algorithmic Learning Theory (ALT)</i>, 2024.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Multioutput Learning</h3></summary>
  <ol start="21">
  <li><b>A Characterization of Multioutput Learnability</b> <a href="https://arxiv.org/abs/2301.02729" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Journal of Machine Learning Research (JMLR)</i>, 2024.</li>
      
  <li><b>On the Learnability of Multilabel Ranking</b> <span class="award-badge">Spotlight</span><a href="https://arxiv.org/abs/2304.03337" class="paper-badge">PDF</a><br>
      with <a href="https://unique-subedi.github.io">Unique Subedi</a>, <a href="https://ambujtewari.github.io">Ambuj Tewari</a><br>
      <i>Conference on Neural Information Processing Systems (NeurIPS)</i>, 2023.</li>
  </ol>
  </details>
  <details open>
  <summary><h3>Other</h3></summary>
  <ol start="23">
  <li><b>Design of thermophotovoltaics for tolerance of parasitic absorption</b> <a href="https://opg.optica.org/oe/fulltext.cfm?uri=oe-27-22-31757&id=422403" class="paper-badge">PDF</a><br>
      with Tobias Burger, <a href="https://lenert.engin.umich.edu">Andrej Lenert</a><br>
      <i>Optics Express</i>, 2019.</li>
  </ol>
  </details>

</details>

<!-- <details>
<summary>
  <h1 style="display:inline-block; cursor:pointer; color: black; margin-top: 60px;">Talks</h1>
</summary>

<ul>
<li>Optimal Stopping vs Best-of-N for Inference Time Optimization (Percepta Job Talk 2025) <a href="https://drive.google.com/file/d/1EPaksfpvEWg-ZWJLz1N57SSlAThaR1Bs/view?usp=sharing" class="paper-badge">Slides</a></li>
<li>Optimal Stopping vs Best-of-N for Inference Time Optimization (Google DeepMind Tech Talk 2025) <a href="https://drive.google.com/file/d/1EPaksfpvEWg-ZWJLz1N57SSlAThaR1Bs/view?usp=sharing" class="paper-badge">Slides</a></li>
<li>A Unified Theory of Supervised Online Learnability (ALT 2025)</li>
<li>Generation through the lens of learning theory (Apple 2025)</li>
<li>Generation through the lens of learning theory (NEU CS Theory Seminar) <a href="https://drive.google.com/file/d/1mfKRbMvGWCDnhhpQbb8RzUDKqRM4hwas/view?usp=share_link" class="paper-badge">Slides</a></li>
<li>Generation through the lens of learning theory (STATS 700 Guest Lecture)</li>
<li>Trichotomies in Online Learnability (Student ML Research Seminar 2024) <a href="https://drive.google.com/file/d/15R-_OTPSbOuGVLGxcwN0N2HQSeK13u8U/view?usp=sharing" class="paper-badge">Slides</a></li>
<li>Trichotomies in Online Learnability (Apple 2024) <a href="https://drive.google.com/file/d/15R-_OTPSbOuGVLGxcwN0N2HQSeK13u8U/view?usp=sharing" class="paper-badge">Slides</a></li>
<li>Revisiting the Learnability of Apple Tasting (MSSISS 2024)</li>
<li>Multiclass Online Learnability under Bandit Feedback (ALT 2024)</li>
<li>Multiclass Online Learning and Uniform Convergence (UM EECS Theory Seminar) <a href="https://drive.google.com/file/d/1YYH1xC_CDVVpjrbjUNPXMQvojB6XomtV/view?usp=sharing" class="paper-badge">Slides</a></li>
<li>On Classification-Calibration of Gamma-Phi Losses (COLT 2023) <a href="https://drive.google.com/file/d/1odpiQMefHoLJbHs6HLIpS6e0wM8FKEzs/view?usp=sharing" class="paper-badge">Slides</a></li>
</ul>
</details> -->
