 ### **📌 Análise Final do Trabalho - Detecção de Fraude em Cartões de Crédito**

#### **🔍 Introdução**
Este estudo explorou diferentes abordagens de **Machine Learning** para detecção de fraudes em transações de cartão de crédito, incluindo **Random Forest, XGBoost, Redes Neurais e um modelo híbrido**. Aplicamos **balanceamento de dados (SMOTE), seleção de features e validação cruzada** para garantir um modelo robusto e eficiente.

---

### **📈 Principais Resultados**
Os testes realizados mostraram **altíssimo desempenho dos modelos** em identificar fraudes, com destaque para o **modelo híbrido (Random Forest + XGBoost)**:

#### **1️⃣ Modelos Individuais - Dados Balanceados**
- **Random Forest:** Acurácia **0.99**, Recall **0.98**, F1-score **0.99**.
- **XGBoost:** Acurácia **1.00**, Recall **1.00**, F1-score **1.00**.
- **Rede Neural:** Acurácia **1.00**, Recall **1.00**, F1-score **1.00**.

#### **2️⃣ Modelos Individuais - Dados Reais (Desbalanceados)**
- **Random Forest:** Acurácia **0.91**, Recall **0.83** → Pequena queda na detecção de fraudes.
- **XGBoost:** Acurácia **0.92**, Recall **0.84** → Melhor adaptação ao conjunto real.
- **Rede Neural:** Acurácia **0.90**, Recall **0.80** → Mais sensível ao desbalanceamento.

#### **3️⃣ Modelo Híbrido - Desempenho Superior**
- **Acurácia em Dados Balanceados:** **1.00**  
- **Acurácia em Dados Reais:** **1.00**  
- **Recall em fraudes:** **0.95** → Melhor recuperação de fraudes que os modelos individuais.  

**🚀 O modelo híbrido demonstrou ser a melhor abordagem para detectar fraudes, mantendo um equilíbrio entre precisão e recall!**

---

### **🔎 Interpretação dos Resultados**
✔ **O modelo híbrido superou os individuais**, combinando a capacidade interpretável do **Random Forest** com o alto desempenho do **XGBoost**.  
✔ **Os testes com SMOTE mostraram alta estabilidade**, sugerindo que o balanceamento dos dados funcionou bem.  
✔ **O modelo se manteve robusto nos dados reais**, indicando que pode ser utilizado em cenários produtivos sem perdas significativas na detecção de fraudes.  

---

### **🚀 Conclusões**
🔹 **Random Forest + XGBoost se provou a melhor estratégia**, garantindo **alta precisão e recuperação de fraudes**.  
🔹 **Os resultados mostraram pouca variação entre treino e teste**, indicando que **o modelo não sofre de overfitting**.  


