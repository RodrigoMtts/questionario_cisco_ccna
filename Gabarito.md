# 1 As redes de hoje

1. Quantas e quais são as características básicas que os arquitetos de rede devem atender para atender às expectativas do usuário?

- **São 4: Tolerância a falhas, Escalabilidade, Qualidade de serviço(QoS) e Segurança.**

2. Por que uma rede tolerante a falhas tem conexões redundantes?

- **Para oferecer caminhos alternativos caso um dispositivo ou link falhe.**

3. Qual a diferença de uma conexão ADSL e SDSL?

- **As conexões ADSL (DSL Assimétrico) tem velocidade de download é maior que a de upload e são usado geralmente por pequenos escritórios e escritórios domésticos.**
- **As conexões SDSL (DSL Simétrica) fornece uploads e downloads nas mesmas velocidades altas e geralemente são usadas por empresas.**

4. Quantos e quais são os requisitos fundamentais para atingir o objetivo de uma rede segura?

- **São 3: Confidencialidade, Integridade e  Disponibilidade.**

5. Qual caracteristica de uma rede garante que o tráfego impotante para uma organização seja priorizado quando ocorre congestionamento na rede.

- **Qualidade do Serviço (QoS)**

6. Qual é a operação realizada pelos dispositivos de rede quando ocorre o congestionamento do tráfego na rede?

- **Os dispositivos retêm os pacotes na memória até que os recursos estejam disponíveis para transmiti-los.** 


# 2 Introdução

1. Oque é o shell?(2.1.1)

- **A interface do usuário que permite que os usuários solicitem tarefas especificas do computador.**

2. Como podem ser feitas as solicitações por meio do Shell?(2.1.1)

- **CLI (Command Line Interface) ou GUI (Graphic User Interface).**

3. Qual a função do kernel?(2.1.1)

- **Comunicar-se com o hardware e o software de um computador e gerenciar como os recursos de hardware são usados para anteder aos requsitos de software.**

4. Como um Switch irá operar assim que ele for conectado a rede sem seja realizada qualquer tipo de configuração?(2.1.4)

- **Um switch encaminhará o tráfego por padrão e não precisa ser explicitamente configurado para operar.**

5. Qual a diferença entre tráfego "out-of-band" e "in-band"?(2.1.4)

- **out-of-band: O acesso out-of-band refere-se ao acesso por meio de um canal dedicado de gerenciamento que é utilizado somente para fins de manutenção do dispositivo.**

- **in-band: requerem serviços de rede ativos no dispositivo, incluindo uma interface ativa configurada com um endereço.**

6. Para que serve as tecnologias Secure Shell(SSH) e Telnet?(2.1.4)

- **Estabelecer remotamente uma conexão CLI** 

7. Qual a desvantagem entre Telnet em relação ao Secure Shell(SSH)?(2.1.4)

- **O telnet não fornece uma conexão segura e criptografada** 

8. O software Cisco IOS separa o acesso de gerenciamento em quais modo de comando?(2.2.1)

- **Modo EXEC de usuário e Modo EXEC privilegiado**

9. Qual a diferença entre os modos de comandos Modo EXEC de usuário e Modo EXEC privilegiado?(2.1.1)

- **O modo permite acesso a apenas um número limitado de comandos de monitoramento básico e é geralmente chamado de modo "view-only".**

- **O modo permite acesso a todos os comandos e recursos e usuário pode usar qualquer comando de monitoramento e executar a configuração e comandos de gerenciamento.**

10. Como sair que qualquer modo de subconfiguração para o modo EXEC privilegiado?(2.2.4)

- **Inserindo o comando end ou a combinação de teclasCtrl+Z.**

11. Qual a estrutura básica dos comandos do Cisco IOS?(2.3.1)

- **Comando seguido por quaisquer palavras-chave e argumentos apropriado**

12. Qual a diferença entre palavras-chave e argumentos nos comandos do IOS?(2.3.1)

- **Palavra-chave - Este é um parâmetro específico definido no sistema operacional**
- **Argumento - Isso não é predefinido; é um valor ou variável definido pelo usuário**

13. Quais são as formas de ajuda disponíveis  no IOS?(2.3.3)

- **Ajuda sensível ao contexto e verificação da sintaxe do comando.**

14. Quais perguntas a ajuda sennsível ao contexto ajuda a responder rápidamente?(2.3.3)

- **Quais comandos estão disponíveis em cada modo de comando?**
- **Quais comandos começam com caracteres específicos ou grupo de caracteres?**
- **Quais argumentos e palavras-chave estão disponíveis para comandos específicos?**

15. Como se utiliza a ajuda sensível ao contexto?(2.3.3)

- **Para acessar a ajuda sensível ao contexto, basta inserir um ponto de interrogação,?, na CLI.**

16. Como funciona a verificação de sintaxe do comando?(2.3.3)

- **Verifica se um comando válido foi inserido pelo usuário. Se o interpretador não puder entender o comando sendo inserido, ele fornecerá feedback descrevendo o que está errado com o comando.**

17. Qual o atalho usada para abortar pesquisas de DNS, tracerouts, pings, etc?(2.3.5)

- **Ctrl-Shift-6**

18. Qual comando do Cisco IOS altera o nome do dispositivo e em qual modo deve ser utilizado?(2.4.1)

- **hostname. Dever ser utilizado no modo de configuração global.**

19. Quais diretrizes de nomeclatura devem ser adotados na hora de nomear um dispositivo de rede?(2.4.1)

- **Começar com uma letra;**
- **Não conter espaços;**
- **Terminar com uma letra ou dígito;**
- **Usar somente letras, números e traços;**
- **Ter menos de 64 caracteres.**

20. Estando no modo EXEC do usuário, quais comandos devem ser inseridos para proteger o acesso via porta console?(2.4.3)

- **enable**
- **configure terminal**
- **line console 0**
- **password \<senha>**
- **login**

21. Estando no modo EXEC do usuário, quais comandos devem ser inseridos para proteger o modo EXEC privilegiado?(2.4.3)

- **enable**
- **configure terminal**
- **enable secret \<senha>**

20. Estando no modo EXEC do usuário, quais comandos devem ser inseridos para proteger o acesso via vty?(2.4.3)

- **enable**
- **configure terminal**
- **line vty 0 15**
- **password \<senha>**
- **login**

21. Como criptografar todas as senhas de texto simples?(2.4.4)

- **No modo de configuração global entre o comando service password-encryption**

22. Como uma mensagem de banner pode ser inserida?(2.4.5)

- **banner motd \<caracter delimitador> \<mensagem qualquer> \<caracter delimitador>**

23. Para que serve o comando login?(2.4.8)

- **Habilita a autenticação de senha para os modos aos quais foram inseridos uma senha**

