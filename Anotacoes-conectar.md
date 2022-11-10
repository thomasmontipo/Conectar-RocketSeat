# Curso RocketSeat 👋


# Trilha: O que é Conectar?
  - Etapa para reunir mundo real com mundo da web;
  - Nomes técnicos;
  - Uma ferramenta na sua jornada;


**O que será ensinado:**
- Configurar ambiente DEV
- Lógica de programação
- Dados e manipulação de dados
- Significado de URL, HTTP, TCP, IP e etc
- Cliente / servidor
- Partes de um computador e o papel de cada uma delas
- Tipos de software
- Com a internet é possível
- Como computador se comunica na internet?
- Sistemas operacionais
- Tipos de aplicações WEB
- Linguagens de programação
<br>
***

## Módulo 1: Guia estelar de programação
**O que é programar?**:
<br>
Fundamentos da programação
<br>Web significa rede (tipo teia de aranha)
<br><br>
:arrow_right: É entender de algoritmos
- Algoritmo é um passo a passo (sequencia lógica de um processo)<br><br>
:arrow_right: Lógica de programação:
- Aplicação dos passos (construção do algoritmo)<br>

:arrow_right:O computador pensa/entende?
- Não, ele processa e calcula, realizando as atividades que são passadas a ele pela linguagem de programação

**Programar é resolver problemas**
____
**Como funciona a WEB?**

