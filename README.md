# Random Forest implementada do zero

Implementação de uma Random Forest em Python puro, sem usar o modelo pronto do scikit-learn, para entender por dentro como o algoritmo funciona.

## O que foi implementado

- **Impureza de Gini** para avaliar a qualidade de cada divisão
- **Escolha da melhor característica** para dividir cada nó
- **Árvore de decisão recursiva** com profundidade máxima configurável
- **Bootstrap** para gerar amostras diferentes para cada árvore
- **Votação por maioria** entre as árvores para a previsão final
- **Avaliação** com matriz de confusão, sensibilidade, especificidade e precisão

## Tecnologias

Python · Pandas · NumPy · SciPy · scikit-learn (apenas para divisão treino/teste e métricas) · Google Colab

## Estrutura

```
random_forest_do_zero.ipynb   notebook com a implementação e os testes
```

## Autora

Rita Farias · [LinkedIn](https://www.linkedin.com/in/rita-farias-b24a33232/)
