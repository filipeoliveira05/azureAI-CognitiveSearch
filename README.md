# Azure Cognitive Search: Indexação e Consulta de Dados com AI Search

## 📌 Introdução
Este repositório explora o **Azure Cognitive Search**, um serviço utilizado para **indexação e consulta de dados** usando inteligência artificial. Vamos entender três conceitos principais:

### 🔹 Mineração de Conhecimentos (Knowledge Mining)  
Refere-se ao processo de **extração de informações úteis** de grandes volumes de dados não estruturados. Utilizando AI, é possível transformar documentos, imagens e outras fontes em **dados estruturados** para análise e insights.

### 🔹 Azure Cognitive Search  
O **Azure Cognitive Search** é um serviço de **busca na nuvem** que permite indexar grandes volumes de dados e realizar consultas avançadas. Oferece a **capacidade de pesquisa inteligente**, utilizando algoritmos de relevância e AI para fornecer **resultados precisos e personalizados**.

### 🔹 Enriquecimento de AI  
É o processo de **adicionar metadados e informações adicionais** durante a indexação, usando **Cognitive Skills** do Azure, como reconhecimento de texto (OCR), análise de sentimentos e deteção de entidades.

---

## 🚀 Passo a Passo para Utilizar o Azure Cognitive Search

### 1️⃣ Acessar o Portal  
- Vá para o [Portal Azure](https://portal.azure.com/#home) e procure por **AI Search**.

### 2️⃣ Criar o Search Service  
- Clique em **Create** e preencha as informações necessárias.  
- Após a validação, clique em **Create** e depois em **Go to resource**.

### 3️⃣ Criar o Recurso de IA  
- Em **Create a resource**, selecione **AI + Machine Learning** e escolha **Azure AI Services**.

### 4️⃣ Configurar o Recurso  
- Preencha os dados necessários, clique em **Review + Create** e depois em **Create**.

### 5️⃣ Criar Conta de Armazenamento  
- No portal, busque por **storage accounts** e clique em **Create**.  
- Preencha as informações, clique em **Create** e depois em **Go to resource**.

### 6️⃣ Configurar o Storage  
- No menu lateral, vá em **Configuration** e habilite a opção necessária.  
- Em **Containers**, clique em **+ containers** para criar um novo container.

### 7️⃣ Importar Dados para o AI Search  
- No **AI Search**, clique em **Import data** e selecione **Azure Blob Storage**.  
- Preencha os dados e siga as etapas de configuração.

### 8️⃣ Adicionar Cognitive Skills  
- Em **Add Cognitive Skills**, anexe o recurso criado e configure os **enrichments**.

### 9️⃣ Criar e Personalizar o Index  
- Em **Customize target index**, personalize conforme a sua necessidade.  
- Em **Create an indexer**, configure o indexer e clique em **Submit**.

### 🔎 Consultar Dados no Search Explorer  
- Acesse o **Search Explorer** em **AI Search**.  
- Utilize queries como:  
  - Todos os dados: `search=*&$count=true`  
  - Por localização: `search=locations:'Chicago'`  
  - Por sentimento negativo: `search=sentiment:'negative'`

---

## 📊 Insights e Possibilidades  
✅ **Busca Inteligente** → Resultados personalizados com AI.  
✅ **Automatização de Processos** → Indexação automática de documentos.  
✅ **Análise de Dados** → Insights a partir de dados não estruturados.

---

## 🔗 Links Úteis  
- [Documentação Oficial](https://aka.ms/ai900-ai-search)  
- [Portal Azure](https://portal.azure.com/#home)
