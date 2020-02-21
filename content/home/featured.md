+++
# A Demo section created with the Blank widget.
# Any elements can be added in the body: https://sourcethemes.com/academic/docs/writing-markdown-latex/
# Add more sections by duplicating this file and customizing to your requirements.

widget = "blank"  # See https://sourcethemes.com/academic/docs/page-builder/
headless = true  # This file represents a page section.
active = true  # Activate this widget? true/false
weight = 40  # Order that this section will appear.


title = "Publications"
subtitle = ""

[design]
  # Choose how many columns the section has. Valid values: 1 or 2.
  columns = "1"

[design.background]
  # Apply a background color, gradient, or image.
  #   Uncomment (by removing `#`) an option to apply it.
  #   Choose a light or dark text color by setting `text_color_light`.
  #   Any HTML color name or Hex value is valid.

  # Background color.
  # color = "navy"
  
  # Background gradient.
  # gradient_start = "DeepSkyBlue"
  # gradient_end = "SkyBlue"
  
  # Background image.
  #image = "headers/bubbles-wide.jpg"  # Name of image in `static/img/`.
  #image_darken = 0.6  # Darken the image? Range 0-1 where 0 is transparent and 1 is opaque.
  #image_size = "cover"  #  Options are `cover` (default), `contain`, or `actual` size.
  #image_position = "center"  # Options include `left`, `center` (default), or `right`.
  #image_parallax = true  # Use a fun parallax-like fixed background effect? true/false

  # Text color (true=light or false=dark).
  #text_color_light = true

[design.spacing]
  # Customize the section spacing. Order is top, right, bottom, left.
 padding = ["20px", "10%", "20px", "9%"]

[advanced]
 # Custom CSS. 
 css_style = "custom.scss"
 
 # CSS class.
 css_class = "home-section wg-about   "
+++

<font size=4>
<ul>
  <br>  
  <li><details>
    <summary><font color="#0000FF"> Fair Division of Mixed Divisible and Indivisible Goods </font>
      <br>
      joint work with Xiaohui Bei, Zihao Li, Shengxin Liu and Xinhang Lu
      <br>
      <b>AAAI Conference on Artificial Intelligence (AAAI), 2020</b> &nbsp;   <a href="https://arxiv.org/pdf/1911.07048.pdf">[PDF]</a>
      <br>
      <font color="#fa6400"><strong>Outstanding Student Paper Award</strong></font>
    </summary>
    <br>
    <div class="abs1" align=left>
      <p style = "margin:10px"><font size=3.5><b>Abstract:</b><br>         
        We study the problem of fair division when the resources contain both divisible and indivisible goods. Classic fairness notions such as envy-freeness (EF) and envy-freeness up to one good (EF1) cannot be directly applied to the mixed goods setting. In this work, we propose a new fairness notion <I>Envy-freeness for mixed goods</I> (EFM), which is a direct generalization of both EF and EF1 to the mixed goods setting. We prove that an EFM allocation always exists for any number of agents. We also propose efficient algorithms to compute an EFM allocation for two agents and for $n$ agents with piecewise linear valuations over the divisible goods. Finally, we relax the envy-free requirement, instead asking for $\epsilon$-<I>Envy-freeness for mixed goods</I> ($\epsilon$-EFM), and present an algorithm that finds an $\epsilon$-EFM allocation in time polynomial in the number of agents, number of goods, and $\frac{1}{\epsilon}$.
      </font></p>
    </div>
  </details></li>
  
  <br>

  <li><details>
    <summary><font color="#0000FF"> Privacy-preserving Crowd-guided AI Decision-making in Ethical Dilemmas </font>
      <br>
      joint work with Teng Wang, Jun Zhao, Han Yu, Xinyu Yang, Xuebing Ren and Shuyu Shi
      <br>
      <b>The 28th ACM International Conference on Information and Knowledge Management (CIKM), 2019</b> &nbsp;  <a href="https://dl.acm.org/doi/abs/10.1145/3357384.3357954">[PDF]</a>
    </summary>
    <div class="abs1" align=left>
      <p style = "margin:10px"><font size=3.5><b>Abstract:</b><br>         
        With the rapid development of artificial intelligence (AI), ethical issues surrounding AI have attracted increasing attention. To investigate such ethical dilemmas, recent studies have adopted preference aggregation, such approaches can potentially violate the privacy of voters. In this paper, we report a first-of-its-kind privacy- preserving crowd-guided AI decision-making approach in ethical dilemmas. We adopt the formal and popular notion of differential privacy and propose different algorithms to achieve these privacy protection granularities. Extensive experiments based on both synthetic data and real-world data of voters’ moral decisions demonstrate that the proposed approaches achieve high accuracy of preference aggregation while protecting individual voter’s privacy.
      </font></p>
    </div>
  </details></li>

  <br>

  <li><details>
    <summary><font color="#0000FF"> Learning Optimal Reserve Price against Non-myopic Bidderss </font>
      <br>
      joint work with Zhiyi Huang and Xiangning Wang 
      <br>
      <b>Advances in Neural Information Processing Systems(NeurIPS), 2018</b> &nbsp;   <a href="http://papers.nips.cc/paper/7474-learning-optimal-reserve-price-against-non-myopic-bidders.pdf">[PDF]</a>
    </summary>
    <div class="abs1" align=left>
      <p style = "margin:10px"><font size=3.5><b>Abstract:</b><br>         
        We consider the problem of learning optimal reserve price in repeated auctions against non-myopic bidders, who may bid strategically in order to gain in future rounds even if the single-round auctions are truthful. Previous algorithms, e.g., empirical pricing, do not provide non-trivial regret rounds in this setting in general. We introduce algorithms that obtain small regret against non-myopic bidders either when the market is large, i.e., no bidder appears in a constant fraction of the rounds, or when the bidders are impatient, i.e., they discount future utility by some factor mildly bounded away from one. Our approach carefully controls what information is revealed to each bidder, and builds on techniques from differentially private online learning as well as the recent line of works on jointly differentially private algorithms.
      </font></p>
    </div>
  </details></li>

  <br>

  <li><details>
    <summary><font color="#0000FF"> Optimal Differentially Private Algorithms for k-Means Clustering </font>
      <br>
      joint work with Zhiyi Huang
      <br>
      <b>In Proceeding of the ACM SIGMOD-SIGACT-SIGAI Symposium on Principles of Databases Systems (PODS), 2018</b> &nbsp;  <a href="https://dl.acm.org/doi/abs/10.1145/3196959.3196977">[PDF]</a>
    </summary>
    <div class="abs1" align=left>
      <p style = "margin:10px"><font size=3.5><b>Abstract:</b><br>         
        We consider privacy-preserving $k$-means clustering. For the objective of minimizing the Wasserstein distance between the output and the optimal solution, we show that there is a polynomial-time $(\epsilon,\delta)$-differentially private algorithm which, for any sufficiently large $\phi^2$ well-separated datasets, outputs $k$ centers that are within Wasserstein distance $O( \phi^2)$ from the optimal. This result improves the previous bounds by removing the dependence on $\epsilon$, number of centers $k$, and dimension $d$. Further, we prove a matching lower bound that no $(\epsilon, \delta)$-differentially private algorithm can guarantee Wasserstein distance less than $\Omega (\phi^2)$ and, thus, our positive result is optimal up to a constant factor. For minimizing the $k$-means objective when the dimension $d$ is bounded, we propose a polynomial-time private local search algorithm that outputs an $\alpha n$-additive approximation when the size of the dataset is at least.      
      </font></p>
    </div>
  </details></li>

</ul>
</font>

