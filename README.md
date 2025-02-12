# BootCamp BairesDev - Machine Learning Practitioner


<p align="center">
<img 
    src="imagem/img_programmer_github.png"
    width="300"
/>
</p>

<p align="center">
<a href="https://dio.me/">
    <img 
        src="https://img.shields.io/badge/DIO-Code_The_Future-28DA77?logo=youtube" 
        alt="DIO - Code The Future">
</a>
<a href="https://dio.me/">
<img 
    src="https://img.shields.io/badge/🔴_LIVE_CODE-FF5E72" 
    alt="🔴 LIVE CODE">
</a>
</p>

<p align="center">
    
</p>

<div align="center">
    <audio src="output/podcast_editado.MP3" controls title="Podcast editado"></audio>
</div>

## Criando um Sistema de Reconhecimento Facial do Zero

 > ℹ️ **NOTE:** Este repositório foi desenvolvido durante o BootCamp BairesDev - Machine Learning Practitioner em parceria com a [DIO](https://dio.me)

Este projeto tem como objetivo aplicar o conhecimento difundido nas aulas teóricas de modo sendimentar através da prática a implementação de uma base de dados supervisionadas para treinamento da rede YOLO, utilizando a plataforma Labelme para treinamento e o Dataset da COCO.


## 💻 Tecnologias utilizadas no projeto

- [ChatGPT](https://chat.openai.com/) 
- [MidJourney](https://www.midjourney.com/app/)
- [Google Colab](https://colab.google/)
- [COCO](https://cocodataset.org/#download)
- [LabelMe](http://labelme.csail.mit.edu/Release3.0/)


## ✨ Como foi feito ?

- O Google Colab foi utilizado para executar os blocos de códigos
- O chatgpt foi utilizado para gerar insights sobre cálculo de métrica
- Midjourney para gerar imagens
- O COCO foi utilizado para prover o Dataset de treinamento
- O LabelMe teve como propósito treinamento na aplicação do rótulo nas imagens

## 🛠️ Instruções de execução

As instruções para a realização deste projeto foram difundidas no módulo Fundamentos e Práticas de Deep Learning do referido Bootcamp da DIO, onde além da explanação teórica foi disponibilizado orientações nos seguintes:
- Para quem estiver utilizar o transfer learning no COLAB
(https://colab.research.google.com/github/ultralytics/yolov3/blob/master/tutorial.ipynb)
- Para instruções para executar e instalar o software para rotular as imagens<br>
(http://labelme.csail.mit.edu/Release3.0/)

## Descrição

### Treinamento da Rede YOLO

A criação de uma base de dados para treinamento da rede YOLO (You Only Look Once) envolve três etapas principais: coleta e preparação das imagens, anotação (rotulagem) dos objetos e treinamento da rede neural.

1️⃣ **Criação da Base de Dados**
As imagens podem ser coletadas de bancos de dados públicos ou capturadas manualmente.
Devem ser organizadas em pastas separadas para treinamento (train) e validação (val), seguindo a estrutura exigida pelo YOLO.

2️⃣ **Anotação das Imagens com LabelMe**
O LabelMe é uma ferramenta de código aberto usada para criar rótulos em imagens no formato JSON. 
O processo de rotulagem inclui:
Abrir a imagem no LabelMe.
Criar caixas delimitadoras (bounding boxes) ou polígonos ao redor dos objetos de interesse.
Atribuir classes aos objetos de acordo com o modelo a ser treinado.

3️⃣ **Treinamento da Rede YOLO**
Após criar a base de dados, o treinamento do YOLO pode ser realizado no Google Colab ou localmente, utilizando a biblioteca Ultralytics YOLOv5. 
O processo inclui:
Clonar o repositório YOLOv5 e instalar as dependências.
Criar o arquivo data.yaml para especificar os caminhos do dataset e número de classes.

### Conclusão

🚀 O uso do LabelMe é essencial para a criação de bases de dados personalizadas, permitindo a anotação precisa de objetos em imagens. Com as anotações convertidas para o formato YOLO, é possível treinar a rede neural para detectar padrões específicos. O treinamento do modelo no YOLOv5 envolve configurar corretamente os diretórios, definir o arquivo data.yaml e ajustar hiperparâmetros para otimizar o desempenho. Após o treinamento, a validação dos resultados garante que o modelo esteja adequado para aplicações reais. Esse processo é fundamental para desenvolver sistemas de visão computacional eficientes, aplicáveis a diversas áreas como segurança, indústria e pesquisa.

## 👨‍💻 Novato

<p>
    <img 
      align=left 
      margin=10 
      width=80 
      src="https://cdn.jsdelivr.net/gh/alohe/avatars/png/memo_30.png"
</p>
<p>
    &nbspGutembergue Martins<br>
    <a href="https://www.linkedin.com/in/gutembergue-martins-38336a59" target="_blank">LinkedIn</a><br>
    <a href="https://github.com/gutembergue-martins" target="_blank">GitHub</a>
    
</p>
    
<br/><br/>
