# Desafio-Maquina-do-Tempo
Neste desafio, dados os valores dos três créditos da máquina, seu programa deve dizer se é ou não possível viajar no tempo e voltar para o presente, fazendo pelo menos uma viagem e, no máximo, três viagens; sempre usando cada um dos três créditos no máximo uma vez.


Entrada
A entrada consiste de uma linha contendo os valores dos três créditos A, B e C (1 ≤ A, B, C ≤ 1000).

Saída
Seu programa deve imprimir uma linha contendo o caracter “S” se é poss ível viajar e voltar para o presente, ou “N” caso contrário.

RESOLUÇÃO:

const line = gets().split("")
const a = line[0];
const b = line[1];
const c = line[2];


if (a + b == c || a + c == b ||   b + c == a  ||   a == b   || c == b   ||  c == a ) {
    print("S");
} else {
    print("N");
}
