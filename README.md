# Projetos de Redes Neurais Profundas — Infnet

**Aluno:** Vítor Turci dos Santos Nogueira  
**Disciplina:** Redes Neurais Profundas [26E3_2]  
**Professor:** Instituto Infnet  

---

## 📌 Visão Geral do Repositório

Este repositório contém a implementação dos projetos práticos e estudos de caso da disciplina de Redes Neurais Profundas. O trabalho está dividido em dois projetos principais desenvolvidos em PyTorch e avaliados via TensorBoard, além de três estudos de caso com auditoria técnica de modelos em produção.

---

## 📁 Estrutura do Repositório

```text
.
├── README.md                                           # Documentação principal do repositório
├── requirements.txt                                    # Dependências do projeto
├── vitor_nogueira_deep-learning-and-vision_deep-neural-networks.pdf # Relatório técnico final em PDF
├── vitor_nogueira_deep_learning_mlp_project1.ipynb    # Notebook do Projeto 1 (MLP Classificação e Regressão)
├── vitor_nogueira_deep_learning_mlp_project2.ipynb    # Notebook do Projeto 2 (CNN e Transfer Learning)
├── best_obesity_mlp.pt                                 # Checkpoint do melhor modelo do Projeto 1 (Classificação)
├── best_flight_mlp.pt                                  # Checkpoint do melhor modelo do Projeto 1 (Regressão)
├── best_flower_resnet18.pt                             # Checkpoint do melhor modelo do Projeto 2 (ResNet18)
└── runs/                                               # Logs e eventos gravados para o TensorBoard
    ├── obesity_classification_experiment/
    ├── flight_price_regression/
    └── flower_resnet18_experiment/
