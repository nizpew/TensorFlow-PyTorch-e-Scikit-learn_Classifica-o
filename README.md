# 🖼️ Image-Fusion Ensemble Vision

**Status:** Em produção 🚀 │ **Colab Notebook**

---

## 🇧🇷 Visão Geral

**Image-Fusion Ensemble Vision** é um projeto em Google Colab que demonstra um pipeline completo de classificação de imagens no **CIFAR-10**, combinando:

- **Pré-processamento** e divisão de dados com **Scikit-learn**  
- **Treinamento de CNN** em **TensorFlow/Keras**  
- **Treinamento de CNN** em **PyTorch**  
- **Ensemble** das previsões (votação majoritária) com **Scikit-learn**  
- **Geração de gráficos** de desempenho e matrizes de confusão  

📈 **Demo ao vivo dos gráficos:**  
👉 https://image-fusion-ensemble-vision.lovable.app/

---

### 🎯 Benefícios para RH e Gestores

- **Velocidade de Prototipação**: tudo num único notebook Colab, sem infraestrutura local.  
- **Transparência e Reprodutibilidade**: código aberto com passos claros de pré-processamento, treino e ensemble.  
- **Resultados Visuais Imediatos**: dashboards e matrizes de confusão prontos para apresentações e relatórios.  
- **Flexibilidade**: fácil extensão para outros datasets ou arquiteturas de rede.  

---

### 🛠️ Stack Tecnológica

| Camada            | Tecnologia                        |
| ----------------- | --------------------------------- |
| Pré-processamento | Scikit-learn, NumPy               |
| Treino (TensorFlow) | TensorFlow 2.x, Keras            |
| Treino (PyTorch)  | PyTorch 2.x, torch.nn             |
| Ensemble & Métricas | Scikit-learn (VotingClassifier, accuracy_score, confusion_matrix) |
| Visualização      | Matplotlib                        |
| Ambiente          | Google Colab                      |

---

## ⚙️ Como Rodar

1. **Abra no Colab**  
   Clique no badge:  
   [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/drive/YOUR_NOTEBOOK_ID)  

2. **Execute as Células**  
   - Instalação de dependências (se necessário)  
   - Pré-processamento e loading do CIFAR-10  
   - Treino dos modelos TensorFlow e PyTorch  
   - Ensemble e geração de gráficos  

3. **Confira o Dashboard ao Vivo**  
   Acesse: https://image-fusion-ensemble-vision.lovable.app/

---

## 📂 Estrutura do Notebook

```text
Image-Fusion-Ensemble-Vision.ipynb   ← Notebook principal
README.md                            ← Este arquivo
LICENSE                              ← MIT License

