
Relatório de Implementação de Serviços AWS
Anexos

**Data:** 25/08/2025 <br>
**Empresa:** Abstergo Industries <br>
**Responsável:** Fabio Roberti Costa


Introdução

Este relatório apresenta a proposta de implementação de serviços da Amazon Web Services (AWS) com o objetivo de otimizar as operações e gerar uma significativa redução de custos para a empresa. A migração para a nuvem permitirá a transição de despesas de capital (CAPEX) para despesas operacionais (OPEX), proporcionando maior flexibilidade e previsibilidade financeira.

Descrição do Projeto

O projeto de implementação foi dividido em três etapas, cada uma focada em um serviço da AWS com a finalidade de diminuir custos imediatos.

Etapa 1: Otimização do Armazenamento com Amazon S3 Intelligent-Tiering
Foco da Ferramenta: Reduzir os custos de armazenamento de dados.

Descrição do Caso de Uso: Atualmente, a empresa armazena grandes volumes de dados (registros de estoque, históricos de pedidos, etc.) em um único tipo de armazenamento. O Amazon S3 Intelligent-Tiering monitora o padrão de acesso a esses dados e os move automaticamente para a classe de armazenamento mais econômica, sem a necessidade de intervenção manual.

Benefício Financeiro: Essa implementação resultará em uma economia direta e automática, pois não haverá pagamento pelo preço de "acesso imediato" para dados que não são utilizados com frequência.

Etapa 2: Otimização da Capacidade de Processamento com Amazon EC2 Auto Scaling
Foco da Ferramenta: Otimizar a capacidade de processamento e evitar o desperdício de recursos.

Descrição do Caso de Uso: Para suportar picos de demanda (como em campanhas promocionais), a empresa mantém um número fixo de servidores ativos 24/7, gerando um custo de infraestrutura desnecessário fora dos horários de pico. O Amazon EC2 Auto Scaling ajusta o número de servidores automaticamente, aumentando-os durante a alta demanda e diminuindo-os quando a demanda é baixa.

Benefício Financeiro: Com esta solução, a empresa pagará apenas pela capacidade de processamento que realmente usa, eliminando o custo de servidores ociosos e gerando uma redução significativa nas despesas de infraestrutura.

Etapa 3: Redução de Carga no Banco de Dados com DynamoDB Accelerator (DAX)
Foco da Ferramenta: Melhorar o desempenho do banco de dados e reduzir a necessidade de escalabilidade.

Descrição do Caso de Uso: O alto volume de consultas diárias ao banco de dados de produtos gera uma alta carga de processamento. O DynamoDB Accelerator (DAX) adiciona uma camada de cache, que armazena as informações mais acessadas. As consultas a esses dados são respondidas quase instantaneamente pelo cache, reduzindo a carga no banco de dados.

Benefício Financeiro: Ao diminuir a carga no banco de dados, a empresa evita a necessidade de provisionar uma capacidade de banco de dados maior e mais cara, otimizando o uso dos recursos existentes e garantindo a velocidade das operações sem custos adicionais.

Conclusão
A implementação desses serviços AWS representa um investimento estratégico que resultará em uma redução de custos direta e sustentável. A transição para um modelo de pagamento "conforme o uso" permitirá alocar os recursos financeiros de forma mais eficiente, garantindo a viabilidade financeira das operações a longo prazo.
