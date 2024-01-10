# Motivo da existência do repo:
Esse repositório foi criado com o intuito de ~espalhar a palavra do DevSecOps~ educar e direcionar aspirantes do mundo de segurança a um lugar que seja diferente da famosa escolha entre o azul (blue team) e o vermelho (red team), sendo esse lugar o mundo maravilhoso (e puxado) de Application Security: uma área relativamente nova, mas em constante expansão, com suas peculiaridades únicas. Também é uma maneira que encontrei de retribuir o que a comunidade fez por mim, porque não cheguei onde estou sozinho e muitas pessoas me orientaram e direcionaram para que eu pudesse ser um pouco melhor a cada dia.

## Quem pode contribuir?
Qualquer profissional de AppSec é bem vindo(a) para contribuir e acrescentar insights!

## Por que e pra quem é AppSec?
Pode ser que você já tenha chegado com a resposta na sua cabeça, mas há quem possa estar indeciso: A área de AppSec (ao menos no BR, na minha visão) engloba aqueles profissionais que não querem viver apenas do pentest. Claro, a ideia de Red Team é fantástica e atrai muita gente na área (provavelmente a série do Mr.Robot trouxe mais gente pra área do que qualquer profissional e curso existente), mas de certa forma é uma opinão bem frequente no meio de AppSec que é difícil encontrar empresas que levam o conceito de Red Team ao pé da letra. Além disso, para aqueles que aprenderam programação ou até mesmo foram devs, terão uma transição e utilizarão esse conhecimento muito mais dentro de AppSec. Isso não quer dizer que em outras áreas não precisam programar, **não é isso**, mas quem gosta ou já se profissionalizou por meio de código e nutre interesse pela parte de segurança, se sentirá em casa como AppSec (obviamente, cada um terá uma experiência diferente sobre isso).

TL;DR - Se você não quer ser Red Team e quer fazer pentests, já foi dev mas quer ser de segurança, AppSec é pra você! Em muitas empresas, AppSecs também fazem pentest :D

## Eu já posso começar direto por esse repo? 
Entende-se que, se você chegou até esse repo, na maioria dos casos é porque você já sabe que AppSec é um nicho e você já sabe as bases de SegInfo, talvez com exceção da programação. Não sabe? Não tem certeza? Volte algumas casas e [estude os conteúdos de iniciante desse roadmap](https://meninadecybersec.notion.site/Iniciando-em-Cybersecurity-e-Seguran-a-da-Informa-o-cfe02d5ac2b74576b315083387894890). É essencial porque muitos conteúdos aqui só farão sentido se você tiver as bases já estabelecidas. Você também pode complementar com [esse repo aqui](https://github.com/arthurspk/guiadecybersecurity)

# Skills, Ferramentas e o que estudar 

##### 💡 Todas as sugestões de curso/conteúdo a seguir são gratuitas, exceto as marcadas com 💰

## Programação e Code Review
Acho que esse é o mais óbvio de todos: não existe Application Security (vulgo Segurança de Aplicações) sem a Aplicação xD. Quando se trata de programação dentro do mundo de AppSec, a pessoa que trabalha com isso precisa ser agnóstica quando se trata de linguagem de programação. Ao contrário do que muitas vezes ocorre no mundo Dev, não existe uma discussão de qual linguagem é "melhor ou pior": simplesmente existem as linguagens com que a sua empresa trabalha. Se a stack da sua empresa envolver Cobol, Erlang e Pascal, você precisará ser capaz de fazer code review nessas linguagens e ponto final. ~Claro que isso é uma hipérbole pra deixar clara a expectativa que terão sobre você~. Obviamente, se você entrar no emprego como Jr/Sandy ou até mesmo como Pleno, em alguns casos, te permitirão ter uma curva de aprendizado. Mas, o foco aqui é que você pode até ter uma linguagem favorita, mas, todas em que você tocar, você precisará se tornar capaz de executar um code review.

Tratando-se de escolher uma linguagem inicial, considere escolher uma linguagem backend de alto nível para facilitar seu primeiro contato. Esqueça frameworks e abstrações no início. Durante a sua evolução profissional como AppSec, você perceberá a necessidade de aprender ṕelo menos uma linguagem de cada um dos principais paradigmas do mercado (imperativo, orientado a objetos, funcional e orientado a eventos). Entendendo "lógica de programação" como uma forma de pensar e resolver problemas, "paradigmas" são diferentes formas de encadeamento lógico para chegar a uma solução (te tapearam quando te disseram que só existia uma forma de lógica de programação, viu? ;-) ). Se você quiser chegar ao topo da carreira técnica, é necessário que você converse de igual pra igual com um dev nesse tópico!

