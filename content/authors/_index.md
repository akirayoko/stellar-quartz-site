---
# Author list page configuration
# Documentation: https://docs.hugoblox.com/reference/content-types/

title: Authors

view: compact

# 著者一覧ページ自体をレンダリングしない設定
build:
  render: never

# 配下の個別プロフィール（me.yaml等）の設定を継承
cascade:
  build:
    render: always
    list: local
---
