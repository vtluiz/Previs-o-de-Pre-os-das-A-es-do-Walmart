# Previs-o-de-Pre-os-das-A-es-do-Walmart
# Projeto de Análise de Dados de Ações do Walmart

Este projeto tem como objetivo baixar, limpar e visualizar dados de preços de ações do Walmart utilizando Python. O código usa bibliotecas como `pandas`, `numpy`, `matplotlib`, e `requests` para realizar as tarefas de análise e visualização.

## Estrutura do Projeto

- **`src/visualizacao_dados.py`**: Script principal para baixar, limpar e visualizar os dados.

## Passos Realizados

1. **Baixar o arquivo**: O arquivo de dados é baixado do Google Drive.
2. **Carregar e explorar os dados**: Os dados são carregados em um DataFrame e as primeiras linhas são exibidas.
3. **Limpar e formatar os dados**: A coluna de data é convertida para o formato de data, e o DataFrame é ordenado por data.
4. **Visualizar os dados**: Um gráfico do preço de fechamento das ações é gerado e exibido.

## Dependências

Certifique-se de ter as seguintes bibliotecas instaladas:

- `pandas`
- `numpy`
- `matplotlib`
- `requests`

Você pode instalar as dependências usando o `pip`:

```bash
pip install pandas numpy matplotlib requests
