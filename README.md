# Mineração de Conhecimento com Azure Cognitive Search

## Objetivo
Este repositório foi criado como parte de um exercício prático sobre **mineração de conhecimento** utilizando a solução de **pesquisa cognitiva do Azure**, com foco em **enriquecimento de dados com IA**.

---

## Passo a Passo: Como configurar uma Pesquisa Cognitiva

### 1. Criar um Recurso de Pesquisa no Azure
- Acesse o [Portal do Azure](https://portal.azure.com)
- Clique em **Criar recurso > Pesquisa > Azure Cognitive Search**
- Escolha a camada gratuita (F) para testes
- Preencha as informações de nome, grupo de recursos, localização etc.

### 2. Preparar os dados
- Use documentos do tipo PDF, imagens, arquivos do Word ou dados estruturados
- Pode utilizar dados próprios ou amostras fornecidas pela Microsoft

### 3. Criar um Índice
- Acesse o serviço criado
- Vá em **Importar dados**
- Escolha a fonte (por exemplo: Blob Storage ou upload direto)
- Selecione **Habilitar enriquecimento com IA**
- Configure os **habilitadores de IA** (OCR, tradução, extração de entidades, etc.)
- Avance até criar o **indexador**, **skillset** e **índice**

### 4. Executar a Indexação
- O indexador será executado automaticamente na criação
- É possível reexecutar manualmente sempre que necessário

### 5. Testar sua Pesquisa Cognitiva
- Vá até **Explorar índice**
- Faça buscas por palavras-chave
- Verifique se os documentos estão enriquecidos com metadados e insights

---

## Insights e Possibilidades

- A pesquisa cognitiva permite **buscar informações mesmo dentro de PDFs ou imagens**, graças à integração com **IA para OCR e NLP**.
- É possível extrair **entidades**, **datas**, **lugares**, **pessoas**, **emoções** e muito mais de conteúdos não estruturados.
- A indexação enriquecida **torna seus dados pesquisáveis de maneira semântica**, indo além da simples busca por palavras exatas.

---

## Ferramentas e Sistemas que Podem se Beneficiar

- Sistemas jurídicos (busca inteligente em documentos legais)
- Portais de RH (pesquisa em currículos)
- Centros de atendimento (análise de feedback e histórico de tickets)
- Bibliotecas digitais
- Soluções de BI (dashboards com insights baseados em texto)

---

## Aprendizados

- Aprendi como o Azure Cognitive Search pode ser integrado com serviços cognitivos para enriquecer dados.
- Descobri que **não é necessário programar** para criar pipelines complexas de análise de texto e imagens.
- Entendi a importância de **pré-processar e organizar dados** para obter resultados mais relevantes.
- Vi que a mineração de conhecimento pode **transformar grandes volumes de informação em conhecimento útil e pesquisável**.

