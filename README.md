# REDES DE COMPUTADORES
## COMUNICAÇÃO EM UM MUNDO CONECTADO
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

## COMPONENTES, TIPOS E CONEXÕES DE REDE
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

## REDES SEM FIO E MÓVEIS
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

## CONSTRUINDO UMA REDE DOMÉSTICA
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

## PRINCÍPIOS DE COMUNICAÇÃO
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

## MÍDIA DE REDE
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

## A CAMADA DE ACESSO
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

### A ESTRUTURA DO ENDEREÇO IPv4

O endereço lógico IPv4 de 32 bits é hierárquico e contém duas partes, a rede e o host Como exemplo, um host com o endereço IPv4 192.168.5.11 e a máscara de sub-rede 255.255.255.0. Os três primeiros octetos (192.168.5) identificam a porção de rede do endereço e o último octeto (11) identifica o host. Isso é conhecido como endereçamento hierárquico porque a porção de rede indica a rede na qual está localizado cada endereço exclusivo de host.

Os roteadores precisam saber apenas como alcançar cada rede, em vez de precisar saber a localização de cada host individual. Com o endereçamento IPv4, poderão existir diversas redes lógicas em uma rede física se a porção de rede dos endereços dos hosts de rede lógica for diferente.

---

## IPv4 E SEGMENTAÇÃO DE REDE
### UNICAST, BROADCAST E MULTICAST IPv4

Transmissão unicast refere-se a um dispositivo que envia uma mensagem para outro dispositivo em comunicações um-para-um. Um pacote unicast tem um endereço IP de destino que é um endereço unicast que vai para um único destinatário. Um endereço IP de origem só pode ser um endereço unicast, porque o pacote só pode originar-se de uma única origem. Isso independentemente de o endereço IP de destino ser unicast, broadcast ou multicast. Os endereços de host unicast IPv4 estão no intervalo de endereços de 1.1.1.1 a 223.255.255.255.

Transmissão broadcast refere-se a um dispositivo enviando uma mensagem para todos os dispositivos em uma rede, ou seja, comunicação de um para todos. Um pacote de broadcast possui um endereço IP de destino com todos os (1s) na parte do host ou 32 (um) bits. Um pacote de broadcast deve ser processado por todos os dispositivos no mesmo domínio de difusão. Um broadcast pode ser direcionado ou limitado. Um broadcast direcionado é enviado para todos os hosts em uma rede específica. Uma broadcast limitado é enviado para 255.255.255.255. Por padrão, os roteadores não encaminham broadcasts.

Transmissão multicast reduz o tráfego, permitindo que um host envie um único pacote para um conjunto de hosts selecionados que participem de um grupo multicast. Um pacote multicast é um pacote com um endereço IP de destino que é um endereço multicast. O IPv4 reservou os endereços 224.0.0.0 a 239.255.255.255 como intervalo de multicast. Cada grupo multicast é representado por um único endereço IPv4 multicast de destino. Quando um host IPv4 se inscreve em um grupo multicast, o host processa pacotes endereçados tanto a esse endereço multicast como a seu endereço unicast alocado exclusivamente.

---

### TIPOS DE ENDEREÇOS IPv4

Os endereços IPv4 públicos são endereços roteados globalmente entre os roteadores ISP. No entanto, nem todos os endereços IPv4 disponíveis podem ser usados na Internet. Existem blocos de endereços (conhecidos como endereços privados) que são usados pela maioria das organizações para atribuir endereços IPv4 a hosts internos. A maioria das redes internas, de grandes empresas a redes domésticas, usa endereços IPv4 privados para endereçar todos os dispositivos internos (intranet), incluindo hosts e roteadores. No entanto, os endereços privados não são globalmente roteáveis. Antes que o ISP possa encaminhar esse pacote, ele deve traduzir o endereço IPv4 de origem, que é um endereço privado, para um endereço IPv4 público usando NAT (Tradução de Endereços de Rede).

Os endereços de loopback (127.0.0.0 / 8 ou 127.0.0.1 a 127.255.255.254) são mais comumente identificados como apenas 127.0.0.1, esses são endereços especiais usados por um host para direcionar o tráfego para si próprio. Os endereços locais de link (169.254.0.0 / 16 ou 169.254.0.1 a 169.254.255.254) são mais conhecidos como endereços APIPA (endereçamento IP privado automático) ou endereços auto-atribuídos. Eles são usados por um cliente DHCP do Windows para auto-configurar no caso de não existirem servidores DHCP disponíveis.

