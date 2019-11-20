+++
abstract = "Non-autoregressive translation (NAT) models remove the dependence on previous target tokens and generate all target tokens in parallel, resulting in significant inference speedup but at the cost of inferior translation accuracy compared to autoregressive translation (AT) models. Considering that AT models have higher accuracy and are easier to train than NAT models, and both of them share the same model configurations, a natural idea to improve the accuracy of NAT models is to transfer a well-trained AT model to an NAT model through fine-tuning. However, since AT and NAT models differ greatly in training strategy, straightforward fine-tuning does not work well. In this work, we introduce curriculum learning into fine-tuning for NAT. Specifically, we design a curriculum in the fine-tuning process to progressively switch the training from autoregressive generation to non-autoregressive generation. Experiments on four benchmark translation datasets show that the proposed method achieves good improvement (more than $1$ BLEU score) over previous NAT baselines in terms of translation accuracy, and greatly speed up (more than $10$ times) the inference process over AT baselines."
abstract_short = ""
authors = ["**Junliang Guo**", "Xu Tan", "Linli Xu", "Tao Qin", "Enhong Chen", "Tie-Yan Liu"]
date = "2019-11-23"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*AAAI 2020*"
publication_short = "*AAAI 2020*"
selected = true
title = "Fine-Tuning by Curriculum Learning for Non-Autoregressive Neural Machine Translation"
#url_code = "https://github.com/zhuohan123/g2-lstm"
# url_dataset = "#"
# url_pdf = "pdf/ENAT_camera[gjl][AddRef].pdf"
# url_project = "project/deep-learning/"
# url_slides = "pdf/aaai19_pre.pdf"
# url_video = "#"

#<!-- [[url_custom]]
#name = "arXiv"
#url = "https://arxiv.org/abs/1806.02988"

# Optional featured image (relative to `static/img/` folder).
#<!-- [header]
#image = "headers/bubbles-wide.jpg" -->
# caption = "My caption :smile:"

+++