24. Quais são os dois arquivos de sistema que armazenam a configuração do dispositivo?(2.5.1)

- **startup-config e running-config**

25. Qual a função do arquivo startup-config?(2.5.1)

- **Este é o arquivo de configuração salvo armazenado na NVRAM. Ele contém todos os comandos que serão usados pelo dispositivo na inicialização ou reinicialização. O flash não perde seu conteúdo quando o dispositivo está desligado.**

26. 25. Qual a função do arquivo running-config?(2.5.1)

- **sto é armazenado na memória de acesso aleatório (RAM). Ele reflete a configuração atual. A modificação de uma configuração ativa afeta o funcionamento de um dispositivo Cisco imediatamente. A RAM é uma memória volátil. Ela perde todo o seu conteúdo quando o dispositivo é desligado ou reiniciado.**

27. Qual comando é utilizado para visualizar as configurações em execução, e em qual modo deve ser utilizado?(2.5.1)

- **show running-config. Deve ser usado no modo EXEC privilegiado.**

28. Qual comando é utilizado para visualizar as configurações de inicialização, e em qual modo deve ser utilizado?(2.5.1)

- **show startup-config. Deve ser usado no modo EXEC privilegiado.**

29. Qual comando é utilizado para salvar as alterações feitas na configuração em execução no arquivo de configuração de inicialização, e em qual modo deve ser utilizado?(2.5.1)

- **use o comando do modo EXEC privilegiado copy running-config startup-config.**

30. Qual comando é utilizado para recarregar as configurações de inicialização salvas anteriormente, e em qual modo deve ser utilizado?(2.5.2)

- **reload. Use-se no modo EXEC privilegiado.**

31. Qual o comando utilizado para restaurar as configurações padrão no arquivo de configurações de inicialização?(2.5.2)

- **Usando o comando do modo EXEC privilegiado erase startup-config.**

32. Como é representada a estrutura de um endereço IPv4?(2.6.1)

- **Por quatro números decimais entre 0 e 255 separados por pontos.**

33. O que é a máscara de sub-rede?(2.6.1)v

- **Uma máscara de sub-rede IPv4 é um valor de 32 bits que diferencia a parte da rede do endereço da parte do host.**

34. Quantos bits tem e como é representado o IPv6?(2.6.1)

- **Os endereços IPv6 têm 128 bits e são escritos como uma sequência de 32 valores hexadecimais**

35. Como o caracter ":"(dois pontos) deve ser na estrutura de um endereço IPv6?(2.6.1)

- **Grupos de quatro dígitos hexadecimais são separados por dois pontos (:).**

36. Os endereços IPv6 diferenciam maiúsculas e minúsculas?(2.6.1)

- **Não.**

37. O que é uma porta SVI e para que ela é usada?(2.6.3)

- **Switch virtual interface é uma inteface utilizada para acessar o switch remotamente.**

38. Qual é a sequência de comando utilizados para configurar acesso remoto a um switch a partir do modo EXEC privilegiado?(2.7.4)

- **configure terminal**
- **interface vlan 1**
- **ip address \<ip> \<mascara de rede>**
- **no shutdown**

39. Qual comando é util para verificar a configurações das interfaces?(2.8.1)

- **show ip interface brief.**

40. Qual comando pode ser usado para testar a conectividade com outro dispositivo na rede ou em um site na Internet?(2.8.2)

- **ping**

41. Quanto tempo demora para uma configuração realizada no IOS passar a ter efeito?(2.9.4)

- **Toda alteração na configurações passar a ter efeito imediato.**

42. Qual tipo de acesso está protegido em um roteador ou switch Cisco com o comando enable secret?(2.9.4)

- **EXEC privilegiado.**

43. Qual é o SVI padrão em um switch Cisco?(2.9.4)

- **VLAN1**

44. Quando um nome de host é configurado por meio da Cisco CLI, quais são as três convenções de nomenclatura incluídas nas diretrizes?(2.9.4)

- **O nome de host deve ter menos de 64 caracteres;**
- **O nome de host não deve conter espaços; e**
- **O nome de host deve começar cpm uma letra.**

45. Um roteador com um sistema operacional válido contém um arquivo de configuração armazenado na NVRAM. O arquivo de configuração tem uma senha secreta (enable secret), mas não uma senha de console. Quando o roteador inicia, qual modo será exibido?(2.9.4)

- **modo EXEC usuário.**

46. Qual localização de memória em um roteador ou switch Cisco perderá todo o conteúdo quando o dispositivo for reiniciado?(2.9.4)

- **RAM**

47. Qual funcionalidade é fornecida pelo DHCP?(2.9.4)

- **Atribuição automática de um endereço IP a cada host.**

48. Qual local de memória em um roteador ou switch Cisco armazena o arquivo de configuração de inicialização?(2.9.4)

- **NVRAM**

49. A qual sub-rede o endereço IP 10.1.100.50 pertence se uma máscara de sub-rede de 255.255.0.0 for usada?(2.9.4)

- **10.1.0.0**

# 3 Protocoloes e modelos

1. Todos os métodos de comunicação têm três elementos em comum, quais?(3.1.1)?

- **Fonte da Mensagem (remetente);**
- **Destino da mensagem (destinatário); e**
- **Canal.**

2. Quais são os tipos de opção de entrega de uma mensagem?(3.1.10)

- **Unicast;**
- **Multicast; e**
- **Broadcast.**

3. Qual é o processo de conversão de informações na forma adequada para transmissão?(3.1.12)

- **Codificação.**

4. Qual etapa do processo de comunicação está relacionada com a identificação adequada do endereço do remetente e do destinatário?(3.1.12)

- **Formatação.**

5. Quais são os três componentes do timing da mensagem?(3.1.12)

- **Controle de Fluxo;**
- **Método de acesso; e**
- **Tempo de resposta excedido.**

6. Qual método de entrega é usado para transmitir informações para um ou mais dispositivos finais, mas não todos os dispositivos na rede?(3.1.12)

- **Multicast.**

7. Qual método de entrega é usado para transmitir informações para todos os dispositivos na rede?(3.1.12)

- **Broadcast.**

8. Qual método de entrega é usado para transmitir informações para um ou dispositivo na rede?(3.1.12)

- **Unicast.**

9. BGP e OSPF são exemplos de que tipo de protocolo?(3.2.4)

- **Roteamento.**

10. Qual é o propósito da função de sequenciamento na comunicação de rede?(3.2.4)

- **Para rotular exclusivamente segmentos transmitidos de dados para remontegem adequada pelo receptor.**

11. Quais é o principal conjunto de protocolo da atualidade?(3.3.2)

- **TCP/IP.**

12. Em quais camadas a suite de protocolos TCP/IP é divida?(3.3.2)

