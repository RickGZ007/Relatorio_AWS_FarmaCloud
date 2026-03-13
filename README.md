# Relatorio_AWS_FarmaCloud

# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

**Data:** 12 de Março de 2026
**Empresa:** FarmaCloud AWS
**Responsável:** Ricardo Alberto Gonzalez Cedeno

---

## Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa FarmaCloud AWS, realizado por Ricardo Alberto Gonzalez Cedeno. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos e otimizar os recursos computacionais da organização.

---

## Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos específicos. A seguir, serão descritas as etapas do projeto:

---

### Etapa 1

- **Nome da ferramenta:** Amazon EC2 (Elastic Compute Cloud)
- **Foco da ferramenta:** Hospedagem de instâncias de servidores na nuvem
- **Descrição de caso de uso:** Criação de instâncias escaláveis para hospedar o sistema de vendas online da FarmaCloud AWS, substituindo servidores físicos internos. Com o Auto Scaling, as instâncias aumentam automaticamente em horários de pico, como campanhas e datas especiais, e reduzem fora deles, eliminando custos fixos com hardware, energia e manutenção de datacenter próprio. A adoção do modelo On-Demand e Reserved Instances proporciona redução imediata de até 40% nos custos de infraestrutura de computação.

---

### Etapa 2

- **Nome da ferramenta:** Amazon S3 (Simple Storage Service)
- **Foco da ferramenta:** Armazenamento de dados escalável e seguro
- **Descrição de caso de uso:** Armazenamento centralizado de todos os arquivos da farmácia, como imagens de produtos, receitas médicas digitalizadas, documentos fiscais, backups do banco de dados e logs de auditoria. O S3 elimina a necessidade de servidores de armazenamento locais e seus custos associados, incluindo hardware, licenças e manutenção. A configuração de ciclo de vida move automaticamente arquivos antigos para o Amazon S3 Glacier, reduzindo o custo de armazenamento em até 80% para dados raramente acessados.

---

### Etapa 3

- **Nome da ferramenta:** AWS Lambda
- **Foco da ferramenta:** Execução de funções serverless sem gerenciamento de servidores
- **Descrição de caso de uso:** Automatização de tarefas rotineiras da farmácia, como envio de notificações de pedidos por e-mail e SMS, processamento de imagens de receitas médicas, geração de relatórios diários de estoque e integração com sistemas de pagamento. Por ser serverless, o Lambda cobra apenas pelo tempo de execução real das funções, sem custo quando ocioso, eliminando completamente o custo de servidores dedicados para tarefas pontuais. Isso representa redução imediata nos custos de energia, manutenção e licenças de software.

---

## Conclusão

A implementação de ferramentas na empresa FarmaCloud AWS tem como esperado os seguintes benefícios:

- Redução imediata de custos operacionais com a eliminação de servidores físicos e despesas de datacenter
- Escalabilidade automática dos serviços conforme a demanda, sem investimento prévio em hardware
- Maior segurança e disponibilidade dos dados com redundância geográfica nativa da AWS
- Aumento da eficiência operacional com automação de tarefas via AWS Lambda
- Redução de até 60% nos custos de infraestrutura em comparação ao modelo tradicional

O que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

---

## Anexos

- Manual de utilização do Amazon EC2 - Guia de configuração de instâncias e Auto Scaling
- Guia de armazenamento e gestão no Amazon S3 - Políticas de ciclo de vida e permissões
- Documentação de funções AWS Lambda implementadas - Triggers, eventos e integração
- Planilha de controle de custos e desempenho - Comparativo mensal pré e pós-migração
- Política de segurança e conformidade com LGPD

---

**Assinatura do Responsável pelo Projeto:**

Ricardo Alberto Gonzalez Cedeno
