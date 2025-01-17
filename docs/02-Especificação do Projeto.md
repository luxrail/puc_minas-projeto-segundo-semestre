# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas

Pedro Paulo tem 26 anos, é arquiteto recém-formado e autônomo. Pensa em se desenvolver profissionalmente através de um mestrado fora do país, pois adora viajar, é solteiro e sempre quis fazer um intercâmbio. Está buscando uma agência que o ajude a encontrar universidades na Europa que aceitem alunos estrangeiros.

As personas levantadas para o entendimento do problema são apresentadas na tabela a seguir:

|Foto                | Nome                               |Descrição                       | Motivações          | Frustações | Hobbies, Histórias |
|--------------------|------------------------------------|--------------------------------| ------------------- | ---------- | ------------------ |
|![natalia](https://user-images.githubusercontent.com/101216578/158676154-c2688be3-c1e9-455a-9628-7717c26bc6a5.jpg)              | Elisabete                            | • Têm 35 anos de idade.<br>• É casada com Reginaldo é tem dois filhos.<br> |                |   Por não ter concluído o ensino médio.<br>O episódio gerou muito estresse, desgaste físico e mental para ela, isso fez com que ela dormisse chateada que acabou afetando seu humor.       |  • texto.<br>• texto.<br>                |
|![natalia](https://user-images.githubusercontent.com/101216578/158676154-c2688be3-c1e9-455a-9628-7717c26bc6a5.jpg)              | Carlos                            | • Têm 46 anos de idade.<br>• É formado em Direiro e é funcionário público.<br> | Devido a vida de solteiro, ele não tem tempo para cuidar da sua casa, então procura por uma faxineira de confiança.               |   Ele teve uma experiência ruim no passado ao procurar uma faxineira por anúncios nos jornais, ela furtou objetos de sua casa.      |  • Gosta de churrasco e cerveja artesanal.<br>                |
|![natalia](https://user-images.githubusercontent.com/101216578/158676154-c2688be3-c1e9-455a-9628-7717c26bc6a5.jpg)              | Carla                            | • Têm Têm 37 anos de idade.<br>• É mãe de três filhos e casada com João.<br>• Utiliza o Facebook para comunicar com a família.<br> | Ela procura uma forma de ganhar uma renda extra para poder ajudar com as despesas de casa.    |   Pessoas que perderam emprego e estão procurando uma fonte de renda.       |  • Gosta de festas.<br>• Ama cuidar da família e dos afazeres da casa.<br>                |
|![natalia](https://user-images.githubusercontent.com/101216578/158676154-c2688be3-c1e9-455a-9628-7717c26bc6a5.jpg)              | Janete                            | • Têm 23 anos de idade.<br>• É casada com Natalino é tem dois filhos.<br>• Utiliza o Whatsapp e Facebook para comunicar com a família.<br> | Janete sonha com sua independência financeira e ela está trabalhando duro e divulga seu trabalho como diarista nas redes socias e compartilha com a família.               |   Por não ter concluído o ensino médio.<br>O episódio gerou muito estresse, desgaste físico e mental para ela, isso fez com que ela dormisse chateada que acabou afetando seu humor.       |  • texto.<br>• Fazeres do lar.<br>                |

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
|Usuário do sistema  | Registrar minhas tarefas           | Não esquecer de fazê-las               |
|Administrador       | Alterar permissões                 | Permitir que possam administrar contas |
|Prestador de serviços       | Consultar disponibilidade de faxina               | Entrar em contato com o cliente |
|Contratante de serviço       | Solicitar orçamento de faxina               | Entrar em contato com o cliente |
|Contratante de serviço      | Comparar diversos orçamentos               | Entrar em contato com o cliente |
|Prestador de serviços       | Consultar disponibilidade de faxina               | Entrar em contato com o cliente |

Apresente aqui as histórias de usuário que são relevantes para o projeto de sua solução. As Histórias de Usuário consistem em uma ferramenta poderosa para a compreensão e elicitação dos requisitos funcionais e não funcionais da sua aplicação. Se possível, agrupe as histórias de usuário por contexto, para facilitar consultas recorrentes à essa parte do documento.

> **Links Úteis**:
> - [Histórias de usuários com exemplos e template](https://www.atlassian.com/br/agile/project-management/user-stories)
> - [Como escrever boas histórias de usuário (User Stories)](https://medium.com/vertice/como-escrever-boas-users-stories-hist%C3%B3rias-de-usu%C3%A1rios-b29c75043fac)
> - [User Stories: requisitos que humanos entendem](https://www.luiztools.com.br/post/user-stories-descricao-de-requisitos-que-humanos-entendem/)
> - [Histórias de Usuários: mais exemplos](https://www.reqview.com/doc/user-stories-example.html)
> - [9 Common User Story Mistakes](https://airfocus.com/blog/user-story-mistakes/)

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto. Para determinar a prioridade de requisitos, aplicar uma técnica de priorização de requisitos e detalhar como a técnica foi aplicada.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | ALTA | 
|RF-002| Emitir um relatório de tarefas no mês   | MÉDIA |

### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ser responsivo para rodar em um dispositivos móvel | MÉDIA | 
|RNF-002| Deve processar requisições do usuário em no máximo 3s |  BAIXA | 

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

## Diagrama de Casos de Uso

O diagrama de casos de uso é o próximo passo após a elicitação de requisitos, que utiliza um modelo gráfico e uma tabela com as descrições sucintas dos casos de uso e dos atores. Ele contempla a fronteira do sistema e o detalhamento dos requisitos funcionais com a indicação dos atores, casos de uso e seus relacionamentos. 

As referências abaixo irão auxiliá-lo na geração do artefato “Diagrama de Casos de Uso”.

> **Links Úteis**:
> - [Criando Casos de Uso](https://www.ibm.com/docs/pt-br/elm/6.0?topic=requirements-creating-use-cases)
> - [Como Criar Diagrama de Caso de Uso: Tutorial Passo a Passo](https://gitmind.com/pt/fazer-diagrama-de-caso-uso.html/)
> - [Lucidchart](https://www.lucidchart.com/)
> - [Astah](https://astah.net/)
> - [Diagrams](https://app.diagrams.net/)
