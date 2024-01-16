##### 💡 Todas as sugestões de curso/conteúdo a seguir são gratuitas, exceto as marcadas com 💰

# Modelagem de Ameaças
A modelagem de ameaças no contexto do Application Security é essencial para antecipar e abordar potenciais vulnerabilidades nos sistemas. Ao identificar ameaças antes que se tornem ataques reais, os profissionais de segurança podem desenvolver estratégias preventivas, fortalecendo a segurança das aplicações. Essa abordagem proativa não apenas melhora a resiliência dos sistemas, mas também promove uma cultura de segurança desde as fases iniciais do desenvolvimento de aplicativos. 
Para aprender sobre modelagem, veja:
- [Modelagem de Ameaças - Conviso](https://www.youtube.com/watch?v=UWDqnhJsafY)
- [Modelando ameaças na prática - Cássio Batista](https://www.youtube.com/watch?v=ZiFw84hv5SQ)
- [Workshop Modelagem de Ameaças - Edu Santos e Rafael Lachi](https://www.youtube.com/watch?v=wt-Nzz_waXk)
- [OWASP Threat Modeling Process](https://owasp.org/www-community/Threat_Modeling_Process)
- [OWASP Threat Dragon](https://owasp.org/www-project-threat-dragon/)
- [IriusRisk DeRisker Training Program](https://www.iriusrisk.com/derisker-training-and-certification)
- [Threat Modeling Security Fundamentals - Microsoft](https://learn.microsoft.com/en-us/training/paths/tm-threat-modeling-fundamentals/)

# Os primeiros passos sobre a modelagem

A modelagem de ameaças é um processo utilizado na área de segurança da informação para identificar e entender potenciais ameaças e vulnerabilidades que um sistema, aplicativo ou projeto. Abstrato eu diria, não é mesmo? Entenda que além de segurança deve ser capaz de falar sobre o negócio assim como suas peculiaridades, desde o que um caminho feliz de usuário esperado até as possíveis tentativas de explorações, cenários maliciosos, tudo que será ofensor para sua atuação.

## Olhando o todo

Ao falarmos de Shift Left, é muito bonita a ideia de antecipar problemas, reduzir custo e valores empregados no conceito, mas como? 
Vamos partir do presuposto que você sabe e conhece sobre arquitetura de sistema, Api REST, afins. Caso não saiba, vou colocar alguns links de apoio. 

Primeiramente é importante entender em um "papel de pão" a construção de um sistema, quem se comunica com o que? Como? Para que? Então estipulei um roteiro de perguntas básicas para que internalize sobre o contexto e seja capaz de a partir delas criar várias e várias outras sobre o produto.

1. Poderia me informar um resumo da finalidade da aplicação?
2. Será exposto na internet ou somente interno?
3. Quem consumirá a aplicação? Serviços internos, Usuários comuns, Usuários internos? 
4. Qual tipo de dado está em trânsito? Dados de cartão? Informações pessoais? Informação de sistema? Transações?
5. Haverá o armazenamento de dados? Onde?

A partir desses pontos você consegue visualizar e até rascunhar uma arquitetura de dutos e filtros onde será possível tanto estruturar quem ou o quê realiza a ação e qual ação para uma finalidade específica. Complexo? Vamos destrinchar um exemplo básico.


## Sobre a Aplicação

1. **Finalidade da Aplicação**
   - A aplicação permite que terceiros de outras empresas registrem informações de atendimento a clientes por um site, durante atendimentos em campo. Isso ajuda a verificar se os atendimentos estão sendo resolvidos no local ou se há reincidências.

2. **Acesso e Exposição**
   - A aplicação estará disponível na internet para terceiros, porém, nossa equipe terá acesso para monitoramento.

3. **Consumidores da Aplicação**
   - Os principais consumidores serão usuários terceiros de uma empresa contratada (Empresa X) e usuários internos da nossa organização.

4. **Dados em Trânsito e Armazenamento**
   - Os dados transitados incluem informações pessoais de clientes (nome, telefone, endereço do atendimento, resumo do problema e resolução), além de dados dos técnicos responsáveis. Todos serão armazenados em nosso banco de dados na nuvem.

5. **Serviços Disponíveis**
   - Teremos um BFF (Backend For Frontend) e um microsserviço. O BFF receberá informações, enquanto o microsserviço será responsável por publicá-las no banco de dados.

## Arquitetura de dutos e filtros

Se baseando somente no que é comentado temos:

![Desenho da Arquiteutra de Rascunho](https://github.com/PedroKetzer/roadmap-appsecbr/assets/37319386/6d91a609-1b47-4c96-aa51-c274bfabfb3c)


## Levantamento de problemas

A partir desse início você conseguiria visualizar alguns problemas, como por exemplo:
Como que vai ser realizada a exposição desse BFF?
Como vai ser a governança desses usuários se a gente vai ter pessoas internas e externas? Quem ou o que vai criar usuários?
Esse serviço vai registrar informações em um banco de dados, são dados pessoais, então como é a LGPD sobre isso? Por quanto tempo vão guardar essa informação? O cliente autorizou?!
Como vai ser feita a publicação desse atendimento? Vão ter que correlacionar a uma origem de chamado? 
Eles vão mandar arquivo ou vai ser um formulário? 
Se querem vincular as reincidências, haverá o consumo da informação no banco de dados, por quem? 
Se só o atendente vai interagir no site por que usuários internos precisam acessar?

Inúmeras dúvidas surgem e podem ser resolvidas posteriormente, mas e se o time precisa de um direcionamento mínimo para entender o que podem ou não realizar? Ou se ainda não há nada pronto, porque no modelo de Shift Left tem uma antecipação que problemas então deve ser capaz de levantar pontos antecedendo a conclusão até de um desenho de arquitetura, ou não necessariamente?

Depende.
Depende do tamanho da empresa, do tamanho do time, da maturidade do time sobre a própria empresa e como funciona, enfim, muitas variáveis. Por isso o AppSec (ou outro nome que a empresa possa endereçar essa atividade) precisa compreender muito bem do negócio, do ecossistema corporativo e suas peculiaridades, assim como arquitetura e ferramentas disponíveis para sua atuação.

## Levantando ameaças

Ameaças poderíamos, em uma visão superficial, reduzir a 3 tipos de possibilidades, tais como:

![Ameaças da Arquiteutra de Rascunho](https://github.com/PedroKetzer/roadmap-appsecbr/assets/37319386/f5a94642-995c-4e17-8484-93f06ede0284)



--
Próximo: [Próximos passos em construção e serão linkados aqui]