- **Aplicação;**
- **Transporte;**
- **Internet; e**
- **Acesso à rede.**

13. Verdadeiro ou falso. As organizações de padrões geralmente são neutras para o fornecedor?(3.4.5)

- **Verdadeiro.**

14. Esta organização de padrões está preocupada com os documentos Request for Comments (RFC) que especificam novos protocolos e atualizam os existentes.(3.4.5)

- **Internet Engineering Task Force (IETF).**

15. Essa organização de padrões é responsável pela alocação de endereços IP e gerenciamento de nomes de domínio.(3.4.5)

- **Internet Assigned Numbers Authority (IANA).**

16. Que tipos de padrões são desenvolvidos pela Electronics Industries Alliance (EIA)?(3.4.5)

- **Fiação elétrica;**
- **conectores; e**
- **Racks de 19 polegadas.**

17. Que tipos de padrões são desenvolvidos pela Associação da Indústria de Telecomunicações (TIA)?(3.4.3)

- **Dispositivos de Voz sobre IP (VoIP);**
- **Comunicações via satélite;**
- **Equipamentos de rádio; e**
- **Torres celulares.**

18. Pelo que a Associação da Indústria de Telecomunicações (ISOC) é responsável?(3.4.2)

- **Resposável por promover o desenvolvimento aberto e a evolução do uso da internet em todo o mundo.**

19. Pelo que a Internet Architecture Board (IAB) é responsável?(3.4.2)

- **Responsável pelo gerencimaneto e desenvolvimento geral dos padrões da internet.**

20. Qual organização de padrões é responsável pelas pequisas de longo prazo relacionadas à internet e aos protocolos TCP/IP?(3.4.2)

- **Força-Tarefa de Pesquisa na Internet (IRTF).**

21. Qual a hierarquia de organizações de padrões envolvidos com o desenvolvimento e suporte da internet?(3.4.2)


![](figuras/		suporte-da-internet.jpg)	

22. Qual a hierarquia de organizações de padrões envolvidos com o desenvolvimento e suporte do TCP/IP?(3.4.2)

![](figuras/suporte-da-tcp-ip.jpg)

23. Que tipos de padrões são desenvolvidos pela Setor de Normalização das Telecomunicações da União Internacional de Telecomunicações (ITU-T)?(3.4.3)

- **Compactação de vídeo;**
- **Televisão por IP (IPTV); e**
- **Comunicações de banda larga, como DSL.**

24. Qual a correspondencia entre as camadas dos modelos OSI e TCP/IP?(3.5.4)

![](figuras/modelo-ois-tcp-ip-correspondencia.jpg)

25. Quais os principais benefícios da segmentação?(3.6.1)

- **Aumenta a velocidade(Muitos emissores podem transmitir ao mesmo tempo de forma que ninguém precise ficar esperando); e**
- **Aumenta a eficiência(apenas os pacotes perdidos precisão ser reenviados).**

26. O que é a multiplexação?(3.6.1)

- **Muitas comunições diferentes podem ser intercaladas no mesmo link sem que ele fique ocupado de forma exclusiva por qualquer uma delas.**

27. O que é o encapsulamento?(3.6.3)

- **À medida que os dados da aplicação são passados pela pilha de protocolos em seu caminho para serem transmitidos pelo meio físico de rede, várias informações de protocolos são adicionadas em cada nível. Isso é conhecido como o processo de encapsulamento.**

28. Qual é o nome que uma parte de dados assume em qualquer camada de rede?(3.6.3)

- **unidade de dados de protocolo (PDU).**

29. Qual os nome dos PDUs em cada camada de rede?(3.6.3)

![](figuras/nome-dos-pdus.jpg)

30. Qual é o processo de dividir um grande fluxo de dados em partes menores antes da transmissão?(3.6.6)

- **Segmentação.**

31. Qual é a PDU associada à camada de transporte?(3.6.6)

- **Segmento.**

32. Qual camada de pilha de protocolo encapsula dados em quadros?(3.6.6)

- **Enlace de dados.**

33. Qual é o nome do processo de adição de informações de protocolo aos dados à medida que ele move para baixo a pilha de protocolos?(3.6.6)

- **Encapsulamento.**

34. Um endereço IP contém quais partes?(3.7.2)

- **Parte da rede (IPv4) ou Prefixo (IPv6); e**
- **Parte do host (IPv4) ou ID da interface (IPv6).**

35. Verdadeiro ou falso? Quadros trocados entre dispositivos em diferentes redes IP devem ser encaminhados para um gateway padrão.(3.7.9)

- **Verdadeiro.**

36. Verdadeiro ou falso? A parte mais à direita de um endereço IP é usada para identificar a rede à qual um dispositivo pertence.(3.7.9)

- **Falso.**

37. O que é usado para determinar a parte da rede de um endereço IPv4?(3.7.9)

- **Mascara de sub-redes.**

38. Qual é a ordem dos dois endereços no quadro do link de dados?(3.7.9)

- **MAC de destino, MAC de origem.**

39. Verdadeiro ou falso? Os endereços do Link de Dados são físicos, de modo que eles nunca mudam no quadro do link de dados da origem para o destino.(3.7.9)

- **Falso.**

40. Que tipo de comunicação enviará uma mensagem para todos os dispositivos em uma rede local?(3.8.2)

- **Broadcast.**

41. Na comunicação entre computadores, qual é o objetivo da codificação de mensagens?(3.8.2)

- **Converter informações para o formato adequado para transmissão.**

42. Qual opção de entrega de mensagens é usada quando todos os dispositivos precisam receber a mesma mensagem simultaneamente?(3.8.2)

- **Broadcast.**

43. Quais são os dois benefícios da utilização de um modelo de rede em camadas?(3.8.2)

- **Evita que a tecnologia em uma camada afete outras camadas; e**
- **Ajuda no projeto do protocolo.**

44. Qual é a finalidade dos protocolos nas comunicações de dados?(3.8.2)

- **Fornece as regras necessárias para possibilitar um tipo especifico de comunicação.**

45. Qual endereço lógico é usado para entrega de dados para uma rede remota?(3.8.2)

- **Endereço IP de destino.**

46. Qual é o termo geral que é usado para descrever um pedaço de dados em qualquer camada de um modelo de rede?(3.8.2)

- **Unidade de dados de protocolo(PDU).**

47. Cite dois protocolos que funcionam na camada de Internet?(3.8.2)

- **IP, ICMP, ARP e etc.**

48. Qual camada do modelo OSI define serviços para segmentar e remontar os dados das comunicações entre os dispositivos finais?(3.8.2)

- **Transporte.**

49. Que tipo de comunicação enviará uma mensagem para um grupo de destinos de host simultaneamente?(3.8.2)

