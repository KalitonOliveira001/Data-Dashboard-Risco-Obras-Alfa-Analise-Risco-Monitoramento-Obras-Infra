# Data-Dashboard-Risco-Obras-Alfa-Analise-Risco-Monitoramento-Obras-Infra
# 📊 Dashboard Estratégico de Monitoramento de Risco e Progresso em Obras (Estudo de Caso)

Este repositório contém a documentação, os dados e o código-fonte de um projeto completo de Análise de Dados e Business Intelligence focado na gestão de riscos e monitoramento do progresso físico e financeiro de um grande projeto de infraestrutura.

O projeto demonstra a capacidade de transformar dados brutos em métricas acionáveis para tomada de decisão executiva.

---

## 🎯 Objetivo Principal

Fornecer uma visão **unificada e em tempo real** dos fatores críticos que impactam o projeto. O Dashboard foi desenhado para responder rapidamente a perguntas sobre orçamento, risco operacional e produtividade, permitindo a atuação proativa da Diretoria de Operações e da Equipe Financeira.

## 🛠️ Tecnologias e Ferramentas

| Ferramenta | Uso |
| :--- | :--- |
| **Python / Google Colab** | Limpeza de dados (Data Cleaning), pré-processamento, engenharia de *features* e criação de métricas financeiras complexas (Taxa de Queima). |
| **Google Looker Studio (Data Studio)** | Construção do Dashboard interativo, visualização de dados e criação de um ambiente de gestão intuitivo e profissional. |
| **Google Drive** | Armazenamento seguro e compartilhamento de dados-fonte e ativos do projeto. |

---

## 💡 Insights e Resoluções Chave

A análise detalhada identificou problemas cruciais e forneceu soluções imediatas para a gestão do projeto:

### 1. Risco Financeiro e Orçamento
* **Problema Resolvido:** Falta de clareza sobre a distribuição dos gastos e o risco de estourar o orçamento.
* **Insight:** O Dashboard calcula a **Taxa de Queima Financeira** em tempo real e utiliza o Gráfico de Pizza para identificar os **Lotes com maior percentual de consumo** do orçamento.
* **Solução:** Criação da métrica **"Orçamento Restante (R$)"** para monitoramento constante do saldo disponível por lote.

### 2. Risco Operacional e Priorização
* **Problema Resolvido:** Não havia distinção entre o incidente mais grave (Criticidade) e o que causava mais atraso (Tempo Perdido).
* **Insight:** A análise separou o risco em dois eixos: **Horas de Paralisação (Downtime)**, indicando a maior causa de atraso (ex: Falha de Máquina), e **Criticidade Média** (Pontuação de Risco), indicando o que é mais perigoso (ex: Acidente Grave).
* **Solução:** Fornecimento de uma **ordem clara de prioridade** para as equipes de Manutenção e Segurança.

### 3. Progresso e Condições Climáticas
* **Problema Resolvido:** O progresso era medido de forma isolada, sem correlação com as variáveis ambientais.
* **Insight:** A Tabela de Progresso por Lote, segmentada por **Condição Climática** (Chuva Intensa, Sol Forte, etc.), revelou quais lotes têm a maior **queda de produtividade** sob condições adversas.
* **Solução:** O Dashboard permite à Gerência de Operações **alocar recursos de forma proativa**, planejando dias de maior produtividade com base no clima.

---

## 🔗 Acesso ao Projeto

Todo o projeto, incluindo o Dashboard interativo, o código de processamento e os dados brutos, está organizado em uma pasta no Google Drive.

Para navegar e reproduzir o trabalho:

1.  **Acesse a Pasta do Projeto (Google Drive):**
    > **[COLE AQUI SEU LINK COMPLETO DO GOOGLE DRIVE]**
2.  **Dashboard Interativo (Looker Studio):**
    > O atalho do dashboard está na pasta do Drive.
3.  **Código-Fonte:**
    > O arquivo **`[NOME_DO_SEU_NOTEBOOK].ipynb`** (Google Colab) está na pasta para revisão da metodologia de processamento dos dados.

---

#### 👨‍💻 Autor
[Seu Nome / Seu Contato de Portfólio]
