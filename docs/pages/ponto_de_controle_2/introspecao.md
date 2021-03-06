# <center> Técnica de Introspecção

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 06/03/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 06/03/2021 |  0.2   | Revisão do documento | Durval Carvalho |

<div align="justify">

## 1. Introdução

A introspeção é o primeiro e o mais óbvio método para tentar entender quais as funcionalidades e restrições que o sistema deve estar sujeito para que o projeto tenha sucesso.

A técnica de introspecção consisti em um método reflexivo de elicitação de requisitos muito rico, profundo, e de baixo custo. Trata-se de entender quais as prioridades que o sistema deve possuir para que seja bem recebido pelos clientes e pelos stakeholders. Nessa técnica, o engenherio de requisitos deve imaginar o que os usuários e stakeholders gostariam de ver presente no sistema.

Por se basear na intuição do engenheiro de requisitos, nem sempre a técnica de introspecção obtem requisitos verdadeiros, uma vez que o engenheiro possui uma visão enviesada e não é capaz de ter a visão de todos os tipos de usuários que estariam envolvidos com o sistema.

## 2. Objetivo

O objetivo dessa técnica é fazer com que o analista de requisitos imagine o que os potenciais usuários do sistema desejam no sistema, e assim levantar requisitos que serão analisados e validados em etapas posteriores do projeto.

## 3. Introspecção