- **Multicast.**

50. Que processo é usado para receber dados transmitidos e convertê-los em uma mensagem legível?(3.8.2)

- **Decodificação.**

51. O que é feito com um pacote IP antes de ser transmitido por um meio físico?(3.8.2)

- **É encpsulado em um quadro da Camada 2.**

52. Qual é o processo usado para inserir uma mensagem dentro de outra mensagem para a transferência da origem para o destino?(3.8.2)

- **Encapsulamento.**

53. Um cliente Web está enviando uma solicitação para uma página da Web para um servidor Web. Do ponto de vista do cliente, qual é a ordem correta da pilha de protocolo que é usada para preparar o pedido de transmissão?(3.8.2)

- **HTTP, TCP, IP, Ethernet.**

# 4 Camada Física

1. Verdadeiro ou falso? A camada física está relacionada apenas às conexões de rede com fio.(4.1.3)

- **Falso.**

2. Verdadeiro ou falso? Quando um quadro é codificado pela camada física, todos os bits são enviados pela mídia ao mesmo tempo.(4.1.3)

- **Falso.**

3. A camada física do dispositivo receptor passa bits até qual camada de nível superior?(4.1.3)

- **Enlace de dados**

4. Qual PDU é recebida pela camada física para codificação e transmissão?(4.1.3)

- **Quadro.**

5. Os serviços e protocolos na suíte TCP/IP são definidos por qual organização padronizadora?(4.2.1)

- **Internet Engineering Task Force (IETF).**

6. Os padrões da camada fśicia são implementados em hardware ou software?(4.2.1)

- **Hardware.**

7. Quais áreas funcionais são abordados pela camada física?(4.2.2)

- **Compnentes Físicos, Codificação e Sinalização.**

8. O que é a codificação?(4.2.3)

- **Um método para converter um fluxo de bits de dados em um "código” predefinido.**

9. O que são códigos?(4.2.3)

- **Os códigos são agrupamentos de bits usados para fornecer um padrão previsível que pode ser reconhecido tanto pelo emissor quanto pelo receptor.**

10. Quais codificações são usadas para os padrões Ethernet 10BASE-T, 100BASE-T e 1000BASE-T respectivamente?(4.2.3)

- **Manchester, 4B/5B e 8B/10B.**

11. O que é a sinalização?(4.2.4)

- **A maneira como os bits são representados.**

12. Como os bits podem ser representados no meio físico?(4.2.4)

- **Sinais elétricos, ópticos ou microondas sem fio.**

13. O que é a largura de banda e oque ela mede?(4.2.5)

- **Largura de banda é a capacidade na qual um meio pode transportar dados. A largura de banda digital mede a quantidade de dados que podem fluir de um lugar para outro durante um determinado tempo.**

14. Quais fatores determina a largura de banda prática de uma rede?(4.2.5)

- **As propriedades do meio físico; e**
- **As tecnologias escolhidas para sinalização e detecção de sinais de rede.**

15. O que é latência?(4.2.6)

- **O tempo necessário para os dados viajarem de um ponto a outro, incluindo atrasos.**

16. Como acontece um gargalo na rede?(4.2.6)

- **Quando um segmento da rede tem uma taxa de transferência menor que os demais.**

17. O que é taxa de transferência?(4.2.6)

- **É a medida da transferência de bits através da mídia durante um determinado período.**

18. Quais fatores influenciam na taxa de transferência?(4.2.6)

- **A quantidade de tráfego;**
- **O tipo de tráfego; e**
- **A latência criada pelo número de dispositivos de rede encontrados entre a origem e o destino.**

19. O que é Goodput?(4.2.6)

- **É a taxa de transferência menos a sobrecarga de tráfego para estabelecer sessões, reconhecimentos, encapsulamento e bits retransmitidos.**

20. Que mídia usa padrões de microondas para representar bits?(4.2.7)

- **Sem fio.**

21. Que mídia usa padrões de luz para representar bits?(4.2.7)

- **Fibra optica.**

22. Que mídia usa pulsos elétricos para representar bits?(4.2.7)

- **Cobre.**

23. Qual deles é o nome para a capacidade de um meio para transportar dados?(4.2.7)

- **Largura de banda.**

24. Qual destes é uma medida da transferência de bits pela mídia?(4.2.7)

- **Taxa de transferência.**

25. Cite possíveis fontes de EMI e RFI?(4.3.1)

- **Dispositivos de ondas de rádio e eletromagnéticos, como luzes fluorescentes ou motores elétricos.**

26. O que é Diafonia?(4.3.1)

- **Diafonia é uma perturbação causada pelos campos elétrico ou magnético de um sinal em um fio para o sinal em um fio adjacente.**

27. Quais são as três principais mídias de cobre usadas em redes?(4.3.2)

- **UTP, STP e Cabo Coaxial.**

28. Quais são os tipos de conectores Coaxiais?(4.3.5)

- **BNC, Tipo N e Tipo F.**

29. Qual das seguintes anexa antenas a dispositivos sem fio? Também pode ser empacotado com cabeamento de fibra óptica para transmissão de dados bidirecionais.(4.3.6)

- **Coaxial.**

30. Qual cabos combatem a EMI e RFI com técnicas de blindagem e conectores especiais?(4.3.6)

- **STP.**

31. Qual é a mídia de rede mais comum?(4.3.6)

- **UTP.**

32. Como o cabo UTP limita os efeitos da diafonia, EMI e RFI?(4.4.1)

- **Cancelamento e Variando o número de torções por par de fios.**

33. Qual organização padronizadora define os padrões para os cabos UTP?(4.4.2)

- **TIA/EIA conjuntamente.**

34. Qual organização padronizadora define os padrões eletricos para os cabos de cobre?(4.4.2)

- **IEEE.**

35. Qual é o padrão de cabeamento comercial para instalações de LAN?(4.4.2)

- **TIA/EIA-568.**

36. Qual a largura de banda para os cabos de categorias 5, 5e, 6, 7 e 8 respectivamente?(4.4.2)

- **100Mbps, 1000Mbps, 10Gbps, 100Gbps e 40Gbps.**

37. Para que serve o cabo rollover?(4.4.3)

- **É uma cabo proprietário da Cisco. É usado para conectar uma estação de trabalho a uma porta do console do roteador ou do switch.**

38. Quais são os principais tipos de cabo obtidos com o uso de convenções de cabeamento específicas para o cabo UTP/STP?(4.4.3)

- **Ethernet direta e Ethernet Crossover.**

39. Quais são os padrões de cabeamento dos cabos UTP/STP?(4.4.3)

- **T568A e T568B.**

40. Quais a ordem das cores do padrão T568A?(4.4.3)

