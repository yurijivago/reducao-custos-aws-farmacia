# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 16/04/2024
Empresa: Abstergo Industries
Responsável: Yuri Jivago Xavier Diniz

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Yuri Jivago Xavier Diniz. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Instâncias spot do Amazon EC2
- Execute cargas de trabalho tolerantes a falhas com desconto de até 90%
- Poderemos combinar as instâncias spot com outros modelos de compra, como as instâncias sob demanda e o Savings Plans, para maximizar a economia de custos. Além disso, usar as instâncias spot com o Amazon EC2 Auto Scaling possibilitará a otimização de custos da workload com o desempenho. 
    - Ainda contamos com a *implantação de contêineres* que nos permitirá, independente de escala, usando o Amazon EC2, o Amazon ECS, o Amazon EKS ou os clusters do Kubernetes autogerenciados em instâncias spot.

Etapa 2: 
- Recomendações de Savings Plans
- Os Savings Plans são modelos de preços flexíveis que oferecem preços mais baixos em comparação com os preços Sob demanda, em troca de um compromisso de uso específico (medido em USD/hora) por um período de um ou três anos
- Economize dinheiro em seu uso em estado estável
    - Com a utilização destes poderemos reduzir a conta de computação para uso geral em estado estável, independentemente da família de instâncias, região, sistema operacional e locação. Utilizando as recomendações fornecidas no Explorador de Custos da AWS (https://console.aws.amazon.com/cost-reports/home?region=us-east-1#/dashboard), a decisão de qual dos Savings Plans a ser escolhida será ainda mais fácil. Nesse cenário, a *Abstergo Industries* poderá acessar o painel da sua conta AWS para explorar as possibilidades, guiadas pelo especialista.

Etapa 3: 
- Explorador de custos
- Visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo
- Dispondo de uma interface fácil de usar que permite visualizar, entender e gerenciar os custos e o uso da AWS ao longo do tempo, poderemos facilmente com essa ferramenta criar relatórios personalizados que analisam dados de custos e uso. Ao utilizarmos, por exemplo, da análise dados de forma resumida (por exemplo, custos e uso totais em todas as contas) ou detalhe os dados de custos, estaremos com dados suficientes para conseguir identificar tendências, determinar causadores de custos e detectar anomalias. Com base nisso, poderemos facilmente prever os custos em um determinado período de tempo selecionado, possibilitando ajustes que venham a ser necessários para cumprir o orçamento desejado.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado auxiliar a tomada de decisão de qual plano contratar junto à AWS que se adeque ao orçamento disponível*, o que aumentará a eficiência, a produtividade da empresa, e permitirá um acompanhamento de perto a fim de não negligenciar a saúde financeira da empresa, bem como otimizar a utilização dos recursos disponíveis. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.



Assinatura do Responsável pelo Projeto:

*Yuri Jivago Xavier Diniz*
