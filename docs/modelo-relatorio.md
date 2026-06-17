[modelo-relatorio.md](https://github.com/user-attachments/files/29061320/modelo-relatorio.md)
# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 17/06/2026
**Empresa:** Abstergo Industries
**Responsável:** Raphael Herkmann

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa **Abstergo Industries**, realizado por **Raphael Herkmann**. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

**Etapa 1:**
- **Nome da ferramenta:** Amazon EC2 Auto Scaling
- **Foco da ferramenta:** Elasticidade e otimização de capacidade computacional
- **Descrição de caso de uso:** A Abstergo mantinha servidores ligados em capacidade máxima 24/7, mesmo em períodos de baixa demanda. Com o Auto Scaling, a quantidade de instâncias passa a se ajustar automaticamente conforme o tráfego, ligando máquinas apenas quando necessário. Isso elimina o desperdício de capacidade ociosa e reduz diretamente a fatura de computação, pagando-se somente pelo que é efetivamente utilizado.

**Etapa 2:**
- **Nome da ferramenta:** Amazon S3 com Intelligent-Tiering
- **Foco da ferramenta:** Armazenamento de objetos com otimização automática de custo
- **Descrição de caso de uso:** Os arquivos da empresa (documentos, backups e mídias) estavam armazenados em discos de alto custo, independentemente da frequência de acesso. Migrando para o Amazon S3 com a classe Intelligent-Tiering, os dados são movidos automaticamente entre camadas de acesso (frequente, infrequente e arquivamento/Glacier) com base no uso real. Arquivos raramente acessados passam a custar uma fração do valor, gerando economia significativa sem intervenção manual.

**Etapa 3:**
- **Nome da ferramenta:** AWS Cost Explorer + AWS Budgets
- **Foco da ferramenta:** Monitoramento, previsão e controle de gastos
- **Descrição de caso de uso:** A empresa não possuía visibilidade clara de onde os custos eram gerados na nuvem. Com o Cost Explorer é possível visualizar gastos por serviço, identificar recursos subutilizados e detectar anomalias. Já o AWS Budgets dispara alertas automáticos quando os gastos se aproximam de limites definidos, evitando surpresas na fatura e permitindo decisões proativas de redução de custo.

## Conclusão

A implementação de ferramentas na empresa **Abstergo Industries** tem como esperado a **redução imediata de custos com infraestrutura ociosa, a otimização automática dos gastos com armazenamento e o controle proativo do orçamento em nuvem**, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- Diagrama de arquitetura da solução (`diagrams/arquitetura.png`)
- Tabela comparativa de custos antes/depois da implementação
- Documentação oficial dos serviços AWS utilizados

Assinatura do Responsável pelo Projeto:

**Raphael Herkmann**