- **brnaco/verde verde branco/laranja azul branco/azul laranja branco/barrom marrom**

41. Quais a ordem das cores do padrão T568B?(4.4.3)

- **brnaco/laranja laranja branco/verde azul branco/azul verde branco/barrom marrom**

42. Por que os cabos cruzados agora são considerados legados?(4.4.3) 

- **pois as NICs usam o cruzamento de interface dependente médio (Auto-MDIX) para detectar automaticamente o tipo de cabo e fazer a conexão interna.**

43. Como os cabos de fibra óptica são amplamente classificados?(4.5.2)

- **Fibra monomodo (SMF) e Fibra multimodo (MMF).**

44. Quais as caracteristicas da Fibra monomodo(SMF)?(4.5.2)

- **Consiste em um núcleo muito pequeno, usa a tecnologia laser cara para enviar um único raio de luz, adequado para longas distâncias.**

45. Quais as caracteristicas da Fibra multimodo(MMF)?(4.5.2)

- **Consiste em um núcleo maior, usa emissores de LED para enviar pulsos de luz, Popular nas LANs pelo baixo custo e tem largura de 10Gbs por links de até 550.**

46. Em qual tipo de fibra ótica a dispersão é maior?(4.5.2)

- **Fibra Multimodo(MMF).**

47. Quais são os setores em que a fibra ótica é utilizada?(4.5.3)

- **Redes corporativas, FTTH (Fiber-to-the-Home), Redes de longo curso e Redes de cabos submarinos.**

48. Quais são os tipos de conectores dos cabos de fibra optica?(4.5.4)

- **Ponta Reta(Straight-Tip-ST), SC(Quadrado), Lucent (LC) Simplex e Lucent LC duplex.** 

49. Qual o tipo de padrão de fibra óptica que usa ondas de comprimento diferentes para enviar e receber através de uma unica fibra?(4.5.4)

- **Padrões BX, como 100BASE-BX.**

50. Quais cores de fibras indicam cabos SMF e MMF respectivamente?(4.5.5)

- **Amarelo e laranja.**

51. Qual dos seguintes tipos de cabo de fibra óptica pode ajudar os dados a viajar aproximadamente 500m?(4.5.7)

- **Multimodo.**

52. Qual dos seguintes tipos de cabos de fibra óptica usa diodos emissores de luz (LEDs) como um transmissor de fonte de luz de dados?(4.5.7)

- **Multimodo.**

53. Qual dos seguintes tipos de cabos de fibra óptica usa lasers em um único fluxo como um transmissor de fonte de luz de dados?(4.5.7)

- **Monomodo.**

54. Qual dos seguintes tipos de cabo de fibra óptica é usado para conectar aplicativos de telefonia de longa distância e TV a cabo?(4.5.7)

- **Monomodo.**

55. Qual dos seguintes tipos de cabos de fibra óptica pode viajar aproximadamente 62,5 milhas ou 100 km/100000 m?(4.5.7)

- **Monomodo.**

56. Qual dos seguintes tipos de cabos de fibra óptica é usado em uma rede de campus?(4.5.7)

- **Multimodo.**

57. Qual é o padrão sem fio para redes WLAN?(4.6.2)

- **Wi-Fi (IEEE 802.11) **

58. Qual é o padrão sem fio para redes WPAN?(4.6.2)

- **Bluetooth (IEEE 802.15)**

59. Qual padrão oferece banda large sem fio?(4.6.2)

- **WiMAX (IEEE 802:16).**

60. Qual padrão é utilizado em Internet das Coisas (IoT)?(4.6.2)

- **Zigbee (IEEE 802.15.4).**

61. Quais são as caracteristicas do padrão Zigbee (IEEE 802.15.4)?(4.6.2)

- **baixa taxa de dados e baixa potência. Destina-se a aplicações que exigem taxas de dados de curto alcance, baixas e longa duração da bateria.**

62. Em geral, uma WLAN requer quais dispositivos de rede?(4.6.3)

- **Ponto de acesso sem fio (AP) e Adaptadores de NIC sem fio.**

63. Verdadeiro ou falso. Redes sem fio não é adequado para redes corporativas.(4.6.4)

- **Falso.**

64. Verdadeiro ou falso. As LANs sem fio operam em full-duplex, permitindo que todos os dispositivos enviem ou recebam dados ao mesmo tempo para que o número de usuários não tenha impacto no desempenho.(4.6.4)

- **Falso.**

65. Qual dos seguintes padrões sem fio é mais adequado para ambientes industriais e IoT?(4.6.4)

- **ZigBee.**

66. Qual dos seguintes padrões sem fio é usado para redes de área pessoal (PANs) e permite que os dispositivos se comuniquem em distâncias de 1 a 100 metros?(4.6.4)

- **Bluetooth.**

67. Um administrador de rede está a resolver problemas de conectividade num servidor. Usando um testador, o administrador observa que os sinais gerados pela NIC do servidor estão distorcidos e não utilizáveis. Em que camada do modelo OSI é o erro categorizado?(4.7.4)

- **Camada Física.**

68. Que tipo de cabo é utilizado para conectar a porta serial de uma estação de trabalho à porta de console de um roteador da Cisco?(4.7.4)

- **Rollover.**

69. Por que dois fios de fibra são usados para uma única conexão de fibra óptica?(4.7.4)

- **Eles permitem conectividade full-duplex.**

70. Qual procedimento é usado para reduzir o efeito do crosstalk em cabos de cobre?(4.7.4)

- **Torcendo pares de fios de circuitos opostos juntos.**

71. Qual é a vantagem de usar cabeamento de fibra óptica em vez de cabeamento de cobre?(4.7.4)

- **É capaz de transportar sinais muito mais longe do que o cabeamento de cobre.**

72. Um administrador de rede está projetando uma nova infraestrutura de rede que inclui conectividade com fio e sem fio.Em que situação seria recomendada uma conexão sem fio?(4.7.4)

- **O dispositivo do usuário final precisa de mobilidade ao se conectar à rede.**

73. Qual tipo de cabo UTP é usado para conectar um computador a uma porta de switch?(4.7.4)

- **Direto.**

74. Qual é a definição de largura de banda?(4.7.4)

- **O volume de dados que pode fluir de um lugar para outro durante um determinado temo.**

75. Qual afirmativa descreve corretamente a codificação de quadro?(4.7.4)

- **Convert bits em um código prédefinido a fim de fornecer um padrão prevísivel que ajude a diferenciar os bits de dados dos bits de controle.**

76. Qual é a característica do cabeamento UTP contra EMI e RFI?(4.7.4)

- **Cancelamento.**

77. Qual é a finalidade da camada física do modelo OSI?(4.7.4)

- **Transmitir bits no meio físico local.**

