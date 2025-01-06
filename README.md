# LLM Transformers

Este repositório contém código e exemplos práticos relacionados ao uso de transformadores, como BERT e RoBERTa, em aplicações de Processamento de Linguagem Natural (NLP). O foco está em demonstrações de como esses modelos podem ser utilizados para resolver problemas comuns em NLP.

## Descrição

O código incluído no repositório explora as seguintes funcionalidades:

- **Treinamento e Fine-Tuning:** Customização de modelos pré-treinados para tarefas específicas, como classificação de texto ou análise de sentimentos.
- **Codificação de Texto:** Conversão de texto em embeddings de alta qualidade usando modelos baseados em transformadores.
- **Avaliação de Modelos:** Métricas para medir a eficiência e precisão de modelos treinados.

### Sobre o BERT e RoBERTa

- **BERT (Bidirectional Encoder Representations from Transformers):** Modelo que analisa o contexto das palavras em ambas as direções (esquerda e direita), sendo ideal para tarefas como preenchimento de lacunas em sentenças e predição de próxima sentença.
- **RoBERTa (Robustly Optimized BERT Pretraining Approach):** Uma versão otimizada do BERT com melhorias como:
  - Remoção da tarefa de predição de próxima sentença.
  - Maior volume de dados e mais épocas de treinamento.
  - Uso de tamanhos maiores de mini-batch e ajustes na taxa de aprendizado.

Essas alterações permitem que o RoBERTa supere o BERT em diversas tarefas, mantendo sua eficiência em diversas aplicações de NLP.

## Estrutura do Repositório

- `llmtransformers.py`: Arquivo principal contendo o código e as implementações dos modelos e experimentos.


