---
permalink: /
title: ""
excerpt: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---

{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

My name is Yuxia Wu, a research scientist at [Singapore Management University (SMU)](https://www.smu.edu.sg/), working with [Assistant Prof. Yuan Fang](https://www.yfang.site/home). I also closely collaborate with [Assistant Prof. Lizi Liao](https://liziliao.github.io/). Previously, I obtained my Ph.D. degree in the area of *Computer Science* at [SMILES lab](http://www.smiles-xjtu.com/), Xi'an Jiaotong University, advised by [Prof. Xueming Qian](https://gr.xjtu.edu.cn/web/qianxm). 

**Research interests:** <a href='https://scholar.google.com/citations?user=bRgptuYAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

- **Recommendation System**: Sequential recommendation; Conversational recommendation; Explainable recommendation
- **Conversational System**: Task-oriented dialog system; Conversational understanding
- **Graph Data Mining**: Dynamic graph modeling; LLM for graphs
- **Spatial-Temporal**: Human mobility; Smart cities; Temporal event forecasting

> "The cradle rocks above an abyss, and common sense tells us that our existence is but a brief crack of light between two eternities of darkness." – "Speak, Memory" by *Vladimir Nabokov.*

# 🔥 News
- **[04/2025]**: We have organized a tutorial at WWW'25 on ["Few-Shot Learning on Graphs: From Meta-Learning to LLM-empowered Pre-Training and Beyond"](https://github.com/smufang/fewshotgraph)([Slides](my_papers/WWW25 Tutorial Fewshot Graph learning.pdf))
- **[04/2025]**: One paper about [RAG for dynamic graphs](https://arxiv.org/pdf/2408.14523) is accepted by SIGIR 2025.
- **[01/2025]**: One paper about [LLM for heterophilic graphs](https://arxiv.org/pdf/2408.14134) is accepted by NAACL 2025.
- **[09/2024]**: We have two papers accepted by EMNLP'24. Congrats to Yimin (one paper about [new intent discovery](https://aclanthology.org/2024.findings-emnlp.443/), accepted as Findings) and Jinggui (the first survey paper about [ontology expansion for conversational understanding](https://arxiv.org/pdf/2410.15019))!
- **[05/2024]**: Check out our Tutorials "Towards Graph Foundation Models" ([Part I](/my_papers/2024.05_WWW24Tutorial_GFM_Part1.pdf), [Part II](/my_papers/2024.05_WWW24Tutorial_GFM_Part2.pdf) & [Part III](/my_papers/2024.05_WWW24Tutorial_GFM_Part3.pdf)) at WWW'24.
- **[03/2024]**: Our paper about [new slot discovery](/my_papers/Active_Discovering_New_Slots_for_Task_oriented_Conversation.pdf) is accepted by IEEE/ACM Transactions on Audio, Speech, and Language Processing (TASLP).
- **[02/2024]**: Our paper about [simple Transformer for dynamic graph modeling](https://dl.acm.org/doi/pdf/10.1145/3589334.3645622) is accepted by WWW'24.
- **[11/2023]**: Our paper about [reason generation for POI recommendation](/my_papers/Reason Generation for Point of Interest Recommendation via a Hierarchical Attention-based Transformer Model.pdf) is accepted by IEEE Transactions on Multimedia (TMM).
- **[05/2023]**: I started the Research Scientist (Postdoc) position at Singapore Management University.

# 📝 Research 

## Selected Papers 
Please see my [Google Scholar](https://scholar.google.com/citations?user=bRgptuYAAAAJ) for the full publication list. (* Equal Contribution)

### Preprints:
- [HeTGB: A Comprehensive Benchmark for Heterophilic Text-Attributed Graphs](https://arxiv.org/abs/2503.04822) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/honey0219/HeTGB)

  **Shujie Li**<sup>\*</sup>, **Yuxia Wu**<sup>\*</sup>, Chuan Shi, Yuan Fang. 


### Published:

  - [Retrieval Augmented Generation for Dynamic Graph Modeling](https://arxiv.org/pdf/2408.14523) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/RAG4DyG)
    
    **Yuxia Wu**, Lizi Liao, Yuan Fang. SIGIR 2025
  
  - [Exploring the Potential of Large Language Models for Heterophilic Graphs](https://arxiv.org/pdf/2408.14134) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/honey0219/LLM4HeG)

    **Yuxia Wu**<sup>\*</sup>, **Shujie Li**<sup>\*</sup>,Yuan Fang, Chuan Shi. NAACL 2025


  - ["Pseudo-Label Enhanced Prototypical Contrastive Learning for Uniformed Intent Discovery"](https://aclanthology.org/2024.findings-emnlp.443/) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/dymanne123/PLPCL)

    **Yimin Deng**<sup>\*</sup>, **Yuxia Wu**<sup>\*</sup>, Li Zhu, Guoshuai Zhao, Xueming Qian. Findings of EMNLP 2024
    
  - ["A Survey of Ontology Expansion for Conversational Understanding"](https://arxiv.org/pdf/2410.15019) [![REPO](https://img.shields.io/badge/CODE-blue)](https://github.com/liangjinggui/Ontology-Expansion)

    Jinggui Liang, **Yuxia Wu**, Yuan Fang, Hao Fei, Lizi Liao. EMNLP 2024
  
  -  ["Active Discovering New Slots for Task-oriented Conversation"](/my_papers/Active_Discovering_New_Slots_for_Task_oriented_Conversation.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/Bi-criteria) <span class='show_paper_citations' data='bRgptuYAAAAJ:UebtZRa9Y70C'></span>
  
      **Yuxia Wu**<sup>\*</sup>, **Tianhao Dai**<sup>\*</sup>, Zhedong Zheng, Lizi Liao. TASLP 2024
        
  - ["On the Feasibility of Simple Transformer for Dynamic Graph Modeling"](https://dl.acm.org/doi/pdf/10.1145/3589334.3645622) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/SimpleDyG) <strong><span class='show_paper_citations' data='bRgptuYAAAAJ:KlAtU1dfN6UC'></span></strong> [![Poster](https://img.shields.io/badge/Poster-blue)](/my_papers/WWW24-SimpleDyG-poster.pdf) [![VIDEO](https://img.shields.io/badge/VIDEO-blue)](https://www.youtube.com/watch?v=7sS0yVRS_jM)
  
    **Yuxia Wu**, Yuan Fang, Lizi Liao. WWW 2024
  
  - ["Reason Generation for Point of Interest Recommendation via a Hierarchical Attention-based Transformer Model"](/my_papers/Reason Generation for Point of Interest Recommendation via a Hierarchical Attention-based Transformer Model.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/HAT)
   
    **Yuxia Wu**, Guoshuai Zhao, Mingdi Li, Zhuocheng Zhang, Xueming Qian. TMM 2023
    
  - ["Semi-supervised New Slot Discovery with Incremental Clustering"](/my_papers/2022.findings-emnlp.462.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/SIC) [![Slides](https://img.shields.io/badge/Slides-blue)](/my_papers/EMNLP22-SIC-slides.pdf) [![VIDEO](https://img.shields.io/badge/VIDEO-blue)](https://aclanthology.org/2022.findings-emnlp.462.mp4) 
  
    **Yuxia Wu**, Lizi Liao, Xueming Qian, Tat-Seng Chua. Findings of EMNLP 2022
  
  
  - ["State Graph Reasoning for Multimodal Conversational Recommendation"](/my_papers/State_Graph_Reasoning_for_Multimodal_Conversational_Recommendation.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/SGR) <strong><span class='show_paper_citations' data='bRgptuYAAAAJ:KlAtU1dfN6UC'></span></strong>
  
      **Yuxia Wu**, Lizi Liao, Gangyi Zhang, Wenqiang Lei, Guoshuai Zhao, Xueming Qian, Tat-Seng Chua. TMM 2022 
     
  
  - [“Personalized Long- and Short-term Preference Learning for Next POI Recommendation"](/my_papers/Personalized_Long-_and_Short-term_Preference_Learning_for_Next_POI_Recommendation.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/PLSPL) 
  
      **Yuxia Wu**, Ke Li, Guoshuai Zhao, Xueming Qian. TKDE 2020 <span style="color:red">(ESI Highly Cited Paper, Citations: 200+)</span>
  
  
  - ["LAST: Location-Appearance-Semantic-Temporal Clustering based POI Summarization"](/my_papers/LAST_Location-Appearance-Semantic-Temporal_Clustering_Based_POI_Summarization.pdf)
  
      Xueming Qian, **Yuxia Wu**, Mingdi Li, Yayun Ren, Shuhui Liang, Zhetao Li. TMM 2020 
    
  - ["Long- and Short-term Preference Learning for Next POI Recommendation"](/my_papers/Long-%20and%20Short-term%20Preference%20Learning%20for%20Next%20POI%20Recommendation.pdf) [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/PLSPL) [![Poster](https://img.shields.io/badge/Poster-blue)](/my_papers/CIKM19-LSPL-poster.pdf) [![Slides](https://img.shields.io/badge/Slides-blue)](/my_papers/CIKM19-LSPL-slides.pdf)
  
    **Yuxia Wu**, Ke Li, Guoshuai Zhao, Xueming Qian. CIKM 2019


> "You can’t ever reach perfection, but you can believe in an asymptote toward which you are ceaselessly striving." – "When Breath Becomes Air" by *Paul Kalanithi*