Em 1981, os endereços IPv4 foram atribuídos usando o endereço classful, conforme definido na RFC 790 ([https://tools.ietf.org/html/rfc790](https://tools.ietf.org/html/rfc790)), Números Atribuídos. Os clientes receberam um endereço de rede com base em uma das três classes, A, B ou C. A RFC dividiu os intervalos de unicast em classes específicas da seguinte maneira:

* **Classe A (0.0.0.0/8 to 127.0.0.0/8)** – Projetado para suportar redes extremamente grandes com mais de 16 milhões de endereços de host.
* **Classe B (128.0.0.0 / 16 - 191.255.0.0 / 16)** – Projetada para oferecer suporte às necessidades de redes de tamanho moderado a grande com até aproximadamente 65.000 endereços de host.
* **Classe C (192.0.0.0 / 24 - 223.255.255.0 / 24)** – Projetado para oferecer suporte a pequenas redes com no máximo 254 hosts.

Há também um bloco multicast de Classe D que consiste em 224.0.0.0 a 239.0.0.0 e um bloco de endereço experimental de Classe E que consiste em 240.0.0.0 - 255.0.0.0.

Endereços IPv4 públicos são endereços roteados globalmente pela Internet. Endereços IPv4 públicos devem ser exclusivos. Os endereços IPv4 e IPv6 são gerenciados pela IANA (Internet Assigned Numbers Authority). A IANA gerencia e aloca blocos de endereços IP aos registros regionais de Internet (RIRs). Os RIRs são responsáveis por alocar endereços IP aos ISPs que fornecem blocos de endereços IPv4 para organizações e ISPs menores. As organizações também podem obter seus endereços diretamente de um RIR.

---

### SEGMENTAÇÃO DE REDE

Em uma LAN Ethernet, os dispositivos utilizam broadcast e ARP para localizar outros dispositivos. O ARP envia broadcast de Camada 2 para um endereço IPv4 conhecido na rede local para descobrir o endereço MAC associado. Os dispositivos em LANs Ethernet também localizam outros dispositivos usando serviços. Um host normalmente adquire sua configuração de endereço IPv4 usando o protocolo DHCP que envia broadcasts na rede local para localizar um servidor DHCP. Os switches propagam broadcasts por todas as interfaces, exceto a interface em que foram recebidos.

Um grande domínio de broadcast é uma rede que conecta vários hosts. Um problema desse tipo de domínio é que os hosts podem gerar broadcasts em excesso e afetar a rede de forma negativa. A solução é reduzir o tamanho da rede para criar domínios de broadcast menores em um processo denominado divisão em sub-redes. Os espaços de rede menores são chamados de sub-redes. Esta é a base da divisão em sub-redes: usar bits de host para criar sub-redes adicionais. A divisão em sub-redes reduz o tráfego total da rede e melhora seu desempenho. Permite o administrador implemente políticas de segurança como, por exemplo, quais sub-redes podem ou não se comunicar com quais sub-redes. Ela reduz o número de dispositivos afetados pelo tráfego broadcast anormal devido a configurações incorretas, problemas de hardware/software ou propósito malicioso.

---

## FORMATOS E REGRAS DE ENDEREÇAMENTO IPv6
### PROBLEMAS DE IPv4
O esgotamento de endereços IPv4 tem sido o fator motivador para a migração para o IPv6. O IPv6 tem um espaço de endereços maior, de 128 bits, fornecendo 340 undecilhões de endereços possíveis. Quando a IETF começou o desenvolvimento de um sucessor para o IPv4, aproveitou para corrigir as limitações do IPv4 e incluir aprimoramentos. Um exemplo é o ICMPv6, que inclui resolução de endereços e configuração automática de endereços não encontrados no ICMPv4.

Ambos IPv4 e IPv6 coexistem e a transição para apenas IPv6 levará vários anos. A IETF criou vários protocolos e ferramentas para ajudar os administradores de rede a migrarem as redes para IPv6. As técnicas de migração podem ser divididas em três categorias: pilha dupla, encapsulamento e tradução. Os dispositivos de pilha dupla executam os protocolos IPv4 e IPv6 simultaneamente. Tunelamento é um método de transporte de pacote IPv6 através de uma rede IPv4. O pacote IPv6 é encapsulado dentro de um pacote IPv4, de forma semelhante a outros tipos de dados. O NAT64 permite que dispositivos habilitados para IPv6 se comuniquem com dispositivos habilitados para IPv4 usando uma técnica de tradução semelhante ao NAT para IPv4. Um pacote IPv6 é traduzido para um pacote IPv4 e um pacote IPv4 é traduzido para um pacote IPv6.

### ENDEREÇAMENTO IPv6

Os endereços IPv6 têm 128 bits e são escritos como uma sequência de valores hexadecimais. Cada quatro bits são representados por um único dígito hexadecimal; perfazendo um total de 32 dígitos hexadecimais. Os endereços IPv6 não diferenciam maiúsculas e minúsculas e podem ser escritos tanto em minúsculas como em maiúsculas. No IPv6, um hexteto que se refere a um segmento de 16 bits, ou quatro dígitos hexadecimais. Cada “x” é um único hexteto, que tem 16 bits ou quatro díitos hexadecimais. Formato preferencial significa que o endereço IPv6 é gravado usando todos os 32 dígitos hexadecimais. Aqui está um exemplo – fe80:0000:0000:0000:0123:4567:89ab:cdef.

Existem duas regras que ajudam a reduzir o número de dígitos necessários para representar um endereço IPv6.

### Regra 1 - omitir zeros à esquerda

Você só pode omitir zeros à esquerda, não zeros à direita.

* 01AB pode ser representado como 1AB
* 09f0 pode ser representado como 9f0
* 0a00 pode ser representado como a00
* 00ab pode ser representado como ab

### Regra 2 - dois pontos duplos

Dois-pontos duplos (::) podem substituir qualquer sequência única e contígua de um ou mais hextetos de 16 bits que consistam em zeros. Por exemplo, 2001:db8:cafe:1:0:0:0:1 (0s iniciais omitidos) poderia ser representado como 2001:db8:cafe:1::1. Os dois-pontos duplos (::) são usados no lugar dos três hextetos compostos por zeros (0:0:0). Os dois-pontos duplos (::) só podem ser usados uma vez dentro de um endereço, caso contrário, haveria mais de um endereço resultante possível. Se um endereço tiver mais de uma string contígua de hextetos com zero, a melhor prática é usar dois pontos duplos (::) na string mais longa. Se as strings forem iguais, a primeira string deve usar dois pontos duplos (::).

---
## ENDEREÇAMENTO DINÂMICO COM DHCP
### ENDEREÇAMENTO ESTÁTICO E DINÂMICO
Com uma atribuição estática, o administrador de rede deve configurar manualmente as informações da rede para um host. No mínimo, isso inclui o endereço IPv4, a máscara de sub-rede e o gateway padrão do host. Embora a atribuição estática de informações de endereçamento possa proporcionar um controle maior dos recursos de rede, a digitação de informações em cada host pode ficar demorada. Ao usar endereçamento IPv4 estático, é importante manter uma lista precisa de quais endereços IPv4 estão atribuídos a quais dispositivos.

Os endereços IPv4 podem ser atribuídos automaticamente usando um protocolo conhecido como DHCP. O DHCP em geral é o método preferido de designação de endereços IPv4 para hosts em redes grandes porque reduz a carga sobre a equipe de suporte da rede e praticamente elimina erros de entrada. Outro benefício do DHCP é que o endereço não é permanentemente atribuído a um host, mas é só “alugado” por um período. Se o host é desligado ou retirado da rede, o endereço retorna ao pool para ser reutilizado.

Assim que você entra na área com um ponto de acesso sem fio, o cliente DHCP do seu notebook entra em contato com o servidor DHCP local por meio de uma conexão sem fio. O servidor DHCP atribui um endereço IPv4 ao seu notebook. Nas redes residenciais, é provável que o servidor DHCP esteja localizado no ISP e um host na rede residencial recebe a configuração IPv4 diretamente do ISP. Muitas redes de residências e pequenas empresas usam um modem e um roteador sem fio. Nesse caso, o roteador sem fio é tanto servidor como cliente DHCP.

### CONFIGURAÇÃO DO DHCPv4
O servidor DHCP é configurado com um intervalo (ou pool) de endereços IPv4 que podem ser atribuídos a clientes DHCP. Um cliente que precise de um endereço IPv4 enviará uma mensagem de descoberta DHCP que é um broadcast com o endereço IPv4 de destino 255.255.255.255 (32 uns) e o endereço MAC de destino FF-FF-FF-FF-FF-FF (48 uns). Todos os hosts na rede receberão esse quadro DHCP de broadcast, mas apenas um servidor DHCP responderá. O servidor responderá com uma oferta DHCP, sugerindo um endereço IPv4 para o cliente. O host então envia uma solicitação DHCP pedindo para usar o endereço IPv4 sugerido O servidor responde com um DHCP Acknowledgment.

Na maioria das redes de residências e pequenas empresas, um roteador sem fio fornece serviços DHCP aos clientes de rede local. Para configurar um roteador sem fio residencial, acesse a interface gráfica Web abrindo o navegador e inserindo o endereço IPv4 padrão do roteador O endereço IPv4 192.168.0.1 e a máscara de sub-rede 255.255.255.0 são os padrões para a interface interna do roteador. Este é o gateway padrão para todos os hosts na rede local e também o endereço IPv4 interno do servidor DHCP. A maioria dos roteadores sem fio residenciais têm o servidor DHCP ativado por padrão.

---
## O PROCESSO DE ARP
### MAC e IP

Às vezes, um host deve enviar uma mensagem, mas ele só sabe o endereço IP do dispositivo de destino. O host precisa saber o endereço MAC desse dispositivo. O endereço MAC pode ser descoberto usando resolução de endereços. Dois endereços principais são atribuídos a um dispositivo em uma LAN Ethernet:

- **Endereço físico (endereço MAC)** – Usado para comunicações de NIC para NIC na mesma rede Ethernet.
- **Endereço lógico (endereço IP)** – Usado para enviar o pacote do dispositivo de origem para o dispositivo de destino. O endereço IP de destino pode estar na mesma rede IP da origem ou em uma rede remota.

Quando o endereço IP de destino (IPv4 ou IPv6) estiver em uma rede remota, o endereço MAC de destino será o endereço do gateway padrão do host (ou seja, a interface do roteador). Os roteadores examinam o endereço IP de destino para determinar o melhor caminho para encaminhar o pacote IP. Quando o roteador recebe o quadro Ethernet, ele desencapsula as informações da Camada 2. Usando o endereço IP de destino, ele determina o dispositivo do próximo salto e, em seguida, encapsula o pacote IP em um novo quadro (da camada de enlace) para a interface de saída.

Ao longo de cada link do caminho, um pacote IP é encapsulado em um quadro. O quadro é específico para a tecnologia de enlace associada a esse link, como Ethernet. Se o dispositivo do próximo salto for o destino final, o endereço MAC de destino será o da NIC Ethernet do dispositivo.

### CONTENÇÃO DE BROADCAST

Uma mensagem pode conter apenas um endereço MAC de destino. A resolução de endereços permite que um host envie uma mensagem de broadcast para um endereço MAC exclusivo que é reconhecido por todos os hosts. O endereço MAC de broadcast é um endereço de 48 bits, com todos eles iguais a 1. Os endereços MAC geralmente são representados em notação hexadecimal. O endereço MAC de broadcast em notação hexadecimal é **FFFF.FFFF.FFFF**. Cada F em notação hexadecimal representa quatro uns em binário.

Quando um host envia uma mensagem de broadcast, os switches encaminham a mensagem para cada host conectado na mesma rede local. Por esse motivo, uma rede local (ou seja, uma rede com um ou mais switches Ethernet) também é conhecida como domínio de broadcast.

Se muitos hosts estiverem conectados ao mesmo domínio de broadcast, o tráfego de broadcast poderá ficar excessivo. O número de hosts e a quantidade de tráfego de rede que pode ser suportada na rede local são limitados pelos recursos dos switches usados para conectá-los. Para melhorar o desempenho, pode ser necessário dividir uma rede local em várias redes ou domínios de broadcast. Os roteadores são usados para dividir a rede em vários domínios de broadcast.

Em uma rede Ethernet local, uma NIC só aceitará um quadro se o endereço de destino for o endereço MAC de broadcast ou corresponder ao endereço MAC da NIC. A maioria dos aplicativos de rede depende do endereço IP de destino lógico para identificar a localização dos servidores e clientes. Como o host emissor determina o endereço MAC de destino a ser colocado no quadro? O host remetente pode fazer uma consulta ARP para descobrir o endereço MAC de qualquer host na mesma rede local.

O ARP usa um processo de três etapas para descobrir e armazenar o endereço MAC de um host da rede local, quando apenas o endereço IPv4 do host é conhecido:

1. O host remetente cria e envia um quadro destinado ao endereço MAC de broadcast. Incluído no quadro, está uma mensagem com o endereço IPv4 do host de destino a ser alcançado.
2. Cada host na rede recebe o quadro de broadcast e compara o endereço IPv4 na mensagem com o endereço IPv4 configurado. O host com o endereço IPv4 correspondente envia o endereço MAC de volta para o host emissor original.
3. O host emissor recebe a mensagem e armazena as informações do endereço IPv4 e do endereço MAC em uma tabela chamada tabela ARP.

O IPv6 usa um método semelhante conhecido como Descoberta de Vizinhos (Neighbor Discovery).

---

## ROTEAMENTO ENTRE REDES
### A NECESSIDADE DO ROTEAMENTO

À medida que as redes crescem, geralmente é necessário dividir uma rede de camada de acesso em várias redes de camada de acesso. As diversas formas de divisão de redes são definidas por critérios diferentes.

* **Contenção de broadcast** – Roteadores na camada de distribuição podem limitar broadcasts somente para a rede local onde devam ser escutados.
* **Requisitos de segurança** – Os roteadores na camada de distribuição podem separar e proteger determinados grupos de computadores onde residem informações confidenciais.
* **Localização física** – Os roteadores na camada de distribuição podem ser usados para interconectar redes locais em vários locais de uma organização que estão separados geograficamente.
* **Agrupamento lógico** – Os roteadores na camada de distribuição podem ser usados para agrupar logicamente usuários, como departamentos de uma empresa, que tenham necessidades comuns ou acesso a recursos.

A camada de distribuição conecta estas redes locais independentes e controla o fluxo do tráfego entre elas. Ela é responsável por garantir que o tráfego entre hosts na rede local permaneça local.

Um roteador é um dispositivo de rede que conecta várias redes IP de Camada 3. Na camada de distribuição da rede, os roteadores direcionam o tráfego e realizam outras funções essenciais em uma operação de rede eficiente. Os roteadores, como switches, conseguem decodificar e ler as mensagens que são enviadas para eles. Ao contrário dos switches, que tomam uma decisão de encaminhamento com base no endereço MAC da Camada 2, os roteadores fundamentam suas decisões de encaminhamento no endereço IP da Camada 3.

Sempre que a porção de rede dos endereços IP dos hosts de origem e de destino não coincidir, deverá ser usado um roteador para encaminhar a mensagem.

### A TABELA DE ROTEAMENTO

Cada porta ou interface em um roteador conecta-se a uma rede local diferente. Cada roteador contém uma tabela de todas as redes localmente conectadas e as interfaces que se conectam a essas redes.

Quando um roteador recebe um quadro, ele decodifica o quadro para obter o pacote que contém o endereço IP de destino. Ele combina a porção de rede do endereço IP de destino com as redes listadas na tabela de roteamento. Se o endereço de rede de destino estiver na tabela, o roteador encapsulará o pacote em um novo quadro para enviá-lo. Ele encaminha o novo quadro para a rede de destino, fora da interface associada ao caminho. O processo de encaminhamento de pacotes para a rede destino é chamado de roteamento.

Um roteador encaminha um pacote para um destes dois locais: a) uma rede diretamente conectada que contém o host de destino real ou b) outro roteador no caminho para o host de destino. Quando um roteador encapsula o quadro para encaminhá-lo para uma interface roteada, ele deve incluir um endereço MAC de destino. Se o roteador precisar encaminhar o pacote para outro roteador por meio de uma interface roteada, ele usará o endereço MAC do roteador conectado. Os roteadores obtêm esses endereços MAC nas tabelas ARP.

