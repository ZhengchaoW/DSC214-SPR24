# DSC 214: Topological Data Analysis

## Basic Information
**Instructor:** [Zhengchao Wan](https://zhengchaow.github.io) (zcwan@ucsd.edu)

**Lectures:** MWF, 9:00am - 9:50am, Pepper Canyon Hall 121

**Office Hours:** Office 147, HDSI, Wednesdays 10:00am - 11:00am or by appointment (zcwan@ucsd.edu)

---
## Course Description
Topological methods provide powerful tools for characterizing structures / features behind data and analyzing diverse complex data (images, graphs, point sets, etc). This course introduces basic concepts and topological structures, as well as recent topological tools, algorithms, as well as examples to applications. Some topics include: basics in topology, simplicial complexes to model data, persistent homology, discrete Morse theory, topology inference, the Mapper methodology, hierarchical clustering, and integration of topological methods with machine learning. A tentative list of topics is listed [here](schedule.pdf)

This course is for graduate students and advanced undergraduate students.

**Prerequisite:** Linear algebra, algorithms

---

## Grading policy
There is a final project/survey: 100%
- The final grade is based on four parts
  - proposal
  - project
    - report
    - short presentation
- Requirement:  
  - Students can work in **groups** up to 3. But I will expect more work from a group project.
  - Each student is required to meet briefly with me around 3-4th week, so that we can discuss to find a good potential topic for your final project. 
  - After a topic is chosen, you are required to submit a short proposal (1-2 pages) about what you intend to work on and your plan. 
  - Later, after you finish your project, you will submit a final report (4+ pages), which should clearly describe the motivation of your project, what you have done, and your findings. A survey needs to be 10+ pages. 
  - A 10-min presentation (in class or video) is also needed.
- Here is the overleaf template for writing proposal and report https://www.overleaf.com/read/bwdqbcxvdmtw

### Project ideas
The goal of the class project is to encourage you to explore topological data analysis methods, whether through applications or theoretical research.  Some possibilities
- use topological methods to analyze datasets from your own research
- theoretical improvements to existing results 
- explore recent TDA-related papers in NeurIPS, ICML, or ICLR. 

You can find over 400 papers on TDA applications in the [Zotero database](https://www.zotero.org/groups/2425412/tda-applications/items), which you may use as inspiration to improve upon an existing paper or apply to your dataset in a non-trivial manner. If you are having difficulty finding a suitable topic, don't hesitate to reach out to me and we can work together to find a topic that fits your background or current research interests.


### Timeline
- Week 2-5: Students meet with me to discuss project topic.
- Week 6: Selection of final project topic done. Project proposal due by end of May 11th, 2023 (Saturday). 
- Week 10: Finish up your final project
- Final week: Final project report as well as your recorded presentation are due by June 12, 2023 (Wednesday). 



## Assignment 0
Access the course materials on https://github.com/ZhengchaoW/DSC214-SPR24

---
## References
Much of the material is from the book 
- ***Computational Topology for Data Analysis*** by Dr. T. K. Dey and Dr. Y. Wang, and you can download an e-version of the book [here](http://yusu.belkin-wang.org/CTDAbook-DeyWang.pdf)

Other useful references
- *Computational Topology: An Introduction*,  by  H. Edelsbrunner and J. Harer, AMS Press, 2009.
- https://www.aatrn.net/ (AATRN: Applied Algebraic Topology Research Network)
  - they have some awesome [short videos](https://sites.google.com/view/aatrn-tutorial-a-thon) on various topics in TDA
- Yusu's [course webpage](https://sites.google.com/ucsd.edu/dsc291-190-tda)
- [Lecture notes](https://drive.google.com/open?id=1SCrKHfZdDuMmSKlZ7xveQT8SqBHjFEkk) by Dr. Tom Needham from FSU (with more focus on mathematics details)
- A [Zotero database](https://www.zotero.org/groups/2425412/tda-applications/items) of papers on topological data analysis
- *Algebraic Topology*,  by  A. Hatcher, Cambridge University Press, 2002. (Online version is available at the [author's webpage](https://pi.math.cornell.edu/~hatcher/AT/ATpage.html).)


---
## Lecture materials

Topic 0: Introduction to Topological Data Analysis ([slides](slides/Topic0-Intro.pdf))

Topic 1: Basics in Topology ([slides](slides/Topic1-basics.pdf))
 
Topic 2: Simplicial Complexes ([slides](slides/Topic2-simplicial-complex.pdf))
   - check out these wonderful videos on alpha, Rips and Čech complexes: 
     -  [Alpha complexes by Ondřej Draganov](https://youtu.be/-XCVn73p3xs)
     -  [Rips and Čech complexes by Henry Adams](https://youtu.be/YLXAF8IB9Ng)
  
Topic 3: Homology ([slides](slides/Topic3-homology.pdf))

Topic 4: Persistent Homology ([slides A](slides/Topic4-A-intro-to-pH.pdf), [slides B](slides/Topic4-B-common-pH.pdf))

Topic 5: Stability of persistence diagrams ([slides](slides/Topic5-stability.pdf))

Topic 6: Persistent Homology of PCD ([slides](slides/Topic6-PCD.pdf))

Topic 7: Persistence in Practice ([slides](slides/Topic7-practice.pdf))

Topic 8: TDA in machine learning ([slides](slides/Topic8-ML.pdf))
  - Nice [video](https://youtu.be/-SqbDUiutu8) by Bastian Rieck

Topic 9: Mapper ([slides](slides/Topic9-Mapper.pdf))

Topic 10: Discrete Morse Theory ([slides](slides/Topic10-DMT.pdf))
  - very nice introduction of DMT by [Nick Scoville](https://youtu.be/_2TjYFTrzAg)

Final Remarks ([slides](slides/Final_Remarks.pdf))