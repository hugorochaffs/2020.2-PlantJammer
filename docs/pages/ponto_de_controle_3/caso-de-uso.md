# <center> Casos de Uso

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 21/03/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 26/05/2021 |  0.2   | Adição de Casos de Uso | Hugo Rocha |
| 26/05/2021 |  0.3   | Adição da especificação de Casos de Uso | Leonardo Gomes |

<div align="justify">

## 1. Introdução

Ao darmos início ao desenvolvimento de um software, a primeira questão que surge é “O que deve ser construído?”. Embora a pergunta seja simples, a resposta não é. Elicitar requisitos é uma tarefa complexa, que exige tempo, planejamento e experiência.

Uma das ferramentas que podem ser utilizadas para apoiar esse processo e representar graficamente os requisitos funcionais é o diagrama de casos de uso, que oferece uma forma simples de comunicação com os stakeholders em torno das funcionalidades e dos serviços que serão oferecidos aos usuários. O diagrama de casos de uso pode ser usado desde as etapas iniciais da elicitação de requisitos, como um instrumento de apoio para as entrevistas, reuniões ou workshops. Ele pode também apoiar o gerente de projetos como uma forma de documentação gráfica do escopo funcional. [Reinehr, 2020]

O diagrama de casos de uso representa o usuário e suas interações com o sistema, portanto ele é uma ferramenta útil quando o sistema em desenvolvimento é um sistema de informação, ou seja, quando existem diversas interações desse tipo para serem projetadas. Sistemas cuja complexidade não esteja na interação com o usuário, mas sim em seu processamento interno, não se beneficiarão desse tipo de representação.

## 2. Objetivo

O objetivo desse documento é apresentar as principais funcionalidades do sistema e seus usuários de maneira gráfica.

## 3. Caso de Uso

<p align='center'>
    <a href='assets/images/user-cases.png' target='_blank'>
        <img src='assets/images/user-cases.png'>
    </a>
    <figcaption align='center'>
        <b>Figura 1: Diagrama de caso de usos</b>
        <br>
        <small>Fonte: Autor</small>
    </figcaption>
</p>

## 4. Especificação dos casos de uso

### US01 - Cadastros

#### Cadastro utilizando E-mail

|Cadastro de usuário utilizando E-mail| Author: *Hugo Rocha* |
| :- | :- |
| **Objetivo** | O ator deve poder se cadastrar utilizando-se de seu email. |
| **Atores** | Usuário |
| **Pré condição** |O ator deve ter email válido|
| **Pós condição** |É criado um novo perfil para o ator|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator insere nome, email e senha e seleciona o botão "Create user"</br></br> 7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo</br></br> |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator insere nome, email e senha e seleciona o botão "Create user", porém seu email já encontra-se cadastrado</br></br> 7.  O aplicativo retorna um erro, informando que seu email já encontra-se cadastrado. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator insere nome, email e senha e seleciona o botão "Create user", porem algum dos dados não é válido</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |


#### Cadastro utilizando conta Google

|Cadastro de usuário utilizando conta Google| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder se cadastrar utilizando-se de sua conta Google. |
| **Atores** | Usuário |
| **Pré condição** |O ator deve ter uma conta Google ativa.|
| **Pós condição** |É criado um novo perfil para o ator.|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator clica em registrar-se com Google</br></br> 7. O aplicativo redireciona o ator para a página de login do Google para a realização do login.</br></br>8. O aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo.  |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator clica em registrar-se com Google, porém sua conta já está cadastrada</br></br> 7.  O aplicativo retorna um erro, informando que sua conta já está vinculada a uma conta Plant Jammer ativa, e deve ser feito o login. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator clica em registrar-se com o Google, porém não tem uma conta Google válida.</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |


### US02 - Criar receita com ingredientes selecionados

