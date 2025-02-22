---
permalink: /
title: "Education"
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

**South China Normal University** (Bachelor of Engineering)  
*Artificial Intelligence* | GPA: **3.92/5.0** | Rank: **1/98**  
*Sep 2022 – Jun 2026*  
**Honors**:  
- First-Class Scholarship  
- CET-4 & CET-6  


Research Experience
======
## China Student Innovation and Entrepreneurship Training Programme  
First Author | First Author | Jan 2023 – Present
- Paper in Submission
  
## AI for Science  
KDD2025 | Second Author | Feb 2025  
- Paper in Submission
  

---

Competitions
======
#### Mathematical Modeling Contest in China (Guangdong Division)  
*Provincial Second Prize | Team Member | Sep 2023*  
- **Project**: *Automated Pricing and Replenishment Decision-Making for Vegetable Products*  
- Built dynamic pricing models using **time series analysis** and **LSTM networks**, optimizing profit by **18%**.  
- Developed Python-based simulations for inventory replenishment under supply-demand constraints.  

#### Mathematical Contest in Modeling (MCM)  
*Honorable Mention | Model Developer | Feb 2024*  
- **Project**: *Momentum-Based Analysis of Sports Dynamics*  
- Designed **Markov Chain** and **CNN-LSTM hybrid models** to predict gameplay trends (R²=0.87).  
- Visualized results using Python’s Matplotlib and Plotly for intuitive strategy insights.  

#### Lanqiao Cup Programming Contest  
*Third Prize (Provincial) | Individual Participant | Mar 2024*  
- Solved complex algorithmic problems using **dynamic programming** and **graph theory** in C++.  

#### National Mathematical Modeling Contest (Guangdong Division)  
*Provincial Second Prize | Team Member | Sep 2024*  
- **Project**: *Path Optimization and Speed Control for "Bench Dragon" Performances*  
- Developed optimization algorithms for path planning and speed control, reducing performance time by **12%**.  
- Created interactive visualizations to demonstrate results.  

#### FLTRP Cup English Writing Competition  
*First Prize (University Level) | Individual Participant | Dec 2023*  
- Authored an essay on AI ethics, showcasing strong analytical and writing skills.  

---

Site-wide configuration
------
The main configuration file for the site is in the base directory in [_config.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_config.yml), which defines the content in the sidebars and other site-wide features. You will need to replace the default variables with ones about yourself and your site's github repository. The configuration file for the top menu is in [_data/navigation.yml](https://github.com/academicpages/academicpages.github.io/blob/master/_data/navigation.yml). For example, if you don't have a portfolio or blog posts, you can remove those items from that navigation.yml file to remove them from the header. 

Create content & metadata
------
For site content, there is one markdown file for each type of content, which are stored in directories like _publications, _talks, _posts, _teaching, or _pages. For example, each talk is a markdown file in the [_talks directory](https://github.com/academicpages/academicpages.github.io/tree/master/_talks). At the top of each markdown file is structured data in YAML about the talk, which the theme will parse to do lots of cool stuff. The same structured data about a talk is used to generate the list of talks on the [Talks page](https://academicpages.github.io/talks), each [individual page](https://academicpages.github.io/talks/2012-03-01-talk-1) for specific talks, the talks section for the [CV page](https://academicpages.github.io/cv), and the [map of places you've given a talk](https://academicpages.github.io/talkmap.html) (if you run this [python file](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.py) or [Jupyter notebook](https://github.com/academicpages/academicpages.github.io/blob/master/talkmap.ipynb), which creates the HTML for the map based on the contents of the _talks directory).

**Markdown generator**

The repository includes [a set of Jupyter notebooks](https://github.com/academicpages/academicpages.github.io/tree/master/markdown_generator
) that converts a CSV containing structured data about talks or presentations into individual markdown files that will be properly formatted for the Academic Pages template. The sample CSVs in that directory are the ones I used to create my own personal website at stuartgeiger.com. My usual workflow is that I keep a spreadsheet of my publications and talks, then run the code in these notebooks to generate the markdown files, then commit and push them to the GitHub repository.

How to edit your site's GitHub repository
------
Many people use a git client to create files on their local computer and then push them to GitHub's servers. If you are not familiar with git, you can directly edit these configuration and markdown files directly in the github.com interface. Navigate to a file (like [this one](https://github.com/academicpages/academicpages.github.io/blob/master/_talks/2012-03-01-talk-1.md) and click the pencil icon in the top right of the content preview (to the right of the "Raw | Blame | History" buttons). You can delete a file by clicking the trashcan icon to the right of the pencil icon. You can also create new files or upload files by navigating to a directory and clicking the "Create new file" or "Upload files" buttons. 

Example: editing a markdown file for a talk
![Editing a markdown file for a talk](/images/editing-talk.png)

For more info
------
More info about configuring Academic Pages can be found in [the guide](https://academicpages.github.io/markdown/), the [growing wiki](https://github.com/academicpages/academicpages.github.io/wiki), and you can always [ask a question on GitHub](https://github.com/academicpages/academicpages.github.io/discussions). The [guides for the Minimal Mistakes theme](https://mmistakes.github.io/minimal-mistakes/docs/configuration/) (which this theme was forked from) might also be helpful.
