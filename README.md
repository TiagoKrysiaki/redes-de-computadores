# REDES DE COMPUTADORES
## MÓDULO 1: COMUNICAÇÃO EM UM MUNDO CONECTADO

### TIPOS DE REDE
  A internet não é de propriedade de nenhum individuo ou grupo. a internet é um conjunto mundial de redes interconectadas (inter-rede ou internet), que cooperam entre si para trocar informações usando padrões comuns. Através de fios de telefone, cabos de fibra óptica, transmissões sem fio e links de satélite, os usuários da internet podem trocar informações de várias formas.

As redes domésticas pequenas conectam alguns computadores entre si e com a internet. A rede `SOHO` permite que computadores em um escritório em casa ou um escritório remoto se  conectem a uma rede corporativa, ou acessem recursos compartilhados centralizados. Redes de médio a grande porte, como as usadas por empresas e escolas, podem ter muitos locais com centenas ou milhares de hosts interconetados. A internet é uma rede de rede que conecta centenas de milhões de computadores em todo o mundo.

Existem dispotivos ao redor com os quais você pode interagir diariamente que também estão conectados a internet. Isso inclui dispositivos móveis, como smarphones, tablets e smartwatches. Coisas em sua casa podem ser conectadas á internet, como um sistema de segurança, aparelhos, sua TV inteligente e seu console de jogos. Fora de casa, há carros inteligentes, equetas RFID, sensores e atuadores e até dispositivos médicos que podem ser conectados.

### TRANSMISSÃO DE DADOS
As seguintes categorias são usadas para classificar tipos de dados pessoais:
  - **Dados voluntários** - São criados e compartilhados explicitamente por indivíduos, como perfis de redes sociais. Esses tipo de dados podem incluir arquivos de vídeo, texto, imagem ou áudio.
  - **Dados observados** - São capturados quando indivíduos registram suas atividades, como dados de localização de celulares.
  - **Dados inferidos** - São baseados na análise de dados voluntários ou observados, como uma pontuação de crédito.

  O termo bits é uma abreviação de `"Digito binário"` e representa a menor parte de dados. Cada bit pode ter apenas dois valores possiveis: 0 ou 1

Existem três métodos comuns de transmissão de sinal usados em redes:
  - **Sinais alétricos** - A transmissão é obtida pela representação dos dados como pulsos elétricos em fios de cobre.
  - **Sinais ópticos** - A transmissão é obtida pela conversão dos sinais elétricos em pulsos de luz.
  - **Sinais sem fio** - A transmissão é obtida pelo uso de infravermelho, micro-ondas ou ondas de rádio pelo ar.

### LARGURA DE BANDA E TAXA DE TRANSFERÊNCIA
Largura de banda é a capacidade de um meio de transportar dados. A largura de banda digital mede a quantidade de dados que podem fluir de um lugar para o outro durante um determinado tempo. A largura de banda costuma ser medida pelo número de bits que (teoricamente) podem ser enviados através da midia em um segundo. Estas são as medidas comuns de largura de banda:
- Milhares de bits por segundo (Kbps)
- Milhões de bits por segundo (Mbps)
- Bilhões de bits por segundo (Gbps)

A taxa de transferência geralmente não corresponde á largura da banda especificada, diversos fatores influenciam:
- A quantidade de dados enviados e recebidos pela conexão
- a latência criada pelo número de dispositivos de rede encontrados entre a origem e o destino

O termo latência se refere ao tempo necessário para os dados viajarem de um ponto a outro, incluindo atrasos.

---

## MÓDULO 2: COMPONENTES, TIPOS E CONEXÕES DE REDE

### CLIENTES E SERVIDORES
Todos os computadores conectados a uma rede que participam diretamente na comunicação de rede são classificados como hosts. Os hosts podem enviar e receber mensagens na rede. Nas redes modernas, um host pode atuar como cliente, servidor ou ambos. O software instalado no computador determina qual função o computador desempenha.

