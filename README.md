# PETRILab

![Python](https://img.shields.io/badge/python-2.7.9-blue)

## Sobre

O PETRILab é um software multiplataforma desenvolvido inteiramente em Python 2. Ele permite a modelagem e simulação de Redes de Petri Interpretadas para Controle (RPIC), tendo suporte a todos seus elementos: lugares, transições, arcos ordinários e inibidores, eventos, condições e ações.

Com uma interface gráfica simples e intuitiva, o usuário consegue modelar e simular passo-a-passo sua RPIC de forma rápida e prática, afim de estudá-la e aprimorá-la.

Além disso, o software conta com uma conversão automática de RPICs em diagramas Ladder, como proposto no artigo "M. V. Moreira e J. C. Basílio - Bridging the Gap Between Design and Implementation of Discrete-Event Controllers, IEEE Transactions on Automation Science and Engineering, pp. 48-65, 2013".

Recursos:

- Suporte a todos os elementos de uma RPIC
- Simulação funcional, a prova de efeito avalanche e loopings infinitos
- Conversão automática da RPIC em diagramas Ladder


## Instalação

Para utilizar o programa, baixe todos os arquivos deste projeto, coloque no local de preferência e execute o arquivo 'petrilab.pyw'. É necessário ter o Python 2 instalado no sistema para que o programa funcione. Se tiver tanto o Python 2 quanto o Python 3, será necessário chamar o programa via linha de comando com "python2 petrilab.pyw".

## Uso

O arquivo "PETRILab - Guia do Usuário.pdf" contém um guia com as principais funcionalidades do programa. Ele foi extraído do projeto de graduação "A. L. Souza - PETRILab: Uma Plataforma para Simulação e Geração de Diagramas Ladder de Controladores a Eventos Discretos Modelados por Redes de Petri, UFRJ, 2015".

## Desenvolvimento

O projeto está sob a licença MIT, e pode ser desenvolvido livremente. O manual técnico "PETRILab - Manual Técnico.pdf", também retirado do projeto de graduação citado acima, contém algumas instruções que podem auxiliar no desenvolvimento. Vale notar que o projeto ainda está programado em Python 2.
