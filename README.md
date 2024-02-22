# Reconhecimento Facial e transformação de imagens em Dados no Azure ML - Desafio de código.


* Autor: Davi Antonino Nunes da Silva


# Objetivo
* Repositório criado para entregar o projeto final da etapa: Reconhecimento Facial e Transformação de Imagens em Dados no Azure ML.


#  Requerimentos do projeto
### Como Entregar esse projeto?


* Chegou a hora de você construir um portfólio ainda mais rico e impressionar futuros recrutadores, para isso é sempre importante mostrar os resultados do seu esforço e como você os obteve deixando claro o seu racional, para isso faça da seguinte maneira:
* Crie um novo repositório no github com um nome a sua preferência
* Crie uma pasta chamada 'inputs' e salve as imagens que você utilizou
* Crie uma pasta chamado 'output' e salve os resultados de reconhecimento de texto nessas imagens
* Crie um arquivo chamado readme.md , deixe alguns prints descreva o processo, alguns insights e possibilidades que você aprendeu durante o conteúdo.
* Compartilhe conosco o link desse repositório através do botão 'entregar projeto'


## Links úteis
1. https://aka.ms/ai900-face
2. https://aka.ms/ai900-ocr
3. https://aka.ms/ai900-image-analysis


# Detect Faces in an image:
![AC_1](https://github.com/dansfisica85/DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/118570287/4db95b06-35e1-4a89-87c5-4afceaf22579)


![AC_2](https://github.com/dansfisica85/DIO---Reconhecimento-Facial-e-transforma-o-de-imagens-em-Dados-no-Azure-ML/assets/118570287/e3d32248-fd30-4d4c-b5a3-8db3d17aa4d0)

```ruby
[
  {
    "recognitionModel": "recognition_01",
    "faceRectangle": {
      "width": 499,
      "height": 712,
      "left": 364,
      "top": 421
    },
    "faceLandmarks": {
      "pupilLeft": {
        "x": 470,
        "y": 725.8
      },
      "pupilRight": {
        "x": 727.5,
        "y": 719.4
      },
      "noseTip": {
        "x": 586.4,
        "y": 860.7
      },
      "mouthLeft": {
        "x": 495.9,
        "y": 970.4
      },
      "mouthRight": {
        "x": 705.2,
        "y": 964.8
      },
      "eyebrowLeftOuter": {
        "x": 399.4,
        "y": 669.1
      },
      "eyebrowLeftInner": {
        "x": 523.5,
        "y": 669.8
      },
      "eyeLeftOuter": {
        "x": 425.6,
        "y": 726.9
      },
      "eyeLeftTop": {
        "x": 473.8,
        "y": 707.5
      },
      "eyeLeftBottom": {
        "x": 463.8,
        "y": 740.8
      },
      "eyeLeftInner": {
        "x": 516.8,
        "y": 728
      },
      "eyebrowRightInner": {
        "x": 651.8,
        "y": 671.6
      },
      "eyebrowRightOuter": {
        "x": 804.2,
        "y": 671.6
      },
      "eyeRightInner": {
        "x": 681.3,
        "y": 725.5
      },
      "eyeRightTop": {
        "x": 721.2,
        "y": 700
      },
      "eyeRightBottom": {
        "x": 730.9,
        "y": 734.8
      },
      "eyeRightOuter": {
        "x": 776.5,
        "y": 717.3
      },
      "noseRootLeft": {
        "x": 554,
        "y": 744.1
      },
      "noseRootRight": {
        "x": 628.2,
        "y": 741.7
      },
      "noseLeftAlarTop": {
        "x": 534.8,
        "y": 825.3
      },
      "noseRightAlarTop": {
        "x": 647.5,
        "y": 822.1
      },
      "noseLeftAlarOutTip": {
        "x": 516.5,
        "y": 871.6
      },
      "noseRightAlarOutTip": {
        "x": 670.1,
        "y": 871.1
      },
      "upperLipTop": {
        "x": 600.3,
        "y": 963.6
      },
      "upperLipBottom": {
        "x": 595.2,
        "y": 977.8
      },
      "underLipTop": {
        "x": 594.4,
        "y": 986.6
      },
      "underLipBottom": {
        "x": 596.7,
        "y": 1012.6
      }
    },
    "faceAttributes": {
      "mask": {
        "type": "noMask",
        "noseAndMouthCovered": false
      }
    }
  }
]
```