Os softwares de cliente e de servidor gerelmente são executados em computadores separados, mas também é possivel que um computador execute as duas funções ao mesmo tempo. Em pequenas empresas e em casas, muitos computadores funcionam como servidores e clientes na rede. Esse tipo de rede é chamado de rede ponto a ponto (P2P). Em empresas de grande porte, devido ao pontecial para quatidades altas de tráfego de rede. geralmente é necessário ter servidores dedicados para suportar o número de solicitações de serviço. As redes P2P são fáceis de configurar, menos complexas, de custo mais baixo e podem ser usadas para tarefas simples, como transfência de arquivos e compartilhamento de impressoras. No entanto, não exite administração centralizada. Elas têm menos segurança, não são escaláveis e podem ter um desempenho mais lento.

### COMPONETES DE REDE
Existem símbolos que representam vários tipos de equipamento de rede. A infraestrutura de rede é a plataforma que suporta a rede. Ela fornece o canal estável e confiável sobre o qual nossas comunicações podem ocorrer. A infraestrutura de rede contém três categorias de componentes de hardware: **dispositivos intermediários, dispositivos final e maios físicos de rede**. O hardware é geralemente composto pelos componentes visíveis da plataforma de rede, tais como um laptop, um PC, um switch, um roteador, um access point sem fio ou os cabos usados para conectar os dispositivos. Os componentes que não estão visíveis incluem mídia sem fio.

Os dispositvos finais, ou hosts, formam a interface entre os usuários e a rede de comunicação subjacente. Alguns exemplos de dispositivos finais são:
- Computadores (estação de trabalho, laptops, servidores de arquivos, servidores Web);
- Impressoras de rede
- Telefones e equipamentos de teleconferência
- Câmeras de segurança
- Dipositivos móveis (como smartphones, tablets, PDAs, leitores de cartão de débito/crédito sem fio e scanners de código de barras)

### OPÇÕES DE CONECTIVIDADE COM O ISP
Um ISP fornece um link entre a rede doméstica e a Internet. Um ISP pode ser o provedor de TV a cabo local, um provedor de serviços de telefonia fixa, a rede celular que forneçe seu serviço de smartphone ou um provedor independente que aluga largura de banda da infraestrutura de rede física de outra empresa. Cada ISP conecta-se a outros ISPs para formar uma rede de links que interconectam usuários em todo o mundo. Os ISPs são conectado de maneira hierárquica que garante que o tráfego da internet geralmente siga o caminho mais curto da origem ao destino.

A interconexão de ISPs, que forma a espinha dorsal da internet, é uma teia complexa de cabos de fibra ótica com switches e roteadores de rede caros que direcionam o fluxo de informações entre os hosts de origem e destino.

Para ele, conectar-se ao ISP é um processo bastante simples. Esta é a opção de conexão mais comum. Consiste em usar um roteador integrado sem fio para se conectar ao ISP. O roteador inclui um switch para conectar hosts com fio e um AP sem fio para conectar hosts sem fio. O roteador também fornece informações de endereçamento IP do cliente e segurança para hosts internos. Os dois métodos mais comuns são cabo e DSL. Outras opções incluem, satélite e conexão discada usando um linha telefônica.

----

## MÓDULO 3: REDES SEM FIO E MÓVEIS
### REDES WIRELESS
Os celulares usam ondas de rádio para transmitir sinais de voz a antenas montadas em torres localizadas em regiões especificas. Quando é feita uma ligação telefônica, o sinal de voz é retransmitido de uma torre a outra até chegar ao destino. Esse tipo de rede é usado quando você faz uma chamada para outro telefone celular ou para um telefone fixo. Também serve para enviar mensagens diretamente do telefone. O tipo mais comum de rede de telefonia celular é uma rede GSM. As abreviações 3G, 4G, 4G-LTE e 5G são usadas para descrever as redes de celular avançadas que foram otimizadas para transmissão rápida de dados. Atualmente, o 4G ainda domina como a rede móvel atual usada pela maioria dos telefones.

Além dos transmissores e receptores GSM e 4G/5G, os smartphones fazem conexões de várias maneiras.

**WI-FI** - Transmissores e receptores WI-FI localizados no smartphone permitem que o telefone se conecte a redes locais e à Internet. As redes WI-FI normalmente pertencem a proprietários particulares, mas costumam oferecer hostspots de acesso público ou para convidado. Um hospot é uma área onde os sinais de WI-FI estão disponiveis.

