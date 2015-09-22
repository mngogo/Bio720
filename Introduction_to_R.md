#Introduction to Programming with R

 We do not have enough "in class" time to really develop all of the `R` programming skills necessary to enable you to independently perform analysis of differential expression using RNAseq data. Therefore, most of the activities will be self-guided, using a combination of video tutorials and practical exercises. It is expected you will have done all of these for class, as we will be doing a larger in class set of activities assuming a basic level of comfort and familiarity.

Readings: From Bioinformatics Data Skills, chapter 8 presents a crash course in programming in `R`. We will not be using any of the functionality in `ggplot2` quite yet, so you can skip those pages (i.e. skip 207-215, 224-227). I suggest that reading a bit, and/or going through the relevant video tutorial & exercises, and then moving onto the next component may work best.

The data set that is used for some of these activities can be found on the [DRYAD Digital repository](http://datadryad.org/) right [here](http://datadryad.org/bitstream/handle/10255/dryad.8377/dll.csv?sequence=1). You can also set this up (so you do not need a local copy by putting this command:
```R
dll.data <- read.csv("http://datadryad.org/bitstream/handle/10255/dryad.8377/dll.csv", h=T)
```

1. Why use `R` (and why learn to program):Motivating example of working counts of expression data from RNAseq.
2. Introduction to `R`: [part 1. `R` as a calculator](https://youtu.be/Kyxx9_NLlUY/0.jpg)
3. Introduction to `R`: [part 2. Basic operations and operators in `R`](https://www.youtube.com/watch?v=UrtWeRPpWCw)
4. Introduction to `R`: [part 3. Element-by-element operations, booleans & basic functions](https://www.youtube.com/watch?v=8VcysxMmpg0)
5. Introduction to `R`: [part 4. objects and classes in `R`](https://www.youtube.com/watch?v=-qDiqnEVaLk)
6. Introduction to `R`: [part 5. workspaces and getting help in `R`](https://www.youtube.com/watch?v=0Y9IRfJwzjo)
7. Introduction to `R`: [part 6. writing your own functions in `R`](https://www.youtube.com/watch?v=Mth_tvrxik0)
8. Introduction to `R`: [part 7. regular sequences and indexing](https://www.youtube.com/watch?v=V5_vb7gLtrk)
9. Introduction to `R`: [part 8. getting data into `R`](https://www.youtube.com/watch?v=SlupCvzH2nM)
10. Introduction to `R`: [part 9. control flow in `R`](https://www.youtube.com/watch?v=FgtqJ8-DN7k)
11. Introduction to `R`: [part 10. using the apply family of functions in `R`](https://www.youtube.com/watch?v=uL_LdYS-scQ) 