# Projeto Final – Classificação de Grãos de Café com MobileNetV2

## Equipe

Ana Beatriz Barreto Teixeira e
João Miguel Dias Rosa

## Descrição da abordagem utilizada

Foi utilizada uma Rede Neural Convolucional (CNN) pré-treinada MobileNetV2 para classificação de imagens de grãos de café.

A técnica de Transfer Learning foi aplicada utilizando os pesos pré-treinados da ImageNet. Foram adicionadas novas camadas densas para adaptação ao problema de classificação das quatro classes presentes no dataset (Dark, Green, Light e Medium).

O treinamento foi realizado utilizando TensorFlow/Keras no Google Colab.

## Repositório do projeto

(https://github.com/anabeatrizbarretot/-Trabalho-Pratico)

## Vídeo de apresentação

(https://drive.google.com/file/d/19OV5s8MG0hPQ7bTqjkSjB0YN6UvoeVYf/view?usp=drivesdk)

## Dataset utilizado

(https://colab.research.google.com/drive/1SUyBSzjwy6_3dO2Do0895fbS2xm2I3Bi?usp=sharing#scrollTo=zw9WCBC_zJQ2)

## Resultados Obtidos

Acurácia: 100%

Precisão Média: 100%

Recall Médio: 100%

F1-Score Médio: 100%

## Instruções de uso

1. Abrir o notebook no Google Colab.
2. Instalar as dependências necessárias.
3. Executar as células em sequência.
4. O dataset será baixado automaticamente via KaggleHub.
