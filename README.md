<h1 align="left">
  Lean-QIT Declarations
  <a href="https://leanqit-catalog.pages.dev" style="font-size: 0.5em; vertical-align: middle;">[live]</a>
</h1>

The complete set of declarations from [Lean-QIT](https://github.com/QuAIR/Lean-QIT),
extracted as a machine-readable dataset, and a catalog for browsing them.

### at: **[leanqit-catalog.pages.dev](https://leanqit-catalog.pages.dev)**

## Table of Contents

- [Credit](#credit)
- [This Project](#this-project)
- [The Catalog](#the-catalog)
  - [Browse](#browse)
  - [Declaration pages](#declaration-pages)
  - [Modules and namespaces](#modules-and-namespaces)
  - [Stats](#stats)
  - [About](#about)
- [Licence and status](#licence-and-status)

## Credit

Lean-QIT is a Lean 4 library formalizing finite-dimensional quantum information
theory, including machine-checked proofs of Schumacher's source-coding theorem,
the Holevo-Schumacher-Westmoreland classical capacity theorem, and the
entanglement-assisted classical capacity theorem.

Everything of mathematical substance here, meaning every theorem, definition,
type signature and docstring, is the work of its authors:

> **Lean-QIT: Towards a Formal Infrastructure for Quantum Information Theory**
> Chengkai Zhu, Ziao Tang, Guocheng Zhen, Yimeng Cao, Yusheng Zhao,
> Ranyiliu Chen, Xuanqiang Zhao, Lei Zhang, Xin Wang
>
> QudeLeap Research; The Hong Kong University of Science and Technology (Guangzhou);
> Quantum Science Center of the Guangdong-Hong Kong-Macao Greater Bay Area;
> The University of Hong Kong
>
> Repository: <https://github.com/QuAIR/Lean-QIT>
> Paper: [arXiv:2607.09632](https://arxiv.org/abs/2607.09632)
> Theorem Catalog: <https://www.quairkit.com/Lean-QIT/>

Copyright (c) 2026 QuAIR, released under the Apache License 2.0. See
[`NOTICE`](NOTICE) for the attribution and the statement of changes, and
[`LICENSE-Lean-QIT`](LICENSE-Lean-QIT) for the licence text.

**If this is useful to you, cite the library:**

```bibtex
@misc{zhu2026leanqit,
  title = {Lean-QIT: Towards a Formal Infrastructure for Quantum Information Theory},
  author = {Chengkai Zhu and Ziao Tang and Guocheng Zhen and Yimeng Cao and Yusheng Zhao and Ranyiliu Chen and Xuanqiang Zhao and Lei Zhang and Xin Wang},
  year = {2026},
  eprint = {2607.09632},
  archivePrefix = {arXiv},
  primaryClass = {quant-ph},
  url = {https://arxiv.org/abs/2607.09632}
}
```

QuAIR also publish a hand-curated
[Theorem Catalog](https://www.quairkit.com/Lean-QIT/) covering the library's
headline results with readable mathematical statements and literature citations.
That is the place to start if you want to understand the library. This project
answers a different question: where is everything, and what is it called.


## This Project

Lean-QIT contains 9,696 declarations across 289 modules. Finding any particular
one previously meant reading the source or knowing where to look.

This project extracted all of them with
[doc-gen4](https://github.com/leanprover/doc-gen4), Lean's official
documentation generator, decoded and verified the output, and published it two
ways: as a dataset you can query directly, and as a website you can search.

## The Catalog

### Browse

Search across all 9,696 declarations by name, signature or docstring. Filter by
kind, by library area, by whether a docstring exists, by attributes. Results are
ranked by how often a declaration is referenced, so the foundational parts of
the library surface first. Search runs entirely in the browser against a
prebuilt index, so it responds as you type.

### Declaration pages

Every declaration has its own page at a stable URL derived from its Lean name,
for example `#/decl/QIT.State.vonNeumann`. Each shows the full type signature
with implicit and instance binders dimmed, the docstring as its authors wrote
it, the exact `import` line, a link to the source at the right line, and the
references in both directions.

### Modules and namespaces

Two different views of the same library, because they answer different
questions. **Modules** are files: 289 of them, grouped by area, each with its
documentation coverage. A module name is what goes after `import`.
**Namespaces** are mathematical objects: `QIT.State` gathers everything about
states regardless of which file it lives in. This is how you think about the
library, while modules are how you import from it.

### Stats

Coverage and shape of the library measured on the snapshot: 71.6% of
declarations carry a docstring, none are marked `sorry`, and the reference graph
has 34,735 in-library edges out of 93,077 total. Also the least-documented
modules and the most-referenced declarations.

### About

Attribution, citation, how the data was produced, and the caveats worth knowing
before relying on any of it.

## Licence and status

The dataset, downloadable from the catalog, is Lean-QIT material: Copyright (c)
2026 QuAIR, under [Apache-2.0](LICENSE-Lean-QIT). Use it under those terms, keep
the attribution, and cite the paper.

No licence is granted for this project's own contribution, meaning the
extraction pipeline and the website. That work is unpublished and all rights are
reserved.

This is an independent project. It is not maintained by QuAIR.
