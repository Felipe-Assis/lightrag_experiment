
# LightRAG Experiment

## Description (English)
This experiment leverages the **LightRAG** framework to evaluate and compare knowledge graphs generated using two language models:
1. **Quantized Llama 3.1 8B** - a compact, quantized large language model.
2. **GPT Mini** - a smaller, efficient GPT model.

### Goals:
- **Graph Generation**: Generate knowledge graphs from textual data using LightRAG.
- **Comparison**: Evaluate differences in generated graphs and underlying documents.
- **Visualization**: Create clear visual representations of the graphs for insights.

### Experiment Steps:
1. **Data Preparation**: Curated textual datasets from multiple domains.
2. **Graph Generation**: Used LightRAG to generate knowledge graphs.
3. **Visualization**: Employed visualization tools to interpret the structure and content of graphs.
4. **Comparative Analysis**: Compared graph structures and document alignments between models.

### Requirements:
- **Python Environment**: Ensure Python 3.8 or later is installed.
- **Dependencies**:
  Key Python packages and their uses:
  - **transformers (4.46.3)**: For utilizing and fine-tuning language models.
  - **datasets (3.1.0)**: For managing and processing textual datasets.
  - **networkx (3.4.2)**: For handling and visualizing graph structures.
  - **torch (2.3.1)**: As the foundational library for PyTorch-based model operations.
  - **matplotlib-inline**: Enables inline plotting in Jupyter Notebook.
  - **numpy (2.1.3)** and **pandas (2.2.3)**: For data manipulation and analysis.

  Install all dependencies using the `requirements.txt` file:
  ```bash
  pip install -r requirements.txt
  ```
- Fork the [LightRAG repository](https://github.com/HKUDS/LightRAG) and clone it locally to execute the Jupyter notebook.
- Ensure Jupyter Notebook is installed and accessible.

### Recommended Hardware:
- GPU-enabled environment for efficient processing of large language models.
- Adequate memory to handle large datasets and graph visualizations.

---

## Descrição (Português)
Este experimento utiliza o framework **LightRAG** para avaliar e comparar grafos de conhecimento gerados utilizando dois modelos de linguagem:
1. **Llama 3.1 8B Quantizado** - um modelo de linguagem grande e compacto.
2. **GPT Mini** - um modelo GPT menor e eficiente.

### Objetivos:
- **Geração de Grafos**: Criar grafos de conhecimento a partir de dados textuais usando o LightRAG.
- **Comparação**: Avaliar diferenças nos grafos gerados e nos documentos subjacentes.
- **Visualização**: Criar representações visuais claras dos grafos para obter insights.

### Etapas do Experimento:
1. **Preparação dos Dados**: Conjuntos de dados textuais organizados de múltiplos domínios.
2. **Geração de Grafos**: Uso do LightRAG para gerar grafos de conhecimento.
3. **Visualização**: Ferramentas de visualização para interpretar a estrutura e o conteúdo dos grafos.
4. **Análise Comparativa**: Comparação das estruturas dos grafos e alinhamentos de documentos entre os modelos.

### Requisitos:
- **Ambiente Python**: Certifique-se de que o Python 3.8 ou posterior esteja instalado.
- **Dependências**:
  Principais pacotes Python e suas utilizações:
  - **transformers (4.46.3)**: Para utilização e ajuste fino de modelos de linguagem.
  - **datasets (3.1.0)**: Para gerenciar e processar conjuntos de dados textuais.
  - **networkx (3.4.2)**: Para manipulação e visualização de estruturas de grafos.
  - **torch (2.3.1)**: Biblioteca base para operações com modelos em PyTorch.
  - **matplotlib-inline**: Para plotagens inline no Jupyter Notebook.
  - **numpy (2.1.3)** e **pandas (2.2.3)**: Para manipulação e análise de dados.

  Instale todas as dependências usando o arquivo `requirements.txt`:
  ```bash
  pip install -r requirements.txt
  ```
- Fork do [repositório LightRAG](https://github.com/HKUDS/LightRAG) e clonagem local para executar o Jupyter Notebook.
- Certifique-se de que o Jupyter Notebook esteja instalado e acessível.

### Hardware Recomendado:
- Ambiente com suporte a GPU para processamento eficiente de modelos de linguagem grandes.
- Memória adequada para lidar com grandes conjuntos de dados e visualizações de grafos.