Alguns links para te apoiar nesse tema:
- [Curso Python - Gustavo Guanabara](https://www.youtube.com/watch?v=S9uPNppGsGo&list=PLHz_AreHm4dlKP6QQCekuIPky1CiwmdI6&index=1)
- [Paradigmas de Programação - João Paulo Leite](https://www.youtube.com/playlist?list=PLsri1g4fxrjuf6UCYHqCmqsfXR4gofAFH)
- [How to Analyze Code for Vulnerabilities - Vickie Li (en)](https://www.youtube.com/watch?v=A8CNysN-lOM)
- [In Code Review We Trust! Finding Security Bugs (pt-br) - Helena Carreço](https://www.youtube.com/watch?v=gewNYKjYybA&t=5586s)
- [OWASP Code Review Guide](https://owasp.org/www-project-code-review-guide/)
- 💰 [PentesterLab](https://pentesterlab.com/)
- 💰 [CodeBashing](https://www.codebashing.com/)

##### 💡 Vale seguir a PentesteLab no Twitter, pois frequentemente sorteiam vouchers de 1 ano de assinatura.

## Modelagem de Ameaças
A modelagem de ameaças no contexto do Application Security é essencial para antecipar e abordar potenciais vulnerabilidades nos sistemas. Ao identificar ameaças antes que se tornem ataques reais, os profissionais de segurança podem desenvolver estratégias preventivas, fortalecendo a segurança das aplicações. Essa abordagem proativa não apenas melhora a resiliência dos sistemas, mas também promove uma cultura de segurança desde as fases iniciais do desenvolvimento de aplicativos. 
Para aprender sobre modelagem, veja:
- [Modelagem de Ameaças - Conviso](https://www.youtube.com/watch?v=UWDqnhJsafY)
- [Modelando ameaças na prática - Cássio Batista](https://www.youtube.com/watch?v=ZiFw84hv5SQ)
- [Workshop Modelagem de Ameaças - Edu Santos e Rafael Lachi](https://www.youtube.com/watch?v=wt-Nzz_waXk)
- [OWASP Threat Modeling Process](https://owasp.org/www-community/Threat_Modeling_Process)
- [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)
- [IriusRisk DeRisker Training Program](https://www.iriusrisk.com/derisker-training-and-certification)
- [Threat Modeling Security Fundamentals - Microsoft](https://learn.microsoft.com/en-us/training/paths/tm-threat-modeling-fundamentals/)

## DevOps e Automações de Esteira
Saber DevOps e automação de esteira em Application Security é crucial para garantir a integridade e segurança de aplicações. A integração contínua e entrega contínua (CI/CD) proporcionadas pelo DevOps permitem atualizações frequentes, enquanto a automação da esteira de segurança identifica e corrige vulnerabilidades de forma eficiente. Isso reduz o tempo de resposta a ameaças, fortalecendo a postura de segurança da aplicação. É comum que o time de AppSec Seja responsável por subir e manter ferramentas e automações de segurança. Então, essa skill é primordial.
Aprenda sobre como automatizar seu processo em:
- [Implementing Secure CI/CD Pipelines (en)](https://www.youtube.com/playlist?list=PLjNII-Jkdjfz5EXWlGMBRk63PC8uJsHMo)
- [DevSecOps Guides (en)](https://devsecopsguides.com/)

A seguir, algumas ferramentas que podem te apoiar. Ao escolher ferramentas de revisão de código, certifique-se de que elas tem suporte para sua linguagem/stack:

### SAST
- [Source Code Analysis Tools - OWASP (en)](https://owasp.org/www-community/Source_Code_Analysis_Tools)

### DAST
- [Dynamic Application Security Testing - OWASP (en)](https://owasp.org/www-project-devsecops-guideline/latest/02b-Dynamic-Application-Security-Testing)

### SCA
- [Component Analysis (en)](https://owasp.org/www-community/Component_Analysis)

### IAST
- [Interactive Application Security Testing - OWASP (en)](https://owasp.org/www-project-devsecops-guideline/latest/02c-Interactive-Application-Security-Testing)

### Secret Scanning
- [Secrets Management - OWASP (en)](https://owasp.org/www-project-devsecops-guideline/latest/01a-Secrets-Management)

### IaC security scanning
- [Container Vulnerability Scanning (en)](https://owasp.org/www-project-devsecops-guideline/latest/02f-Container-Vulnerability-Scanning)


## DevSecOps
Embora muitas empresas usem DevOps e DevSecOps para nomear cargos, esses são processos que vão muito além das ferramentas de automação: passam por treinamento das pessoas, evolução da cultura e maturidade de segurança da empresa e todas as ações que aproximam a Segurança de Aplicações do famoso shift-left.
Pensando em processos, maturidade e treinamentos, podem te auxiliar:
- [Security Champions Playbook (pt-br)](https://github.com/c0rdis/security-champions-playbook/tree/master/Security%20Playbook_PTBR)
- [OWASP SAMM (en)](https://owaspsamm.org))
- [Security Champions: Elevando a Maturidade de Segurança - Helena Carreço "Molocohorror"](https://www.youtube.com/watch?v=tJ7kqOtyuxQ&t=8131s)


## OWASP
A partir de hoje, a OWASP é a sua melhor amiga. Se você não sabe quem é a OWASP e também não usou o Google até aqui, confira [aqui](https://owasp.org/about/). A seguir, alguns dos principais projetos da OWASP. Observe que a OWASP tem [mais de 300 projetos](https://owasp.org/projects/), e essa lista foi construída com base em experiência, podendo variar de empresa pra empresa. 

### OWASP Top 10
O maior projeto que você precisa acompanhar é o [Top 10](https://owasp.org/www-project-top-ten/). A OWASP Top 10 é uma coleção das 10 principais ameaças de seguranças identificadas pela organização. Atualizada de tempos em tempos, consiste de oito principais levantadas por meio de análise de dados, considerando "prevalência" ao invés de quantidade de testes, e duas orquestradas pela comunidade. Observe que, quando falamos de "Top 10 OWASP", geralmente nos referimos ao Top 10 de vulnerabilidades WEB. No entanto, a OWASP disponibiliza um Top 10 Mobile, API, LLM, entre outros. É muito importante identificar o que faz mais sentido no contexto da sua empresa!

#### 💡 Além dessa extrema relevância, o Top 10 é de longe o tópico mais perguntado nas entrevistas para a senioridade júnior/sandy: geralmente pedem o conceito de uma ou mais vulnerabilidades, como identificar ela no código, como ela pode ser explorada e qual seria a correção sugerida! 

### ASVS/MASVS
O ASVS (Application Security Verification Standard) é um conjunto de requisitos e controles de segurança usado para avaliar e verificar a segurança de aplicações. Ele fornece uma estrutura detalhada para garantir que as aplicações estejam protegidas contra ameaças comuns. Já o MASVS (Mobile Application Security Verification Standard), é uma extensão do ASVS especificamente projetada para avaliar a segurança de aplicativos móveis. Ele estabelece diretrizes e requisitos específicos para garantir a robustez da segurança em plataformas móveis, abordando ameaças únicas associadas a aplicativos para dispositivos móveis. Esses dois projetos, são instrumentos valiosos para desenvolvedores e AppSecs, apoiando como checklists para levantamento de requisitos de segurança e apoio na Modelagem de Ameaças:
- [ASVS - Application Security Verification Standard](https://owasp.org/www-project-application-security-verification-standard/#)
- [MASVS - Mobile Application Security Verification Standard ](https://github.com/OWASP/owasp-masvs/releases/latest/download/OWASP_MASVS.pdf)

### Cheatsheets
O OWASP Cheatsheets é um recurso que consiste em documentos de referência rápida contendo orientações práticas e conselhos para abordar desafios específicos de segurança em desenvolvimento de software. Esses cheatsheets são projetados para auxiliar a implementar boas práticas de segurança durante o ciclo de vida do desenvolvimento de software e abrangem uma variedade de tópicos, desde codificação segura até mitigação de ameaças específicas, fornecendo informações detalhadas e acionáveis para melhorar a segurança de aplicações. Esse projeto costuma ser uma mão na roda ao lidar com desenvolvedores com menos experiência em segurança, com traz exemplos de código em linguagens específicas, com soluções práticas que elespodem reutilizar.
- [OWASP CheatsheetSeries](https://cheatsheetseries.owasp.org/index.html)

  
## Pentests e Ferramentas
Sendo uma área relativamente nova, as responsabilidades do profissional de AppSec podem variar entre as empresas (conheça mais sobre as diferentes formas de fazer AppSec [nessa palestra da Gi Assis "gihyperia"](https://www.youtube.com/watch?v=UCmX5mo0b1U&list=PLUJRxfaTTjKwjkyLiWtxPh5gADtbG5Oo1&index=3&t=527s)). Dito isso, em muitas empresas será comum que a atividade de pentest também seja uma atividade de AppSec. Então, é essencial que você manje de descoberta de vulnerabilidades, como complemento aos seus conhecimentos em code review e uso de ferramentas de análise de código. Nessa frente, a ferramenta que mais usada, será o 💰 [BurpSuite](https://portswigger.net/burp). É altamente recomendado fazer o [curso gratuito oferecido por eles](https://portswigger.net/web-security) e **opcionalmente** tirar a cert deles, se tu tiver um troquinho sobrando aí (hoje gira mais ou menos em torno de 100 dólares).

Outros cursos que podem te ajudar a desenvolver conhecimentos em descoberta de vulnerabilidades e também tem prova de certificação:
- 💰 [Web Hacking na Prática](https://app.hackingclub.com)
- 💰 [Pentest DESEC](https://desecsecurity.com/curso/novo-pentest-profissional)


## Mobile
Embora seja opcional quando se está por migrar ou em início de carreira, a avaliação de riscos em mobile se torna um diferencial gigantesco a medida que você evoluir!  Alguns recursos quepodem te ajudar a evoluir nesse item são:
- [Android Application Security Series](https://manifestsecurity.com/android-application-security/)
- [Android Applications Reversing 101](https://www.evilsocket.net/2017/04/27/Android-Applications-Reversing-101/#.WQND0G3TTOM.reddit)
- [Engenharia Reversa de Apps Android](https://www.youtube.com/watch?v=eHdDS2e_qf0&list=PL4zZ9lJ-RCbfv6f6Jc8cJ4ljKqENkTfi7)
- 💰 [Android Hacker's Handbook](https://www.amazon.com/Android-Hackers-Handbook-Joshua-Drake/dp/111860864X)
- 💰 [eMAPT](https://security.ine.com/certifications/emapt-certification/)

#### 💰  Optar Java como a sua principal linguagem reduzirá muito a dificuldade em aprender sobre essa parte

## Soft Skills
Soft Skills e comunicação assertiva são muito importantes para alguém de AppSec, mas **muito** mesmo, quase mais do que as hard skills! Isso é dito porque faz parte do cotidiano conversar com devs que estão nos mais variados níveis de carreira, desde o estagiário até o expert conhecido na bolha dev. Nessas horas não basta dizer: "esse código tá ruim, corrige aí". É esperado que alguém de AppSec se torne uma referência, tenha jogo de cintura, seja maleável (a vida não é binária né?) e saber conversar e explicar coisas pra pessoas que nem sempre estão propensas a concordar contigo, além de normalmente não terem background de segurança.

"Ah, mas vulnerabilidade é vulnerabilidade"! Sim, até você precisar explicar porquê uma vulnerabilidade que só pode ser executada em ambiente restrito é crítica e precisa ter sua correção priorizada frente a um backlog apertado, com datas de lançamento vencidas. Nessas horas são as soft skills que provalecem: correções tomam tempo da sprint do dev e com outras coisas que eles precisam entregar. Agir com empatia junto ao dev, aprender a demonstrar para pessoas não-técnicas como um risco pode se tornar perda financeira e lembrar que **segurança não aceita risco, mas apresenta com clareza a probabilidade de exploração** vão te ajudar a ter sucesso nessa frente.

Soft Skills também podem ser desenvolvidas. Considere os seguintes conteúdos:
- [Soft skills: o que são, 10 principais exemplos e como desenvolver](https://www.gupy.io/blog/soft-skills)
- 💰 [Soft skills: competências essenciais para os novos tempos - Lucedile Antunes ](https://www.amazon.com.br/Soft-skills-compet%C3%AAncias-essenciais-tempos-ebook/dp/B08KWDD7N7)
- [3 dicas para ter Comunicação Assertiva no trabalho - Bianca Celoto](https://www.youtube.com/watch?v=rqE_mxXlZik)


# Conteúdos extras e criadores legais de seguir:
- [Ben-Hur](https://twitter.com/guiadeappsec) do [Guia de AppSec](https://www.guiadeappsec.com.br/), ele também tem um [canal no youtube](https://www.youtube.com/@GuiadeAppSec) com dicas
- [Cássio Developer](https://cassiodeveloper.com.br/) do [DevSecOps PodCast](https://www.youtube.com/@CassioBatistaPereira)
- [Carlos "CrowSec"](https://www.instagram.com/carlos.crowsec/), que além do [Web Hacking na Prática](https://app.hackingclub.com) tem um canal no Youtube com o [mesmo nome](https://www.youtube.com/@CarlosVieiraCrowSec)
- [Daiane "wh0isdxk" Santos](https://www.instagram.com/wh0isdxk/) do [MobileHackingBr](https://www.instagram.com/mobilehackingbr/)
- [Edu Santos](https://www.instagram.com/edusantos.official/) do canal [WarmSec](https://www.youtube.com/@edusantos.official)

# Seção final e considerações
Com isso, você já deve estar bem munido(a) para começar a sua carreira e tentar a sorte nas vagas! Não se iluda que é um caminho fácil e que acaba somente com os conteúdos recomendados aqui. **Não é**, tem muito mais conteúdo que você precisará. Mas, é uma jornada recompensadora, desde o dia 1 (:

Qualquer coisa, sinta-se livre pra mandar uma mensagem para tirar dúvidas. Te desejo todo o sucesso do mundo na sua jornada o/
