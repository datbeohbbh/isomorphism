# isomorphism

see example.png ,we have 2 graphs ,now I will tell you how to get input from file test.inp,and show output in file test.out.

- test.inp contains <b>two</b> sets of graph G and H

  * the first line is number n - the number of vertice
  * the second line is set of two graphs
  * each set of edges is entered until type = -1.

- there are 4 types of edges in graph :
     <ol>
         <li>type = 0 U V: arcs </li>
         <li>type = 1 U V: incident edge</li>
         <li>type = 2 U U : loop</li>
         <li>type = 3 U U: no edges</li>
     </ol>

-so for each vertice u and each its adjacent vertices v,you need to enter corresponding type of edge then u and v.
(see test.inp and test.out for detail)
