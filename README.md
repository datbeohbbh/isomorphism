# Isomorphism

We have 2 graphs , see [example](https://github.com/datbeohbbh/isomorphism/blob/master/example.png) for detail . 

## INPUT 

\- test.inp contains <b>two</b> sets of graph G and H : 

  * the first line is number n - the number of vertice
  * the second line is set of two graphs
  * each set of edges is entered until type = -1.

\- there are 4 types of edges in graph :

    1. type = 0 U V : arc
    2. type = 1 U V: incident edge
    3. type = 2 U U : loop
    4. type = 3 U U: no edges
 

\- so for each vertice u and each its adjacent vertices v,you need to enter corresponding type of edge then u and v.
(see test.inp and test.out for detail)

## OUTPUT

output will look like [this](https://github.com/datbeohbbh/isomorphism/blob/master/test.out) .

*if you don't want to get input from file or print output to file , *just remove these lines**

```c++
#ifndef ONLINE_JUDGE
freopen(fn".inp","r",stdin);
freopen(fn".out","w",stdout);
#endif // ONLINE_JUDGE
```
