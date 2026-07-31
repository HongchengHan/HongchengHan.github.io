---
# Leave the homepage title empty to use the site title
title: 'HAN Hongcheng'
summary: 'Personal Homepage'
date: 2026-06-13
type: landing

sections:
  - block: resume-biography-3
    content:
      # Choose a user profile to display (a folder name within `content/authors/`)
      username: hanhc
      text: ''
      # Show a call-to-action button under your biography? (optional)
      button:
        text: Download CV
        url: uploads/CV_Hongcheng_Han.pdf
      headings:
        about: ''
        education: ''
        interests: ''
    design:
      # Use the new Gradient Mesh which automatically adapts to the selected theme colors
      background:
        gradient_mesh:
          enable: true

      # Name heading sizing to accommodate long or short names
      name:
        size: md # Options: xs, sm, md, lg (default), xl

      # Avatar customization
      avatar:
        size: medium # Options: small (150px), medium (200px, default), large (320px), xl (400px), xxl (500px)
        shape: circle # Options: circle (default), square, rounded
  - block: markdown
    content:
      title: '� Google Scholar Metrics'
      subtitle: 'Citation impact at a glance'
      text: |-
        <div style="display:grid; gap:1rem; grid-template-columns:repeat(auto-fit,minmax(140px,1fr)); margin:1rem 0;">
          <div style="border:1px solid rgba(127,127,127,0.2); border-radius:1rem; padding:1rem 1.1rem; background:linear-gradient(135deg, rgba(59,130,246,0.08), rgba(16,185,129,0.08));">
            <div style="font-size:0.8rem; opacity:0.75; text-transform:uppercase; letter-spacing:0.08em;">Citations</div>
            <div style="font-size:2rem; font-weight:700; margin-top:0.25rem;">137</div>
          </div>
          <div style="border:1px solid rgba(127,127,127,0.2); border-radius:1rem; padding:1rem 1.1rem; background:rgba(255,255,255,0.04);">
            <div style="font-size:0.8rem; opacity:0.75; text-transform:uppercase; letter-spacing:0.08em;">h-index</div>
            <div style="font-size:2rem; font-weight:700; margin-top:0.25rem;">5</div>
          </div>
          <div style="border:1px solid rgba(127,127,127,0.2); border-radius:1rem; padding:1rem 1.1rem; background:rgba(255,255,255,0.04);">
            <div style="font-size:0.8rem; opacity:0.75; text-transform:uppercase; letter-spacing:0.08em;">i10-index</div>
            <div style="font-size:2rem; font-weight:700; margin-top:0.25rem;">1</div>
          </div>
        </div>
        <p style="margin-top:0.5rem;"><a href="https://scholar.google.com/citations?user=KhaN2PgAAAAJ&hl=zh-CN" target="_blank" rel="noopener noreferrer">View full profile on Google Scholar →</a></p>
    design:
      columns: '1'
  - block: markdown
    content:
      title: '�📚 My Research'
      subtitle: ''
      text: |-
        My research focuses on AI-driven medical image analysis, including medical image segmentation, multimodal fusion diagnosis, and cross-modal generation. Currently, I am dedicated to developing a visual foundation model for multimodal ultrasound imaging. This model is designed to support diverse modalities such as B-mode ultrasound, elastography, color Doppler ultrasound, and contrast-enhanced ultrasound, enabling diagnostic assistance for multiple diseases including thyroid and breast conditions.
    design:
      columns: '1'
  - block: collection
    id: papers
    content:
      title: Featured Publications
      filters:
        folders:
          - publications
        featured_only: true
    design:
      view: article-grid
      columns: 3
  - block: collection
    content:
      title: Recent Publications
      text: ''
      filters:
        folders:
          - publications
        exclude_featured: false
      count: 8
    design:
      view: citation
  - block: resume-awards
    id: competitions
    content:
      title: Competitions
      text: 'Competition Awards in Science and Technology'
      username: hanhc
  - block: markdown
    id: patents
    content:
      title: Patents
      subtitle: 'Granted Invention Patents'
      text: |-
        - "杜少毅, **韩泓丞**, 李胜鹏, 刘宇颖, 张栋, 郭钦钵, 王明豪, 田智强. 一种车辆驾驶意图识别方法及系统: 中国, ZL202511126984.2. 申请日: 2025.08.13. 公告日: 2025.10.31."
        - "杜少毅, **韩泓丞**, 王明豪, 郭钦钵, 张栋, 李冰洁, 王娟. 一种基于跨模态时空联合学习的多模态视频目标识别方法: 中国, ZL202510679690.6. 申请日: 2025.05.26. 公告日: 2025.08.22."
        - "杜少毅, **韩泓丞**, 张栋, 王娟, 郭钦钵, 田智强, 姜珏. 一种基于多层级一致性的虚拟模态成像计算方法: 中国, ZL202410887089.1. 申请日: 2024.07.03. 公告日: 2025.08.01."

        [See all patents](patents/)
  # - block: collection
  #   id: talks
  #   content:
  #     title: Recent & Upcoming Talks
  #     filters:
  #       folders:
  #         - events
  #   design:
  #     view: card
  # - block: collection
  #   id: news
  #   content:
  #     title: Recent News
  #     subtitle: ''
  #     text: ''
  #     # Page type to display. E.g. post, talk, publication...
  #     page_type: blog
  #     # Choose how many pages you would like to display (0 = all pages)
  #     count: 10
  #     # Filter on criteria
  #     filters:
  #       author: ''
  #       category: ''
  #       tag: ''
  #       exclude_featured: false
  #       exclude_future: false
  #       exclude_past: false
  #       publication_type: ''
  #     # Choose how many pages you would like to offset by
  #     offset: 0
  #     # Page order: descending (desc) or ascending (asc) date.
  #     order: desc
  #   design:
  #     # Choose a layout view
  #     view: card
  #     # Reduce spacing
  #     spacing:
  #       padding: [0, 0, 0, 0]
  # - block: cta-card
  #   demo: true # Only display this section in the HugoBlox Kit demo site
  #   content:
  #     title: 👉 Build your own academic website like this
  #     text: |-
  #       This site is generated by HugoBlox Kit - the FREE, Hugo-based open source website builder trusted by 250,000+ academics like you.

  #       <a class="github-button" href="https://github.com/HugoBlox/kit" data-color-scheme="no-preference: light; light: light; dark: dark;" data-icon="octicon-star" data-size="large" data-show-count="true" aria-label="Star HugoBlox/kit on GitHub">Star</a>

  #       Easily build anything with blocks - no-code required!

  #       From landing pages, second brains, and courses to academic resumés, conferences, and tech blogs.
  #     button:
  #       text: Get Started
  #       url: https://hugoblox.com/templates/
  #   design:
  #     card:
  #       # Card background color (CSS class)
  #       css_class: 'bg-gradient-to-br from-primary-500 via-primary-600 to-secondary-600 text-white shadow-2xl'
  #       css_style: ''
---