78. Quais as características do crosstalk(diafonia)?(4.7.4)

- **A distorção das mensagens enviadas por parte de sinais trnasmitidos em cabos adjacentes.**

79. O que o termo taxa de transferência indica?(4.7.4)

- **A medida de bits transferidos através do meio físico durante um determinado periodo.**

80. Qual organização de padrões supervisiona o desenvolvimento de padrões de LAN sem fio?(4.7.4)

- **IEEE.**


# 6 Camada de Enlace de Dados

1. Quais funções a camada de elance de dados desempenha?(6.1.1)

- **Permite que as camadas superiores acessem a mídia. O protocolo de camada superior não está completamente ciente do tipo de mídia que é usado para encaminhar os dados;**
- **Aceita dados, geralmente pacotes de Camada 3 (ou seja, IPv4 ou IPv6), e os encapsula em quadros da Camada 2;**
- **Controla como os dados são colocados e recebidos na mídia;**
- **Troca quadros entre pontos de extremidade através da mídia de rede;**
- **Recebe dados encapsulados, geralmente pacotes de Camada 3, e os direciona para o protocolo de camada superior apropriado; e**
- **Executa a detecção de erros e rejeita qualquer quadro corrompido.**

2. A camada de link de dados LAN/MAN IEEE 802 consiste de quais subcamadas?(6.1.2)

- **Logical Link Control (LLC) e Controle de Acesso a Mídia (MAC).**

3. Qual padrão é implementado pela Logical Link Control (LLC)?(6.1.2)

- **IEEE 802.2.**

4. Qual a função da subcamada LLC?(6.1.2)

- **Comunica entre o software de rede nas camadas superiores e o hardware do dispositivo nas camadas inferiores. Ela coloca a informação no quadro que identifica qual protocolo de camada de rede está sendo usado para o quadro. Essas informações permitem que vários protocolos da camada 3, como IPv4 e IPv6, usem a mesma interface de rede e mídia.**

5. Quais padrões são implementados pela Controle de Acesso a Mídia (MAC)?(6.1.2)

- **IEEE 802.3(LANs Ethernet), 802.11 ou 802.15 no hardware.**

6. Qual a função da subcamada MAC?(6.1.2)

- **É responsável pelo encapsulamento de dados e controle de acesso à mídia. Ele fornece endereçamento de camada de link de dados e é integrado com várias tecnologias de camada física.**

7. Para que serve o controle de acesso a mídia?(6.1.2)

- **Permitindo que vários dispositivos se comuniquem através de uma mídia compartilhada (half-duplex).**

8. Em cada salto ao longo do caminho, um roteador executa quais funções da Camada 2?(6.1.3)

- **Aceita um quadro de um meio;**
- **Desencapsula o quadro;**
- **Encapsula novamente o pacote em um novo quadro; e**
- **Encaminha o novo quadro apropriado para o meio desse segmento da rede física.**

9.Qual é outro nome para a camada de enlace de dados OSI?(6.1.5)

- **Camada 2.**

10. A camada de enlace de dados IEEE 802 LAN/MAN consiste em quais duas subcamadas?(6.1.5)

- **Controle de link lógico(LLC) e Controle de Acesso ao Meio(MAC).**

11. Qual é a responsabilidade da subcamada MAC?(6.1.5)

- **Fornece o método para obter o quadro ligado e fora da mídia.**

12. O método de controle de acesso à mídia usado depende de dois critérios?(6.1.5)

- **Topologia e Compartilhamento da mídia.**

13. Quais são os dois tipos de topologias usadas para descrever redes LAN e WAN?(6.2.1)

- **Topologia física e Topologia logica.**

14. Qual a caracteristica da topologia física?(6.2.1)

- ** Identifica as conexões físicas e como os dispositivos finais e intermediários (ou seja, roteadores, comutadores e pontos de acesso sem fio) são interconectados. A topologia também pode incluir a localização específica do dispositivo, como o número do quarto e a localização no rack do equipamento. As topologias físicas são geralmente ponto a ponto ou estrela.**

15. Qual a caracteristica da topologia logica?(6.2.1)

- **refere-se à maneira como uma rede transfere quadros de um nó para o próximo. Esta topologia identifica conexões virtuais usando interfaces de dispositivo e esquemas de endereçamento IP da Camada 3.**

16.  WANs são comumente interligadas usando três topologias, quais?(6.2.2)

- **Ponto a ponto, estrela e Malha.**

17. O que é uma topologia hibrida?(6.2.2)

- **É uma variação ou combinação de qualquer topologia.**

18. Em que caso o protocolo de comunicação serial PPP pode ser usado?(6.2.3)

- **Quando utilizado topologia ponto a ponto, em que não há compartilhamento do meio físico com outros hosts e um nó não precisa determinar se um quadro de entrada é destinado a ele ou a outro nó.**

19. Como funciona a comunicação half-duplex?(6.2.5)

- **Ambos os dispositivos podem transmitir e receber no meio físico, mas não podem fazer isso simultaneamente. **

20. Como funciona a comunicação full-duplex?(6.2.5)

- **Ambos os dispositivos podem transmitir e receber simultaneamente na mídia compartilhada.**

21. É verdadeiro que as duas NICs tem que operar no mesmo modo duplex para evitar erros?(6.2.5)

- **Verdeiro**.

22. O que é uma rede multiacesso?(6.2.6)

- **É uma rede que pode ter dois ou mais dispositivos finais tentando acessar a rede simultaneamente.**

23. Algumas redes multiacesso requerem regras para controlar como os dispositivos compartilham a mídia física. Existem dois métodos básicos de controle de acesso para meio físico compartilhado, quais?(6.2.6)

- **Acesso baseado em contenção e acesso controlado.**

24. Como opera os nós da rede em redes multiacesso baseadas em contenção?(6.2.6)

- **Todos os nós estão operando em half-duplex, competindo pelo uso do meio. No entanto, apenas um dispositivo pode enviar por vez.**

25. Quais são os métodos de acesso baseados em contenção?(6.2.6)

- **Acesso múltiplo com detecção de colisão (CSMA/CD) usado em LANs Ethernet de topologia de barramento herdada; e**
- **Acesso múltiplo por operadora com prevenção de colisão (CSMA / CA) usado em LANs sem fio.**

26. Como funciona uma rede baseada em acesso controlado?(6.2.6)

- **cada nó tem seu próprio tempo para usar o meio. Esses tipos determinísticos de redes herdadas são ineficientes porque um dispositivo deve aguardar sua vez para acessar o meio.** 

27. Quais são as redes multiacesso que usam acesso controlado?(6.2.6)

- **Anel de token legado ARCNET legado.**

28. Redes Ethernet perando em full-duplex exigem método de acesso?(6.2.6)

