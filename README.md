# Trabalho de Visão Computacional - FIAP

### Modo de uso do código.

o trabalho de visão computacional apresenta alguns steps conforme as seções descritas no colab.

1. Limpeza de pasta no colab para a criação de pastas utilizadas no trabalho;
2. Instalação de pacotes que são utilizados no código (dlib, mediapipe, DFSD);
3. Importação de pacotes Utilizados;
4. Criação de uma pasta para armazenamento do vídeo gravado e modelos utilizados (dlib);
5. Baixar os modelos do dlib na pasta disponibilizada anteriormente;
6. Através de um código JavaScript, realizamos a captura de um video no colab e o exportamos com a formatação (webm);
7. Devemos baixar o video disponibilizado anteriormente e adicionar na mesma pasta criada (/content/videos/recorded-video.webm);
8. Executar o detector de faces e cálculo de prova de vida válida (Validar se o usuário do vídeo piscou os olhos).
9. Após a execução do vídeo, nós teremos um output com o prefixo "_processado" (/content/videos/recorded-video_processado.webm), e nele é possível identificarmos a validação de prova de vida e detecção facial.