Código    | Significado                       | Função    | Obseravação
--------- | ------                            | ------    | --------
HTTP      | HyperText Transfer Protocol       | Trocar mensagens entre computadores;  |
URL       | Uniform Resource Locator          | Garantir que os pacotes cheguem corretamente ao destino   | 
TCP       | Transmission Control Protocol     | Garantir que os pacotes cheguem corretamente ao destino    |
IP        | Internet Protocol                 | Endereçamento dos computadores através de um número (72.76.21.21). É como se fosse o CPF do computador.    |
DNS       | Domain Name Servers               | Converter um Domínio (tipo https://www.rocketseat.com.br) em um número IP
Proxies   |Qualquer dispositivo que ligue a sua máquina ao servidor| Encaminhar os pacotes de dados para os IPs
<br>
____
<br>:heavy_exclamation_mark:**Lógica de funcionamento**:heavy_exclamation_mark:<br><br>
:arrow_right: Usuário digita a URL;<br>:arrow_right: Inicia-se a comunicação entre TCP (Computador do cliente até o servidor); <br>:arrow_right: Endereço é convertido para o IP (ex. 76.76.21.21) pelo DNS; <br>:arrow_right: Pedido percorre os Proxies; <br>:arrow_right: Chega ao servidor; <br>:arrow_right: Servidor analisa o pedido e dá uma resposta; <br>:arrow_right:Retorna por todo o caminho realizado;<br>:arrow_right:**O processo acontece diversas vezes por que é uma requisação para "linguagem"**<br>
____


## Módulo 2: Computador, Software e Hardware
**Hardware**<br>
- Parte Física do sistema:<br>:arrow_right: Mouse, teclado, monitor, memória e etc...<br>
- Periféricos:
<br>:arrow_right:Dispositivos auxiliares que são usados para enviar ou receber informaões do computador
<br>:arrow_right: Mouse, teclado, usb, webcam
<br><br>

**Software**
 - Conjunto de instruções que permite controlar um aparelho eletrônico;
 - Parte lógica do computador

**Firmware**
- É o software responsável por realizar a comunicação entre o periférico e o computador


**Drivers**
- É a ponte que realiza a comunicação entre o sistema operacional e o firmware dos dispositivos eletrônicos.
- Para todos Hardware existe um Driver


**Sistemas operacionais**
- Software mais importante do computador
- Responsável por quantificar o uso de Memória, processador, memória RAM e gerenciamento (SSD ou HD)


**Programas**
<br>:arrow_right: No inglês:
- Software: Qualquer conjunto de códigos que façam a diretriz de um computador.
- Program: Um aplicativo, tipo o Excel.
<br>**Obs:** Todo programa de computador é um software, mas nem todo software é um programa. 
 
**Memória RAM**
- É uma memória temporária;
- Exemplo: Você abre o Word e começa a digitar. Antes de salvar, tudo que está ali fica armazenado na memória RAM. Ao salvar, libera-se a memória RAM e os dados são salvos no SSD ou HD.
- Sempre que você desligar, tudo será apagado da memória RAM.

**HD e SSD**
- São dispositivos que armazenam dados;
- HD: Partes móveis, discos e um cabeçote. Pode arranhar, e é gravado/ lido por um imã de forma magnética.
- SSD: Sem partes móveis, apenas chips

**Processador**
- É o cérebro do computador
- Transforma as informações em binário
- Tem um formato de um chip
- Transforma dados em informações, carrega páginas, fazer downloads, abrir e executar programas.
- A velocidade que seu computador abre ou executa é diretamente relacionado à velocidade do processador 

## Módulo 3: Internet, Roteadores e Servidores
**O que é a internet**
- A internet são redes interligadas pelo mundo todo;
- É uma conexão fisica por cabos. (Com excessão do roteador/antena até o seu dispositivo)

**Rede de computadores e a comunicação**
- Rede de dispositivos que permite a transmissão de dados;

**IP e MAC Address**
- IP: Número dado para dispositivo pelo provedor de internet (CPF do aparelho - Muda sempre que necessário)
- MAC Address: Número dado para a especificação do seu Hardware do dispositivo de rede (nunca muda)

**Servidor**
- Servidor é utilizado para "SERVIR" dados;
- Serve para alocar sites;

**DNS**
- Serve para, ao invés de digitar números na barra de url do site, digitarmos nomes (domínios)

**HTTP**
- Ao entrar em um site, o navegador cria uma requisição (que é HTTP ou HTTPS) e manda para o servidor;
- O servidor retorna todos os elementos para que aquela página possa ser exibida;
- O "s" de HTTPS significa "Secure", que é um criptografia para impedir/dificultar a ação de pessoas mal intensionadas.

## Módulo 4: Sistemas Operacionais
- É a interface entre o usuário e a máquina
- Gerencia tudo: Hardware, software e o gerenciamento de tarefas;
<br>OS dois grandes grupos de sistemas operacionais são:
<br>

Unix    |Windows
--------|------
Linux   | Windows 7
OS X    | Windows 10
Android | Windows Server
IOS     |

**Tipos de interfaces do usuários**
<br><br>GUI<br>
- Graphical User Interface
- Utiliza uma interface gráfica para

<br>CLI<br>
- Command-Line Interface
- **NÃO** utiliza uma interface gráfica;
- Tudo é feito por linha de comando;

**Kernel**
- É a primeira coisa que incia no software
- Tem a capacidade de conversar com o hardware e o software
<br> **Responsabilidades**<br>
- Gerenciamento da memória, processos, armazenamento e dispositivos

![Kernel](imagens/kernel.png)


**Gerenciamento de processos**
- Processo é um programa em execução
- Scheduling - Agendamento de processos
  - Sabe qual processo está executando no momento
- Thread
  - Divisão de um processo em vários pedaços
- Multitask (Multitarefas)
  - Dois processos não rodam ao mesmo tempo, apenas um. Mas é tão rápido que parece que estão funcionado em paralelo.

  **Gerenciamento de arquivos**
  - Em inglês: File System
  - Organiza e armazena os arquivos
    - Vídeos, imagens e etc...


  **Ferramentas de gerenciamento**
- Gerenciamento de tarefas:
  - Windows:Task mananger (Gerenciador de tarefas)
  - MAC: Activity Monitor (Monitor ativo) 
<br><br>
- Gerenciamento de pacotes
  - Chocolatey, brew, apt, snap
  - Podem ser programas, gerenciamento de programas e etc...

## Módulo 5: Linguagem de Programação
**Termos técnicos**
<br><br>:arrow_right: *Codar*
- Escrever para o computador
- Linguagem humana x máquina

:arrow_right: Código VS programa
  - Programa: é um conjunto de códigos que realizam funções
  - Código: Uma sequência lógica. 

  **Low-level e High-level**
- Low-Level
  - Linguagem de baixo nível, mais próximo do binário
  - São milisegundos mais rápidas que as linguagens high-level
- High-Level
  - Linguagem como Python, JS e etc
  - Mais próximas das linguas comumente faladas (Inglês)

  **Sintaxe**
- Conjunto de regras de escrita
- Cada linguagem tem suas regras
- Existem palavras reservadas