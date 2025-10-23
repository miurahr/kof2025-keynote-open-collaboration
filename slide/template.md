---
theme: uncover
marp: true
paginate: true
---

# **Hello World**

---

# How to write slides

Split pages by horizontal ruler (`---`). It's very simple! :satisfied:

? Foot notes

---

# Title Page

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@10/dist/mermaid.esm.min.mjs';
  mermaid.initialize({ startOnLoad: true });
</script>

---

# Diagram
<div class="mermaid">
  graph LR;
  a --> b;
  b --> c;
  c --> a;
</div>

---