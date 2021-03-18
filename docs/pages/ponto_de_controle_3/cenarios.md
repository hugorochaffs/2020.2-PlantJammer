# <center> Cenários

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 18/03/2021 |  0.1   | Criação do documento | João Victor  |

<div align="justify">

## 1. Introdução
Os cenários são exemplos da vida real em que o sistema é ou será utilizado. Os cenários podem ser úteis para adicionar detalhes a uma descrição geral de requisito. Trata-se de descrições de iterações do usuário com o sistema. Cada cenário cobre um pequeno número de interações possíveis. Diferentes cenários são desenvolvidos e oferecem diversos tipos de informação em variados níveis de detalhamento sobre o sistema.

## 2. Metodologia
Utilizaremos a tabela a seguir como modelo para os cenários
| | |
| :-: |:-: |
| **Título** | Título do cenário |
| **Objetivo** | Objetivo/meta do cenarios |
| **Contexto** | pré-condição:</br> pós-condição: |
| **Atores** | Atores envolvidos |
| **Recursos** | Recursos envolvidos |
| **Episódios** | Detalhes do cenários |
| **Restrições** | Descrição da retrição |
| **Exceção** | Descrição da exceção |

## 3. Objetivo
O objetivo desse documento é registrar todos os cenários criados.


## 4. Cenários
 
### C01 - Cadastrar usuário utilizando email

| | |
| :-: |:-: |
| **Título** | Cadastrar usuário utilizando email |
| **Objetivo** | Criar perfil para o usuário no Plant Jammer utilizando email |
| **Contexto** | Pré-condição: Possuir email valido</br> Pós-condição: É criado um perfil para o novo usuário|
| **Atores** | Usuário |
| **Recursos** | Acesso à internet </br> App intalado |
| **Episódios** | 1. O usuário não cadastrado acessa o Plant Jammer</br> 2. O usuário não cadastrado seleciona seu objetivo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br> 3. O usuário não cadastrado seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br> 4. O usuário não cadastrado seleciona pratos favoritos (Macarrão, Lasanhas, etc)</br> 5. O usuário não cadastrado seleciona a linguagem do app e a unidade de medida</br> 6. O usuário não cadastrado insere nome, email e senha e seleciona o botão "Create user"</br> 7. É apresentado o modo Tour, onde o aplicativo irá guiar a navegação |
| **Restrições** | FLuxo intuitivo |
| **Exceção** | Email inválido</br> Usuário fechar aplicativo antes de terminar a ação</br> Internet parar de funcionar no meio da ação |

### C01 - Cadastrar usuário utilizando Google

| | |
| :-: |:-: |
| **Título** | Cadastrar usuário utilizando Google |
| **Objetivo** | Criar perfil para o usuário no Plant Jammer utilizando sua conta Google  |
| **Contexto** | pré-condição: Possuir conta Google</br> pós-condição: É criado um perfil para o novo usuário |
| **Atores** | Usuário |
| **Recursos** | Acesso à internet </br> App intalado |
| **Episódios** | 1. O usuário não cadastrado acessa o Plant Jammer</br> 2. O usuário não cadastrado seleciona seu objetivo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br> 3. O usuário não cadastrado seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br> 4. O usuário não cadastrado seleciona pratos favoritos (Macarrão, Lasanhas, etc)</br> 5. O usuário não cadastrado seleciona a linguagem do app e a unidade de medida</br> 6. O usuário seleciona o botão "Sign-up with Gmail(easiest)"</br> 7. É apresentado o modo Tour, onde o aplicativo irá guiar a navegação  |
| **Restrições** | Sistema possuir conexão com o Google |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação |

### C01 - Modificar Nome

| | |
| :-: |:-: |
| **Título** | Modificar Nome |
| **Objetivo** | Modificar o nome dentro do app |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Nome alterado |
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant jammer</br> 2. O usuário acessa as configurações da conta</br> 3. O usuário seleciona o campo nome e faz a alteração</br> 4. O usuário salva a alteração ao clicar no botão "Save Changes" |
| **Restrições** | Nome que caiba no campo |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação |

### C01 - Excluir conta