Um host conhece o endereço IPv4 do roteador por meio do endereço de gateway padrão configurado em suas configurações de TCP/IP. O endereço do gateway padrão é o endereço da interface do roteador conectada à mesma rede local do host de origem. Todos os hosts na rede local usam o endereço do gateway padrão para enviar mensagens ao roteador.

Tabelas de roteamento contêm endereços de redes e o melhor caminho para acessar essas redes. As entradas podem ser feitas na tabela de roteamento de duas maneiras: atualizadas dinamicamente por informações recebidas de outros roteadores na rede ou inseridas manualmente por um administrador de rede.

### CRIANDO UMA LAN

LAN refere-se a uma rede local ou a um grupo de redes locais interconectadas que estão sob o mesmo controle administrativo. Todas as redes locais dentro de uma LAN estão sob um controle administrativo. Outras características comuns das LANs são que elas normalmente usam protocolos Ethernet ou Wireless e suportam altas taxas de transmissão de dados.

Dentro de uma LAN, é possível colocar todos os hosts em uma única rede local ou dividi-los entre várias redes conectadas por um dispositivo na camada de distribuição.

Colocar todos os hosts em uma única rede local permite que eles sejam vistos por todos os outros hosts. Isso ocorre porque existe um domínio de broadcast e os hosts usam o ARP para se localizarem.