**Bluetooth** é uma tecnologia sem fio que permite que os dispositivos se cominiquem em distâncias pequenas. É possivel conectar vários dispositivos ao mesmo tempo com Bluetooth.

É um tecnologia de comunicação sem fio que permite a troca de dados entre dispositivos que estejam bem próximos uns dos outros, normalmente apenas alguns centimetros.

### CONECTIVIDADE DE DISPOSITIVO MÓVEL
Quase todos os dispositivos móveis podem se conectar a redes WI-FI. É preciso tomar essas precauções para proteger as comunicações WI-FI em dispositivos móveis:
- Nunca envie informações de login ou senha usando um texto não criptografado (texto simples).
- Use uma conexão VPN quando possível se você estiver enviado dados confidenciais.
- Ative a segurança em redes domésticas.
- Use criptografia WPA2 ou superior para segurança.

Apple iOS e Android são os dois dos sistemas operacionais mais conhecidos para dispositivos móveis. Os dispositivos móveis são pré-programados para usar uma rede WI-FI para Internet (se houver uma disponível) e o dispositivo pode se conectar ao access point e receber um endereço IP. Se não existir uma rede WI-FI disponível, o dispositivo usará o recurso de dado móveis configurado.

A tecnologia Bluetooth proporciona um modo simples para os dispositivos móveis se conectarem uns aos outros e a acessórios sem fio. O Bluetooth é sem fio, automático e usa muito pouca energia, o que ajuda a economizar a bateria. Alguns exemplos de dispositivos que usam Bluetooth incluem fones de ouvido, teclado, mouse, controle de som, alto-falantes para carros e alto-falantes móveis.

O pareamento Bluetooth ocorre quando dois dispositivos Bluetooth estabelecem uma conexão para compartilhar recursos. Para que os dispositivos se emparelhem. os rádios Bluetooth são ativado e um dispositivo começa a procurar outros dispositivos. Outros dispositivos devem estar configurados no modo detectável, também chamado visivel, para que possam ser detectados.

Quando um dispositivo Bluetooth está no modo detectável, ele transmite as seguintes informações quando outro dispositivo Bluetooth as solicita:
- Nome
- Classe de Bluetooth
- Serviços que o dispositivo pode usar
- Informações técnicas, como funcionalidade ou a especificação de bluetooth compatível

Durante o processo de emparelhamento, um PIN pode ser solicitado para aumentar o processo de emparelhamento.

---

## MÓDULO 4: CONSTRUINDO UMA REDE DOMÉSTICA
### CONCEITOS BÁSICOS DA REDE DOMÉSTICA

A maioria das redes domésticas consiste em pelo menos duas redes separadas. A rede pública vem do provedor de serviços. O roteador está conectado à internet. Provavelmente, o roteador doméstico tem recursos com e sem fio. Uma rede doméstica é uma pequena LAN com dispositivos que normalmente se conectam uns aos outros e a um roteador integrado para trocar informações.

A tecnologia sem fio é razoavelmente econîmica e fácil de instalar. Vantagens da tecnologia de LAN sem fio incluem mobilidade, escalabilidade, flexibilidade, economia de custos, tempo de instalação reduzido e onfiabilidade em ambientes hostis.

Além de um roteador integrado, há muitos tipos diferentes de dispositivos que podem estar se conectando a uma rede doméstica. Por exemplo, computadores desktop, sistemas de jogos, sistemas de smart TV, impressoras, scanners, câmeras de segurança e dispositos de cotrole de clima.

Roteadores residenciais e de pequenas empresas normalmente têm dois tipos principais de portas: portas **Ethernet** e uma porta de **Internet**. Além das portas com fio, muitos roteadores residenciais incluem antena sem fio e um ponto de acesso interno sem fio.

### TECNOLOGIAS DE REDE NA RESIDÊNCIA

As tecnologias sem fio usam ondas eletromagnéticas para transportar informações entre dispositivos. O espectro eletromagnético inclui banda de transmissão de rádio e televisão, luz visível, raios x e raios gama. Alguns tipos de ondas eletromagnéticas não são apropriados para transmitir dados. Outras partes do espectro são reguladas pelos governos e lecenciadas a várias empresa para aplicações especificas.

