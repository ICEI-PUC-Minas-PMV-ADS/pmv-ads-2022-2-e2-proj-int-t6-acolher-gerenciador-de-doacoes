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

|EU COMO... `PERSONA`| QUERO/DESEJO ... `O QUE`                                          |PARA ... `POR QUE`                                       |
|--------------------|-----------------------------------------------------------------------------|--------------------------------------------------------------|
|Annaluh Oliveira    | Fazer doações de cestas básicas e bens materiais.                            | Ajudar pessoas em áreas de risco.                             |
|Annaluh Oliveira    | Saber quais pontos de apoio estão mais próximos.                             | Levar os itens para serem doados à uma campanha específica.  |
|Annaluh Oliveira    | Procurar saber sobre a segurança da doação e informação daquela plataforma. | Para se sentir segura em relação a doção e conseguir doar sem medo de golpes. |
|Filipe Afonso       | Fazer o cadastro para conseguir doar.                                       | Para ser reconhecido pela doação. |
|Filipe Afonso       | Mobilizar pessoas com o auxílio das redes sociais.                           | Aglutinar voluntários para a realização de doações em todo território nacional. |
|Gabriel Queiroz     | Realizar campanhas para a arrecadação de dinheiro em sua ONG de animais.     | Destinar recursos para animais abandonados em diferentes regiões. 
|Gabriel Queiroz     | Cadastrar profissionais veterinários voluntários.                            | Encaminhar veterinários para locais necessitados. |
|Patrícia Figueiredo | Estimular funcionários e pais de alunos a iniciar uma conduta voluntária.    | Disponibilizar um ponto de apoio para arrecadação de itens na comunidade.| 
|Patrícia Figueiredo | Angariar doações de estabelecimentos que se identificam com a causa.         | Arrecadar itens para suprir necessidade básica de crianças em situação de vulnerabilidade. |

Fonte: Criado pelos autores. 

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001| O site deve possuir uma página de login com usuário e senha  | ALTA | 
|RF-002| O site deve apresentar um link para criar e gerenciar o acesso do usuário doador    | ALTA |
|RF-003| A plataforma deve informar a origem, quantidade de itens arrecadados e o destino das doações. | ALTA 
|RF-004| A aplicação deve permitir o gerenciamento do total de itens recolhidos e destinados. | ALTA |
|RF-005| O site deve gerenciar concordância dos usuários nos termos de conduta e uso da plataforma antes do cadastro. | ALTA |
|RF-006| O programa deve administrar o aceite de política de privacidade ao usuário. | ALTA |
|RF-007| A plataforma deve exibir os nomes de parceiros doadores com maior reconhecimento no rodapé da página | MÉDIA |
|RF-008| Na plataforma será informado os pontos de coleta próximos a casa do doador. | ALTA |
|RF-009| O nome das Ongs e/ou instituições responsáveis por receber as doações bem como seu breve histórico ficarão disponíveis para consulta no site. | MÉDIA |
|RF-010| O site deve administrar as áreas de atuações das empresas (ONGs) parceiras, assim como o destino das doações por ela manuseadas.  | MÉDIA | 
|RF-011| Calcular a quantidade de donativos arrecadados. | MÉDIA |  
Fonte: Criada pelos autores. 


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O site deve ser publicado em um ambiente acessível publicamente na Internet via GitHub.  | ALTA | 
|RNF-002| O site deverá ser responsivo permitindo a visualização em um celular de forma adequada.  |  ALTA | 
|RNF-003| O site deve ser compatível com os principais navegadores do mercado (Google Chrome, Firefox, Microsoft Edge). | ALTA |
|RNF-004| O site deve possuir interface simplificada tornando-o acessível para pessoas com limitações de velocidade de acesso à internet. Visto que o público alvo está em comunidades atingidas por catástrofes. | MÉDIA |
|RNF-005| O site ficará online e disponível aos usuários 24 horas por dia, 7 dias na semana. Com manutenções programadas em horários com baixo número de usuários ativos. | ALTA |
|RNF-006| O site deverá detalhar os itens arrecadados por meio de uma lista de controle acessível aos administradores.  | MÉDIA |
|RNF-007| No final da página home haverá um espaço destinado para a logo das instituições e/ou Ongs parceiras a fim de dar credibilidade ao site. | MÉDIA |
Fonte: Criada pelos autores. 


## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01|O projeto deverá ser entregue no final do semestre letivo, não podendo extrapolar a data de 11/12/2022. |
|02|A plataforma deve se restringir às tecnologias básicas utilizando ferramentas de desenvolvimento BackEnd.        |
|03|A equipe não pode subcontratar o desenvolvimento do trabalho. |
|04| A plataforma se compromete em não compartilhar históricos de pesquisa, localização em tempo real e dados sensíveis dos usuários. |


## Diagrama de Casos de Uso

O portal acolher intermediará as interações entre os doadores e a instituição responsável por administrar as doações aos atingidos. O site gerenciará duas formas de doação: a financeira (via PIX ou TED) e o ponto de apoio para aqueles que desejarem levar os alimentos e/ou itens diversos. 

A doação se dará a partir do registro no site, ou tendo cadastro prévio, por meio do login que se inserido incorretamente retorna uma mensagem de erro impossibilitando o usuário de realizar a transferência financeira, mas ainda assim ele poderá acessar o gerenciamento dos desastres realizado pela plataforma, assim como seus respectivos pontos de apoio. 

No rodapé da página inicial constará os parceiros do sítio eletrônico, a fim de trazer credibilidade ao mesmo, bem como as informações de privacidade e termos de uso que estarão disponíveis a todos os usuários e administradores da plataforma.

Figura 1 – Diagrama de Fluxo de dados
![Casos de uso Acolher](https://user-images.githubusercontent.com/103782980/193474325-c7265977-29ad-4823-aa1b-07ef31d42070.png)