Colocando hosts adicionais em uma rede remota diminuirá o impacto em demandas de tráfego. No entanto, os hosts em uma rede não poderão se comunicar com hosts na outra rede sem o uso de roteamento. Os roteadores aumentam a complexidade da configuração de rede e podem introduzir latência (ou seja, atraso) nos pacotes enviados de uma rede local para outra.

---

## TCP e UDP
O UDP é um sistema de entrega de melhor esforço que não requer confirmação de recebimento. O UDP é preferível para aplicações como a transmissão de áudio e vídeo ao vivo, e Voz sobre IP (VoIP). Confirmações retardariam a entrega e retransmissões são indesejáveis. Os pacotes seguem um caminho da origem até um destino. Alguns pacotes podem ser perdidos, mas isso geralmente não é percebido.

Os pacotes TCP seguem um caminho da origem até o destino. No entanto, cada um dos pacotes tem um número de sequência. O TCP divide uma mensagem em pequenos pedaços conhecidos como segmentos. Os segmentos são numerados em sequência e passados para o processo IP para montagem em pacotes. O TCP monitora o número de segmentos que foram enviados a um host específico de um aplicativo específico. Quando o remetente não recebe uma confirmação dentro de um certo período, ele supõe que os segmentos foram perdidos e transmite-os novamente. Somente a parte da mensagem perdida é reenviada, e não toda a mensagem.

