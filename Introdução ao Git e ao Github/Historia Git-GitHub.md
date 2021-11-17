O GitHub foi desenvolvido por Chris Wanstrath, J. Hyett, Tom Preston-Werner e Scott Chacon usando Ruby on Rails, e começou em fevereiro de 2008. A empresa, GitHub, Inc., existe desde 2007 e está localizada em São Francisco.

O sombreamento do mapa ilustra o número de usuários como uma proporção da população da Internet de cada país. Os gráficos circulares que cercam os dois hemisférios descrevem o número total de usuários do GitHub (à esquerda) e comprometem (à direita) por país.

Em 24 de fevereiro de 2009, os membros da equipe do GitHub anunciaram, em uma palestra no Yahoo! sede, que no primeiro ano de estar on-line, o GitHub acumulou mais de 46 mil repositórios públicos, 17 mil dos quais foram formados apenas no mês anterior. Naquela época, cerca de 6200 repositórios haviam sido bifurcados pelo menos uma vez e 4600 foram fundidos.

Em 5 de julho de 2009, o GitHub anunciou que o site agora era aproveitado por mais de 100 mil usuários. Em 27 de julho de 2009, em outra palestra no Yahoo !, Preston-Werner anunciou que o GitHub tinha crescido para hospedar 90 mil repositórios públicos únicos, 12 mil tendo sido bifurcados pelo menos uma vez, para um total de 135 mil repositórios.

Em 25 de julho de 2010, o GitHub anunciou que estava hospedando 1 milhão de repositórios. Em 20 de abril de 2011, o GitHub anunciou que estava hospedando 2 milhões de repositórios.

Em 2 de junho de 2011, ReadWriteWeb informou que o GitHub havia ultrapassado o SourceForge e o Google Code em número total de commits para o período de janeiro a maio de 2011.

Em 9 de julho de 2012, Peter Levine, sócio geral da investidora do GitHub, Andreessen Horowitz, afirmou que o GitHub vinha crescendo a receita de 300% ao ano desde 2008, "lucrativamente quase todo o caminho".

Em 16 de janeiro de 2013, o GitHub anunciou que havia passado da marca de 3 milhões de usuários e, então, hospedava mais de 5 milhões de repositórios. Em 23 de dezembro de 2013, o GitHub anunciou que alcançou 10 milhões de repositórios.

Em junho de 2015, o GitHub abriu um escritório no Japão que é seu primeiro escritório fora dos EUA.

Em 29 de julho de 2015, o GitHub anunciou que havia captado US $ 250 milhões em financiamento em uma rodada liderada pela Sequoia Capital. A rodada valorizou a empresa em aproximadamente US $ 2 bilhões.

Em 2016, o GitHub ficou em 14º lugar na lista Forbes Cloud 100.

Em 28 de fevereiro de 2018, o GitHub foi vítima do segundo maior ataque de negação de serviço distribuído (DDoS) da história, com o tráfego de entrada chegando a um pico de cerca de 1,35 terabit por segundo.

Em 4 de junho de 2018, a Microsoft anunciou que havia chegado a um acordo para adquirir o GitHub por US $ 7,5 bilhões. [23] A compra foi encerrada em 26 de outubro de 2018.

Em 19 de junho de 2018, o GitHub expandiu seu GitHub Education oferecendo pacotes de educação gratuitos para todas as escolas.

Aquisição pela Microsoft
Em 4 de junho de 2018, a Microsoft anunciou a compra da plataforma por US$ 7,5 bilhões, equivalente a R$ 27,225 bilhões com dólar cotado a R$ 3,63 no dia 06/06/2018. Satya Nadella, diretor executivo da Microsoft, reafirma a nova postura da Microsoft frente ao código aberto, dizendo: "A Microsoft é uma empresa que desenvolve em primeiro plano e, ao unir forças com o GitHub, fortalecemos nosso compromisso com a liberdade, a abertura e a inovação dos desenvolvedores. Reconhecemos a responsabilidade da comunidade que assumimos com este acordo e faremos o nosso melhor trabalho para capacitar cada desenvolvedor a construir, inovar e resolver os desafios mais prementes do mundo."[3]

Referências
 «GitHub on Alexa». Consultado em 1 de junho de 2018
 «About». GitHub (em inglês). Consultado em 10 de julho de 2017
 «Microsoft + GitHub = Empowering Developers - The Official Microsoft Blog». The Official Microsoft Blog (em inglês). 4 de junho de 2018



O desenvolvimento do Git surgiu após vários desenvolvedores do kernel (núcleo) do Linux decidirem desistir de acessar ao sistema do BitKeeper, que é um software proprietário.[8] O acesso gratuito ao BitKeeper foi removido pelo detentor dos direitos autorais, Larry McVoy, depois de acusar Andrew Tridgell de usar de engenharia reversa nos protocolos do BitKeeper, alegando violação da licença do mesmo. Tridgell demonstrou, em uma apresentação na Linux.Conf.Au, realizada em 2005, que o processo de engenharia reversa utilizado não foi mais do que simplesmente direcionar um telnet para a porta apropriada de um servidor BitKeeper e digitar "help" (ajuda).[9]

