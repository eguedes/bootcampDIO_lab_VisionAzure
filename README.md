## Laboratório: Reconhecimento Facial e transformação de imagens em Dados no Azure ML

Este repositório tem como objetivo entregar o projeto final do módulo "Reconhecimento Facial e transformação de imagens em Dados no Azure ML" do Bootcamp "Microsoft Azure AI Fundamentals" da DIO, ministrado pela Valéria Baptista.

O desenvolvimento deste projeto visa mostrar os resultados do processo guiado pelos tutoriais do Microsoft Learn de [Detecção de rostos](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/04-face.html), [Leitura de Textos](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/05-ocr.html) e [Análise de Imagens](https://microsoftlearning.github.io/mslearn-ai-fundamentals/Instructions/Labs/03-image-analysis.html).

Neste exercício, foi criado um recurso Azure AI servcies, em seguida testado sua utilização  no Vision Studio. 

### Criando um recurso Azure AI servcies

Seguindo o tutorial da Microsoft, foram utilizados os passos baixo para a criação do recurso.

1. Faça login no portal do [Azure](https://portal.azure.com) usando suas credenciais da Microsoft.
2. Selecione **+ Criar um recurso**, pesquise por *Azure AI services* e crie um novo recurso do Azure Machine Learning com as seguintes configurações:

    >**Assinatura**: Sua assinatura do Azure.

    >**Grupo de recursos**: Crie ou selecione um grupo de recursos.

    >**Região**: East US.

    >**Nome**: Insira um nome único para o seu espaço de trabalho.

    >**Pricing tier**: *Standard S0*

    >**By checking this box I acknowledge that I have read and understood all the terms below**: *Selecionado*

3. Selecione **Review + create** e depois **Create** e aguarde o final do deployment.

### Conecte o recurso Azure AI servcies ao Vision Studio

Em seguida, é preciso conectar o recuso criado ao Vision Studio.

1. Acesse o [Vision Studio](https://portal.vision.cognitive.azure.com/?azure-portal=true)

2. Faça login usando suas credenciais da Microsoft.

3. Na página principal, selecione **View all resources** em baixo do títulos **Getting started with Vision**.

4. Na página **Select a resource to work with**, marque a caixa de seleção à esquerda do nome do recurso criado e depois selecione **Select as default resource**

5. Feche a página de configurações clicando no "x" na parte superior direita da tela.

#### Detectando rostos no Vision Studio

Testando a função de deteção de rostos, foram usadas as imagens contidas na pasta [/inputs/rostos](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/tree/main/inputs/rostos).

Os resultados, foram os mostrados abaixo.

[![primeira](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/rostos/Face_01_rec.png?raw=true "primeira")](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/rostos/Face_01_rec.png?raw=true "primeira")

[![segunda](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/rostos/Face_02_rec.png?raw=true "segunda")](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/rostos/Face_02_rec.png?raw=true "segunda")

Os códigos *json* retornados, assim como as imagens acima estão na pasta [/outputs/rostos](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/rostos).

#### Extraindo textos no Vision Studio

Testando a função de extração de textos, foram usadas as imagens contidas na pasta [/inputs/texto](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/tree/main/inputs/texto).

Os resultados, foram os mostrados abaixo.

[![primeira](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR2_rec.jpg?raw=true "primeira")](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR2_rec.jpg?raw=true "primeira")

[![segunda](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR3_rec.jpg?raw=true "segunda")](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR3_rec.jpg?raw=true "segunda")

[![terceira](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR6-CreditCard_rec.jpg?raw=true "terceira")](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto/OCR6-CreditCard_rec.jpg?raw=true "terceira")

Os códigos *json* retornados, assim como as imagens acima estão na pasta [/outputs/texto](https://github.com/eguedes/bootcampDIO_lab_VisionAzure/blob/main/outputs/texto).
