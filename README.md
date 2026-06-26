# Relatório de Atividades – Práticas Extensionistas na Educação em Computação

**Estudante:** Gabriel Souza Baggio

---

# RELATÓRIO SEMANAL

Nesta seção, são relatadas minhas experiências semanais ao longo da disciplina.

---

## 1ª Semana (02/03/2026 - 06/03/2026)

### Acolhida e apresentação da proposta pedagógica

A primeira semana foi marcada pela apresentação geral da disciplina e introdução dos **Fundamentos da Extensão e Contextualização**, momento em que foram explicitados os objetivos, a metodologia e o papel da extensão dentro do currículo do curso.

Um dos pontos centrais dessa introdução foi a discussão sobre os **5 Is**, conceitos que orientam a construção de ações extensionistas de qualidade:

- **Interação dialógica**: reconhecimento da importância da escuta ativa e da construção conjunta de soluções entre universidade e comunidade.
- **Impacto social**: compromisso com a geração de benefícios efetivos para a sociedade a partir das atividades realizadas.
- **Impacto na formação**: compreensão de que a extensão contribui para a formação integral do estudante, ampliando sua percepção sobre realidades sociais.
- **Interdisciplinaridade**: necessidade de integrar diferentes campos do conhecimento para abordar problemas complexos de forma mais adequada.
- **Indissociabilidade**: entendimento de que ensino, pesquisa e extensão devem caminhar de forma articulada dentro da universidade.

Essa primeira semana teve um papel fundamental para situar o estudante diante dos princípios que norteiam as práticas extensionistas, evidenciando que a atuação profissional em Computação pode, e deve, dialogar com questões sociais.

### Atividade de pesquisa: Incubadora Social da UFSM

Como parte dos estudos iniciais, foi realizada uma pesquisa sobre a **Incubadora Social da UFSM**, com o objetivo de conhecer sua trajetória, seu funcionamento e seu papel no suporte a empreendimentos de caráter social.

A Incubadora Social atua no auxílio a grupos e iniciativas que muitas vezes se encontram em situação de vulnerabilidade econômica, oferecendo orientação em gestão, planejamento e formalização. O trabalho desenvolvido pela incubadora contribui para que pequenos negócios e cooperativas possam se estruturar, ampliando sua autonomia e sua capacidade de geração de renda.

Essa pesquisa foi importante para começar a reconhecer como a universidade, por meio de programas como esse, já atua em diálogo com a comunidade. Além disso, permitiu levantar questões sobre como a Computação poderia contribuir com esses processos, especialmente no que diz respeito à visibilidade digital, à organização de informações e à comunicação com o público.

---

## 2ª Semana (09/03/2026 - 13/03/2026)

### Visita ao Hub Incubadora Social

Uma das atividades centrais desta semana foi a visita ao **Hub Incubadora Social**, espaço que materializa as ações de apoio aos empreendimentos atendidos pelo programa. O objetivo da visita foi conhecer a estrutura, conversar com os envolvidos e identificar possíveis demandas que pudessem ser endereçadas por soluções computacionais.

A partir do contato com a equipe e da observação do contexto, foi possível identificar uma necessidade concreta: a criação de um site para divulgação dos catálogos de produtos dos empreendimentos incubados. Essa demanda aponta para uma possível atuação da Computação no sentido de ampliar a visibilidade dos negócios, facilitar o acesso de clientes às informações e fortalecer a presença digital dos grupos atendidos.

---

## 3ª Semana (16/03/2026 - 20/03/2026)

### Reunião de alinhamento com a equipe

Nesta semana, realizamos encontros com o objetivo de discutir e sistematizar os requisitos do projeto, considerando as necessidades apresentadas pelos representantes da Incubadora Social, que atuam como nossos "clientes" e parceiros na construção da solução. Ao longo da discussão, destacou-se que o sistema deve ser intuitivo e de fácil utilização, a fim de permitir que pessoas com pouca experiência tecnológica consigam utilizá-lo.

