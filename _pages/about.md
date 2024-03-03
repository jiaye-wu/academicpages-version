---
permalink: /
title: "Jiaye Wu's Academic Information Hub"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---
Welcome to my personal academic page! It is well known that the information is quite scattered across various different academic websites such as Google Scholar, Researchgate, Scopus, etc, which all have their respective focuses. Their functions are also relatively specialized and not as flexible as a personal website. A personal academic information hub website allows me to freely communicate science as I wish.

Biography
==============================

Jiaye is currently a PhD researcher and doctoral assistant at Photonic Systems Laboratory (PHOSL), Institute of Electrical and Micro Engineering (IEM), School of Engineering (STI), [École Polytechnique Fédérale de Lausanne](https://www.epfl.ch/) (EPFL, Swiss Federal Institute of Technology Lausanne). His expertise and current research interests span ultrafast light-matter-interactions, nonlinear optics and nanophotonics in epsilon-near-zero materials, fibre, fibre laser, and waveguide network design, functional thin film design, and non-Hermitian optics. He received M.Sc. degree in Microelectronics and Solid-State Electronics (Integrated Photonic Devices) from [Peking University](https://www.pku.edu.cn/) in 2021 with the highest honours, and B.Sc. degree in Optical Information Science and Technology (Xiangqin Optoelectronic Creative Class) from [South China Normal University](https://www.scnu.edu.cn/) in 2018 with distinction. Throughout his academic trajectory, he has consistently exemplified a commitment to outstanding scholarship. His prolific publications include 20+ academic papers <a href='https://scholar.google.com/citations?user=D2n8tswAAAAAJ'><img src="https://img.shields.io/endpoint?logo=Google%20Scholar&url=https%3A%2F%2Fcdn.jsdelivr.net%2Fgh%2Fjiaye-wu%2Fjiaye-wu.github.io@google-scholar-stats%2Fgs_data_shieldsio.json&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a> (incl. 16+ as first author and 3 as corresponding author) in peer-reviewed esteemed journals such as *Nature Communications*, *Laser & Photonics Reviews*, *Communications Physics*, *Photonics Research*, *ACS Applied Materials & Interfaces*, etc. He served as a peer-reviewer for *Communications Physics*, *Optics Express*, *Optics Letters*, *Optics & Laser Technology*, etc., and a co-reviewer for *Nature*, *Light: Science & Applications*, etc. He is an active member of Elsevier Advisory Panel, OPTICA (formerly OSA, the Optical Society) and IEEE Photonics Society. He was the founding president of IEEE Photonics Society PKUSZ branch chapter and the president of OSA PKUSZ chapter.

Getting started
===============

1. Register a GitHub account if you don't have one and confirm your e-mail (required!)
2. Fork [this repository](https://github.com/academicpages/academicpages.github.io) by clicking the "fork" button in the top right.
3. Go to the repository's settings (rightmost item in the tabs that start with "Code", should be below "Unwatch"). Rename the repository "[your GitHub username].github.io", which will also be your website's URL.
4. Set site-wide configuration and create content & metadata (see below -- also see [this set of diffs](http://archive.is/3TPas) showing what files were changed to set up [an example site](https://getorg-testacct.github.io) for a user with the username "getorg-testacct")
5. Upload any files (like PDFs, .zip files, etc.) to the files/ directory. They will appear at https://[your GitHub username].github.io/files/example.pdf.
6. Check status by going to the repository settings, in the "GitHub pages" section

Site-wide configuration
-----------------------

The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header.

Create content & metadata
-------------------------

For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you&#39;ve given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

I have also created [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the academicpages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
-----------------------------------------

Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons.

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
-------------

More info about configuring academicpages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
