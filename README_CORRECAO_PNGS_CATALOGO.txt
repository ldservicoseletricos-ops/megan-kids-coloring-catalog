CORREÇÃO — PNGs iniciais do catálogo online

Causa do erro no app:
- O catalog.json estava carregando.
- Mas os links imageUrl apontavam para PNGs que ainda não existiam no GitHub.
- Por isso o app mostrava: "Não consegui baixar este desenho."

Arquivos incluídos:
- github_pages/catalog.json
- github_pages/coloring/animals/panda_fofo.png
- github_pages/coloring/vehicles/carrinho_fofo.png

Depois de subir esses arquivos para o GitHub, teste estes links no navegador:

https://ldservicoseletricos-ops.github.io/megan-kids-coloring-catalog/catalog.json
https://ldservicoseletricos-ops.github.io/megan-kids-coloring-catalog/coloring/animals/panda_fofo.png
https://ldservicoseletricos-ops.github.io/megan-kids-coloring-catalog/coloring/vehicles/carrinho_fofo.png
