# TAIÓ — Webmap

Mapa em tela cheia com zoom/pan contínuo (Leaflet, HTML autônomo — precisa de
internet pra carregar os tiles) do sistema intrusivo de Taió (SC): pontos de campo,
mapa geológico real (CPRM), sill/dique, dados estruturais, camadas de referência
(rios/estradas/localidades) e basemap de hipsometria com sombreamento de relevo.

Abra `webmap_taio.html` direto no navegador.

Identidade visual TAIÓ — Sistema Intrusivo · Plumbing System. Complemento dos outros
produtos: [TPS_HUB](https://github.com/TPlumbingSystem/TPS_HUB) (página inicial),
[TPS_MOD3D](https://github.com/TPlumbingSystem/TPS_MOD3D),
[TPS_SEC2D](https://github.com/TPlumbingSystem/TPS_SEC2D),
[TPS_DASH](https://github.com/TPlumbingSystem/TPS_DASH).

Gerado por `gerar_webmap_taio.py` (Python, GeoPandas) — depende dos dados do
projeto completo, não roda de forma standalone fora dessa estrutura; incluído aqui
como referência/histórico do código.
