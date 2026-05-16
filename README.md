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
- 
























