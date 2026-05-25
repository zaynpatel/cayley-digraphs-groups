### Groups, graphs, and morphisms

This repository includes the slides, figures, sources, and `.tex` file for my talk: "Groups, graphs, and morphisms."

The goal of this talk is to demonstrate a relationship between group theory and graph theory. Cayley digraphs of groups is the first topic of the talk. We define Cayley digraphs and see several examples of such structures for well-known groups. During this section we consider two important questions about the relations of a group and think about how a graph can help us find relations. Next, we discuss the Hamiltonicity of Cayley digraphs and prove three theorems about the existence of Hamiltonian circuits and paths in specific groups. The most general, complex, and exciting theorem we prove states that "Finite Abelian groups have a Hamiltonian path in their Cayley digraph." Following this discussion, we learn about the automorphism group of a (non-Cayley) graph and find an isomorphism between the automorphism group of a graph and a well-known group. Lastly, we rigorously define generators and relations by learning about free groups and proving some important theorems about them.

You can [watch the talk on YouTube](https://www.youtube.com/watch?v=bIDwjBnaFsw). The [slides](/GroupsGraphsTalkFullSlides.pdf) were designed to be standalone; this is a good resource too.

### Quick discussion of Geometric Group Theory
In a [blog post about Cayley graphs](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/), written by Terence Tao, Tao mentions that most undergraduate courses introduce groups as an algebraic concept: a set with a single binary operation that satisfies [four group axioms](https://en.wikipedia.org/wiki/Universal_algebra#Groups). This is how I learned the definition of a group. But he shares, [in a different post](https://terrytao.wordpress.com/2009/10/19/grothendiecks-definition-of-a-group/), that we can think about groups from at least eight other perspectives. 

One of these perspectives is ["presentation-theoretic"](https://en.wikipedia.org/wiki/Presentation_of_a_group) which we covered in this talk; we thought about groups given by a set of generators and relations and used this to form a group presentation. When we considered a group's presentation we immediately had more structure to understand how specific elements (e.g. generators) behave in the group. Furthermore, we learned that if two groups have the same presentation they are isomorphic but it is possible for two isomorphic groups to be defined by different presentations. The latter point is because we may have a choice about which generating set we use for $G$ and this may result in a different presentation. If we determine a presentation for an arbitrary group $G$ and recognize that this presentation matches one for a familiar group, for example, $D_{4}$ then we may conclude that $G \cong D_{4}$. This allows us to apply known results about $D_{4}$ to $G$. You can imagine a situation where it is hard to think about $G$ from the purely algebraic perspective but it is simpler from the presentation-theoretic perspective.

Tao mentions that we can consider groups ["with some geometry"](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/), hence the development of geometric group theory. An important idea in [geometric group theory](https://en.wikipedia.org/wiki/Geometric_group_theory) is to consider finitely generated groups (e.g. $A_{4}$, $\mathbb{Z}_6$, $S_{3}$) as geometric objects.

To study a group geometrically we need to define a notion of distance between points, which we will call a metric, and a structure where we can apply the metric. Cayley digraphs of groups are a commonly chosen structure for this purpose; each element of $G$ is a vertex of the graph and the generators are directed edges. We define the [word metric](https://en.wikipedia.org/wiki/Word_metric) as the measure between any $g, h \in G$. We denote this distance $d(g, h)$ and it measures how efficiently the difference between two words $g^{-1}h$ [can be expressed as another word in $G$ whose letters come from a generating set $S$ for the group](https://en.wikipedia.org/wiki/Word_metric). Said another way, we are interested in the smallest number of insertions or deletions in the difference $g^{-1}h$ such that we can express this as another word in the group.

In the appendix of the talk we defined terms like word, letters, and insertions/deletions in the context of free groups. Recall that given some set of distinct symbols $S$ (which we later defined as the generators) we create a new set $S^{-1}$ by replacing each element of $S$ with its inverse. Then we defined $W(S)$ to be the set of all finite strings of the form $x_{1}x_{2}...x_{k}$ where each $x_{i}$ in these finite strings was an element of $W(S)$. We called this the set of words from $S$ and we learned that every element of $G$ can be written as a word. We can then study the geometry of the digraph instead of the algebraic properties of $G$. This gives us another perspective to analyze a group.

Tao gives another example where one can [see the Cayley graph](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/) of $\mathbb{Z}_{6}$ as one or two dimensional using some topology too.

There is significantly more theory and ongoing research in the branch of mathematics called geometric group theory. The purpose of this section was to introduce the role of Cayley digraphs in geometric group theory and also provide new perspectives to think about a group.

**Acknowledgements:**
- Thank you Dr. Mann for your time and willingness to dive into the details of Theorem 28.3, equivalence relations of words, and other topics in this presentation. I left all of our meetings with more clarity about these results.
- Thank you Dr. Joseph A. Gallian for writing a sublime Abstract Algebra textbook and specifically for the exposition on generators and relations and Cayley Digraphs of Groups.
- Thank you to the authors of the many online sources I used and learned from while creating this talk. I have linked their work in the [SOURCES.md](/SOURCES.md) file of this GitHub repository.

---
No LLM assistance was used in this project, for anything.

Please reach out to me if you would like to learn more about the things I learned while making this talk or if you have questions about abstract algebra. I would love to help if I can. If you have any feedback on the talk please send me an email.

Contact: zaynpatelwhs@gmail.com