Torvalds queria um sistema distribuído que ele pudesse utilizar de forma similar ao BitKeeper (BK), mas nenhum dos sistemas livres disponíveis atendia suas necessidades, particularmente com relação à performance. Segue abaixo uma parte retirada de um e-mail, de 7 de Abril de 2005, escrito enquanto desenvolvia seu primeiro protótipo:[10]

De qualquer forma, os SCVs que olhei dificultam as coisas. Uma delas (a maior delas, na verdade) que estive trabalhando é fazer este processo ser realmente eficiente. Se leva meio minuto para aplicar um patch e ainda lembrar o que mudou, etc (e francamente, isso é rápido para a maioria dos SCVs por aí para um projeto do tamanho do Linux), daí uma série de 250 e-mails (que não é estranho acontecer quando eu sincronizo com o Andrew, por exemplo) demora duas horas. Se um dos patches no meio do processo não é aplicado, as coisas ficam realmente muito feias.

Agora, o BK (BitKeeper) não era um inferno também (na verdade, comparado com todo o resto, o BK é um inferno em velocidade, geralmente em uma ou duas ordens de magnitude), e levou cerca de 10-15 segundos por e-mail quando mesclei meus arquivos com o Andrew. MESMO ASSIM, com o BK isso não era um problema tão grande, visto que mesclas de arquivos de BK?>BK eram tão fáceis, eu nunca precisei das lentas mesclas por e-mail com nenhum dos outros desenvolvedores principais. Então um "mesclador" de um SCV baseado em patches precisaria ser realmente mais rápido que o BK. O que realmente é extremamente difícil.

Então eu estou escrevendo alguns scripts para tentar alinhar tudo mais rápido. Indicações iniciais são de que eu poderei fazer isso tão rápido quanto eu aplico patches, mas para ser franco, estou no máximo com metade pronto, e se eu estiver na direção errada, talvez essa não seja a mais pura verdade. De qualquer forma, a razão de que eu consigo criar tudo isso tão rápido é que meus scripts não serão um SCV, serão tipo um "registro de estado do Linus" bem específico. Isso vai fazer minhas mesclas lineares de patches muito mais eficientes no tempo, e nestas condições, possível.

(Se a aplicação de um patch demora três segundos, até mesmo uma série grande de patches não é um problema: se eu for notificado em um minuto ou dois que falhou na metade do caminho, sem problemas, eu posso então simplesmente arrumar manualmente. É por isso que a latência é crítica - se eu tivesse que fazer as coisas efetivamente "desconectado", eu não poderia, por definição, arrumar as coisas quando problemas aparecessem).
Torvalds teve vários critérios para o projeto:

Tomar o CVS como um exemplo do que não fazer; na dúvida, tomar exatamente a decisão contrária. Para citar Torvalds, de certa forma mordendo a língua:
"Nos primeiros 10 anos de manutenção do kernel, nós literalmente usamos patches de tarballs, o que é muito superior como controle de versão que o CVS, mas eu acabei usando o CVS por 7 anos em uma empresa comercial [Transmeta[11]] e eu odiava de paixão. Quando eu digo que eu odiava de paixão, eu também tenho que dizer que, se houver algum usuário de SVN (Subversion) na platéia, talvez você queira sair. Porque meu ódio pelo CVS significa que eu vejo o Subversion como sendo o projeto iniciado mais sem objetivo de todos os tempos. O slogan do Subversion por um tempo foi "CVS feito [do jeito] certo", ou algo assim, e se você começa com esse slogan, você não vai a lugar nenhum. Não tem como o CVS fazer [do jeito] certo."
Suportar um fluxo distribuído, como o BitKeeper
"O BitKeeper não foi simplesmente o primeiro sistema de versionamento que eu senti que absolutamente valia a pena, foi também o sistema de controle de versão que me ensinou porque eles têm um objetivo, e como você realmente deve fazer as coisas. Então o Git, de várias formas, mesmo que de uma visão técnica muito diferente do BitKeeper (e isso foi outro objetivo de projeto, porque eu queria deixar claro que não era um plágio do BitKeeper), muitos dos fluxos que usamos no Git vieram diretamente dos fluxos que aprendemos com o BitKeeper."
Várias firmes proteções contra corrompimento de arquivos, seja por acidente ou origem maldosa[12]
Alto desempenho
Os primeiros três critérios acima eliminam cada controle de versão preexistente ao Git, exceto pelo Monotone, e o quarto elimina todos. Então, imediatamente depois de liberar a versão 2.6.12-rc2 de desenvolvimento do kernel do Linux, ele começou a desenvolver o seu próprio.

