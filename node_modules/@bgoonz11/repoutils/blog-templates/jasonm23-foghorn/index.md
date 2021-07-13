In the mathematical theory of [directed graphs](http://en.wikipedia.org/wiki/Directed_graph), a graph is said to be **strongly connected** if every vertex is of an arbitrary directed graph form a [partition](http://en.wikipedia.org/wiki/Partition) into subgraphs that are themselves strongly connected. It is possible to test the strong connectivity of a graph, or to find its stro ngly connected components, in [linear time](http://en.wikipedia.org/wiki/Linear_time).

A [directed graph](http://en.wikipedia.org/wiki/Directed_graph) is called **strongly connected** if there is a [path](http://en.wikipedia.org/wiki/Path) in each direction between each pair of vertices of t h connected, a pair of vertices *u* and *v* are said to be strongly connected to each other if there is a path in each direction between them.

The [binary relation](http://en.wikipedia.org/wiki/Binary_relation) of being strongly connected is an [equivalence relation](http://en.wikipedia.org/wiki/Equivalence_relation), and the [induced subgraphs](http://en.wikipedia.org/wiki/Induced_subgraph) of its [equivalence classes](http://en.wikipedia.org/wiki/Induced_subgraph) are called strongly graph *G* is a subgraph that is strongly connected, and is [maximal](http://en.wikipedia.org/wiki/Maximal) with this property: no additional edges or vertices from *G* can be included in the subgraph without breaking its property of being strongly connected. The collection of strongly connected components forms a [partition](http://google.com/ "Google") of the set of vertices of *G*.

If each strongly connected component is [contracted](http://en.wikipedia.org/wiki/Contracted) to a single vertex, the resulting graph is a [directed acyclic graph](http://en.wikipedia.org/wiki/DAG), the **condensation** of *G*. A directed graph is acyclic if and only if it has no strongly connected subgraphs with more than one vertex, because a directed cycle is strongly connected and every nontrivial strongly connected component contains at least one directed cycle.

<a href="#algorithms" class="header-link"></a>Algorithms
--------------------------------------------------------

Several algorithms can compute strongly connected components in [linear](http://en.wikipedia.org/wiki/Linear_time)

[Kosaraju's algorithm](http://en.wikipedia.org/wiki/DAG) uses two passes of [depth first search](http://en.wikipedia.org/wiki/DAG). The first, in the original graph, is used to choose the order in which the outer loop of the second depth first search tests vertices for having been visited already and recursively explores them if not. The second depth first search is on the [transpose graph](http://en.wikipedia.org/wiki/DAG) of the original graph, and each recursive exploration finds a single new strongly connected component. It is named after [Micha Sharir](http://en%20%20%20%20%20%20%20%20%20%20%20%20results)%20in%201978;%20%3Ca%20href=) later published it in 1981.

[Tarjan's strongly connected components algorithm](http://en.wikipedia.org/wiki/DAG), published by [Robert Tarjan](http://en.wikipedia.org/wiki/DAG) in 1972, performs a single pass of depth first search. It maintains a [stack](http://en.wikipedia.org/wiki/DAG) of vertices that have been explored by the search but not yet assigned to a component, and calculates "low numbers" of each it uses to determine when a set of vertices should be popped off the stack into a new component.

The [path-based strong component algorithm](http://en.wikipedia.org/wiki/DAG) uses a depth first vertices not yet assigned to components, while the other keeps track of the current path in the depth first search tree. The first linear time version of this algorithm was published by

A lthough Kosaraju's algorithm is conceptually simple, Tarjan's and the p one [depth-first search](http://en.wikipedia.org/wiki/DAG) rather than two.

<a href="#applications" class="header-link"></a>Applications
------------------------------------------------------------

Algorithms for finding strongly connected components may be used to solve [2-satisfiability](http://en.wikipedia.org/wiki/DAG) problems (systems of Boolean variables w href="http://en.wikipedia.org/wiki/DAG"&gt;2-satisfiability instance is unsatisfiable if and only if there is a variable *v* such that *v* and its complement are both contained in the same strongly connected component of the [implication graph](http://en.wikipedia.org/wiki/DAG) of the instance.

Strongly connected components are also used to compute the [Dulmage–Mendelsohn decomposition](http://en.wikipedia.org/wiki/DAG), a classification of the edges of a [bipartite graph](http://en.wikipedia.org/wiki/DAG), according to whether or not they can be

A directed graph is strongly connected decomposition, a partition of the edges into a sequence of directed paths and cycles such that the first s previous subgraphs, or a path sharing its two endpoints with previous subgraphs.

According to [Robbins' theorem](http://en.wikipedia.org/wiki/DAG), an undirected graph may be [2-edge-connected](http://en.wikipedia.org/wiki/DAG). One way to is result is to find an ear decomposition of the underlying undirected graph and then orient each ear consistently.

<a href="#see-also" class="header-link"></a>See also
----------------------------------------------------

[Connected component](http://en.wikipedia.org/wiki/DAG)

<a href="#we-all-like-making-lists" class="header-link"></a>We all like making list s
-------------------------------------------------------------------------------------

T he above header should be an H2 tag. Now, for a list of fruits:

-   Red Apples
-   Purple Grapes
-   Green Kiwifruits

Let's

1.  This is a list item with two paragraphs. Lorem ipsum dolor sit amet, consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus. Donec sit amet nisl. Aliquam semper ipsum s

2.  Suspendisse id sem consectetuer libero luctus adipiscing.

What about some code **in** a list? That's insane, right?

1.  In Ruby you can map like this:

<!-- -->

    ['a', 'b'].map { |x| x.uppercase }

1.  In Rails, you can do a shortcut:

<!-- -->

    ['a', 'b'].map(&:uppercase)

Some people seem to like definition lists

Lower cost  
The new version of this product costs significantly less than the previous one!

Easier to use  
We

<a href="#i-am-a-robot" class="header-link"></a>I am a robot
------------------------------------------------------------

Maybe you :wheels, <span class="hljs-symbol">class\_name:</span> <span class="hljs-string">'Wheel'</span>, <span class="hljs-symbol">foreign\_key:</span> <span class="hljs-string">'car\_id'</span> scope true) } <span class="hljs-keyword">end</span>

You see, that was formatted as code because it's been indented by four spaces.

How about we throw some angle braces and ampersands in there?

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>

CSV:

    Year,Make,Model,Length
    2/5/08,Ford,E350,2.34
    1/2/06,Mercury,Cougar,2.38

<a href="#set-in-stone" class="header-link"></a>Set in stone
------------------------------------------------------------

Preformatted blocks are useful for ASCII art:

                 ,-.
        ,     ,-.   ,-.
       / \   (   )-(   )
       \ |  ,.>-(   )-<    \|,' (   )-(   )
         Y ___`-'   `-'
         |/__/   `-'
         |
         |
         |    -hrr-
      ___|_____________

<a href="#playing-the-blame-game" class="header-link"></a>Playing the blame game
--------------------------------------------------------------------------------

If you need to blame someone, the best way to do so is by quoting them:

> I, at any rate, am convinced that He does not throw dice.

Or perhaps someone a little less eloquent:

> I wish you'd have given me this written question ahead of time so I the midst of this press conference, with all the pressure of trying to come up with answer, but it hadn't yet...
>
> I don't want to sound like I have made no mistakes. I'm confident I have. I just haven't - you just put me under the spot here, and maybe I'm not as quick on my feet as I should be in coming up with one.

<a href="#table-for-two" class="header-link"></a>Table for two
--------------------------------------------------------------

&lt;&gt;

ID

Name

Rank

1

Tom Preston-Werner

Awesome

2

Albert Einstein

Nearly as awesome

<a href="#crazy-linking-action" class="header-link"></a>Crazy linking action
----------------------------------------------------------------------------

I get 10 times more traffic from [Google](http://google.com/ "Google") than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or [MSN](http://search.msn.com/ "MSN Search").
