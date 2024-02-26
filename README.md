# Reid Atcheson


My name is Reid Atcheson. I have a PhD in Computational and Applied Mathematics (CAAM) from Rice University. I am a Research Engineer at [Aquatic Capital Management](https://aquatic.com/).
I work on software for technical computing, numerical analysis, and linear algebra.
I also have interest in programming languages and currently am very excited about [Rust](https://www.rust-lang.org/), but I have also used
a wide variety of other lanugages such as Haskell,Ocaml,SML, and I have even done a little with dependently typed languages such as Coq.



# How I use GitHub

I do many experiments, usually in a scripting language such as Julia or Python. I will experiment with algorithm concepts, novel ideas, potentially new mathematics.
Most of my repositories are private but even the ones which are public are not curated for production use but rather as a starting place for discussions with others.
If you are interested in a more curated view of my work with careful explanation (including code) explained you can [visit my website](https://www.reidatcheson.com/).


# Structure of my Experiments

Most of my experiments take the following form:

  1. A simple proof-of-concept algorithm
  2. A random sampling of problems from a well-defined problem space (e.g. sparse symmetric matrices)
  3. Statistical analysis of results compared to a benchmark algorithm


Before I invest more research into a new algorithm I try to find statistically significant differences between that novel algorithm concept
and a classical or commonly used algorithm for the same problem. I usually measure the following

  1. Execution time
  2. Memory cost
  3. Accuracy
  4. Arithmetic throughput (FLOPS)
  5. Memory throughput (bandwidth)


Often if an algorithm can deliver considerably better results on any single one of these factors then it will have some environment or platform which favors it.