| Descrição | Prioridade (MosCoW) | Tipo |
| :-------: | :-----------------: | :--: |
| Buscar uma receita pelo nome (pizza de..., sopa de..., etc) | Must | Requisito Funcional |
| Compartilhar o link para um receita | Would | Requisito Funcional |
| O layout do aplicativo deve ser responsivo para os variados tamanho de telas | Must | Requisito Não Funcional |
| Ter a opção de fazer login através do Facebook ou Google | Would | Requisito Funcional |
| Ter a opção de fazer login usando email/username e senha | Must | Requisito Funcional |
| Ter a opção de realizar cadastro através do Facebook ou Google | Would | Requisito Funcional |
| Ter a opção de realizar cadastro usando email/username e senha | Must | Requisito Funcional |
| Quando o cadastro for realizado utilizando o email, deve ser enviado um link de confirmação no email definido | Should | | Requisito Funcional |
| Após o envio do formulário de cadastro, usando email e senha, o usuário deve ser capaz de digitar o código de verificação enviado por email | Should | | Requisito Funcional |
| Ter a opção de recuperar a senha esquecida | Must | Requisito Funcional |
| Durante o cadastro o usuário deve ser apresentado aos Termos e Políticas do APP | Must |  | Requisito Funcional |
| Ter a opção de alterar o nome do perfil cadastrado | Should | Requisito Funcional |
| Ter a opção de alterar o email do perfil cadastrado | Should | Requisito Funcional |
| Ter a opção de alterar a senha do perfil cadastrado | Must | Requisito Funcional |
| O usuário deve ser capaz de utilizar o aplicativo mesmo sem estar logado | Must | Requisito Funcional |
| O aplicativo deve ter a opção de deletar a conta  | Must | Requisito Funcional  |
| Os dados dos usuários devem ser apagados ou anonimados após a conta ser deletada (LGPD)  | Must | Requisito Funcional |
| O usuário deve poder utilizar a versão Premium do aplicativo durante alguns dias | Should | Requisito Funcional |
| Durante o formulário de cadastro de novos usuários, deve-se perguntar qual o objetivo do usuário (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis, etc.) | Could | | Requisito Funcional |
| Durante o formulário de cadastro de novos usuários, deve-se perguntar se usuário o usuário possui alguma restrição alimentar (alergias, intolerâncias, o não consumo de produtos de animais (vegetarianismo e/ou veganismo)) | Must | Requisito Funcional |
| Durante o formulário de cadastro de novos usuários, uma lista de pratos clássicos (macarrão, lasanhas, saladas, etc) deve ser apresentado ao usuário para se descobrir as suas preferências culinárias | Should | Requisito Funcional |
| Durante o formulário de cadastro de novos usuários, deve-se perguntar qual a linguagem que usuário deseja que o app esteja | Could | Requisito Funcional |
| Durante o formulário de cadastro de novos usuários, deve-se perguntar qual a unidade de medida (imperial, métrica) que o que usuário deseja que o app esteja | Must | Requisito Funcional |
| Usuários novos, ao entrarem pela primeira vez no aplicativo, devem ser guiados por um tour pelos principais elementos gráficos da tela | Could | Requisito Funcional |
| O sistema deve disponibilizar uma lista de idiomas | Could | Requisito Funcional |
| Ao selecionar um idioma, o sistema deve ser traduzido para o idioma selecionado | Could | Requisito Funcional |
| Deve ser possível favoritar uma determinada receita | Must | Requisito Funcional |
| Deve ser possível desfavoritar uma determinada receita | Must | Requisito Funcional |
| Deve ser possível visualizar a lista de receitas que foram favoritadas  | Must | Requisito Funcional |
| Deve ser possível visualizar a lista de receitas de um determinado Chef  | Should | Requisito Funcional |
| O usuário deve ser capaz de avaliar uma receita | Should | Requisito Funcional |
| Deve ser possível visualizar a lista de receitas mais bem avaliadas | Must | Requisito Funcional |
| As receitas devem está associada um vídeo explicando o seu preparo | Could | Requisito Funcional |
| Antes de apresentar qualquer receita, deve ser perguntado se o usuário possui alguma restrição alimentar | Must | Requisito Funcional |
| Na tela principal deve haver uma lista de receitas genéricas (pizzas, omeletes, sopas, etc) que os usuários podem selecionar e gerar uma receita de acordo com os ingredientes presentes em sua casa | Must | Requisito Funcional |
| Após selecionar um prato clássico o usuário deve ser apresentado a uma lista de ingredientes que podem ser selecionados para compor a receita | Should | Requisito Funcional |
| Deve ser possível favoritar o perfil de um Chef | Would | Requisito Funcional |
| Deve ser possível desfavoritar o perfil de um Chef | Would | Requisito Funcional |
| Deve ser possível visualizar uma lista de receitas de Chefs favoritados | Would | Requisito Funcional |
| Após definir o prato e os ingredientes, o usário deve ser apresentado a uma lista de aromas que podem ser selecionados para compor a receita | Must | Requisito Funcional |
| Após a seleção dos ingredientes e dos aromas, deve ser apresentado uma tela com a listagem de tudo selecionado para confirmar as escolhas do usuário | Must | Requisito Funcional |
| Após a confirmação, deve ser apresentado uma roda dos sabores básicos do paladar humano (Doce, Salgado, Azedo, Amargo, Umami), cada um dos ingredientes selecionados devem ser categorizados em um desses sabores | Should | Requisito Funcional |
| Na tela da roda de sabores, deve ser apresentado um score, de acordo com os ingredientes selecionados | Should | Requisito Funcional |
| Na tela da roda de sabores, caso o usuário não tenha selecionado ao menos 1 ingrediente para cada sabor básico do paladar humano, deve ser apresentado uma notificação sugerindo que receitas que selecionam os 5 sabores básicos são melhores | Should | Requisito Funcional |
| Após a apresentação da roda de sabores, o usuário deve confirmar as opções selecionadas para que uma receita seja gerada | Should | Requisito Funcional |
| Após a confirmação dos ingredientes na tela da roda de sabores, deve ser apresentado uma receita com os ingredientes selecionados | Must | Requisito Funcional |
| Toda receita deve ter a opção de definir a quantidade de porções que se deseja a refeição  | Must | Requisito Funcional |
| As quantidades de cada ingrediente deve ser dinâmico, e devem aumentar ou diminuir de acordo com a quantidade de porções selecionadas  | Must | Requisito Funcional |
| Na tela da receita deve ser listado os ingredientes e as respectivas quantidades necessárias para se produzir a receita | Must | Requisito Funcional |
| No aplicativo, deve ser possível realizar buscas de receitas selecionados os ingredientes que estão presentes em casa | Must | Requisito Funcional |
| O aplicativo não deve ocupar mais do que 100MB de um dispositivo móvel | Must | Requisito Não Funcional |
| O aplicativo não deve realizar downloads maiores do que 2MB sem autorização explícita do usuário | Must | Requisito Não Funcional |
| O aplicativo deve enviar os logs de execução para um servidor, para futura análise de bugs | Must | Requisito Não Funcional |
| O aplicativo não deve demorar mais do que 500ms para abrir | Must | Requisito Não Funcional |
| O aplicativo não deve demorar mais do que 500ms no carregamento das receitas | Must | Requisito Não Funcional |
| O aplicativo não deve consumir realizar downloads quando estiver do background | Must | Requisito Não Funcional |


## 4. Conclusão

Foram identificados 51 requisitos utilizando o método da introspecção.


## Bibliografia

1. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 06/03/2021).

2. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

3. SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

</div>