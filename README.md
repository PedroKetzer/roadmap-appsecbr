# Motivo da existência do repo:
Esse repositório foi criado com o intuito de ~espalhar a palavra do DevSecOps~ educar e direcionar aspirantes do mundo de segurança a um lugar que seja diferente da famosa escolha entre o azul (blue team) e o vermelho (red team), sendo esse lugar o mundo maravilhoso (e puxado) de Application Security, uma área relativamente nova, mas em constante expansão com suas peculiaridades únicas. Também isso é uma maneira que encontrei de retribuir o que a comunidade fez por mim, porque não cheguei onde estou sozinho e muitas pessoas me orientaram e direcionaram para que eu pudesse ser um pouco melhor a cada dia.

## Quem pode contribuir?
Qualquer profissional de AppSec é bem vindo(a) para contribuir e acrescentar insights!

## Por que e pra quem é AppSec?
Pode ser que você já tenha chegado com a resposta na sua cabeça, mas há quem possa estar indeciso: A área de AppSec (ao menos no Br na minha visão) engloba aqueles profissionais que não querem viver apenas do pentest. Claro, a ideia de Red Team é fantástica e atrai muita gente na área (provavelmente a série do Mr.Robot trouxe mais gente pra área do que qualquer profissional e curso existente), mas de certa forma é uma opinão bem frequente no meio de AppSec que é difícil encontrar empresas que levam o conceito de Red Team na letra, além disso, para aqueles que aprenderam programação ou até mesmo foram devs irão ter uma transição e irão utilizar esse conhecimento muito mais essa parte dentro de AppSec, isso não quer dizer que em outras áreas não precisa programar, **não é isso**, mas para quem gosta ou já se profissionalizou por meio de código e nutre interesse pela parte de segurança se sentirá muito mais em casa como AppSec do que em outras áreas (obviamente cada um terá uma experiência diferente sobre isso).

TL;DR - Se você não quer ser pentester e quer fazer pentests, já foi dev mas quer ser de segurança, AppSec é pra você :D