- **Não.**

29. Cite exemplos de redes baseadas em contenção?(6.2.7)

- **LAN sem fio (usa CSMA/CA);**
- **LAN Ethernet de topologia de barramento legado (usa CSMA/CD); e**
- **LAN Ethernet herdada usando um hub (usa CSMA/CD).**

30. Como funciona um hub ethernet?(6.2.7)

- **Quaisquer bits recebidos em uma porta de entrada são regenerados e enviados para todas as outras portas.**

31. Qual topologia exibe endereços IP da camada de dispositivo de rede?(6.2.9)

- **Topologica lógica.**

32. Que tipo de rede usaria ponto-a-ponto, hub e spoke ou topologias de malha?(6.2.9)

- **WAN.**

33. Qual método de comunicação duplex é usado em WLANs?(6.2.9)

- **Half duplex.**

34. Qual método de controle de acesso de mídia é usado em LANs Ethernet herdadas?(6.2.9)

- **Detecção de acesso multiplo/colisão com detecção de portadora.**

35. Quais são as partes básicas de um quandro da camada 2?(6.3.1)

- **Cabeçalho, Dados e Trailer.**

36. Qual valor é colocado no campo FCS (Sequência de Verificação de Quadro)?(6.3.2)

- **Cyclic redundancy check - CRC, um resumo lógico ou matemático dos bits que compõem o quadro no trailer.**

37. Qual a função do FCS?(6.3.2)

- **Fornece um método para o nó de recebimento determine se o quadro apresentou erros de transmissão.**

38. No que depente a escolha do protocolo da camada 2?(6.3.4)

- **Topologia lógica e do meio físico.**

39. Cite alguns protocolos da camada de enlace de dados?(6.3.4)

- **Ethernet, 802.11 sem fio, Protocolo ponto a ponto (PPP), Controle de Enlace de Dados de Alto Nível (HDLC) e Frame Relay.**

40. Qual é a função do último campo em um quadro de camada de link de dados?(6.3.5)

- **Para determinar se o quadro experimentou erros de trnasmissão.**

41. O que lista os campos de endereço da Camada 2 e da Camada 3 na ordem correta?(6.3.4)

- **Endereço NIC de destivo, Endereço NIC de origem, Endereço IP de orgiem e Endereço IP de destino.**

42. Qual identificador é usado na camada de link de dados para identificar exclusivamente um dispositivo Ethernet?(6.4.2)

- **Endereço MAC.**

43. Qual método é usado para gerenciar o acesso baseado em contenção em uma rede sem fio?(6.4.2)

- **CSMA/CA**

44. Foi solicitado a um técnico que desenvolvesse uma topologia física para uma rede que fornece um alto nível de redundância. Qual topologia física requer que cada nó esteja conectado a todos os outros nós na rede?(6.4.2)

- **Malha.**

45. Qual instrução descreve o modo half-duplex de transmissão de dados?(6.4.2)

- **Os dados que fluem em uma rede fluem em uma direção por vez.**

46. Qual método de controle de acesso de mídia de camada de link de dados é usado pela Ethernet?(6.4.2)

- **CSMA/CD**

47. Quais são as duas subcamadas da camada de enlace de dados do modelo OSI?(6.4.2)

- **MAC e LLC.**

48. Qual camada do modelo OSI é responsável por especificar o método de encapsulamento usado para tipos específicos de mídia?(6.4.2)

- **Enlace de dados.**

49. Que tipo de topologia física pode ser criada conectando todos os cabos Ethernet a um dispositivo central?(6.4.2)

- **Estrela.**

50. Embora CSMA/CD ainda seja um recurso da Ethernet, por que não é mais necessário?(6.4.2)

- **O uso de switches de camada 2 compatíveis com full-duplex.**



# 7 Switching Ethernet


1. A tecnologia Ethernet atua em quais camadas do modelo OSI?(7.1.1)

- **Enlace de dados(subcamada MAC) e Física.**

2. Qual a funcionalidade do CSMA/CD?(7.1.3)

- **Permite que vários dispositivos compartilhem o mesmo meio half-duplex, detectando uma colisão quando mais de um dispositivo tenta transmitir simultaneamente. Ele também fornece um algoritmo de recuo para retransmissão.**

3. Qual o tamamnho mínimo e máximo de um quadro ethernet?(7.1.4)

- **Mínimo de 64 bytes e o máximo é 1518 bytes.**

4. Verdadeiro ou falso. O campo preâmbulo é incluído ao descrever o tamanho do quadro.(7.1.4)

- **Falso.**

5. Como são chamados quadros mairoes que 1518 bytes?(7.1.4)

- **“jumbo” ou “baby giant”.**

6. Quais são os campos do quadro ethernet e seus respectivos tamanhos?(7.1.4)

![](figuras/quadro-ethernet.jpg)

7. Qual o tamanho do preambulo e do SFD?(7.1.4)

- **O Preâmbulo tem 7 bytes e o Delimitador de Quadro Inicial SFD tem 1 byte.**

8. Qual é a utilidade do preambulo e do SFD?(7.1.4)

- **são usados para sincronização entre o dispositivos de envio e recepção.Essencialmente, o primeiro poucos bytes informam aos receptores para se prepararem para receber um novo quadro.**

9. Qual a utilidade do campo Tipo/Comprimento/EtherType?(7.1.4)

- **Identifica o protocolo da camada superior encapsulado em o quadro Ethernet.**

10. Quais são os valores hexadecimais para os protocolos IPv4, IPv6 e ARP no campo EtherType?(7.1.4)

- **0x800 para IPv4, 0x86DD para IPv6 e 0x806 para ARP.**

11. Qual o tamanho mínimo e máximo do campo dados de um quadro ethernet?(7.1.4)

- **46 - 1500 bytes**

12. Se um pequeno pacote for encapsulado em um quadro ethernet, fazendo com que o tamanho do quadro não alcance 64 bytes, o tamanho mínimo de um quadro, o que é realizado?(7.1.4)

- **bits adicionais chamados pad são usados para aumentar o tamanho do quadro para este tamanho mínimo.**

13. Qual parte de um quadro Ethernet usa um pad para aumentar o campo de quadro para pelo menos 64 bytes?(7.1.5)

- **Campo de dados.**

14. Qual parte de um quadro Ethernet detecta erros no quadro?(7.1.5)

- **Sequência de verificação de quadro (FCS).**

15. Qual parte de um quadro Ethernet descreve o protocolo de camada superior encapsulado?(7.1.5)

- **EtherType.**

16. Qual parte de um quadro Ethernet notifica o receptor para se preparar para um novo quadro?(7.1.5)

- **Preâmbulo.**

17. Qual subcamada de link de dados controla a interface de rede através de drivers de software?(7.1.5)

