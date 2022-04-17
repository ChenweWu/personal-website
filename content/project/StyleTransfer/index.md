---
title: Unsupervised lyrics style transfer
summary: While interest in text style transfer has grown in recent years, little work has addressed its potential applications to music. In this paper, we investigate an intriguing question: what would a lyric from a Taylor Swift song look like if it were written by Drake? And what would a Drake verse look like if it were penned by Taylor Swift? This problem is challenging, as both artist have distinct styles and there is no set of parallel corpora to translate between the two. Our work uses unsupervised text style transfer to address this problem and translates each artist’s lyrics into the other’s style. We consider a variety of approaches from recent literature that combine a sequence-to-sequence autoencoder (with or without attention) with either a classifier or discriminator. We evaluate these models on fluency, content preservation, and style, and find that a simple model that uses a non-attention autoencoder and an adversarial discriminator achieves the best results.
tags:
- NLP
date: "2016-04-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: "https://github.com/ChenweWu/lyrics-style-transfer"


links:
- icon: file-powerpoint
  icon_pack: fas
  name: Slides
  url: https://docs.google.com/presentation/d/1N74jDwBnn5pFzSHiI0ksrJE09a3h2z7FSyobjQ4gxz4/edit?usp=sharing
  
- icon: github-alt
  icon_pack: fab
  name: Code
  url: https://github.com/ChenweWu/lyrics-style-transfer
  
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides: ""
---


