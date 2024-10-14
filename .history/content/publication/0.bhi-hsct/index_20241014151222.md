---
title: 'HSC-T: B-ultrasound-to-elastography Translation via Hierarchical Structural Consistency Learning for Thyroid Cancer Diagnosis'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - hanhc
  - Zhiqiang Tian
  - Qinbo Guo
  - Jue Jiang
  - Shaoyi Du*
  - Juan Wang*

# Author notes (optional)
author_notes:
  - 
  - 
  - 
  - 
  - 'Corresponding author'
  - 'Corresponding author'

date: '2024-10-09'
doi: '10.1109/ITSC57777.2023.10421891'

# Schedule page publish date (NOT publication's date).
publishDate: '2024-10-13'

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ['paper-conference']

# Publication name and optional abbreviated publication name.
publication: In *IEEE-EMBS International Conference on Biomedical and Health Informatic (BHI)*
publication_short: In *BHI 2024*

abstract: Elastography ultrasound imaging is increasingly important in the diagnosis of thyroid cancer and other diseases, but its reliance on specialized equipment and techniques limits widespread adoption. This paper proposes a novel multimodal ultrasound diagnostic pipeline that expands the application of elastography ultrasound by translating B-ultrasound (BUS) images into elastography images (EUS). Additionally, to address the limitations of existing image-to-image translation methods, which struggle to effectively model inter-sample variations and accurately capture regional-scale structural consistency, we propose a BUS-to-EUS translation method based on hierarchical structural consistency. By incorporating domain-level, sample-level, patch-level, and pixel-level constraints, our approach guides the model in learning a more precise mapping from BUS to EUS, thereby enhancing diagnostic accuracy. Experimental results demonstrate that the proposed method significantly improves the accuracy of BUS-to-EUS translation on the MTUSI dataset and that the generated elastography images enhance nodule diagnostic accuracy compared to solely using BUS images on the STUSI and the BUSI datasets. This advancement highlights the potential for broader application of elastography in clinical practice.

# Summary. An optional shortened abstract.
summary: Translating B-ultrsound to Elastography through hierarchical structural consistency learning.

tags: [Medical image translation, Elastography ultrasound, Hierarchical structural consistency]

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 
url_code: 'https://github.com/HongchengHan/HSC-T'
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: 'https://openreview.net/forum?id=EwSohBIcje'
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


