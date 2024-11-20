<h1>WeCare</h1>


A economia de energia é uma prática fundamental para a sustentabilidade e redução de custos, especialmente em ambientes corporativos ou residenciais. Este projeto, desenvolvido pela iniciativa WeCare, tem como objetivo criar soluções inteligentes para promover boas práticas de consumo energético. 
O foco principal é utilizar inteligência artificial para identificar a presença de pessoas em um ambiente, automatizando o controle de luzes.

Com o auxílio de visão computacional, o sistema detecta automaticamente se há pessoas no local e, com base nessa informação, decide manter as luzes ligadas 
ou apagá-las. Essa abordagem busca minimizar o desperdício de energia, proporcionando uma solução eficiente e sustentável.


Descrição do Problema


O problema identificado é o desperdício de energia causado por luzes que permanecem acesas em ambientes desocupados. Em muitos casos, isso ocorre por esquecimento ou falta de sistemas automatizados para gerenciar o consumo de eletricidade.

Para resolver essa questão, foi desenvolvido um modelo baseado em visão computacional que utiliza imagens capturadas de câmeras em tempo real para detectar a presença ou ausência de pessoas em um ambiente.



Metodologia

A metodologia seguiu as etapas descritas abaixo:

1. Coleta e Preparação do Dataset

O dataset foi criado utilizando a plataforma RoboFlow, onde foram incluídas imagens de ambientes com e sem pessoas.

As imagens foram rotuladas manualmente com duas classes principais:

Person: Quando há pessoas no ambiente.

No-Person: Quando o ambiente está vazio.

Divisão dos dados em treino (80%), validação (10%) e teste (10%) para garantir a generalização do modelo.

2. Treinamento do Modelo

Modelo utilizado: YOLOv5

Ferramentas:

Plataforma para treinamento: Colab

Métrica de avaliação principal: mAP (Mean Average Precision).

Resultados Obtidos

Os resultados do modelo foram avaliados com base nos dados de teste. Os principais resultados incluem:

Precisão (Accuracy): 94.8%

mAP: 48.3%




Conclusão

O projeto WeCare conseguiu desenvolver uma solução funcional para economizar energia através da detecção automática de presença, podendo facilitar e automatizar tarefas repetitivas do nosso dia a dia, além de prevenir esquecimentos e desperdícios.

Link: https://youtu.be/WUSvgJVZxik
