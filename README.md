# RELATÓRIO DE IMPLEMENTAÇÃO DE SERVIÇOS AWS

Data: 21/08/2025
Empresa: Abstergo Industries
Responsável: FERNANDO ANTUNES FILHO

## Introdução
Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Fernando Antunes Filho. O objetivo do projeto foi elencar 3 serviços AWS, com a finalidade de realizar diminuição de custos imediatos.

## Descrição do Projeto
O projeto de implementação de ferramentas foi dividido em 3 etapas, cada uma com seus objetivos especí­ficos. A seguir, serão descritas as etapas do projeto:

Etapa 1: 
- Amazon EC2
- Redução de custos de computação por meio de compromissos de uso.
- A utilização de servidores EC2 constantemente (ex.: para sistemas de ERP, integrações e APIs de comunicação com parceiros), pode aderir aos Savings Plans. Com eles, a empresa se compromete a um uso mínimo (por hora/dólar), e a AWS oferece descontos significativos de até 66% em relação ao preço sob demanda. Isso gera economia imediata sem alterar a infraestrutura existente.

Etapa 2: 
- Amazon S3 Intelligent-Tiering
- Armazenamento de dados com otimização automática de custos.
- Como é necessário manter grande volume de documentos (notas fiscais eletrônicas, contratos, registros de comunicação com outras empresas farmacêuticas), o S3 Intelligent-Tiering move automaticamente os arquivos menos acessados para camadas de armazenamento mais baratas, sem necessidade de intervenção manual. Isso reduz custos de armazenamento sem impactar a disponibilidade dos dados.

Etapa 3: 
- Amazon Aurora
- Banco de dados relacional escalável e sob demanda.
- Para manter integração constante com várias empresas, o banco de dados pode ter picos de acesso em determinados horários, mas não precisa ficar sempre provisionado em alta capacidade. O Aurora Serverless v2 ajusta automaticamente a quantidade de recursos consumidos pelo banco, permitindo pagar apenas pelo uso real, ao invés de manter instâncias superdimensionadas. Isso reduz custos de imediato sem comprometer performance ou disponibilidade.



## Conclusão
A implementação de ferramentas na empresa *Abstergo Industries tem como esperado a implementação de ferramentas virtuais da AWS*, o que aumentará a eficiência e a produtividade da empresa. Recomenda-se a continuidade da utilização das ferramentas implementadas e a busca por novas tecnologias que possam melhorar ainda mais os processos da empresa.

## Anexos

- [EC2 Savings Plans](https://docs.aws.amazon.com/savingsplans/latest/userguide/what-is-savings-plans.html "Abrir documentação oficial da AWS")
- [S3 Intelligent-Tiering](https://docs.aws.amazon.com/AmazonS3/latest/userguide/intelligent-tiering-overview.html "Abrir documentação oficial da AWS")
- [Aurora Serverless v2](https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/aurora-serverless-v2.html "Abrir documentação oficial da AWS")


Assinatura do Responsável pelo Projeto:

FERNANDO ANTUNES FILHO
