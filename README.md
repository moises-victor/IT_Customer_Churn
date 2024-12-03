### Previsão de Churn de Clientes com vários algoritmos 
XGBoost | ExtraTrees | SVC | CatBoost | DecisionTree

- Este projeto destaca a necessidade de saber tratar bases de dados desbalanceadas (quando há pequena incidência de uma categoria dentro de um dataset (classe minoritária) em comparação com as demais categorias (classes majoritárias))
- Como veremos, a grande maioria dos exemplos disponíveis no dataset representam casos em que não houve 'churn'.
- Existem cuidados especiais ao se avaliar um algoritmo de Machine Learning quando se trata de datasets desbalanceados. Se desenvolvermos um modelo sem considerar essa desproporcionalidade nos dados, poderá levar a uma falsa percepção de que o modelo possuiu alta acurácia e que produz ótimos resultados.

Os dados para análise estão disponíveis no Kaggle: 
- [IT Customer Chrun (Goal : Imbalanced Dataset)](https://www.kaggle.com/datasets/soheiltehranipour/it-customer-churn/data)

### Sobre os dados:

O Churn indica se um cliente desistiu/cancelou detereminado serviço. Em negócios que cobram mensalmente por um serviço, o churn é um problema sério. Afinal, quando um cliente que paga uma mensalidade resolve cancelar, todo o faturamento da empresa é comprometido a longo prazo, não só no mês atual.

Prever o 'Churn' de clientes implica saber quais clientes provavelmente sairão ou cancelarão a assinatura. Para várias empresas, geralmente uma previsão crítica pois frequentemente, como obter clientes custa mais do que manter os existentes.

O dataset inclui informações sobre:

- Clientes que saíram no último mês: a coluna é chamada 'Churn'
- Serviços que cada cliente assinou: telefone, várias linhas, internet, segurança online, backup online, proteção de dispositivo, suporte técnico e streaming de TV e filmes
- Informações da conta do cliente: há quanto tempo ele é cliente, contrato, método de pagamento, faturamento sem papel, cobranças mensais e cobranças totais
- Informações demográficas sobre os clientes: sexo, faixa etária e se eles têm parceiros e dependentes
