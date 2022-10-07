---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
#title: Bioinformatics for Computer Scientists
---

# Introduction

The content below is my attempt to explore Biology and progress toward Bioinformatics, on my own time, without initially committing money or sacrificing my existing career.  I have a BS, MS, and 20 years experience in Computer Science.  

The inspiration for this is that I was originally a Biochemistry major at Penn State, but, through a sequence inspirations, found my calling in Computer Science.  I still have a desire to learn Biology, and recent advancements in machine learning and Bioinformatics have made it enticing to cross-train.  However, while trying to pursue this, I discovered that most Bioinformatics material is geared toward beginning as a Biologist or Biochemist and subsequently cross-training into Computer Science; the converse does not seem to exist in the way that would satisfy me intellectually.  In particular, I would like a fundamental understanding of the concepts so that I can understand the implications of the data to be processed.

The content here primarily from [MIT's Open Courseware](https://ocw.mit.edu/).  I constructed the list from  MIT's interdisciplinary [BS in CS and Molecular Biology](http://catalog.mit.edu/degree-charts/computer-science-molecular-biology-course-6-7/) along with guidance and advice from an oncology colleague, who also pointed me to curricula from [the University of Maryland Baltimore County's (UMBC) B.S. in Bioinformatics and Computataional Biology](./umbc.md) and [The Johns Hopkins University MS in Bioinformatics](./hopkins.md).

The checked content is content that I've either completed since beginning this endeavor, or that I satisfied as part of my undergraduate or graduate studies in Computer Science.

## Brief Notes on the MIT Curriculum  

A note on MIT numbering:

* 5 => Chemistry
* 6 => Electrical Engineering and Computer Science
* 7 => Biology

While identifying classes, the folowing explanations of course numbering at MIT were helpful in identifying whether courses were related or equivalent;

* https://eecsis.mit.edu/numbering.html#6.10xx
* https://eecsis.mit.edu/numbering.html#6.47xx

## Required - Mathematics and Programming

`Note: I didn't do these through MIT OCW.  I satisfied all of this through my undergraduate studies and career.`

* [x] 6.100A - Introduction to Computer Science Programming in Python
* [x] 6.100B - Introduction to Computational Thinking and Data Science 
    * Best satisfied by [6.0002 - Introduction to Computational Thinking and Data Science](https://ocw.mit.edu/courses/6-0002-introduction-to-computational-thinking-and-data-science-fall-2016/) (Erik Grimson, Fall 2016) - This is Python 3.5, so it might be best to start here
* [x] 6.1200J - Mathematics for Computer Science

## Start Here - Biology

> A Note: I studied AP Biology and AP Chemistry in high school.  Though the content isn't fresh, I needed to recall significant portions of it to complete the below class.  If you have absolutely no biology or chemistry experience, you will need to find additional courses to satisfy the basics in each.

* [x] [5.111SC - Principles of Chemical Science](https://ocw.mit.edu/courses/5-111sc-principles-of-chemical-science-fall-2014/) (Catherine Drennan, Fall 2014)
   * The lectures make this look roughly equivalent to high school AP Chemistry, or at least overlap heavily.  I'm going to assume I remember enough of this and then return to it if I determine otherwise.  If your Chemistry is really weak or non-existent, maybe start here...
* [x] [7.01 - Getting up to Speed in Biology](https://openlearninglibrary.mit.edu/courses/course-v1:OCW+Pre-7.01+1T2020/about) - Do this first
    * Definitely had to do this; it's been 23 years since my last biology class.  I tried starting with `7.016 - Introduction to Biology`, but the intro class gave me indications that the content would exceed my understanding at the time.
    * [My class notes](./notes/mit_ocw-7.01.md)
    * I took this before the [5.12 - Organic Chemistry I](https://ocw.mit.edu/courses/5-12-organic-chemistry-i-spring-2005/) class.  Should I have?  I believe that this class was a gentle enough introduction to concepts in Biology and Chemistry with an AP Biology high school background.

## Prerequisites - Chemistry

* [ ] [5.12 - Organic Chemistry I](https://ocw.mit.edu/courses/5-12-organic-chemistry-i-spring-2005/) (Kimberly Berkowski, Spring 2005)
* [ ] [5.60 - Thermodynamics and Kinetics](https://ocw.mit.edu/courses/5-60-thermodynamics-kinetics-spring-2008/) (Spring 2008)
  * This seems to have since split into two classes since hte time it was offered, but the professor for the linked class is the same as the one for both of the below classes.:
    * [ ] 5.601 - Thermodynamics I
    * [ ] 5.602 - Thermodynamics II and Kinetics
  
## Prerequisites - Biology



* Choose 1
    * [ ] [7.013 - Introduction to Biology](https://ocw.mit.edu/courses/7-013-introductory-biology-spring-2018/) (Angelika Amon, Spring 2018)  - Genomics focus
    * [ ] [7.016 - Introductory Biology](https://ocw.mit.edu/courses/7-016-introductory-biology-fall-2018/) (Barbara Imperiali, Fall 2018) - Focus on biological function @ molecular level, gene regulation, etc.

Note: The above may overlap a lot with 7.03 - Genetics

## Foundational

* [x] 6.1010 - Fundamentals of Programming - This course is Python-based
    * Best satisfied through ocw by [Introduction to Computer Science and Programming in Python](https://ocw.mit.edu/courses/6-0001-introduction-to-computer-science-and-programming-in-python-fall-2016/) (Ana Bell, Fall 2016)
    * This could be weird because I don't know whether Python3 has taken over Bioinformatics, so this may be a little dated
    * It is hard to tell how this differs from 6.100A
* [x] 6.1210 - Introduction to Algorithms
    * Best satisfied through ocw by [Introduction to Algorithms](https://ocw.mit.edu/courses/6-006-introduction-to-algorithms-spring-2020/) (Erik Demaine, Spring 2020)
* [x] 5.1220J - Design and Analysis of Algorithms
    * Best satisfied through ocw by [Design and Analysis of Algorithms](https://ocw.mit.edu/courses/6-046j-design-and-analysis-of-algorithms-spring-2015/) (Erik Demaine, Spring 2015)
* [ ] [7.03 - Genetics](https://ocw.mit.edu/courses/7-03-genetics-fall-2004/) (Chris Kaiser, Fall 2004)
* [ ] [7.05 - General Biochemistry](https://ocw.mit.edu/courses/7-05-general-biochemistry-spring-2020/) (Matthew Vander Heiden, Spring 2020)
* [ ] [7.06 - Cell Biology](https://ocw.mit.edu/courses/7-06-cell-biology-spring-2007/) (Hidde Ploegh, Spring 2007)

## Computational Biology

* [ ] 6.8701 - Computational Biology: Genomes, Networks, Evolution
    * Satisfy with [6.047 - Computational Biology](https://ocw.mit.edu/courses/6-047-computational-biology-fall-2015/) (Manolis Kellis, Fall 2015).  This is the same instructor as 6.8701; in fact, per the re-numbering, this is the same class, just older
* [ ] 6.8711 - Computational Systems Biology: Deep Learning in the Life Sciences
    * Satisfy with [7.91J - Foundations of Computational and Systems Biology](https://ocw.mit.edu/courses/7-91j-foundations-of-computational-and-systems-biology-spring-2014/) (Christopher Burge, Spring 2014). This is the older numbering
* [ ] 7.093 - Modern Biostatistics - can't find it on OCW
* [ ] 7.094 - Modern Computational Biology - can't find it on OCW
* [ ] 7.33J - Evolutionary Biology: Concepts, Models, and Computation
    * Possibly satisfy with [6.877J - Computational Evolutionary Biology](https://ocw.mit.edu/courses/6-877j-computational-evolutionary-biology-fall-2005/) (Robert Berwick, Fall 2005) - Same instructor

## Biology Restricted Electives (Select 1)

These should be sufficiently difficult to find on OCW, I expect

* [ ] 7.08[J] Fundamentals of Chemical Biology	
* [ ] ~~7.093 Modern Biostatistics~~
* [ ] ~~7.094	Modern Computational Biology 1~~
* [ ] 7.20[J]	Human Physiology	
* [ ] 7.21	Microbial Physiology	
* [ ] 7.23[J]	Immunology	
* [ ] 7.26	Molecular Basis of Infectious Disease	
* [ ] [7.27 Principles of Human Disease and Aging](https://ocw.mit.edu/courses/7-27-principles-of-human-disease-spring-2006/)
* [ ] [7.28	Molecular Biology](https://ocw.mit.edu/courses/7-28-molecular-biology-spring-2005/)
* [ ] 7.29[J]	Cellular and Molecular Neurobiology	
* [ ] 7.30[J]	Fundamentals of Ecology	
* [ ] 7.31	Current Topics in Mammalian Biology: Medical Implications	
* [ ] [7.32 Systems Biology](https://ocw.mit.edu/courses/8-591j-systems-biology-fall-2004/) - Older offering
* [ ] ~~7.33[J]	Evolutionary Biology: Concepts, Models and Computation 1~~
* [ ] 7.37[J]	Molecular and Engineering Aspects of Biotechnology	
* [ ] 7.371	Biological and Engineering Principles Underlying Novel Biotherapeutics	
* [ ] 7.45	!!The Hallmarks of Cancer!!	
* [ ] 7.46	Building with Cells	
* [ ] 7.49[J]	Developmental Neurobiology

## Not Required but Interesting

* [ ] 5.07SC Biological Chemistry I
* [ ] 5.08J Biological Chmeistry II
* [ ] [7.89J - Foundations of Computational and Systems Biology](https://ocw.mit.edu/courses/7-91j-foundations-of-computational-and-systems-biology-spring-2014/) (Christopher Burge, Spring 2014)
* [ ] [6.096 - Algorithms for Computational Biology](https://ocw.mit.edu/courses/6-096-algorithms-for-computational-biology-spring-2005/) (Manolis Kellis, Spring 2005)
* [ ] [15.097 - Prediction: Machine Learning and Statistics](https://ocw.mit.edu/courses/15-097-prediction-machine-learning-and-statistics-spring-2012/)
* [ ] [7.88J Protein Folding and Human Disease](https://ocw.mit.edu/courses/7-88j-protein-folding-and-human-disease-spring-2015/)
* [ ] [20.482J Foundations of Algorithms and Computational Techniques in Systems Biology](https://ocw.mit.edu/courses/20-482j-foundations-of-algorithms-and-computational-techniques-in-systems-biology-spring-2006/)
* [ ] [HST.508 Genomics and Computational Biology](https://ocw.mit.edu/courses/hst-508-genomics-and-computational-biology-fall-2002/)

## Other Biologiy/Chemistry

* [ ] [Undergrad - Computational Biology](https://ocw.mit.edu/courses/6-047-computational-biology-fall-2015/)
* [ ] [Graduate - Foundations of Computational and Systems Biology](https://ocw.mit.edu/courses/7-91j-foundations-of-computational-and-systems-biology-spring-2014/)
* [ ] [Bioinformatics and Proteomics](https://ocw.mit.edu/courses/6-092-bioinformatics-and-proteomics-january-iap-2005/)

## My Own Ideas on Getting up to Speed in Machine Learning

* [Microsoft's ML for Beginners](https://github.com/microsoft/ML-For-Beginners)
* [Introduction to Modeling and Simulation](https://ocw.mit.edu/courses/3-021j-introduction-to-modeling-and-simulation-spring-2012/)
* [Algorithms for Computational Biology](https://ocw.mit.edu/courses/6-096-algorithms-for-computational-biology-spring-2005/)

### Sub-List

* https://nyandwi.com/machine_learning_complete/outline/

## Online Courses

* [edX](https://www.edx.org/)
    * [RiceX](https://www.edx.org/school/ricex)
    * [GeorgetownX](https://www.edx.org/school/georgetownx)
* [MITx](https://openlearning.mit.edu/courses-programs/mitx-courses?f%5B0%5D=course_availability%3A62)

# Other Resources

* https://github.com/ossu/bioinformatics
* https://github.com/harvardinformatics/learning-bioinformatics-at-home
* https://github.com/ctmrbio/bioinformatics_curriculum
* https://github.com/czbiohub/learn-bioinformatics
* https://github.com/BioinformaNicks/Bioinformatics-training-collection
* https://github.com/danielecook/Awesome-Bioinformatics
