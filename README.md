
# Desafio Data Science – Análise de Evasão de Clientes (Churn)

## Objetivo

Analisar o fenômeno de evasão de clientes em uma empresa de telecomunicações, identificando padrões e sugerindo ações para redução do churn.

## Estrutura

- `TelecomX_Churn_Analise_Completa.ipynb`: Notebook com toda a análise, gráficos e recomendações.
- `TelecomX_Data.json`: Base de dados de clientes.
- `TelecomX_dicionario.md`: Dicionário de dados com descrição de cada campo.

## Como rodar o notebook

1. Instale as dependências:
   ```bash
   pip install pandas matplotlib seaborn jupyter
   ```
2. Abra o notebook no Jupyter (`jupyter notebook` ou pelo VSCode).
3. Execute as células na ordem para visualizar a análise e os gráficos.

## Principais etapas do notebook

- **Limpeza dos dados:** Verificação de valores nulos, duplicados e categorias inconsistentes.
- **Engenharia de atributos:** Criação da coluna `Contas_Diarias`.
- **Análise descritiva:** Estatísticas gerais e visualização do churn.
- **Análise por categorias:** Churn por gênero, contrato, método de pagamento, etc.
- **Correlação de variáveis:** Identificação de fatores mais associados à evasão.
- **Conclusões e recomendações:** Sugestões práticas para reduzir o churn.

---



