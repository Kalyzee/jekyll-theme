
Example config file

```
title: Gstreamer Webkit Plugin
email: ludovic.bouguerra@kalyzee.com
description: >
  Write an awesome description for your new site here. You can edit this
  line in _config.yml. It will appear in your document head meta (for
  Google search results) and in your feed.xml site description.
baseurl: "" # the subpath of your site, e.g. /blog

url: "https://kalyzee.github.io/gst-webkit/"

twitter_username: kalyzee
github_username:  kalyzee

# Build settings
markdown: kramdown

homepage:
  buttons:
    - title : 'Mac Installation'
      url   : 'mac-install.adoc'
    - title : 'Window Installation'
      url   : 'window-install.adoc'
    - title : 'Linux Installation'
      url   : 'linux-install.adoc'
doc:
  categories:
    - title: gst-webkit 1.0
      items:
        - title : 'Presentation'
          url   : '#presentation'
        - title : 'Installation'
          url   : '#installation'
        - title : 'Usage'
          url   : '#usage'


```

Theme homepage:

```
---
layout: homepage
title: Accueil documentation
---

The purpose of this documentation is to present vision of Kast v3 product. You also find what are possibilites to customise Kast. There are many ways to make your Kast OS unique and fully integrated with your business cases. The following picture shows you the architecture which gives you all customisations entrypoints.
```
