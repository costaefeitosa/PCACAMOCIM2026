# PCA Camocim 2026 — Painel Web

Painel estático com o Plano de Contratações Anual 2026 do Município de Camocim/CE.

## Conteúdo
- `index.html` — painel completo (640 itens, R$ 294 milhões), com brasão oficial embutido, dropdowns de visualização, KPIs, gráficos e tabela detalhada filtrável
- `vercel.json` — configuração de headers de cache e segurança

## Como rodar localmente
Abrir o `index.html` em qualquer navegador moderno (Chrome, Safari, Firefox).

## Como publicar na Vercel
```bash
npm i -g vercel
cd pca-camocim-2026
vercel
```

## Atualizar dados
Substituir o conteúdo de `index.html` pela nova versão gerada e rodar `vercel --prod`.
