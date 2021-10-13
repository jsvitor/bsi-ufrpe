# bsi-ufrpe
Bacharelado em Sistemas de Informação - Universidade Rural Federal de Peranambuco


# Fundamentos de Sistemas de Informação
Livro de apoio a disciplina:
> Stair, Ralph M.
> Princípios de sistemas de informação / Ralph M. Stair, 
> George W. Reynolds ; tradução Noveritis do Brasil ; revisão técnica Tânia Fátima Calvi Tait. – São Paulo: Cengage Learning, 2015.

<details>
	<summary>Resumo feito reproduzindo integralmente algumas partes do livro</summary>
  
## Hardware

  <details>
    <summary>toggle</summary>
    
### Sistemas de Computadores

* Cases de resoluções de problemas por meio dos Sistemas de Computadores.

#### Componentes do Hardware

* **Componentes de hardware.** 
	* Esses componentes incluem os dispositivos de entrada, dispositivos de saída, os de armazenamento primário e secundário e a unidade de processamento central (CPU). A unidade de controle, a unidade aritmética/lógica (ALU) e as áreas de armazenamento de registro constituem a CPU.

* UNIDADE DE PROCESSAMENTO CENTRAL (CPU, CENTRAL PROCESSING UNIT):  Cada unidade de processamento central consiste em três elementos associados: a unidade aritmética/lógica, a unidade de controle e as áreas de registro. 
* UNIDADE ARITMÉTICA/ LÓGICA (ALU, ARITHMETIC/ LOGIC UNIT): Componentes da CPU que realizam cálculos matemáticos e fazem comparações lógicas.
* UNIDADE DE CONTROLE: Parte da CPU que acessa sequencialmente as instruções do programa, decodificando‑as, e coordena o fluxo de dados de entrada e de saída da ALU, registradores, armazenamento primário e até mesmo o armazenamento secundário e vários dispositivos de saída.
* REGISTRADOR: Área de armazenamento de alta velocidade na CPU utilizada para o armazenamento temporário de pequenas unidades de instruções de programas e dados imediatamente antes, durante e depois da execução pela CPU.
* ARMAZENAGEM PRIMÁRIA (MEMÓRIA PRINCIPAL, MEMÓRIA): Parte do computador que guarda as instruções e dados do programa. FIGURA 3.1 

### DISPOSITIVOS DE PROCESSAMENTO E MEMÓRIA: POTÊNCIA, VELOCIDADE E CAPACIDADE

Os componentes responsáveis pelo processamento – CPU e memória

#### CARACTERÍSTICAS E FUNÇÕES DO PROCESSAMENTO

* **MIPS**: Milhões de instruções por segundo, uma medida de tempo de ciclo de máquina. 
* **MEGAHERTZ (MHZ)**: Milhões de ciclos por segundo, uma medida de velocidade de clock.
* **GIGAHERTZ (GHZ)**: Bilhões de ciclos por segundo, uma medida de velocidade de clock.
* **VELOCIDADE DE CLOCK**: Uma série de pulsos eletrônicos produzidos a uma taxa predeterminada que afeta o tempo de ciclo de máquina.
* *Devido a problemas de aquecimento ao busca atingir maiores velocidades de clock → Arquitetura energético‑eficiente* → **ARM**

#### Características físicas da CPU
* **LEI DE MOORE*:  A Lei de Moore é uma  hipótese que afirma que o número de transistores em um único chip dobrará a cada dois anos.

#### CARACTERÍSTICAS E FUNÇÕES DA MEMÓRIA

##### Capacidade de armazenamento

* BYTE (B): Oito bits que juntos representam um único caractere de dado. 

##### Tipos de memória

* MEMÓRIA DE ACESSO ALEATÓRIO (RAM, RANDOM ACCESS MEMORY): Tipo de memória na qual as instruções ou dados podem ser armazenados temporariamente.
* MEMÓRIA SOMENTE DE LEITURA (ROM, READ‑ONLY MEMORY): Tipo de memória não volátil
	* memória somente de leitura programável (**PROM, programmable read-only memory**), usada para guardar dados e instruções que nunca podem ser alterados;
	* memória somente de leitura programável e apagável (**EPROM, erasable programmable read‑only memory**), que é uma ROM programável e pode ser apagada e reutilizada;
	* e a memória somente de leitura programável e apagá‑ vel eletricamente (**EEPROM, electrically erasable programmable read‑only memory**), que é somente de leitura, que pode ser modificada pelo usuário e apagada e reprogra‑ mada repetidamente, por meio de aplicativos com tensão elétrica acima do normal.
