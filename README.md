<div align="center">

# 🐾 Tabby

[![latest release](https://shields.io/github/v/release/TabbyML/tabby?sort=semver)](https://github.com/TabbyML/tabby/releases/latest)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](https://makeapullrequest.com)
[![Docker pulls](https://img.shields.io/docker/pulls/tabbyml/tabby)](https://hub.docker.com/r/tabbyml/tabby)

[![Slack Community](https://shields.io/badge/Join-Tabby%20Slack-red?logo=slack)](https://links.tabbyml.com/join-slack)
[![Office Hours](https://img.shields.io/badge/Book-Office%20Hours-purple?logo=googlecalendar&logoColor=white)](https://calendly.com/tabby_ml/chat-with-tabbyml)

</div>

<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div align="center" dir="auto">
<h1 tabindex="-1" dir="auto"><a id="user-content--tabby" class="anchor" aria-hidden="true" tabindex="-1" href="#-tabby"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🐾 虎斑猫</font></font></h1>
<p dir="auto"><a href="https://github.com/TabbyML/tabby/releases/latest"><img src="https://camo.githubusercontent.com/f5f583113f89b94f9129d1be0d50a9a4d8d809546732193b111b2a379f4eff46/68747470733a2f2f736869656c64732e696f2f6769746875622f762f72656c656173652f54616262794d4c2f74616262793f736f72743d73656d766572" alt="最新发布" data-canonical-src="https://shields.io/github/v/release/TabbyML/tabby?sort=semver" style="max-width: 100%;"></a>
<a href="https://makeapullrequest.com" rel="nofollow"><img src="https://camo.githubusercontent.com/a5ceaa9e114c16d2c7cfd7ef62032b26b6eb47b61b1263ae4ebc5497fedd45b2/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f5052732d77656c636f6d652d627269676874677265656e2e7376673f7374796c653d666c61742d737175617265" alt="欢迎 PR" data-canonical-src="https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square" style="max-width: 100%;"></a>
<a href="https://hub.docker.com/r/tabbyml/tabby" rel="nofollow"><img src="https://camo.githubusercontent.com/e60447e036e13fdce196d34b0a4f6d871370251154bef502bd12d22d8de2a506/68747470733a2f2f696d672e736869656c64732e696f2f646f636b65722f70756c6c732f74616262796d6c2f7461626279" alt="Docker 拉取" data-canonical-src="https://img.shields.io/docker/pulls/tabbyml/tabby" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://links.tabbyml.com/join-slack" rel="nofollow"><img src="https://camo.githubusercontent.com/cc427f03161ee59441f97b8392373183dca62ef1823f90baac2c305b71a87517/68747470733a2f2f736869656c64732e696f2f62616467652f4a6f696e2d5461626279253230536c61636b2d7265643f6c6f676f3d736c61636b" alt="松弛社区" data-canonical-src="https://shields.io/badge/Join-Tabby%20Slack-red?logo=slack" style="max-width: 100%;"></a>
<a href="https://calendly.com/tabby_ml/chat-with-tabbyml" rel="nofollow"><img src="https://camo.githubusercontent.com/47e596af6cbfeffef7a604b16114683c498005d242423456fef9302a47309b03/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f426f6f6b2d4f6666696365253230486f7572732d707572706c653f6c6f676f3d676f6f676c6563616c656e646172266c6f676f436f6c6f723d7768697465" alt="工作时间" data-canonical-src="https://img.shields.io/badge/Book-Office%20Hours-purple?logo=googlecalendar&amp;logoColor=white" style="max-width: 100%;"></a></p>
</div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Tabby 是一款自托管 AI 编码助手，提供 GitHub Copilot 的开源和本地替代方案。</font><font style="vertical-align: inherit;">它拥有几个关键特性：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">独立的，不需要 DBMS 或云服务。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">OpenAPI接口，易于与现有基础设施（例如Cloud IDE）集成。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">支持消费级 GPU。</font></font></li>
</ul>
<p align="center" dir="auto">
  <a href="https://tabbyml.github.io/tabby/playground" rel="nofollow"><img alt="在游乐场开放" src="https://camo.githubusercontent.com/26c029a56d2b60d19dab4aa4b86f64e564d66eb65dc8a7194268240858a85141/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4f50454e253230494e253230504c415947524f554e442d626c75653f6c6f676f3d78636f6465267374796c653d666f722d7468652d6261646765266c6f676f436f6c6f723d677265656e" data-canonical-src="https://img.shields.io/badge/OPEN%20IN%20PLAYGROUND-blue?logo=xcode&amp;style=for-the-badge&amp;logoColor=green" style="max-width: 100%;"></a>
</p>
<p align="center" dir="auto">
  <animated-image data-catalyst=""><a target="_blank" rel="noopener noreferrer nofollow" href="https://user-images.githubusercontent.com/388154/230440226-9bc01d05-9f57-478b-b04d-81184eba14ca.gif" data-target="animated-image.originalLink"><img alt="演示" src="https://user-images.githubusercontent.com/388154/230440226-9bc01d05-9f57-478b-b04d-81184eba14ca.gif" style="max-width: 100%; display: inline-block;" data-target="animated-image.originalImage"></a>
      <span class="AnimatedImagePlayer" data-target="animated-image.player" hidden="">
        <a data-target="animated-image.replacedLink" class="AnimatedImagePlayer-images" href="https://user-images.githubusercontent.com/388154/230440226-9bc01d05-9f57-478b-b04d-81184eba14ca.gif" target="_blank">
          
        <span data-target="animated-image.imageContainer">
            <img data-target="animated-image.replacedImage" alt="Demo" class="AnimatedImagePlayer-animatedImage" src="https://user-images.githubusercontent.com/388154/230440226-9bc01d05-9f57-478b-b04d-81184eba14ca.gif" style="display: block; opacity: 1;">
          <canvas class="AnimatedImagePlayer-stillImage" aria-hidden="true" width="600" height="300"></canvas></span></a>
        <button data-target="animated-image.imageButton" class="AnimatedImagePlayer-images" tabindex="-1" aria-label="Play Demo" hidden=""></button>
        <span class="AnimatedImagePlayer-controls" data-target="animated-image.controls" hidden="">
          <button data-target="animated-image.playButton" class="AnimatedImagePlayer-button" aria-label="Play Demo">
            <svg aria-hidden="true" focusable="false" class="octicon icon-play" width="16" height="16" viewBox="0 0 16 16" fill="none" xmlns="http://www.w3.org/2000/svg">
              <path d="M4 13.5427V2.45734C4 1.82607 4.69692 1.4435 5.2295 1.78241L13.9394 7.32507C14.4334 7.63943 14.4334 8.36057 13.9394 8.67493L5.2295 14.2176C4.69692 14.5565 4 14.1739 4 13.5427Z">
            </path></svg>
            <svg aria-hidden="true" focusable="false" class="octicon icon-pause" width="16" height="16" viewBox="0 0 16 16" xmlns="http://www.w3.org/2000/svg">
              <rect x="4" y="2" width="3" height="12" rx="1"></rect>
              <rect x="9" y="2" width="3" height="12" rx="1"></rect>
            </svg>
          </button>
          <a data-target="animated-image.openButton" aria-label="Open Demo in new window" class="AnimatedImagePlayer-button" href="https://user-images.githubusercontent.com/388154/230440226-9bc01d05-9f57-478b-b04d-81184eba14ca.gif" target="_blank">
            <svg aria-hidden="true" class="octicon" xmlns="http://www.w3.org/2000/svg" viewBox="0 0 16 16" width="16" height="16">
              <path fill-rule="evenodd" d="M10.604 1h4.146a.25.25 0 01.25.25v4.146a.25.25 0 01-.427.177L13.03 4.03 9.28 7.78a.75.75 0 01-1.06-1.06l3.75-3.75-1.543-1.543A.25.25 0 0110.604 1zM3.75 2A1.75 1.75 0 002 3.75v8.5c0 .966.784 1.75 1.75 1.75h8.5A1.75 1.75 0 0014 12.25v-3.5a.75.75 0 00-1.5 0v3.5a.25.25 0 01-.25.25h-8.5a.25.25 0 01-.25-.25v-8.5a.25.25 0 01.25-.25h3.5a.75.75 0 000-1.5h-3.5z"></path>
            </svg>
          </a>
        </span>
      </span></animated-image>
</p>
<h2 tabindex="-1" dir="auto"><a id="user-content--whats-new" class="anchor" aria-hidden="true" tabindex="-1" href="#-whats-new"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🔥 最新消息</font></font></h2>
<ul dir="auto">
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 12 月 23 日</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用SkyPilot 的</font><a href="https://skypilot.readthedocs.io/en/latest/serving/sky-serve.html" rel="nofollow"><font style="vertical-align: inherit;">SkyServe 🛫</font></a></font><a href="https://tabby.tabbyml.com/docs/installation/skypilot/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在任何云上</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">无缝部署 Tabby </font><font style="vertical-align: inherit;">。</font></font><a href="https://skypilot.readthedocs.io/en/latest/serving/sky-serve.html" rel="nofollow"><font style="vertical-align: inherit;"></font></a><font style="vertical-align: inherit;"></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023年12月15日</font></font></strong> <a href="https://github.com/TabbyML/tabby/releases/tag/v0.7.0"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">v0.7.0</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">发布，支持团队管理和安全访问！</font></font></li>
<li><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">2023 年 10 月 24 日⛳️ 跨</font></font></strong><font style="vertical-align: inherit;"></font><a href="https://tabby.tabbyml.com/docs/extensions" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">VSCode/Vim/IntelliJ</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">的 Tabby IDE 插件的重大更新</font><font style="vertical-align: inherit;">！</font></font></li>
</ul>
<details>
  <summary><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">已存档</font></font></summary>
<ul dir="auto">
<li><strong>10/15/2023</strong> RAG-based code completion is enabled by detail in <a href="https://github.com/TabbyML/tabby/releases/tag/v0.3.0">v0.3.0</a>🎉! Check out the <a href="https://tabby.tabbyml.com/blog/2023/10/16/repository-context-for-code-completion/" rel="nofollow">blogpost</a> explaining how Tabby utilizes repo-level context to get even smarter!</li>
<li><strong>11/27/2023</strong> <a href="https://github.com/TabbyML/tabby/releases/tag/v0.6.0">v0.6.0</a> released!</li>
<li><strong>11/09/2023</strong> <a href="https://github.com/TabbyML/tabby/releases/tag/v0.5.5">v0.5.5</a> released! With a redesign of UI + performance improvement.</li>
<li><strong>10/04/2023</strong> Check out the <a href="https://tabby.tabbyml.com/docs/models/" rel="nofollow">model directory</a> for the latest models supported by Tabby.</li>
<li><strong>09/18/2023</strong> Apple's M1/M2 Metal inference support has landed in <a href="https://github.com/TabbyML/tabby/releases/tag/v0.1.1">v0.1.1</a>!</li>
<li><strong>08/31/2023</strong> Tabby's first stable release <a href="https://github.com/TabbyML/tabby/releases/tag/v0.0.1">v0.0.1</a> 🥳.</li>
<li><strong>08/28/2023</strong> Experimental support for the <a href="https://github.com/TabbyML/tabby/issues/370" data-hovercard-type="issue" data-hovercard-url="/TabbyML/tabby/issues/370/hovercard">CodeLlama 7B</a>.</li>
<li><strong>08/24/2023</strong> Tabby is now on <a href="https://plugins.jetbrains.com/plugin/22379-tabby" rel="nofollow">JetBrains Marketplace</a>!</li>
</ul>
</details>
<h2 tabindex="-1" dir="auto"><a id="user-content--getting-started" class="anchor" aria-hidden="true" tabindex="-1" href="#-getting-started"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">👋 开始使用</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://tabby.tabbyml.com/docs/getting-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">您可以在这里</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">找到我们的文档</font><font style="vertical-align: inherit;">。</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📚</font></font><a href="https://tabby.tabbyml.com/docs/installation/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💻 </font></font><a href="https://tabby.tabbyml.com/docs/extensions/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IDE/编辑器扩展</font></font></a></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">⚙️</font></font><a href="https://tabby.tabbyml.com/docs/configuration" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">配置</font></font></a></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content-run-tabby-in-1-minute" class="anchor" aria-hidden="true" tabindex="-1" href="#run-tabby-in-1-minute"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">1 分钟跑动虎斑猫</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">启动 Tabby 服务器的最简单方法是使用以下 Docker 命令：</font></font></p>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>docker run -it \
  --gpus all -p 8080:8080 -v <span class="pl-smi">$HOME</span>/.tabby:/data \
  tabbyml/tabby \
  serve --model TabbyML/StarCoder-1B --device cuda</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="docker run -it \
  --gpus all -p 8080:8080 -v $HOME/.tabby:/data \
  tabbyml/tabby \
  serve --model TabbyML/StarCoder-1B --device cuda" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有关其他选项（例如推理类型、并行性），请参阅</font></font><a href="https://tabbyml.github.io/tabby" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档页面</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--contributing" class="anchor" aria-hidden="true" tabindex="-1" href="#-contributing"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🤝 贡献</font></font></h2>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">完整指南位于</font></font><a href="https://github.com/TabbyML/tabby/blob/main/CONTRIBUTING.md"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">CONTRIBUTING.md</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">；</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-get-the-code" class="anchor" aria-hidden="true" tabindex="-1" href="#get-the-code"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">获取代码</font></font></h3>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre>git clone --recurse-submodules https://github.com/TabbyML/tabby
<span class="pl-c1">cd</span> tabby</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone --recurse-submodules https://github.com/TabbyML/tabby
cd tabby" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您已经克隆了存储库，则可以运行</font></font><code>git submodule update --recursive --init</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">命令来获取所有子模块。</font></font></p>
<h3 tabindex="-1" dir="auto"><a id="user-content-build" class="anchor" aria-hidden="true" tabindex="-1" href="#build"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建造</font></font></h3>
<ol dir="auto">
<li>
<p dir="auto"><font style="vertical-align: inherit;"></font><a href="https://www.rust-lang.org/learn/get-started" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">按照本教程</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置 Rust 环境</font><font style="vertical-align: inherit;">。</font></font></p>
</li>
<li>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装所需的依赖项：</font></font></p>
</li>
</ol>
<div class="highlight highlight-source-shell notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c"><span class="pl-c">#</span> For MacOS</span>
brew install protobuf

<span class="pl-c"><span class="pl-c">#</span> For Ubuntu / Debian</span>
apt-get install protobuf-compiler libopenblas-dev</pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="# For MacOS
brew install protobuf

# For Ubuntu / Debian
apt-get install protobuf-compiler libopenblas-dev" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<ol start="3" dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">现在，您可以通过运行命令来构建 Tabby </font></font><code>cargo build</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
</ol>
<h3 tabindex="-1" dir="auto"><a id="user-content-start-hacking" class="anchor" aria-hidden="true" tabindex="-1" href="#start-hacking"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">开始黑客攻击！</font></font></h3>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">...并且不要忘记提交</font></font><a href="https://github.com/TabbyML/tabby/compare"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Pull Request</font></font></a></p>
<h2 tabindex="-1" dir="auto"><a id="user-content--community" class="anchor" aria-hidden="true" tabindex="-1" href="#-community"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🌍 社区</font></font></h2>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">#️⃣ </font></font><a href="https://links.tabbyml.com/join-slack-extensions" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Slack</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 与 TabbyML 社区联系</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🎤 </font></font><a href="https://twitter.com/Tabby_ML" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Twitter / X</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 与 TabbyML 合作，尽一切可能</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">📚 </font></font><a href="https://www.linkedin.com/company/tabbyml/" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">LinkedIn</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;"> - 关注社区的最新动态</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">💌</font></font><a href="https://newsletter.tabbyml.com/archive" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">时事通讯</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">- 订阅以解锁虎斑猫的见解和秘密</font></font></li>
</ul>
<h3 tabindex="-1" dir="auto"><a id="user-content--star-history" class="anchor" aria-hidden="true" tabindex="-1" href="#-star-history"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">🌟 明星历史</font></font></h3>
<p dir="auto"><a href="https://star-history.com/#tabbyml/tabby&amp;Date" rel="nofollow"><img src="https://camo.githubusercontent.com/f086679de488f547c65a80a5fae7227a8d4b96a6d92a2cec96f12db6e35d4703/68747470733a2f2f6170692e737461722d686973746f72792e636f6d2f7376673f7265706f733d74616262796d6c2f746162627926747970653d44617465" alt="明星历史图" data-canonical-src="https://api.star-history.com/svg?repos=tabbyml/tabby&amp;type=Date" style="max-width: 100%;"></a></p>
</article></div>
