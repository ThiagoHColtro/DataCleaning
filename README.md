
# DataCleaning

**Projetos de limpeza de dados | Data Cleaning Projects**

Este repositório contém projetos focados em técnicas de limpeza e pré-processamento de dados, com ênfase na análise de indicadores econômicos globais. Utiliza-se Python, principalmente através de Jupyter Notebooks, para transformar dados brutos em conjuntos prontos para análise.

## Estrutura do Repositório

```
DataCleaning/
├── GPD_per_Capita_GovExpenditure_Trade.ipynb
└── README.md
```

## Descrição do Projeto

O notebook `GPD_per_Capita_GovExpenditure_Trade.ipynb` realiza as seguintes etapas:

- **Importação de Dados:** Leitura de um conjunto de dados contendo informações sobre PIB per capita, gastos governamentais e comércio internacional.
- **Exploração Inicial:** Visualização das primeiras linhas, verificação de tipos de dados e identificação de valores ausentes.
- **Limpeza de Dados:**
  - Remoção de colunas irrelevantes.
  - Renomeação de colunas para nomes mais intuitivos.
  - Tratamento de valores ausentes e duplicados.
  - Conversão de tipos de dados para formatos apropriados.
- **Criação de Subconjuntos:** Separação dos dados em diferentes DataFrames para análises específicas.
- **Exportação de Dados Limpos:** Salvamento dos conjuntos de dados tratados para uso futuro.

## Tecnologias Utilizadas

- Python 3.x
- Jupyter Notebook
- Bibliotecas:
  - pandas
  - numpy

## Como Executar

1. Clone o repositório:

   ```bash
   git clone https://github.com/ThiagoHColtro/DataCleaning.git
   ```

2. Navegue até o diretório do projeto:

   ```bash
   cd DataCleaning
   ```

3. Instale as dependências necessárias:

   ```bash
   pip install pandas numpy
   ```

4. Abra o notebook Jupyter:

   ```bash
   jupyter notebook GPD_per_Capita_GovExpenditure_Trade.ipynb
   ```

## Contribuições

Contribuições são bem-vindas! Sinta-se à vontade para abrir issues ou pull requests com sugestões de melhorias, correções ou novas funcionalidades.

---

**Autor:** Thiago Henrique Coltro | Analista de Dados
