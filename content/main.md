+++
title = "EvadeML: Evading Machine Learning Classifiers"
type = "index"
+++

# Is Robust Machine Learning Possible?

Machine learning has shown remarkable success in solving complex
classification problems, but current machine learning techniques
produce models that are vulnerable to adversaries who may wish to
confuse them, especially when used for security applications like
malware classification.

<img align="right" src="/images/mlassumption.png" width=600>

The key assumption of machine learning is that a model that is trained
on training data will perform well in deployment because the training
data is representative of the data that will be seen when the
classifier is deployed.

When machine learning classifiers are used in security applications,
however, adversaries may be able to generate samples that exploit the
invalidity of this assumption. 

Our project is focused on understanding, evaluating, and improving the
effectiveness of machine learning methods in the presence of motivated
and sophisticated adversaries.

## Projects

<section style="display: table;width: 100%">
  <header style="display: table-row; padding: 0.5rem">
    <div style="display: table-cell; padding: 0.5rem; color:#FFFFFF;background:#663399;text-align: center;width: 49%">
<a href="/gpevasion" class="hlink">Genetic&nbsp;Programming</a>
    </div>
        <div style="display: table-cell; padding: 0.5rem;color:#000000;background: #FFFFFF;text-align: center; width:2%""></div>
    <div style="display: table-cell; padding: 0.5rem;color:#FFFFFF;background: #2c0f52;text-align: center;">
<a href="/squeezing" class="hlink">Feature Squeezing</a>
    </div>
  </header>
  <div style="display: table-row;">
    <div style="display: table-cell;">
    <a href="/gpevasion"><img src="/images/geneticsearch.png" alt="Genetic Search" width="100%" align="center"></a><br>
Evolutionary framework to automatically find variants that preserve malicious behavior but evade a target classifier.
    </div>
    <div style="display: table-cell;"></div>
    <div style="display: table-cell;text-align:center">
    <a href="/squeezing"><img src="/images/squeezing.png" alt="Feature Squeezing" width="100%" align="center"></a><br>
Reducing the search space for adversaries by coalescing inputs.<br>
<font size="-1" style="color:#666;">(The top row shows L<sub>0</sub> adversarial examples, squeezed by median smoothing.)</font>
</div>
  </div>
</section>

## Papers

Weilin Xu, David Evans, Yanjun Qi. [_Feature Squeezing Mitigates and Detects
Carlini/Wagner Adversarial Examples_](https://arxiv.org/abs/1705.10686). arXiv preprint, 30 May 2017. [[PDF](https://arxiv.org/pdf/1705.10686.pdf), 3 pages]

Weilin Xu, David Evans, Yanjun Qi. [_Feature Squeezing: Detecting Adversarial Examples in Deep Neural Networks_](https://arxiv.org/abs/1704.01155). arXiv preprint, 4 April 2017. [[PDF](https://arxiv.org/pdf/1704.01155.pdf), 17 pages]

Weilin Xu, Yanjun Qi, and David Evans. [_Automatically Evading
Classifiers A Case Study on PDF Malware Classifiers_](/docs/evademl.pdf).  [_Network and Distributed Systems Symposium 2016_](https://www.internetsociety.org/events/ndss-symposium-2016), 21-24 February 2016, San Diego, California. Full paper (15 pages): [[PDF](/docs/evademl.pdf)]


## Talks

<p>
<script async class="speakerdeck-embed" data-id="450d6c5f23dd452b8504ac4b8c1bbf84" data-ratio="1.77777777777778" src="//speakerdeck.com/assets/embed.js"></script><br>
David Evans' Talk at <a href="https://www.icsi.berkeley.edu/icsi/events/2017/06/adversarial-machine-learning">Berkeley ICSI</a>, 8 June 2017.
</p>
<p>
<iframe width="640" height="360" src="https://www.youtube.com/embed/XYJamxDROOs" frameborder="0" allowfullscreen></iframe><br>
David Evans' Talk at <a href="https://www.usenix.org/conference/enigma2017/conference-program/presentation/evans">USENIX Enigma 2017</a>, Oakland, CA, 1 February 2017. [<A href="https://speakerdeck.com/evansuva/classifiers-under-attack-1">Speaker Deck</a>]</br>

[More Talks...](talks/)

## Code

**Genetic Evasion:** [https://github.com/uvasrg/EvadeML](https://github.com/uvasrg/EvadeML) (Weilin Xu)  
**Feature Squeezing:** [https://github.com/uvasrg/FeatureSqueezing](https://github.com/uvasrg/FeatureSqueezing) (Weilin Xu)  
**Adversarial Learning Playground**: [https://github.com/QData/AdversarialDNN-Playground](https://github.com/QData/AdversarialDNN-Playground) (Andrew Norton)

## Team

[Weilin Xu](http://www.cs.virginia.edu/~wx4ed/) (Lead PhD Student, leading work on [Feature Squeezing](/squeezing) and [Genetic Evasion](/gpevasion))  
Anant Kharkar (Undergraduate Researcher working on [Genetic Evasion](/gpevasion))  
Helen Simecek (Undergraduate Researcher working on [Genetic Evasion](/gpevasion))  

[David Evans](https://www.cs.virginia.edu/evans) (Faculty Co-Advisor)  
[Yanjun Qi](https://www.cs.virginia.edu/yanjun/) (Faculty Co-Advisor)  
