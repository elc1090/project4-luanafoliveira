# Tattoo Market

![Screenshot do projeto](https://mdswanson.com/static/chops-ux-step-4.png "Screenshot do projeto").


#### Descrição

A ideia do site eh de ser um market place para tatuagem. Teriam dois tipos de usuarios, tatuador e cliente. O objetivo seria para facilitar os tatuadores para administrar seus orcamentos, e ter mais visibilidade e para o cliente o objetivo seria de tonar mais facil para encontrar o tatuador que deseja e pedir um orcamento.

O cliente pode procurar tatuadores na lista de tatuadores ou por categoria do tipo de tatuagem que ele quer, cada tatuador tem uma categoria. O cliente pode acahar o tatuador que deseja e pedir um orcamento para este, o orcamento deve conter uma foto da inspiracao, uma descricao da tatuagem e especificar o local do corpo,tamanho e cor. O cliente pode acessar seus orcametos na pagina com a lsita de orcamentos que sao separados de acordo com seu status, pendente ou aprovado.

O tatuador pode visualizar seu perfil proprio e seus orcamentos. Os orcamentos ficam tambem dividos entre aprovados e pendentes. Quando o tatuador acessa um orcamento especifico ele pode ver os detalhes e colocar um preco para este orcamento e aprova-lo.

Um detalhe que pelo tempo nao foi implementado eh dos usuarios poderem editar seu perfil.

Ja foram cadastrados 10 tatuadores, um para cada categoria. Para cadastrar um novo tatuador alem de informacoes basicas eh necessario colocar o link para foto de perfil, e links para quatro exemplos de tatuagens deste.

#### Deploy

https://tattoomarket.onrender.com/
#### Testes

Para os testes pode-se criar um perfil de cliente e procurar tatuadores para pedir orcamentos.
Ja tem um cliente cadastrado com o meu email que ja tem orcamentos, que foram usados para teste, segue o login e senha->  email: luluoliveira7@gmail.com  , senha: senha
Pode tambem criar o perfil de um tatuador e administrar os orcamentos que foram mandados para ele. Como aprovar orcamentos, mudar preco etc.
Vou deixar um arquivo com o login de todos os tatuadores ja cadastrados.


#### Desenvolvedor(es)
Luana Ferreira Oliveira


#### Tecnologias

React js
Node js
Mongo DB
Express
Nodemon

#### Ambiente de desenvolvimento

Visual Studio Code
GitHub
#### Créditos

Wallpaper feito por: Katiany Echevarria Pinto

- Peguei as informacoes dos tatuadores, bem como suas fotos de perfil e de exemplo do instagram de cada, segue a lista com o instagram desses:
- @maico_borges, @igortattoocs, @flavio_bunker_tattoo, @rodrigocosta_tattoo, @andreipagel, @rafa.handpoke, @corvo_tattoo, @fabianoptattoo, danicunha.ink


#### Bastidores

A maior dificuldade foi em como comunicar para o front e para o back qual usuario estava logado. Primeiro tentei fazer com o local storage do react porem ele nao esta dando o resultado que eu precisva entao mudei a maneira de fazer, colocando o email do usuario locado nas urls e passando de pagina para pagina. Estam maneira nao eh a ideial, porem para este projeto achei melhor deste jeito do que lutar com o local storage.



---
Projeto entregue para a disciplina de [Desenvolvimento de Software para a Web](http://github.com/andreainfufsm/elc1090-2023a) em 2023a
