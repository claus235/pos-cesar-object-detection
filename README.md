# Projeto Final - Modelos Preditivos Conexionistas

### Aluno: Cláusio Tibério Teixeira Barbosa

### Projeto
|**Tipo de Projeto**|**Modelo Selecionado**|**Linguagem**|
|--|--|--|
|Deteção de Objetos|ex.: YOLOv8|Tensorflow|

## Visão Geral
Este projeto é parte da disciplina de "RNA e Deep Learning" do curso de Pós Graduação em Engenharia e Análise de Dados do CESAR e tem como objetivo desenvolver um sistema de detecção de bueiros e buracos em ciclofaixas usando técnicas avançadas de Deep Learning. A motivação por trás desse projeto é aumentar a segurança dos ciclistas, identificando antecipadamente os obstáculos potenciais que eles podem encontrar ao pedalar em ciclofaixas urbanas. 

![Imagem](https://even3.blob.core.windows.net/clausio/Imagem-ParaGit.png)

### Funcionalidades Principais
- Detectar automaticamente bueiros e buracos em imagens capturadas pelo StreetView.
- Gerar marcadores visuais ou alertas para indicar a presença de obstáculos.
- Facilitar a identificação de áreas de risco para ciclistas e planejamento de rotas mais seguras.


## Performance

O modelo treinado possui performance de **47%**.

<img width="436" alt="image" src="https://github.com/claus235/pos-cesar-object-detection/assets/12860665/82479843-8c66-4aa1-9eae-42fc757a01fa">


As duas classes são:

|**Classe**|**Acurácia**|
|--|--|
|Bueiro|82%|
|Buraco|10%|


Acredito que o principal problema reside na quantidade de imagens que contêm buracos. Além disso, os buracos apresentam uma considerável variedade, tornando necessário aprimorar a análise do algoritmo.

### Output do bloco de treinamento

<details>
  <summary>Click to expand!</summary>
  
  ```text
    Você deve colar aqui a saída do bloco de treinamento do notebook, contendo todas as épocas e saídas do treinamento
  ```
</details>

### Evidências do treinamento

Matriz de Confusão:

<img width="647" alt="image" src="https://github.com/claus235/pos-cesar-object-detection/assets/12860665/f167f5f1-7c1a-4e2d-8a66-96f36702454d">

Exemplo de adição de imagem:

<img width="935" alt="image" src="https://github.com/claus235/pos-cesar-object-detection/assets/12860665/b91cf21d-0d49-4d3a-8b64-88b76cecedb8">

Exemplo de adição de imagem:
<img width="1036" alt="image" src="https://github.com/claus235/pos-cesar-object-detection/assets/12860665/4fa5b840-14ba-4633-a26a-ff56776cfafd">

Exemplo de adição de imagem:
<img width="1043" alt="image" src="https://github.com/claus235/pos-cesar-object-detection/assets/12860665/399322db-c011-442e-9756-e9960d0104a4">


## Roboflow

[https://app.roboflow.com/pessoal-kh5qm/detectar-perigo-em-ciclofaixas/](https://app.roboflow.com/pessoal-kh5qm/detectar-perigo-em-ciclofaixas/) 

## HuggingFace

Nessa seção você deve publicar o link para o HuggingFace
