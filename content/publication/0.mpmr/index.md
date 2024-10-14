---
title: "MPMR: multi-scale feature and probability map for melanoma recognition"
authors:
- Dong Zhang
- hanhc
- Shaoyi Du
- Longfei Zhu
- Jing Yang
- Xijing Wang
- Lin Wang
- Meifeng Xu
author_notes:
- "Equal contribution"
- "Equal contribution"
- 
- 
- 
- 
- "Corresponding author"
- "Corresponding author"
date: "2022-01-05"
doi: "10.3389/fmed.2021.775587"

# Schedule page publish date (NOT publication's date).
publishDate: "2024-06-06"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: "*Frontiers in Medicine, 8*(775587)"
publication_short: "*Front. Med.*"

abstract: "Malignant melanoma (MM) recognition in whole-slide images (WSIs) is challenging due to the huge image size of billions of pixels and complex visual characteristics. We propose a novel automatic melanoma recognition method based on the multi-scale features and probability map, named MPMR. First, we introduce the idea of breaking up the WSI into patches to overcome the difficult-to-calculate problem of WSIs with huge sizes. Second, to obtain and visualize the recognition result of MM tissues in WSIs, a probability mapping method is proposed to generate the mask based on predicted categories, confidence probabilities, and location information of patches. Third, considering that the pathological features related to melanoma are at different scales, such as tissue, cell, and nucleus, and to enhance the representation of multi-scale features is important for melanoma recognition, we construct a multi-scale feature fusion architecture by additional branch paths and shortcut connections, which extracts the enriched lesion features from low-level features containing more detail information and high-level features containing more semantic information. Fourth, to improve the extraction feature of the irregular-shaped lesion and focus on essential features, we reconstructed the residual blocks by a deformable convolution and channel attention mechanism, which further reduces information redundancy and noisy features. The experimental results demonstrate that the proposed method outperforms the compared algorithms, and it has a potential for practical applications in clinical diagnosis."
# Summary. An optional shortened abstract.
summary: "We propose a novel automatic melanoma recognition method based on the multi-scale features and probability map."

tags:
- [Medical image analysis]
featured: True

# links:
# - name: ""
#   url: ""
url_pdf: 
url_code: 
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://www.sciencedirect.com/science/article/abs/pii/S0031320322007269'
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---



{{% callout note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /callout %}}

{{% callout note %}}
Create your slides in Markdown - click the *Slides* button to check out the example.
{{% /callout %}}

Add the publication's **full text** or **supplementary notes** here. You can use rich formatting such as including [code, math, and images](https://docs.hugoblox.com/content/writing-markdown-latex/).
