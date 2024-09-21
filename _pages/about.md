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

My name is Yuxia Wu, a research scientist at [Singapore Management University (SMU)](https://www.smu.edu.sg/), supervised by [Assistant Prof. Yuan Fang](https://www.yfang.site/home). Before that, I obtained my Ph.D. degree in the area of *Computer Science* at [SMILES lab](http://www.smiles-xjtu.com/), Xi'an Jiaotong University, advised by [Prof. Xueming Qian](https://gr.xjtu.edu.cn/web/qianxm). I also hold a Master's and Bachelor's degrees in *Biomedical Engineering* from Airforce Medical University and Zhengzhou University.

**Research interests:** <a href='https://scholar.google.com/citations?user=bRgptuYAAAAJ&hl=en'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>

- **Graph mining**: dynamic graph modeling, LLM for graphs
- **Recommendation systems**: conversational recommendation, sequential recommendation, generative AI for recommendations
- **NLP**: task-oriented dialog system, new class discovery
- **Medical image processing**:  computer-aided diagnosis, neuroscience
- **AI for science**: LLM for molecular generation

I am interested in conducting interdisciplinary research and am open to collaborations with academic and industry partners in my research areas. If you are interested in working together, please feel free to contact me.

> "Imagination is more important than knowledge. For knowledge is limited, whereas imagination embraces the entire world, stimulating progress, giving birth to evolution." – Albert Einstein

# 🔥 News

- **[09/2024]**: Two papers are accepted by EMNLP'24. Congratulations to Yimin and Jinggui!
- **[05/2024]**: Check out our Tutorials "Towards Graph Foundation Models" ([Part I](/my_papers/2024.05_WWW24Tutorial_GFM_Part1.pdf), [Part II](/my_papers/2024.05_WWW24Tutorial_GFM_Part2.pdf) & [Part III](/my_papers/2024.05_WWW24Tutorial_GFM_Part3.pdf)) at WWW'24.
- **[03/2024]**: Our paper about [new slot discovery](/my_papers/Active_Discovering_New_Slots_for_Task_oriented_Conversation.pdf) is accepted by IEEE/ACM Transactions on Audio, Speech, and Language Processing (TASLP).
- **[02/2024]**: Our paper about [simple Transformer for dynamic graph modeling](https://dl.acm.org/doi/pdf/10.1145/3589334.3645622) is accepted by WWW'24.
- **[11/2023]**: Our paper about [Reason generation for POI recommendation](/my_papers/Reason Generation for Point of Interest Recommendation via a Hierarchical Attention-based Transformer Model.pdf) is accepted by IEEE Transactions on Multimedia (TMM).
- **[05/2023]**: I started the Postdoc position at Singapore Management University.

# 📝 Research [[Google Scholar](https://scholar.google.com/citations?user=bRgptuYAAAAJ)]

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
 
[![CODE](https://img.shields.io/badge/CODE-blue)](https://github.com/yieshah/PLSPL) <span style="color:red">(ESI Highly Cited Paper, Citations: 160+)</span>

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

# 🌟 Teaching
- SSS606 Social Analytics and Applications, Singapore Management University, Guest Lecturer, 2024
- COMP 701 Nature Inspired Computing, Auckland University of Technology, Guest Lecturer, 2024
- Top-conference Paper Analysis, Beijing, Lecturer, 2022
- Deep Learning Algorithm, Beijing, Teaching Assistant, 2018 - 2020
- Video Processing and Communications, Xi'an Jiaotong University, Teaching Assistant, 2018 

# 🎓 Education
- *2017.09 - 2023.03*,	Ph.D. in Information and Communication Engineering, Xi'an Jiaotong University, Shaanxi, China.
- *2014.09 - 2017.07*,	Master of Engineering in Biomedical Engineering, Air Force Medical University, Shaanxi, China.
- *2010.09 - 2014.07*,	Bachelor of Engineering in Biomedical Engineering, Zhengzhou University, Henan, China

# 🍀 Experience
- *2023.05 - now*, Research Scientist, Singapore Management University.  
- *2021.03 - 2022.10*, Research Intern, NExT++ Research Center, National University of Singapore.    
- *2020.10 - 2021.03*, Research Intern, Meituan, Beijing, China.

# 👍 Service
- **Area Chair**: AJCAI 2024
- **Reviewer/PC Member**: WWW, MM, ACL ARR, ACL, CIKM, EMNLP, NLPCC, TPAMI, TKDE, TBD, TAI, TMC, Knowledge-Based Systems, Neurocomputing, The Journal of Supercomputing

> "You can’t ever reach perfection, but you can believe in an asymptote toward which you are ceaselessly striving." – "When Breath Becomes Air" by *Paul Kalanithi*
