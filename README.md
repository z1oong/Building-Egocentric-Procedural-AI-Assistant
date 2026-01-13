

<h1 align="center"><img src="image.png" alt="icon" width="48" height="48"> Building-Egocentric-Procedural-AI-Assistant</h1>
<p align="center">
    <a href='https://arxiv.org/pdf/2511.13261'>
      <img src='https://img.shields.io/badge/arXiv-PDF-green?style=flat&logo=arXiv&logoColor=green' alt='arXiv PDF'>
         </a>

## Our work focuses on Egocentric vision, VLMs, AI agent, Procedural tasks

🤔 Driven by recent advances in vision language models (VLMs) and egocentric perception research, we introduce the concept of an egocentric procedural AI assistant (EgoProceAssist) tailored to step-by-step support daily procedural tasks in a first-person view. In this work, we start by identifying three core tasks: egocentric procedural error detection, egocentric procedural learning, and egocentric procedural question answering. These tasks define the essential functions of EgoProceAssist within a new taxonomy. Specifically, our work encompasses a comprehensive review of current techniques, relevant datasets, and evaluation metrics across these three core areas. To clarify the gap between the proposed EgoProceAssist and existing VLM-based AI assistants, we introduce novel experiments and provide a comprehensive evaluation of representative VLM-based methods. Based on these findings and our technical analysis, we discuss the challenges ahead and suggest future research directions.

🔥 This is an active repository, you can watch for following the latest advances. If you find it useful, please kindly star this repo.

### ✨You are welcome to provide us your work with a topic related to it (involving egocentric procedural error detection, egocentric procedural learning and egocentric procedural question answering)!


<p align="center">
<div align="center">
  <img src="./image/precision1.png" width="350" style="display: inline-block; margin-right: 20px;">
  <img src="./image/eda.png" width="350" style="display: inline-block;">
</div>
<br>
<em>Left: Precision comparison | Right: EDA comparison</em>
</p>

