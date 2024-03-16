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