Essas faixas não licenciadas do espectro são incorporadas a produtos de consumo, como os roteadores WI-FI encontrados na maioria das casas. A tecnologias sem fio mais usadas em redes residenciais estão nas faixas de frequências não licenciadas de 2,4 GHz e 5GHz. Bluetooth é uma tecnologia que utiliza a banda de 2,4 GHz. Outras tecnologias que usam as bandas 2,4 GHz e 5 GHz são as modernas tecnologias de LAN sem fio que estão em conformidade com vários padrões IEEE 802.11. A diferença em relação à tecnologia de Bluetooth é que elas transmitem em um nível de potência muito maior, o que lhes dá maior alcance e melhor rendimento.

Embora muito dispositivos de rede doméstica suportem comunicações sem fio, ainda existem algumas aplicações em que os dispositivos se beneficiam de uma conexão de switch com fio. o protocolo com fio implementado com mais frequência é o protocolo **Ethernet**. Dispositivos conectados diretamente usam um cabo de ligação Ethernet, normalmente par trançado não blindado. A categoria 5e é o cabeamento mais comum usado em uma LAN. O cabo é composto de 4 pares de fios que são trançados para reduzir a interferência elétrica. Para residências que não têm cabeamento UTP, há outras tecnologias, como o usa da rede elétrica, que podem distrinuir conectividade com fio nos ambientes.

### PADRÕES DE REDES SEM FIO

O padrão IEEE 802.11 controla o ambiente WLAN. Os padrões sem fio de LANs usam as bandas de frequência de 2,4 GHz e 5 GHz. Coletivamente, essas tecnologias são conhecidas como Wi-Fi. O Wi-Fi Alliance, é responsável por testar dispositivos de LAN sem fio de diferentes fabricantes.

Os roteadores sem fio que usam os padrões 802.11 têm várias configurações que devem ser ajustadas. Estas configurações incluem:

- **Modo de Rede** – Determina o tipo de tecnologia que deve ser suportada. Por exemplo, 802.11b, 802.11g, 802.11n ou Mixed Mode (Modo misto).
- **Nome da rede (SSID)** – Usado para identificar a WLAN. Todos os dispositivos que desejam participar na WLAN devem ter o mesmo SSID.
- **Canal Padrão** – Especifica o canal no qual a comunicação ocorrerá. Por padrão, é configurado para Automático para permitir que o ponto de acesso (AP) determine o melhor canal a usar.
- **Broadcast SSID** – Determina se o SSID será transmitido para todos os dispositivos dentro do intervalo. Por padrão, é configurado para Ativado.

O protocolo 802.11 pode fornecer melhor taxa de transferência, dependendo do ambiente de rede sem fio. Se todos os dispositivos sem fio se conectarem com o mesmo padrão 802.11, poderão ser obtidas as velocidades máximas desse padrão. Se o ponto de acesso estiver configurado para aceitar apenas um padrão 802.11, os dispositivos que não usarem esse padrão não poderão se conectar ao access point. Um ambiente de rede sem fio com modo misto pode incluir dispositivos que utilizem qualquer padrão Wi-Fi atual.

Ao criar uma rede sem fio, é importante que os componentes sem fio se conectem à WLAN apropriada. Isso é feito por meio do SSID. O SSID é usado para informar aos dispositivos sem fio, chamados STAs, à qual WLAN eles pertencem e com quais outros dispositivos eles podem se comunicar. O broadcast SSID permite que outros dispositivos e clientes sem fio detectem automaticamente o nome da rede sem fio. Se o broadcast SSID estiver desativado, insira manualmente o SSID nos dispositivos sem fio.

### CONFIGURAR UM ROTEADOR DOMÉSTICO

Muitos roteadores sem fio para residências têm um utilitário de configuração automática que pode ser usado para ajustar as configurações básicas no roteador. Para se conectar ao roteador usando uma conexão com fio, conecte um cabo de ligação Ethernet à porta de rede no computador Conecte a outra extremidade a uma porta LAN no roteador.

Após a confirmação de que o computador está conectado ao roteador de rede e que as luzes dos links na NIC (placa de interface de rede) indicam uma conexão ativa, o computador precisa de um endereço IP. A maioria dos roteadores de rede estão configurados para que o computador receba um endereço IP automaticamente de um servidor DHCP local.

