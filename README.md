# 🧠 Quantum Machine Learning — Blood Transfusion Prediction  
### Comparação de Algoritmos Quânticos aplicados a Dados de Saúde Pública  

Este projeto apresenta uma análise comparativa de três abordagens de **Aprendizado de Máquina Quântico (QML)** utilizando o dataset *Blood Transfusion Service Center*, disponível no Kaggle. O objetivo foi avaliar precisão, custo computacional e aplicabilidade prática em um problema real de saúde pública.

---

## 📌 Objetivo do Projeto

Avaliar e comparar três modelos de Quantum Machine Learning:

- **Variational Quantum Classifier (VQC)**
- **Multiclass Margin Classifier**
- **Data Reuploading Classifier**

> *“Qual modelo quântico apresenta o melhor equilíbrio entre precisão e custo computacional para este conjunto de dados?”*

---

## 📂 Estrutura do Projeto


- **`data/`**  
  Pasta contendo o dataset utilizado no estudo (`blood.csv`).

- **`imgs/`**  
  Imagens dos circuitos, gráficos de resultados e visualizações geradas.


- **`notebook/`** 
📓 [Notebook da Análise](https://colab.research.google.com/drive/1uPY3Hu8VgE6L0PcISNSZ-N4wU3QKMG7V?usp=sharing)  
  Contém o notebook do carregamento dos dados, pré-processamento, implementação dos modelos quânticos e comparação dos resultados.

- **`pdf/`**  
  PDF da apresentação utilizada para explicar metodologia, resultados e conclusão.

- **`README.md`**  
  Documento principal com explicação do projeto.
---

## 🗂️ Dataset

📌 **Blood Transfusion Service Center — Kaggle ou /data/blood.csv**  
https://www.kaggle.com/datasets/foolishboi/blood-transfusion  

---

## 🧪 Modelos Quânticos Avaliados

### 🔹 1. Variational Quantum Classifier (VQC)
- Baixo custo computacional  
- Fácil implementação  
- Acurácia moderada
- ![Variational Circuit](/Imgs/circuit_variational.jpg)

### 🔹 2. Multiclass Margin Classifier
- Robusto e com boa precisão  
- Mais caro computacionalmente  
- Treinamento mais lento
- ![Multiclass Classifier](/Imgs/multiclass_classifier.jpg)

### 🔹 3. Data Reuploading Classifier
- Melhor capacidade de generalização  
- Ótimo desempenho geral  
- Equilíbrio entre custo e precisão
- ![Data Reuploading](/Imgs/data_reuploading.jpg)

---

## 📊 Resultados

| Modelo | Acurácia | Custo Computacional | Observação |
|-------|----------|---------------------|------------|
| **VQC** | Média | Baixo | Bom para protótipos |
| **Multiclass Margin** | Alta | Alto | Desempenho robusto |
| **Data Reuploading** | **Melhor** | Médio | Melhor custo-benefício |

⭐ **Conclusão:** A comparação entre os três modelos de Quantum Machine Learning mostrou que cada arquitetura apresenta um equilíbrio diferente entre desempenho e custo computacional. O VQC se destacou pela simplicidade e baixo custo, sendo adequado para estudos iniciais, mas limitado em expressividade. O Multiclass Margin Classifier apresentou boa precisão, porém com um custo computacional elevado, o que reduz sua viabilidade prática.

O Data Reuploading Classifier foi o modelo com melhor desempenho geral, alcançando o melhor equilíbrio entre acurácia, profundidade do circuito e tempo de execução. Os resultados evidenciam que, mesmo com hardware limitado, abordagens híbridas e técnicas modernas de QML podem oferecer soluções promissoras para problemas reais, especialmente em cenários de dados modestos como o estudado.

---

## 🛠 Tecnologias Utilizadas

<a href='https://assets.cloud.pennylane.ai/pennylane_website/generic/logo.svg' target="_blank"><img alt='PennyLane' src='https://img.shields.io/badge/PENNYLANE-100000?style=for-the-badge&logo=PennyLane&logoColor=180606&labelColor=000000&color=FFFFFF'/></a> ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54) ![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=Matplotlib&logoColor=black) ![NumPy](https://img.shields.io/badge/numpy-%23013243.svg?style=for-the-badge&logo=numpy&logoColor=white) ![scikit-learn](https://img.shields.io/badge/scikit--learn-%23F7931E.svg?style=for-the-badge&logo=scikit-learn&logoColor=white) ![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white) ![Jupyter](https://img.shields.io/badge/jupyter-%23FA6F1E.svg?style=for-the-badge&logo=jupyter&logoColor=white)
## 👨‍💻 Autor

**Weverton Farias** 

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/wevertonfarias/)