|Criar receita com ingredientes selecionados| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder criar receitas com ingredientes que possui em casa. |
| **Atores** | Usuário, Sistema |
| **Pré condição** |O usuário deve estar logado no aplicativo|
| **Pós condição** |Receita deve ser criada de acordo com a quantidade de cada ingrediente e passo a passo do preparo|
| **Fluxo principal** |1. O ator acessa o Plant jammer</br></br>2. O ator acessa a aba de Lista de Compras</br></br>3. O ator busca pelos ingredientes desejados</br></br>4. O ator seleciona os ingredientes</br></br>5. O sistema recomenda receitas que utilizam os ingredientes selecionados</br></br>6. O ator seleciona uma das receitas recomendadas</br></br>7. O ator confirma que possui todos os ingredientes da receita</br></br>8. O sistema apresenta a roda de sabores e o score de sabor da receita, e recomenda ingredientes para melhorar a receita</br></br>9. Após analisar o score e a roda de sabores da receita, o ator pode adicionar mais ingredientes ou confirmar a seleção.</br></br>10. Se o score de sabor for abaixo de uma certa porcentagem o sistema alerta o ator perguntando se o ator deseja prosseguir assim mesmo.</br></br>11. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta de receitas criadas.</br></br>12. O ator pode modificar a quantidade de porções da receita|
| **Fluxo excepcional 1** |1. O ator acessa o Plant jammer</br></br>2. O ator acessa a aba de Lista de Compras</br></br>3. O ator busca pelos ingredientes desejados</br></br>4. O ator seleciona os ingredientes</br></br>5. O sistema recomenda receitas que utilizam os ingredientes selecionados</br></br>6. O ator seleciona uma das receitas recomendadas</br></br>7. ator confirma que possui todos os ingredientes da receita</br></br>8. O sistema apresenta a roda de sabores e o score de sabor da receita, e recomenda ingredientes para melhorar a receita</br></br>9. Após analisar o score e a roda de sabores da receita, o ator pode adicionar mais ingredientes ou confirmar a seleção.</br></br>10. Se o score de sabor for abaixo de uma certa porcentagem o sistema alerta o ator perguntando se o ator deseja prosseguir assim mesmo.</br></br>11. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta de receitas criadas.</br></br>12. O ator pode modificar a quantidade de porções da receita</br></br>13. O ator agenda a receita.|


### US03 - Preparar receitas criadas por chefs

|Preparar receitas criadas por chefs| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder preparar receitas criadas por diversos chefs |
| **Atores** | Usuário |
| **Pré condição** |O ator deve estar logado no aplicativo.|
| **Pós condição** |Lista de ingredientes e suas quantidades, passo a passo do preparo|
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br>2. Realiza a busca por receitas com o filtro de Chefs ligado.</br></br>3. O ator seleciona uma das receitas criadas por Chefs</br></br>4. O sistema apresenta os ingredientes necessários e o passo a passo de preparação|
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br>2. Realiza a busca por receitas com o filtro de Chefs ligado.</br></br>3. O ator não seleciona nenhuma receita.|


### US04 - Modificar nome

|Modificar nome| Author: *Leonardo Gomes*|
| :- | :- |
| **Objetivo** | O ator deve poder modificar o nome |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá o nome modificado. |
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br>2. O ator acessa as configurações da conta.</br></br> 3. O ator seleciona o campo nome </br></br> 4. O ator faz a alteração</br></br>4.  O ator salva a alteração ao clicar no botão "Save Changes" |
| **Fluxo alternativo 1** | 1. O ator acessa o Plant jammer</br></br>2. O ator acessa as configurações da conta.</br></br>3. O ator seleciona o campo nome </br></br> 4. O ator faz a alteração</br></br>5. O ator digitou algo caracter inválido </br></br> 6. O ator faz a alteração novamente </br></br> 7. O ator salva a alteração ao clicar no botão "Save Changes"  |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br>2. O ator acessa as configurações da conta.</br></br> 3. O ator seleciona o campo nome </br></br> 4. O clica em cancelar para sair do campo |
| **Fluxo excepcional 2** | 1. O ator acessa o Plant jammer</br></br>2. O ator acessa as configurações da conta.</br></br>3. O ator seleciona o campo nome </br></br> 4. O ator faz a alteração</br></br>5. O ator digitou algo caracter inválido </br></br> 6. O ator clica em cancelar para sair do campo |


### US05 - Excluir conta

| Excluir conta | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder excluir a conta |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá sua conta excluída. |
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br> 2. O ator acessa as configurações da conta</br></br> 3. O ator seleciona o botão de deletar conta </br></br> 4. O ator confirma o email </br></br> 5. O ator seleciona novamente o botão para confirmar |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br> 2. O ator acessa as configurações da conta</br></br> 3. O ator seleciona o botão de deletar conta </br></br> 4. O ator clica em cancelar para sair do campo  |


### US06 - Obter assinatura

