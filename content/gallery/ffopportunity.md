---
weight: 4
title: "ffopportunity"
subtitle: "Expected Fantasy Points"
image: "ffopp_square.png"
imageheader: "ffopp_inverse.png"
alt: "ffopportunity logo"
color: "#333333"
type: github
github: 
  repo: "ffverse/ffopportunity"
  showInfo: true
  showButtons: false
buttons:
  - i18n: docs
    url: "https://ffopportunity.ffverse.com"
  - i18n: github 
    url: "https://github.com/ffopportunity/ffscrapr/"
---

Expected Fantasy Points are a measure of player opportunities in fantasy football - essentially aiming to quantify how many points the average player would score given a specific situation and passing/rushing/receiving attempt.

ffopportunity builds a dataframe of Expected Fantasy Points by preprocessing and applying an xgboost model to nflverse play-by-play data. It also includes utilities to download precomputed data from automated GitHub releases.