O desenvolvimento do Git começou em 3 de Abril de 2005.[13] O projeto foi anunciado em 6 de Abril,[14] e tornou-se auto-hospedeiro no dia 7 de Abril.[13] A primeira mescla de arquivos (merge) em múltiplos ramos (branches) foi realizado em 18 de Abril.[15] Torvalds alcançou seus objetivos de performance; em 29 de Abril, o recém-nascido Git se tornou referência ao registrar patches para a árvore de desenvolvimento do kernel do Linux na taxa de 6,7 por segundo.[16] No dia 16 de Junho, a entrega do kernel 2.6.12 foi gerenciada pelo Git.[17]

Mesmo que fortemente influenciado pelo BitKeeper, Torvalds deliberadamente tentou evitar abordagens tradicionais, levando a um design único.[18] Ele desenvolveu o sistema até que fosse possível sua utilização por usuários técnicos, entregando então a manutenção do software para Junio Hamano, um dos principais colaboradores do projeto, em 16 de Julho de 2005.[19] Hamano foi responsável pela entrega da versão 1.0 em 21 de dezembro de 2005,[20] e continua como responsável pela manutenção do mesmo.

Desenho
O desenho do Git foi inspirado no BitKeeper e no Monotone.[21][22] Seu desenho original era de um controle de versão de baixo nível, de forma que outros pudessem desenvolver interfaces em cima dele, como por exemplo o cogito ou o StGIT.[22] No entanto, o núcleo do projeto do Git se tornou, desde então, um sistema de controle de versão completo que pode ser diretamente utilizado.[23]

Características
O projeto do Git é uma síntese da experiência de Torvalds com a manutenção do desenvolvimento altamente distribuído do projeto do Linux, junto com seu íntimo conhecimento de performance de sistemas de arquivos (conhecimentos adquiridos no mesmo projeto) e a necessidade urgente de produzir um sistema funcional em um curto espaço de tempo. Essas influências o levaram às seguintes escolhas de implementação:

Suporte consistente para desenvolvimentos não lineares
O Git suporta rápidas criações de ramos (branches) e mesclas (merges), e inclui ferramentas específicas para visualização e navegação de históricos de desenvolvimento não lineares. Uma suposição intrínseca no Git é que uma mudança será mesclada mais do que é escrita, enquanto é passada por vários revisores.
Desenvolvimento distribuído
Assim como o Darcs, o BitKeeper, o Mercurial, o SVK, o Bazaar e o Monotone, o Git dá a cada desenvolvedor uma cópia local completa de todo o histórico de desenvolvimento, e as mudanças são copiadas de um único repositório para outro. Estas mudanças são importadas como ramos (branches) adicionais de desenvolvimento, e podem sofrer uma mescla (merge) da mesma forma que um ramo de desenvolvimento local.
Compatibilidade com protocolos/sistemas existentes
Repositórios podem ser publicados por HTTP, FTP, rsync, um protocolo Git sobre uma porta conhecida ou por ssh. O Git também tem uma emulação de servidor CVS, o que habilita a existência de clientes CVS e extensões (plugins) em diversos ADIs a utilizar os repositórios Git. O Subversion e o svk podem utilizar os repositórios diretamente com o git-svn.
Manipulação eficiente de projetos extensos
Torvalds descreveu o Git como sendo veloz e escalável,[24] e testes de performance realizados pela Mozilla apontaram que o Git é uma ordem de magnitude mais rápido que alguns sistemas de controle de versão. Obter o histórico das revisões salvos em repositórios locais resulta ser duas ordens de magnitude mais rápido que obtê-los de um servidor remoto.[25][26] Um detalhe interessante é que o Git não fica mais lento com o aumento do histórico do projeto.[27]
Autenticação criptográfica do histórico
O histórico do Git é salvo de uma maneira que o nome de uma determinada revisão (um "commit", ou entrega, nos termos do Git) depende de todo o histórico de desenvolvimento que leva até este commit. Uma vez publicado, não é possível mudar as versões antigas sem passar despercebido. A estrutura é similar a uma árvore hash (hash tree), mas com dados adicionais nos nós e nas folhas.[28] (o Mercurial e o Monotone também possuem esta propriedade.)
Modelo baseado em ferramentas
O Git foi modelado como um conjunto de programas escrito em C, e numerosos scripts em shell que encapsulam estes programas.[29] Embora muitos destes scripts tenham sido reescritos em C, como parte de um esforço de portar o Git para o Windows, o modelo básico continua, sendo fácil agrupar seus componentes.[30]
Estratégias de mescla (merge) conectáveis
Como parte de desenho em ferramentas, o Git tem um conjunto bem definido de modelos de uma mescla incompleta, e possuí vários algoritimos para completá-las, culminando em comunicar ao usuário que é incapaz de completar o merge automaticamente, sendo necessária uma edição manual.
O lixo se acumula se não for limpo
Abortar operações ou desfazer mudanças irá deixar objetos sem valor pendentes no banco de dados. Existe porém uma pequena fração desejável de objetos no sempre crescente histórico, mas liberar o espaço usando git gc --prune pode ser uma operação lenta.[31]
Empacotamento periódico explícito de objetos
O Git armazena cada novo objeto criado como um arquivo separado. Embora cada arquivo seja individualmente comprimido, isso requer um espaço considerável no disco e é ineficiente. Isto é resolvido com o uso de "pacotes" que armazenam um grande número de objetos em um único arquivo (ou pela rede), comprimidos pelo delta entre eles. Pacotes são comprimidos usando a heurística de que arquivos com o mesmo nome são provavelmente similares, mas que não dependam exatamente disso. Mesmo assim, novos objetos criados (novo histórico adicionado) são gravados um a um, e reempacotamentos periódicos são necessários para manter o espaço de forma eficiente. O Git faz reempacotamentos periódicos automaticamente, mas também é possível fazer reempacotamentos manuais com o comando git gc.
Outra propriedade do Git é que ele salva o estado (snapshot) dos diretórios de arquivos. Os sistemas mais antigos de controle de versão de código fonte, Sistemas de Controle de Código Fonte (SCCF) e Sistemas de Controle de Revisão (SCR), trabalhavam em cima de arquivos individuais, enfatizando o espaço em disco ganho por intercalação de deltas (SCCF) ou por codificação de deltas (RCS) entre versões (mais similares). Sistemas de controle de versão posteriores mantiveram esta noção de arquivos possuírem uma identidade através de múltiplas revisões de um projeto. Porém, Torvalds rejeitou esse conceito.[32] Consequentemente, o Git não salva relacionamentos entre revisão de arquivos em nenhum nível abaixo da árvore de diretório do código fonte.

