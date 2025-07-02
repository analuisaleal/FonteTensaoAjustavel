# **Fonte de Tensão Ajustável**

O projeto foi realizado para a disciplina 'SSC0180 – Eletrônica para Computação', ministrada pelo professor Eduardo do Valle Simões. Nele, busca-se projetar uma fonte de tensão ajustável entre 3v e 12v, com uma corrente de 100mA.

# Alunos
  * Ana Luísa Pereira da Silva Leal
  * Beatriz Aredes Teixera
  * Leonardo Oliveira Eid
  * Mariane Ferreira dos Santos

# Componentes

| Componente | Quantidade | Valor |
| -------- | ------- | ------- |
| Diodo Retificador 1N4007 LGE=1N4004 | 1 | R$ 0,20 |
| Capacitor 680uF X 50V | 1 |  R$ 4,90 |
| Led 5mm VM DIFUSO 333-2SDRD/S530-L PARALIGHT | 4 |  R$ 0,50 |
| Resistor CR25 120R Carvão | 10 |  R$ 0,07 |
| Resistor CR25 220R Carvão | 10 |  R$ 0,07 |
| Resistor CR25 5K6 Carvão | 10 |  R$ 0,07 |
| Resistor CR25 3K3 Carvão | 10 |  R$ 0,07 |
| Potenciômetro 1W  B10K B-16,5XE-20XR-7MM JH  | 1 |  R$ 7,00 |
| Transistor BC548B N 30V 0,1A 0,5W 300MHZ TO-92 FSC | 1 |  R$ 0,50 |
| Diodo Zener 13V  1W = 1N4743 SEMTECH | 1 |  R$ 0,50 |
| Total || R$25,80 |

## Cálculo dos Componentes
![imagem dos calculos](https://github.com/analuisaleal/FonteTensaoAjustavel/blob/main/C%C3%A1lculos%20do%20projeto%20.jpg)

## Diodos
* Os diodos são dispositivos semicondutores que permitem a passagem de corrente elétrica em apenas uma direção.
* A ponte retificadora tem diodos que são responsáveis por permitir a passagem da corrente elétrica em uma única direção, pois eles “abrem” ou “fecham” de acordo com o ciclo da corrente alternada.
* A ponte retificadora é chamada assim porque ela “retifica” a corrente alternada. A palavra “retificar” significa “tornar reto” ou “alinhar”, ou seja, a ponte retificadora acaba deixando “reta” a tensão alternada, que é a transformação para uma tensão contínua!

## Diodo Zener
* Regulador de tensão máxima. 
* Somente conduz corrente quando a tensão que chegar alcança a tensão nominal do diodo, que no caso deste projeto, será 13v. 
* Informalmente, o diodo Zener “trava” o valor da tensão em 13v, que é praticamente o valor de tensão máximo que queremos na saída da nossa fonte.

## Capacitador
* O capacitor serve para armazenar temporariamente uma certa carga durante um período crescente da tensão e descarrega no período subsequente.
* É responsável por carregar o sistema quando a tensão (vinda da ponte retificadora) está em declínio, estabilizando a tensão que vai para o restante do circuito e criando o "ripple".

## Led
* Componente eletrônico capaz de converter energia elétrica em fonte de luz.
* Indica a passagem de corrente no circuito.
  
## Resistores
* Dispositivos eletrônicos que limitam a corrente elétrica em um circuito.

## Potenciômetro
* Serve para regular a voltagem que passará pelo transistor.
* Através dele, é possível ajustar a tensão de acordo com o dispositivo conectado (3v e 12v).

## Transistor
* Serve para ajustar a corrente que será alimentada ao dispositivo.
* Amplifica a corrente sem exigir que uma grande corrente passe pelo resistor ligado ao Zener.

# Imagens do projeto

# Circuito no Falstad
![imagem do circuito no falstad](https://github.com/analuisaleal/FonteTensaoAjustavel/blob/main/circuit-20250701-2335.png)

# Protoboard no Tinkercad
![imagem da protoboard no tinkercad](https://github.com/analuisaleal/FonteTensaoAjustavel/blob/main/Fonte%20de%20Tens%C3%A3o%20Ajust%C3%A1vel.png)

# Esquemático no Eagle
![imagem do esquemático no software eagle](https://github.com/analuisaleal/FonteTensaoAjustavel/blob/main/schematic_eagle.png)

# PCB no Eagle
![imagem da pcb no software eagle](https://github.com/analuisaleal/FonteTensaoAjustavel/blob/main/pcb_eagle.png)

# Vídeo explicativo sobre o projeto