Durante a reunião, foram levantadas e registradas as principais funcionalidades que o sistema deverá contemplar. A seguir, estão elencados alguns dos requisitos funcionais debatidos:

- Plataforma de catálogo virtual
- Gerador de catálogos em formato PDF e outros tipos (posts, etc.)
- Autenticação baseada em perfis (*role-based*)
- Perfil de cada empresa: contatos e links; itens com fotos e indicação de preços (valor, faixa ou opcional)
- Medidor de métricas, captura de dados e *analytics*
- Página inicial com cards destacados de cada empreendimento
- Categorização das empresas e itens
- Modos temáticos do website (datas comemorativas)

Por fim, definimos algumas metas de entrega para a semana seguinte:

- Coletar mais conteúdo sobre os negócios incubados e seus produtos
- Gerar propostas de *front-end* com Figma (com prioridade para o que ficará visível ao público: galeria de empreendimentos, vitrine por empreendimento e produtos por empreendimento)

---

## 4ª Semana (23/03/2026 - 27/03/2026)

### Desenvolvimento dos protótipos no Figma

Desenvolvemos os protótipos do projeto no Figma, sendo apresentadas duas propostas distintas de interface. Com isso, avaliamos os aspectos positivos e negativos de cada abordagem para criar uma versão final que combinasse o melhor de cada uma. Eu elaborei um protótipo e fui responsável por realizar o *merge* final entre as duas abordagens, preparando tudo para a apresentação da semana seguinte.

---

## 5ª Semana (30/03/2026 - 03/04/2026)

### Apresentação do protótipo visual para a equipe do Hub IS

A professora organizou uma visita à Incubadora Social, em sua sede no Hub de Integração Social (Hub IS). Apresentamos o protótipo final desenvolvido no Figma e, durante a apresentação, coletamos novos requisitos que poderiam aprimorar o modelo proposto. De modo geral, o protótipo foi bem recebido pelos participantes, que demonstraram satisfação com a proposta apresentada.

---

## 6ª Semana (06/04/2026 - 10/04/2026)

### Divisão do trabalho de desenvolvimento e início da iteração final

Na primeira aula, realizamos uma reunião para analisar as capacidades e aptidões de cada integrante do grupo. Fiquei responsável pela especificação da API (comunicação entre *front-end* e *back-end*) e pela especificação do banco de dados. Como tarefa para a aula seguinte, realizei toda a especificação de tabelas e colunas do banco de dados, em formato MySQL.

---

## 7ª Semana (13/04/2026 - 17/04/2026)

### Desenvolvimento da versão inicial, com *deploy* de *frontend* e *backend*