### NÚMEROS DE PORTA

Quando uma mensagem é entregue usando o TCP ou o UDP, os protocolos e os serviços são identificados por um número de porta. Uma porta é um identificador numérico dentro de cada segmento que é usado para rastrear conversas específicas entre um cliente e um servidor. Cada mensagem que um host envia contém uma porta origem e destino.

Quando uma mensagem é recebida por um servidor, é necessário que o servidor consiga determinar qual serviço está sendo solicitado pelo cliente. Os clientes são pré-configurados para usar uma porta de destino que foi registrada na Internet para cada serviço.

As portas são atribuídas e gerenciadas por uma organização conhecida como ICANN (Corporação da Internet para Atribuição de Nomes e Números). As portas foram divididas em três categorias e variam em número de 1 a 65.535.

* **Portas bem conhecidas** – As portas de destino que estão associadas a aplicativos de rede comuns são identificadas como portas bem conhecidas. Elas estão no intervalo de 1 a 1.023.
* **Portas registradas** – As portas 1.024 a 49.151 podem ser usadas como portas de destino ou de origem. Elas podem ser usadas por empresas para registrar aplicativos específicos, como os de mensagem instantânea.
* **Portas privadas** – As portas de 49.152 a 65.535 são geralmente utilizadas como portas de origem. Elas podem ser usadas por qualquer aplicativo.

