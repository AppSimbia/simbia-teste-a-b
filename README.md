
# Simbia - Teste A/B

Este projeto realiza um teste A/B para comparar o desempenho entre duas versões da interface do usuário (UI) do aplicativo Simbia: a versão A (atual) e a versão B (nova). Ele coleta os dados de duração das tarefas, remove outliers, calcula as médias de cada grupo e aplica um teste t estatístico para verificar se a nova interface reduz significativamente o tempo necessário para completar tarefas.

O teste identifica qual versão apresenta melhor desempenho, fornecendo ao time de desenvolvimento de UI informações essenciais para decidir qual tela deve ser utilizada no aplicativo. Ele é desenvolvido com Python, utilizando manipulação de dados com Pandas e análise estatística com a biblioteca Pingouin, permitindo resultados confiáveis e fáceis de interpretar.


## Dependências


#### Python
* Versão: Python 3.12 ou superior
* Bibliotecas:
* pandas
* plotly
* pingouin

Para instalar as dependências, execute:

    pip install -r requirements.txt


## Autores
- [@Valenaantunes](https://github.com/Valenaantunes)