| | |
| :-: |:-: |
| **Título** | Excluir conta |
| **Objetivo** | Excluir a conta cadastrada no app |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Conta excluida e usuário redirecionado para a tela de cadastro|
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant jammer</br> 2. O usuário acessa as configurações da conta</br> 3. O usuário seleciona o botão "Delete User"</br> 4. O usuário confirma o email</br> 5. o usuário seleciona novamente o botão para confirmar |
| **Restrições** | - |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> O usuário selecionar o botão "Undo" e cancelar a ação |

### C01 - Criar lista de compras

| | |
| :-: |:-: |
| **Título** | Criar lista de compras |
| **Objetivo** | O usuário pode adicionar items a lista de compras |
| **Contexto** | Pré-condição:Usuário logado</br> Pós-condição: Usuário poderá editar e/ou compartilhar a lista de compras criada |
| **Atores** | Usuário |
| **Recursos** | Acesso a internet |
| **Episódios** | 1. O usuário acessa o Plant jammer</br> 2. O usuário acessa a aba Shop</br> 3. O usuário pesquisa por items que deseja adicionar a lista</br> 4. O usuário seleciona o item desejado</br> 5. Os items selecionados serão exibidos com uma descrição de adicionados manualmente |
| **Restrições** | Fluxo intuitivo |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> O usuário não encontrar o item desejado |

### C01 - Criar receitas com ingredientes selecionados

| | |
| :-: |:-: |
| **Título** | Criar receitas com ingredientes selecionados |
| **Objetivo** | Criar receitas com ingredientes que ja possui em casa |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Receita criada com quantidade de cada ingrediente e passo a passo do preparo |
| **Atores** | Usuário</br>Sistema |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant jammer</br> 2. O usuário acessa a aba Search</br> 3. O usuário busca pelos ingredientes desejados</br> 4. O usuário seleciona os ingredientes</br> 5. O usuário seleciona o botão "Next"</br>6. O sistema recomenda receitas que utilizam os ingredientes selecionados</br> 7. O usuário seleciona uma das receitas recomendadas</br> 8. Usuário verifica se os ingredientes estão corretos e seleciona o botão "Next"</br> 9. O sistema apresenta a roda de sabores e o score de sabor da receita, e recomenda ingredientes para melhorar a receita</br> 10. O usuário poderá adicionar mais ingredientes para melhorar o score de sabor</br> 11. O usuário seleciona o botão "Get recipe"</br> 12. Se o score de sabor for abaixo de uma certa porcentagem o sistema exibi um alerta perguntando se o usuário deseja prosseguir assim mesmo</br> 13. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta "Others Recipes"</br> 14. O usuário pode modificar a quantidade de pessoas que deseja servir a receita |
| **Restrições** | - |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> O usuário não encontrar o item desejado |

### C01 - Preparar receitas criadas por chefs 

| | |
| :-: |:-: |
| **Título** | Preparar receitas criadas por chefs |
| **Objetivo** | Preparar receitas que chef criaram e modifica las se desejar |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Lista de ingredientes e suas quantidades, passo a passo do preparo|
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant jammer</br> 2. O usuário a aba Home</br> 3. O sistema recomenda receitas de acordo com se deseja adicionar uma receita das receitas salveas ou criar uma receita novaas preferências do usuário</br> 4. O usuário pode escolher alguma das receitas recomendadas nas sessão de receitas de chefs ou selecionar o botão "See all" para buscar por outras receitas</br> 5. O usuário pode selecionar ingredientes que deseja e o sistema filtra os resultados para que a receita do chef tenha esses ingredientes</br> 6. O usuário seleciona a receita<br> 7. Se a receita possuir algum igrediente que seja possivel usar mais de um o sistema permite ao usuário escolher</br> 8. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta "Others Recipes"</br> 9. O usuário pode modificar a quantidade de pessoas que deseja servir a receita |
| **Restrições** | Fluxo intuitivo |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> |

### C01 - Agendarse deseja adicionar uma receita das receitas salveas ou criar uma receita nova refeição