O número da porta de origem é gerado dinamicamente pelo dispositivo de envio para identificar uma conversa entre dois dispositivos. Este processo permite que várias conversas ocorram simultaneamente. É comum que um dispositivo envie várias solicitações de serviço HTTP para um servidor Web ao mesmo tempo. Cada conversa HTTP separada é rastreada com base em portas origem.

O cliente preenche um número de porta destino no segmento para informar o servidor destino qual serviço está sendo solicitado. Um servidor pode oferecer mais de um serviço simultaneamente como serviços Web na porta 80, ao mesmo tempo que oferece o estabelecimento de uma conexão FTP na porta 21.

Conexões TCP desconhecidas podem representar uma grande ameaça à segurança. Elas podem indicar que algo ou alguém está conectado ao host local. Às vezes é necessário conhecer quais conexões TCP ativas estão abertas e sendo executadas em um host de rede. O netstat é um utilitário de rede importante que pode ser usado para verificar essas conexões. O comando netstat é usado para listar os protocolos em uso, o endereço e os números de porta locais, o endereço e os números de porta externos, e o estado da conexão.

---

## SERVIÇOS DA CAMADA DE APLICAÇÃO
### A RELAÇÃO CLIENTE - SERVIDOR

O termo servidor refere-se a um host executando um aplicativo de software que fornece informações ou serviços para outros hosts conectados à rede, como um servidor web. Um exemplo de software cliente é um navegador, como Chrome ou FireFox. Um único computador pode também executar vários tipos de software cliente. Um fator crucial para permitir que essas interações complexas funcionem é que todas elas usam padrões e protocolos acordados.

A principal característica de sistemas cliente/servidor é que o cliente envia uma solicitação para o servidor, o qual responde ao executar uma função, como o envio de um documento solicitado de volta para o cliente. A combinação de navegador Web e servidor Web é provavelmente a instância mais usada de um sistema cliente/servidor.

Um URI é uma sequência de caracteres que identifica um recurso de rede específico. As partes de uma URI são protocolo/esquema, nome do host, caminho e nome do arquivo e fragmento. Uma URI tem duas especializações:

