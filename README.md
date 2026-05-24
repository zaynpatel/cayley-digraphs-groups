### Groups, graphs, and morphisms

This repository includes the slides, figures, sources, and `.tex` file for my talk: "Groups, graphs, and morphisms."

The goal of this talk is to demonstrate a relationship between group theory and graph theory. Cayley digraphs of groups is the first topic of the talk. We define Cayley digraphs and see several examples of such structures for well-known groups. During this section we consider two important questions about the relations of a group and think about how a graph can help us find relations. Next, we discuss the Hamiltonicity of Cayley digraphs and prove three theorems about the existence of Hamiltonian circuits and paths in specific groups. The most general, complex, and exciting theorem we prove states that "Finite Abelian groups have a Hamiltonian path in their Cayley digraph." Following this discussion, we learn about the automorphism group of a (non-Cayley) graph and find an isomorphism between the automorphism group of a graph and a well-known group. Lastly, we rigorously define generators and relations by learning about free groups and proving some important theorems about them.

You can [watch the talk on YouTube](). The [slides](/GroupsGraphsTalkFull.pdf) were designed to be standalone; this is a good resource too.

### Quick discussion of Geometric Group Theory
In a [blog post about Cayley graphs](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/), written by Terence Tao, Tao mentions that most undergraduate courses introduce groups as an algebraic concept: a set with a single binary operation that satisfies [four group axioms](https://en.wikipedia.org/wiki/Universal_algebra#Groups). This is how I learned the definition of a group. But he shares, [in a different post](https://terrytao.wordpress.com/2009/10/19/grothendiecks-definition-of-a-group/), that we can think about groups from at least eight other perspectives. 

One of these perspectives is ["presentation-theoretic"](https://en.wikipedia.org/wiki/Presentation_of_a_group) which we covered in this talk; we thought about groups given by a set of generators and relations and used this to form a group presentation. When we considered a group's presentation we immediately had more structure to understand how specific elements (e.g. generators) behave in the group. Furthermore, we learned that a group presentation determines a group up to isomorphism, although isomorphic groups might have different presentations. If we determine a presentation for an arbitrary group $G$ and recognize that this presentation matches one for a familiar group such as $D_{4}$, we may conclude that $G \cong D_{4}$. This allows us to transfer known results about $D_{4}$ to $G$. You can imagine a situation where it is hard to think about $G$ from the purely algebraic perspective but it is simpler from the presentation-theoretic perspective.

Tao mentions that we can consider groups ["with some geometry"](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/). This is the purpose of [geometric group theory](https://en.wikipedia.org/wiki/Geometric_group_theory). To study a finitely-generated group geometrically we define a metric to measure of distance between elements in the group. We use the [word metric](https://en.wikipedia.org/wiki/Word_metric). Given a generating set $S$, we form the alphabet $S \cup S^{-1}$. A word is a finite sequence of symbols from this alphabet. In a Cayley digraph of $G$ the word metric measures the length of the shortest path between two elements of $G$. Tao gives a specific example of [seeing the Cayley graph](https://terrytao.wordpress.com/2010/07/10/cayley-graphs-and-the-geometry-of-groups/) of $\mathbb{Z}_{6}$ as one or two dimensional.

There is much more theory and research in the field of geometric group theory. The purpose of this section was to introduce the role of Cayley digraphs in geometric group theory and also expose you to other ways to think about a group.

**Acknowledgements:**
- Thank you Dr. Mann for your time and willingness to dive into the details of Theorem 28.3, equivalence relations of words, and other topics in this presentation. I left all of our meetings with more clarity about these results.
- Thank you Dr. Joseph A. Gallian for writing a sublime Abstract Algebra textbook and specifically for the exposition on generators and relations and Cayley Digraphs of Groups.
- Thank you to the authors of the many online sources I used and learned from while creating this talk. I have linked their work in the [SOURCES.md](/SOURCES.md) file of this GitHub repository.

---
No LLM assistance was used in this project, for anything.

Please reach out to me if you would like to learn more about the things I learned while making this talk or if you have questions about abstract algebra. I would love to help if I can. If you have any feedback on the talk please send me an email.

Contact: zaynpatelwhs@gmail.com