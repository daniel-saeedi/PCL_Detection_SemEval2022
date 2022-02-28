# SemEval-2022 Task 4: Effective Data Augmentation Methods for Patronizing Language Detection and Multi-label Classification
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

# What is Patronizing and Condescending Language (PCL)?
We all are patronizing and condescending sometimes. And of course, we all are susceptible to be condescended and patronized by others. But some groups are, unfortunately, more used to be referred to with this undervaluing treatment. The so-called vulnerable communities seem to be the perfect target for charity and pity-driven texts, condescension and patronization in news stories.



PCL is often involuntary and unconscious and the authors using such language are usually trying to help the communities in need, by raising awareness, moving the audience to action or standing for the rights of the under-represented. But PCL can potentially be very harmful, as it feeds tereotypes, routinizes discrimination and drives to greater exclusion.

For more details about the task check out [here](https://sites.google.com/view/pcl-detection-semeval2022/).


## Abstract

> This paper presents a combination of data aug- mentation methods to boost the performance of state-of-the-art transformer-based language models for Patronizing and Condescending Language (PCL) detection and multi-label PCL classification tasks. These tasks are inherently different from sentiment analysis because posi- tive/negative hidden attitudes in the context will not necessarily be considered positive/negative for PCL tasks. Our approach relies on fine- tuning pretrained RoBERTa and GPT3 mod- els such as Davinci and Curie engines with extra-enriched PCL dataset. We augmented the underrepresented class of annotated data to achieve competitive results among top-16 SemEval-2022 participants. Furthermore, we discuss Few-Shot learning technique to over- come the limitation of low-resource NLP prob- lems.

## Software implementation

> This paper presented a system description for PCL detection and multi-label categorization tasks. Our exploratory data analysis revealed annotated PCL dataset is highly imbalanced. We enhanced data quality with a combination of data augmentation methods. We evaluated the performance of the large pre-trained RoBERTa model on the extra en- riched PCL dataset. We boosted the baseline perfor- mance and achieved competitive results among the top-16 SemEval-2022 participants. Furthermore, we tried two models of GPT3, Davinci and Curie with Few-Shot learning technique. Our investi- gation showed both models perform well without hyper-parameter tuning and on just a few exam- ples of PCL. We believe these tasks have many potentials and challenges to further improve cur- rent results.

All source code used to generate the results and figures in the paper are in
the `code` folder.
The calculations and figure generation are all run inside
[Jupyter notebooks](http://jupyter.org/).
The data used in this study is available [upon request](https://docs.google.com/forms/d/e/1FAIpQLSe5KyzXgpnEOjS-Y6Gb8TTKiWxh4_qLuPL-NGiqKCyF41ALlg/viewform).

## Getting the code

You can download a copy of all the files in this repository by cloning the
[git](https://git-scm.com/) repository:

    git clone https://github.com/daniel-saeedi/PCL_Detection_SemEval2022.git

or [download a zip archive](https://github.com/daniel-saeedi/PCL_Detection_SemEval2022/archive/refs/heads/main.zip).


## Dependencies

Run this command to install dependencies:

    pip3 install -r requirements.txt
