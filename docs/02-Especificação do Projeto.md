# Especificações do Projeto

A origem do modelo, assim como a concepção do projeto da plataforma de doações Acolher (arrecadação e gerenciamento), foram as observações de forma crescente e recorrente de tragédias ambientais nos últimos anos, em particular nesse ano de 2022.  

Para fundamentar a construção do presente projeto, foram observadas reportagens veiculadas em mídias de comunicação em massa, além de pesquisas na Web relacionadas aos eventos climáticos que atingiram o território nacional, em específico a região 8888888 do país. Casos conhecidos como o 8888 e a dificuldade dos voluntários ao localizar pontos de apoio para doar os donativos, motivaram o desenvolvimento da solução para encurtar a conexão voluntário/ necessitado.  

Um case semelhante a solução a ser implantada, pode ser observada no site www.praquemdoar.com.br, iniciativa divulgada pelo grupo Globo, como a finalidade de unir projetos já em andamento e pessoas que se identificam com o destino de interesse. A partir dos últimos acontecimentos observados, baseado nas pesquisas e também na consolidação das ideias dos membros desenvolvedores, foram criados personas e histórias de usuários a quem se destina a plataforma Acolher. 

> **Links Úteis**:
> - [Pra quem doar](www.praquemdoar.com.br)

## Personas

1. Annaluh Oliveira 
   Idade: 39 anos. 
   Ocupação: Advogada, possui sua própria advocacia. 
   Motivações: Ela sempre procurando ajudar quem precisa, pois além de estar fazendo o bem para o próximo, também se sente melhor com isto. Annaluh não se sente bem em doar dinheiro, prefere doar bens ou cestas básicas.
   
2. Filipe Afonso 
   Idade: 23 anos 
   Ocupação: Estudante. 
   Motivações: Ele vive em redes sociais, se deparou com um mutirão de gente fazendo campanhas de doação para pessoas que perderam bens materiais por causa da chuva, com isso separou roupas que não lhe servem mais para serem doadas.
   
3. Gabriel Queiroz 
   Idade: 30 anos 
   Ocupação: Fundador de uma ONG que ajuda a cuidar de animais feridos e abandonados. 
   Motivações: Por viver isso na pele, ele está sempre procurando ajudar ONGs e campanhas, João gosta de contribuir com dinheiro pois acha mais fácil, mas possui insegurança. 
   
4. Patrícia Figueiredo 
   Idade: 29 anos 
   Ocupação: Professora de história, trabalha em uma rede pública. 
   Motivações: Ela defende muitas causas infantis e ao ver no jornal notícias de enchentes que destruíram casas, se propôs a arrecadar e doar itens de primeira necessidade para crianças.

## Histórias de Usuários

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE`                                          |PARA ... `MOTIVO/VALOR`                                       |
|--------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------|
|Annaluh Oliveira    | Fazer doações de cestas básicas e bens materiais                            | Ajudar pessoas em áreas de risco                             |
|Annaluh Oliveira    | Saber quais pontos de apoio estão mais próximos                             | Levar os itens para serem doados à uma campanha específica.  |
|Annaluh Oliveira    | Procurar saber sobre a segurança da doação e informação daquela plataforma. | Para se sentir segura em relação a doção e conseguir doar sem medo de golpes. |

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