Antes de entrar no utilitário de configuração ou configurar manualmente o roteador através de um navegador da Web, você deve considerar como a rede será usada. Considere o que você chamará de rede e quais dispositivos devem se conectar à rede. Não é uma boa prática incluir o modelo do dispositivo ou o nome da marca como parte do SSID, pois as pesquisas na Internet podem expor falhas de segurança.

O modo de uso da rede determina quem pode acessar a rede doméstica. Muitos roteadores são compatíveis com a filtragem de endereços MAC. Isso permite identificar especificamente quem tem permissão na rede sem fio. Isso torna a rede sem fio mais segura, mas também reduz a flexibilidade ao conectar dispositivos novos. Em alguns roteadores sem fio, é possível configurar o acesso para convidado. Essa é uma área de cobertura do SSID que permite o acesso aberto, restringindo-o apenas ao uso da Internet.

---

## MÓDULO 5: PRINCÍPIOS DE COMUNICAÇÃO
### Protocolo de comunicação

Os protocolos são necessários para que os computadores se comuniquem corretamente na rede. Isso inclui formato de mensagem, tamanho de mensagem, temporização, codificação, encapsulamento e padrões de mensagem.

- **Formato da mensagem** – Quando uma mensagem é enviada, ela deve usar um formato ou estrutura específica.
- **Tamanho da mensagem** – As regras que regem o tamanho das peças comunicadas pela rede são muito rígidas. Eles também podem ser diferentes, dependendo do canal usado.
- **Temporização** – A temporização determina a velocidade na qual os bits são transmitidos pela rede. Também afeta quando um host individual pode enviar dados e a quantidade total de dados que pode ser enviada em qualquer transmissão.
* **Codificação** – As mensagens enviadas pela rede são primeiro convertidas em bits pelo host de envio. Cada bit é codificado em um padrão de sons, de ondas de luz ou de impulsos elétricos, dependendo da mídia de rede em que os bits são transmitidos.
- **Encapsulamento** – Cada mensagem transmitida em uma rede deve incluir um cabeçalho que contenha informações de endereçamento que identifiquem os hosts de origem e destino. Encapsulamento é o processo de adicionar essas informações aos dados que compõem a mensagem.
- **Padrão de mensagem** – **Algumas mensagens requerem uma confirmação antes** que a próxima mensagem possa ser enviada. Esse tipo de padrão de solicitação/resposta é um aspecto comum em muitos protocolos de rede. No entanto, existem outros tipos de mensagens que podem ser simplesmente transmitidas pela rede, sem a preocupação de chegarem ao seu destino.

---

### Padrões de comunicação

As topologias nos permitem ver a rede usando a representação de dispositivos finais e dispositivos intermediários. Como um dispositivo vê uma rede? Pense em um dispositivo em uma bolha. Um dispositivo só vê suas próprias informações de endereçamento. Como o dispositivo sabe que está na mesma rede que outro dispositivo? A resposta é: protocolos de rede. A maioria das comunicações de rede é dividida em unidades de dados menores ou pacotes.

Um padrão é um conjunto de regras que determina como algo deve ser feito. Os padrões de rede e de Internet asseguram que todos os dispositivos conectados à rede implementem o mesmo conjunto de regras ou protocolos da mesma forma. O uso de padrões permite que diferentes tipos de dispositivos enviem informações entre si pela Internet.

Um padrão da Internet é o resultado final de um ciclo completo de discussão, solução de problemas e testes. Esses diferentes padrões são desenvolvidos, publicados e mantidos por uma variedade de organizações. Quando um novo padrão é proposto, cada etapa do processo de desenvolvimento e aprovação é registrada em um documento numerado de Solicitação de comentários (RFC), para que a evolução do padrão seja monitorada. As RFCs de padrões da Internet são publicadas e gerenciadas pelo IETF (Internet Engineering Task Force).

---

### Modelos de comunicação de rede

Os protocolos são as regras que regem as comunicações. Uma comunicação bem-sucedida entre hosts requer interação entre vários protocolos. Os protocolos incluem HTTP, TCP, IP e Ethernet. Esses protocolos são implementados em software e hardware instalados em cada host e dispositivo de rede.

