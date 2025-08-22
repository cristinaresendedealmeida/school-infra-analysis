# 📊 Data Analysis Project for UNICEF

Este repositório contém o código e os recursos de um projeto de análise de dados focado em avaliar a **infraestrutura básica das escolas no Brasil**, utilizando os dados do **Censo Escolar 2024**.  

O projeto demonstra habilidades em **engenharia de dados, análise de dados e computação em nuvem**, essenciais para o programa **UNICEF Data & AI Internship**.

---

## 📌 Project Overview

O principal objetivo deste projeto é **identificar e visualizar as lacunas de infraestrutura básica** (água, energia elétrica e saneamento) nas escolas brasileiras.  

Através da análise de dados oficiais, o projeto gera **insights valiosos** que podem apoiar **decisões estratégicas e alocação de recursos** para melhorar o ambiente escolar das crianças.

---

## ✨ Key Features

### 🔹 Data Source
- Dados do **Censo Escolar 2024 (microdados)**, fornecido pelo **Ministério da Educação (MEC)**.

### 🔹 Cloud-Native Architecture
Pipeline construído e executado inteiramente na **nuvem Microsoft Azure**, demonstrando proficiência com serviços essenciais:

- **Azure Blob Storage**: armazenamento seguro e escalável para os arquivos CSV brutos.  
- **Azure Databricks**: plataforma de análise de dados e Machine Learning em nuvem, utilizada para rodar o código em Python.  

### 🔹 Data Analysis & Visualization
Ferramentas utilizadas:
- **pandas** → limpeza e transformação dos dados  
- **matplotlib** e **seaborn** → visualizações  

Saídas principais:
- 📉 **Gráfico de barras**: porcentagem de escolas sem infraestrutura básica (água, energia e saneamento) no Brasil.  
- 🌎 **Quebra regional por UF**: gráficos detalhando as deficiências por estado.  

---

## 💡 Why This Matters

Este projeto aborda uma questão crítica na educação e desenvolvimento infantil.  

Os resultados podem ajudar organizações como a **UNICEF** a:  
- ✅ Priorizar regiões para intervenção e investimento  
- ✅ Monitorar o progresso de projetos de infraestrutura ao longo do tempo  
- ✅ Fornecer **evidências baseadas em dados** para formuladores de políticas públicas  

Essa abordagem demonstra a capacidade de **traduzir problemas reais em soluções baseadas em ciência de dados**, uma competência-chave para uma carreira na área.

---

## ⚙️ How to Run the Project

### 1. Azure Setup
- Tenha uma conta **Azure** com um **Databricks Workspace** ativo e um **Storage Account** configurado.  

### 2. Upload Data
- Carregue o arquivo **`microdados_ed_basica_2024.CSV`** em um contêiner do **Azure Blob Storage**.  

### 3. Run the Notebook
- Abra o **Databricks Notebook**  
- Preencha os detalhes da sua **Storage Account** e **Access Key**  
- Anexe o notebook a um **Databricks Cluster ativo**  
- Execute o notebook para gerar as análises e visualizações  

---

## 📎 Licença
Este projeto foi desenvolvido para fins educacionais e demonstração de habilidades em ciência de dados e computação em nuvem.


### Dados do Projeto
O conjunto de dados original está disponível para download neste link: https://storageschoolanalysis.blob.core.windows.net/eof-raw/microdados_ed_basica_2024.csv?sp=r&st=2025-08-22T18:53:38Z&se=2025-11-01T02:59:59Z&spr=https&sv=2024-11-04&sr=b&sig=Ni5%2FsOp2Jwxq7YBbtecw4XU5%2Bj16%2BVNLptkDyW5Xw8M%3D
