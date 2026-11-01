# Designation Causal Diagram

An interactive causal diagram for a thesis design: the effect of a FEMA major-disaster hurricane declaration on where
displaced students' families land (doubled-up, hotel or motel, shelter, unsheltered) and how long each rung of student
homelessness stays elevated, compared with same-state counties the storm left undeclared.

**Live page:** https://brynhild-chale.github.io/DesignationCausalDiagram/

Drawn after Huntington-Klein, *The Effect* (2021), ch. 7, "Drawing Causal Diagrams".

- **Expand and contract** from the minimal diagram (the paper's Figure 1) to everything considered: mediators opened,
  merged nodes split, nodes removed as irrelevant shown with the reason.
- **Click a node, an arrow or a dataset** for its card: what collapsed into a node, the assumption behind an arrow, and
  links out to the data.
- **Deep links:** `#level=0..3`, `#node=<id>`, `#ds=<id>[,<id>]`, `#edge=<from>-<to>`, `#open=<id>[,..]|all`.

The page is one self-contained HTML file with its data inlined: no build step, no external scripts.
Diagram built with Claude from the author's design decisions.
