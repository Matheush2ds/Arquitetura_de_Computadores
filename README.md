# Arquitetura_de_Computadores
Atividades feitas usando a linguagem de máquina "Assembly", durante o período de aulas em Arquitetura de Computadores.


👉 CALCULAR_MÉDIA: Elabore um programa que o usuário informa 4 notas (0 a 10) e programa informa se o mesmo foi aprovado, reprovado ou recuperação.
Condições: Média maior ou igual a 6 --> Aprovado; Média menor que 6 e maior igual a 3 --> Recuperação; Média menor que 3 reprovado.


👉 BANCO: Elabore um programa que simula um sistema de operações com um saldo bancário: 
Operação 1:depósito de um valor
Operação 2: saque de um valor
Operação 3: Visualizaçao da quantia
Operação 4: Encerrar operação (finalizar programa).
Obs: Enquanto não encerrar operação, as operações 1,2 e 3 podem ser repetidas diversas vezes.

👉 FATORIAL: Elabore uma calculadora que receba e calcule o fatorial de um número inteiro. 

👉 CALCULA_DOBRO: Converta o programa abaixo para assembly mips
int main(){
	int x,y;
	x = 2;
	y = dobro(x);
	printf("Dobro: %d\n", y)
}
int dobro (int a){
	int dobro;
	dobro = 2*a;
	return dobro;	
}

