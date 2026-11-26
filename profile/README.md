# Formal phylogenetics

Lean 4 formalizations of papers in phylogenetics, on top of Mathlib. Each paper is formalized with
the [formalize-math-paper](https://github.com/vltanh/formalize-math-paper) skill: its results are
proved by the paper's own arguments, and an audit reports its errors and gaps.

The collection is rooted at
[lean4-phylogenetics](https://github.com/formal-phylogenetics/lean4-phylogenetics), which holds the
library `Phylogenetics` that every repository shares, the registry of the repositories, the
conventions and the tools. Its README shows the tree of the hubs. A hub holds a library for what its
papers share and the catalog of the papers it covers, and its README has the checklist of those
papers, with their repositories. The site
[formal-phylogenetics.vltanh.me](https://formal-phylogenetics.vltanh.me/) draws the whole tree, with
a card for each entry of the catalogs.

The hubs of inference, on estimating alignments, trees and networks from data, and placing new
sequences on trees:

- [lean4-phylo-alignment](https://github.com/formal-phylogenetics/lean4-phylo-alignment): sequence
  alignment;
- [lean4-phylo-gene-tree](https://github.com/formal-phylogenetics/lean4-phylo-gene-tree): gene tree
  estimation;
- [lean4-phylo-species-tree](https://github.com/formal-phylogenetics/lean4-phylo-species-tree):
  species tree estimation;
- [lean4-phylo-network](https://github.com/formal-phylogenetics/lean4-phylo-network): phylogenetic
  network estimation, with the library
  [lean4-phylo-tree-of-blobs](https://github.com/formal-phylogenetics/lean4-phylo-tree-of-blobs) of
  its papers on the tree of blobs of a phylogenetic network;
- [lean4-phylo-placement](https://github.com/formal-phylogenetics/lean4-phylo-placement): phylogenetic
  placement, and the phylogenetic metagenomics that rests on it.

The hubs of theory:

- [lean4-phylo-combinatorics](https://github.com/formal-phylogenetics/lean4-phylo-combinatorics):
  the combinatorics of phylogenetic trees and networks;
- [lean4-phylo-algebraic](https://github.com/formal-phylogenetics/lean4-phylo-algebraic): algebraic
  phylogenetics;
- [lean4-phylo-statistics](https://github.com/formal-phylogenetics/lean4-phylo-statistics): the
  statistical theory of phylogenetic inference;
- [lean4-phylo-geometry](https://github.com/formal-phylogenetics/lean4-phylo-geometry): phylogenetic
  geometry.

Maintainer: The-Anh Vu-Le.
