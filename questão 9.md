Em uma Pir�mide de Testes, a equipe de desenvolvimento de software faz (ou pelo menos, deveria)
testes em todas as aplica��es produzidas. Testes de software s�o divididos primariamente em 
tr�s categorias: unit�rios, de integra��o e ponta a ponta.
Ao longo de todo o s�culo percebeu-se que h� uma economia muito grande no custo se forem efetuados
testes ao longo da cria��o e sendo efetuados as trativas pontuais necess�rias, do que encontrar
um erro ao final do processo e ter um gasto imenso para refazer todo o processo ou at� ter que 
iniciar um processo do zero. 


                               /\                                     
                              /  \                                  
                             /    \                                     
                            /      \                                     
                           / Ponta  \                                     
                          /    a     \                                     
                         /   Ponta    \                                     
                        /_ _ _ _ _ _ __\                                     
                       /                \                                     
                      /                  \                                     
                     /                    \                                     
                    /                      \                                     
                   /      Integra��o        \                                     
                  /                          \                                     
                 /_ _ _ _ _ _ _ _ _ _ _ _ _ __\                                     
                /                              \                                     
               /                                \                                     
              /                                  \                                     
             /             Unit�rio               \                                     
            /                                      \                                     
           /                                        \                                     
          /_ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ _ __\                                     

Testes unit�rios s�o feitos em partes isoladas do c�digo, para cada componente. � como se 
test�ssemos cada �pe�a� de um aparelho antes de coloc�-las. Vamos pensar que estamos montando
 um carro. Para garantir a seguran�a e evitar erros antes de unir todas as pe�as, � preciso 
testar cada uma delas separadamente. Por exemplo, para ter certeza que o ve�culo est� funcionando
normalmente antes de ir para o mercado, voc� tem que testar separadamente o freio, o volante, 
o c�mbio, etc.
Testes de integra��o s�o testes unit�rios feitos em mais de uma parte do c�digo. Eles juntam 
m�ltiplos componentes (normalmente 2) e verificam a comunica��o e integra��o entre os mesmos. 
Este � o teste que garante que a liga��o entre as pe�as est� funcionando. Pense no caso do carro
novamente: quando voc� utiliza o volante para dirigir-lo, a roda tem que responder ao pedido e 
mover o autom�vel.
Testes de ponta a ponta s�o testes que validam todo tipo de comportamento poss�vel dentro da 
aplica��o, ou seja, simulam a atividade do usu�rio final. Se usarmos o exemplo do carro, esse 
tipo de teste seria dirigir o ve�culo ap�s tudo estar finalizado, como se fosse o usu�rio normal.
Garantindo assim que todas as pe�as do produto final e as comunica��es entre elas est�o funcionando 
corretamente.