A interação entre os diferentes protocolos em um dispositivo pode ser ilustrada como uma pilha de protocolos. Uma pilha ilustra os protocolos como uma hierarquia em camadas, com cada protocolo de alto nível dependendo dos serviços dos protocolos mostrados nos níveis inferiores. A separação das funções permite que cada camada na pilha opere de forma independente das outras.

A suíte de protocolos TCP/IP que é usada para comunicações na Internet segue a estrutura deste modelo:

- **Aplicativo** - Representa dados para o usuário, além de codificação e controle de diálogo
- **Transporte** - Suporta a comunicação entre vários dispositivos em diversas redes
- **Internet** - Determina o melhor caminho através da rede
- **Acesso à rede** - Os dispositivos de hardware e mídia que compõem a rede.

Um modelo de referência descreve as funções que devem estar em uma camada específica, mas não especifica exatamente como uma função deve ser realizada. A principal finalidade de um modelo de referência é ajudar a entender melhor as funções e os processos necessários para as comunicações de rede.

O modelo de referência de internetwork mais conhecido foi criado pelo projeto OSI na ISO Internacional. Ele é usado para projeto de redes de dados, especificações de operação e solução de problemas. Esse modelo costuma ser chamado de modelo OSI.

---

### Descrição das camadas do modelo OSI:

- **7 – Aplicação** – A camada de aplicação contém protocolos usados para comunicações entre processos.
- **6 – Apresentação** – A camada de apresentação fornece uma representação comum dos dados transferidos entre os serviços da camada de aplicação.
- **5 – Sessão** – A camada de sessão fornece serviços à camada de apresentação para organizar seu diálogo e gerenciar a troca de dados.
- **4 – Transporte** – A camada de transporte define serviços para segmentar, transferir e remontar os dados para comunicações individuais entre os dispositivos finais.
- **3 – Rede** – A camada de rede fornece serviços para troca de dados individuais pela rede entre dispositivos finais identificados.
- **2 – Enlace de dados** – Os protocolos da camada de enlace de dados descrevem métodos para troca de quadros de dados entre dispositivos em uma mídia comum.
- **1 – Física** – Os protocolos da camada física descrevem os meios mecânicos, elétricos, funcionais e procedimentais para ativar, manter e desativar conexões físicas para uma transmissão de bits de e para um dispositivo de rede.

---

## MÓDULO 6: MÍDIA DE REDE
### TIPOS DE MÍDIA DE REDE

A comunicação é transmitida através de uma rede na mídia. A mídia fornece o canal pelo qual a mensagem viaja da origem ao destino.

As redes modernas usam principalmente três tipos de mídia para interconectar dispositivos:

- **Fios de metal dentro de cabos** – Os dados são codificados em impulsos elétricos.
- **Fibras de vidro ou plástico nos cabos (cabo de fibra óptica)** – Os dados são codificados em pulsos de luz.
- **Transmissão sem fio** – Os dados são codificados através da modulação de frequências específicas de ondas eletromagnéticas.

Os quatro critérios principais para a escolha da mídia de rede são estes:

- Qual é a distância máxima pela qual o meio físico consegue carregar um sinal com êxito?
- Qual é o ambiente em que a mídia será instalada?
- Qual é a quantidade de dados e a que velocidade deve ser transmitida?
- Qual é o custo da instalação da mídia?

Os três cabos de rede mais comuns são par trançado, cabo coaxial e cabo de fibra óptica. A tecnologia Ethernet geralmente usa cabos de par trançado para interconectar dispositivos. O cabo coaxial é um tipo de cabo de cobre usado por empresas de TV a cabo. Também serve para conectar os diversos componentes que constituem os sistemas de comunicação via satélite. O cabo de fibra óptica pode ser de vidro ou plástico com diâmetro aproximadamente igual ao de um cabelo humano e pode transportar informações digitais em velocidades muito altas por longas distâncias. Como a luz é usada em vez de eletricidade, a interferência elétrica não afeta o sinal.

---

## MÓDULO 7: A CAMADA DE ACESSO
### ENCAPSULAMENTO E O QUADRO ETHERNET