| Obter assinatura | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder obter o plano PREMIUM do Plant Jammer |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo, o ator deve possuir um cartão de crédito válido |
| **Pós condição** | O ator terá sua conta excluída. |
| **Fluxo principal** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de configurações do aplicativo</br></br> 3. O ator seleciona o botão de mudança de asssinatura</br></br> 4. O ator seleciona qual plano deseja(mensal, anual ou vitalicio)</br></br> 5. O sistema redireciona o ator para a Play Store onde será feito o pagamento |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de configurações do aplicativo</br></br> 3. O ator seleciona o botão de mudança de asssinatura</br></br> 4. O ator clica em cancelar para sair do campo  |
| **Fluxo excepcional 2** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de configurações do aplicativo</br></br> 3. O ator seleciona o botão de mudança de asssinatura</br></br> 4. O ator seleciona qual plano deseja(mensal, anual ou vitalicio)</br></br> 5. O sistema redireciona o ator para a Play Store onde será feito o pagamento</br></br> 6. O sistema do cartão de crédito recusa o pagamento |


### US07 - Visualizar quadro nutricional

| Visualizar quadro nutricional | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder visualizar o quadro nutricional |
| **Atores** | Usuário, Sistema |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá visualizado o quadro nutricional. |
| **Fluxo principal** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa o menu lateral</br></br> 3. O ator seleciona a aba de Quadro Nutricional </br></br> 4. O sistema calcula os valores de proteinas, gordura, carboidratos, etc; das receitas do planejamento e exibe para o ator |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa o menu lateral</br></br> 3. O ator seleciona a aba de Quadro Nutricional </br></br> 4. O sistema retorna que não há como fazer o calculo de valor nutricional, já que o ator não fez o planejamento das receitas |


### US08 - Alterar unidade de medida ou linguagem do app

| Alterar unidade de medida ou linguagem do app | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder Alterar unidade de medida ou linguagem do app |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá a unidade de medida ou linguagem do app alterada. |
| **Fluxo principal** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de configurações do App</br></br> 3. O ator seleciona a configuração desejada</br></br> 4. O ator seleciona a unidade de medida preferida / O ator seleciona a linguagem desejada |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de configurações do App</br></br> 3. O ator seleciona a configuração desejada</br></br> 4. O ator clica em cancelar para sair do campo |


### US09 - Criar pasta para salvar receitas

| Criar pasta para salvar receitas | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder criar pasta para salvar receitas |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá criado pasta para salvar receitas |
| **Fluxo principal** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de pastas</br></br> 3. O ator seleciona o botão de criar nova pasta</br></br> 4. O ator digita o nome da pasta |
| **Fluxo alternativo 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de receitas</br></br> 3. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona o botão de adicionar receita em uma pasta </br></br> 4. O ator seleciona o botão de criar nova pasta</br></br> 5. O ator digita o nome da pasta |
| **Fluxo alternativo 2** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de históricos</br></br> 3. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona o botão de adicionar receita em uma pasta</br></br> 5. O ator seleciona o botão de criar nova pasta</br></br> 6. O ator digita o nome da pasta |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de receitas</br></br> 3. O ator seleciona o botão de criar nova pasta</br></br> 4. O ator clica em cancelar para sair do campo |


### US10 - Criar receita (Chef)

| Criar receita (Chef) | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder criar receita |
| **Atores** | Chef |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá criado receita. |
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator clica no botão de criar um nova receita </br></br> 4. O ator seleciona os ingredientes </br></br> 5. O ator detalha o passo a passo de criação da receita </br></br> 6. O ator seleciona as possibilidades de mudança de ingredientes </br></br> 7. O ator detelha o valor nutriciona de novos ingredientes ainda não registrados no aplicativo </br></br> 8. O ator clica no botão salvar receita |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator clica no botão de criar um nova receita </br></br> 4. O ator clica em cancelar em qualquer etapa da criação da receita para sair do campo |


### US11 - Criar vídeo preparando receita

