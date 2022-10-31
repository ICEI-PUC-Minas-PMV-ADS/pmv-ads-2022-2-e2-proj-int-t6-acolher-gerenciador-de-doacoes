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
>
>Fonte: Criada pelos autores.






# Programação de Funcionalidades

>Validação de campos de cadastro:
>
>A aplicação obrigará ao usuário preencher corretamente aos campos do formulário, caso não seja preenchido o campo retornará uma mensagem de erro ao usuário informando a obrigatoriedade do seu preenchimento 
>
>![12](https://user-images.githubusercontent.com/102244252/198910821-74246d21-7f86-41ae-ba8e-b6f16275c186.png)
>
> Fonte: Criada pelos autores.