O processo de colocar um formato de mensagem dentro de outro formato de mensagem é chamado de encapsulamento. O desencapsulamento ocorre quando o processo é invertido pelo destinatário e a carta é retirada do envelope. Assim como uma carta é colocada dentro de um envelope para ser entregue, no caso das mensagens de computador, elas são encapsuladas. Uma mensagem enviada por uma rede de computadores segue regras específicas de formato para que seja entregue e processada.

Os padrões do protocolo Ethernet definem muitos aspectos da comunicação de rede, como o formato e o tamanho do quadro, a temporização e a codificação. O formato dos quadros Ethernet especifica a localização dos endereços MAC de destino e de origem e informações adicionais, incluindo preâmbulo para sequenciamento e temporização, início do delimitador de quadro, comprimento e tipo de quadro e sequência de verificação de quadro para detectar erros de transmissão.

### A CAMADA DE ACESSO

É a parte da rede em que as pessoas recebem acesso a outros hosts e a arquivos compartilhados e impressoras. A camada de acesso atua como a primeira linha nos dispositivos de rede que conectam hosts à rede Ethernet com fio. Em uma rede Ethernet, cada host pode se conectar diretamente a um dispositivo de rede da camada de acesso usando um cabo Ethernet. Os hubs Ethernet contêm várias portas que são usadas para conectar hosts à rede. Apenas uma mensagem de cada vez pode ser enviada por um hub Ethernet. Duas ou mais mensagens enviadas ao mesmo tempo causarão um colisão. Como retransmissões excessivas podem congestionar a rede e reduzir o tráfego, os hubs passaram a ser considerados obsoletos e foram substituídos por switches Ethernet.

Um switch Ethernet é um dispositivo usado na camada 2. Quando um host envia uma mensagem para outro host conectado à mesma rede comutada, o switch aceita e decodifica os quadros para ler a parte do endereço MAC da mensagem. Uma tabela no switch, chamada de tabela de endereços MAC, contém uma lista de todas as portas ativas e dos endereços MAC de host conectados a elas. Quando uma mensagem é enviada entre hosts, o switch verifica se o endereço MAC de destino está na tabela. Se estiver, o switch criará uma conexão temporária, chamada de circuito, entre as portas de origem e de destino. Os switches Ethernet também permitem o envio e o recebimento de quadros no mesmo cabo Ethernet simultaneamente. Isso melhora o desempenho da rede eliminando colisões.

Um switch cria a tabela de endereços MAC examinando o endereço MAC de origem de cada quadro enviado entre hosts. Quando um novo host envia uma mensagem ou responde a uma mensagem inundada, o switch descobre imediatamente o endereço MAC e a porta à qual ele está conectado. A tabela é atualizada dinamicamente toda vez que um novo endereço MAC de origem é lido pelo switch.

---

## PROTOCOLO DE INTERNET (INTERNET PROTOCOL - IP)
### FINALIDADE DO ENDEREÇO IPv4

O endereço IPv4 é um endereço de rede lógico que identifica um host específico. Ele deve ser configurado corretamente e de forma exclusiva dentro da LAN, para fornecer comunicação local. Também deve ser configurado corretamente e de forma exclusiva no mundo, para fornecer comunicação remota.

Um endereço IPv4 é atribuído à conexão de interface de rede de um host. Essa conexão geralmente é uma placa de interface de rede (NIC) instalada no dispositivo.

Cada pacote enviado pela Internet tem um endereço IPv4 de origem e de destino. Essa informação é necessária para os dispositivos de rede garantirem que os dados cheguem ao destino e que as respostas sejam retornadas à origem.

---

### A ESTRUTURA DO ENDEREÇO IPv4

O endereço lógico IPv4 de 32 bits é hierárquico e contém duas partes, a rede e o host Como exemplo, um host com o endereço IPv4 192.168.5.11 e a máscara de sub-rede 255.255.255.0. Os três primeiros octetos (192.168.5) identificam a porção de rede do endereço e o último octeto (11) identifica o host. Isso é conhecido como endereçamento hierárquico porque a porção de rede indica a rede na qual está localizado cada endereço exclusivo de host.

Os roteadores precisam saber apenas como alcançar cada rede, em vez de precisar saber a localização de cada host individual. Com o endereçamento IPv4, poderão existir diversas redes lógicas em uma rede física se a porção de rede dos endereços dos hosts de rede lógica for diferente.

---
