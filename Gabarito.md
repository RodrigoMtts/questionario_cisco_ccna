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

3. Qual a função do kernel?

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

9. Qual a diferença entre os modos de comandos Modo EXEC de usuário e Modo EXEC privilegiado(2.1.1)?

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
- **password cisco**
- **login**

