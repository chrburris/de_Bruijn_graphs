# de Bruijn Sequences (and Graphs)

## What are they and why do we care about them?

Consider the sequence of 0s and 1s: 00110. Notice that, stepping from left to right with a subword length 2, we see the subwords 00, 01, 11, and 10. It turns out that these are all possible subsequences of 0s and 1s of length 2. 

For positive integers *k* and *n*, a *de Bruijn sequence B(k, n*) is a finite sequence of elements drawn from *k* characters whose subwords of length *n* are exactly the *k^n* words of length *n* on *k* characters. This definition is mentioned below again in the abstract of the paper I wrote regarding these sequences. It turns out that de Bruijn sequences have a lot of useful properties in graph theory and combinatorics. Although I won't define the de Bruijn graph, you can take my word for it that its symmetries and paths are of interest to the field. 
  
I was interested in de Bruijn sequences as they related to genes. Way back when (not very long ago) microarrays were the primary technology used for collecting gene expression data. However, microarray data is expensive to collect. My colleagues and I were interested in using de Bruijn sequence structure to simplify the microarray probing mechanism. 

## Content 

In this repo you will find a pdf of a presentation I gave on this work at the Front Range Applied Mathematics conference, a poster of the same work presented at the Joint Mathematics Meeting,  as well as the arXiv paper that appears in the Journal of Graphs and Combinatorics.

*Unoriented_Var_de_Bruijn_Seq.pdf* is the pdf from the arXiv copy of a peer-reviewed article on de Bruijn sequences as they apply to microarray technology. The paper also appears in the Journal of Graphs and Combinatorics. 

*Final_Fram.pdf* is a presentation on the work that appears in the paper above given at the Front Rance Applied Mathematics conference.

*de_Bruijn_poster.pdf* is a poster of the same work presented at the Joint Mathematics Meeting. 

### Abstract of the work:

For positive integers *k* and *n*, a *de Bruijn sequence B(k, n*) is a finite sequence of elements drawn from *k* characters whose subwords of length *n* are exactly the *k^n* words of length *n* on *k* characters. This paper introduces the unoriented de Bruijn sequence *uB(k, n)*, an analog to de Bruijn sequences, but for which the sequence is read both forwards and backwards to determine the set of subwords of length n. We show that nontrivial unoriented de Bruijn sequences of optimal length exist if and only if *k* is two or odd and *n* is less than or equal to 3. Unoriented de Bruijn sequences for any *k*, n may be constructed from certain Eulerian paths in Eulerizations of unoriented de Bruijn graphs.

