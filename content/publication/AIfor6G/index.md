---
title: "A Digital Twin for Reconfigurable Intelligent Surface Assisted Wireless Communication"
authors:
- Baoling Sheen
- Jin Yang
- Xianglong Feng
- Moin Chowdhury
date: "2020-10-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2020-10-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["3"]

# Publication name and optional abbreviated publication name.
publication: In *arXiv preprint*
publication_short: In * *

abstract: Reconfigurable Intelligent Surface (RIS) has emerged as one of the key technologies for 6G in recent years, which comprise a large number of low-cost passive elements that can smartly interact with the impinging electromagnetic waves for performance enhancement. However, optimally configuring massive number of RIS elements remains a challenge. In this paper, we present a novel digital-twin framework for RIS-assisted wireless networks which we name it Environment-Twin (Env-Twin). The goal of the Env-Twin framework is to enable automation of optimal control at various granularities. In this paper, we present one example of the EnvTwin models to learn the mapping function between the RIS configuration with measured attributes for the receiver location, and the corresponding achievable rate in an RISassisted wireless network without involving explicit channel estimation or beam training overhead. Once learned, our EnvTwin model can be used to predict optimal RIS configuration for any new receiver locations in the same wireless network. We leveraged deep learning (DL) techniques to build our model
and studied its performance and robustness. Simulation results demonstrate that the proposed Env-Twin model can recommend near-optimal RIS configurations for test receiver locations which achieved close to an upper bound performance that assumes perfect channel knowledge. Our Env-Twin model was trained using less than 2% of the total receiver locations. This promising result represents great potential of the proposed Env-Twin framework for developing a practical RIS solution where the panel can automatically configure itself without requesting channel state information (CSI) from the wireless network infrastructure.

# Summary. An optional shortened abstract.
summary: The goal of the Env-Twin framework is to enable automation of optimal control at various granularities.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
 # url: http://example.org
url_pdf: https://arxiv.org/ftp/arxiv/papers/2009/2009.00454.pdf
#url_code: '#'
#url_dataset: '#'
#url_poster: '#'
url_project: ''
#url_slides: ''
#url_source: '#'
#url_video: '#'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/pLCdAaMFLTE)'
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects:
- AIFor6G

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: example
---

{{% alert note %}}
Click the *Cite* button above to demo the feature to enable visitors to import publication metadata into their reference management software.
{{% /alert %}}

{{% alert note %}}
Click the *Slides* button above to demo Academic's Markdown slides feature.
{{% /alert %}}

Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).

