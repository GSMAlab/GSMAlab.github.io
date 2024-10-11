---
permalink: /
title: "Biography"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

Pengfei Jia, Ph.D., associate professor and master's supervisor, is engaged in the theoretical and applied research of machine olfactory technology, involving the whole link from materials, devices, algorithms to systems. Postdoctoral fellow at Southwest University Applied Mathematics Mobile Station, short-term visiting scholar at Institute of Intelligent Agricultural Equipment of Zhejiang University and Monell-ZJGSU Sensory Science Laboratory in United States. Director of Power Equipment Sensing and Information Processing Research Office, Guangxi Key Laboratory of Intelligent Control and Operation and Maintenance of Electric Power Equipment. He has presided over or participated in the research and development of machine olfactory equipment for GIS insulation anomaly detection, air switch cabinet partial discharge detection, medical waste disposal supervision, bacterial infection detection, indoor toxic gas detection, PM2.5 detection, tobacco baking process control and citrus maturity detection. He has published more than 70 academic papers in domestic and foreign journals, authorized 11 Chinese invention patents, 1 Australian patent, 10 utility model patents, 15 software copyrights, and completed 2 scientific and technological achievements transformation (patent transfer and implementation).

Main research directions
======
The theoretical and application scenario research of intelligent olfactory (also known as computer olfaction, machine olfactory or electronic nose), from the research and development of materials, devices, algorithms to equipment, including:  
(1) High-voltage insulation technology direction:  
1) Development of gas-sensitive materials for the detection of landmark gases with abnormal insulation of air switchgear  
2) Development of gas-sensitive materials for the detection of iconic gases for GIS leakage and insulation anomalies  
3) Development of gas-sensitive materials for the detection of landmark gases for transformer insulation abnormalities
3) Development of detection materials for new insulating gases
(2) Dual-carbon direction: develop gas-sensitive materials for dual-carbon gas adsorption, conversion and sensing
(3) Intelligent perception direction:
1) Detection of abnormal landmark gases for insulation of power grid switchgear, including abnormal marker gases for air switchgear insulation, such as carbon monoxide, nitrogen oxides, ozone, etc.; SF6 switchgear is insulated with abnormal iconic gases such as sulfur dioxide, hydrogen sulfide, hydrogen fluoride, etc
2) Correction and compensation of individual differences in metal oxide semiconductor gas sensors (algorithm level)
3) Gas classification algorithm model
4) Algorithm-based gas sensor drift correction (long-term drift, temperature drift)
5) Identification of small samples, single samples, and no samples (GAN, transfer learning, semi-supervised learning)
6) Mixture gas concentration prediction
(4) Intersection direction:
1) Use artificial intelligence (machine learning, deep learning) to assist in the design of gas-sensitive materials

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
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
