---
title: 'Coarse-to-fine feature representation based on deformable partition attention for melanoma identification'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Dong Zhang
  - Jing Yang
  - Shaoyi Du*
  - hanhc
  - Yuyan Ge
  - Longfei Zhu
  - Ce Li
  - Meifeng Xu
  - Nanning Zheng*

# Author notes (optional)
author_notes:
  - 
  - 
  - 'Corresponding author'
  - 
  - 
  - 
  - 
  - 
  - 'Corresponding author'
  - 

date: '2023-04-01'
doi: '10.1016/j.patcog.2022.109247'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-06-06'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Pattern Recognition, 136*(109247)"
publication_short: "*Pattern Recognition*"

abstract: In the histopathological melanoma image diagnosis system, manual identification of super-scale slides with dense cells is tedious, time-consuming, and subjective. To deal with this problem, we propose an automatic identification network based on the deformable partition attention to identify lots of dense slides as an assistant. A coarse-to-fine strategy is adopted in feature representation and qualitative identification to improve the identification accuracy of melanomas and nevi. First of all, because it is difficult to extract features in the lesion area with blurred boundaries and uneven distribution, we develop a deformable partition attention module, which integrates the advantage of the attention mechanism and deformable convolution. The module overcomes the limitation of rectangular convolution and gradually refines the channel and spatial features, which enriches feature representation by combining global and local features. Secondly, to address the problem of difficult convergence and poor recognition rate caused by the excessive non-aligned distance between benign-malignant and benign subcategories, we propose a progressive architecture via a coarse sub-network closely followed by a fine sub-network. Moreover, to further increase the inter-class differences and reduce the intra-class disparities, we propose a joint loss function to mine hard samples, which effectively improves the identification performance. Experimental results on the clinical dataset show that the proposed algorithm has higher sensitivity and specificity and outperforms state-of-the-art deep neural networks.

# Summary. An optional shortened abstract.
summary: We propose a novel and efficient coarse-to-fine neural network for melanomas and nevi identification, which adopt a divide and conquer idea to overcome unbalanced inter-class spacing, and then leverages a fine sub-network to tackle the challenges of arduous training and unfavorable classification accuracy.

tags: [Medical image analysis]

# Display this page in the Featured widget?
featured: False

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: ''
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/abs/pii/S0031320322007269'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---



{{% callout note %}}
Click the _Cite_ button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the _Slides_ button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).


