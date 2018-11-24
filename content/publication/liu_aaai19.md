+++
abstract = "We focus on empirical risk minimization with a composite
regulariser, which has been widely applied in various ma-
chine learning tasks to introduce important structural infor-
mation regarding the problem or data. In general, it is chal-
lenging to calculate the proximal operator with the composite
regulariser. Recently, proximal average (PA) which involves a
feasible proximal operator calculation is proposed to approx-
imate composite regularisers. Augmented with the prevail-
ing variance reducing (VR) stochastic methods (e.g. SVRG,
SAGA), PA based algorithms would achieve a better per-
formance. However, existing works require a fixed stepsize,
which needs to be rather small to ensure that the PA approx-
imation is sufficiently accurate. In the meantime, the smaller
stepsize would incur many more iterations for convergence.
In this paper, we propose two fast PA based VR stochas-
tic methods – APA-SVRG and APA-SAGA. By initializing
the stepsize with a much larger value and adaptively decreas-
ing it, both of the proposed methods are proved to enjoy the
$O(n \log \frac{1}{\epsilon} + m_{0} \frac{1}{\epsilon})$ iteration complexity to achieve the ε- εε
accurate solutions, where m0 is the initial number of inner iterations and n is the number of samples. Moreover, exper- imental results demonstrate the superiority of the proposed algorithms."
abstract_short = ""
authors = ["Jingchang Liu", "Linli Xu", "**Junliang Guo**", "Xin Sheng"]
date = "2019-01-27"
image_preview = ""
math = true
publication_types = ["1"]
publication = "*Thirty-Third AAAI Conference on Artificial Intelligence  (AAAI 2019)*"
publication_short = "*AAAI 2019 (to appear)*"
selected = true
title = "Adaptive Proximal Average based Variance Reducing Stochastic Methods for Optimization with Composite Regularization"
#url_code = "https://github.com/zhuohan123/g2-lstm"
# url_dataset = "#"
#url_pdf = "pdf/g2-lstm-icml18.pdf"
# url_project = "project/deep-learning/"
# url_slides = "#"
# url_video = "#"

<!-- [[url_custom]]
name = "arXiv"
url = "https://arxiv.org/abs/1806.02988"

[[url_custom]]
name = "Blog Post (Chinese)"
url = "https://mp.weixin.qq.com/s?__biz=MzAwMTA3MzM4Nw==&mid=2649443972&idx=1&sn=9c73d0e3afd003031905457fb3e33bc4&chksm=82c0a700b5b72e166ebd0884ec36a9ceaff9e5254c2c2b586e9f9b9ea4577a0337d1a5bde34f&scene=21#wechat_redirect" -->

# Optional featured image (relative to `static/img/` folder).
<!-- [header]
image = "headers/bubbles-wide.jpg" -->
# caption = "My caption :smile:"

+++
