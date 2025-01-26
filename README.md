# Classificação de Flores Utilizando Transfer Learning com Deep Learning

Nesse projeto utilizo Transfer Learning para classificar imagens de flores em 5 categorias: margarida, dente de leão, rosas, girassóis e tulipas. Realizei a implementação em Python no ambiente Google Colab, usando uma base de dados de flores no TensorFlow.

![exemplo_flores](https://github.com/user-attachments/assets/f383de93-199d-4ec7-975c-b05e3be75ce0)


# Tecnologias e Ferramentas Utilizadas
* Linguagem: Python

*  Ambiente de Desenvolvimento: Google Colab

*  Bibliotecas Principais:
   * TensorFlow/Keras
   * Matplotlib
   * NumPy
*  Base de Dados: imagens de flores do TensorFlow (https://storage.googleapis.com/download.tensorflow.org/example_images/flower_photos.tgz)

# Estrutura do Projeto
* transfer-learning.ipynb: Código-fonte principal para treinar e avaliar o modelo.
* flowers_photos: Diretório que contém um arquivo .zip com as imagens das flores organizadas em subpastas, sendo cada subpasta correspondente a uma classe.
* README.md: Documentação do projeto.

# Base de Dados
Contém:
* 633 imagens de margaridas
* 898 imagens de dente-de-leão
* 641 imagens de rosas
* 699 imagens de girassóis
* 799 imagens de tulipas
As imagens foram organizadas em 5 pastas, cada uma de um tipo de flor pertencente. 


# Exemplos de Resultados

![exemplo_resultado](https://github.com/user-attachments/assets/1b3d6a31-ed85-40fb-bf0f-773c4663b275)


No conjunto de validação, observa-se uma estabilização tanto na acurácia quanto na perda, indicando que o modelo conseguiu aprender padrões relevantes dos dados.
