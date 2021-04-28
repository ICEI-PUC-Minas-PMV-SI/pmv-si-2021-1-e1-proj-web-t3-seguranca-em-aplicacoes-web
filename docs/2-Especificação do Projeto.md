# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Este documento tem a finalidade de apresentar as personas deste projeto, que seriam pessoas as quais teriam suas demandas satisfeitas com este sistema Web. As técnicas e ferramentas utilizadas são o brainstorming e análise de necessidades do mercado e dos próprios desenvolvedores para montar os perfis. 

Também são definidos os requisitos funcionais e os não funcionais, que foram concebidos com a análise citada anteriormente. Nesta etapa, foi feita uma reflexão com base na demanda crescente por serviços que norteiem boas práticas de Segurança da Informação.

As restrições desse projeto consistem em ter o prazo de ser concluído até o final do semestre e não ser desenvolvido um módulo backend para ele.

## Personas

Augustus tem 30 anos, é formado em Sistemas de Informação e trabalha com projetos de segurança da informação, pois essa área o deixa fascinado. Ele é metódico e troca suas senhas periodicamente. Augustus participa de vários projetos de SI simultaneamente e faz todos os registros em uma planilha. Isso faz com que ele encontre certa dificuldade para enviar feedbacks aos seus clientes e as vezes ele se sente perdido sem saber ao certo de onde deve continuar. Ele busca uma ferramenta que o auxilie nesse processo dar retorno aos seus clientes e ao mesmo tempo gerenciar melhor seus projetos de SI.

Ana Beatriz, 25 anos, é recém-formada no curso de Tecnologia em Segurança da Informação, está em busca de algumas certificações e de aprimorar-se mais na área, apesar disso ela já atua na área de segurança da informação dando consultoria para pequenas empresas e fazendo adequações de segurança da informação para elas. 

Miguel tem 23 anos, é técnico em informática, possui muita habilidade em programação e recentemente começou a trabalhar com Segurança da Informação, fazendo testes de vulnerabilidades em sistemas web, redes de computadores locais e participando de projetos de implantação de Segurança da Informação. Ele deseja ter uma ferramenta que o guie em cada etapa quando estiver implantando projetos. 

Enumere e detalhe as personas da sua solução. Para tanto, baseie-se tanto nos documentos disponibilizados na disciplina e/ou nos seguintes links:

> **Links Úteis**:
> - [Rock Content](https://rockcontent.com/blog/personas/)
> - [Hotmart](https://blog.hotmart.com/pt-br/como-criar-persona-negocio/)
> - [O que é persona?](https://resultadosdigitais.com.br/blog/persona-o-que-e/)
> - [Persona x Público-alvo](https://flammo.com.br/blog/persona-e-publico-alvo-qual-a-diferenca/)
> - [Mapa de Empatia](https://resultadosdigitais.com.br/blog/mapa-da-empatia/)
> - [Mapa de Stalkeholders](https://www.racecomunicacao.com.br/blog/como-fazer-o-mapeamento-de-stakeholders/)
>
Lembre-se que você deve ser enumerar e descrever precisamente e personalizada todos os clientes ideais que sua solução almeja.

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Checklist de ações de Segurança da Informação           | Não esquecer de fazer alguma ação.               |
|Usuário do sistema      | Orientação sobre ações de Segurança da Informação                 | Saber quais ações tomar; quais certificações adquirir e com emissores confiáveis. |
|Administrador       | Modificar a informação disponível para os usuários pertinentes ao sistema Web                 | Constantemente estar atualizando o sistema quanto a novas informações, procedimentos e certificações. |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Usuários poderem preencher Checklists sobre ações de Segurança da Informação. | ALTA | 
|RF-002| Indicação de parceiros confiáveis para serem adquiridas as certificações.   | MÉDIA |
|RF-003| Orientação sobre quais medidas de Segurança de Informação devem ser feitas. | BAIXA |
|RF-004| Dar opções aos usuários de selecionar Certificações especificas ou apenas consultorias em respeito à segurança virtual. | ALTA |
|RF-005| Criar a possibilidade de usuários compartilharem suas tabelas com colegas de equipe. | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Funcionar em dispositivos móveis e em computadores. | MÉDIA | 
|RNF-002| Ter uma wiki ou um repositório de links ou arquivos a respeito da Segurança da Informação. |  BAIXA | 
|RNF-003| Interface intuitiva e minimalista. |  MÉDIA | 
|RNF-004| Autenticação de multiplos fatores. |  ALTA | 
|RNF-005| Alerta para usuários dentro projeto sobre modificações e alterações no mesmo, feito por e-mail. |  MÉDIA | 

Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |


Enumere as restrições à sua solução. Lembre-se de que as restrições geralmente limitam a solução candidata.

> **Links Úteis**:
> - [O que são Requisitos Funcionais e Requisitos Não Funcionais?](https://codificar.com.br/requisitos-funcionais-nao-funcionais/)
> - [O que são requisitos funcionais e requisitos não funcionais?](https://analisederequisitos.com.br/requisitos-funcionais-e-requisitos-nao-funcionais-o-que-sao/)
