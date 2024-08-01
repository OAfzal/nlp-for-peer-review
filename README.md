## Datasets in Peer Review

In this repository, we compile existing datasets in peer review. This repository is associated with the paper ["What Can Natural Language Processing Do for Peer Review?"](https://arxiv.org/abs/2405.06563)

The number of scientific articles produced every year is growing steadily, making quality control crucial for scientists and the public good. Peer review, a widely used process in which each submission is evaluated by several independent experts in the field, is hard, time-consuming, and prone to error. As the artifacts involved in peer review, such as manuscripts, reviews, and discussions, are largely text-based, natural language processing (NLP) has great potential to improve the reviewing process. However, it is essential to identify where help is needed, where NLP can assist, and where it should stand aside. The paper aims to provide a foundation for the future efforts in NLP for peer reviewing assistance. We discuss peer review as a general process, exemplified particularly by reviewing at AI conferences. We detail each step of the process from manuscript submission to camera-ready revision, and discuss the associated challenges and opportunities for NLP assistance, illustrated by existing work. This repository aims to serve as a jumping-off point for researchers with a list of available datasets and a brief summary of each.


**If you have any suggestions for additional datasets, please submit a pull request or email us at [osama.afzal@mbzuai.ac.ae](mailto:osama.afzal@mbzuai.ac.ae).**


## Resource List


| Year | Title | Data URL | Summary |
|------|-------|----------|---------|
| 2023 | [ARIES: A Corpus of Scientific Paper Edits Made in Response to Peer Reviews](https://arxiv.org/pdf/2306.12587.pdf) | [Data](https://github.com/allenai/aries) | New small-scale corpus of peer review comments with paper edits made in response to them. |
| 2023 | [Testing for Reviewer Anchoring in Peer Review: A Randomized Controlled Trial](https://arxiv.org/pdf/2307.05443.pdf) | [Data](https://github.com/theryanl/ReviewerAnchoring) | Controlled peer-review experiment on reviewer anchoring in rebuttals. |
| 2023 | [Automatic Analysis of Substantiation in Scientific Peer Reviews](https://aclanthology.org/2023.findings-emnlp.684.pdf) | [Data](https://github.com/YanzhuGuo/SubstanReview) | Peer reviews with claims and associated evidences for detecting lack of substantiation. |
| 2023 | [Overview of PragTag-2023: Low-Resource Multi-Domain Pragmatic Tagging of Peer Reviews](https://aclanthology.org/2023.argmining-1.21.pdf) | [Data](https://codalab.lisn.upsaclay.fr/competitions/13334) | Shared task extending NLPEER with pragmatic tag annotations for studying tagging across domains. |
| 2023 | [When Reviewers Lock Horns: Finding Disagreements in Scientific Peer Reviews](https://aclanthology.org/2023.emnlp-main.1038/) | [Data](https://github.com/sandeep82945/Contradiction-in-Peer-Review) | Identifying contradictions between reviewers. |
| 2023 | [PolitePEER: does peer review hurt? A dataset to gauge politeness intensity in the peer reviews](https://link.springer.com/article/10.1007/s10579-023-09662-3) | [Data](https://github.com/PrabhatkrBharti/PolitePEER) | Politeness classifier for peer review to develop politeness indicators. |
| 2023 | [NLPEER: A Unified Resource for the Computational Study of Peer Review](https://aclanthology.org/2023.acl-long.277.pdf) | [Data](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/3618) | Benchmark dataset combining new and existing datasets for cross-domain peer review assistance. |
| 2023 | [ArgSciChat (Argumentative Dialogues on Scientific Papers)](https://aclanthology.org/2023.acl-long.425/) | [Data](https://github.com/UKPLab/acl2023-argscichat) | Argumentative dialogues for studying dialogue agents and information needs from abstracts. |
| 2023 | [Summarizing Multiple Documents with Conversational Structure for Meta-Review Generation](https://aclanthology.org/2023.findings-emnlp.472/) | [Data](https://github.com/oaimli/PeerSum) | Meta-review as a summary with conflicting information and full thread input. |
| 2023 | [A Dataset on Malicious Paper Bidding in Peer Review](https://arxiv.org/pdf/2207.02303) | [Data](https://github.com/sjecmen/malicious_bidding_dataset) | Controlled peer-review experiment on collusion ring behavior. |
| 2023 | [ReviewerGPT? An Exploratory Study on Using Large Language Models for Paper Reviewing](https://arxiv.org/pdf/2306.00622.pdf) | [Data](https://github.com/niharshah/ReviewerGPT2023/) | Small-scale data to evaluate LLM reviewing. |
| 2023 | [Exploring Jiu-Jitsu Argumentation for Writing Peer Review Rebuttals](https://aclanthology.org/2023.emnlp-main.894.pdf) | [Data](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/4000) | Dataset of review statements with attitude roots, themes, and canonical rebuttals. |
| 2023 | [A Gold Standard Dataset for the Reviewer Assignment Problem](https://arxiv.org/pdf/2303.16750.pdf) | [Data](https://github.com/niharshah/goldstandard-reviewer-paper-match) | Researchers' own evaluations of their expertise in reviewing papers. |
| 2022 | [Towards Automated Document Revision: Grammatical Error Correction, Fluency Edits, and Beyond](https://arxiv.org/abs/2205.11484) | [Data](https://github.com/chemicaltree/tetra) | Dataset with papers from ACL anthology revised by professional editors. |
| 2022 | [ReAct (A Review Comment Dataset for Actionability)](https://arxiv.org/abs/2210.00443) | [Data](https://github.com/gtmdotme/ReAct) | Review comment actionability classification. |
| 2022 | [HedgePeer (Uncertainty Detection)](https://dl.acm.org/doi/10.1145/3529372.3533300) | [Data](https://github.com/Tirthankar-Ghosal/HedgePeer-Dataset) | Uncertainty detection in peer review texts using hedge cues and spans. |
| 2022 | [Can we automate scientific reviewing?](https://www.jair.org/index.php/jair/article/view/128622) | [Data](https://github.com/neulab/ReviewAdvisor) | Insights into applications and review quality with challenges for review generation. |
| 2022 | [DISAPERE: A Dataset for Discourse Structure in Peer Review Discussions](https://aclanthology.org/2022.naacl-main.89.pdf) | [Data](https://github.com/nnkennard/DISAPERE/tree/main) | Multi-layer-annotated dataset for studying discourse structure between rebuttals and reviews. |
| 2022 | [Revise and Resubmit: An Intertextual Model of Text-based Collaboration in Peer Review](https://direct.mit.edu/coli/article/48/4/949/112555/Revise-and-Resubmit-An-Intertextual-Model-of-Text) | [Data](https://github.com/UKPLab/f1000rd) | Annotated reviews with pragmatic tags, links, and paper version alignment for intertextual study. |
| 2022 | [arXivEdits: Understanding the Human Revision Process in Scientific Writing](https://aclanthology.org/2022.emnlp-main.641/) | [Data](https://github.com/chaojiang06/arXivEdits) | Corpus of arxiv preprints with aligned edits labeled with intentions. |
| 2021 | [COMPARE: A Taxonomy and Dataset of Comparison Discussions in Peer Reviews](https://arxiv.org/abs/2108.04366) | [Data](https://github.com/shruti-singh/COMPARE) | Identifying comparison sentences in peer reviews and taxonomy of comparison discussions. |
| 2021 | [Argument Mining Driven Analysis of Peer-Reviews](https://ojs.aaai.org/index.php/AAAI/article/view/16607) | [Data](https://github.com/fromm-m/aaai2021-am-peer-reviews),[Data](https://zenodo.org/records/4314390) | Argument mining for extracting relevant info from reviews. |
| 2020 | [Catch Me if I Can: Detecting Strategic Behaviour in Peer Assessment](https://arxiv.org/pdf/2010.04041.pdf) | [Data](https://cs.cmu.edu/~nihars/data/data_catch_me_if_i_can.zip) | Controlled peer-review experiment on strategic reviewing. |
| 2020 | [APE: Argument Pair Extraction from Peer Review and Rebuttal via Multi-task Learning](https://aclanthology.org/2020.emnlp-main.569.pdf) | [Data](https://github.com/LiyingCheng95/ArgumentPairExtraction) | Annotated dataset linking arguments in review reports to author rebuttals. |
| 2019 | [Argument Mining for Understanding Peer Reviews](https://aclanthology.org/N19-1219/) | [Data](https://xinyuhua.github.io/Resources/naacl19/) | Peer reviews annotated by argumentative units and their types. |
| 2019 | [Does my rebuttal matter?](https://aclanthology.org/N19-1129/) | [Data](https://tudatalib.ulb.tu-darmstadt.de/handle/tudatalib/2639) | Dataset of anonymized review scores before and after rebuttal from ACL 2018. |
| 2018 | [A Dataset of Peer Reviews (PeerRead): Collection, Insights and NLP Applications](https://aclanthology.org/N18-1149/) | [Data](https://github.com/allenai/PeerRead) | One of the first datasets of peer reviews from the NLP community. |
| 2017 | [AAMAS Bidding Data](https://preflib.simonrey.fr/dataset/00037) | [Data](https://preflib.simonrey.fr/static/data/aamas/aamas.zip) | Anonymized bidding data from the AAMAS conference. |

## Citation

```bibtex
@misc{kuznetsov2024natural,
      title={What Can Natural Language Processing Do for Peer Review?}, 
      author={Ilia Kuznetsov and Osama Mohammed Afzal and Koen Dercksen and Nils Dycke and Alexander Goldberg and Tom Hope and Dirk Hovy and Jonathan K. Kummerfeld and Anne Lauscher and Kevin Leyton-Brown and Sheng Lu and Mausam and Margot Mieskes and Aurélie Névéol and Danish Pruthi and Lizhen Qu and Roy Schwartz and Noah A. Smith and Thamar Solorio and Jingyan Wang and Xiaodan Zhu and Anna Rogers and Nihar B. Shah and Iryna Gurevych},
      year={2024},
      eprint={2405.06563},
      archivePrefix={arXiv},
      primaryClass={cs.CL}
}
```