## Summary of Contents
- [Summary of Contents](#summary-of-contents)
- [Taxonomy](#Taxonomy)
- [Paper Structure](#Paper-Structure)
- [Egocentric vision surveys](#Egocentric-vision-surveys)
- [Egocentric procedural error detection](#Egocentric-procedural-error-detection)
  - [Method](#Method)
  - [Datasets](#Datasets)
- [Egocentric procedural learning](#Egocentric-procedural-learning)
  - [Method](#Method)
  - [Datasets](#Datasets)
- [Egocentric procedural question answering](#Egocentric-procedural-question-answering)
  - [Method](#Method)
  - [Datasets](#Datasets)
- [Experiment](#Experiment)
- [Cite The Paper](#Cite-The-Paper)


## Taxonomy

<p align="center">
<img src="./image/taxonomy.png" width="750">
</p>

## Paper Structure

<p align="center">
<img src="./image/stu2.png" width="750">
</p>

## Egocentric vision surveys
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2025|arXiv|[Challenges and Trends in Egocentric Vision: A Survey](https://arxiv.org/pdf/2503.15275) |-|
|2025|Elsevier|[Egocentric and Exocentric Methods: A Short Survey](https://arxiv.org/pdf/2410.20621) |-|
|2024|IJCV|[An Outlook into the Future of Egocentric Vision](https://arxiv.org/pdf/2410.20621) |-|
|2022|Elsevier|[Egocentric Vision-based Action Recognition: A survey](https://pdf.sciencedirectassets.com/271597/1-s2.0-S0925231221X00422/1-s2.0-S0925231221017586/main.pdf?X-Amz-Security-Token=IQoJb3JpZ2luX2VjEAgaCXVzLWVhc3QtMSJHMEUCIBucUcuZaPn8CMmxvGeH3ov8Wz5W%2BBXKQP%2BLn%2F3ueb74AiEA8vhKKu5ffSKYCN0rv5dXFpWUDATeUnY61RCy%2FYAKCJIqvAUI0f%2F%2F%2F%2F%2F%2F%2F%2F%2F%2FARAFGgwwNTkwMDM1NDY4NjUiDDARy3BOOS88wBpfSyqQBW7VBIcsJvX3AXHdfMS1NkyXedochSm49UqRwdSpbsMV9taGvHvNgGozLCveQnuSH%2FvbColAKpmDDSwK5XwIhjX0H%2FXLvRQzAL%2B6Q0QDWeE6rBksFQkvcvpHdeQxsCEBbq6AOfQNCIeUxdfjUWGYk0J3bvu7mMye4ERryqRuzo9yy5kEjlmNmgRpciTisJTGa2DlVKoEJV17peTc9e86GmKa%2Fqx4SGlSyzd%2Bnd%2F8v%2BK3yeg3%2FMMCK7O2cmOJSJ9AcD5%2Fd0nHC8dNqfCeAQLK8EqqJUm4wcPlznzbXjbLpS65k7A0OXgwIaSKVsjspFryRkrYZaclUrxI8o16RRcB%2FvhYQkiG0M2rXLnlp0lQYRRkNTUyK9DSwwOQnC170L%2FWXUZznbFieiqxMfDlNAz0EjVApl7KV1Jel9%2FbZOrA8HSHkVKFicKsX9x83PE2CwP8Y%2FZ%2FlHhbALPXfoa9Nn3PB7OaqvA4WlR6%2BJbwLaHRMl7MgjTX0eM8INtvWF%2FTdgLgiPXinFrMVeoWgCCw%2BBo93w9a0R%2FCqznFtBjGCemDV05X%2FF4wJhHNdrIHjE26IBaYzHccuZqIQ2EST2GUnrYeRIyAAzFnFfo5BhrTiAzFTO17Tl0wjq%2FnIPRVRTTCq6pEtNRBd21DVVCLrc%2BqxNx8ztRdh22Ghb8DzsYGbRKMZskRgi8cjQweFg0V%2FX50bN6MonaOXtX%2BnPv%2BKwwNUAN5JPh1usYReIHpPzCF9VZv5zU2X5awuvBY1BHj7W0iI25dVPQ%2FxuhDXwcASN1HMggRr6rjX23ZGFm%2Fagx0gwVdZ7IT0VBL%2FVw4JNi%2BRLnPwoUphYAeRTA%2F7MscRoR%2BNmoDzFju5mZRqqo9DRdu4HsqG%2FvZMI3ku8gGOrEBvWl%2BLALTvtLSkEmdkgKg2E1f%2B0qWPfFe0AooyJ5wNzKZfqlQ5cDgLpVeZcVJIux5Fq550CBdKeGl8LwUGHx8i%2BScJlaNTHuPDzVz5cQijxY1hiUcQDIEQ2Te0lVpjIf78yhuX%2BIcDQEFptTN8TSb%2BO1Lba%2BL6AZ5VUUXRlYgNz3Te74G2WARIHOsda7xd6XoEFj3FriV5ATsOcQuUrHpCqXAYP6MfCqvA93mos%2FJ1Wi%2B&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Date=20251108T082612Z&X-Amz-SignedHeaders=host&X-Amz-Expires=300&X-Amz-Credential=ASIAQ3PHCVTYTNMWRRPT%2F20251108%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Signature=8da42e2e006a7d2aa586e62c90c3d2a9fc659265f3499877706d1c19026ebab5&hash=1b29c1a88b7322e376002b3b92c9611ea3f33c7d5cb651ee92acb58dd55dfbf5&host=68042c943591013ac2b2430a89b270f6af2c76d8dfd086a07176afe7c76c2c61&pii=S0925231221017586&tid=spdf-e7b3c3bb-a024-4360-856f-c86447562be1&sid=d36d6db986e485479b2b2495214d36574204gxrqa&type=client&tsoh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&rh=d3d3LnNjaWVuY2VkaXJlY3QuY29t&ua=120e5e56005702065d5155&rr=99b3af2629b88570&cc=hk) |-|
|2021|ITSC|[A Survey on Deep-Learning Methods for Pedestrian Behavior Prediction from the Egocentric View](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9565041) |-|
|2021|Elsevier|[Predicting the Future from First Person (Egocentric) Vision: A Survey](https://arxiv.org/pdf/2107.13411) |-|
|2020|TPAMI|[Analysis of the hands in egocentric vision: A survey](https://arxiv.org/pdf/1912.10867) |-|
|2017|ICWT|[A Survey of Activity Recognition in Egocentric Life-logging datasets](https://www.researchgate.net/profile/Khalid-Elasnaoui-2/publication/317248361_A_survey_of_activity_recognition_in_egocentric_lifelogging_datasets/links/5c225a87299bf12be399fd0e/A-survey-of-activity-recognition-in-egocentric-lifelogging-datasets.pdf) |-|
|2016|THMS|[Summarization of egocentric videos: A comprehensive survey](https://ink.library.smu.edu.sg/cgi/viewcontent.cgi?article=6200&&context=sis_research&&sei-redir=1&referer=https%253A%252F%252Fscholar.google.com%252Fscholar%253Fhl%253Dzh-CN%2526as_sdt%253D0%25252C5%2526q%253DSummarization%252Bof%252Begocentric%252Bvideos%25253A%252BA%252Bcomprehensive%252Bsurvey%2526btnG%253D#search=%22Summarization%20egocentric%20videos%3A%20comprehensive%20survey%22) |-|
|2016|MDPI|[Recognition of Activities of Daily Living with Egocentric Vision: A Review](https://www.mdpi.com/1424-8220/16/1/72) |-|
|2015|arXiv|[A Survey on Recent Advances of Computer Vision Algorithms for Egocentric Video](https://arxiv.org/pdf/1501.02825) |-|

### Egocentric vision surveys timeline

<p align="center">
<img src="./image/sur.png" width="750">
</p>

## Egocentric procedural error detection

### Method

|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2025|CVPR|[Modeling Multiple Normal Action Representations for Error Detection in Procedural Tasks](https://openaccess.thecvf.com/content/CVPR2025/papers/Huang_Modeling_Multiple_Normal_Action_Representations_for_Error_Detection_in_Procedural_CVPR_2025_paper.pdf) |[Project Page](https://github.com/iSEE-Laboratory/AMNAR)|
|2025|CVPR|[Gazing Into Missteps: Leveraging Eye-Gaze for Unsupervised Mistake Detection in Egocentric Videos of Skilled Human Activities](https://openaccess.thecvf.com/content/CVPR2025/papers/Mazzamuto_Gazing_Into_Missteps_Leveraging_Eye-Gaze_for_Unsupervised_Mistake_Detection_in_CVPR_2025_paper.pdf) |-|
|2025|arXiv|[Technical Report for Egocentric Mistake Detection for the HoloAssist Challenge](https://arxiv.org/pdf/2506.06174) |[Project Page](https://www.codabench.org/competitions/2613/)|
|2025|EMNLP|[Transparent and Coherent Procedural Mistake Detection](https://aclanthology.org/2025.emnlp-main.706.pdf)|-|
|2024|CVPR|[Error Detection in Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/papers/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.pdf)|[Project Page](https://github.com/robert80203/EgoPER_official)|
|2024|CVPR|[PREGO: online mistake detection in PRocedural EGOcentric videos](https://openaccess.thecvf.com/content/CVPR2024/papers/Flaborea_PREGO_Online_Mistake_Detection_in_PRocedural_EGOcentric_Videos_CVPR_2024_paper.pdf)|[Project Page](https://github.com/aleflabo/PREGO)|
|2024|arXiv|[TI-PREGO: Chain of Thought and In-Context Learning for Online Mistake Detection in PRocedural EGOcentric Videos](https://arxiv.org/pdf/2411.02570)|-|
|2024|ICCV|[EgoOops: A Dataset for Mistake Action Detection from Egocentric Videos referring to Procedural Texts](https://openaccess.thecvf.com/content/ICCV2025W/SAUAFG/papers/Haneji_EgoOops_A_Dataset_for_Mistake_Action_Detection_from_Egocentric_Videos_ICCVW_2025_paper.pdf)|[Project Page](https://y-haneji.github.io/EgoOops-project-page/)|
|2023|arXiv|[Every Mistake Counts in Assembly](https://arxiv.org/pdf/2307.16453)|-|

### Datasets
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2024|NeurIPS|[CaptainCook4D: A Dataset for Understanding Errors in Procedural Activities](https://proceedings.neurips.cc/paper_files/paper/2024/file/f4a04396c2ed1342a5d8d05e94cb6101-Paper-Datasets_and_Benchmarks_Track.pdf)|[Project Page](https://captaincook4d.github.io/captain-cook/)|
|2024|WACV|[ndustreal: A dataset for procedure step recognition handling execution errors in egocentric videos in an industrial-like setting](https://openaccess.thecvf.com/content/WACV2024/papers/Schoonbeek_IndustReal_A_Dataset_for_Procedure_Step_Recognition_Handling_Execution_Errors_WACV_2024_paper.pdf)|[Project Page](https://github.com/TimSchoonbeek/IndustReal)|
|2024|CVPR|[Error Detection in Egocentric Procedural Task Videos](https://openaccess.thecvf.com/content/CVPR2024/papers/Lee_Error_Detection_in_Egocentric_Procedural_Task_Videos_CVPR_2024_paper.pdf)|[Project Page](https://github.com/robert80203/EgoPER_official)|
|2024|ICCV|[EgoOops: A Dataset for Mistake Action Detection from Egocentric Videos referring to Procedural Texts](https://openaccess.thecvf.com/content/ICCV2025W/SAUAFG/papers/Haneji_EgoOops_A_Dataset_for_Mistake_Action_Detection_from_Egocentric_Videos_ICCVW_2025_paper.pdf)|[Project Page](https://y-haneji.github.io/EgoOops-project-page/)|
|2024|NeurIPS|[IKEA Manuals at Work: 4D Grounding of Assembly Instructions on Internet Videos](https://proceedings.neurips.cc/paper_files/paper/2024/file/936c72edff325b2ad5eda320e916487f-Paper-Datasets_and_Benchmarks_Track.pdf)|[Project Page](https://yunongliu1.github.io/ikea-video-manual/)|
|2024|CVPR|[Ego-Exo4D: Understanding Skilled Human Activity from First- and Third-Person Perspectives](https://openaccess.thecvf.com/content/CVPR2024/papers/Grauman_Ego-Exo4D_Understanding_Skilled_Human_Activity_from_First-_and_Third-Person_Perspectives_CVPR_2024_paper.pdf)|-|
|2023|ICCV|[HoloAssist: an Egocentric Human Interaction Dataset for Interactive AI Assistants in the Real World](https://openaccess.thecvf.com/content/ICCV2023/papers/Wang_HoloAssist_an_Egocentric_Human_Interaction_Dataset_for_Interactive_AI_Assistants_ICCV_2023_paper.pdf)|[Project Page]( https://holoassist.github.io/)|
|2022|CVPR|[Ego4D: Around the World in 3,000 Hours of Egocentric Video](https://openaccess.thecvf.com/content/CVPR2022/papers/Grauman_Ego4D_Around_the_World_in_3000_Hours_of_Egocentric_Video_CVPR_2022_paper.pdf)|[Project Page]( https://ego4d-data.org/)|
|2022|CVPR|[Assembly101: A Large-Scale Multi-View Video Dataset for Understanding Procedural Activities](https://openaccess.thecvf.com/content/CVPR2022/papers/Sener_Assembly101_A_Large-Scale_Multi-View_Video_Dataset_for_Understanding_Procedural_Activities_CVPR_2022_paper.pdf)|[Project Page](https://assembly101.github.io/)|
|2020|TPAMI|[EgoCom: A Multi-Person Multi-Modal Egocentric Communications Dataset](https://ieeexplore.ieee.org/stamp/stamp.jsp?arnumber=9200754)|[Project Page](https://github.com/facebookresearch/EgoCom-Dataset)|
|2020|TPAMI|[The EPIC-KITCHENS Dataset: Collection, Challenges and Baselines](https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=9084270)|[Project Page]( http://epic-kitchens.github.io.)|
|2019|ICCV|[EPIC-Tent: An Egocentric Video Dataset for Camping Tent Assembly](https://openaccess.thecvf.com/content_ICCVW_2019/papers/EPIC/Jang_EPIC-Tent_An_Egocentric_Video_Dataset_for_Camping_Tent_Assembly_ICCVW_2019_paper.pdf)|-|

## Egocentric procedural learning

### Method
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2025|ICCV|[HiERO: understanding the hierarchy of human behavior enhances reasoning on egocentric videos](https://openaccess.thecvf.com/content/ICCV2025/papers/Peirone_HiERO_Understanding_the_Hierarchy_of_Human_Behavior_Enhances_Reasoning_on_ICCV_2025_paper.pdf)|[Project Page](https://sapeirone.github.io/HiERO/)|
|2025|arXiv|[Procedure Learning via Regularized Gromov-Wasserstein Optimal Transport](https://arxiv.org/pdf/2507.15540)|-|
|2024|WACV|[United We Stand, Divided We Fall: UnityGraph for Unsupervised Procedure Learning from Videos](https://openaccess.thecvf.com/content/WACV2024/papers/Bansal_United_We_Stand_Divided_We_Fall_UnityGraph_for_Unsupervised_Procedure_WACV_2024_paper.pdf) |-|
|2024|NeurIPS|[OPEL: Optimal Transport Guided ProcedurE Learning](https://proceedings.neurips.cc/paper_files/paper/2024/file/6e4b14e76d0d4f42a9dff031a7a8417b-Paper-Conference.pdf)|-|
|2023|ICCV|[STEPs: Self-Supervised Key Step Extraction and Localization from Unlabeled Procedural Videos](https://openaccess.thecvf.com/content/ICCV2023/papers/Shah_STEPs_Self-Supervised_Key_Step_Extraction_and_Localization_from_Unlabeled_Procedural_ICCV_2023_paper.pdf)|[Project Page](https://github.com/anshulbshah/STEPs)| 
|2022|CVPR|[Learning To Recognize Procedural Activities with Distant Supervision](https://openaccess.thecvf.com/content/CVPR2022/papers/Lin_Learning_To_Recognize_Procedural_Activities_With_Distant_Supervision_CVPR_2022_paper.pdf)|[Project Page](https://github.com/annusha/unsup_temp_embed)|
|2022|ECCV|[My View is the Best View: Procedure Learning from Egocentric Videos](https://arxiv.org/pdf/2207.10883)|[Project Page](https://sid2697.github.io/egoprocel/)| 
|2020|BMVC|[Procedure Completion by Learning from Partial Summaries](https://par.nsf.gov/servlets/purl/10304222)|-|
|2019|ICCV|[Unsupervised Procedure Learning via Joint Dynamic Summarization](https://openaccess.thecvf.com/content_ICCV_2019/papers/Elhamifar_Unsupervised_Procedure_Learning_via_Joint_Dynamic_Summarization_ICCV_2019_paper.pdf)|-|
|2019|CVPR|[Unsupervised learning of action classes with continuous temporal embedding](https://openaccess.thecvf.com/content_CVPR_2019/papers/Kukleva_Unsupervised_Learning_of_Action_Classes_With_Continuous_Temporal_Embedding_CVPR_2019_paper.pdf)|[Project Page](https://github.com/annusha/unsup_temp_embed)|
|2019|CVPR|[Cross-task weakly supervised learning from instructional videos](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhukov_Cross-Task_Weakly_Supervised_Learning_From_Instructional_Videos_CVPR_2019_paper.pdf)|[Project Page](https://github.com/DmZhukov/CrossTask)|
|2018|AAAI|[Towards Automatic Learning of Procedures From Web Instructional Videos](https://ojs.aaai.org/index.php/AAAI/article/view/12342)|[Project Page](http://youcook2.eecs.umich.edu)|
|2016|CVPR|[Unsupervised Learning from Narrated Instruction Videos](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Alayrac_Unsupervised_Learning_From_CVPR_2016_paper.pdf)|-|
|2015|ICCV|[Unsupervised Semantic Parsing of Video Collections](https://openaccess.thecvf.com/content_iccv_2015/papers/Sener_Unsupervised_Semantic_Parsing_ICCV_2015_paper.pdf)|-|

### Datasets
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2022|ECCV|[My View is the Best View: Procedure Learning from Egocentric Videos](https://arxiv.org/pdf/2207.10883)|[Project Page](https://sid2697.github.io/egoprocel/)| 
|2019|ICCV|[Unsupervised Procedure Learning via Joint Dynamic Summarization](https://openaccess.thecvf.com/content_ICCV_2019/papers/Elhamifar_Unsupervised_Procedure_Learning_via_Joint_Dynamic_Summarization_ICCV_2019_paper.pdf)|-|
|2019|CVPR|[Cross-task weakly supervised learning from instructional videos](https://openaccess.thecvf.com/content_CVPR_2019/papers/Zhukov_Cross-Task_Weakly_Supervised_Learning_From_Instructional_Videos_CVPR_2019_paper.pdf)|[Project Page](https://github.com/DmZhukov/CrossTask)|
|2019|ICCV|[HowTo100M: Learning a Text-Video Embedding by Watching Hundred Million Narrated Video Clips](https://openaccess.thecvf.com/content_ICCV_2019/papers/Miech_HowTo100M_Learning_a_Text-Video_Embedding_by_Watching_Hundred_Million_Narrated_ICCV_2019_paper.pdf)|[Project Page](https://www.di.ens.fr/willow/research/howto100m)|
|2019|CVPR|[COIN: A Large-scale Dataset for Comprehensive Instructional Video Analysis](https://openaccess.thecvf.com/content_CVPR_2019/papers/Tang_COIN_A_Large-Scale_Dataset_for_Comprehensive_Instructional_Video_Analysis_CVPR_2019_paper.pdf)|[Project Page](https://coin-dataset.github.io/)|
|2018|AAAI|[Towards Automatic Learning of Procedures From Web Instructional Videos](https://ojs.aaai.org/index.php/AAAI/article/view/12342)|[Project Page](http://youcook2.eecs.umich.edu)|
|2016|CVPR|[Unsupervised Learning from Narrated Instruction Videos](https://www.cv-foundation.org/openaccess/content_cvpr_2016/papers/Alayrac_Unsupervised_Learning_From_CVPR_2016_paper.pdf)|-|
|2014|CVPR|[The Language of Actions: Recovering the Syntax and Semantics of Goal-Directed Human Activities](https://www.cv-foundation.org/openaccess/content_cvpr_2014/papers/Kuehne_The_Language_of_2014_CVPR_paper.pdf)|[Project Page](http://serre-lab.clps.brown.edu/resource/breakfast-actions-dataset)|

## Egocentric procedural question answering
### Method
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2025|CVPR|[EgoLife: Towards Egocentric Life Assistant](https://openaccess.thecvf.com/content/CVPR2025/papers/Yang_EgoLife_Towards_Egocentric_Life_Assistant_CVPR_2025_paper.pdf)|[Project Page](https://egolife-ai.github.io/)|
|2025|ACM|[Vinci: A Real-time Smart Assistant Based on Egocentric Vision-language Model for Portable Devices](https://dl.acm.org/doi/pdf/10.1145/3749513?casa_token=4R5wGrfFEg0AAAAA:-XIdnoXT_uvFvFglxoh__NMgOI9ttVekQj_Vb-rN_oBu-Qg6mfN9cynV4CCsXhi6Jfi_VcrCPOoKRw)|[Project Page](https://github.com/OpenGVLab/vinci)|
|2025|arXiv|[HCQA-1.5 @ Ego4D EgoSchema Challenge 2025](https://arxiv.org/pdf/2505.20644?)|[Project Page]( https://github.com/Hyu-Zhang/HCQA)|
|2025|arXiv|[From Pixels to Graphs: using Scene and Knowledge Graphs for HD-EPIC VQA Challenge](https://arxiv.org/pdf/2506.08553?)|-|
|2025|AAAI|[Grounded Multi-Hop VideoQA in Long-Form Egocentric Videos](https://ojs.aaai.org/index.php/AAAI/article/view/32214)|[Project Page](https://qirui-chen.github.io/MultiHop-EgoQA/)|
|2025|ICLR|[MM-EGO: TOWARDS BUILDING EGOCENTRIC MULTIMODAL LLMS FOR VIDEO QA](https://arxiv.org/pdf/2410.07177)|-|
|2025|arXiv|[RAVEN: Query-Guided Representation Alignment for Question Answering over Audio, Video, Embedded Sensors, and Natural Language](https://arxiv.org/pdf/2505.17114)|[Project Page](https://github.com/BASHLab/RAVEN)|
|2024|CVPR|[Grounded Question-Answering in Long Egocentric Videos](https://openaccess.thecvf.com/content/CVPR2024/papers/Di_Grounded_Question-Answering_in_Long_Egocentric_Videos_CVPR_2024_paper.pdf)|[Project Page](https://github.com/Becomebright/GroundVQA)|
|2024|arXiv|[HCQA @ Ego4D EgoSchema Challenge 2024](https://arxiv.org/pdf/2406.15771?)|[Project Page](https://github.com/Hyu-Zhang/HCQA)|
|2024|arXiv|[ALANA VLM: A Multimodal Embodied AI Foundation Model for Egocentric Video Understanding](https://arxiv.org/pdf/2406.13807)|[Project Page]( https://github.com/alanaai/EVUD)|
|2023|arXiv|[LifelongMemory: Leveraging LLMs for Answering Queries in Long-form Egocentric Videos](https://arxiv.org/pdf/2312.05269)|[Project Page](https://agenticlearning.ai/lifelong-memory)|

### Datasets
|Year|Venue|Paper Title|Link|
|:-:|:-:|-|-|
|2025|CVPR|[Egotextvqa: Towards egocentric scene-text aware video question answering](https://openaccess.thecvf.com/content/CVPR2025/papers/Zhou_EgoTextVQA_Towards_Egocentric_Scene-Text_Aware_Video_Question_Answering_CVPR_2025_paper.pdf)|[Project Page](https://github.com/zhousheng97/EgoTextVQA)|
|2025|arXiv|[EgoBlind: Towards Egocentric Visual Assistance for the Blind People](https://arxiv.org/pdf/2503.08221?)|[Project Page](https://github.com/doc-doc/EgoBlind)|
|2025|CVPR|[Omnia de egotempo: Benchmarking temporal understanding of multi-modal llms in egocentric videos](https://openaccess.thecvf.com/content/CVPR2025/papers/Plizzari_Omnia_de_EgoTempo_Benchmarking_Temporal_Understanding_of_Multi-Modal_LLMs_in_CVPR_2025_paper.pdf)|[Project Page](https://github.com/google-research-datasets/egotempo.git)|
|2024|arXiv|[Hoi-ref: Hand-object interaction referral in egocentric vision](https://arxiv.org/pdf/2404.09933?)|[Project Page](https://sid2697.github.io/hoi-ref)|
|2024|arXiv|[ALANA VLM: A Multimodal Embodied AI Foundation Model for Egocentric Video Understanding](https://arxiv.org/pdf/2406.13807)|[Project Page]( https://github.com/alanaai/EVUD)|
|2024|arXiv|[Video question answering for people with visual impairments using an egocentric 360-degree camera](https://arxiv.org/pdf/2405.19794)|[Project Page](https://agenticlearning.ai/lifelong-memory)|
|2023|NeurIPS|[Egoschema: A diagnostic benchmark for very long-form video language understanding](https://proceedings.neurips.cc/paper_files/paper/2023/file/90ce332aff156b910b002ce4e6880dec-Paper-Datasets_and_Benchmarks.pdf)|[Project Page](egoschema.github.io)|
|2022|ECCV|[Assistq: Affordance-centric question-driven task completion for egocentric assistant](https://arxiv.org/pdf/2203.04203)|[Project Page](https://showlab.github.io/assistq/)|
|2018|CVPR|[Embodied question answering](https://openaccess.thecvf.com/content_cvpr_2018/papers/Das_Embodied_Question_Answering_CVPR_2018_paper.pdf)|[Project Page](embodiedqa.org)|

## Experiment

🧪 In this part, we demonstrate the performance of some models and agents in egocentric procedural error detection and egocentric procedural learning. Specific experimental details can be found in the paper.

### Experiment Results in Egocentric Procedural Error Detection

<p align="center">
<img src="./image/error.png" width="750">
</p>


### Experiment Results in Egocentric Procedural Learning

<p align="center">
<img src="./image/learning.png" width="750">
</p>

## Cite The Paper
If you find our paper and repository useful for your research project, please consider citing our paper:

```bibtex
@misc{li2025buildingegocentricproceduralai,
      title={Building Egocentric Procedural AI Assistant: Methods, Benchmarks, and Challenges}, 
      author={Junlong Li and Huaiyuan Xu and Sijie Cheng and Kejun Wu and Kim-Hui Yap and Lap-Pui Chau and Yi Wang},
      year={2025},
      eprint={2511.13261},
      archivePrefix={arXiv},
      primaryClass={cs.CV},
      url={https://arxiv.org/abs/2511.13261}, 
}
```



