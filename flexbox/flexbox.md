# Dois conceitos principais são importantes :

## Flex container e flex item : Flex container é toda tag que recebe o display flexbox. Flex item é todo elemento que está dentro do container.

## Flex container : como aplicar ? Utilizando a priedade display: flex; na tag desejada

Sem essa propriedade , os items de um container ficam naturalmente em colunas (block).Quando utilizamos essa propriedade , os elemen-
tos do container ficam ajustados em linhas horizontais.

# ATRIBUTOS RELACIONADOS AO FLEX CONTAINER:

## Flex-direction: é a forma de posicionar os elementos na vertical ou horizontal.Ainda podemos inverter a ordem dos elementos.

Primeiramente , precisamos ter o flexbox ativado.Sendo assim , o flex-direction é uma propriedade utilizada além do display:flexbox.
Seus falores podem ser :

flex-direction: row, row-reverse, column e column-reverse.

## Flex-wrap : é o atributo que permite ou não a quebra de linha. Usado quando elementos ultrapassam o limite do container

Quando utilizamos o wrap , os flex items irão se organizar respeitando o limite do container. Sem o wrap eles não respeitarão esse
limite.

flex-wrap: nowrap, wrap e wrap-reverse;

## Flex-flow : atributo que recebe valores de flex-direction e flex-wrap.

Portanto , podemos usar valores do flex wrap e direction juntos.

## Justify-content : atributo para posicionar elementos no eixo horizontal. Possui diversos valores:

flex-start - coloca os elementos no início da linha
flex-end - coloca elementos no final da linha
center - posicionará os elementos ao centro
space-between, around ou evenly - dá espaços entre os elementos diferenciando esses 3 tipos.

## Align-items : atributo para posicionar elementos no eixo vertical. Possui diversos valores :

flex-start, flex-end, stretch(os elementos se alongam tendo como referência o maior entre eles), baseline e center.

## Align-content : semelhante ao align-items, entretanto, posiciona todo o conteúdo.Possui como valores:

flex-start, flex-end, center , stretch , space-between , space-around
