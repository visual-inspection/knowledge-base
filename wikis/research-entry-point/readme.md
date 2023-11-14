# Visual Inspection: Research Entry Point

- [<span class="toc-section-number">1</span> About](#about)
- [<span class="toc-section-number">2</span> Directory](#directory)
- [References](#references)

This document was rendered 2023/11/14 at 13:04:32.

# About

The purpose of this document is supposed to be a kind of one-page Wiki.
It shall serve as the **entry-point** for people joining the project, as
well as a **reference** for what is going on in the project (e.g., what
approaches we are working on).

**\*Do not\* directly edit the file `readme.md` as your changes would be
<u>lost</u>!**

Instead, use [**`Quarto`**](https://quarto.org/) to render this file
([`readme.`**`qmd`**](./readme.qmd)) to markdown like this:

``` script
quarto render readme.qmd --to gfm
```

This will properly render and format the references (which can be found
in [`../references.bib`](../references.bib)). If you have not installed
the extension **`citetools`**, do so:

``` script
quarto install extension bcdavasconcelos/citetools
```

# Directory

Here is a directory of approaches that we either attempted, plan to
attempt, or are just listed as food-for-thought.

- **`General`**
  - Data Pre-processing and -Augmentation
    - Image Segmentation
    - Defect Localization
    - Data Augmentation
      - Gaussian Splats
        - Papers:
          - <span id="cite_1">\[1\]</span>: “3D gaussian splatting for
            real-time radiance field rendering” (2023)
        - Repos:
          - [*3D Gaussian Splatting for Real-Time Radiance Field
            Rendering*](https://github.com/graphdeco-inria/gaussian-splatting)
  - Related Problems
    - Predictive Maintenance / Anomaly Detection
      - Papers:
        - <span id="cite_2">\[2\]</span>: “Uncertainty-estimation with
          normalized logits for out-of-distribution detection” (2023)
        - <span id="cite_3">\[3\]</span>: “Do deep generative models
          know what they don’t know?” (2019)
    - Transfer Learning
      - Papers:
        - <span id="cite_4">\[4\]</span>: “A systematic literature
          review on transfer learning for predictive maintenance in
          industry 4.0” (2023)
      - Links:
        - [*A Gentle Introduction to Transfer Learning for Deep
          Learning*](https://machinelearningmastery.com/transfer-learning-for-deep-learning/)
        - [*Transfer Learning in Keras with Computer Vision
          Models*](https://machinelearningmastery.com/how-to-use-transfer-learning-when-developing-convolutional-neural-network-models/)
- **`Supervised Learning`**
  - Papers:
    - <span id="cite_5">\[5\]</span>: “A multi-branch u-net for steel
      surface defect type and severity segmentation” (2021)
    - <span id="cite_6">\[6\]</span>: “U-net: Convolutional networks for
      biomedical image segmentation” (2015)
    - <span id="cite_7">\[7\]</span>: “Improved u-net with residual
      attention block for mixed-defect wafer maps” (2022)
    - <span id="cite_8">\[8\]</span>: “An automatic welding defect
      location algorithm based on deep learning” (2021)
- **`Semi-supervised Learning`**
  - Domain Generalization
    - Papers:
      - <span id="cite_9">\[9\]</span>: “Domain generalization: A
        survey” (2023)
      - <span id="cite_10">\[10\]</span>: “Generalizing to unseen
        domains: A survey on domain generalization” (2023)
  - Domain Adaptation
    - Zero-Shot Learning
      - Papers:
        - <span id="cite_11">\[11\]</span>: “Importance of semantic
          representation: Dataless classification” (2008)
        - <span id="cite_12">\[12\]</span>: “Zero-data learning of new
          tasks” (2008)
        - <span id="cite_13">\[13\]</span>: “WinCLIP: Zero-/few-shot
          anomaly classification and segmentation” (2023)
        - <span id="cite_14">\[14\]</span>: “AnoVL: Adapting
          vision-language models for unified zero-shot anomaly
          localization” (2023)
      - Repositories:
        - [*Official Implementation of AnoVL
          (Updating)*](https://github.com/hq-deng/AnoVL)
- **`Unsupervised Learning`**
  - Normalizing Flows
    - Papers:
      - <span id="cite_15">\[15\]</span>: “Density estimation by dual
        ascent of the log-likelihood” (2010)
      - <span id="cite_16">\[16\]</span>: “A family of nonparametric
        density estimation algorithms” (2013)
      - <span id="cite_17">\[17\]</span>: “A case for unsupervised
        defect detection in manufacturing” (2023)
      - <span id="cite_18">\[18\]</span>: “Fully convolutional
        cross-scale-flows for image-based defect detection” (2022)
      - <span id="cite_19">\[19\]</span>: “Same same but DifferNet:
        Semi-supervised defect detection with normalizing flows” (2021)
      - <span id="cite_20">\[20\]</span>: “Normalizing flows for
        probabilistic modeling and inference” (2021)
      - <span id="cite_21">\[21\]</span>: “Neural density estimation and
        likelihood-free inference” (2019)
    - Repositories:
      - [*DifferNet: Semi-Supervised Defect Detection with Normalizing
        Flows*](https://github.com/marco-rudolph/differnet)
      - [*CS-Flow: Fully Convolutional Cross-Scale-Flows for Image-based
        Defect Detection*](https://github.com/marco-rudolph/cs-flow)
- **`Other`**
  - Potentially Interesting Concepts (Limited Applicability)
    - Cross-Modality
    - Typicality / Out-Of-Distribution Detection (OOD)
      - Papers:
        - <span id="cite_22">\[22\]</span>: “Detecting
          out-of-distribution inputs to deep generative models using a
          test for typicality” (2019)
        - <span id="cite_23">\[23\]</span>: “Entropic issues in
          likelihood-based OOD detection” (2021)

# References

<div id="refs" class="references csl-bib-body">

<div id="ref-kerbl2023gauss" class="csl-entry">

<span class="csl-left-margin">\[1\]
</span><span class="csl-right-inline">B. Kerbl, G. Kopanas, T.
Leimkühler, and G. Drettakis, “3D gaussian splatting for real-time
radiance field rendering,” *ACM Trans. Graph.*, vol. 42, no. 4, pp.
139:1–139:14, 2023, doi:
[10.1145/3592433](https://doi.org/10.1145/3592433).</span>
\[[1](#cite_1)\]

</div>

<div id="ref-huang2023uncertainty" class="csl-entry">

<span class="csl-left-margin">\[2\]
</span><span class="csl-right-inline">M. Huang and Y. Qiao,
“Uncertainty-estimation with normalized logits for out-of-distribution
detection,” *CoRR*, vol. abs/2302.07608, 2023, doi:
[10.48550/arXiv.2302.07608](https://doi.org/10.48550/arXiv.2302.07608).</span>
\[[1](#cite_2)\]

</div>

<div id="ref-nalisnick2019know" class="csl-entry">

<span class="csl-left-margin">\[3\]
</span><span class="csl-right-inline">E. T. Nalisnick, A. Matsukawa, Y.
W. Teh, D. Görür, and B. Lakshminarayanan, “Do deep generative models
know what they don’t know?” in *7th international conference on learning
representations, ICLR 2019, new orleans, LA, USA, may 6-9, 2019*,
OpenReview.net, 2019. doi:
[10.48550/arXiv.1810.09136](https://doi.org/10.48550/arXiv.1810.09136).</span>
\[[1](#cite_3)\]

</div>

<div id="ref-azari2023pred" class="csl-entry">

<span class="csl-left-margin">\[4\]
</span><span class="csl-right-inline">M. S. Azari, F. Flammini, S.
Santini, and M. Caporuscio, “A systematic literature review on transfer
learning for predictive maintenance in industry 4.0,” *IEEE Access*,
vol. 11, pp. 12887–12910, 2023, doi:
[10.1109/ACCESS.2023.3239784](https://doi.org/10.1109/ACCESS.2023.3239784).</span>
\[[1](#cite_4)\]

</div>

<div id="ref-neven2021unet" class="csl-entry">

<span class="csl-left-margin">\[5\]
</span><span class="csl-right-inline">R. Neven and T. Goedemé, “A
multi-branch u-net for steel surface defect type and severity
segmentation,” *Metals*, vol. 11, no. 6, p. 870, May 2021, doi:
[10.3390/met11060870](https://doi.org/10.3390/met11060870).</span>
\[[1](#cite_5)\]

</div>

<div id="ref-ronneberger2015unet" class="csl-entry">

<span class="csl-left-margin">\[6\]
</span><span class="csl-right-inline">O. Ronneberger, P. Fischer, and T.
Brox, “U-net: Convolutional networks for biomedical image segmentation,”
in *Medical image computing and computer-assisted intervention - MICCAI
2015 - 18th international conference munich, germany, october 5 - 9,
2015, proceedings, part III*, N. Navab, J. Hornegger, W. M. W. III, and
A. F. Frangi, Eds., in Lecture notes in computer science, vol. 9351.
Springer, 2015, pp. 234–241. doi:
[10.1007/978-3-319-24574-4\\28](https://doi.org/10.1007/978-3-319-24574-4\_28).</span>
\[[1](#cite_6)\]

</div>

<div id="ref-cha2022unet" class="csl-entry">

<span class="csl-left-margin">\[7\]
</span><span class="csl-right-inline">J. Cha and J. Jeong, “Improved
u-net with residual attention block for mixed-defect wafer maps,”
*Applied Sciences*, vol. 12, no. 4, p. 2209, Feb. 2022, doi:
[10.3390/app12042209](https://doi.org/10.3390/app12042209).</span>
\[[1](#cite_7)\]

</div>

<div id="ref-yang2021automatic" class="csl-entry">

<span class="csl-left-margin">\[8\]
</span><span class="csl-right-inline">L. Yang, H. Wang, B. Huo, F. Li,
and Y. Liu, “An automatic welding defect location algorithm based on
deep learning,” *NDT & E International*, vol. 120, p. 102435, 2021, doi:
<https://doi.org/10.1016/j.ndteint.2021.102435>.</span> \[[1](#cite_8)\]

</div>

<div id="ref-zhou2023dg" class="csl-entry">

<span class="csl-left-margin">\[9\]
</span><span class="csl-right-inline">K. Zhou, Z. Liu, Y. Qiao, T.
Xiang, and C. C. Loy, “Domain generalization: A survey,” *IEEE Trans.
Pattern Anal. Mach. Intell.*, vol. 45, no. 4, pp. 4396–4415, 2023, doi:
[10.1109/TPAMI.2022.3195549](https://doi.org/10.1109/TPAMI.2022.3195549).</span>
\[[1](#cite_9)\]

</div>

<div id="ref-wang2023generalizing" class="csl-entry">

<span class="csl-left-margin">\[10\]
</span><span class="csl-right-inline">J. Wang, C. Lan, C. Liu, Y.
Ouyang, T. Qin, W. Lu, Y. Chen, W. Zeng, and P. S. Yu, “Generalizing to
unseen domains: A survey on domain generalization,” *IEEE Trans. Knowl.
Data Eng.*, vol. 35, no. 8, pp. 8052–8072, 2023, doi:
[10.1109/TKDE.2022.3178128](https://doi.org/10.1109/TKDE.2022.3178128).</span>
\[[1](#cite_10)\]

</div>

<div id="ref-chang2008dataless" class="csl-entry">

<span class="csl-left-margin">\[11\]
</span><span class="csl-right-inline">M.-W. Chang, L.-A. Ratinov, D.
Roth, and V. Srikumar, “Importance of semantic representation: Dataless
classification,” in *Proceedings of the twenty-third AAAI conference on
artificial intelligence, AAAI 2008, chicago, illinois, USA, july 13-17,
2008*, D. Fox and C. P. Gomes, Eds., AAAI Press, 2008, pp. 830–835.
Available: <http://www.aaai.org/Library/AAAI/2008/aaai08-132.php></span>
\[[1](#cite_11)\]

</div>

<div id="ref-larochelle2008zerodata" class="csl-entry">

<span class="csl-left-margin">\[12\]
</span><span class="csl-right-inline">H. Larochelle, D. Erhan, and Y.
Bengio, “Zero-data learning of new tasks,” in *Proceedings of the
twenty-third AAAI conference on artificial intelligence, AAAI 2008,
chicago, illinois, USA, july 13-17, 2008*, D. Fox and C. P. Gomes, Eds.,
AAAI Press, 2008, pp. 646–651. Available:
<http://www.aaai.org/Library/AAAI/2008/aaai08-103.php></span>
\[[1](#cite_12)\]

</div>

<div id="ref-jeong2023winclip" class="csl-entry">

<span class="csl-left-margin">\[13\]
</span><span class="csl-right-inline">J. Jeong, Y. Zou, T. Kim, D.
Zhang, A. Ravichandran, and O. Dabeer, “WinCLIP: Zero-/few-shot anomaly
classification and segmentation,” in *IEEE/CVF conference on computer
vision and pattern recognition, CVPR 2023, vancouver, BC, canada, june
17-24, 2023*, IEEE, 2023, pp. 19606–19616. doi:
[10.1109/CVPR52729.2023.01878](https://doi.org/10.1109/CVPR52729.2023.01878).</span>
\[[1](#cite_13)\]

</div>

<div id="ref-deng2023anovl" class="csl-entry">

<span class="csl-left-margin">\[14\]
</span><span class="csl-right-inline">H. Deng, Z. Zhang, J. Bao, and X.
Li, “AnoVL: Adapting vision-language models for unified zero-shot
anomaly localization,” *CoRR*, vol. abs/2308.15939, 2023, doi:
[10.48550/ARXIV.2308.15939](https://doi.org/10.48550/ARXIV.2308.15939).</span>
\[[1](#cite_14)\]

</div>

<div id="ref-esteban2010density" class="csl-entry">

<span class="csl-left-margin">\[15\]
</span><span class="csl-right-inline">E. G. Tabak and E. Vanden-Eijnden,
“<span class="nocase">Density estimation by dual ascent of the
log-likelihood</span>,” *Communications in Mathematical Sciences*, vol.
8, no. 1, pp. 217–233, 2010, Available:
<https://projecteuclid.org/journals/communications-in-mathematical-sciences/volume-8/issue-1/Density-estimation-by-dual-ascent-of-the-log-likelihood/cms/1266935020.full></span>
\[[1](#cite_15)\]

</div>

<div id="ref-tabak2013family" class="csl-entry">

<span class="csl-left-margin">\[16\]
</span><span class="csl-right-inline">E. G. Tabak and C. V. Turner, “A
family of nonparametric density estimation algorithms,” *Communications
on Pure and Applied Mathematics*, vol. 66, no. 2, pp. 145–164, 2013,
doi: [10.1002/cpa.21423](https://doi.org/10.1002/cpa.21423).</span>
\[[1](#cite_16)\]

</div>

<div id="ref-viberg2023" class="csl-entry">

<span class="csl-left-margin">\[17\]
</span><span class="csl-right-inline">F. Viberg, J. Nordqvist, M.
Ericsson, A. Kaiser, M. Kroon, W. Löwe, M. Nilsson, and F. Sandberg, “A
case for unsupervised defect detection in manufacturing,” in *35th
annual workshop of the swedish artificial intelligence society, SAIS
2023, karlskrona, sweden, june 12–13, 2023*, H. Grahn, A. Borg, and M.
Boldt, Eds., 2023. Available:
<https://grahn.cse.bth.se/SAIS-2023/extended_abstracts/paper_33.pdf></span>
\[[1](#cite_17)\]

</div>

<div id="ref-rudolph2022csf" class="csl-entry">

<span class="csl-left-margin">\[18\]
</span><span class="csl-right-inline">M. Rudolph, T. Wehrbein, B.
Rosenhahn, and B. Wandt, “Fully convolutional cross-scale-flows for
image-based defect detection,” in *IEEE/CVF winter conference on
applications of computer vision, WACV 2022, waikoloa, HI, USA, january
3–8, 2022*, IEEE, 2022, pp. 1829–1838. doi:
[10.1109/WACV51458.2022.00189](https://doi.org/10.1109/WACV51458.2022.00189).</span>
\[[1](#cite_18)\]

</div>

<div id="ref-rudolph2021samesame" class="csl-entry">

<span class="csl-left-margin">\[19\]
</span><span class="csl-right-inline">M. Rudolph, B. Wandt, and B.
Rosenhahn, “Same same but DifferNet: Semi-supervised defect detection
with normalizing flows,” in *IEEE winter conference on applications of
computer vision, WACV 2021, waikoloa, HI, USA, january 3–8, 2021*, IEEE,
2021, pp. 1906–1915. doi:
[10.1109/WACV48630.2021.00195](https://doi.org/10.1109/WACV48630.2021.00195).</span>
\[[1](#cite_19)\]

</div>

<div id="ref-papamakarios2021normalizing" class="csl-entry">

<span class="csl-left-margin">\[20\]
</span><span class="csl-right-inline">G. Papamakarios, E. T. Nalisnick,
D. J. Rezende, S. Mohamed, and B. Lakshminarayanan, “Normalizing flows
for probabilistic modeling and inference,” *J. Mach. Learn. Res.*, vol.
22, pp. 57:1–57:64, 2021, Available:
<http://jmlr.org/papers/v22/19-1028.html></span> \[[1](#cite_20)\]

</div>

<div id="ref-papamakarios2019phd" class="csl-entry">

<span class="csl-left-margin">\[21\]
</span><span class="csl-right-inline">G. Papamakarios, “Neural density
estimation and likelihood-free inference,” PhD thesis, University of
Edinburgh, UK, 2019. Available:
<https://ethos.bl.uk/OrderDetails.do?uin=uk.bl.ethos.798882></span>
\[[1](#cite_21)\]

</div>

<div id="ref-nalisnick2019detecting" class="csl-entry">

<span class="csl-left-margin">\[22\]
</span><span class="csl-right-inline">E. T. Nalisnick, A. Matsukawa, Y.
W. Teh, and B. Lakshminarayanan, “Detecting out-of-distribution inputs
to deep generative models using a test for typicality,” *CoRR*, vol.
abs/1906.02994, 2019, doi:
[10.48550/arXiv.1906.02994](https://doi.org/10.48550/arXiv.1906.02994).</span>
\[[1](#cite_22)\]

</div>

<div id="ref-caterini2021entropic" class="csl-entry">

<span class="csl-left-margin">\[23\]
</span><span class="csl-right-inline">A. L. Caterini and G.
Loaiza-Ganem, “Entropic issues in likelihood-based OOD detection,” in *I
(still) can’t believe it’s not better! Workshop at NeurIPS 2021, virtual
workshop, december 13, 2021*, M. F. Pradier, A. Schein, S. L. Hyland, F.
J. R. Ruiz, and J. Z. Forde, Eds., in Proceedings of machine learning
research, vol. 163. PMLR, 2021, pp. 21–26. Available:
<https://proceedings.mlr.press/v163/caterini22a.html></span>
\[[1](#cite_23)\]

</div>

</div>
