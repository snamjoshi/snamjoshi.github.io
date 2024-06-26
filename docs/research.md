---
title: Research and Talks
---

## Talks and Podcasts

* Education, Expectation-Maximisation, Evolution (Active Inference Insights Episode 18) [[Link](https://www.youtube.com/watch?v=sAwPXw-WNg4)] [March 2024]
* How Active Inference is Bridging Neuroscience and AI (Hidden Layers Episode 10) [[Link](https://youtu.be/0EsZkTzux-I?si=DWjaLGuJt3WMS0mB)] [February 2024]
* Machine Learning Street Talk Podcast (Patreon Access Only) [[Link](https://www.patreon.com/posts/dr-sanjeev-97242527?utm_medium=clipboard_copy&utm_source=copyLink&utm_campaign=postshare_fan&utm_content=web_share)] [January 2024]
* Engineering Explained: Bayesian mechanics [[Link](https://youtu.be/3VpptCcInjU?si=qoxCAd89_yvyulIh)] [September 2023]
* Developing Next-Gen Active Inference Tools: Broadening Accessibility, Educational Resources, and the Software Ecosystem (3rd Annual Active Inference Symposium) [[Link](https://youtu.be/Y5ychDWJ-Ig?si=8ckKM2TOLr2rCIOs&t=9)]

In Winter 2020 I gave two talks at the [Deep Learning Meetup](https://www.meetup.com/austin-deep-learning/) in Austin, TX on the history of AI. The aim of these talks was to weave together a unique historical perspective on AI that integrates developments in philosophy, mathematics, and neuroscience and the various paths toward AI as we think of it today. The recordings of these talks can be found below:

* The History of AI Part I: Before the AI Winter (1822-1980) [[Link](https://www.youtube.com/watch?v=wgG5h6RTNmw)]
* The History of AI Part II: Modern Developments in AI and Neuroscience (1980-Present) [[Link](https://www.youtube.com/watch?v=kkh42Z9DTLo)]

## Personal research projects

**Active inference textbooks**: My primary research focus is the development of a textbook and other educational resources around the fields of Active Inference and Bayesian Mechanics. The book will be published by The MIT Press. I have primarily written this book outside of work but from January-July 2023 I was on sabbatical to focus on it exclusively. More detailed information is given on the [textbook](faif.md) page.

**Animal learning-based AI**: In collaboration with [Roy Clymer](https://matheta.com/) we have written a paper showcasing his work on an AI model inspired by animal learning. The model is based on a model of the synapse but is entirely different in construction from feed-forward neural networks and does not learn through backpropogation; superficially, the model has some similarities with spiking neural networks. It includes an agent-environment interaction loop and is capable of fairly complex behavioral chaining and learning in continuous time without any explicit calculations of gradients. More information and proof of concept results (using a Roomba) can be found on Roy's website linked above and in [this YouTube video](https://youtu.be/9IE-STHKxew). 

* Clymer RE, **Namjoshi SV**. A computational model of behavioral adaptation to solve the credit assignment problem. 2023. arXiv:2311.18134v1 [q-bio.NC]. [[arXiv](https://arxiv.org/abs/2311.18134)]

**Asynchronous federated learning**: In collaboration with my former co-workers at KUNGFU.AI. As part of my work at KUNGFU.AI we had to utilize federated learning in order to prevent the mixture of private patient data stored in different AWS cloud accounts. Federated learning as implemented by tools such as [Flwr](https://flower.dev/) require synchronous learning where the slowest dataset to train becomes the bottleneck for the other datasets. With our asynchronous federated learning setup it is possible to eliminate issues caused by bottlenecking datasets. This work is currently implemented in Python [[Github](https://github.com/kungfuai/flwr_serverless)]. 

* **Namjoshi SV**, Green R, Sharma K, Si Z. Serverless Federated Learning with flwr-serverless. 2023. arXiv:2310.15329v1 [cs.LG]. [[arXiv](https://arxiv.org/abs/2310.15329)]

## Industry research (highlights)

In December 2023, I joined VERSES.AI as a machine learning engineer.

At KUNGFU.AI I served as lead on a project to develop breast-cancer risk prediction software. The project involved developing a deep learning model using over 30 terrabytes of mammography data and temporal patient outcome data from hospitals around the world. The goal of the model was to provide calibrated risk scores with a 5-year predictive risk window that radiologists could use to provide more informed recommendations for their patients. This project required the application of federated learning to datasets stored on different cloud servers that could interact through VPC peering. 

At Hypergiant I served as lead on a project to develop an agent-based logistics simulator. The simulation was designed such that the user could change the initial conditions of the simulator to produce different outcome data. This data could then be used for forecasting to see how various business metrics would be expected to change as a result of changing the parameters of the simulation. This project served as a test-bed for asking "what-if" questions useful in business analytics.

## Postdoctoral research (highlights)

As part of my transition toward industry I worked in [Dr. Wei Zhang's lab](https://school.wakehealth.edu/faculty/z/wei-zhang#View%20Profile) on a computer vision project to detect brain cancer in 3D MRI images. I also contributed some bioinformatics analysis on a paper investigating the oncogene FGFR3-TACC3. 

* Lyu Q, **Namjoshi SV**, McTyre E, Topaloglu U, Barcus R, Chan MD, Cramer CK, Debinski W, Gurcan MN, Lesser GJ, Lin HK, Munden RF, Pasche BC, Sai KKS, Strowd RE, Tatter SB, Watabe K, Zhang W, Wang G, Whitlow CT. A transformer-based deep-learning approach for classifying brain metastases into primary organ sites using clinical whole-brain MRI images. *Patterns (N Y)*. 2022. 3(11):100613. doi: 10.1016/j.patter.2022.100613. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/36419451/)]
* Li T, Mehraein-Ghomi F, Forbes ME, **Namjoshi SV**, Ballard EA, Song Q, Chou PC, Wang X, Parker Kerrigan BC, Lang FF, Lesser G, Debinski W, Yang X, Zhang W. HSP90-CDC37 functions as a chaperone for the oncogenic FGFR3-TACC3 fusion. *Mol Ther*. 2022. 30(4):1610-1627. doi: 10.1016/j.ymthe.2022.02.009. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/35151844)] 

After my graduate work I wished to refine my knowledge in computational neuroscience. I worked with [Dr. Ken Kishida's lab](https://www.kishidalab.com/) on a number of different projects applying reinforcement learning and Bayesian statistics to analyze human subjects interacting with game theory-inspured tasks that investigated social norms, decision-making, and subjective consciousness. Among my major contributions was optimizing a model that could decompose a fast-scan cyclic voltammetry signal recording from patients undergoing deep-brain stimulation to distinguish different neurotransmitter measurements.

## Graduate research (highlights)

My graduate research was performed in [Kimberly Raab-Graham's lab](https://raabgrahamlab.com/) where I worked on a mix of molecular biology and bioinformatics applied to proteomics and transcriptomics. My early work focused on functional and network analysis of proteins affected by excitation or inhibition of the protein complex mTORC1 expressed in rat or mouse hippocampal neurons (via mass spectrometry). Many of these proteins controlled by mTORC1 expression are involved in memory processes and dysregulated in neurodegenerative diseases. Main paper related to this project:

* Niere F, **Namjoshi S**, Song E, Dilly GA, Schoenhard G, Zemelman BV, Mechref Y, Raab-Graham KF. Analysis of Proteins That Rapidly Change Upon Mechanistic/Mammalian Target of Rapamycin Complex 1 (mTORC1) Repression Identifies Parkinson Protein 7 (PARK7) as a Novel Protein Aberrantly Expressed in Tuberous Sclerosis Complex (TSC). *Mol Cell Proteomics.* 2016. 15(2):426-44. doi: 10.1074/mcp.M115.055079. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/26419955/)]

I have also worked with the RNA-binding protein fragile-X mental retardation protein (FMRP) whose dysregulation is implicated in neuronal dysfunction (autism spectrum disorders, depression). The researched involved utilizing RNA immunopreciptation followed by Illumina sequencing to identify the populations of RNA sequestered or released in RNA granules controlled by FMRP. Many of these RNA molecules could potentially be used in therapeutic treatments, particularly for the development of better rapidly-acting antidepressants. Main paper related to this project:

* Heaney CF, **Namjoshi SV**, Uneri A, Bach EC, Weiner JL, Raab-Graham KF. Role of FMRP in rapid antidepressant effects and synapse regulation. *Mol Psychiatry*. 2021. 26(6):2350-2362. doi: 10.1038/s41380-020-00977-z. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/33432187/)]

Additionally, I wrote a review which covers the general process of devising experiments for the purpose of extracting and analyzing RNA populations to study local mRNA translation under different experimental conditions.

* **Namjoshi SV** and Raab-Graham KF. Screening the Molecular Framework Underlying Local Dendritic mRNA Translation.
*Front Mol Neurosci.* 2017. doi: 10.3389/fnmol.2017.00045. eCollection 2017. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/28286470/)]

Other papers from my time in the Raab-Graham Lab

* Niere F, Uneri A, McArdle CJ, Deng Z, Egido-Betancourt HX, Cacheaux LP, **Namjoshi SV**, Taylor WC, Wang X, Barth SH, Reynoldson C, Penaranda J, Stierer MP, Heaney CF, Craft S, Keene CD, Ma T, Raab-Graham KF. Aberrant DJ-1 expression underlies L-type calcium channel hypoactivity in dendrites in tuberous sclerosis complex and Alzheimer's disease. *Proc Natl Acad Sci USA.* 2023. 120(45). doi: 10.1073/pnas.2301534120. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/37903257/)]
* Raab-Graham KF, Workman ER, **Namjoshi S**, Niere F. Pushing the threshold: How NMDAR antagonists induce homeostasis through protein synthesis to remedy depression. *Brain Res.* 2016. 1647:94-104. doi: 10.1016/j.brainres.2016.04.020. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/27125595/)]
* Wolfe SA, Workman ER, Heaney CF, Niere F, **Namjoshi S**, Cacheaux LP, Farris SP, Drew MR, Zemelman BV, Harris RA, Raab-Graham KF. FMRP regulates an ethanol-dependent shift in GABABR function and expression with rapid antidepressant properties. *Nat Commun*. 2016. 7:12867. doi: 10.1038/ncomms12867. [[PubMed](https://pubmed.ncbi.nlm.nih.gov/27666021/)]

I also worked in [Dr. Scott Stevens' Lab](https://molecularbiosci.utexas.edu/directory/scott-w-stevens) focusing on yeast genetics. This lab provided my background in experimental molecular biology. I performed functional analysis of proteins in the spliceosome, the primary protein complex in the cell which carries out RNA processing.