## Eu já posso começar direto por esse repo? 
Entende-se que se você chegou até esse repo, na maioria dos casos é porque você já sabe que AppSec é um nicho e você já sabe as bases de SegInfo, talvez com exceção da programação. Não sabe? Não tem certeza? Volte algumas casas e [estude os conteúdos de iniciante desse roadmap](https://meninadecybersec.notion.site/Iniciando-em-Cybersecurity-e-Seguran-a-da-Informa-o-cfe02d5ac2b74576b315083387894890), é essencial porque muitos conteúdos aqui só farão sentido se você tiver as bases já estabelecidas. Você também pode complementar com [esse repo aqui](https://github.com/arthurspk/guiadecybersecurity)

## Programação e Code Review
Acho que esse é o mais óbvio de todos, não existe Application Security (vulgo Segurança de Aplicações) sem a Aplicação xD. Quando se trata de  programação dentro do mundo de AppSec, a pessoa que está trabalhando com isso precisa ser agnóstica quando se trata de linguagem de programação, ao contrário do que muitas vezes ocorre no mundo Dev, não existe uma discussão de qual linguagem "melhor ou pior", simplesmente existe as linguagens que a sua empresa trabalha, se a pipeline da sua empresa for executada em Cobol, Erlang e Pascal você precisará ser capaz de fazer code review nessas linguagens e ponto final. ~Claro que isso é uma hipérbole pra deixar clara a expectativa que terão sobre você~, obviamente se você entrar no emprego como Jr ou até mesmo como Pleno em alguns casos, te permitirão ter uma curva de aprendizado, mas o foco aqui é que você pode até ter uma linguagem favorita, mas todas em que você tocar, você precisará se tornar capaz de executar um code review nelas.

Se tratando de escolher uma linguagem, primeiro tenha certeza que você sabe o básico (vulgo lógica de programação) e após isso, escolha uma linguagem, aprenda bem os conceitos de Orientação a Objetos e comece evoluir a partir daí, já ouvi de vários profissionais que não é necessário que você desenvolva uma aplicação de ponta a ponta, apenas que você entenda o código que você está revisando/testando, todavia, se você quiser chegar ao topo da carreira técnica, é necessário que você converse de igual pra igual com um dev nesse tópico.

## Conteúdos da OWASP
A partir de hoje, a OWASP é a tua melhor amiga. Por que eu digo isso? Muito do mundo do AppSec surgiu justamente por causa da OWASP, se você não sabe quem é a OWASP e também não usou o Google até aqui, confira [aqui](https://owasp.org/about/) quem são eles.
### OWASP Top 10
O maior projeto que você precisa acompanhar e que merece um tópico dedicado é o [Top 10](https://owasp.org/www-project-top-ten/). A OWASP Top 10 é uma coleção das 10 principais ameaças de seguranças de apps identificadas pela organização. Atualizada de tempos em tempos, consiste de 8 principais levantadas por meio de análise de dados, considerando "prevalência" ao invés de quantidade de testes, e duas orquestradas pela comunidade.

Além dessa extrema relevância, é de longe o tópico mais perguntado nas entrevistas, onde geralmente pedem o conceito de uma ou mais vulnerabilidades, como identificar ela no código, como ela pode ser explorada e qual seria a correção sugerida.

Após conhecer tanto a parte de programação, quanto os conceitos da OWASP Top 10, se você quiser um curso pago para poder revisar códigos inseguros em cenários tanto criados com fim de aprendizado quanto cenários que rolaram com CVEs, a maior recomendação seria o [Pentester Lab](https://pentesterlab.com/) que tem uma trilha excepcional nesse tópico em várias linguagens diferentes e permite um aprendizado enorme! (Vale seguir eles no twitter que frequentemente sorteiam vouchers de 1 ano de assinatura)

##### Nota: Não é só de Top 10 que vive a OWASP, tire tempo para explorar os outros frameworks deles e entender um pouco mais de cada um.

## Pentests e Ferramentas
Lembra que foi falado que o AppSec também faz pentest? Então, o mais comum nesse mundo é que pentests do tipo Web e/ou Mobile façam parte do dia-a-dia de alguém que trabalha com AppSec, então é essencial que você manje de vulnerabilidades voltadas para a Web (aqui que os pontos da programação e da Owasp começam a se juntar), já que na maioria dos testes que você fará, você terá acesso ao código, independente de ser um alerta de SAST que você irá avaliar ou se de fato for um pentest do tipo white-box.

Dito isso, a ferramenta que será mais usadas, será o [BurpSuite](https://portswigger.net/burp), assim como uma panela tem a sua tampa, o analista de AppSec tem o Burpsuite xD

Piadas a parte ela será de uso quase diário, além de ser altamente recomendado fazer o [curso gratuito oferecido por eles](https://portswigger.net/web-security) e **opcionalmente** tirar a cert deles se tu tiver um troquinho sobrando aí (hoje gira mais ou menos em torno de 100 dólares)

Alternativamente, se você tiver uma graninha sobrando também, pode ser interessante adquirir o curso [Web Hacking na Prática](https://app.hackingclub.com)

### Mobile (Opcional)
Também merece uma subseção dedicada justamente por ser um opcional quando se está por migrar ou em início de carreira, mas certamente será um diferencial gigantesco! Um conselho caso você opte por ele, é optar Java como a sua linguagem de preferência, o que já reduz muito a dificuldade em aprender sobre essa parte, em adendo, como mais um **opcional** a [certificação da Sec4Us de Mobile](https://sec4us.com.br/certificacao/scmpa-sec4us-certified-mobile-pentester-android/) e a [eMAPT](https://security.ine.com/certifications/emapt-certification/) são legais de ter nesse quesito.

## Soft Skills
Parece meio óbvio, você pode se achar "bom de conversa" e todos os seus amigos gostam de você, porém, todavia, contundo, entretanto, soft skills são muito importantes para alguém de AppSec mas **muito** mesmo, quase mais do que as hard skills! Isso é dito porque faz parte do cotidiano conversar com devs que estão nos mais variáveis níveis de carreira, desde o estagiário até o expert conhecido na bolha dev e nessas horas não basta fazer como fazem em muitas consultorias ao dizer: "esse código tá ruim, corrige aí". É esperado que alguém de AppSec se torne uma referência, tenha jogo de cintura, seja maleável (a vida não é binária né?) e saber conversar e explicar coisas pra pessoas que nem sempre estão propensas a concordar contigo.

"Ah, mas vulnerabilidade é vulnerabilidade", pode até ser, até você precisar explicar porque carambolas um SSRF que só pode ser executado em ambiente local ou em algum contexto muito improvável precisa ser corrigido, e nessas horas que são as soft skills que provalecem, afinal coisas assim tomam tempo da sprint do dev e os devs obviamente tem outras coisas que precisam entregar também.

## DevSecOps, SAST e DAST
Esse aqui vai ser um pouco mais enxuto, porque não se espera que um Jr implemente tais coisas, mas é super importante que esses exista familirialidade com esses conceitos, até porque podem ser perguntandos em entrevistas.

#### [DevSecOps](https://devsecopsguides.com/)
![image](https://github.com/PedroKetzer/roadmap-appsecbr/assets/37319386/e0ab5cfa-05c7-4fb2-a148-545bd6f9b994)

Você sabe a esteira de DevOps? Então, ao incorporar a segurança dentro do que chamam de ciclo de vida de desenvolvimento de software (SDLC), temos a cultura de DevSecOps, existem diversas maneiras de executar esse processo, mas aqui vamos citar dois pontos importantes dela, SAST e DAST.

##### SAST
Static Application Security Testing (SAST) nada mais é que a sigla em inglês para Análise Estática de código. De forma resumida nada mais é que uma ferramenta que analisa o código fonte de um repositório (e isso pode se expandir para binários também) em buscas de padrões inseguros, padrões esses que são definidos por meio de regras (que podem ser tanto padrões da ferramenta quanto customizadas pela empresa que adquiriu/contratou a ferramenta), o exemplo mais fácil de você procurar por aí é por "secret keys".

##### DAST
Recomendaria ler [esse artigo](https://www.convisoappsec.com/glossario/dast)

###### Nota: Uma ótima fonte para esses conceitos, é o [livro do Cássio Developer](https://cassiodeveloper.com.br/livro/)

## Conteúdos extras e criadores legais de seguir:
- [Ben-Hur](https://twitter.com/guiadeappsec) do [Guia de AppSec](https://www.guiadeappsec.com.br/), ele também tem um [canal no youtube](https://www.youtube.com/@GuiadeAppSec) com dicas
- [Cássio Developer](https://cassiodeveloper.com.br/) do [DevSecOps PodCast](https://www.youtube.com/@CassioBatistaPereira)
- [Carlos "CrowSec"](https://www.instagram.com/carlos.crowsec/), que além do [Web Hacking na Prática](https://app.hackingclub.com) tem um canal no Youtube com o [mesmo nome](https://www.youtube.com/@CarlosVieiraCrowSec)
- [Daiane "wh0isdxk" Santos](https://www.instagram.com/wh0isdxk/) do [MobileHackingBr](https://www.instagram.com/mobilehackingbr/)
- [Edu Santos](https://www.instagram.com/edusantos.official/) do canal [WarmSec](https://www.youtube.com/@edusantos.official)

#### Seção final e considerações
Com isso, você já deve estar bem munido(a) para começar a sua carreira e tentar a sorte nas vagas, não se iluda que é um caminho fácil e que acaba somente com os conteúdos que eu te passei, **não é**, tem muito mais conteúdo que você precisará mas te digo que é uma jornada recompensadora, desde o dia 1 (:

Qualquer coisa, sinta-se livre pra mandar uma mensagem para tirar dúvidas e tudo mais e te desejo todo o sucesso do mundo na sua jornada o/
