---
permalink: /
title: "Daliang Xu （徐大亮）"
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
<span style="font-family: 'Times New Roman', Times, serif; font-size: 14pt;">
I am an incoming Assistant Professor (Associate Researcher) at [Beijing University of Posts and Telecommunications (BUPT)](https://www.bupt.edu.cn/), and I will soon work with Prof. Shangguang Wang and [Prof. Mengwei Xu](https://xumengwei.github.io/).
I received my Ph.D. from Peking University (PKU) in June 2025, where I was fortunate to be advised by Prof. Gang Huang, [Prof. Xuanzhe Liu](http://www.liuxuanzhe.com/), and [Prof. Mengwei Xu](https://xumengwei.github.io/).
My research interests are in mobile computing and system software.
</span>

<hr style="border: none; border-top: 1px solid #ccc; margin: 16px 0;" />

<span style="font-family: 'Times New Roman', Times, serif; color: red; font-weight: bold; font-size: 14pt;">
I always look for highly self-motivated undergraduates and graduates. If you are interested in my research, please feel free to send your CV to contact me at bupt_on_device_lab@163.com. 
</span>

<span style="font-family: 'Times New Roman', Times, serif; color: black; font-size: 14pt;">
Notice: Please refer to the [tips](https://daliangxu.github.io/cv/) before sending your email. 
</span>

<hr style="border: none; border-top: 1px solid #ccc; margin: 16px 0;" />

## Research
<div style="font-family: 'Times New Roman', Times, serif; font-size: 14pt;">
  My research focuses on empowering resource-constrained edge devices (e.g., satellites, UAVs, and smartphones) with multimodal large language model (LLM) capabilities through hardware-software co-design.
</div>
<ul>
  <li>
    <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
      Efficient on-device multimodal LLMs
    </span>
    <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
      - Our research primarily optimizes on-device multimodal LLM inference from the perspective of heterogeneous hardware.
    </div>
    <ul>
      <li>
        <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
          Heterogeneous computing systems (e.g., NPU) for on-device multimodal LLMs.
        </span>
        <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
          - Mobile devices typically contain a variety of heterogeneous computing resources (such as CPU, GPU, NPU, etc.). However, current on-device multimodal LLM systems fail to fully utilize them. To address this, we are designing new system software stack optimized for heterogeneous computing resources to maximize their utilization.
          <br><br>
          Our current research topics cover NPU-optimized on-device multimodal LLM engines, NPU compiler design, and other related areas.
          <br><br>
          Papers:
          Mandheling [<a href="https://dl.acm.org/doi/10.1145/3495243.3560545" target="_blank">MobiCom22</a>],
          Niagara [<a href="https://dl.acm.org/doi/abs/10.1007/978-3-031-48421-6_6" target="_blank">ICSOC23 Distinguished Award</a>],
          SoCFlow [<a href="https://dl.acm.org/doi/10.1145/3617232.3624847" target="_blank">ASPLOS24</a>],
          EdgeLLM [<a href="https://ieeexplore.ieee.org/abstract/document/10812936" target="_blank">TMC24</a>],
          LLM.NPU() [<a href="https://dl.acm.org/doi/10.1145/3669940.3707239" target="_blank">ASPLOS25</a>]
        </div>
      </li>
      <li>
        <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
          NPU-friendly multimodal LLM algorithms.
        </span>
        <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
          PieBridge [<a href="https://dl.acm.org/doi/10.1145/3666025.3699327" target="_blank">SenSys24</a>], Q-FedUpdate [<a href="https://dl.acm.org/doi/10.1145/3589334.3645341" target="_blank">WWW24</a>]
        </div>
      </li>
      <li>
        <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
          Intelligent autonomous systems: multimodal perception, autonomous control, and self-evolution in UAVs or satellites.
        </span>
      </li>
    </ul>
  </li>
  <li>
    <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
      New hardware for intelligent satellites or smartphones.
    </span>
    <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
      - Next-generation intelligent satellites featuring high reliability, fault tolerance, and support for multimodal LLM inference.
    </div>
    <ul>
      <li>
        <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
          On-device accelerators for multimodal LLM.
        </span>
        <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
          - Our research focuses on multimodal LLM quantized inference efficiency and minimizing accelerator energy consumption, current, and area.
        </div>
      </li>
      <li>
        <span style="font-weight: bold; font-size: 14pt; color: black; font-family: 'Times New Roman', Times, serif;">
          High-Reliability SoCs for Satellites.
        </span>
        <div style="font-size: 12pt; color: black; font-family: 'Times New Roman', Times, serif;">
          - Focus on characteristics such as high reliability and fault tolerance.
        </div>
      </li>
    </ul>
  </li>
</ul>



## On-going projects
- <span style="font-family: 'Times New Roman', Times, serif; color: black; font-weight: bold; font-size: 14pt;">[MLLM-NPU](https://github.com/UbiquitousLearning/mllm)</span>
<span style="font-family: 'Times New Roman', Times, serif; color: black; font-size: 12pt;"> - 
  a fast and lightweight NPU-optimized multimodal LLM inference engine for mobile devices.
  </span>


- <span style="font-family: 'Times New Roman', Times, serif; color: black; font-weight: bold; font-size: 14pt;">Satellite hardware. </span>
<span style="font-family: 'Times New Roman', Times, serif; color: black; font-size: 12pt;"> - 
  A lightweight satellite SoC, focusing on space-grade reliability and enhancing multimodal LLM acceleration capabilities.
  </span>


## Selected Publications (* = equal contributions)
<div style="font-family: 'Times New Roman', Times, serif; font-size: 16px;">

<div style="margin-bottom: 14px;">
• <b><span style="color: #c00;">[CCF-A]</span></b> <b>[ASPLOS'2025]</b> Fast On-device LLM Inference with NPUs <br>
<b>Daliang Xu</b>, Hao Zhang, Liming Yang, Ruiqi Liu, Gang Huang, Mengwei Xu, Xuanzhe Li
</div>

<div style="margin-bottom: 14px;">
• <b><span style="color: #c00;">[CCF-A]</span></b> <b>[ASPLOS'2024]</b> SoCFlow: Efficient and Scalable DNN Training on SoC-Clustered Edge Servers <br>
<b>Daliang Xu*</b>, Mengwei Xu*, Chiheng Lou, Li Zhang, Gang Huang, Xin Jin, Xuanzhe Liu
</div>

<div style="margin-bottom: 14px;">
• <b><span style="color: #c00;">[CCF-A]</span></b> <b>[TMC'2024]</b> EdgeLLM: Fast On-Device LLM Inference With Speculative Decoding <br>
<b>Daliang Xu</b>, Wangsong Yin, Hao Zhang, Xin Jin, Ying Zhang, Shiyun Wei, Mengwei Xu, Xuanzhe Liu
</div>

<div style="margin-bottom: 14px;">
• <b> 🏆 <span style="color: #c00;">[CCF-B Distinguished Paper Award]</span></b> <b>[ICSOC'2023]</b> Niagara: Scheduling DNN Inference Services on Heterogeneous Edge Processors  <br>
<b>Daliang Xu</b>, Qing Li, Mengwei Xu, Kang Huang, Gang Huang, Shangguang Wang, Xin Jin, Ma Yun, Xuanzhe Liu
</div>

<div style="margin-bottom: 14px;">
• <b><span style="color: #c00;">[CCF-A]</span></b> <b>[Mobicom'2022]</b> Mandheling: Mixed-Precision On-Device DNN Training with DSP Offloading <br>
<b>Daliang Xu*</b>, Mengwei Xu*, Qipeng Wang, Shangguang Wang, Kang Huang, Gang Huang, Xin Jin, Xuanzhe Liu
</div>

</div>



<!-- This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

A data-driven personal website
======
Like many other Jekyll-based GitHub Pages templates, academicpages makes you separate the website's content from its form. The content & metadata of your website are in structured markdown files, while various other files constitute the theme, specifying how to transform that content & metadata into HTML pages. You keep these various markdown (.md), YAML (.yml), HTML, and CSS files in a public GitHub repository. Each time you commit and push an update to the repository, the [GitHub pages](https://pages.github.com/) service creates static HTML pages based on these files, which are hosted on GitHub's servers free of charge.

Many of the features of dynamic content management systems (like Wordpress) can be achieved in this fashion, using a fraction of the computational resources and with far less vulnerability to hacking and DDoSing. You can also modify the theme to your heart's content without touching the content of your site. If you get to a point where you've broken something in Jekyll/HTML/CSS beyond repair, your markdown files describing your talks, publications, etc. are safe. You can rollback the changes or even delete the repository and start over -- just be sure to save the markdown files! Finally, you can also write scripts that process the structured data on the site, such as [this one](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb) that analyzes metadata in pages about talks to display [a map of every location you've given a talk](https://academicpages.github.io/talkmap.html).

Getting started
======
1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
1. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right. 
1. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
1. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
1. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.  
1. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful. -->
