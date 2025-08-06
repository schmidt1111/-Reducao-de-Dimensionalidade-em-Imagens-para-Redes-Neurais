🔍 Projeto de Conversão de Imagens TIFF/RAW para Escala de Cinza e Binarização

Este projeto implementa, com uso mínimo de bibliotecas, um processo de redução de dimensionalidade de imagens, transformando-as em:

Imagem original
Imagem em tons de cinza (0 a 255)
Imagem binarizada (preto e branco, 0 ou 255)
É uma versão simplificada, sem uso de bibliotecas de processamento de imagem complexas como OpenCV, NumPy ou imageio. Apenas Pillow (para manipulação básica de imagem) e matplotlib (para visualização) são utilizados.

✅ Funcionalidades
Leitura de imagens no formato TIFF ou RAW
Conversão para escala de cinza
Binarização com limiar fixo (127)
Exibição gráfica com matplotlib
Título dinâmico indicando o formato da imagem original
