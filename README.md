# 📊 Predição de Evasão de Clientes – Telecom X Parte 2

## 📌 Descrição do Projeto
Este projeto foi desenvolvido como parte de um desafio de **Ciência de Dados e Machine Learning**, com foco em prever a **evasão de clientes (churn)** na empresa fictícia **Telecom X**.  

Após uma primeira etapa de **análise exploratória e limpeza de dados**, o presente trabalho concentra-se na **construção de modelos preditivos** capazes de antecipar quais clientes têm maior chance de cancelar seus serviços.  

---

## 🎯 Objetivos
- Preparar os dados para modelagem (tratamento, encoding, normalização).  
- Analisar correlações entre variáveis e sua relação com o cancelamento.  
- Treinar **dois ou mais modelos de classificação**.  
- Avaliar o desempenho dos modelos com métricas adequadas.  
- Interpretar os resultados, destacando a importância das variáveis.  
- Propor uma **conclusão estratégica** com recomendações práticas para redução do churn.  

---

## 🧰 Tecnologias Utilizadas
- **Python 3.x**
- **Pandas / NumPy** – Manipulação e tratamento de dados  
- **Matplotlib / Seaborn** – Visualização gráfica  
- **Scikit-learn** – Modelagem preditiva (Machine Learning)  
- **Imbalanced-learn (SMOTE)** – Balanceamento de classes  

---

## 🔑 Principais Insights
- **Tempo de Contrato (em dias/meses)** é o fator mais relevante: contratos mais curtos estão associados a maior probabilidade de cancelamento.  
- **Cobrança Total acumulada** está positivamente correlacionada com a evasão, indicando sensibilidade ao preço.  
- Clientes mais antigos tendem a permanecer, reforçando a importância de estratégias de fidelização.  

---

## 🤖 Modelos Utilizados
### 🔹 Regressão Logística
- Modelo baseline, interpretável e de fácil comunicação.  
- Apresentou desempenho consistente, sendo útil para entendimento rápido do fenômeno.  

### 🔹 Random Forest
- Modelo robusto, com maior **AUC-ROC** e melhor capacidade de generalização.  
- Permitiu identificar as variáveis mais relevantes para previsão da evasão.  
- Recomendado para uso em produção para scoring de risco.  

---

## 📊 Resultados e Métricas
- **Random Forest** superou a **Regressão Logística** em métricas de desempenho, especialmente em **AUC-ROC**.  
- Foi possível atingir resultados satisfatórios na identificação de clientes em risco, mesmo diante de **classes desbalanceadas**.  
- O balanceamento via **SMOTE** também foi testado, aumentando o recall para a classe minoritária (clientes cancelados).  

---

## 🚀 Conclusão Estratégica
- Clientes em contratos iniciais e de curta duração apresentam **maior risco de evasão**.  
- **Altos custos acumulados** elevam a chance de cancelamento, mostrando a necessidade de políticas de preço mais atrativas.  
- Estratégias recomendadas:  
  - **Programas de retenção nos primeiros meses**.  
  - **Política de descontos e benefícios progressivos**.  
  - **Planos de fidelização de longo prazo**.  
  - **Monitoramento contínuo com modelos preditivos** para atuação proativa da equipe de retenção.  

---

## 📌 Próximos Passos
- Explorar outros algoritmos (XGBoost, LightGBM).  
- Implementar um **pipeline automatizado de predição**.  
- Desenvolver um **dashboard interativo** para monitoramento em tempo real.  

---

## 👨‍💻 Autor
📌 Projeto desenvolvido por **Ana Santos** 
📅 Ano: 2025

