<div class="Box-sc-g0xbh4-0 bJMeLZ js-snippet-clipboard-copy-unpositioned" data-hpc="true"><article class="markdown-body entry-content container-lg" itemprop="text"><div class="markdown-heading" dir="auto"><h1 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WOMBAT：风电场运营和维护成本效益分析工具</font></font></h1><a id="user-content-wombat-windfarm-operations--maintenance-cost-benefit-analysis-tool" class="anchor-element" aria-label="永久链接：WOMBAT：风电场运营和维护成本效益分析工具" href="#wombat-windfarm-operations--maintenance-cost-benefit-analysis-tool"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><a href="https://www.osti.gov/biblio/1894867" rel="nofollow"><img src="https://camo.githubusercontent.com/db2c7606a0f0dc6714be89947935b83bbfddb18f61284097779f6bdc5f430761/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f444f492d31302e32313732253246313839343836372d627269676874677265656e3f6c696e6b3d68747470733a2f2f646f692e6f72672f31302e323137322f31383934383637" alt="DOI 10.2172/1894867" data-canonical-src="https://img.shields.io/badge/DOI-10.2172%2F1894867-brightgreen?link=https://doi.org/10.2172/1894867" style="max-width: 100%;"></a>
<a href="https://badge.fury.io/py/wombat" rel="nofollow"><img src="https://camo.githubusercontent.com/a4472b48f784f75655600150bb2b4881d7cb02f0d9ad446d7254ed8f6dba5d18/68747470733a2f2f62616467652e667572792e696f2f70792f776f6d6261742e737667" alt="PyPI版本" data-canonical-src="https://badge.fury.io/py/wombat.svg" style="max-width: 100%;"></a>
<a href="https://opensource.org/licenses/Apache-2.0" rel="nofollow"><img src="https://camo.githubusercontent.com/db9dfde8049c5d66ba62fde707d2cfb30e26f9f26ff274c3442c0aec1ec410a4/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f4c6963656e73652d417061636865253230322e302d626c75652e737667" alt="阿帕奇2.0" data-canonical-src="https://img.shields.io/badge/License-Apache%202.0-blue.svg" style="max-width: 100%;"></a>
<a href="https://mybinder.org/v2/gh/WISDEM/WOMBAT/main?filepath=examples" rel="nofollow"><img src="https://camo.githubusercontent.com/e91e1d353a8b6acf0b42547ac3901f2c30138a3abaaa3d3c242da30b5b4f8426/68747470733a2f2f6d7962696e6465722e6f72672f62616467655f6c6f676f2e737667" alt="活页夹" data-canonical-src="https://mybinder.org/badge_logo.svg" style="max-width: 100%;"></a>
<a href="https://wisdem.github.io/WOMBAT" rel="nofollow"><img src="https://camo.githubusercontent.com/4edbe118130ec7c1534d22bdfa1d438aff98dc04a3d9c46394348d280a94e6e4/68747470733a2f2f6a757079746572626f6f6b2e6f72672f62616467652e737667" alt="Jupyter 书" data-canonical-src="https://jupyterbook.org/badge.svg" style="max-width: 100%;"></a></p>
<p dir="auto"><a href="https://github.com/pre-commit/pre-commit"><img src="https://camo.githubusercontent.com/f9f3d4b9da2ae7190cc5ce42cbdb9d04ce63bec0fd0af14e0e115218fceac615/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f7072652d2d636f6d6d69742d656e61626c65642d627269676874677265656e3f6c6f676f3d7072652d636f6d6d6974266c6f676f436f6c6f723d7768697465" alt="预提交" data-canonical-src="https://img.shields.io/badge/pre--commit-enabled-brightgreen?logo=pre-commit&amp;logoColor=white" style="max-width: 100%;"></a>
<a href="https://github.com/psf/black"><img src="https://camo.githubusercontent.com/7d770c433d6198d89f8c1e2f187b904a9721d176259d0e97157337741cc8e837/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f636f64652532307374796c652d626c61636b2d3030303030302e737667" alt="黑色的" data-canonical-src="https://img.shields.io/badge/code%20style-black-000000.svg" style="max-width: 100%;"></a>
<a href="https://pycqa.github.io/isort/" rel="nofollow"><img src="https://camo.githubusercontent.com/314441e9acfd471bfa49df181c5ac0a2591e6a3244b6dacd65675ad83d93dca6/68747470733a2f2f696d672e736869656c64732e696f2f62616467652f253230696d706f7274732d69736f72742d2532333136373462313f7374796c653d666c6174266c6162656c436f6c6f723d656638333336" alt="伊索特" data-canonical-src="https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&amp;labelColor=ef8336" style="max-width: 100%;"></a></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">该库提供了一个工具，使用离散事件模拟框架来模拟分布式、陆基和海上风电场的运行和维护阶段 (O&amp;M)。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">WOMBAT 是围绕</font></font><a href="https://gitlab.com/team-simpy/simpy" rel="nofollow"><code>SimPy</code></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">离散事件模拟框架编写的。</font><font style="vertical-align: inherit;">此外，还使用灵活且模块化的面向对象的代码库来支持这一点，该代码库可以对任意大型（或小型）风电场进行建模，并可编码任意数量的故障和维护任务。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">请注意，该功能仍处于开发阶段，因此您可能会发现某些功能目前尚不完整，但请放心，该功能正在扩展。</font><font style="vertical-align: inherit;">话虽如此，如果您能提交问题或 PR 来进行任何改进，从修复拼写错误（肯定会有一些）到功能再到测试，我们将不胜感激。</font></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果您使用此库，请引用我们的 NREL 技术报告：</font></font></p>
<div class="highlight highlight-text-bibtex notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c">   </span><span class="pl-k">@techreport</span>{<span class="pl-en">hammond2022wombat</span>,
      <span class="pl-s">title</span> = <span class="pl-s"><span class="pl-pds">{</span>Windfarm Operations and Maintenance cost-Benefit Analysis Tool (WOMBAT)<span class="pl-pds">}</span></span>,
      <span class="pl-s">author</span> = <span class="pl-s"><span class="pl-pds">{</span>Hammond, Rob and Cooperman, Aubryn<span class="pl-pds">}</span></span>,
      <span class="pl-s">abstractNote</span> = <span class="pl-s"><span class="pl-pds">{</span>This report provides technical documentation and background on the newly-developed Wind Operations and Maintenance cost-Benefit Analysis Tool (WOMBAT) software. WOMBAT is an open-source model that can be used to obtain cost estimates for operations and maintenance of land-based or offshore wind power plants. The software was designed to be flexible and modular to allow for implementation of new strategies and technological innovations for wind plant maintenance. WOMBAT uses a process-based simulation approach to model day-to-day operations, repairs, and weather conditions. High-level outputs from WOMBAT, including time-based availability and annual operating costs, are found to agree with published results from other models.<span class="pl-pds">}</span></span>,
      <span class="pl-s">doi</span> = <span class="pl-s"><span class="pl-pds">{</span>10.2172/1894867<span class="pl-pds">}</span></span>,
      <span class="pl-s">url</span> = <span class="pl-s"><span class="pl-pds">{</span>https://www.osti.gov/biblio/1894867<span class="pl-pds">}</span></span>,
      <span class="pl-s">place</span> = <span class="pl-s"><span class="pl-pds">{</span>United States<span class="pl-pds">}</span></span>,
      <span class="pl-s">year</span> = <span class="pl-s"><span class="pl-pds">{</span>2022<span class="pl-pds">}</span></span>,
      <span class="pl-s">month</span> = <span class="pl-s"><span class="pl-pds">{</span>10<span class="pl-pds">}</span></span>,
      <span class="pl-s">institution</span> = <span class="pl-s"><span class="pl-pds">{</span>National Renewable Energy Lab. (NREL)<span class="pl-pds">}</span></span>,
   }</pre><div class="zeroclipboard-container">
    
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">袋熊在行动</font></font></h2><a id="user-content-wombat-in-action" class="anchor-element" aria-label="永久链接：袋熊在行动" href="#wombat-in-action"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有一些 Jupyter 笔记本可以让用户在</font></font><code>examples/</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
文件夹中启动并运行 WOMBAT，但这里有一些亮点：</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
在 v0.6 中，由于后端的大量模型升级以及新的/更新的功能以更好地指定如何管理修复，因此在某些建模条件下，结果将与过去的版本显着不同。</font></font></p>
</blockquote>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">丁伍迪等人。</font><font style="vertical-align: inherit;">的复制</font></font><code>wombat</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">可以在 _ 中找到
</font></font><code>examples folder &lt;https://github.com/WISDEM/WOMBAT/blob/main/examples/dinwoodie_validation.ipynb&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">IEA 任务 26
 </font></font><code>validation exercise  &lt;https://github.com/WISDEM/WOMBAT/blob/main/examples/iea_26_validation.ipynb&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">_。</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">演示文稿：</font></font><code>slides  &lt;https://github.com/WISDEM/WOMBAT/blob/main/presentation_material/&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">_。</font></font></li>
</ul>
<div class="markdown-heading" dir="auto"><h2 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">设置</font></font></h2><a id="user-content-setup" class="anchor-element" aria-label="永久链接：设置" href="#setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">要求</font></font></h3><a id="user-content-requirements" class="anchor-element" aria-label="永久链接：要求" href="#requirements"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Python 3.8 到 3.10</font></font></li>
</ul>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
对于寻求安装更多基本依赖项的 Python 3.10 用户，我们注意到 pip 可能需要很长时间才能解决所有包要求，因此建议使用以下工作流程：</font></font></p>
</blockquote>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre># <span class="pl-s1">Enter the <span class="pl-c1">source</span> code directory</span>
<span class="pl-c1">cd wombat/</span>

# <span class="pl-s1">First install the base package requirements</span>
<span class="pl-c1">pip install -e .</span>

# <span class="pl-s1">Then install whichever additional dependencies are required/desired</span>
<span class="pl-c1">pip install -e '.[dev]'  # '.[docs]' or '.[all]'</span></pre><div class="zeroclipboard-container">
   

# First install the base package requirements
pip install -e .

# Then install whichever additional dependencies are required/desired
pip install -e '.[dev]'  # '.[docs]' or '.[all]'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">环境设置</font></font></h3><a id="user-content-environment-setup" class="anchor-element" aria-label="永久链接：环境设置" href="#environment-setup"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
下载适用于适当操作系统的</font><font style="vertical-align: inherit;">最新版本的</font></font><a href="https://docs.conda.io/en/latest/miniconda.html" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">Miniconda 。</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
对于适当的操作系统版本，</font><font style="vertical-align: inherit;">请执行其余
</font></font><a href="https://conda.io/projects/conda/en/latest/user-guide/install/index.html#regular-installation" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">步骤。</font></font></a><font style="vertical-align: inherit;"></font></p>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">使用conda，创建一个新的虚拟环境：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">conda create -n &lt;environment_name&gt; python=3.8 --no-default-packages</span>
<span class="pl-c1">conda activate &lt;environment_name&gt;</span>
<span class="pl-c1">conda install -c anaconda pip</span>

# <span class="pl-s1">activate the environment</span>
<span class="pl-c1">conda activate &lt;environment_name&gt;</span>

# <span class="pl-s1">to deactivate</span>
<span class="pl-c1">conda deactivate</span></pre><div class="zeroclipboard-container">
  

# activate the environment
conda activate <environment_name>

# to deactivate
conda deactivate" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装</font></font></h3><a id="user-content-installation" class="anchor-element" aria-label="永久链接：安装" href="#installation"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">点</font></font></h4><a id="user-content-pip" class="anchor-element" aria-label="永久链接： 皮普" href="#pip"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">pip install wombat</span></pre><div class="zeroclipboard-container">
   
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">从源头</font></font></h4><a id="user-content-from-source" class="anchor-element" aria-label="永久链接：来自来源" href="#from-source"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">直接将其安装到激活的虚拟环境中：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">git clone https://github.com/WISDEM/WOMBAT.git</span>
<span class="pl-c1">cd wombat</span>
<span class="pl-c1">python setup.py install</span>

# <span class="pl-s1">Alternatively:</span>
<span class="pl-c1">pip install .</span></pre><div class="zeroclipboard-container">
   
python setup.py install

# Alternatively:
pip install ." tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用法</font></font></h4><a id="user-content-usage" class="anchor-element" aria-label="永久链接：用法" href="#usage"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">安装完成后，可以导入包：</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">python</span>
<span class="pl-c1">import wombat</span>
<span class="pl-c1">wombat.__version__</span></pre><div class="zeroclipboard-container">
  

      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如需进一步使用，请参阅文档站点</font></font><a href="https://wisdem.github.io/WOMBAT" rel="nofollow"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">https://wisdem.github.io/WOMBAT</font></font></a><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">。</font></font></p>
<div class="markdown-heading" dir="auto"><h3 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">为 WOMBAT 做出贡献的要求</font></font></h3><a id="user-content-requirements-for-contributing-to-wombat" class="anchor-element" aria-label="永久链接：为 WOMBAT 做出贡献的要求" href="#requirements-for-contributing-to-wombat"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码贡献</font></font></h4><a id="user-content-code-contributions" class="anchor-element" aria-label="永久链接：代码贡献" href="#code-contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码贡献者应该注意，有一个额外的依赖套件用于运行测试并启用预提交工作流程以自动标准化核心代码格式化原则。</font></font></p>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">git clone https://github.com/WISDEM/WOMBAT.git</span>
<span class="pl-c1">cd wombat</span>

# <span class="pl-s1">Install the additional dependencies <span class="pl-k">for</span> running the tests and automatic code formatting</span>
<span class="pl-c1">pip install -e '.[dev]'</span>

# <span class="pl-s1">Enable the pre-commit workflow <span class="pl-k">for</span> automatic code formatting</span>
<span class="pl-c1">pre-commit install</span>

# <span class="pl-s1">... contributions and commits ...</span>

# <span class="pl-s1">Run the tests and ensure they all pass</span>
<span class="pl-c1">pytest tests</span></pre><div class="zeroclipboard-container">
    

# Install the additional dependencies for running the tests and automatic code formatting
pip install -e '.[dev]'

# Enable the pre-commit workflow for automatic code formatting
pre-commit install

# ... contributions and commits ...

# Run the tests and ensure they all pass
pytest tests" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">用户可能遇到的基本预提交问题及其补救措施：</font></font></p>
<ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">对于任何失败的运行，更改可能已自动应用或需要贡献者进行进一步编辑。</font><font style="vertical-align: inherit;">无论哪种情况，做出更改后，贡献者都必须重新运行</font></font><code>git add &lt;the changed files&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">并
</font></font><code>git commit -m &lt;the commit message&gt;</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">重新启动应用更改的预提交工作流程。</font><font style="vertical-align: inherit;">一旦所有检查通过，提交就可以安全地推送。</font></font></li>
<li><code>isort</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">、</font></font><code>black</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或简单文件检查失败，但进行了更改
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">根据需要重新运行</font></font><code>add</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>commit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进程，直到更改满足检查要求</font></font></li>
</ul>
</li>
<li><code>pylint</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">或</font></font><code>flake8</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">失败：
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">解决错误并重新运行</font></font><code>add</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>commit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进程</font></font></li>
</ul>
</li>
<li><code>mypy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">有看起来不正确的类型错误
</font></font><ul dir="auto">
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">仔细检查输入实际上是否正确，并重新运行
</font></font><code>add</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">和</font></font><code>commit</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">进程</font></font></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果</font></font><code>mypy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">只是与看似正确的类型混淆，可以在错误上方添加以下语句</font></font><code>mypy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">：
</font></font><code>assert isinstance(&lt;variable of concern&gt;, &lt;the type you think mypy should be registering&gt;)</code></li>
<li><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">如果这仍然不起作用，但您确信类型是正确的，只需</font></font><code># type ignore</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">在行末尾添加注释即可。</font><font style="vertical-align: inherit;">有时</font></font><code>mypy</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">会遇到复杂的场景，或者特别是某些</font></font><code>attrs</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">约定。</font></font></li>
</ul>
</li>
</ul>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">文档贡献</font></font></h4><a id="user-content-documentation-contributions" class="anchor-element" aria-label="永久链接：文档贡献" href="#documentation-contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">git clone https://github.com/WISDEM/WOMBAT.git</span>
<span class="pl-c1">cd wombat</span>
<span class="pl-c1">pip install -e '.[docs]'</span></pre><div class="zeroclipboard-container">
  
pip install -e '.[docs]'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">建立网站</font></font></p>
<blockquote>
<p dir="auto"><strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">注意</font></font></strong><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
您可能需要将文件中的“execute_notebooks”参数更改</font></font><code>docs/_config.yaml</code><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">
为“off”，除非您要更新编码示例，否则它们将在您每次构建站点时运行。</font></font></p>
</blockquote>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">jupyter-book build docs</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="jupyter-book build docs" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
<p dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">查看结果：</font></font><code>docs/_build/html/index.html</code></p>
<div class="markdown-heading" dir="auto"><h4 tabindex="-1" class="heading-element" dir="auto"><font style="vertical-align: inherit;"><font style="vertical-align: inherit;">代码和文档贡献</font></font></h4><a id="user-content-code-and-documentation-contributions" class="anchor-element" aria-label="永久链接：代码和文档贡献" href="#code-and-documentation-contributions"><svg class="octicon octicon-link" viewBox="0 0 16 16" version="1.1" width="16" height="16" aria-hidden="true"><path d="m7.775 3.275 1.25-1.25a3.5 3.5 0 1 1 4.95 4.95l-2.5 2.5a3.5 3.5 0 0 1-4.95 0 .751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018 1.998 1.998 0 0 0 2.83 0l2.5-2.5a2.002 2.002 0 0 0-2.83-2.83l-1.25 1.25a.751.751 0 0 1-1.042-.018.751.751 0 0 1-.018-1.042Zm-4.69 9.64a1.998 1.998 0 0 0 2.83 0l1.25-1.25a.751.751 0 0 1 1.042.018.751.751 0 0 1 .018 1.042l-1.25 1.25a3.5 3.5 0 1 1-4.95-4.95l2.5-2.5a3.5 3.5 0 0 1 4.95 0 .751.751 0 0 1-.018 1.042.751.751 0 0 1-1.042.018 1.998 1.998 0 0 0-2.83 0l-2.5 2.5a1.998 1.998 0 0 0 0 2.83Z"></path></svg></a></div>
<div class="highlight highlight-text-shell-session notranslate position-relative overflow-auto" dir="auto"><pre><span class="pl-c1">git clone https://github.com/WISDEM/WOMBAT.git</span>
<span class="pl-c1">cd wombat</span>
<span class="pl-c1">pip install -e '.[all]'</span></pre><div class="zeroclipboard-container">
    <clipboard-copy aria-label="Copy" class="ClipboardButton btn btn-invisible js-clipboard-copy m-2 p-0 tooltipped-no-delay d-flex flex-justify-center flex-items-center" data-copy-feedback="Copied!" data-tooltip-direction="w" value="git clone https://github.com/WISDEM/WOMBAT.git
cd wombat
pip install -e '.[all]'" tabindex="0" role="button">
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-copy js-clipboard-copy-icon">
    <path d="M0 6.75C0 5.784.784 5 1.75 5h1.5a.75.75 0 0 1 0 1.5h-1.5a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-1.5a.75.75 0 0 1 1.5 0v1.5A1.75 1.75 0 0 1 9.25 16h-7.5A1.75 1.75 0 0 1 0 14.25Z"></path><path d="M5 1.75C5 .784 5.784 0 6.75 0h7.5C15.216 0 16 .784 16 1.75v7.5A1.75 1.75 0 0 1 14.25 11h-7.5A1.75 1.75 0 0 1 5 9.25Zm1.75-.25a.25.25 0 0 0-.25.25v7.5c0 .138.112.25.25.25h7.5a.25.25 0 0 0 .25-.25v-7.5a.25.25 0 0 0-.25-.25Z"></path>
</svg>
      <svg aria-hidden="true" height="16" viewBox="0 0 16 16" version="1.1" width="16" data-view-component="true" class="octicon octicon-check js-clipboard-check-icon color-fg-success d-none">
    <path d="M13.78 4.22a.75.75 0 0 1 0 1.06l-7.25 7.25a.75.75 0 0 1-1.06 0L2.22 9.28a.751.751 0 0 1 .018-1.042.751.751 0 0 1 1.042-.018L6 10.94l6.72-6.72a.75.75 0 0 1 1.06 0Z"></path>
</svg>
    </clipboard-copy>
  </div></div>
</article></div>
