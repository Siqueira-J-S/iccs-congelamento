# Congelamento do ICCS

Este repositório guarda as assinaturas do congelamento do Índice de Condições de Crédito Setorial (ICCS), um indicador setorial para a economia brasileira feito com dados públicos e metodologia aberta.

O congelamento foi gravado em 2026-11-10T19:36:55Z (UTC), com data de congelamento 2026-11-10. O `MANIFESTO.json` (SHA-256 `0731222bb8f50266d2dff5884bcc4705c9c078f3878af8a54aebb72330a4b09e`) traz o SHA-256 de cada arquivo congelado: a metodologia, o código de construção, o programa da avaliação e a lista de testes. Os arquivos em si não estão aqui; quando forem publicados, qualquer pessoa poderá conferir, na pasta do ICCS, que são os mesmos:

```
sha256sum -c assinaturas.txt
```

`estado_no_congelamento.txt` registra, sem travar, o estado do dia, como o painel da base usado na avaliação de 2020 em diante; alguns desses arquivos mudam por desenho depois do congelamento. `registro_congelamento.md` descreve o congelamento e os próximos passos. Depois desta data, qualquer mudança no método é uma emenda datada e assinada, registrada antes do cálculo que ela afeta.
