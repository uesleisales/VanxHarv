
##### Universidade Estadual de Santa Cruz
##### Curso : Ciência da Computação 
##### Matéria : OAC

## Arquitetura de Von Neumann vs Arquitetura de Harvard

### Tópicos Abordados.
#### 1   - A arquitetura de Von Neumann 
#### 2   - A arquitetura de Harvard
#### 3   - Von Neumann ou Harvard ?

### Introdução

##### Nesse documento será aprensentado os modelos, vantagens e desvantagens em se utilizar a arquitetura de Von Neumann ou a Arquitetura de Harvard . Também será mostrado um pouco da história de cada uma delas e principais realidades de aplicação. Cada uma dessas arquiteturas trabalha com diferentes modelos de organização visando melhorar a eficiência das máquinas dependendo da sua finalidade. Do ponto de vista de padronização pode-se afirmar que a maioria dos computadores atuais baseiam-se na arquitetura de Von Neumann que se baseia no principio de que é possível armazenar um programa na mesma memória de dados

## A Arquitetura de Von Neumann 

##### Essa arquitetura surgiu a partir do conceito de "Programa Armazenado" durante o desenvolvimento do projeto EDVAC, projetado para operar com números binário e manter programas armazenados na memória , diferentemente do ENIAC que operava com base decimal e não fazia o armazenamento. Para  fazer qualquer alteração em um programa desenvolvido no ENIAC era preciso muito tempo e isso se tornava algo bastante complicado e acabava se tornando inviável , pois o tempo era um fator bastante importante já que a finalidade da máquina era operar para fins da guerra. Diante dessa situação , John Von Neumann e diversas outras pessoas começaram a trabalhar no projeto do EDVAC. Apesar de muita gente está envolvida na construção dessa máquina, Jhon recebeu a maior parte dos créditos pois descreveu como o sistema deveria funcionar em um relatório de 101 páginas.
##### O esquema inicial de um computador com programa armazenado era dividido em cinco partes : Central Aritmética , Central de controle ,memória , gravação e entrada e saída .

### Central Aritmética (CA)
##### Nessa primeira parte foi descrito que o dispositivo deve ser capaz de realizar as operações básicas da aritmética como: subtrair , somar , dividir , verificar se o número é positivo , negativo ou igual a zero .Sendo assim é preciso que a máquina contenha unidades especializadas para executar tal função. A tecnologia utilizada para o desenvolvimento dessa central foi inicialmente relés, herança da telefonia, e posteriormente válvulas, herança da radiofonia. Com o aparecimento dos transistores, e depois dos circuitos integrados, os circuitos da unidade aritmética e lógica passaram a ser implementados com a tecnologia de semicondutores. 

### Central de Controle (CC)
#####  A sequenciação apropriada das operações pode ser executada, de forma mais eficiente, por um controle central. Através desse controle é feito o gerenciamento do sistema e de todo o fluxo de dados presente nele . Com isso toda essa informação é ordenada e controlada pela mesma .

### Memória (M) 
##### A memória é necessária para executar sequências de instruções.Quanto mais longas e complexas essas instruções forem , maior também deve ser a capacidade da memória .

### Gravação (R) 

#### Deve ser capaz de manter contato com a entrada e saída , que são como os neurônios correspondentes sensoriais e motores do cerébro humano .

### Input 
#### É necessário ter unidades para transferência das informações de Gravação para a a Memória.

### Output 
#### É necessário ter unidades que transfiram as informações da Memória para Gravação . 


#### Cada um desses elementos  são operados por componentes físicos que estão evoluindo ao longo do tempo desde os Relés electromagnéticos aos semicondutores .A variação física desses componentes influênciam em todos os processos das operações realizadas no computador , o que é algo bastante importante e o motivo de diversos estudos até hoje já a velocidade de processamento e quantidade de armazenamento precisam ser maiores a cada dia que passa .     
#### Essa arquitetura no geral possui um modelo menos complexos no ponto de vista de implementação apesar de fazer o armazenamento de dados e gerênciar como as instruções do processador devem se comportar. Atualmente grande parte das CPUs utilizam essa arquitetura, porém é comum encontrar partes que se baseam em outros tipos como a de Harvard . Mais vale ressaltar que em comparação com a arquitetura de Harvard ela é mais lenta pois o acesso aos dados na memória não é simultâneo .


## A Arquitetura de Harvard

#### A projeção dessa arquitetura aconteceu durante o período da 2ª guerra mundial onde seria aplicada ao Harvard Mark 1 desenvolvido entre as décadas de 30 e 40 sendo conhecido como o primeiro computador . Para que esse projeto fosse realizado foi preciso o apoio de alguns órgão e empresas de grande porte como por exemplo: A IBM e a marinha dos Estados Unidos . Por alguns anos a Arquitetura de Harvard ficou estacionada em questo de desenvolvimento e aplicação porém na década de 70 voltou a ativa.
#### O objetivo principal de sua criação foi o de aumentar de uma maneira significativa o desempenho do Microprocessador. O seu diferencial está na divisão dos barramentos de dados pertencente as memórias onde as instruções estão armazenadas e das memórias de dados . Sua utilização principal se dá em sistemas de uso bastante específicos como os DSP (specialized digital signal processing) . Ela também é bastante utilizada em microprocessadores pequenos que são aplicados em sistemas eletrônicos . 

## Von Neumann ou Harvard ?

#### A diferença principal entre as duas arquiteturas é que a de Harvard faz a separação do local de armazenamento , comportamento do processador e dos dados enquanto a de Jhon faz a utilização do mesmo local de memória para realizar esses processos. Com isso podemos citar algumas vantagens e desvantagens na utilização delas :
#### Na de Jhon os dados e instruções são movimentados á partir de um único barramento , acarretando assim em alguns problemas de lentidão durante os processos . Já na de Harvard isso não ocorre pois o caminho onde cada um deles são transportados estão em locais diferentes . Podemos concluir que do ponto de vista de desempenho a de Harvard tem uma grande vantagem em comparação com a de Von Neumann , porém como já foi dito , ela tem uma aplicação de maior escala em sistemas específicos , porém não deixa de estar presente em diversas projetos de larga escala . Apesar dessas conclusões não significa que a de Von Neumann seja uma má arquitetura , pois se fosse por isso não seria a mais usada em todo mundo , ressaltando que a questão de custos de produção e complexidade são fatores fundamentais para a aplicação e é exatamente essa "simplicidade" que torna essa arquitetura bastante acessível . 