* **URN** - Identifica apenas o namespace do recurso sem referência ao protocolo.
* **URL** - Isso define o localização de rede de um recurso específico na rede. URLs de HTTP ou HTTPS são normalmente usados por navegadores web. Outros protocolos como FTP, SFTP, SSH e outros podem ser usados por meio de uma URL.

### NETWORK APLLICATION SERVICES

Para a maioria das pessoas, os serviços de Internet mais comuns que eles usam incluem pesquisas na Internet, sites de mídia social, streaming de vídeo e áudio, sites de compras on-line, e-mail e mensagens. Cada um desses serviços depende de protocolos, do conjunto de protocolos TCP/IP, para comunicar de forma confiável as informações entre os clientes e os servidores. Os serviços comuns incluem: DNS, SSH, SMTP, POP, IMAP, DHCP, HTTP e FTP.

### DOMAIN NAME SYSTEM (SISTEMA DE NOMES DE DOMÍNIOS).

O DNS fornece uma maneira para os hosts solicitarem o endereço IP de um servidor específico. Os nomes DNS são registrados e organizados na Internet em grupos ou domínios específicos de alto nível. Alguns dos domínios de alto nível mais comuns na Internet são .com, .edu e .net.

Quando o servidor DNS recebe a solicitação de um host, ele verifica sua tabela para determinar o endereço IP associado a esse servidor web. Se o servidor DNS local não tiver uma entrada para o nome solicitado, ele consultará outro servidor DNS no domínio. Quando o servidor DNS aprende o endereço IP, essa informação é enviada de volta ao host.

### CLIENTES E SERVIDORES WEB

Quando um cliente Web recebe o endereço IP de um servidor Web, o navegador do cliente usa esse endereço IP e a porta 80 para solicitar serviços da Web. Essa solicitação é enviada para o servidor usando HTTP. O protocolo HTTP não é um protocolo seguro; as informações podem ser facilmente interceptadas por outros usuários à medida que os dados são enviados pela rede. Para fornecer segurança aos dados, o HTTP pode ser usado com protocolos de transporte seguros. As solicitações de HTTP seguro são enviadas para a porta 443. Essas solicitações usam https no endereço do site no navegador, em vez de http.

Quando um cliente Web recebe o endereço IP de um servidor Web, o navegador do cliente usa esse endereço IP e a porta 80 para solicitar serviços da Web. O conteúdo de informação de uma página web é codificado usando HTML. A codificação HTML informa ao navegador como formatar a página Web e quais gráficos e fontes usar.

Existem muitos servidores web e clientes web diferentes. Os padrões de HTML e do protocolo HTTP fazem com que esses servidores e clientes de diversos fabricantes trabalhem em conjunto sem dificuldades.

### CLIENTES E SERVIDORES FTP

O FTP fornece um método fácil de transferir arquivos de um computador para outro. Um host com software de cliente FTP pode acessar um servidor FTP para executar várias funções de gerenciamento de arquivos, como uploads e downloads. O servidor FTP permite que o cliente troque arquivos entre dispositivos. Ele também possibilita que os clientes gerenciem arquivos remotamente enviando comandos de gerenciamento de arquivos, como delete ou rename. Para conseguir isso, o serviço FTP usa duas portas diferentes para a comunicação entre cliente e servidor. Para iniciar uma sessão de FTP, as solicitações de conexão de controle são enviadas para o servidor usando a porta TCP de destino 21. Quando a sessão é aberta, o servidor usa a porta TCP 20 para transferir os arquivos de dados.

A maioria dos sistemas operacionais de cliente (como Windows, Mac OS e Linux) inclui uma interface de linha para o FTP. Há também um software cliente FTP baseado em GUI que fornece uma interface simples de arrastar e soltar para FTP.

### TERMINAIS VIRTUAIS

O Telnet fornece um método padrão de emulação de dispositivos terminais baseados em texto na rede de dados. O protocolo e o software cliente que implementa o protocolo são comumente chamados de Telnet. Os servidores Telnet escutam solicitações de clientes na porta TCP 23. Uma conexão usando Telnet é chamada de sessão vty, ou conexão. Em vez de usar um dispositivo físico para se conectar ao servidor, o Telnet usa software para criar um dispositivo virtual que fornece os mesmos recursos de uma sessão de terminal com acesso à CLI do servidor.

O Telnet não é considerado um protocolo seguro. Embora o protocolo Telnet possa exigir o login de um usuário, ele não suporta o transporte de dados criptografados. Todos os dados trocados durante as sessões Telnet são transportados como texto simples pela rede. Isso significa que os dados podem ser facilmente interceptados e compreendidos.

