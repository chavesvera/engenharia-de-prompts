# **🌾 Classificação de Grãos de Trigo com Machine Learning 🤖**

Um projeto completo de Data Science usando a metodologia CRISP-DM para classificar variedades de trigo com alta precisão.

## **🎯 Visão Geral do Projeto**

Este projeto desenvolve uma solução completa de Machine Learning para automatizar a classificação de três variedades de grãos de trigo (Kama, Rosa e Canadian). O objetivo é substituir o processo de classificação manual, que é lento e sujeito a erros em cooperativas agrícolas, por um sistema automatizado, preciso e eficiente.

Toda a análise foi estruturada seguindo rigorosamente a metodologia **CRISP-DM**, desde o entendimento dos dados até a avaliação e otimização dos modelos.

## **✨ Principais Destaques**

* **Metodologia Robusta:** Análise completa seguindo as 6 fases do CRISP-DM.  
* **Comparação de Modelos:** Implementação e avaliação de 5 algoritmos de classificação, incluindo Random Forest, SVM e KNN.  
* **Otimização de Performance:** Uso de GridSearchCV para encontrar os melhores hiperparâmetros e maximizar a acurácia.  
* **Análise de Features:** Identificação das características físicas dos grãos que mais impactam na classificação.  
* **Alta Acurácia:** O modelo final alcançou **92.1% de acurácia** na classificação das variedades.

## **📊 O Dataset**

Utilizamos o **Seeds Dataset**, um conhecido benchmark do repositório da UCI.

* **Total de Amostras:** 210\.  
* **Variedades (Classes):** 3 (Kama, Rosa, Canadian), perfeitamente balanceadas com 70 amostras cada.  
* **Características (Features):** 7 atributos geométricos de cada grão, como Área, Perímetro e Compacidade.

## **🛠️ Tecnologias Utilizadas**

* **Linguagem:** Python 3  
* **Bibliotecas Principais:**  
  * Pandas & NumPy (Manipulação de dados)  
  * Scikit-learn (Machine Learning)  
  * Matplotlib & Seaborn (Visualização de dados)  
* **Ambiente:** Jupyter Notebook

## **🚀 Como Executar o Projeto**

Siga os passos abaixo para replicar a análise.

**1\. Pré-requisitos:**

* Python 3.9 ou superior  
* O arquivo do dataset seeds\_dataset.txt no mesmo diretório do projeto.

**2\. Instalação das Dependências:**

pip install pandas numpy scikit-learn matplotlib seaborn jupyter

**3\. Execução:**

* Abra o notebook SOLUÇÃO\_COMPLETA\_CLASSIFICAÇÃO\_DE\_GRÃOS\_DE\_TRIGO\_COM\_MACHINE\_LEARNING.ipynb em um ambiente Jupyter.  
* Execute as células sequencialmente para ver todo o processo de análise, treinamento e avaliação.

## **🏆 Resultados e Insights**

* **Melhor Modelo:** O **Random Forest** se destacou como o algoritmo mais performático, alcançando **92.1% de acurácia**.  
* **Características Mais Importantes:** A análise revelou que as 3 características mais discriminativas são:  
  1. **Área do grão** (22.5% de importância)  
  2. **Perímetro** (21.8% de importância)  
  3. **Comprimento do sulco** (16.7% de importância)  
* **Conclusão Estratégica:** Apenas 3 características físicas são responsáveis por mais de **60% do poder preditivo** do modelo, o que pode simplificar a implementação de um sistema de medição em campo.