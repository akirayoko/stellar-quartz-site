---
# Homepage configuration
# Documentation: https://docs.hugoblox.com/tutorial/customizing-landing-page/

title: Home
type: landing

sections:
  - block: about.biography
    id: about
    content:
      user_groups:
        - me
  - block: collection
    id: publications
    content:
      title: Recent Publications
      filters:
        folders:
          - publication
        exclude_featured: false
    design:
      view: citation
  - block: contact
    id: contact
    content:
      title: Contact
      text: |-
        If you are interested in my research, please feel free to contact me.
      email: akira.yoko.c7@tohoku.ac.jp
      # フォームを有効にする場合は以下を設定
      form:
        provider: netlify
        formspree_id:
        netlify:
          captcha: false
---
