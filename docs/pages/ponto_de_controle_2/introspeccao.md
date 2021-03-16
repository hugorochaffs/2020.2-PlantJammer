# <center> Técnica de Introspecção

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 06/03/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 06/03/2021 |  0.2   | Revisão do documento | Durval Carvalho |
| 09/03/2021 |  0.3   | Modificação da tabela de requisitos | Durval Carvalho |
| 11/03/2021 |  1.0   | Correção ortográfica | Leonardo Gomes |

<div align="justify">

## 1. Introdução

A introspecção é o primeiro e o mais óbvio método para tentar entender quais as funcionalidades e restrições que o sistema deve estar sujeito para que o projeto tenha sucesso.

A técnica de introspecção consiste em um método reflexivo de elicitação de requisitos muito rico, profundo, e de baixo custo. Trata-se de entender quais as prioridades que o sistema deve possuir para que seja bem recebido pelos clientes e pelos stakeholders. Nessa técnica, o engenherio de requisitos deve imaginar o que os [usuários](pages/ponto_de_controle_3/lexico?id=usuário) e stakeholders gostariam de ver presente no sistema.

Por se basear na intuição do engenheiro de requisitos, nem sempre a técnica de introspecção obtem requisitos verdadeiros, uma vez que o engenheiro possui uma visão enviesada e não é capaz de ter a visão de todos os tipos de [usuários](pages/ponto_de_controle_3/lexico?id=usuário) que estariam envolvidos com o sistema.

## 2. Objetivo

O objetivo dessa técnica é fazer com que o analista de requisitos imagine o que os potenciais [usuários](pages/ponto_de_controle_3/lexico?id=usuário) do sistema desejam no sistema, e assim levantar requisitos que serão analisados e validados em etapas posteriores do projeto.

## 3. Introspecção