Relacionamentos inexplícitos de revisão remete a consequências significativas:

É pouco mais dispendioso examinar o histórico de um único arquivo do que o histórico de todo o projeto.[33] Para obter o histórico de mudanças de um arquivo, Git precisa caminhar pelo histórico global e então verificar qual mudança modificou aquele arquivo. Este método de examinar o histórico faz, porém, com que o Git produza igual eficiência em mostrar um histórico de mudanças de um ou de vários arquivos arbitrários. Por exemplo, é comum o caso de um subdiretório da árvore de arquivos fontes mais um arquivo global de cabeçalho associado.
Renomeação de arquivos são feitos de forma implícita. Uma queixa comum no CVS é que este usa o nome do arquivo para identificar o seu histórico de revisões. Então, não é possível mover ou renomear um arquivo sem interromper ou renomear seu histórico,o que, consequentemente, faz com que o histórica seja impreciso. A maioria dos controles de revisão pós-CVS resolve este problema por dar um tipo de identidade por nome único invariável para cada arquivo (um tipo de nó-i) que continua mesmo após renomeações. O Git não salva este tipo de identificador, e isso é uma vantagem alegada por Torvalds.[34][35] Arquivos de código fonte, às vezes, são divididos, mesclados ou simplesmente renomeados.[36] Salvar todas estas mudanças como simples renomes poderia congelar uma descrição imprecisa do que aconteceu na história real do mesmo (que é imutável). Git resolve este problema por detectar renomes enquanto navega pela história dos estados invés de gravá-los quando o estado é criado.[37] (Para ser breve, dado um arquivo numa revisão N, um arquivo de mesmo nome numa revisão N-1 é seu ancestral comum. Porém, quando não existe arquivo com um nome parecido na revisão N-1, o Git procura por um arquivo que existiu apenas na revisão N-1 e que era similar ao arquivo novo). No entanto, não é necessário mais tempo de processamento intensivo toda vez que o histórico é revisado. Existem também numerosas opções para ajustar estas heurísticas.
O Git implementa várias estratégias de merge (mescla de arquivos); uma não padrão pode ser selecionada durante um merge:[38]

resolve (resolver): o tradicional algoritmo de merge em três vias.
recursive (recursivo): Este é o padrão quando baixando ou mesclando um branch, uma variante do algoritmo de mescla em três vias. Quando há mais de um ancestral comum que pode ser usado em um merge de três vias, cria-se uma árvore de merge dos ancestrais comuns e usa-se isso como a árvore de referência para o merge em três vias. Isto têm resultado em menor número de conflitos em merges sem causar merges errados por testes realizados em merges tirados do histórico de desenvolvimento do kernel do Linux 2.6. Adicionalmente pode detectar e lidar com merges envolvendo renomeações."[39]
octopus (polvo): Este é o padrão quando efetuado merge em mais de duas heads.
Implementação
Como o BitKeeper, o Git não usa um servidor centralizado. Entretanto, os primórdios do Git não são inerentemente um sistema de gerenciamento de versão. Torvalds explica:[40]
Você pode ver o git apenas como um sistema de arquivos por vários motivos — ele é um armazenamento endereçável de conteúdo (SCM), e tem o conceito de versionamento, mas eu realmente o modelei vindo de um problema no ponto de vista de um sistema de arquivos (ei, eu faço núcleos de sistemas operacionais), e na verdade eu não tenho absolutamente nenhum interesse em criar um sistema tradicional de SCM.
Apesar de suas intenções, o Git agora possui toda a coleção de funcionalidade de um SCM tradicional.[41]

