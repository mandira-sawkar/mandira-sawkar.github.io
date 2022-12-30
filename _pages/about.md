---
permalink: /
title: "Hi! I'm Abhishek, an Applied Scientist at [Amazon International Machine Learning](https://www.amazon.science/working-at-amazon/how-rajeev-rastogis-machine-learning-team-in-india-develops-innovations-for-customers-worldwide)."
excerpt: "About me"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

We're a group of ~100 ML researchers working across Bangalore, Seattle, Sydney and Berlin, led by [Rajeev Rastogi](https://www.linkedin.com/in/rajeev-rastogi-5019701/?originalSubdomain=in). I research and train models for AutoML and NLP projects.

<iframe style="padding-bottom: 1em;" src="https://www.youtube.com/embed/15sa6OeIWJg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>


**Bio:** From 2017 to 2019 I was a Software Engineer. In late-2019, I moved to Amazon IML as a Research Engineer to work on an Automated Machine Learning platform, EPS. I got hooked on ML research and by Fall 2020 had started a CS Masters at UT Austin to sharpen the saw. At the end of 2021, two things happened: (1) I published enough internal papers to become an Applied Scientist (2) I caught the NLP bug and started working on a task-oriented chatbot (training models for intent detection, information retrieval and knowledge-base curation). Before all this, I completed my undergraduate at VJTI Mumbai in 2017.

**Impact:** My work has been published at internal venues such as Amazon Machine Learning Conference (AMLC, ~30% acceptance rate, 2k-5k attendees). The AutoML platform (where I am now a technical lead) has been used by internal teams to deploy 1,000+ models across 14 Amazon websites, driving $550 million revenue for Amazon businesses like [Subscribe and Save](https://www.amazon.com/b?node=5856181011). My work has also been adopted in external features like [AutoGluon's `infer_limit` feature](https://auto.gluon.ai/0.4.0/tutorials/tabular_prediction/tabular-indepth.html#inference-speed-as-a-fit-constraint) and presented at [ARD 2021](https://adivekar-utexas.github.io/files/Squeezing_the_last_DRiP_ARD_2021_slides.pdf) and [AIMLSys 2022](https://adivekar-utexas.github.io/files/AIMLSys_2022_demo_vF.pdf).

**Future Plans:** In 2023, my focus will be NLP for dialogue and publishing my work externally. I've also taken a background interest in scaling Neural Networks; efforts in this direction include designing architecture for scheduling multiple experiments across a 800-GPU AWS cluster, which will be used to pre-train multimodal Transformers on a billion-row dataset.


Publications (➔[Abstracts](https://adivekar-utexas.github.io/publications/))
------
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-short.html %}
  {% endfor %}</ul>

<!-- 
This is the front page of a website that is powered by the [academicpages template](https://github.com/academicpages/academicpages.github.io) and hosted on GitHub pages. [GitHub pages](https://pages.github.com) is a free service in which websites are built and hosted from code and data stored in a GitHub repository, automatically updating when a new commit is made to the respository. This template was forked from the [Minimal Mistakes Jekyll Theme](https://mmistakes.github.io/minimal-mistakes/) created by Michael Rose, and then extended to support the kinds of content that academics have: publications, talks, teaching, a portfolio, blog posts, and a dynamically-generated CV. You can fork [this repository](https://github.com/academicpages/academicpages.github.io) right now, modify the configuration and markdown files, add your own PDFs and other content, and have your own site for free, with no ads! An older version of this template powers my own personal website at [stuartgeiger.com](http://stuartgeiger.com), which uses [this Github repository](https://github.com/staeiou/staeiou.github.io).

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