O SSH fornece a estrutura para proteger login remoto e outros serviços de rede segura. Ele também fornece autenticação mais forte do que o Telnet e suporta o transporte de dados de sessão usando criptografia. Os profissionais de rede devem procurar usar SSH no lugar de Telnet, sempre que possível.

### E-MAILS E MENSAGENS

Cada servidor de e-mail recebe e armazena e-mails de usuários que têm caixas de correio configuradas no servidor de e-mail. Cada usuário com uma caixa de correio deve usar um cliente de e-mail para acessar o servidor de e-mail e ler essas mensagens. Muitos sistemas de mensagens da Internet usam um cliente baseado na Web para acessar emails, incluindo Microsoft 365, Yahoo e Gmail. Os protocolos de aplicação usados no processamento de e-mail incluem SMTP, POP3 e IMAP4.

O SMTP é usado por um cliente de e-mail para enviar mensagens para o servidor de e-mail local. O servidor local então decide se a mensagem é destinada a uma caixa de correio local ou se é endereçada a uma caixa de correio em outro servidor. Se o servidor precisar enviar a mensagem para um servidor diferente, o SMTP será usado entre esses dois servidores. As solicitações SMTP são enviadas para a porta 25. Um servidor compatível com clientes POP recebe e armazena as mensagens endereçadas a seus usuários. Quando o cliente se conecta ao servidor de e-mail, as mensagens são baixadas no cliente. Por padrão, as mensagens não são mantidas no servidor após serem acessadas pelo cliente. Os clientes contatam os servidores POP3 na porta 110.

Um servidor compatível com clientes IMAP também recebe e armazena as mensagens endereçadas a seus usuários. Entretanto, ao contrário do POP, o IMAP mantém as mensagens nas caixas de correio no servidor, a menos que elas sejam excluídas pelo usuário. A versão mais recente de IMAP é o IMAP4, que ouve solicitações do cliente na porta 143.

As mensagens de texto podem ser chamadas de mensagens instantâneas, mensagens diretas, mensagens privadas e mensagens de bate-papo. As mensagens de texto permitem que os usuários conversem pela Internet em tempo real. Os serviços de mensagens de texto em um computador geralmente são acessados por meio de um cliente baseado na Web integrado a uma mídia social ou site de compartilhamento de informações. Esses clientes geralmente se conectam apenas a outros usuários do mesmo site.

Um cliente de telefonia pela Internet usa tecnologia peer-to-peer semelhante à usada por mensagens instantâneas. A telefonia IP usa VoIP, que converte sinais de voz analógicos em dados digitais. Os dados de voz são encapsulados em pacotes IP, que transportam a chamada telefônica pela rede.

---

## UTILITÁRIOS DE TESTE DE REDE
### Comandos

para solução de problemas. Vários softwares utilitários estão disponíveis para ajudar a identificar problemas de rede. A maioria desses utilitários é fornecida pelo sistema operacional como comandos da CLI.

Estes são alguns dos utilitários disponíveis:

* **ipconfig** - Exibe informações da configuração IP.
* **ping** - Testa conexões com outros hosts IP.
* **netstat** - Exibe as conexões de rede.
* **tracert** - Exibe a rota percorrida até o destino.
* **nslookup** - Consulta diretamente o servidor de nomes para obter informações sobre um domínio de destino.

O comando **ipconfig** é usado para exibir as informações de configuração de IP atuais de um host. A emissão deste comando a partir do prompt de comando exibirá as informações básicas de configuração, incluindo endereço IP, máscara de sub-rede e gateway padrão.

O comando **ipconfig /all** exibe informações adicionais que incluem o endereço MAC, os endereços IP do gateway padrão e os servidores DNS. Ele também indica se o DHCP está ativado, o endereço do servidor DHCP e as informações da concessão.

Se as informações de endereçamento IP forem atribuídas dinamicamente, o comando **ipconfig /release** liberará as ligações DHCP atuais. **ipconfig /renew** solicitará novas informações de configuração ao servidor DHCP. Um host pode conter informações de configuração de IP desatualizadas ou com falhas. Com uma simples renovação dessas informações, a conectividade pode ser recuperada.

Provavelmente, o utilitário de rede mais usado é o **ping**. A maioria dos dispositivos habilitados para IP oferece suporte a alguma forma do comando **ping** para testar se dispositivos de rede podem ou não ser alcançados através da rede IP. Quando um ping é enviado para um endereço IP, um pacote conhecido como **echo request** é enviado através da rede para o endereço IP especificado. Se o host de destino receber o **echo request**, ele responderá com um pacote conhecido como **echo reply**. Se a origem receber o **echo reply**, a conectividade será verificada pela resposta do endereço IP específico.
