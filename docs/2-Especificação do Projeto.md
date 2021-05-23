# Especificações do Projeto

Este documento tem a finalidade de apresentar as personas deste projeto, que seriam pessoas as quais teriam suas demandas satisfeitas com este sistema Web. As técnicas e ferramentas utilizadas são o brainstorming e análise de necessidades do mercado e dos próprios desenvolvedores para montar os perfis. 

Também são definidos os requisitos funcionais e os não funcionais, que foram concebidos com a análise citada anteriormente. Nesta etapa, foi feita uma reflexão com base na demanda crescente por serviços que norteiem boas práticas de Segurança da Informação.

As restrições desse projeto consistem em ter o prazo de ser concluído até o final do semestre e não ser desenvolvido um módulo backend para ele.

## Personas

Augustus tem 30 anos, é formado em Sistemas de Informação e trabalha com projetos de segurança da informação, pois essa área o deixa fascinado. Ele é metódico e troca suas senhas periodicamente. Augustus participa de vários projetos de SI simultaneamente e faz todos os registros em uma planilha. Isso faz com que ele encontre certa dificuldade para enviar feedbacks aos seus clientes e as vezes ele se sente perdido sem saber ao certo de onde deve continuar. Ele busca uma ferramenta que o auxilie nesse processo dar retorno aos seus clientes e ao mesmo tempo gerenciar melhor seus projetos de SI.

Ana Beatriz, 25 anos, é recém-formada no curso de Tecnologia em Segurança da Informação, está em busca de algumas certificações e de aprimorar-se mais na área, apesar disso ela já atua na área de segurança da informação dando consultoria para pequenas empresas e fazendo adequações de segurança da informação para elas. 

Miguel tem 23 anos, é técnico em informática, possui muita habilidade em programação e recentemente começou a trabalhar com Segurança da Informação, fazendo testes de vulnerabilidades em sistemas web, redes de computadores locais e participando de projetos de implantação de Segurança da Informação. Ele deseja ter uma ferramenta que o guie em cada etapa quando estiver implantando projetos. 

## Histórias de Usuários

Com base na análise das personas forma identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Usuário do sistema  | Checklist de ações de Segurança da Informação           | Não esquecer de fazer alguma ação.               |
|Usuário do sistema      | Orientação sobre ações de Segurança da Informação                 | Saber quais ações tomar; quais certificações adquirir e com emissores confiáveis. |
|Administrador       | Modificar a informação disponível para os usuários pertinentes ao sistema Web                 | Constantemente estar atualizando o sistema quanto a novas informações, procedimentos e certificações. |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Usuários poderem preencher Checklists sobre ações de Segurança da Informação. | ALTA | 
|RF-002| Orientação sobre quais medidas de Segurança de Informação devem ser feitas. | BAIXA |
|RF-003| Dar opções aos usuários de selecionar Certificações especificas ou apenas consultorias em respeito à segurança virtual. | ALTA |
|RF-004| Criar a possibilidade de usuários compartilharem o progresso de seus projetos com outras pessoas e colegas de equipe. | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| Funcionar em dispositivos móveis e em computadores. | MÉDIA | 
|RNF-002| Ter uma wiki ou um repositório de links ou arquivos a respeito da Segurança da Informação. |  BAIXA | 
|RNF-003| Interface intuitiva e minimalista. |  MÉDIA | 
|RNF-004| Autenticação de multiplos fatores. |  ALTA | 
|RNF-005| Alerta para usuários dentro projeto sobre modificações e alterações no mesmo, feito por e-mail. |  MÉDIA | 
|RNF-006| Indicação de parceiros confiáveis para serem adquiridas as certificações.   | MÉDIA |

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O projeto deverá ser entregue até o final do semestre |
|02| Não pode ser desenvolvido um módulo de backend        |
