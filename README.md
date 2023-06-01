# CIRCULO-POLIMORFICO

Crie uma classe abstrata Circulo (com
encapsulamento máximo) contendo o
atributo raio. Deve ter dois construtores :
um sem parâmetro, zerando o raio e outro
passando o raio como parâmetro. Deve
conter os seguintes métodos :
 diametro (2 * raio)
 area (π * raio²)
 perimetro/comprimento (2 *π * raio)
 e um que mostre os dados : raio, área,
perímetro e diâmetro.

Crie uma classe Esfera como subclasse
de Circulo. Deve ter dois construtores
conforme sua superclasse. Não deve
permitir cálculo de diâmetro, perímetro e
comprimento. Deve conter os métodos :
 area (4 * área do círculo)
 volume (4/3 * π * raio³)
 e um que mostre os dados : raio, área e
volume.

 Crie uma classe Cilindro (com encapsulamento
máximo) como subclasse de Circulo. Esta classe
contém o atributo altura. Deve ter dois construtores
conforme sua superclasse : um sem parâmetro,
zerando o raio e a altura e outro passando o raio e a
altura como parâmetro. Não deve permitir cálculo de
diâmetro, perímetro e comprimento. Deve conter os
métodos :
 area lateral (comprimento da base * altura)
 area ( 2 * área da base + área lateral)
 volume (área da base * altura)
 e um que mostre os dados : raio, altura, área da
base, perímetro da base, diâmetro da base,
área lateral, área e volume

Crie um programa polimórfico chamado
LerEsferaCilindro que contenha o método
lerTipo. Este programa deve ler o tipo e,
enquanto o usuário não desejar sair, crie uma
esfera ou cilindro, leia e mostre os dados. A
leitura do raio deve ser apenas uma para as
duas classes e o mostrar dados também.

 Obs : Escreva as saídas no vídeo à medida
que o programa for sendo executado.
