# Análise de Entregas de Delivery com Python

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/isracorrea/analise-delivery-python/blob/main/Trilhas2cd.ipynb)

**Aluno:** Israel Nicolas Amorim Corrêa

## Perguntas Investigadas
1. Qual é o horário de maior movimento no delivery?
2. Como o nível de trânsito afeta o tempo médio de entrega?
3. As entregas demoram significativamente mais em dias de tempestade (`Stormy`) do que em dias ensolarados (`Sunny`)?

## Principais Conclusões
- **Pico de demanda:** Entre 19h e 23h, com o maior volume às 21h (4.686 pedidos).
- **Trânsito:** Entregas em congestionamento (`Jam`) levam em média 31,15 min contra 21,28 min em trânsito livre (`Low`).
- **Teste de Hipótese (Clima):** Entregas em tempestade (média de 25,86 min) são estatisticamente mais lentas do que em dias ensolarados (média de 21,85 min), com $p = 9,02 \times 10^{-178}$ (Teste t de Welch).

## Arquivos
- `Trilhas2cd.ipynb`: Notebook completo, executado e comentado.
- `dados/train.csv`: Base de dados original sem alterações.

## Como rodar

### Só para ver
Clique em `Trilhas2cd.ipynb` aqui no GitHub. O notebook aparece com todas as tabelas e gráficos, sem precisar instalar nada.

### No Google Colab
1. Clique no botão **Open in Colab** no topo desta página.
2. Faça o upload da pasta `dados/train.csv` no ambiente do Colab.
3. No menu superior, vá em **Ambiente de execução → Executar tudo**.
 t de Welch).

## Estrutura do Repositório
- `dados/train.csv`: Base de dados original sem alterações.
- `Trilhas2cd.ipynb`: Notebook completo, executado e comentado.
