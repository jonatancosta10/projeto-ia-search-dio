# Desafio DIO - IA para Ingestão e Indexação de Documentos

## Objetivo

Este projeto tem como objetivo aplicar técnicas de organização e pesquisa de documentos utilizando ferramentas de inteligência artificial, com foco na ingestão de conteúdo, criação de índices inteligentes e exploração de dados.

## Etapas

### 1. Criação do Serviço no Azure

O primeiro passo foi criar o serviço de **Azure Cognitive Search**. No portal do Azure, selecionei "Criar um Recurso", busquei por "Azure Cognitive Search", preenchi as informações necessárias (nome, região, assinatura, etc.), e criei o serviço.

![Imagem do serviço criado no Azure](images/azure_service_creation.png)

### 2. Criação do Índice de Pesquisa

Em seguida, criei um índice para armazenar e organizar os dados. O índice possui os seguintes campos: **Id**, **Title**, **Content**, e **Category**.

![Imagem da criação do índice no Azure](images/index_creation.png)

### 3. Ingestão de Dados

Com o índice criado, comecei a ingestão de dados. Utilizei um arquivo JSON com a estrutura dos documentos para preenchê-lo com informações relevantes.

![Imagem da ingestão de dados no Azure](images/data_ingestion.png)

### 4. Consulta ao Índice

Após a ingestão dos dados, realizei consultas utilizando a API de pesquisa do Azure, buscando palavras-chave específicas dentro dos documentos indexados.

---

## Tecnologias Utilizadas

- **Azure Cognitive Search** para ingestão e indexação de documentos.
- **JSON** como formato para armazenamento e ingestão de dados.
- **API REST** para consulta ao índice.

## Como Rodar o Projeto

1. Clonar este repositório.
2. Criar uma instância do Azure Cognitive Search (seguindo as etapas acima).
3. Iniciar o processo de ingestão de dados e consulta ao índice.
