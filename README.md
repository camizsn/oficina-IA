# 🤖 Projeto Classificação de Imagens com Machine Learning
Este projeto foi desenvolvido pela professora **Nicole Pessoa** com foco no aprendizado prático e descomplicado de Machine Learning e Visão Computacional, usando Python. Ele tem como objetivo identificar a raça (branca ou preta) de mulheres em imagens através de modelos de classificação.

## 🎯 Objetivo do projeto
1. Classificar imagens de mulheres em duas categorias: **branca** e **preta**
2. Utilizar modelos pré-treinados como ViT e MobileNetV2
3. Construir, treinar e avalizar uma CNN customizada
4. Aplicar Transfer Learnin
5. Testar imagnes da internet e gerar predições com porcentagem de confiança
   
O modelo utilizado foi o **MobileNetV2** com Transfer Learning.

## 📚 Bibliotecas utilizadas
- transformers
- PIL
- tensorflow | keras
- matplotlib
- torch
- numpy
- requests
- io | BytesIO
- shutil | os

## 🔍Etapas do projeto
1. **Organização dos Dados**
- Estruturação das pastas para Keras: ```dataset_organizado/treinamento/brancas``` e ```pretas```
- Utilização de ```shutil```
  
2. **Modelos utilizados**
- CNN personalizada (Conv2D + MaxPooling + Flatten + Dense)
- MobileNetV2 com Transfer Learning
- Comparação de desempenho entre modelos

3. **Data Augmentation**
- Rotação, espelhamento, normalização
- Divisão de treino/validação com ```ImageDataGenerator```

4. **Avaliação e Métricas**
- Função de perda binária
- Acurácia
- Visualização dos resultados

5. **Teste com Imagens da Web**
- Download e processamento de imagens por URL
- Geração de predição e exibição de confiança

## ⚠️ Limitações
- Dataset pequeno: risco de overfitting e baixa generalização
- Bias do modelo: cuidado com decisões automatizadas sobre raça
- Não recomendado para uso em produção

## 🚀 Como executar
Clone o repositório:
git clone https://github.com/camizsn/oficina-IA.git

## 🧾 Licença
Projeto educacional com fins de estudo. Não utilizar para fins comerciais ou de produção sem validação ética e técnica.
