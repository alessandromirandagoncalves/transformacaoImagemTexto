# Extração de texto a partir de imagem

O desafio proposto pela Dio era extrair texto a partir de imagens.

O primeiro passo foi criar uma conta na Azure (portal.azure.com) escolhendo a opção gratuita ou Pay For Use.
Escolhi a segunda opção por nmão e enquadrar na primeira.

Depois criei um grupo de recurso chamado inst-ml-dio, conforme visto abaixo:

![image](https://github.com/user-attachments/assets/aa3c2c15-d391-4709-ad28-c13cddbd27c3)

Feito isto, acessei o portal do Vision Studio na URL https://portal.vision.cognitive.azure.com

Associei ao grupo de recursos criado na Azure no passo anterior.
Depois escolhi a opção Extrat text from images, como visto a seguir:
![image](https://github.com/user-attachments/assets/84d7e547-97e9-4f7e-a77b-88d5d6c4939f)

Escolhi a imagem com texto abaixo:

![a_invencao_abraco](https://github.com/user-attachments/assets/336655c5-7f44-45bb-8a2c-ad967e0876a8)

Após o reconhecimento ficou assim:

![a_invencao_abraco_com_texto_extraído jpg](https://github.com/user-attachments/assets/4a91c8de-1ae6-4f99-ac30-f6759857ceaf)

E a versão final somente texto:
![a_invencao_abraco_somente_texto](https://github.com/user-attachments/assets/c2baffe8-420b-4c24-aff7-5d7de6683ad7)

O uso da ferramente é bem intuitivo, além de ser rápido.
As possibilidades são incríveis: recuperação de documentos danificados, digitalização de texto a partir de documentos que só existem em versão impressa, reconhecimento de caligrafia...

Sobre os custos é bom observar porque pode ser que em ambientes pesados em produção eles podem ser bem altos.

A sugestão é fazer pequenos testes e observar os valores cobrados.
