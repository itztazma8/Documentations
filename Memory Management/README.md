## Overview
The following document evaluates two important data structures- *Hashed Page Table* and *Inverted Page Table* for understanding how virtual addresses work inside our operating systems. 

## Hashed Page Table
Use of linked lists is common here to ensure fast lookup and also convinient for handling collisions. But it comes with a price which is the overhead. Details are given in the document.

## Inverted Page Table
In this case, the page number and the process ID is stored. The storage is done using phsical frames. It is super easy to implement and contains less overhead but it comes with the complexity of searching

## Main purpose?
It is to understand when we can allow to use the data structures as both have different pros and cons in what kind of circumstances.
