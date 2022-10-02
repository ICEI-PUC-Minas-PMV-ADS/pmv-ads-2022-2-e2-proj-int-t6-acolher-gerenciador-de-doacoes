# Arquitetura da Solução

<span style="color:red">Pré-requisitos: <a href="3-Projeto de Interface.md"> Projeto de Interface</a></span>

Definição de como o software é estruturado em termos dos componentes que fazem parte da solução e do ambiente de hospedagem da aplicação.

## Diagrama de Classes

Uma instituição situada em um local fixo, referenciada como um ponto de apoio, possui um nome fantasia e um CNPJ registrado ativo para dar credibilidade e transparência na manipulação dos itens arrecadados. A instituição deve adicionar por meio de cadastro, os locais afetados por tragédias, a fim de disponibilizar os dados necessários para o mapeamento e rastreamento de distribuição das doações. A instituição deve cadastrar o local afetado e a quantidade de itens disponíveis no momento em seu galpão de armazenamento. 

Os doadores, por sua vez, têm seus dados registrados na plataforma. São inseridos dados pessoais como nome, profissão e cidade. Pelo sistema, é possível adicionar ou excluir o cadastro, assim como informar a quantidade de itens doados e sua natureza.  

![image](https://user-images.githubusercontent.com/102244252/193481617-aa0efd87-52e4-4ab2-86c2-9f7f1ea0aabe.png)

## Diagrama de Fluxo de Dados

O diagrama de fluxo de dados a seguir, fornece a visão estruturada do sistema da plataforma de gerenciamento de doações Acolher, assim como suas funções de cadastro e consulta dos atores envolvidos. No diagrama logo abaixo, é apresentado a interação do doador, instituição (ponto de apoio) e local afetado no quesito de armazenamento de dados. 

![image](https://user-images.githubusercontent.com/102244252/193481755-8f3e2868-02da-4840-9aea-dc8830be7e97.png)


##  MODELO ENTIDADE RELACIONAMENTO 

O esquema de construção da página do site “Acolher” é exemplificado abaixo através do modelo entidade relacionamento. A interação entre o usuário e sistema está indicada por meio das setas. 

![image](https://user-images.githubusercontent.com/102244252/193481792-5f4a8dc2-c745-4e4c-a0a9-41e600665379.png)


## Projeto da Base de Dados

O projeto da base de dados da plataforma ‘Acolher’ tem como objetivo organizar, gerenciar, identificar, os usuários doadores e seus dados de cadastro – nome, CPF e Dados Bancários.  

> Entidades 

Usuário – Para cadastrar os usuários doadores na plataforma; 

Instituições – Para cadastrar as ONGs e instituições associadas que receberão as doações; 

Postos – Para cadastrar os postos de coleta e retirada de doações; 

Inventário – Tem a função de organizar e quantificar as doações recebidas por posto.  

> Atributos 

	Usuário (CPF (chave primária), Nome, login, senha;) 

	Instituições (CNPJ (chave primária), Nome, Estado); 

	Postos (Nome, Endereço, Estado – A combinação dos três atributos constituem a chave primária); 

	Estoque (Item, Quantidade). 

> Regras de negócio 

	Para a entidade de Usuário, o atributo CPF será a chave primária constituído de um número de CPF válido com 11 dígitos numéricos não nulos onde o mesmo só corresponderá a uma única linha na tabela de login. 

	Para a entidade Instituições, o atributo CNPJ será a chave primária constituído de um número de CNPJ válido com 14 dígitos numéricos não nulos onde o mesmo só corresponderá a uma única linha na tabela de nome correspondente à instituição 

## Tecnologias Utilizadas

Descreva aqui qual(is) tecnologias você vai usar para resolver o seu problema, ou seja, implementar a sua solução. Liste todas as tecnologias envolvidas, linguagens a serem utilizadas, serviços web, frameworks, bibliotecas, IDEs de desenvolvimento, e ferramentas.

Apresente também uma figura explicando como as tecnologias estão relacionadas ou como uma interação do usuário com o sistema vai ser conduzida, por onde ela passa até retornar uma resposta ao usuário.

## Hospedagem

Explique como a hospedagem e o lançamento da plataforma foi feita.

> **Links Úteis**:
>
> - [Website com GitHub Pages](https://pages.github.com/)
> - [Programação colaborativa com Repl.it](https://repl.it/)
> - [Getting Started with Heroku](https://devcenter.heroku.com/start)
> - [Publicando Seu Site No Heroku](http://pythonclub.com.br/publicando-seu-hello-world-no-heroku.html)
