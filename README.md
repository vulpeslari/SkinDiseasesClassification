# Classificação de doenças de pele

O objetivo geral deste trabalho se voltou à classificação multi-classe de nove doenças dermatológicas, mediante as classes presentes no [PUMCH_ISD dataset](https://www.kaggle.com/datasets/jcwang10000/pumch-isd), que são: 
- Acne vulgaris
- Dermatite (dois subsets distintos)
- Lichen planus (líquen plano)
- Morphea (morfeia/esclerodermia localizada)
- Pityriasis rosea (pitiríase)
- Psoriase
- Rosacea
- Vitiligo

A classificação foi voltada a dispositivos embarcados, com menor capacidade de recurso e desempenho, e, por isso, os modelos de treinamento escolhidos eram igualmente menores. Foram testados quatro modelos de redes convolucionais (`ShuffleNet`, `MobileNet`, `EfficientNetV2B0` e `EffNet`) com as imagens dermatoscópicas da base de dados. O desempenho de cada rede está representado em um jupyter notebook correspondente. Como métricas de avaliação, selecionou-se *precision*, *recall* e *f1-score*, sendo esta ultima a métrica principal escolhida para a análise do problema.

## Integrantes
- Adriano Henrique de Souza Andrade (2115310028)
- Felipe Peres de Almeida (2015310070)
- Guilhermo Aguiar Ferreira (1415170016)
- Jorge Henrique Borges Santos (2215310039)
- Júlio César Pinheiro de Araújo (2215310015)
- Larissa de Souza Costa (2215310042)
- Vitor Hugo Trovão de Moraes
