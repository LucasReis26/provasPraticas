<h1 align="center">Inserção e Impressão em Árvore Binária por Placa</h1>

## Descrição

Leia os dados de vários carros e insira-os em uma árvore binária ordenada pela placa. Em seguida, imprima os carros em ordem alfabética da placa.


## Entrada

Entrada: Cada linha contém os dados de um carro, no formato:

placa,modelo,tipo,chassi

A entrada termina com a linha:

FIM

## Saída

Saída: Lista ordenada dos carros conforme critério acima, um por linha, no formato:

placa modelo tipo chassi

## Classe

Classe Carro:

class Carro { String placa, modelo, tipo, chassi;

void ler(String linha) {

    String[] partes = linha.split(",");

    placa = partes[0]; modelo = partes[1]; tipo = partes[2]; chassi = partes[3];

}



void imprimir() {

    System.out.println(placa + " " + modelo + " " + tipo + " " + chassi);

}

}

Classe Principal:

public class Main { public static void main(String[] args) { // implementar inserção em árvore binária e impressão em ordem } }
