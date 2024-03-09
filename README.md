# mslearn-ai-fundamentals-vision-studio

Explore cognitive services with Vision Studio on Microsoft Azure.

# 1 Detecção de Rostos

Criar um recurso:

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image1.png)

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image2.png)


Preencha todos os dados, conforme abaixo:

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image3.png)

Acessar o portal Vision Studio:
portal.vision.cognitive.azure.com

E acesse a área "View all resources":

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image4.png)

Definir o recurso como padrão:

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image5.png)

Volte para a tela anterior e selecione a aba "Face" e em seguida o módulo "Detect faces in an image":

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image6.png)

Selecione uma das imagens ou faça upload. Se houverem rostos na imagem, eles serão detectados.

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image7.png)


### Entrada de dados utilizado no teste

[face_detection.jpg](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/face_detection.jpg)

### Resultado no teste

[face_detection_result.json](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/face_detection_result.json)



# 2 Análise de Documentos

Na tela inicial do Vision Studio, acesse aba "Optical character recognition" e acesse o módulo "Extract text from images":

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image8.png)

Faça upload ou selecione uma das imagens. A descrição do texto virá no quadro a direta:

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image9.png)


### Entrada de dados utilizado no teste

[text_ocr.png](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/text_ocr.png)

### Resultado no teste

[text_ocr_result.json](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/text_ocr_result.json)




# 3 Análise de Imagens

Na tela inicial do Vision Studio acesse a aba "Image analysis". Em seguida selecione o módulo "Add captions to images":

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image10.png)

Faça upload ou selecione uma das imagens.
O resultado da análise será exibido no quadro a direito da tela, em texto puro e json.

![](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image11.png)


### Entrada de dados utilizado no teste

[image_caption.png](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image_caption.png)

### Resultado no teste

[image_caption_result.json](https://raw.githubusercontent.com/henriquebjr/mslearn-ai-fundamentals-vision-studio/main/images/image_caption_result.json)