| ID LOCAL | Descrição | Tipo de Requisito |
| :------: | :-------: | :---------------: |
| ITP01 | Buscar uma [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) pelo nome (pizza de..., sopa de..., etc) | Requisito Funcional |
| ITP02 | Ter a opção de [compartilhar receita](pages/ponto_de_controle_3/lexico?id=compartilhar-uma-receita) | Requisito Funcional |
| ITP03 | O layout do aplicativo deve ser responsivo para os variados tamanho de telas | Requisito Não Funcional |
| ITP04 | Ter a opção de [fazer login](pages/ponto_de_controle_3/lexico?id=fazer-login) através do Facebook ou Google | Requisito Funcional |
| ITP05 | Ter a opção de [fazer login](pages/ponto_de_controle_3/lexico?id=fazer-login) usando email/username e senha | Requisito Funcional |
| ITP06 | Ter a opção de [realizar cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) através do Facebook ou Google | Requisito Funcional |
| ITP07 | Ter a opção de [realizar cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) usando email/username e senha | Requisito Funcional |
| ITP08 | Quando o [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) for realizado utilizando o email, deve ser enviado um link de confirmação no email definido | Requisito Funcional |
| ITP09 | Após o envio do formulário de cadastro, usando email e senha, o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve ser capaz de digitar o código de verificação enviado por email | Requisito Funcional |
| ITP10 | Ter a opção de recuperar a senha esquecida | Requisito Funcional |
| ITP11 | Durante o [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve ser apresentado aos Termos e Políticas do APP | Requisito Funcional |
| ITP12 | Ter a opção de alterar o nome do perfil cadastrado | Requisito Funcional |
| ITP13 | Ter a opção de alterar o email do perfil cadastrado | Requisito Funcional |
| ITP14 | Ter a opção de alterar a senha do perfil cadastrado | Requisito Funcional |
| ITP15 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve ser capaz de utilizar o aplicativo mesmo sem [estar logado](pages/ponto_de_controle_3/lexico?id=Estar-Logado) | Requisito Funcional |
| ITP16 | O aplicativo deve ter a opção de deletar a conta  | Requisito Funcional |
| ITP17 | Os dados dos [usuários](pages/ponto_de_controle_3/lexico?id=usuário) devem ser apagados ou anonimados após a conta ser deletada (LGPD)  | Requisito Funcional |
| ITP18 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve poder utilizar a versão [Premium](pages/ponto_de_controle_3/lexico?id=Premium) do aplicativo durante alguns dias | Requisito Funcional |
| ITP19 | Durante o formulário de [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) de novos [usuários](pages/ponto_de_controle_3/lexico?id=usuário), deve-se perguntar qual o objetivo do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita), Comer comidas saudáveis, etc.) | Requisito Funcional |
| ITP20 | Durante o formulário de [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) de novos [usuários](pages/ponto_de_controle_3/lexico?id=usuário), deve-se perguntar se [usuário](pages/ponto_de_controle_3/lexico?id=usuário) o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) possui alguma [restrição alimentar](pages/ponto_de_controle_3/lexico?id=Restrição-Alimentar) (alergias, intolerâncias, o não consumo de produtos de animais (vegetarianismo e/ou veganismo)) | Requisito Funcional |
| ITP21 | Durante o formulário de [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) de novos [usuários](pages/ponto_de_controle_3/lexico?id=usuário), uma lista de pratos clássicos (macarrão, lasanhas, saladas, etc) deve ser apresentado ao [usuário](pages/ponto_de_controle_3/lexico?id=usuário) para se descobrir as suas preferências culinárias | Requisito Funcional |
| ITP22 | Durante o formulário de [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) de novos [usuários](pages/ponto_de_controle_3/lexico?id=usuário), deve-se perguntar qual a linguagem que [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deseja que o app esteja | Requisito Funcional |
| ITP23 | Durante o formulário de [cadastro](pages/ponto_de_controle_3/lexico?id=fazer-cadastro) de novos [usuários](pages/ponto_de_controle_3/lexico?id=usuário), deve-se perguntar qual a unidade de medida (imperial, métrica) que o que [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deseja que o app esteja | Requisito Funcional |
| ITP24 | [usuários](pages/ponto_de_controle_3/lexico?id=usuário) novos, ao entrarem pela primeira vez no aplicativo, devem ser guiados por um tour pelos principais elementos gráficos da tela | Requisito Funcional |
| ITP25 | O sistema deve disponibilizar uma lista de idiomas | Requisito Funcional |
| ITP26 | Ao selecionar um idioma, o sistema deve ser traduzido para o idioma selecionado | Requisito Funcional |
| ITP27 | Deve ser possível favoritar uma determinada [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP28 | Deve ser possível desfavoritar uma determinada [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP29 | Deve ser possível visualizar a lista de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) que foram favoritadas  | Requisito Funcional |
| ITP30 | Deve ser possível visualizar a lista de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) de um determinado Chef  | Requisito Funcional |
| ITP31 | O [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve ser capaz de avaliar uma [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP32 | Deve ser possível visualizar a lista de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) mais bem avaliadas | Requisito Funcional |
| ITP33 | As [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) devem está associada um vídeo explicando o seu preparo | Requisito Funcional |
| ITP34 | Antes de apresentar qualquer [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita), deve ser perguntado se o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) possui alguma [restrição alimentar](pages/ponto_de_controle_3/lexico?id=Restrição-Alimentar) | Requisito Funcional |
| ITP35 | Na tela principal deve haver uma lista de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) genéricas (pizzas, omeletes, sopas, etc) que os [usuários](pages/ponto_de_controle_3/lexico?id=usuário) podem selecionar e gerar uma [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) de acordo com os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) presentes em sua casa | Requisito Funcional |
| ITP36 | Após selecionar um prato clássico o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve ser apresentado a uma lista de [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) que podem ser selecionados para compor a [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP37 | Deve ser possível favoritar o perfil de um Chef | Requisito Funcional |
| ITP38 | Deve ser possível desfavoritar o perfil de um Chef | Requisito Funcional |
| ITP39 | Deve ser possível visualizar uma lista de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) de Chefs favoritados | Requisito Funcional |
| ITP40 | Após definir o prato e os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente), o usário deve ser apresentado a uma lista de [aromas](pages/ponto_de_controle_3/lexico?id=Aroma) que podem ser selecionados para compor a [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP41 | Após a seleção dos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) e dos [aromas](pages/ponto_de_controle_3/lexico?id=Aroma), deve ser apresentado uma tela com a listagem de tudo selecionado para confirmar as escolhas do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | Requisito Funcional |
| ITP42 | Após a confirmação, deve ser apresentado uma roda dos sabores básicos do paladar humano (Doce, Salgado, Azedo, Amargo, Umami), cada um dos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) selecionados devem ser categorizados em um desses sabores | Requisito Funcional |
| ITP43 | Na tela da roda de sabores, deve ser apresentado um score, de acordo com os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) selecionados | Requisito Funcional |
| ITP44 | Na tela da roda de sabores, caso o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) não tenha selecionado ao menos 1 [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) para cada sabor básico do paladar humano, deve ser apresentado uma notificação sugerindo que [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) que selecionam os 5 sabores básicos são melhores | Requisito Funcional |
| ITP45 | Após a apresentação da roda de sabores, o [usuário](pages/ponto_de_controle_3/lexico?id=usuário) deve confirmar as opções selecionadas para que uma [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) seja gerada | Requisito Funcional |
| ITP46 | Após a confirmação dos [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) na tela da roda de sabores, deve ser apresentado uma [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) com os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) selecionados | Requisito Funcional |
| ITP47 | Toda [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) deve ter a opção de definir a quantidade de porções que se deseja a [refeição](pages/ponto_de_controle_3/lexico?id=comida)  | Requisito Funcional |
| ITP48 | As quantidades de cada [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) deve ser dinâmico, e devem aumentar ou diminuir de acordo com a quantidade de porções selecionadas  | Requisito Funcional |
| ITP49 | Na tela da [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) deve ser listado os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) e as respectivas quantidades necessárias para se produzir a [receita](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Funcional |
| ITP50 | No aplicativo, deve ser possível realizar buscas de [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) selecionados os [ingredientes](pages/ponto_de_controle_3/lexico?id=ingrediente) que estão presentes em casa | Requisito Funcional |
| ITP51 | O aplicativo não deve ocupar mais do que 100MB de um dispositivo móvel | Requisito Não Funcional |
| ITP52 | O aplicativo não deve realizar downloads maiores do que 2MB sem autorização explícita do [usuário](pages/ponto_de_controle_3/lexico?id=usuário) | Requisito Não Funcional |
| ITP53 | O aplicativo deve enviar os logs de execução para um servidor, para futura análise de bugs | Requisito Não Funcional |
| ITP54 | O aplicativo não deve demorar mais do que 500ms para abrir | Requisito Não Funcional |
| ITP55 | O aplicativo não deve demorar mais do que 500ms no carregamento das [receitas](pages/ponto_de_controle_3/lexico?id=avaliar-receita) | Requisito Não Funcional |
| ITP56 | O aplicativo não deve consumir realizar downloads quando estiver do background | Requisito Não Funcional |
| ITP57 | O aplicativo deve ter suporte a Android e IOS | Requisito Não Funcional |
| ITP58 | O aplicativo deve ter suporte para as versões do Android iguais ou maiores que a 6.0 | Requisito Não Funcional |
| ITP58 | O aplicativo deve ser nativo do sistema operacional | Requisito Não Funcional |
| ITP59 | O aplicativo enquanto executado não deve consumir mais do que 20MB de memória | Requisito Não Funcional |
| ITP60 | O aplicativo não deve apresentar mais do que 1 falha por 100 horas de execução | Requisito Não Funcional |


## 4. Conclusão

Foram identificados 60 requisitos utilizando o método da introspecção. Sendo:
- 51 Requisitos funcionais.
- 9 Requisitos não funcionais.


## Bibliografia

1. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 06/03/2021).

2. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

3. SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

</div>