O Git possuí duas estruturas de dados: um índice mutável que provê informações sobre o diretório de trabalho e a próxima revisão a ser cometida; e um banco de dados de objetos de acréscimo imutável.

O banco de dados de objetos contém quatro tipos de objetos:

Um objeto blob é o conteúdo de um arquivo. Estes objetos não possuem nomes, datações ou outros metadados.
Um objeto tree (árvore) é o equivalente a um diretório. Ele contém um lista de nomes de arquivos, cada um com bits que informam o tipo e o nome do blob, da árvore, ligação simbólica ou conteúdo de diretório que pertence a este nome. Este objeto descreve o estado da árvore de diretório.
Um objeto commit (entrega) liga árvores de objetos junto com um histórico. Ele contém o nome de uma árvore de objetos (da raiz de diretórios), datação, uma mensagem de log, e os nomes de zero ou mais objetos-pai de commit.
Um objeto tag (rótulo) é um invólucro que referencia outros objetos e pode conter metadados adicionais relacionados a outro objeto. Em geral, é usado para armazenar uma assinatura digital de um objeto commit correspondente àquela release de dados que estão sendo rastreados pelo Git.
O índice serve como um ponto de conexão entre o banco de dados de objetos e a árvore de trabalho.

Cada objeto é identificado por um hash SHA-1 de seu conteúdo. O Git computa o hash e usa esse valor como nome para o objeto. O objeto é colocado em um diretório que corresponde aos primeiros dois caracteres deste hash. O resto do hash é usado como um nome de arquivo para cada objeto.

O Git armazena cada revisão do arquivo com um único objeto blob. Os relacionamentos entre os blobs podem ser encontrados por examinar à árvore de objetos commit. Objetos recém adicionados são armazenados internamente usando compressão do zlib. Isto pode consumir uma grande quantidade de espaço de disco rapidamente. Desta forma, os objetos são combinados em pacotes, que são comprimidos em delta para salvar espaço, gravando blobs como mudanças relativas a outros blobs.

Servidores Git tipicamente escutam na porta TCP/IP 9418.[42]

Portabilidade
O Git está primariamente desenvolvido para Linux, mas pode ser usado em outros sistemas operacionais baseados no Unix, incluindo o BSD, o Solaris e o Darwin. O Git é extremamente rápido em arquiteturas POSIX como o Linux.[43]

O Git também roda no Microsoft Windows. Existem duas variantes:

Uma adaptação nativa para Microsoft Windows, chamada msysgit (usando MSYS da MinGW). Ao passo que é relativamente mais vagaroso que a versão para o Linux,[44] ele é rápido de forma aceitável[45] e é notoriamente usado em produção, com apenas algumas dificuldade menores.[46] Em particular, alguns comandos ainda não estão disponíveis nas GUIs, e precisam ser chamadas por linha de comando.
O git também roda em cima do Cygwin (uma camada de emulação POSIX),[47] embora é notoriamente mais lento, especialmente para comando escritos em shell script.[48] Isto é causado principalmente pelo alto custo realizado pelo comando fork emulado pelo Cygwin. Entretanto, as recentes reescritas de vários comandos do Git (originalmente escritas em shell script) para a linguagem C, resultaram em um ganho significativo de performance no Windows.[49]
Outras alternativas para rodar o Git inclui:

git-cvsserver (que emula um servidor CVS, permitindo seu uso em cliente CVS para Windows):[50]
Ambientes de desenvolvimento baseados em Eclipse para Git, baseado em implementações puras em Java no interior do Git: egit
Suporte do NetBeans para o Git está em desenvolvimento [11] e está também disponível pelo plugin NbGit
O TortoiseGit, Git-Cheetah e o Git Extensions são extensões clientes para o Gerenciador de Arquivos do Windows, assim como versões independentes de GUI e o plugin para Visual Studio. O Git Source Control Provider é outro software gratuito em forma de plugin para o Visual Studio que exibe o status do projeto Git no 'solution explorer'.
IntelliJ IDEA Versão 8.1 agora suporta o Git por um plugin embutido: Intellij Version Control Systems Integration
Xcode 4 - assim como a versão 4 de demonstração, o git está disponível como parte da IDE [12]
Git#é uma implementação .Net/Mono do git.
Refatorar as operações de mais baixo nível em bibliotecas poderia, teoricamente, permitir a reimplementação do componente de níveis mais altos para o Windows sem reescrever o resto.[51]

Adoção
Hospedagem de código fonte
Os seguintes websites provêm hospedagem gratuita de código fonte para repositório Git:[52]

