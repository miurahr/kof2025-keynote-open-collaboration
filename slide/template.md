---
theme: uncover
html: true
size: 16:9
author: Hiroshi Miura
allowLocalFiles: true
marp: true
paginate: true
---

# Title Page

<script type="module">
  import mermaid from 'https://cdn.jsdelivr.net/npm/mermaid@11/dist/mermaid.esm.min.mjs';
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