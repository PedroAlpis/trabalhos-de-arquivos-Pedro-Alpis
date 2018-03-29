# trabalho1-de-arquivos-Pedro-Alpis

-O código irá imprimir ao início, o tamanho do arquivo cep_ordenado.dat, o tamanho em bytes de cada registro de CEP, e a quantidade de registros.
-Após isso, ele irá realizar uma busca binária usando um loop while de forma que vai procurar sempre o registro do meio e comparar o CEP deste com o CEP de entrada digitado pelo operador. Se não for compatível o processo será repetido novamente, ou com a metade superior ou inferior, caso o CEP de entrada seja maior ou menor que o CEP encontrado no registro.
-Então, o código irá imprimir o quantidade de comparações "Contador: x" e após isso, imprimirá o registro encontrado.


-O Exemplo a seguir considera o CEP de entrada 20240192.

O OPERADOR DEVE ENTRAR NO TERMINAL COM:

gcc BuscaTeste.c -o BuscaTeste
./BuscaTeste 20240192

QUE IMPRIMIRÁ:

Tamanho do Arquivo: 209792100
Tamanho do Registro: 300
Tamanho do Arquivo em Registros: 699307



Contador: 19

RUA MONTE ALEGRE                                                        
SANTA TERESA                                                            
RIO DE JANEIRO                                                          
RIO DE JANEIRO                                                          
RJ
20240192