* **MEMÓRIA CACHE**: Tipo de memória de alta velocidade que um processador pode acessar mais rapidamente do que a memória principal.

##### PCM, phase change memory → Curiosidade:

> Fabricantes estão competindo para desenvolver um chip de memória não
> volátil, que necessite de um mínimo de energia, ofereça velocidade
> extremamente rápida de es‑ crita e possa armazenar dados de forma
> precisa, mesmo após um grande número de ci‑ clos escreve‑e‑apaga. Tais
> chips devem eliminar a necessidade de RAM e simplificar e acelerar o
> processamento da memória. A memória de mudança de fase (PCM, phase
> change memory) é uma abordagem potencial para suprir tal dispositivo
> de memória. A PCM emprega material especial semelhante ao vidro que
> pode alterar seu estado físico, alternando entre estado cristalino de
> baixa resistência para um estado gasoso de alta re‑ sistência, por
> meio da aplicação de tensão para reorganizar os átomos do material.
> Espera‑se que essa tecnologia seja até 100 vezes mais rápida do que a
> memória flash e que possa ser usada por computadores de servidores por
> volta de 2016.7

#### MULTIPROCESSAMENTO

* MULTIPROCESSAMENTO: 
Execução simultânea de duas ou mais instruções.

* COPROCESSADOR: 
Parte do computador que acelera o processamento, executando instruções de tipos específicos enquanto a CPU trabalha em outra atividade de processamento.

* MICROPROCESSADOR MULTICORE: 
Microprocessador que combina dois ou mais processadores independentes em um único computador, para que possam compartilhar a carga de trabalho elevar a capacidade de processamento

#### COMPUTAÇÃO PARALELA

* COMPUTAÇÃO PARALELA: Execução simultânea da mesma tarefa em múltiplos processadores para se obter resultados mais rapidamente.

* SISTEMAS DE PROCESSAMENTO MACIÇAMENTE PARALELOS: Tipo de multiprocessamento que acelera o processamento por meio da conexão de centenas ou milhares de processadores para operar simultaneamente, ou em paralelo, no qual cada processador tem seu próprio barramento, memória, discos, cópia do sistema operacional e aplicativos.

* COMPUTAÇÃO EM GRADE: Uso de um conjunto de computadores, frequentemente pertencentes a vários indivíduos ou organizações, para trabalhar de maneira coordenada a fim de resolver problemas em comum.

#### ARMAZENAMENTO SECUNDÁRIO

* ARMAZENAGEM SECUNDÁRIA: Dispositivos que armazenam grandes quantidades de dados, instruções e informações de forma mais permanente do que o permitido pela memória principal.

> A seleção dos meios e dispositivos da armazenagem secundária necessita
> do entendimento de suas características principais – método de acesso,
> capacidade e portabilidade.

#### MÉTODOS DE ACESSO

* ACESSO SEQUENCIAL: Método de recuperação no qual os dados devem ser acessados na ordem em que são armazenados.

* ACESSO DIRETO: Método de recuperação, no qual os dados podem ser acessados sem a necessidade de ler e descartar outros dados.

* DISPOSITIVO DE ARMAZENAMENTO DE ACESSO SEQUENCIAL (SASD, SEQUENCIAL ACCESS STORAGE DEVICE): Dispositivo para acessar sequencialmente dados de armazenagem secundária.

* DISPOSITIVO DE ARMAZENAMENTO DE ACESSO DIRETO (DASD, DIRECT ACCESS STORAGE DEVICE): Dispositivo para acessar diretamente dados de armazenagem secundária.

#### DISPOSITIVO DE ARMAZENAMENTO SECUNDÁRIO

##### Dispositivos magnéticos de armazenamento secundário

* FITAS MAGNÉTICAS: Tipo de mídia de armazenagem secundária, usado hoje principalmente para armazenar backup de dados organizacionais críticos em caso de um desastre.
* DISCO MAGNÉTICO: Dispositivo de armazenamento direto com bits representados por áreas magnetizadas. "O Disco Rígido"

* MATRIZ REDUNDANTE DE DISCOS INDEPENDENTES/ DE BAIXO CUSTO (RAID, REDUNDANT ARRAY OF INDEPENDENT/ INEXPENSIVE DISKS): Método de armazenamento de dados que gera bits adicionais a partir dos dados existentes, permitindo que o sistema crie um “mapa de reconstrução” para que, se um disco rígido falhar, os dados perdidos possam ser recuperados.

