# 📊 Análise de Cancelamento de Clientes

Análise de dados em Python para descobrir os principais motivos de cancelamento de clientes de uma empresa e propor ações para reduzi-los.

Projeto desenvolvido durante o **Intensivão de Python** da [Hashtag Treinamentos](https://www.hashtagtreinamentos.com/).

## 💡 O problema

Uma empresa com mais de 800 mil clientes percebeu que a maior parte da sua base já havia cancelado o serviço. O objetivo desta análise é entender **por que** os clientes cancelam e **quais ações** seriam mais eficientes para reduzir esse número.

## ⚙️ Etapas da análise

1. **Importação da base** com o Pandas
2. **Tratamento dos dados:** remoção de colunas irrelevantes (como o ID do cliente) e de linhas com informações faltantes
3. **Análise inicial:** cálculo da taxa geral de cancelamento
4. **Análise visual:** gráficos com o Plotly comparando clientes que cancelaram e que não cancelaram em cada característica da base
5. **Conclusões, recomendações e simulação** do impacto das ações propostas

## 🔍 Principais descobertas

A taxa inicial de cancelamento era de **56,8%**. A análise mostrou três perfis com cancelamento de 100%:

- Clientes com **mais de 50 anos**
- Clientes que ligaram para o **call center mais de 4 vezes**
- Clientes com **mais de 20 dias de atraso** no pagamento

## ✅ Recomendações

- **Idade:** criar planos de fidelidade para clientes acima de 50 anos.
- **Call center:** melhorar o atendimento e encaminhar para atendimento prioritário todo cliente que chegar à 3ª ligação.
- **Atraso no pagamento:** a equipe de cobrança deve entrar em contato com o cliente a partir do 15º dia de atraso para negociar o pagamento.

## 📉 Resultado da simulação

Simulando a aplicação das três recomendações, a taxa de cancelamento cairia de **56,8% para [X]%**, uma redução de **[Y] pontos percentuais**.

## 🛠️ Tecnologias

- **Python**
- **Pandas:** tratamento e análise dos dados
- **Plotly:** visualização dos dados
- **Jupyter Notebook**

## 📁 Base de dados

A base utilizada está disponível [neste link](https://drive.google.com/drive/folders/1uDesZePdkhiraJmiyeZ-w5tfc8XsNYFZ?usp=drive_link). Para executar o notebook, baixe o arquivo `cancelamentos.csv` e coloque-o na mesma pasta do notebook.

## ▶️ Como executar

1. Instale as dependências:

```
pip install -r requirements.txt
```

2. Abra o arquivo `analise_cancelamentos.ipynb` no VS Code ou no Jupyter e execute todas as células.

## 👩‍💻 Autora

**Maria Eduarda Tucunduva**

[LinkedIn](https://www.linkedin.com/in/maria-eduarda-tucunduva) · [GitHub](https://github.com/madutucunduva)