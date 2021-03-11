# <center> Requisitos Elicitados

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 10/03/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 11/03/2021 |  0.2   | Adição dos titulos de cada tipo de requisito | Leonardo Gomes |


<div align="justify">

## 1. Introdução

O documento de requisitos elicitados é responsável por agrupar todos os requisitos que o projeto em questão está sujeito. A existência deste documento facilita a validação, a priorização e a modelagem dos diversos requisitos, uma vez que todos estaram agrupados.

## 2. Objetivo

Com o objetivo de facilitar futuras consultas e remover duplicatas, todos os requisitos listados pelas diversas técnicas de elicitação devem ser compilados neste documento.

## 3. Resultado

### Requisitos Não Funcionais


| ID     | Descrição do requisito | Técnicas que originou o requisitos |
| :-:    | :-:                    | :-:               |
| RNF001 | Deve ter uma interface fácil e intuitiva para qualquer pessoa conseguir acessar e encontrar receitas | [PRS01](http://localhost:3000/#/pages/ponto_de_controle_2/personas), [BST40](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [STB03](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard) |
| RNF002 | Ter um layout responsivo para varios tamanhos de tela  | [BST36](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP03](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF003 | O aplicativo não deve ocupar mais de 100MB de armazenamento do dispositivo | [BST38](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [STB01](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [ITP51](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF004 | O aplicativo não deve demorar mais do que 500ms para abrir | [BST39](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [STB01](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [ITP54](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF005 | O aplicativo deve ter compatibilidade com as versões do Android iguais ou maiores que a 6.0 | [BST41](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP57](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP58](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF006 | O aplicativo deve ter compatibilidade com com o IOS | [BST41](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP57](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF007 | O aplicativo deve ter compatibilidade com com o Windows Phone | [BST41](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP57](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF008 | A lista para seleção de ingredientes deve ser apresentada de forma clara e legível | [STB03](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard) |
| RNF009 | O aplicativo não deve realizar downloads maiores do que 2MB sem autorização explícita do usuário | [ITP52](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF010 | O aplicativo deve enviar os logs de execução para um servidor, para futura análise de bugs | [ITP53](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF011 | O aplicativo não deve demorar mais do que 500ms no carregamento das receitas | [ITP55](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF012 | O aplicativo não deve consumir realizar downloads quando estiver do background | [ITP56](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF013 | O aplicativo deve ser nativo do sistema operacional | [BST41](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP57](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP58](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF014 | O aplicativo enquanto executado não deve consumir mais do que 20MB de memória | [ITP59](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [PRS06](http://localhost:3000/#/pages/ponto_de_controle_2/personas) |
| RNF015 | O aplicativo não deve apresentar mais do que 1 falha por 100 horas de execução | [ITP60](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RNF016 | Os dados dos usuários que apagaram suas contas devem ser apagados ou anonimados, de acordo com a LGPD | [ITP17](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |

### Requisitos Funcionais


| ID     | Descrição do requisito | Técnicas que originou o requisitos |
| :-:    | :-:                    | :-:               |
| RF001 | O aplicativo deve deve fornecer no mínimo 100 pratos/receitas diferentes, sem contar as receitas que são criadas pelos usuários | [ETV05](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista) |
| RF002 | O aplicativo deve disponibilizar receitas simples e objetivas, que possuem um baixo grau de dificuldade | [PRS02](http://localhost:3000/#/pages/ponto_de_controle_2/personas) |
| RF003 | O aplicativo deve ter uma sessão para listagem das receitas criadas por determinados chefs de cozinha | [PRS03](http://localhost:3000/#/pages/ponto_de_controle_2/personas), [ITP30](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF004 | O aplicativo deve ter uma sessão de edição de pratos favoritos | [PRS05](http://localhost:3000/#/pages/ponto_de_controle_2/personas) |
| RF005 | Na página de cada receita, deve possuir uma área para o vídeo de alguém preparando a receitas | [BST01](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [BST09](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP33](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF006 | Na página de cada receita, deve haver os passsoa ensinando a preparar a receita | [BST02](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF007 | Na página de cada receita, deve haver um indicador do custo monetário estimado da receita, com base nos ingredientes necessários para o preparo | [BST03](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF008 | Na página de cada receita, deve exitir algum indicador de quais ingredientes podem ser substituídos para melhorar a receita | [BST04](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [BST05](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [OBS13](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF009 | Na página de cada receita, deve haver um seletor da quantidade de porções que se deseja fazer com a receita escolhida. Uma vez definido a quantidade de porções, a quantidade de ingredientes devem ser atualizadas automaticamente | [BST06](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP47](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP48](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP49](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS17](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa), [OBS16](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF010 | Na página de cada receita, deve ser exibido as informações nutricionais da refeição | [BST07](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF011 | Na página de cada receita, deve ser exibido o tempo estimado de preparo da receita | [BST08](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [OBS18](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF012 | Na página de cada receita, na sessão de passo a passo, pode haver dicas entre os passos, sinalizado a melhor maneira de se realizar o passo | [BST09](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ETV03](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista), [OBS14](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF013 | Na página de cada receita, deve haver a opção de compartilhar uma receita | [BST24](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP02](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF014 | Na página de cada receita, deve haver uma sessão de sugestões, onde será sugerido as melhores bebidas que combinam com determinada receita | [BST34](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF015 | Toda receita deve possuir uma avaliação associada, e essa avaliação deve ser apresentada sempre que a receita for exibida | [BST10](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF016 | Na página de cada receita, deve existir a opção de avaliar a receita | [BST15](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [STB06](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [ITP31](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS20](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF017 | Na página de cada receita, deve existir a opção de favoritar a receita | [ITP27](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF018 | Na página de cada receita, deve existir a opção de desfavoritar a receita | [ITP28](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF019 | Em algum lugar do APP deve ser possível ver todas as receitas que já foram favoritadas pelo usuário | [ITP29](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF020 | Na página de cada receita, deve existir uma sessão de avaliações, onde será exibido todas as avaliações feitas até então | [BST16](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF021 | Na página de pesquisa de receitas, deve existir um filtro para exibir somente as receitas acima de um certa avaliação | [BST11](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP32](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF022 | Na página de pesquisa de receitas, deve existir um filtro para selecionar o fator predominante na receita, sendo que o fator é um ingrediente que irá predominar sobre os demais | [OBS12](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF023 | Na página de pesquisa de receitas, deve ser possível pesquisar receitas pelo nome | [ETV01](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista), [ITP01](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF024 | Caso uma receita seja de um Chef, deve existir a opção de visualizar o perfil do Chef, e nesse perfil deve exibir informações como: nome, local onde trabalha, experiencia, número de seguidores, número de receitas curtidas, etc | [BST12](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF025 | Na página de perfil de um Chef deve exitir a opção de seguir o Chef | [BST29](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP37](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF026 | Na página de perfil de um Chef deve exitir a opção de deixar de seguir o Chef | [ITP38](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF027 | Na página de perfil de um Chef deve exitir a opção de avaliar o Chef | [BST13](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF028 | Na página de perfil de um Chef, deve exibir a média das avaliações e a quantidade de avaliações do chefe | [BST14](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF029 | O aplicativo deve ter a opção de criar uma nova conta, utilizando email e senha | [BST17](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP07](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS08](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF030 | Após criar uma nova conta utilizando email e senha, deve ser enviado um email de confirmação, com um link, para o emaild definido. Enquanto o link não for clicado a conta deve permanecer como "não verificada" | [ITP08](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP09](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF031 | O aplicativo deve ter a opção de criar uma nova conta, utilizando a conta do Google ou Facebook | [ITP06](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS07](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF032 | Durante o fluxo de criação de conta, deve ser apresentado os Termos e Políticas do APP, e para criar a conta o usuário deve clicar que leu e concorda | [ITP11](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF033 | O aplicativo deve ter a opção de relizar login com uma conta existente, utilizando email e senha | [BST18](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP05](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS01](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF034 | Na tela de login, deve haver a opção de recuperar senha | [ITP10](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF035 | O aplicativo deve ter a opção de relizar login utilizando a conta do Google ou Facebook | [ITP04](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS02](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa), [OBS03](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF036 | O aplicativo deve ter a opção de modificar o nome, email e senha da conta existente | [BST19](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP12](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP13](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP14](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS40](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF037 | O aplicativo deve ter a opção de excluir uma conta existente | [BST20](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF038 | O aplicativo deve ter a opção de modificar a unidade de medida escolhida (medida imperial, medida métrica) | [BST21](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [OBS19](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF039 | O aplicativo deve ter a opção de registrar as preferências culinárias (pizza, sopas, tortas, etc) | [BST22](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF040 | O aplicativo deve ter a opção de modificar as preferências culinárias (pizza, sopas, tortas, etc) | [BST23](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF041 | O aplicativo deve ter a opção de registrar as restrições alimentáres do usuário | [BST25](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ETV04](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista), [PRS04](http://localhost:3000/#/pages/ponto_de_controle_2/personas) |
| RF042 | O aplicativo deve ter a opção de modificar as restrições alimentáres do usuário | [BST26](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ETV04](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista), [OBS37](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF043 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas pelos ingredientes disponíveis | [BST27](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [STB02](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [STB04](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [ETV02](http://localhost:3000/#/pages/ponto_de_controle_2/entrevista), [ITP50](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS10](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa), [OBS33](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa), [OBS34](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF044 | A lista de resultados exibidas para o usuário deve levar em consideração as preferências culinárias do usuário | [STB05](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard) |
| RF045 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas pelo Chef que cadastrou a receita | [BST28](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP39](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF046 | Na página de pesquisa de receitas, deve ser possível filtrar as receitas com base na estação do ano | [BST35](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF047 | O aplicativo deve ter uma sessão de agendar uma refeição, desse modo o usuário poderá programar qual dia irá fazer qual receita | [BST30](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [OBS29](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF048 | O usuário deve poder modificar a data agendada de uma determinada refeição | [OBS30](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF049 | O usuário deve poder remover uma receita que foi agendada para uma determinada data | [OBS32](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF050 | O usuário deve poder compartilhar o planejamento de refeições agendadas de uma determinada semana ou mês | [OBS31](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF051 | Na página de refeições cadastradas deve ser possível cancelar um agendamento de refeição | [BST33](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF052 | O aplicativo deve ter uma sessão para gerar uma lista de compras com base nas receitas que foram programas para a semana ou para o mês | [BST31](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF053 | Na página da lista de compras, deve ser possível remover produtos da lista de compras | [BST32](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [OBS25](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF054 | Na página da lista de compras, deve blocos de notas, para lembrar de algo | [OBS26](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF055 | Em uma determinada lista de compras, deve ser possível marcar os alimentos que já foram adquiridos | [OBS27](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF056 | Deve ser possível compartilhar uma lista de compras | [OBS28](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF057 | Na página da lista de compras, deve ser possível adicionar produtos da lista de compras | [OBS24](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF058 | Na página de configurações do aplicativo, deve ser possível de mudar a linguagem do APP (portuges, ingles, espanhol, frances, ...) | [BST37](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP25](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS39](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF059 | Ao selecionar uma nova linguagem, a linguagem do aplicativo deve mudar para a opção selecionada | [ITP26](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF060 | Na página de configurações do aplicativo, deve ser possível de escolher o tema do aplicativo (modo claro e modo escuro) | [BST42](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF061 | Na página de configurações do aplicativo, deve ser possível apagar a conta do usuário | [ITP16](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF062 | Quando um novo usuário acessar o aplicativo pela primeira vez, o aplicativo deve iniciar com o modo Tour, onde o aplicativo irá guiar a navegação, apresentando as principais sessões do APP | [BST43](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm), [ITP24](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF063 | Na página de perfil do usuário, deve haver opção de exibir o histórico de receitas curtidas e receitas visitadas pelo usuário | [BST44](http://localhost:3000/#/pages/ponto_de_controle_2/brainstorm) |
| RF064 | De tempos em tempos deve ser exibido um popup solicitando a avaliação do aplicativo pelo usuário, caso ainda não tenha sido avaliado | [STB06](http://localhost:3000/#/pages/ponto_de_controle_2/storyboard), [OBS36](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF065 | Deve ser possível utilizar o aplicativo mesmo sem estar logado ou possuir uma conta. Quando o aplicativo for aberto, se não existir um usuário logado deve existir uma opção para acessar sem login | [ITP15](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF066 | Usuários que nunca tiveram uma assitura Premium devem poder experimentar a assinatura Premium durante 7 dias | [ITP18](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF067 | Os usuáros devem poder obter a assinatura Premium após a confirmação do pagamento | [OBS42](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF068 | Deve ser mostrado anúncios para usuários Freemium, e não deve ser mostrado anúncios para usuários que tiverem assinatura Premium | [OBS43](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF069 | Usuários Freemium devem ter um limite de receitas que podem ser consultadas no dia. Usuários Premium não possuem essa limitações | [OBS44](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF070 | Durante períodos excepcionais (promoções, datas comemorativas, pandemias, etc) deve ser liberado assinaturas Premium para todos os usuários | [OBS45](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF071 | Para usuários que acabaram de criar a conta, deve ser perguntando qual o objetivo do usuário (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis) | [ITP19](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS04](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF072 | Para usuários que acabaram de criar a conta, deve ser perguntando se o usuário possui alguma restrição alimentar (Alergias, Intolerâncias, não consumo de produtos de animais, etc) | [ITP20](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS05](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF073 | Para usuários que acabaram de criar a conta, deve ser perguntando quais são os pratos favoritos do usuário (Macarrão, Lasanhas, Saladas, etc) | [ITP21](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [OBS06](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF074 | Para usuários que acabaram de criar a conta, deve ser perguntando qual a linguagem que o APP deve ser configurado | [ITP22](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF075 | Para usuários que acabaram de criar a conta, deve ser perguntando qual a unidade de medida (imperial, métrica) o APP deve ser configurado | [ITP23](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF076 | Em algum lugar do APP deve ser possível ver todas as receitas que já foram favoritadas pelo usuário | [ITP29](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF077 | Antes de apresentar qualquer receita, deve ser perguntando ao usuário se ele tem alguma restrição alimentar | [ITP34](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF078 | Deve existir a opção de selecionar receitas genéricas (Pizzas, omeletes, sopas, etc), onde o usuário irá receber uma receita adaptada com base nos ingredientes selecionados | [ITP35](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP36](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF079 | Na página de busca de receitas, deve ser possível definir qual será o aroma da receita desejada | [ITP40](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF080 | Antes de gerar uma receita para o usuário, deve ser exibido a lista de ingredientes selecionados e solicitado a confirmação | [ITP41](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF081 | Antes de gerar uma receita para o usuário, deve ser apresentando a roda dos sabores básicos do paladar humano (Doce, Salgado, Azedo, Amargo, Umami), onde cada ingrediente será categorizado em uma parte da roda, e será solicitado a confirmação do usuário. Nessa etapa, o usuário pode adicionar novos ingredientes de acordo com os sabores que estão faltando | [ITP42](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao), [ITP45](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF082 | Antes de gerar uma receita para o usuário, deve ser apresentado um score da receita que será gerada, de acordo com os ingredientes que foram selecionados | [ITP43](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF083 | Antes de gerar uma receita para o usuário, caso o score seja muito baixo o APP deve intervir e perguntar se o usuário não deseja realizar determinada alteração na receita | [ITP44](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF084 | Após a seleção e confirmação de todas as etapas de geração de receita, deve ser apresentado a receita de acordo com os ingredientes definidos | [ITP46](http://localhost:3000/#/pages/ponto_de_controle_2/introspecao) |
| RF085 | O usuário deve poder selecionar e visualizar uma receita já existente | [OBS09](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF086 | O usuário deve poder criar/cadastrar uma receita no APP | [OBS11](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF087 | Na receita que o usuário está executando deve haver a opção de selecionar os passos que já foram executados | [OBS15](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF088 | O usuário deve poder agrupar as receitas em pastas (por exemplo: pasta doces, pasta salgados, pasta "gluten free") | [OBS21](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa), [OBS22](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF089 | O usuário deve poder agrupar as receitas em pastas (por exemplo: pasta doces, pasta salgados, pasta "gluten free") | [OBS21](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF090 | Na página de pesquisa deve ser possível encontrar pastas criadas por outros usuários | [OBS23](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF091 | Na parte de configurações deve existir a opção de convidar/compartilhar o aplicativo com outros usuários | [OBS35](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF092 | O aplicativo deve possui uma sessão de anotações, onde os usuários poderá deixar seus lembretes | [OBS41](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |
| RF093 | Na página de perfil do usuário, deve ter a opção de visualizar o quadro nutricional do usuário, com base nas receitas que o usuário preparou durante a semana e durante o mês | [OBS38](http://localhost:3000/#/pages/ponto_de_controle_2/observacao_participativa) |


## 4. Conclusão

Após reunir todos os requisitos que foram elicitados nas diversas técnicas foi obtido uma lista com 168 requisitos, sendo 21 requisitos não funcionais e 147 requisitos funcionais.

Após analisar individualmente cada um desses requisitos e identificar as duplicatas, a lista de requisitos final foi de 109 requisitos, sendo 16 requisitos não funcionais e 93 requisitos funcionais.

## Bibliografia

- SERRANO, Maurício; SERRANO, Milene. Requisitos - Aula 7. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

- Demoiselle Process - Diretriz: Orientações para a Elicitação de Requisitos. Disponível em: http://demoiselle.sourceforge.net/process/ds/1.2.3-BETA1/ProcessoDemoisellePlugin/guidances/guidelines/orientacoesElicitacaoRequisitos_3AF37DEB.html Acesso em: 10 de março de 2021.


</div>