| Criar vídeo preparando receita | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder criar vídeo preparando receita |
| **Atores** | Chef |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá criado um vídeo preparando receita. |
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator seleciona a receita desejada </br></br> 4. O ator clica no botão adicionar vídeo explicativo </br></br> 5. O ator clica em criar vídeo </br></br> 6. O ator clica em _record_ para iniciar a gravação </br></br> 7. O ator clica em _stop_ para parar a gravação </br></br> 8. O ator clica em adicionar vídeo |
| **Fluxo alternativo 1** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator seleciona a receita desejada </br></br> 4. O ator clica no botão adicionar vídeo explicativo </br></br> 5. O ator clica em criar vídeo </br></br> 6. O ator clica em _record_ para iniciar a gravação </br></br> 7. O vídeo é interrompido por exceder o tempo máximo estipulado pelo aplicativo </br></br> 8. O ator clica em adicionar mesmo assim |
| **Fluxo alternativo 2** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator seleciona a receita desejada </br></br> 4. O ator clica no botão adicionar vídeo explicativo </br></br> 5. O ator clica em criar vídeo </br></br> 6. O ator clica em _record_ para iniciar a gravação </br></br> 7. O vídeo é interrompido por exceder o tempo máximo estipulado pelo aplicativo </br></br> 8. O ator clica em gravar novamente |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator seleciona a receita desejada </br></br> 4. O ator clica no botão adicionar vídeo explicativo </br></br> 5. O ator clica em cancelar em qualquer etapa da criação do vídeo para sair do campo |
| **Fluxo excepcional 2** | 1. O ator acessa o Plant jammer</br></br> 2. O ator vai na aba de receitas criadas </br></br> 3. O ator seleciona a receita desejada </br></br> 4. O ator clica no botão adicionar vídeo explicativo </br></br> 5. O ator clica em criar vídeo </br></br> 6. O ator clica em _record_ para iniciar a gravação </br></br> 7. O vídeo é interrompido por exceder o tempo máximo estipulado pelo aplicativo </br></br> 8. O ator clica em cancelar |



### US12 - Agendar o preparo de uma receita

| Agendar o preparo de uma receita | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder agendar o preparo de uma receita |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá agendado o preparo de uma receita. |
| **Fluxo principal** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de agenda culinária</br></br> 3. O ator seleciona o dia que deseja agendar uma receita</br></br> 4. O ator seleciona a receita que deseja associar ao dia agendado |
| **Fluxo alternativo 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de receitas</br></br> 33. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona o botão de agendar uma receita </br></br> 5. O ator seleciona o dia que deseja agendar uma receita</br></br> |
| **Fluxo alternativo 2** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de históricos</br></br> 3. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona o botão de agendar uma receita </br></br> 5. O ator seleciona o dia que deseja agendar uma receita</br></br> |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de agenda culinária</br></br> 3. O ator seleciona o dia que deseja agendar uma receita</br></br> 4. O ator não pode adicionar receita porque extrapolou o número de receitas agendáveis naquele dia. |
| **Fluxo excepcional 2** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de agenda culinária</br></br> 3. O ator seleciona o dia que deseja agendar uma receita</br></br> 4. O ator clica em cancelar para sair do campo |


### US13 - Criar lista de compras

| Criar lista de compras | Author: *Leonardo Gomes* |
| :- | :- |
| **Objetivo** | O ator deve poder criar lista de compras |
| **Atores** | Usuário |
| **Pré condição** | O ator deve estar logado no aplicativo. |
| **Pós condição** | O ator terá criado lista de compras. |
| **Fluxo principal** | 1. O ator acessa o Plant jammer</br></br> 2. O ator acessa a aba de Lista de Compras</br></br> 3. O ator pesquisa por items que deseja adicionar a lista</br></br> 4. O ator seleciona o item desejado</br></br> 5. Os items selecionados serão exibidos com uma descrição de adicionados manualmente |
| **Fluxo alternativo 1** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de receitas</br></br> 3. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona adicionar a lista de compras </br></br> 5. O item selecionado será exibido com uma descrição de adicionado manualmente |
| **Fluxo alternativo 2** | 1. O ator acessa o Plant Jammer</br></br> 2. O ator acessa a aba de históricos</br></br> 3. O ator clica nos "três pontos" em uma receita </br></br> 4. O ator seleciona o botão de agendar uma receita </br></br> 5. O item selecionado será exibido com uma descrição de adicionado manualmente |
| **Fluxo excepcional 1** | 1. O ator acessa o Plant jammer</br></br> 2. O ator acessa a aba de Lista de Compras</br></br> 3. O ator pesquisa por items que deseja adicionar a lista</br></br> 4. O ator seleciona o item desejado</br></br> 5. O ator clica em cancelar para sair do campo |



## 5. Conclusão

O diagrama produzido irá auxiliar no processo de validação com os stakeholders, uma vez que é uma forma visual e simples de representar as principais funcionalidades do sistema e as interações entre ators e casos de uso.


## Bibliografia

1. Reinehr, Sheila. Livro Engenharia de Requisitos, 2020.

2. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 21/03/2021).

3. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

</div>