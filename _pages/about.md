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

My name is Yuxia Wu, a research scientist at [Singapore Management University (SMU)](https://www.smu.edu.sg/), supervised by [Assistant Prof. Yuan Fang](https://www.yfang.site/home). Before that, I obtained my Ph.D. degree in the area of *Computer Science* at [SMILES lab](http://www.smiles-xjtu.com/), Xi'an Jiaotong University, advised by [Prof. Xueming Qian](https://gr.xjtu.edu.cn/web/qianxm). I also hold a Master's degree and a Bachelor's degree in *Biomedical Engineering* from Airforce Medical University and Zhengzhou University.

**Research interests:** <a href='https://scholar.google.com/citations?user=bRgptuYAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

- **Graph mining**: dynamic graph modeling, temporal knowledge graph, LLM for graphs
- **Recommendation systems**: conversational recommendation, sequential recommendation, generative AI for recommendations
- **NLP**: conversational search and recommendation, new slot/intent discovery
- **Medical image processing**: medical image registration, brain image analysis, computer aided diagnosis
- **AI for science**: molecular generation

I am interested in conducting interdisciplinary research and open to collaborations with academic and industry partners in my research areas. If you are interested in working together, please feel free to contact me.

> "Imagination is more important than knowledge. For knowledge is limited, whereas imagination embraces the entire world, stimulating progress, giving birth to evolution." – Albert Einstein

# 📝 Publications [[Google Scholar](https://scholar.google.com/citations?user=bRgptuYAAAAJ)]

<div class='paper-box' style="width:100%; margin:auto;">
    <div class='paper-box-image'>
        <div>
            <div class="badge">TASLP 2024</div>
            <img src='images/Active_Discovering_New_Slots_for_Task_oriented_Conversation_03.png' alt="sym" style="width:100%; height:auto;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
      
["Active Discovering New Slots for Task-oriented Conversation"](/my_papers/Active_Discovering_New_Slots_for_Task_oriented_Conversation.pdf)

<span style="color:#4FC3F7">**Yuxia Wu**</span>, Tianhao Dai, Zhedong Zheng, Lizi Liao.

[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/Bi-criteria) <span class='show_paper_citations' data='bRgptuYAAAAJ:UebtZRa9Y70C'></span>
</div>
</div>

<div class='paper-box' style="width:100%; margin:auto;">
    <div class='paper-box-image'>
        <div>
            <div class="badge">WWW 2024</div>
            <img src='images/On the Feasibility of Simple Transformer for Dynamic Graph Modeling_03 copy.png' alt="sym" style="width:100%; height:auto;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
           
  ["On the Feasibility of Simple Transformer for Dynamic Graph Modeling"](https://dl.acm.org/doi/pdf/10.1145/3589334.3645622)
      
<span style="color:#4FC3F7">**Yuxia Wu**</span>, Yuan Fang, Lizi Liao.
        
[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/SimpleDyG) <strong><span class='show_paper_citations' data='bRgptuYAAAAJ:KlAtU1dfN6UC'></span></strong> [![Poster](https://img.shields.io/badge/Poster-blue)](/my_papers/WWW24-SimpleDyG-poster.pdf) [![VIDEO](https://img.shields.io/badge/VIDEO-blue)](https://www.youtube.com/watch?v=7sS0yVRS_jM)
</div>
</div>

<div class='paper-box' style="width:100%; margin:auto;">
    <div class='paper-box-image'>
        <div>
            <div class="badge">EMNLP 2022</div>
            <img src='images/2022.findings-emnlp.462_02.png' alt="sym" style="width:100%; height:auto;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">

["Semi-supervised New Slot Discovery with Incremental Clustering"](/my_papers/2022.findings-emnlp.462.pdf) 
        
<span style="color:#4FC3F7">**Yuxia Wu**</span>, Lizi Liao, Xueming Qian, Tat-Seng Chua.

[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/SIC) [![Slides](https://img.shields.io/badge/Slides-blue)](/my_papers/EMNLP22-SIC-slides.pdf) [![VIDEO](https://img.shields.io/badge/VIDEO-blue)](https://aclanthology.org/2022.findings-emnlp.462.mp4)
    
</div>
</div>

<div class='paper-box' style="width:100%; margin:auto;">
    <div class='paper-box-image'>
        <div>
            <div class="badge">TMM 2022</div>
            <img src='images/SGR.png' alt="sym" style="width:100%; height:auto;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">
        
["State Graph Reasoning for Multimodal Conversational Recommendation"](/my_papers/State_Graph_Reasoning_for_Multimodal_Conversational_Recommendation.pdf)
        
<span style="color:#4FC3F7">**Yuxia Wu**</span>, Lizi Liao, Gangyi Zhang, Wenqiang Lei, Guoshuai Zhao, Xueming Qian, Tat-Seng Chua
      
[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/SGR) <strong><span class='show_paper_citations' data='bRgptuYAAAAJ:KlAtU1dfN6UC'></span></strong>
   
</div>
</div>



<div class='paper-box' style="width:100%; margin:auto;">
    <div class='paper-box-image'>
        <div>
            <div class="badge">TKDE 2020</div>
            <img src='images/PLSPL.png' alt="sym" style="width:100%; height:auto;">
        </div>
    </div>
    <div class='paper-box-text' markdown="1">

  [“Personalized Long- and Short-term Preference Learning for Next POI Recommendation](/my_papers/Personalized_Long-_and_Short-term_Preference_Learning_for_Next_POI_Recommendation.pdf)
      
       
<span style="color:#4FC3F7">**Yuxia Wu**</span>, Ke Li, Guoshuai Zhao, Xueming Qian.
 
[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/PLSPL) <span style="color:red">(ESI Highly Cited Paper, Citations: 130+)</span>

</div>
</div>



- ``TMM 2023`` ["Reason Generation for Point of Interest Recommendation via Hierarchical Attention-based Transformer Model"](/my_papers/Reason Generation for Point of Interest Recommendation via a Hierarchical Attention-based Transformer Model.pdf) 

  <span style="color:#4FC3F7">**Yuxia Wu**</span>, Guoshuai Zhao, Mingdi Li, Zhuocheng Zhang, Xueming Qian. 
  [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/YuxiaWu/HAT)

- ``TMM 2020`` ["LAST: Location-Appearance-Semantic-Temporal Clustering based POI Summarization"](/my_papers/LAST_Location-Appearance-Semantic-Temporal_Clustering_Based_POI_Summarization.pdf)
  
  Xueming Qian, <span style="color:#4FC3F7">**Yuxia Wu**</span>, Mingdi Li, Yayun Ren, Shuhui Liang, Zhetao Li. 
  
- ``CIKM 2019``["Long- and Short-term Preference Learning for Next POI Recommendation"](/my_papers/Long-%20and%20Short-term%20Preference%20Learning%20for%20Next%20POI%20Recommendation.pdf)
  
  <span style="color:#4FC3F7">**Yuxia Wu**</span>, Ke Li, Guoshuai Zhao, Xueming Qian.
  [![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/PLSPL) [![Poster](https://img.shields.io/badge/Poster-blue)](/my_papers/CIKM19-LSPL-poster.pdf) [![Slides](https://img.shields.io/badge/Slides-blue)](/my_papers/CIKM19-LSPL-slides.pdf)

- ``SPIE 2017``["Multi-contrast MRI registration of carotid arteries based on cross-sectional images and lumen boundaries"](/my_papers/SPIE.pdf)
  
  <span style="color:#4FC3F7">**Yuxia Wu**</span>, Xi Zhang, Xiaopan Xu, Yang Liu, Guopeng Zhang, Baojuan Li, Huijun Chen, Hongbing Lu. 

# 🎓 Educations
- *2017.09 - 2023.03*,	Ph.D. in Information and Communication Engineering, Xi'an Jiaotong University, Shaanxi, China.
- *2014.09 - 2017.07*,	Master of Engineering in Biomedical Engineering, Air Force Medical University, Shaanxi, China.
- *2010.09 - 2014.07*,	Bachelor of Engineering in Biomedical Engineering, Zhengzhou University, Henan, China

# 🍀 Experiences
- *2023.05 - now*, Research Scientist, Singapore Management University. 
  - **Research Topic**: Graph Data Mining
  - **Supervisor**: [Assistant Prof. Yuan Fang](https://www.yfang.site/home)
    
- *2021.03 - 2022.10*, Research Intern, NExT++ Research Center, National University of Singapore.
  - **Research Topic**: Conversational Recommender System
  - **Supervisor**: [Prof.Tat-Seng Chua](https://www.chuatatseng.com/), [Assistant Prof.Lizi Liao](https://liziliao.github.io/)
    
- *2020.10 - 2021.03*, Research Intern, Meituan, Beijing, China.
  - **Research Topic**: Cross-domain Recommender System
  - **Supervisor**: [Yafeng Zhang](https://scholar.google.com/citations?user=bMQ6vNwAAAAJ&hl=en), [Jinpeng Wang](https://joopoo.github.io/)

# 👍 Services

- **Journal Reviewer**:
  - IEEE Transactions on Pattern Analysis and Machine Intelligence (**TPAMI** A*)
  - IEEE Transactions on Knowledge and Data Engineering (**TKDE**, A*)
  - IEEE Transactions on Big Data (**TBD**, Q1)
  - IEEE Transactions on Artificial Intelligence (**TAI**)
  - IEEE Transactions on Mobile Computing (**TMC**, A*)
  - Knowledge-Based Systems (B)
  - Neurocomputing (B)
  - The Journal of Supercomputing (B)

- **Program Committee Member**:
  - The Web Conference (**WWW**, A*), 2024
  - ACM Multimedia (**ACM MM**, A*), 2024
  - ACL Rolling Review (**ACL ARR**, A*),2024
  - Annual Meeting of the Association for Computational Linguistics (**ACL**, A*), 2023-2024
  - Conference on Information and Knowledge Management (**CIKM**, A), 2024
  - Empirical Methods in Natural Language Processing (**EMNLP**, A*), 2022-2023
  - Natural Language Processing and Chinese Computing (**NLPCC**, CCF C), 2023

# 🌟 Miscellaneous

In my spare time, I enjoy reading, running, fitness, swimming, and hiking.

> "You can’t ever reach perfection, but you can believe in an asymptote toward which you are ceaselessly striving." – "When Breath Becomes Air" by *Paul Kalanithi*
