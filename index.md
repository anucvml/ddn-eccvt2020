<link rel="stylesheet" type="text/css" href="css/bootstrap.min.css">
<link rel="stylesheet" type="text/css" href="css/main.css?1" media="screen,projection">

## Deep Declarative Networks
[ECCV 2020 Tutorial](https://eccv2020.eu/workshops-and-tutorials/), 23-28 August, Glasgow, Ireland

---

[Program](#program) |
[Speakers](#invited-speakers) |
[Organizers](#organizers)

 
Conventional deep learning architectures involve composition of simple and explicitly defined feedforward processing functions. Recently, researchers have been exploring deep learning models with implicitly defined components. To distinguish these from conventional deep learning models they are called  **deep declarative networks** (DDN), borrowing nomenclature from the programming languages community ([Gould et al., 2019](https://arxiv.org/abs/1909.04866)).
<center>
<img src="assets/declarative_node.png" width="50%">
</center>



The deep declarative network’s processing node requires solving an optimization problem in the forward pass, which is parameterized by the inputs to the node, and computing the gradients for back-propagation through the node. This requires the optimization problem to be differentiable, i.e., being able to compute the gradient of the solution with respect to the node’s input. 
A few recent works have studied various optimization problem classes and shown how backpropagation is possible even without prior knowledge of the algorithm used for solving the optimization problem 
(([Agrawal et al., 2019b](http://web.stanford.edu/~boyd/papers/pdf/diff_cvxpy.pdf); 
[Agrawal et al., 2019a](https://web.stanford.edu/~boyd/papers/pdf/diff_cone_prog.pdf); 
[Amos, 2019](http://reports-archive.adm.cs.cmu.edu/anon/2019/CMU-CS-19-109.pdf); 
[Pfau et al. 2019](https://arxiv.org/abs/1806.02215); 
[Amos and Kotler, 2017](https://github.com/locuslab/optnet); 
[Gould et al., 2016](https://arxiv.org/abs/1607.05447)). ). 
These ideas have been applied to various problems including video classification 
(([Fernando and Gould, 2016](http://proceedings.mlr.press/v48/fernando16.pdf); 
 [Cherian et al., 2017](http://openaccess.thecvf.com/content_cvpr_2017/papers/Cherian_Generalized_Rank_Pooling_CVPR_2017_paper.pdf), 
 [Wang and Cherian, 2019](https://ieeexplore.ieee.org/document/8812898))), 
 attribute ranking  ([Santa Cruz et al., 2018](https://ieeexplore.ieee.org/document/8481554)),
 meta-learning  ([Lee et al., 2019](http://openaccess.thecvf.com/content_CVPR_2019/papers/Lee_Meta-Learning_With_Differentiable_Convex_Optimization_CVPR_2019_paper.pdf)).
, decision making ([Donti et.al, 2017](https://papers.nips.cc/paper/7132-task-based-end-to-end-model-learning-in-stochastic-optimization.pdf)), 
and control ([East et.al. 2020](https://arxiv.org/pdf/2001.02244.pdf)).

### Topics

This tutorial will introduce deep declarative networks and their variants. We will discuss the theory behind differentiable optimization, technical issues that need to be overcome in developing such models and applications of these models to computer vision problems. Additionally, the tutorial will provide hands-on experience in designing and implementing a custom declarative node.
 Topics include:
*	Declarative end-to-end learnable processing nodes.
*	Differentiable convex optimization problems.
*	Declarative nodes for computer vision applications.
*	Implementation techniques and gotchas.

## Program

TBA

## Speakers

<div class="row">
  <div class="col-xs-3">
    <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">
      <img class="people-pic" src="assets/sgould.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">Stephen Gould</a><br>
      ANU
    </div>
  </div>
  
  <div class="col-xs-3">
    <a href="https://sites.google.com/view/djcampbell/" target="_blank">
      <img class="people-pic" src="assets/dcampbell.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://sites.google.com/view/djcampbell/" target="_blank">Dylan Campbell</a><br>
      ANU
    </div>
  </div>
</div>


## Organizers

<div class="row">
  <div class="col-xs-3">
    <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">
      <img class="people-pic" src="assets/sgould.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://cecs.anu.edu.au/people/stephen-gould/" target="_blank">Stephen Gould</a><br>
      ANU
    </div>
  </div>
  
  <div class="col-xs-3">
    <a href="https://sites.google.com/view/djcampbell/" target="_blank">
      <img class="people-pic" src="assets/dcampbell.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://sites.google.com/view/djcampbell/" target="_blank">Dylan Campbell</a><br>
      ANU
    </div>
  </div>
    <div class="col-xs-3">
    <a href="http://bamos.github.io/" target="_blank">
      <img class="people-pic" src="assets/bamos.png">
    </a>
    <div class="people-name text-center">
      <a href="http://bamos.github.io/" target="_blank">Brandon Amos</a><br>
      Facebook AI
    </div>
   </div>
     <div class="col-xs-3">
    <a href="https://www.itzikbs.com" target="_blank">
      <img class="people-pic" src="assets/ybenshabat.jpg">
    </a>
    <div class="people-name text-center">
      <a href="https://www.itzikbs.com" target="_blank">Yizhak (Itzik) Ben-Shabat</a><br>
      ANU
    </div>
  </div>
</div>
<br>
<p>
Contact: <a href="mailto:eccv2020@deepdeclarativenetworks.com">eccv2020@deepdeclarativenetworks.com</a>
</p>
