# Respostas das questão do capítulo 1

## Questão 1

R: Abstração e Gerência de Recursos 

## Questão 2

R:  Por prover interfaces de acesso ao dispositivo, tornar os aplicativos independentes do hardware e definir interfaces de acesso homogêneas para dispositivos com tecnologias distintas.

## Questão 3

R:  Executando os aplicativos simultaneamente em velocidade adequada, gerando filas de acesso para que não ocorram conflitos entre processos. O principal desafio ao implantar essa solução e impedir que os recursos dos sistema seja usados por um só usuário.

## Questão 4

R:Seu tempo de resposta é conhecido no melhor e pior caso de operação. É classificados em soft real-time systems e hard time-systems, a perda de prazo implica na degradação do serviço prestado, e no hard-time systems, a perda de praxo pode causar graves consequências.

## Questão 5

R: É como se fosse o coração do sistema operacional responsável  por todo gerenciamento dos demais recursos utilizados pelas aplicações, além de implantaras abstrações utilizadas pelos aplicativos.


## Questão 6

R:Não, porque poderia desestabilizar o sistema inteiro, provocando conflitos e uma lentidão.


## Questão 7

R:Sim, se houvesse a divisão de processamento entre os níveis.


## Questão 8

R:Interrupções são causadas por dispositivos externos ao processador, exceções são eventos causados pelo próprio processador e traps são eventos causados por softwares.


## Questão 9

R:O processador perde tempo para varrer todos os dispositivos do sistema para verificar se há eventos a serem tratados ou não.


## Questão 10

R:Função. Porque ela é uma função da biblioteca padrão de entrada/saida, ela abre o arquivo cujo nome é indicado por filename;


## Questão 11

R:
Arquitetura					               Benefícios							                      Deficiências

°Sistemas Monolíticos				      • Desempenho.						                     • O mal funcionamento de uma
																	                                             aplicação do núcleo pode se alastrar e levar
																	o sistema ao travamento ou a instabilidade.
																	• Manutenção mais complexa;
																	• Evolução mais complexa.




Sistemas em Camadas				        • Separação de código;					    • Aumento no número de classes existentes no sistema.
                                  • Permite a mudança de
                                implementação de uma
                                camada sem afetar a outra;
                                  • Possibilita que uma
                                 camada trabalhe com 
                                diferentes versões de outra 
                                camada.						





Sistemas Micronúcleo				      • Robustez e flexibilidade				• O custo associado às trocas 
																	de mensagens entre componentes
								 									pode ser bastante elevado, o que 
																	prejudica seu desempenho e diminui
								 									a aceitação desta abordagem.
								




Máquinas Virtuais					• Aperfeiçoamento e testes 				      • Custo adicional de execução dos
                          de novos sistemas operacionais;			    processos na máquina virtual em
                          • Executar diferentes sistemas 			    comparação com a máquina real.
                          operacionais sobre o mesmo 		 		      Esse problema não existe em
                          hardware, simultaneamente;				      ambientes cujo hardware suporta
                          • Simulação de configurações 			      o conceito de virtualização, como
                          e situações diferentes do mundo			    é o caso dos mainframes.
                           real, alterações e falhas no hardware 
                          para testes ou reconfiguração de um
                           sistema operacional;
                          • Diminuir custos com hardware.




## Questão 12

R:D,M,E,S,D,T,K,M,T,E.

## Questão 13

R:C,E,F

## Questão 14

R: opções D e E pois tratam diretamente com o hardware

## Questão 15

R:5,9,1,4,8,2,7,3,6

## Questão 16

R:A III e a IV estão erradas. III está errado pois é uma característica de sistemas distribuídos e não de rede e IV está errado pois é uma característica de sistemas desktop e não de tempo real.


## Questão 17

R:As afirmações II e V estão corretas.
I está errada pois uma máquina virtual de sistema é construída para suportar sistemas operacionais convidados completos; III está errada pois isso ocorre em sistemas monolíticos e não micro-núcleos; IV está errada pois sistemas monolíticos não tem uma manutenção fácil e sim complexa.

