# PROVA DE CONCEITO DA ARQUITETURA (POC)

>O projeto Acolher, é um sistema de gerenciamento de doações. É um sistema web que necessita de tecnologias front-end e back-end. Para que aja uma integração entre o front-end e o back-end  deve ser implementado algum padrão de projeto arquitetural que facilite e permite isso. 
>
>Adotar um padrão pode trazer alguns benefícios como aumento de produtividade, uniformidade na estrutura do software, redução de complexidade do código, entre outros. >
>
>Realizamos uma prova de conceitos com o padrão MVC. 
>
>Objetivo: utilizar uma arquitetura para realizar uma integração de front-end e back-end tendo uma estrutura clara, tal que é possível ver claramente separações entre as camadas de visualização e regras de negócios, ter uma manutenção do sistema fácil, e que possamos ter testes e manutenções de forma isolada entre as camadas. Isso tudo para facilitar o desenvolvimento da aplicação do projeto Acolher. 
>
>Critérios para aceitação: Isolar as regras de negócios da lógica de apresentação, a interface com o usuário. Como o site irá ter várias interfaces, isto possibilita a modificação das mesmas sem que haja a necessidade de alteração das regras de negócios, proporcionando assim muito mais flexibilidade e oportunidades de reuso das classes. 


>Modelo padrão de projeto MVC 

>Vantagens: Possui um controlador que separa as camadas. Quando um evento é executado na interface gráfica, como um clique de um botão, a interface se comunicará com o controlador, que por sua vez se comunica com as regras de negócios. 
Tem facilidade de separar os códigos por camadas de responsabilidade, modelo de dados, visualização (renderização) e controle. 

>Desvantagens: Geralmente requer um conhecimento mais enriquecido, pois possui uma certa dificuldade de ser entendido, além disso ele também exige regras mais rígidas sobre métodos. 

 

Conclusão 

Chegamos à conclusão que a vantagem de adotar um padrão como o MVC que se dá a característica da facilidade na obtenção de múltiplas visões dos mesmos dados, desacoplagem de interface da lógica da aplicação, camadas muito bem definidas. Cada uma delas, o Model, o Controller e a View, executa o que lhe é definido e nada mais do que isso. 

>![CUCE](https://user-images.githubusercontent.com/102244252/198903226-42b5a30a-d093-4ab2-9aeb-ebeaf5983b49.PNG)







# Programação de Funcionalidades

<span style="color:red">Pré-requisitos: <a href="2-Especificação do Projeto.md"> Especificação do Projeto</a></span>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="4-Metodologia.md"> Metodologia</a>, <a href="3-Projeto de Interface.md"> Projeto de Interface</a>, <a href="5-Arquitetura da Solução.md"> Arquitetura da Solução</a>

Implementação do sistema descrita por meio dos requisitos funcionais e/ou não funcionais. Deve relacionar os requisitos atendidos com os artefatos criados (código fonte), deverão apresentadas as instruções para acesso e verificação da implementação que deve estar funcional no ambiente de hospedagem.

Por exemplo: a tabela a seguir deverá ser preenchida considerando os artefatos desenvolvidos.

|ID    | Descrição do Requisito  | Artefato(s) produzido(s) |
|------|-----------------------------------------|----|
|RF-001| Permitir que o usuário cadastre tarefas | tarefas.shtml / tarefas.cs / controllertarefas.cs | 
|RF-002| Emitir um relatório de tarefas no mês   | relatorio.shtml |

# Instruções de acesso

Não deixe de informar o link onde a aplicação estiver disponível para acesso (por exemplo: https://adota-pet.herokuapp.com/src/index.html).

Se houver usuário de teste, o login e a senha também deverão ser informados aqui (por exemplo: usuário - admin / senha - admin).

O link e o usuário/senha descritos acima são apenas exemplos de como tais informações deverão ser apresentadas.

> **Links Úteis**:
>
> - [Trabalhando com HTML5 Local Storage e JSON](https://www.devmedia.com.br/trabalhando-com-html5-local-storage-e-json/29045)
> - [JSON Tutorial](https://www.w3resource.com/JSON)
> - [JSON Data Set Sample](https://opensource.adobe.com/Spry/samples/data_region/JSONDataSetSample.html)
> - [JSON - Introduction (W3Schools)](https://www.w3schools.com/js/js_json_intro.asp)
> - [JSON Tutorial (TutorialsPoint)](https://www.tutorialspoint.com/json/index.htm)