Na aula de quarta-feira, fizemos uma reunião na sala 127 do térreo do CT, em que discutimos os rumos futuros com base nas definições de *backend* propostas. A aula de sexta-feira foi reservada para desenvolvimento. As equipes de *back-end* e *front-end* ficaram responsáveis por desenvolver, nesse período, o *deploy* já funcional da primeira versão do sistema. Nessa semana, foi criado o repositório oficial da plataforma do Hub IS (https://github.com/hubisct).

---

## 8ª Semana (20/04/2026 - 24/04/2026)

### Apresentação do site funcional e análise de ajustes necessários

Na quarta-feira, foi apresentada a primeira integração de *back-end* e *front-end* já com *deploy*. Testamos a aplicação e identificamos diversos ajustes necessários. Anotei no quadro da sala as tarefas para resolver os problemas (e os responsáveis por cada uma) — e, nesse processo, acabei revelando uma caligrafia digna de iluminuras medievais. A letra sempre foi meu calcanhar de Aquiles, mas parece que os quadros brancos do CT têm um efeito redentor sobre mim.

> *"Não é a força, mas o constante desenvolvimento que leva ao êxito."* — Winston Churchill

Na sexta-feira, a maioria dos ajustes solicitados foram implementados e o sistema ficou ainda mais funcional. Mostramos as melhorias no site e combinamos uma apresentação oficial para o pessoal do Hub IS na semana seguinte. Fiquei responsável por registrar o feedback da apresentação.

---

## 9ª Semana (27/04/2026 - 01/05/2026)

### Apresentação oficial do site para o Hub IS e empreendedores

Apresentamos o site funcional para os membros do Hub IS e para alguns empreendedores atendidos pelo programa. Eles conseguiram cadastrar seus próprios produtos no site e testar as funcionalidades. Alguns ajustes e *bugs* foram apontados, e a equipe ficou responsável por corrigi-los na versão disponível no GitHub.

---

## 10ª Semana (04/05/2026 - 08/05/2026)

### Vídeos tutoriais e Microsoft Clarity

Durante essa semana, integramos o site com o **Microsoft Clarity**, uma ferramenta de análise de dados que nos permite compreender melhor como os usuários interagem com a plataforma. Além disso, iniciamos o desenvolvimento dos vídeos tutoriais destinados a auxiliar os usuários na utilização do site. Discutimos também os requisitos que atenderiam ao feedback recebido — e, ao listar tudo no quadro, minha caligrafia alcançou um patamar que eu mesmo considerei transcendental. Há quem diga que a necessidade aguça o engenho; eu acrescento que o quadro branco aguça a letra.

---

## 11ª Semana (11/05/2026 - 15/05/2026)

### Ambiente de testes e slides de tutoriais

Na aula de quarta-feira, a professora apresentou uma proposta de separação de ambientes em teste e *deploy*. Nosso colega Guilherme idealizou graficamente — no quadro — como seria um sistema com esses dois ambientes.

Na aula de sexta-feira, convergimos na decisão de criar slides para auxiliar os usuários na utilização do site, em vez de vídeos tutoriais. Durante essa semana, encerrei alguns *commits* que estavam em aberto no repositório do Hub IS.

---

## 12ª Semana (18/05/2026 - 22/05/2026)

### Apresentação dos slides de tutoriais e orçamento de hospedagem

Na quarta-feira, realizamos uma reunião na sala 127 do térreo do CT. Apresentamos os slides de tutoriais e o processo de hospedagem e domínio do site para a Nathália, administradora do Hub IS. Fiquei responsável por elaborar um orçamento de domínios e hospedagens que pudessem atender ao projeto. Na sexta-feira, entregamos uma proposta de orçamento contemplando três alternativas: uma hospedagem institucional (Plano A), uma hospedagem paga (Plano B) e uma hospedagem gratuita (Plano C). Ao longo da semana, encerrei também alguns *commits* que estavam pendentes no repositório do Hub IS.

---

## 13ª Semana (25/05/2026 - 29/05/2026)

### Reunião com Designer e futuro do Hub IS

Na quarta-feira, realizamos outra reunião na sala 127 do térreo do CT. Uma aluna do curso de Desenho Industrial, a Sophia, analisou nosso projeto para desenvolver, nas próximas semanas, uma versão visualmente mais aprimorada. Na sexta-feira, elencamos todas as tarefas futuras em aberto do projeto: data do lançamento oficial, refatoração, documentação de APIs e outros ajustes menores. Novamente, coube a mim o registro no quadro — tarefa que, a essa altura, exercia com a maestria silenciosa de um calígrafo japonês.

> *"A perfeição não é alcançada quando não há mais nada a acrescentar, mas quando não há mais nada a retirar."* — Antoine de Saint-Exupéry

---

## 14ª Semana (01/06/2026 - 05/06/2026)

### Relatório de atividades desenvolvidas e conversa com uma empreendedora

Durante essa semana, estudei o sistema de API com **Swagger**. Também criei arquivos `.md` com a documentação dos contratos (rotas, *endpoints*, etc.), do código (stacks utilizadas, *frameworks*, etc.) e uma documentação geral do projeto. O escopo principal dessa iniciativa foi aprimorar a adoção de *Spec Driven Development* (SDD) na codificação do projeto.

Na aula de quarta-feira, conversei com uma empreendedora que havia relatado um problema na inserção de produtos. Um colega (Guilherme) já havia implementado a correção do *bug*, mas ainda não havíamos retornado o feedback a ela. Expliquei o ocorrido de forma clara, e ela relatou que estava conseguindo utilizar o site sem mais dificuldades.

---

## 15ª Semana (08/06/2026 - 12/06/2026)

### Implementação de documentação para IA em OpenAPI.json

Implementei um arquivo `.json` na raiz do projeto com toda a documentação contratual da API. Com isso, ferramentas de IA passam a compreender melhor o funcionamento da API e podem gerar código de forma mais acurada. Nessa semana, discutimos também como será a inauguração oficial do Hub IS para o público externo, marcada para **08/07/2026, às 9h**.

---

## 16ª Semana (15/06/2026 - 19/06/2026)

### Reunião e criação dos relatórios individuais

Na quarta-feira, realizamos uma reunião para apresentar os avanços na refatoração do código. Apresentei para a turma todo o processo de utilização de documentações em `.md` e `.json` para potencializar o *Spec Driven Development* (SDD) no projeto. Na sexta-feira, foi definido que a aula seria remota para a finalização dos relatórios individuais.

---

## 17ª Semana (22/06/2026 - 26/06/2026)

### Apresentação da Sophia (Design)

Nessa semana, nos deslocamos ao Prédio 40A, 3º andar, sala 2322. A professora Débora, a aluna Sophia e outras colegas apresentaram a proposta de *redesign* do site, incluindo ícones personalizados e até um mascote. O aspecto mais enriquecedor do dia foi, sem dúvida, a oportunidade de dialogar com pessoas que, embora estudem na mesma universidade, habitam um universo acadêmico completamente distinto. Raramente eu adentrava o perímetro sociabilizatório além do CT — e a experiência de encontrar alunos de Desenho Industrial foi uma espécie de epifania.

> *"Há três métodos para ganhar sabedoria: primeiro, por reflexão, que é o mais nobre; segundo, por imitação, que é o mais fácil; e terceiro, por experiência, que é o mais amargo."* — Confúcio

Um dos aspectos que mais me surpreendeu foi a familiaridade delas com ferramentas de Inteligência Artificial — eu, estudante de Ciência da Computação, conhecia menos recursos que elas. Outro ponto revelador foi a receptividade delas ao uso dessas tecnologias: eu pressupunha que alunos de cursos artísticos encarariam a IA com certo conservadorismo; pelo contrário, demonstraram uma abertura bastante maior do que a que eu havia conjecturado. Conhecer o cotidiano de alunos de outros cursos foi, de fato, uma experiência de valor inestimável.

Na sexta-feira, ficou acertada a entrega deste relatório.

---

> *"Eu tinha uma visão muito limitada do que era o desenvolvimento de um projeto de extensão. Com o tempo, fui percebendo que ele envolve muito mais do que apenas o desenvolvimento de código."*

---

# RELATÓRIO FINAL

Nesta seção, são relatadas minhas experiências pessoais, aprendizados e impactos ao longo da disciplina. Para estruturar essas vivências e os conhecimentos adquiridos, organizei o relato segundo os **5 Is da Extensão**:

---

### Interação Dialógica

Aprimorei consideravelmente minhas *soft skills* de interação nessa disciplina. Aprendi a escutar as necessidades reais dos nossos "clientes", o que, na prática, enriquece o conhecimento empírico de forma que a teoria, por si só, dificilmente proporciona. Muitas disciplinas da graduação priorizam o desenvolvimento do saber teórico; uma cadeira que rompe esse paradigma e explora outra faceta do aprendizado revelou-se uma experiência genuinamente inédita. Na primeira apresentação, cometi algumas gafes memoráveis — mas, nas interações subsequentes, cheguei a um nível de proficiência comunicativa que, ousaria dizer, causaria inveja aos maiores oradores da história.

---

### Impacto Social

Na primeira semana da disciplina, eu não fazia ideia do que iria desenvolver. Quando foi apresentada a ideia da Vitrine Social para o Hub IS, eu não tinha muita convicção de que isso, na prática, resolveria tantas problemáticas sociais. Agora, ao redigir estas linhas — já com noção do impacto potencial da nossa aplicação, embora ainda repleto de incertezas, dado que o lançamento oficial ainda não ocorreu —, sinto satisfação em saber que contribuí, ainda que modestamente, para a vida de alguns empreendedores.

> *"Ninguém é inútil neste mundo se aliviar o fardo de outrem."* — Charles Dickens

Essa percepção se aprofundou em um momento peculiar: enquanto treinava na academia com um amigo do curso de Direito, relatei a ele sobre o projeto. Ele me disse, com convicção, que era "mais do que minha obrigação" retribuir à comunidade tudo que os recursos públicos me proporcionam na UFSM. A frase ressoou. Compreendi, de forma visceral, por que a disciplina de Práticas Extensionistas é tão singular no currículo.

---

### Impacto na Formação

Esta foi, inequivocamente, a disciplina em que mais acumulei conhecimentos aplicáveis à vida real. Das *soft skills* às *hard skills*, do *vibe coding* à comunicação com stakeholders não técnicos — a amplitude do que aprendi é difícil de mensurar. Aprendi a estruturar ambientes em estágios (`Local → Teste → Staging → Produção`), a documentar contratos de API, novas stacks e *frameworks*, a praticar SDD de forma concreta e a elaborar apresentações para públicos leigos em tecnologia.

> *"Diga-me e eu esquecerei. Ensine-me e eu me lembrarei. Envolva-me e eu aprenderei."* — Benjamin Franklin

Mas, para além dos conhecimentos técnicos e comportamentais, esta disciplina me conduziu a uma reflexão de cunho mais profundo. Ela me revelou o significado genuíno do filantropismo — esse amor pela humanidade, esse altruísmo que transcende a esfera profissional e toca a dimensão ética da existência. Em última instância, esta disciplina não apenas me tornou um profissional mais capaz; ela me tornou um ser humano mais consciente de seu lugar no mundo.

---

### Interdisciplinaridade

Essa dimensão manifestou-se com maior intensidade na segunda metade da disciplina, quando estabelecemos interlocução com alunas de áreas artísticas. Nunca havia travado diálogos acadêmicos substantivos com pessoas das áreas "humanas" dentro da universidade. Embora as produções da aluna Sophia ainda não tenham sido incorporadas ao projeto, acredito que o trabalho dela agregará valor significativo à plataforma. Além disso, essa experiência me permitiu compreender perspectivas completamente distintas da minha — como a relação que estudantes de Desenho Industrial estabelecem com a Inteligência Artificial e as particularidades do seu percurso formativo.

---

### Indissociabilidade

A indissociabilidade entre ensino, pesquisa e extensão talvez seja o princípio que mais se materializou de forma orgânica ao longo da disciplina. Em nenhum momento o projeto pareceu uma atividade isolada ou descolada do que aprendemos em sala: cada decisão técnica era, simultaneamente, um aprendizado; cada interação com o Hub IS era, ao mesmo tempo, pesquisa aplicada e ação extensionista. Ensino, pesquisa e extensão não foram conceitos abstratos nessa cadeira — foram a própria substância do que vivemos.

> *"A educação é a arma mais poderosa que você pode usar para mudar o mundo."* — Nelson Mandela

Ao encerrar este relatório, fica a certeza de que a extensão universitária não é um apêndice da formação acadêmica, mas uma de suas dimensões mais essenciais — aquela que devolve à sociedade o que dela recebemos.