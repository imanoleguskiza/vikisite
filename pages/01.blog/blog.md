---
title: Home
body_classes: 'header-image fullwidth'
admin:
    children_display_order: collection
blog_url: blog
sitemap:
    changefreq: monthly
    priority: 1.03
content:
    items: '@self.children'
    order:
        by: date
        dir: desc
    limit: 5
    pagination: true
feed:
    description: 'Sample Blog Description'
    limit: 10
pagination: true
---