| | |
| :-: |:-: |
| **Título** | Agendar refeição |
| **Objetivo** | Agendar refeições da semana |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Receita adicionada ao planejamento do dia desejado|
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant Jammer</br> 2. O usuário a aba Plan</br> 3. O usuário seleciona o botão "Add recipe +" do dia que desejar adicionar uma receita</br> 4. O usuário seleciona se deseja adicionar uma receita das receitas salveas ou criar uma receita nova |
| **Restrições** | Fluxo intuitivo |
| **Exceção** |  O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> |

### C01 - Obter assinatura Premium

| | |
| :-: |:-: |
| **Título** | Obter assinatura Premium |
| **Objetivo** | O usuário poder obter assinatura premium para ter acesso a todas as funcionalidades e não ver propagandas |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br>Usuário utilizar a versão free</br> Pós-condição: Usuário será premium e terá acesso a todas as funcionalidades do app|
| **Atores** | Usuário |
| **Recursos** | Acesso a internet</br>Possuir conta na Play store</br> Possuir cartão de crédito cadastrado na Play Store |
| **Episódios** | 1. O usuário acessa o Plant Jammer</br> 2. O usuário acessa o menu lateral</br> 3. O usuário seleciona o botão "Get Prime"</br> 4. O usuário seleciona qual plano que deseja(mensal, anual ou vitalicio)</br> 5. O usuário seleciona o botão "Continue"</br> 6. O sistema redireciona o usuário para a Play Store onde ele terminará o pagamento |
| **Restrições** | Cartão de crédito válido |
| **Exceção** | O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação |

### C01 - Visualizar quadro nutricional

| | |
| :-: |:-: |
| **Título** | Visualizar quadro nutricional |
| **Objetivo** | O usuário pode visualizar seu consumo de proteinas, gorduras, carboidratos, etc |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: O usuário verá informações nutricionais sobre sua alimentação |
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant Jammer</br> 2. O usuário acessa o menu lateral</br> 3. O usuário seleciona o botão "My nutrition"</br> 4. O sistema calcula os valores de proteinas, gordura, carboidratos, etc das receitas do planejamento e exibe para o usuário |
| **Restrições** | Fluxo intuitivo |
| **Exceção** | O usuário nao planejar nenhuma receita para a semana</br> |


### C01 - Criar pasta para salvar receitas

| | |
| :-: |:-: |
| **Título** | Criar pasta para salvar receitas |
| **Objetivo** | O usuário criar uma pasta personalizada para organizar suas receitas |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Pasta criada para facilitar a organização das receitas do usuário |
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant Jammer</br> 2. O usuário acessa a aba Folders</br> 3. O usuário seleciona o botão "+"</br> 4. O usuário seleciona o campo "Add a name" e digita o nome desejado para a pasta |
| **Restrições** | Nome da pasta nao pode ser vazio |
| **Exceção** |  O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br>O usuário seleciona o botão "Close" para cancelar a ação |

### C01 - Alterar unidade de medida ou linguagem do app

| | |
| :-: |:-: |
| **Título** | Alterar unidade de medida ou linguagem do app |
| **Objetivo** | O usuário alterar a unidade de medida(Imperial ou metrica) ou alterar a linguagem do app(Inglês, francês, espanhol,etc) |
| **Contexto** | Pré-condição: Usuário logado no Plant Jammer</br> Pós-condição: Unidade de medida alterada ou linguagem do app alterada |
| **Atores** | Usuário |
| **Recursos** | Acesso à internet |
| **Episódios** | 1. O usuário acessa o Plant Jammer</br> 2. O usuário acessa o menu lateral</br> 3. O usuário seleciona configurações da conta</br> 4. O usuário seleciona a unidade de medida preferida, ou seleciona a linguagem desejada |
| **Restrições** | Fluxo intuitivo |
| **Exceção** |  O usuário fechar o aplicativo antes de terminar a ação</br> A internet parar de funcionar no meio da ação</br> |

## Bibliografia

Durante a elaboração desse documento, os seguintes documentos de Cenarios serviu como referência:

- [Documento de cenario do grupo iFut](https://requisitos-de-software.github.io/2020.1-iFut/modelagem/cenarios/cenariosTotais/)
- [Documento de Cenario do grupo Deezer](https://requisitos-de-software.github.io/2019.2-Deezer/modelagem/cenarios/cenarios/)


</div>