BerliOS
GitHub
Gitorious
Sourceforge
GNU Savannah
Project Kenai
Unfuddle
SourceRepo
Google Code
Bitbucket
GitLab
«Azure DevOps»
Projetos que usam Git
Um grande número de projetos de software de alto-padrão estão utilizando agora o Git como controle de revisão::[53]

Amarok[54][55]
Android[56]
Arch Linux
Aquamacs Emacs
BlueZ[57]
Btrfs[58]
Clojure[59]
CakePHP[60]
cURL[61]
Debian[62]
Digg[63]
DragonFly BSD[64]
Eclipse[65]
Elinks[66]
Fedora
FFmpeg [67]
Freenet[68]
FreeSWITCH[69]
git[70]
GITORA
GIMP[71]
GNOME[72][73]
GPM[74]
GStreamer[75]
gThumb[76]
GTK+[77]
Hurd[78]
jQuery[79]
Laika (EHR testing framework)[80]
LilyPond (music typesetting)[81]
Linux kernel
Linux Mint[82][83]
LMMS[84]
Maemo[85]
MeeGo[86]
Merb[87]
MicroEMACS
Mono[88][89]
MooTools[90]
One Laptop Per Child (OLPC)[91]
OpenFOAM[92]
openSUSE[93]
Penumbra: Overture [94][95]
Perl[96]
PHP[97]
phpBB[98]
Prototype.js[99]
Qt[100]
Reddit[101]
rsync[102]
RTEMS - Real-Time Executive for Multiprocessor Systems[103]
Ruby on Rails[104]
Samba[105]
SproutCore[106]
Starlink[107]
Sugar[108]
SWI-Prolog[109]
Trilinos
VLC[110]
VTK[111]
Wine[112]
Xfce[113]
Xiph[114]
X.org Server[115]
x264[110]
Yahoo! UI Library[116]
Zend Framework[117]
O projeto KDE começou a migrar para o Git, o Amarok completou sua migração[118][119] e logo também a do Phonon.[120] A comunidade do Drupal recentemente anúnciou planos para migrar o desenvolvimento para Git.[121]

