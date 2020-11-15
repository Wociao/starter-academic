---
title: "Runtime Fault Injection Detection for FPGA-based DNN Execution Using Siamese Path Verification"
authors:
- Xianglong Feng
- Mengmei Ye
- Ke Xia
- Sheng Wei
date: "2021-02-01"
doi: ""

# Schedule page publish date (NOT publication's date).
#publishDate: "2017-01-01T00:00:00Z"

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: In *Design, Automation and Test in Europe *
#publication_short: In *DATE*



# Summary. An optional shortened abstract.

Deep neural networks (DNNs) have been widely deployed on FPGAs to achieve superior performance, power efficiency, and design flexibility. However, the FPGA-based DNNs are vulnerable to fault injection attacks that aim to compromise the original functionality. To defend against such attacks, the existing methods either duplicate the models and check the consistency of the results at runtime, or strengthen the robustness of the models by adding additional neurons. However, these existing methods could introduce huge processing overhead or require re-training the models. In this paper, we develop a runtime verification method, namely Siamese path verification (SPV), to check the integrity of the DNN models running on FPGAs. By leveraging the computing features of the DNN and carefully designing the weight parameters, we add neurons to check the integrity of the model without impacting the original functionality and, therefore, no re-training of the model is required. We implement the proposed SPV approach on Xilinx Virtex-7 FPGA and evaluate it using the MNIST dataset. The evaluation results show that SPV has superior efficiency with small processing overhead.

tags:
- Source Themes
featured: true

links:
#- name: Custom Link
#  url: http://example.org
#url_pdf: https://dl.acm.org/doi/pdf/10.1145/3328914
#url_code: 'https://github.com/hwsel/LiveMotion'


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
- Security

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

