# Implementação de Ferramentas AWS na Abstergo Industries LTDA

Este repositório contém a documentação e os scripts relacionados ao projeto de implementação de ferramentas AWS na empresa Abstergo Industries LTDA.

## Visão Geral do Projeto

O projeto foi dividido em três etapas principais, cada uma com objetivos específicos:

### Etapa 1: AWS DynamoDB

- **Objetivo:** Armazenar dados críticos da empresa em um banco de dados NoSQL de alta performance e escalabilidade.
- **Descrição de Caso de Uso:** Utilizar o DynamoDB para armazenar dados de produtos, categorias, cupons e registros de vendas, proporcionando alta disponibilidade e baixa latência no acesso a dados críticos.

### Etapa 2: AWS EC2

- **Objetivo:** Prover instâncias de computação sob demanda para hospedar o backend Node.js e o banco de dados PostgreSQL.
- **Descrição de Caso de Uso:** Configurar instâncias otimizadas para a execução do servidor Node.js e PostgreSQL, garantindo desempenho adequado e permitindo escalabilidade conforme a demanda.

### Etapa 3: AWS S3 (Amazon Simple Storage Service)

- **Objetivo:** Armazenamento seguro e escalável de arquivos e dados estáticos.
- **Descrição de Caso de Uso:** Utilizar o S3 para armazenar arquivos de mídia (imagens de produtos, documentos anexados pelos usuários), backups e logs de aplicação, garantindo durabilidade e acessibilidade.

## Estrutura do Repositório

```plaintext
/docs
    - dynamodb-setup.md
    - ec2-setup.md
    - s3-setup.md
/scripts
    - deploy-dynamodb.sh
    - deploy-ec2.sh
    - deploy-s3.sh


# Exemplo de uso dos scripts de automação

# Deploy DynamoDB
bash /scripts/deploy-dynamodb.sh

# Deploy EC2
bash /scripts/deploy-ec2.sh

# Deploy S3
bash /scripts/deploy-s3.sh

