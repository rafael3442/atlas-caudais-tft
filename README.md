# Atlas de Caudais TFT

https://rafael3442.github.io/atlas-caudais-tft/

Mapa interativo das bacias naturais de Portugal continental estudadas em Francisco e Matos (2026),
*Streamflow prediction in natural ungauged catchments using Temporal Fusion Transformers*.
Para cada bacia: precipitação, temperatura e caudal diário observado, previsto pelo TFT
(modelo selecionado no artigo, antecedência de 3 dias) e simulado pelo HBV calibrado na bacia,
em condições de bacia não monitorizada ou após especialização.

Dados e resultados: [FORESIGHT-ULisboa/streamflow-portugal-ungauged](https://github.com/FORESIGHT-ULisboa/streamflow-portugal-ungauged).

Site estático, sem compilação: `index.html`, `meta.json` (bacias e métricas), `map.json`
(geometria) e `data/<estação>.txt` (séries diárias, Uint16 comprimidas com zlib e em base64).