* ESPELHAMENTO DE DISCO: Processo que fornece uma cópia exata que protege totalmente os usuários em caso de perda de dados.

* FITA VIRTUAL: Dispositivo de armazenamento que gerencia dados menos frequentemente consultados, de modo que parecem estar armazenados inteiramente em rolos de fitas, embora algumas partes possam estar realmente localizadas em discos rígidos mais rápidos.

#### Dispositivos de armazenamento óticos secundários

> Um dispositivo de armazenamento ótico usa lasers especiais para fazer
> a leitura e gravação de dados. Os lasers gravam os dados queimando
> fisicamente ranhuras nos discos. O dado é acessado diretamente do
> disco por um dispositivo de leitura ótica, que opera de modo
> semelhante a um tocador de disco compacto. Esse dispositivo de disco
> ótico utiliza um laser de baixa potência que mede a diferença na luz
> refletida, provocada pela ranhura (ou a falta dela) no disco.

* DISPOSITIVO DE ARMAZENAMENTO ÓTICO: Forma de armazenamento de dados que usa lasers para ler ou gravar dados.

* MEMÓRIA SOMENTE DE LEITURA EM DISCOS COMPACTOS (CD‑ROM, COMPACT DISC READ‑ONLY MEMORY): Forma comum de discos óticos nos quais os dados não podem ser modificados depois de gravados.

* DISCO DE VÍDEO DIGITAL (DVD, DIGITAL VIDEO DISK): Mídia de armazenamento de dados usada para armazenar videogames, softwares e vídeos.

#### Dispositivos de armazenagem secundária de estado sólido

> Dispositivos de armazenagem secundária de estado sólido (SSDs, solid
> state storage devices) armazenam os dados nos chips de memória em vez
> de mídias magnéticas ou óticas. Esses chips necessitam de menos
> energia e fornecem acesso mais rápido aos dados do que os equipamentos
> de armazenamento de dados magnéticos. Enquanto os discos rígidos podem
> fornecer de 250 a 350 IOPS (operações de entrada/saída por segundo ou
> operações de leitura/gravação por segundo), os SSDs mais avançados
> realizam a operação a uma taxa de meio milhão de IOPS.23

* Unidade flash: as unidades flash são dispositivos de armazenamento em estado sólido.

#### OPÇÕES DE ARMAZENAMENTO DAS EMPRESAS

#### TIPOS DE SISTEMA DE COMPUTADORES

##### COMPUTADORES PORTÁTEIS
##### COMPUTADORES NÃO PORTÁTEIS PARA ÚNICO USUÁRIO

##### SISTEMAS DE COMPUTADORES PARA MÚLTIPLOS USUÁRIOS

* SERVIDOR: Computador utilizado por muitos usuários para realizar tarefas específicas, como rodar aplicações de rede ou internet.
* ESCALABILIDADE: Habilidade para aumentar a capacidade de processamento de um sistema computacional para que possa lidar com mais usuários, mais dados ou mais transações em determinado período.
* SERVIDOR BLADE (SERVIDOR EM LÂMINA): Servidor que hospeda muitas placas‑mãe que incluem um ou mais processadores, memória, armazenamento e conexões de rede de computadores.
* COMPUTADORES MAINFRAME: Computador grande e potente, em geral compartilhado por centenas de usuários simultaneamente conectados à máquina por meio de rede.
* SUPERCOMPUTADOR: São máquinas mais potentes com maior velocidade de processamento e mais alto desempenho.
* UNIDADE DE PROCESSAMENTO GRÁFICO (GPU, GRAPHICS PROCESSING UNIT): Circuito especial muito eficiente na manipulação dos gráficos do computador. É mais rápido do que um chip de CPU para realizar operações de ponto flutuante e na execução de algoritmos, nos quais o processamento de grandes blocos de dados é feito em paralelo.

#### COMPUTAÇÃO VERDE
COMPUTAÇÃO VERDE: Programa que diz respeito à eficiência e responsabilidade ambiental de um projeto, manufatura, operação e descarte de produtos relacionados aos SI.

**A computação verde tem três metas**:

* reduzir o uso de materiais perigosos,
* permitir que as empresas abaixem os custos de energia (incluindo a potencial captação e taxas de aquisição) e
* permitir o uso seguro ou reciclagem de computadores e equipamentos relacionados.
  
  </details>
  


## Software

## SI


</details>
