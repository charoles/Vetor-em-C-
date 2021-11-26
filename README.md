///implemente um sistema onde o usuário entre com 5 valores e diga quantos dele são repetidos e suas posições.

#include <iostream>
using namespace std;

class vetores{ 		/// nome da classe;																	
int vetor[5];		/// variavel para ação no metodo;																			
int i, x, y;	
public: 

/// metodo para acesso fora da classe

vet(int vet[5]);  /// declaração do metodo																	
};

///ação do metodo - parametro x
int vetores::vet(int vet[5]){															
	for (i=1;i<=5;i++){
    		cout << "Digite o numero na posicao " << i << endl;
    		cin >> x;
    		vet[i] = x;
					}
///ação do metodo - parametro y
	for (i=1;i<=5;i++){																	
    for (y=1;y<=5;y++){
            if(vet[i] == vet[y]){
            if(i != y){
    cout << "O numero repetido " << vet[y] <<  " esta na posicao: " << i << endl; ///declara o numero repetido
        break;

    					}
								}
					}
					}
							}
int main(){ 																			
	int vet[5];			///declarou o nosso vetor
	vetores vetts;		///busca a variavel
	vetts.vet(vet);		///traz o objeto

		}
