---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: home
---
{% if site.google_scholar_stats_use_cdn %}
{% assign gsDataBaseUrl = "https://cdn.jsdelivr.net/gh/" | append: site.repository | append: "@" %}
{% else %}
{% assign gsDataBaseUrl = "https://raw.githubusercontent.com/" | append: site.repository | append: "/" %}
{% endif %}
{% assign url = gsDataBaseUrl | append: "google-scholar-stats/gs_data_shieldsio.json" %}

<span class='anchor' id='about-me'></span>

I am currently pursuing a master's degree in computer science at East China Normal University and I graduated from the School of Computer Science and Technology, Huaqiao University with a bachelor's degree. 

My research interests include bioinformatics, ai for science, graph neural network and generative models. I have published several papers in conferences and journals 
<a href='https://scholar.google.com/citations?user=vcIXSBMAAAAJ'><img src="https://img.shields.io/endpoint?url={{ url | url_encode }}&logo=Google%20Scholar&labelColor=f6f6f6&color=9cf&style=flat&label=citations"></a>.

# 📝 Publications 

- <code class="language-plaintext highlighter-rouge">ICIC 2024</code> [DP-DCAN: Differentially Private Deep Contrastive Autoencoder Network for Single-cell Clustering](https://arxiv.org/pdf/2311.03410).
**Huifa Li**, Jie Fu, Zhili Chen, Xiaomin Yang, Haitao Liu, Xinpeng Ling

- Multi-Scale Graph Contrastive Learning for Clustering Single-Cell RNA-Seq.
**Huifa Li**, Jie Fu, Xinpeng Ling, Tong Cheng, Zhili Chen, Junqing Gong.

- `BIBM 2024` [Single-cell Curriculum Learning-based Deep Graph Embedding Clustering](https://arxiv.org/pdf/2408.10511).
**Huifa Li**, Jie Fu, Xinpeng Ling, Zhiyu Sun, Kuncan Wang, Zhili Chen

- [FedFDP: Federated Learning with Fairness and Differential Privacy](https://arxiv.org/pdf/2402.16028).
Xinpeng Ling, Jie Fu, Kuncan Wang, **Huifa Li**, Tong Cheng, Zhili Chen

- EC-LDA: Embedding Compression-Label Distribution Inference Attack against Federated Graph Learning.
Tong Cheng, Jie Fu, Xinpeng Ling, Zhili Chen, **Huifa Li**, Wendy Hui Wang, Junqing Gong

- CBNN: 3-Party Secure Framework for Customized Binary Neural Networks Inference.
Benchang Dong, Zhili Chen, Junqing Gong, Xin Chen, Jie Fu, **Huifa Li**, Shiwen Wei

# 📖 Educations
- *2022.09 - 2024.08 (now)*, Master, East China Normal University, Shanghai. 
- *2018.09 - 2022.06*, Undergraduate, Huaqiao University, Xiamen.

# 🎖 Honors and Awards
- *2021.06* First Prize in Fujian Province, China Undergraduate Mathematical Contest in Modeling. 
- *2020.12* Merit Student of Huaqiao University. 
- *2020.11* First Prize in Fujian Province, Blue Bridge Cup National Software and Information Technology Professional Talent Competition. 