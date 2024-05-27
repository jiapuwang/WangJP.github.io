---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Hello! I am Jiapu Wang (王家普), a PhD student of computer science and and technology at Beijing University of Technology advised by [Prof. Wen Gao](https://idm.pku.edu.cn/info/1017/1041.htm), and [Prof. Baocai Yin](), and Griffith University advised by [Prof. Shirui Pan](https://shiruipan.github.io). 

My research interests mainly focus on the areas of artificial intelligence and data mining, especially for the knowledge graph, large language model, and graph neural network.

<span style="color:red">_News_</span>
======
  *<span style="color:red">[Paper:]</span> Our paper ``[Large Language Models-guided Dynamic Adaptation for Temporal Knowledge Graph Reasoning](https://arxiv.org/abs/2405.14170)'' is now published.(May 2024)

  *<span style="color:red">[Paper:]</span> Our paper ``[MADE: Multicurvature Adaptive Embedding for Temporal Knowledge Graph Completion](https://ieeexplore.ieee.org/abstract/document/10535899)'' has been accepted by TCYB.(May 2024)
  
  *<span style="color:red">[Paper:]</span> Our paper ``[Multi-modal long document classification based on Hierarchical Prompt and Multi-modal Transformer](https://www.sciencedirect.com/science/article/pii/S0893608024002466)'' has been accepted by Neural Network.(April 2024)
  
  *<span style="color:brown">[Award:]</span> Our paper ``[IME: Integrating Multi-curvature Shared and Specific Embedding for Temporal Knowledge Graph Completion](https://dl.acm.org/doi/abs/10.1145/3589334.3645361)'' has been recognized as an Oral paper.

  *<span style="color:red">[Paper:]</span> Our paper ``Common-Memory Bridged Cross-Modal Adaptive Graph Embedding for Image-Text Retrieva'' has been accepted by ICME 2024''.(February 2024)

  *<span style="color:red">[Paper:]</span> Our paper ``[IME: Integrating Multi-curvature Shared and Specific Embedding for Temporal Knowledge Graph Completion](https://dl.acm.org/doi/abs/10.1145/3589334.3645361)'' has been accepted by WWW 2024''.(February 2024)

  *<span style="color:red">[Paper:]</span> Our survey paper ``[Unifying large language models and knowledge graphs: A roadmap](https://ieeexplore.ieee.org/abstract/document/10387715)'' has been accepted by TKDE''.(February 2024)

  *<span style="color:red">[Paper:]</span> Our paper ``[Multi-Level Interaction Based Knowledge Graph Completion](https://ieeexplore.ieee.org/abstract/document/10313042)'' has been accepted by TASLP''.(December 2023)

  *<span style="color:red">[Paper:]</span> Our paper ``[QDN: A Quadruplet Distributor Network for Temporal Knowledge Graph Completion](https://ieeexplore.ieee.org/document/10132432)'' has been accepted by TNNLS''.(May 2023)

  *<span style="color:red">[Paper:]</span> Our paper ``[TDN: Triplet Distributor Network for Knowledge Graph Completion](https://ieeexplore.ieee.org/abstract/document/10115028)'' has been accepted by TKDE''.(May 2023)

  *<span style="color:red">[Paper:]</span> Our paper ``[Multi-concept representation learning for knowledge graph completion](https://dl.acm.org/doi/full/10.1145/3533017)'' has been accepted by TKDD''.(February 2023)

__Services__
======
__Reviewer__

  *[IEEE Transactions on Cybernetics](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6221036) (TCYB, IF:19.11)
  
  *[IEEE Transactions on Knowledge and Data Engineering](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=69) (TKDE, IF: 9.235)
  
  *[IEEE Transactions on Neural Networks and Learning Systems](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=5962385) (TNNLS, IF: 14.255)
  
  *[IEEE/ACM Transactions on Audio, Speech, and Language Processing](https://ieeexplore.ieee.org/xpl/RecentIssue.jsp?punumber=6570655) (TASLP, IF: 5.4)
  
  *[ACM Transactions on Knowledge Discovery from Data](https://dl.acm.org/journal/tkdd) (TKDD, IF: 4.711)
  
  *[Neurocomputing](https://www.sciencedirect.com/journal/neurocomputing) (IF: 6)

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