Ver também
Mercurial
Sistema de controle de versões
Referências
 «'git' meaning in the Cambridge English Dictionary»
 «Definition of git by Oxford Dictionary»
 «When it comes to reproducible science, Git is code for success». www.natureindex.com. Consultado em 20 de junho de 2018
 «After controversy, Torvalds begins work on "git"». InfoWorld. 19 de abril de 2005. ISSN 0199-6649. Consultado em 22 de abril de 2013 Texto " Platforms - InfoWorld:" ignorado (ajuda)
 «Git FAQ - Git SCM Wiki:». Git.or.cz. Consultado em 22 de abril de 2013
 Robert McMillan (20 de abril de 2005). «After controversy, Torvalds begins work on "git"» (em inglês). PC World. Consultado em 2 de janeiro de 2016. When asked why he called the new software, "git," British slang meaning "a rotten person," he said. "I'm an egotistical bastard, so I name all my projects after myself. First Linux, now git."
 Torvalds, Linus and David Diamond, Just for Fun: The Story of an Accidental Revolutionary, 2001, ISBN 0-06-662072-4
 «Feature: No More Free BitKeeper | KernelTrap.org». Consultado em 23 de maio de 2012. Arquivado do original em 23 de maio de 2012
 Jonathan Corbet (20 de abril de 2005). «Como Tridge usou engenharia reversa no BitKeeper». Linux Weekly News
 Linus Torvalds (7 de abril de 2005). «Re: Kernel SCM saga..». linux-kernel (Lista de grupo de correio)
 Linus Torvalds (31 de outubro de 2005). «Re: git contra o CVS (contra o bk)». git (Lista de grupo de correio)
 Linus Torvalds (10 de junho de 2007). «Re: fatal: aumento inconsistente grave». git (Lista de grupo de correio) Uma breve descrição dos objetivos de integridade de dados no projeto do Git.
 Linus Torvalds (27 de fevereiro de 2007). «Re: Trivia: When did git self-host?». git (Lista de grupo de correio)
 Linus Torvalds (6 de abril de 2005). «Kernel SCM saga..». linux-kernel (Lista de grupo de correio)
 Linus Torvalds (17 de abril de 2005). «First ever real kernel git merge!». git (Lista de grupo de correio)
 Matt Mackall (29 de abril de 2005). «Mercurial 0.4b vs git patchbomb benchmark». git (Lista de grupo de correio)
 Linus Torvalds (17 de junho de 2005). «Linux 2.6.12». git-commits-head (Lista de grupo de correio)
 Linus Torvalds (20 de outubro de 2006). «Re: VCS comparison table». git (Lista de grupo de correio) A discussion of Git vs. BitKeeper
 Linus Torvalds (27 de julho de 2005). «Meet the new maintainer…». git (Lista de grupo de correio)
 Junio C Hamano (21 de dezembro de 2005). «ANNOUNCE: GIT 1.0.0». git (Lista de grupo de correio)
 Linus Torvalds (5 de maio de 2006). «Re: [ANNOUNCE] Git wiki». linux-kernel (Lista de grupo de correio) "Some historical background" on git's predecessors
 Linus Torvalds (8 de abril de 2005). «Re: Kernel SCM saga». linux-kernel (Lista de grupo de correio). Consultado em 20 de fevereiro de 2008
 Linus Torvalds (23 de março de 2006). «Re: Errors GITtifying GCC and Binutils». git (Lista de grupo de correio)
 Linus Torvalds (19 de outubro de 2006). «Re: VCS comparison table». git (Lista de grupo de correio)
 jst, Johnny (30 de novembro de 2006). «bzr/hg/git performance». Jst's Blog. Consultado em 20 de fevereiro de 2008. Arquivado do original em 29 de maio de 2010 |último= e |autor= redundantes (ajuda), benchmarking "git diff" against "bzr diff", and finding the former 100x faster in some cases.
 Roland Dreier (13 de novembro de 2006). «Oh what a relief it is», observing that "git log" is 100x faster than "svn log" because the latter has to contact a remote server.
 Robert Fendt, Robert (21 de janeiro de 2009). DVCS Round-Up: One System to Rule Them All?—Part 2. [S.l.]: Linux Foundation. Consultado em 25 de junho de 2009. One aspect that really sets Git apart is its speed. …dependence on repository size is very, very weak. For all facts and purposes, Git shows nearly a flat-line behavior when it comes to the dependence of its performance on the number of files and/or revisions in the repository, a feat no other VCS in this review can duplicate (although Mercurial does come quite close). |último= e |autor= redundantes (ajuda)
 «Git User's Manual - Git Concepts - Trust». 18 de outubro de 2006
 Linus Torvalds. «Re: VCS comparison table». git (Lista de grupo de correio). Consultado em 10 de abril de 2009, describing Git's script-oriented design
 iabervon (22 de dezembro de 2005). «Git rocks!», praising Git's scriptability
 «Git User's Manual». 5 de agosto de 2007
 Linus Torvalds (10 de abril de 2005). «Re: more git updates..». linux-kernel (Lista de grupo de correio)
 Bruno Haible (11 de fevereiro de 2007). «how to speed up "git log"?». git (Lista de grupo de correio)
 Linus Torvalds (1 de março de 2006). «Re: impure renames / history tracking». git (Lista de grupo de correio)
 Junio C Hamano (24 de março de 2006). «Re: Errors GITtifying GCC and Binutils». git (Lista de grupo de correio)
 Junio C Hamano (23 de março de 2006). «Re: Errors GITtifying GCC and Binutils». git (Lista de grupo de correio)
 Linus Torvalds (28 de novembro de 2006). «Re: git and bzr». git (Lista de grupo de correio), on using git-blame to show code moved between source files
 Linus Torvalds (18 de julho de 2007). «git-merge(1)»
 Linus Torvalds (18 de julho de 2007). «CrissCrossMerge». Consultado em 31 de agosto de 2010. Arquivado do original em 13 de janeiro de 2006
 Linus Torvalds (10 de abril de 2005). «Re: more git updates…». linux-kernel (Lista de grupo de correio)
 Linus Torvalds (23 de março de 2006). «Re: Errors GITtifying GCC and Binutils». git (Lista de grupo de correio)
 «Exporting a git repository via the git protocol». Kernel.org. Consultado em 17 de novembro de 2009
 Stenback, Johnny (30 de novembro de 2006). «bzr/hg/git performance». Jst's Blog. Consultado em 20 de fevereiro de 2008. Arquivado do original em 29 de maio de 2010
 Johannes Schindelin (14 de outubro de 2007). «Re: Switching from CVS to GIT». git (Lista de grupo de correio) A subjective comparison of Git under Windows and Linux on the same system.
 Martin Langhoff (15 de outubro de 2007). «Re: Switching from CVS to GIT». git (Lista de grupo de correio) Experience running msysgit on Windows
 Johannes Sixt (15 de outubro de 2007). «Re: Switching from CVS to GIT». git (Lista de grupo de correio)
 Shawn Pearce (24 de outubro de 2006). «Re: VCS comparison table». git (Lista de grupo de correio)
 Johannes Schindelin (1 de janeiro de 2007). «Re: [PATCH] Speedup recursive by flushing index only once for all». git (Lista de grupo de correio)
 Shawn O. Pearce (18 de setembro de 2007). «[PATCH 0/5] More builtin-fetch fixes». git (Lista de grupo de correio)
 «git-cvsserver(1)». Kernel.org. 2 de abril de 2009. Consultado em 15 de junho de 2009
 Johannes Schindelin (2 de março de 2006). «Re: windows problems summary». git (Lista de grupo de correio)
 Git Hosting - Git SCM Wiki
 «Projects that use Git for their source code management». Consultado em 20 de fevereiro de 2008
 Getting Started/Sources/Amarok Git Tutorial - KDE TechBase
 «amarok in kde-developers - Gitorious». Consultado em 31 de agosto de 2010. Arquivado do original em 8 de agosto de 2011
 «Usando Repo e o Git». Consultado em 31 de agosto de 2010. Arquivado do original em 6 de setembro de 2010
 BlueZ » Acessar o GIT
 «Btrfs source repositories - btrfs Wiki». Btrfs.wiki.kernel.org. Consultado em 15 de junho de 2009
 [1]
 [2]
 [3]
 git.debian.org Git
 digg.git - part 1 | Digg About
 TypicalGitUsage - dragonflywiki[ligação inativa]
 WTP Incubator using Git
 Download
 «Get FFmpeg». Ffmpeg.org. Consultado em 15 de junho de 2009
 [4]
 [5]
 «Git - Fast Version Control System». Consultado em 24 de abril de 2010
 The GIMP Development Team. «GIMP Developer Resources». Consultado em 7 de agosto de 2010
 Lucas Rocha. «Mailing List Announcement». Consultado em 19 de março de 2009. GNOME to migrate to git version control system…
 «Git - GNOME Live!». Consultado em 31 de agosto de 2010. Arquivado do original em 10 de abril de 2012
 [6]
 «gstreamer Wiki - GitDeveloperGuidelines». Consultado em 31 de agosto de 2010. Arquivado do original em 6 de fevereiro de 2013
 gthumb - GNOME Live!
 «GTK+ - Download». Consultado em 31 de agosto de 2010. Arquivado do original em 3 de julho de 2010
 source repositories
 Downloading jQuery - jQuery JavaScript Library
 «CCHIT's laika at master - GitHub». Consultado em 31 de agosto de 2010. Arquivado do original em 20 de abril de 2010
 LilyPond, music notation for everyone
 The Linux Mint Blog » Blog Archive » Mint to use Launchpad for translations, bugs, blueprints and github for code hosting and version control
 DistroWatch.com: Put the fun back into computing. Use Linux, BSD
 LMMS - Linux MultiMedia Studio
 «Maemo - Gitorious». Consultado em 31 de agosto de 2010. Arquivado do original em 8 de outubro de 2009
 «MeeGo - Gitorious». Consultado em 31 de agosto de 2010. Arquivado do original em 29 de janeiro de 2011
 «Ruby on Rails: Merb». Consultado em 31 de agosto de 2010. Arquivado do original em 30 de abril de 2010
 GitFAQ - Mono
 Mono Project - GitHub
 MooTools - a compact javascript framework
 OLPC wiki. «Project hosting». Consultado em 20 de fevereiro de 2008
 «Cópia arquivada». Consultado em 31 de agosto de 2010. Arquivado do original em 28 de janeiro de 2010
 «openSUSE - Gitorious». Consultado em 31 de agosto de 2010. Arquivado do original em 27 de maio de 2010
 «FrictionalGames' PenumbraOverture at master». GitHub
 «Penumbra: Overture goes Open Source!». Frictional Games
 Léon Brocard. «Mailing List Announcement». Consultado em 22 de dezembro de 2008. The Perl Foundation has migrated Perl 5 to the Git version control system…
 PHP (20 de março de 2012). «PHP migrates to Git». The PHP Group. Consultado em 23 de março de 2012
 phpBB (7 de março de 2010). «phpBB moves source code versioning from Subversion to Git». phpBB Group. Consultado em 7 de março de 2010
 Prototype JavaScript framework: Contribute
 «Qt now open for community contributions». 11 de maio de 2009. Consultado em 22 de junho de 2009
 «Reddit Goes Open Source». Consultado em 26 de fevereiro de 2010
 [7]
 [8]
 «"Rails is moving from SVN to Git"». Consultado em 3 de abril de 2008
 «Using Git for Samba Development - SambaWiki». Consultado em 31 de agosto de 2010. Arquivado do original em 15 de outubro de 2015
 «SproutCore Documentation». Consultado em 31 de agosto de 2010. Arquivado do original em 16 de julho de 2009
 [9]
 Sugar Labs project hosting
 Accessing SWI-Prolog source via <a href="http://git-scm.com/">GIT</a>
 Git - VideoLAN Wiki
 [10]
 GitWine - The Official Wine Wiki
 Xfce Git
 Xiph Git
 X.Org Wiki - Development/git
 «YUI 2 and YUI 3 Source Code Now on GitHub». Consultado em 20 de janeiro de 2009
 «Cópia arquivada». Consultado em 31 de agosto de 2010. Arquivado do original em 21 de setembro de 2010
 life at the end of the universe » we’re testing the water for everyone
 «KDE gets millionth commit - The H Open Source: News and Features». Consultado em 31 de agosto de 2010. Arquivado do original em 24 de julho de 2009
 (Kde-scm-interest) Minutes from Today's KDE ? Git BoF, Ian Monroe, Wed July 8 18:43:42 CEST 2009
 Migrating Drupal.org to Git