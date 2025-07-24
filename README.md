# Classificador de Gatos e Cachorros com Transfer Learning

## 🎯 Descrição do Projeto
Este projeto implementa um classificador de imagens utilizando Transfer Learning com TensorFlow/Keras. O modelo é capaz de distinguir entre fotos de gatos e cachorros com alta precisão.

## 🚀 Tecnologias Utilizadas
- Python 3.x
- TensorFlow/Keras
- Transfer Learning com MobileNetV2
- OpenCV/PIL para processamento de imagens
- Matplotlib para visualização

## 📊 Dataset
- Dataset Cats vs Dogs (Microsoft)
- 2 classes: Gatos e Cachorros
- Pré-processamento de imagens incluindo:
  - Limpeza de arquivos corrompidos
  - Normalização de nomes de arquivos
  - Verificação de integridade das imagens

## 🔧 Características Técnicas
- **Modelo Base:** MobileNetV2 (pré-treinado no ImageNet)
- **Arquitetura:** Transfer Learning com camadas personalizadas
- **Otimização:** Adam optimizer com learning rate de 0.0001
- **Métricas:** Acurácia e Loss para treino e validação
- **Pré-processamento:** Pipeline otimizado com tf.data

## 📈 Resultados
- Acurácia de validação: ~90-95% (dependendo do treinamento)
- Processamento acelerado com GPU (quando disponível)
- Visualização de resultados em gráficos

## 🎓 Projeto Desenvolvido para Digital Innovation One (DIO)
Parte do desafio de Transfer Learning em Deep Learning

## 📚 Referências
- Dataset: https://www.microsoft.com/en-us/download/details.aspx?id=54765
- TensorFlow Transfer Learning Guide
