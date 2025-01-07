# Trabalho de Visão Computacional - FIAP

## Integrantes do grupo
* Cleber Veiga Galvão - 356846
* Danildo André Amorim dos Santos - 355182
* Victor Marcio Hayee Falcão -  354955
* Lucas Ribeiro Del Poggetto - 355220 

### Modo de uso do código.

o trabalho de visão computacional apresenta alguns steps conforme as seções descritas no colab.

1. Limpeza de pasta no colab para a criação de pastas utilizadas no trabalho;
2. Instalação de pacotes que são utilizados no código (dlib, mediapipe, DFSD);
3. Importação de pacotes Utilizados;
4. Criação de uma pasta para armazenamento do vídeo gravado e modelos utilizados (dlib);
5. Baixar os modelos do dlib na pasta disponibilizada anteriormente;
6. Realizar a captura de uma foto "base" utilizada no algoritimo de similaridade
7. Realizar uma nova captura para que seja feita uma comparação com a face base disponibilizada anteriormente;
9. Através de um código JavaScript, realizamos a captura de um video no colab e o exportamos com a formatação (webm);
10. Devemos baixar o video disponibilizado anteriormente e adicionar na mesma pasta criada (/content/videos/recorded-video.webm);
11. Executar o detector de faces e cálculo de prova de vida válida (Validar se o usuário do vídeo piscou os olhos).
12. Após a execução do vídeo, nós teremos um output com o prefixo "_processado" (/content/videos/recorded-video_processado.webm), e nele é possível identificarmos a validação de prova de vida e detecção facial.

<a target="_blank" href="https://colab.research.google.com/github/lpoggetto/fiap_liveness/blob/main/trabalho_computer_vision.ipynb">
  <img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/>
</a>

# Exemplo de funcionamento do código - etapa de face recogntion

# Foto base utilizada para comparação
![Alt text] (https://github.com/lpoggetto/fiap_liveness/blob/main/arquivos/foto_base.jpg)

# Retorno de recognition positivo
![Alt text] (https://github.com/lpoggetto/fiap_liveness/blob/main/arquivos/recognition_ok.png)

# Retorno de recognition negativo
![Alt text] (https://github.com/lpoggetto/fiap_liveness/blob/main/arquivos/recognition_nok.png)

# Exemplo de funcionamento do código - etapa de liveness
![caption](https://github.com/lpoggetto/fiap_liveness/blob/main/arquivos/recorded-video_processado.gif)
