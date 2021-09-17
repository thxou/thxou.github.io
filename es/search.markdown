---
layout: page
title: Buscar
permalink: es/buscar/
lang: es
lang-ref: search
---

<!-- Html Elements for Search -->
<div id="search-container">
<input type="text" id="search-input" placeholder="Empieza a escribir...">
<br />
<br />
<div id="results-container"></div>
</div>

<!-- Script pointing to search-script.js -->
<script src="/js/search-script.js" type="text/javascript"></script>

<!-- Configuration -->
<script type="text/javascript">
SimpleJekyllSearch({
  searchInput: document.getElementById('search-input'),
  resultsContainer: document.getElementById('results-container'),
  json: '/json/search-es.json'
})
</script>