- **LLC**

18. Qual subcamada de link de dados trabalha com as camadas superiores para adicionar informações de aplicativos para entrega de dados a protocolos de nível superior?(7.1.5)

- **LLC**

19. Qual o tamanho de um endereço MAC em bits e em bytes?(7.2.2)

- **48 bits e 6 bytes.**

20. Em quais partes um endereço MAC é dívidido?(7.2.2)

- **Em duas partes de 3 bytes siguinificando: OUI (Organizationally Unique Indentifier) e Fonecedor atribuído.**

21. Onde o endereço MAC fica armazenado?(7.2.3)

- **Em hardware, na memória ROM da NIC.**

22.  Qua é o processo que um host de origem usa para determinar o endereço MAC de destino associado a um endereço IPv4?(7.2.4)

- **ARP (Address Resolution Protocol)**

23. Qual é o processo que um host de origem usa para determinar o endereço MAC de destino associado a um endereço IPv6?(7.2.4)

- **ND (Neighbour Discovery Discovery).**

24. O que um switch faz ao receber um quadro com endereço MAC de destino iguaal a FF-FF-FF-FF-FF-FF?(7.2.5)

- **É inundada todas as portas de switch Ethernet, exceto a porta de entrada.**

25. Quais são os préfixo de multicast MAC para IPv4 e IPv6 respectivamente?(7.2.6)

- **01-00-5E e 33-33**

26. Qual é o intervalo de endereço multicast do IPv4?(7.2.6)

- **224.0.0.0 a 239.255.255.255**

27. O intervalo de endereços multicast IPv6 começa com que valor?(7.2.6)

- **ff00::/8**

28. Como um switch cria a tabela de endereços MAC?(7.3.2)

- **Dinamicamente examinando o endereço MAC de origem dos quadros recebidos em uma porta.**

29. U que é o "unicast desconhecido"?(7.3.2)

- **Se o endereço MAC de destino não estiver na tabela, o switch encaminhará o quadro por todas as portas, exceto a de entrada.**

30. Quanto tempo por padrão a maioria de switches ethernet mantém uma entrada na tabela de endereços MAC?(7.3.2)

- **5 minutos.**

31. Como um switch filtra um quadro?(7.3.3)

- **Quando a tabela de endereços MAC contém o a entrada para o endereço destino, o quadro é enviado apenas para a porta específica.**

32. Quais são os métodos de emcaminhamento de quadro?(7.4.1)

- **Switching store-and-forward e Switching cut-through.**

33. Como o método Switching store-and-forward funciona?(7.4.1)

- **Recebe o quadro inteiro e calcula o CRC. Se o CRC é válido, o switch procura o endereço de destino, que determina a interface de saída.**

34. Como o método Switching cut-through funciona?(7.4.1)

- **Esse método de encaminhamento de quadros encaminha o quadro antes de ser totalmente recebido. Somente o endereço de destino é lido.**

35. Qual a vantegem do método Switching store-and-forward?(7.4.1)

- **O descarte de quadros com erros reduz o consumo de largura de banda por dados corrompidos e é necessário para a análise de qualidade de serviço (QoS).**

36. Quais são os dois modos de Switching cut-through?(7.4.2)

- **Switching Fast-forward e Switching Fragment-free.**

37. Como o método Switching Fast-forward funciona?(7.4.2)

- **Encaminha imediatamente um pacote depois de ler o endereço de destino, sem verificação de erros.**

38. Como o método Switching Fragment-free funciona?(7.4.2)

- **armazena os primeiros 64 bytes do quadro antes de encaminhar e executa uma pequena verificação de erros.**

39. Quais são os Memory Buffering Methods?(7.4.3)

- **Memória por porta e Memória compartilhada.**

40. Como funciona o método buffer de Memoria por porta?(7.4.3)

- **Os quadros são armazenados em filas vinculadas a entradas e portas de saída.**
- **Um quadro é transmitido para a porta de saída somente quando todos os quadros à frente na fila foram transmitidos com sucesso.**
- **É possível para um único quadro atrasar a transmissão de todos os os quadros na memória devido a uma porta de destino ocupada.**
- **Esse atraso ocorre mesmo que os outros quadros possam ser transmitidos para portas de destino abertas.**

41. Como funciona o método buffer de Memoria compartilhada?(7.4.3)

- **Deposita todos os quadros em um buffer de memória comum compartilhado por todos os switches e a quantidade de memória de buffer necessária por uma porta é alocados dinamicamente.**
- **Os quadros no buffer são vinculados dinamicamente ao destino permitindo que um pacote seja recebido em uma porta e, em seguida, transmitida em outra porta, sem movê-la para uma fila diferente.**

42. Verdadeiro ou falso. Portas Gigabit Ethernet só operam em full-duplex?(7.4.4)

- **Verdadeiro**

43. Como o recurso auto-MDIX pode ser ativado?(7.4.5)

- **usando o comando de configuração de mdix auto interface.**

44. Quais são os dois métodos para alternar dados entre portas em um switch?(7.4.6)

- **Switching cut-trhough e Switching store and forward.**

45. Qual método de comutação pode ser implementado usando comutação rápida ou comutação sem fragmentos?(7.4.6)

- **Switching cut-trhough.**

46. Quais dois tipos de técnicas de buffer de memória são usadas por switches?(7.4.6)

- **Buffer de memória baseado em porta e buffer de memória compartilhado.**

47. Qual recurso negocia automaticamente a melhor velocidade e configuração duplex entre dispositivos de interconexão?(7.4.6)

- **Negociação automática.**

48. O que um host em uma rede Ethernet fará se receber um quadro com um endereço MAC de destino que não corresponda ao seu próprio endereço MAC?(7.5.2)

- **Ele descartará.**

49. Qual dispositivo de rede toma decisões de encaminhamento com base no endereço MAC destino contido no quadro?(7.5.2)

- **Switch**

50. Qual função ou operação é executada pela subcamada LLC?(7.5.2)

- **Ele se comunica com camadas de protocolos superiores.**

51. O que acontece com os quadros runt recebidos pelo switch Ethernet Cisco?(7.5.2)

- **Ele é descartado.**

52. Que informações de endereçamento são registradas por um switch para construir sua tabela de endereços MAC?(7.5.2)

- **O endereço MAC de origem da camada 2 dos quadros recebidos.**

53. O que é auto-MDIX?(7.5.2)

- **Um recurso que detecta o tipo de cabo Ehternet.**

54. Que tipo de endereço é 01-00-5E-0A-00-02?(7.5.2)

- **Um endereço multicast.**

55. Quais são os dois tamanhos (mínimo e máximo) de um quadro Ethernet?(7.5.2)

- **64 e 1518 bytes**















































