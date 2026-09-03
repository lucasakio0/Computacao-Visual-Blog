# Teceira Aula de Computação Visual!

## O que você aprendeu durante essa aula?

Durante a terceira aula de computação visual nos foram apresentados diversos tópicos interessantes relacionados a transformações de intensidade (Operam individualmente nos pixels da imagem, processamento de ponto a ponto) e filtragem especial (Operam na vizinhança de cada pixel da imagem, processamento de vizinhança) e como os mesmos podem ser utilizados. 

Imagens em um tom de cinza (Exemplo de uma operação de intensidade)
- Um pixel de 1 byte = 8 bits, podendo apresnetar valores de 0 a 255 -> 256 niveis de cinza.
- 0 equivale a cor preta e 255 a cor branca

- Para obter o negativo de uma imagem devemos realizar a operação de

![Fórmula](Anotacao/Imagens/image.png)

### Exemplo: P' = 255 - P
Um pixel 220 -> 35
![Um exemplo de uma imagem em negativo](Anotacao/Imagens/negative.jpg)
Essa função também pode ser utilizada para realçar detalhes em imagens escuras que antes não poderiam ser identificados com facilidades, um outro exemplo muito bom é a imagem disponiblizada no slide do professor, em que médicos usam para facilitar a identificação de cancêr.
### Outro exemplo de alteração de intensidade é da adição e a multiplicação de um valor N:
                P' = P + N
. Essa operação aumenta o brilho de uma determinada imagem em N;
. Porém um detalhe importante é que toda imagem tem um limitador superior [0; 255], que se ultrapassado deve ser limitado ao número, de tal forma que resulta em um pixel branco.

### RGB - Red Blue Green possui 3 canais, onde cada um deles tem a intensidade de 0 a 255. Portanto cada pixel RGB normalmente ocupa 3 bytes (24 bits)
