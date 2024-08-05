# Projeto Imobiliária

Este projeto faz parte de um curso da Alura sobre análise de dados utilizando a biblioteca `pandas` em Python. O objetivo é explorar e entender um conjunto de dados sobre aluguéis de imóveis, realizando diversas operações de análise e limpeza para extrair insights significativos. Este notebook é uma aplicação prática dos conceitos abordados no curso.

## Conteúdo do Projeto

1. **Importação de Dados**
   - Dados são carregados a partir de um arquivo CSV disponível na web.

2. **Exploração Inicial dos Dados**
   - Visualização das primeiras e últimas linhas do conjunto de dados.
   - Verificação das informações gerais do DataFrame, incluindo tipos de dados e a presença de valores ausentes.

3. **Análise Descritiva**
   - Cálculo da média dos valores dos imóveis.
   - Agrupamento e cálculo da média de valores por tipo de imóvel.
   - Criação de gráficos para visualização dos preços médios por tipo de imóvel.

4. **Filtragem e Limpeza de Dados**
   - Identificação e separação de imóveis comerciais dos residenciais.
   - Remoção de registros com valores ausentes ou zero em colunas críticas.
   - Substituição de valores ausentes por zero e revalidação dos dados.

5. **Análise de Tipos de Imóveis**
   - Cálculo e visualização da distribuição percentual dos tipos de imóveis residenciais.
   - Filtragem de imóveis com características específicas, como número de quartos e faixa de preço.

6. **Cálculo de Valores e Descrição de Imóveis**
   - Criação de novas colunas para valores mensais e anuais, incluindo condomínio e IPTU.
   - Geração de descrições textuais para os imóveis com base nas suas características.
   - Adição de uma coluna indicando se o imóvel possui suíte ou não.

## Tecnologias Utilizadas

- **Python**: Linguagem de programação utilizada para análise de dados.
- **Pandas**: Biblioteca para manipulação e análise de dados.
- **Matplotlib**: Biblioteca para visualização de dados (não explicitamente mencionada no código, mas comum para gráficos).

## Resultados e Insights

- A análise revelou a média dos preços dos imóveis por tipo, possibilitando identificar quais tipos têm os preços mais altos e mais baixos.
- A limpeza dos dados foi essencial para garantir a precisão das análises, removendo registros incompletos e ajustando valores ausentes.
- A criação de novas colunas permitiu uma visão mais detalhada dos custos e das características dos imóveis.

## Como Executar

1. Clone este repositório.
2. Certifique-se de ter o Python e as bibliotecas `pandas` instaladas.
3. Execute o notebook Jupyter para explorar e visualizar os dados.

    ```bash
    git clone https://github.com/seu_usuario/projeto_imobiliaria.git
    cd projeto_imobiliaria
    jupyter notebook projeto_imobiliaria.ipynb
    ```

## Sobre o Curso

Este projeto é uma parte do curso da Alura sobre **"Pandas: Conhecendo a Biblioteca"**. O curso oferece uma introdução abrangente à biblioteca `pandas` e ensina como usar ferramentas de análise de dados para resolver problemas do mundo real. Para mais informações sobre o curso, visite [Alura](https://www.alura.com.br).
