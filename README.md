
##### Universidade Estadual de Santa Cruz
##### Curso : Ciência da Computação 
##### Matéria : OAC

## Arquitetura de Von Neumann vs Arquitetura de Harvard

### Tópicos Abordados.
#### 1   - A arquitetura de Von Neumann 
#### 1.1 - Vantagens e desvantagens de sua utilização
#### 2   - A arquitetura de Harvard
#### 2.1 - Vantagens e desvantagens de sua utilização
#### 3   - Von Neumann ou Harvard ?

### Introdução

##### Nesse artigo será aprensentado os modelos, vantagens e desvantagens em se utilizar a arquitetura de Von Neumann ou a Arquitetura de Harvard . Também será mostrado um pouco da história de cada uma delas e principais realidades de aplicação. Cada uma dessas arquiteturas trabalha com diferentes modelos de organização visando melhorar a eficiência das máquinas dependendo da sua finalidade. Do ponto de vista de padronização pode-se afirmar que a maioria dos computadores atuais baseam-se na arquitetura de Von Neumann que se basea no principio de que é possível armazenar um programa na mesma memória de dados

## A Arquitetura de Von Neumann 

##### Essa arquitetura surgiu a partir do conceito de "Programa Armazenado" duarante o desenvolvimento do projeto EDVAC(Electronic Discrete Variable Automatic Computer) projetado para operar com números binário e manter programas armazenados na memória diferentemente do ENIAC que operava com base decimal e não fazia o armazenamento. Esse projeto foi dirigido por John Von Neumann e diversas outras pessoas que estavam envolvidas , porém , Jhon recebeu a maior parte dos créditos pois descreveu como o sistema deveria funcionar em um relatório de 101 páginas.
##### O esquema inicial de um computador com programa armazenado era dividido em cinco partes : Central Aritmética , Central de controle ,memória , gravação e entrada e saida .

### Central Aritmética (CA)
##### Nessa primeira parte foi descrito que o dispositivo deve ser capaz de realizar as operações básicas da aritmética como: subtrair , somar , dividir , verificar se o número é positivo , negativo ou igual a zero .Sendo assim é preciso que a máquina contenha unidades especializadas para executar tal função. A tecnologia utilizada para o desnevolvimento dessa central foi inicialmente relés, herança da telefonia, e posteriormente válvulas, herança da radiofonia. Com o aparecimento dos transistores, e depois dos circuitos integrados, os circuitos da unidade aritmética e lógica passaram a ser implementados com a tecnologia de semi-condutores. 

### Central de Controle (CC)
#####  A sequenciação apropriada das operações pode ser executada, de forma mais eficiente, por um controle central.

### Memória (M) 
##### A memória é necessária para executar sequências de instruções.Quanto mais longas e complexas essas instruções forem , maior também deve ser a capacidade da memória .

### Gravação (R) 

#### Deve ser capaz de manter contato com a entrada e saida , que são como os neurônios correspondentes sensoriais e motores do cerébro humano .

### Input 
#### É necessário ter unidades para transferência das informações de Gravação para a a Memória.

### Output 
#### É necessário ter unidades que transfiram as informações da Memória para Gravação . 


#### Cada um desses elementos  são operados por componentes físicos que estão evoluindo ao longo do tempo desde os Relés electromagnéticos aos semicondutores .A variação física desses componentes influênciam em todos os processos das operações realizadas no computador , o que é algo bastante importante e o motivo de diversos estudos até hoje já a velocidade de processamento e quantidade de armazenamento precisam ser maiores a cada dia que passa .     


### Vantagens e desvantagens 

#### Essa arquitetura no geral possui um modelo menos complexos no ponto de vista de implementação apesar de fazer o armazenamento de dados e gerênciar como as instruções do processador devem se comportar. Atualmente grande parte das CPUs utilizam essa arquitetura, porém é comum encontrar partes que se baseam em outros tipos como a de Harvard . Mais vale ressaltar que em comparação com a arquitetura de Harvard ela é mais lenta pois o acesso aos dados na memória não é simultâneo .


## A Arquitetura de Harvard
#### A projeção dessa arquitetura aconteceu durante o período da 2ª guerra mundial onde seria aplicada ao Harvard Mark 1 desenvolvido entre as décadas de 30 e 40 sendo conhecido como o primeiro computador . Para que esse projeto fosse realizado foi preciso o apoio de alguns orgão e empresas de grande porte como por exemplo: A IBM e a marinha dos Estados Unidos . Por alguns anos a Arquitetura de Harvard ficou estacionada em questo de desenvolvimento e aplicação porém na década de 70 voltou a ativa.
#### O objetivo principal de sua criação foi o de aumentar de uma maneira significativa o desempenho do Microprocessador. O seu diferencial está na divisão dos barramentos de dados pertencente as memórias onde as instruções estão armazenadas e das memórias de dados . Sua utilização principal se dá em sistemas de uso bastante específicos como os DSP (specialized digital signal processing) . Ela também é bastante utilizada em microprocessadores pequenos que são aplicados em sistemas eletrônicos . 


