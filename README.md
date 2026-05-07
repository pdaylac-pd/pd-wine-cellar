# PD Wine Cellar

Diário pessoal de vinhos do Patrick — dashboard estático com 67+ vinhos catalogados, mapas de estudo e materiais de apoio.

## Acesso
🌐 **Live:** https://pdaylac-pd.github.io/pd-wine-cellar/

## Stack
- HTML único + Vanilla JS
- Leaflet (mapa de regiões)
- Chart.js (KPIs e análises)
- localStorage (persistência local de edições)

## Features
- Dashboard com KPIs (total degustado, avaliação média, países, uvas, última degustação)
- Adega visual com filtros (país, região, uva, avaliação)
- Cadastro com edição inline em tabela
- Mapa interativo das regiões com cross-link pra mapas de estudo
- **Estudos**: 8 mapas Wine Folly + 7 materiais de apoio (PDFs)
- Upload de foto + leitura automática de data EXIF
- 6 tags de qualidade (Custo Benefício, Dia a Dia, Bom, Ótimo, Vinhasso, Não vale)
- Export/import JSON

## Estrutura
```
pd-wine-cellar/
├── index.html       # Dashboard (single-file)
├── Photos/          # Thumbnails dos vinhos (~800px JPEG)
├── maps/            # Mapas Wine Folly por região
├── materials/       # PDFs de material de apoio
└── README.md
```

## Deploy
Hospedado via GitHub Pages, branch `main`, root.
