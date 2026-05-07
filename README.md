# PD Wine Cellar

Diário pessoal de vinhos do Patrick — dashboard estático com 67+ vinhos catalogados.

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
- Mapa interativo das regiões
- Upload de foto + leitura automática de data EXIF
- 6 tags de qualidade (Custo Benefício, Dia a Dia, Bom, Ótimo, Vinhasso, Não vale)
- Export/import JSON

## Estrutura
```
pd-wine-cellar/
├── index.html       # Dashboard (single-file)
├── Photos/          # Thumbnails dos vinhos (~800px JPEG)
└── README.md
```

## Deploy
Hospedado via GitHub Pages, branch `main`, root.
