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


![](suporte-da-internet.jpg)	

22. Qual a hierarquia de organizações de padrões envolvidos com o desenvolvimento e suporte do TCP/IP?(3.4.2)

![](suporte-da-tcp-ip.jpg)

23. Que tipos de padrões são desenvolvidos pela Setor de Normalização das Telecomunicações da União Internacional de Telecomunicações (ITU-T)?(3.4.3)

- **Compactação de vídeo;**
- **Televisão por IP (IPTV); e**
- **Comunicações de banda larga, como DSL.**

24. Qual a correspondencia entre as camadas dos modelos OSI e TCP/IP?(3.5.4)

![](modelo-ois-tcp-ip-correspondencia.jpg)

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

![](nome-dos-pdus.jpg)

30. Qual é o processo de dividir um grande fluxo de dados em partes menores antes da transmissão?(3.6.6)

- **Segmentação.**

31. Qual é a PDU associada à camada de transporte?(3.6.6)

- **Segmento.**

32. Qual camada de pilha de protocolo encapsula dados em quadros?(3.6.6)

- **Enlace de dados.**

33. Qual é o nome do processo de adição de informações de protocolo aos dados à medida que ele move para baixo a pilha de protocolos?(3.6.6)

- **Encapsulamento.**

34. Um endereço IP contém quais partes?(3.7.2)

- **Parte da rede (IPv4) ou Prefixo (IPv6)**
- **Parte do host (IPv4) ou ID da interface (IPv6)**

35. 



