# Bairesdev-machine-learning-training
Projetos desenvolvidos ao longo do bootcamp -DIO Bairesdev machine learning training

## Lab: Treinamento de Redes Neurais com Transfer Learning
utilizando como base a rede VGG16 e treinado com o base de dados Celebrity Face Image Dataset, disponível no kaggle.

Relatório de projeto: a rede foi treinado, contudo devido ao tamanho do dataset de treino/ a própria natureza da rede utilizada como base (a rede VGG16 foi criada para a detecção de objetos e não reconhecimento facial) a acurácia resultando deixou a desejar.

Possíveis ajustes: utilizar métodos de data augmentation para expandir o dataset e criar mais variedade das imagens (canais de cores, posição das imagens e etc) alterar a rede base para uma rede mais especializada em detecção facial. Alterar o tamanho dos batches e número de épocas de treinamento teve pouco impacto no resultado.

## Lab: Redução de Dimensionalidade em imagens para Redes Neurais
Utilizando a bilioteca PIL (Python Imaging Library) a função recebe uma imagem e um código que define a conversão, retornando uma imagem em escala de cinza ou binarizada.

## Lab: Cálculo de Métricas de Avaliação de Aprendizado
Define funções para calcular as principais métricas para avaliação de modelos de classificação de dados, acurácia, sensibilidade(recall), especificidade, precisão e F-score.
Possui também uma função para gerar uma curva de ROC contúdo, devido a indisponibilidade de todos os dados necessários para a sua devida plotagem, gera apenas os pontos por classe e não a curva de aprendizado por épocas de treinamento.
