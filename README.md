# Analise-de-Fatura-por-Gráficos
Este projeto realiza uma análise de dados de faturas, onde utilizei Python e as bibliotecas **Pandas**, **Seaborn** e **Matplotlib** para a geração dos gráficos. O conjunto de dados contém informações de compras realizadas por diferentes pessoas, registrando nome, número do cartão, data, hora, categoria, estabelecimento e valor da compra.

# Análise de Faturas com Python, Pandas, Seaborn e Matplotlib

Este projeto realiza uma análise de dados de faturas, onde utilizei Python e as bibliotecas **Pandas**, **Seaborn** e **Matplotlib** para a geração dos gráficos. O conjunto de dados contém informações de compras realizadas por diferentes pessoas, registrando nome, número do cartão, data, hora, categoria, estabelecimento e valor da compra.

## Estrutura do Projeto

O projeto está estruturado da seguinte maneira:

- **fatura.csv**: O arquivo CSV com os dados de entrada para a análise.
- **main.py**: O script Python que escrevi para realizar a análise dos dados e gerar os gráficos.
- **README.md**: Este arquivo de documentação explicando tudo o que fiz no projeto e como rodá-lo.

## Requisitos

Para rodar o projeto, você precisará das seguintes bibliotecas Python instaladas:

- `pandas`
- `matplotlib`
- `seaborn`

Você pode instalar todas as dependências necessárias com o seguinte comando:

```bash
pip install pandas matplotlib seaborn


Descrição da Análise
1. Valor Total de Compras
Eu calculei o valor total de todas as compras realizadas, somando a coluna ValorCompra do dataset. Isso fornece uma visão geral do total gasto por todas as pessoas.

2. Valor Total por Pessoa
Agrupei os dados pelo nome da pessoa, somando o valor de compras para cada uma. Em seguida, gerei um gráfico de barras para visualizar o total gasto por cada pessoa.

Gráfico: Barra vertical com os nomes das pessoas no eixo X e o valor de compras no eixo Y.
Adição: Exibi o valor exato em cima de cada barra para facilitar a visualização.
3. Valor Total por Categoria
Agrupei os dados pela categoria de compra, somando o valor gasto em cada uma. Um gráfico de barras horizontais foi gerado para facilitar a análise dos valores totais por categoria.

Gráfico: Barra horizontal com as categorias no eixo Y e o valor de compras no eixo X.
Adição: Exibi o valor exato em cima de cada barra.
4. Distribuição de Compras por Hora
Utilizei a coluna hora_compra para criar um histograma que mostra a distribuição das compras ao longo das horas do dia. Isso permite identificar os horários mais comuns para compras.

Gráfico: Histograma com a frequência de compras em cada hora do dia.
5. Total de Compras ao Longo do Tempo
Agrupei os dados pela data de compra (data_compra) e somei os valores diários. Em seguida, gerei um gráfico de linha para visualizar como os gastos variaram ao longo do tempo.

Gráfico: Linha com os valores totais de compra ao longo das datas.
Adição: Incluí uma grade no gráfico para melhor visualização dos dados.
6. Distribuição de Valor de Compras por Pessoa
Por último, criei um gráfico de pizza para representar a participação de cada pessoa no valor total de compras, facilitando a análise visual da distribuição.

Gráfico: Pizza com as porcentagens de cada pessoa no total de compras.
