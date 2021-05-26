# <center> Casos de Uso

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 21/03/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 26/05/2021 |  0.2   | Adição de Casos de Uso | Hugo Rocha |

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

### Casos de Uso Cadastros via email e conta Google

|Cadastro de usuário utilizando E-mail| Author: *Hugo Rocha* |
| :- | :- |
| **Objetivo** | O ator deve poder se cadastrar utilizando-se de seu email. |
| **Atores** | Usuário |
| **Pré condição** |O ator deve ter email válido|
| **Pós condição** |É criado um novo perfil para o ator|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator insere nome, email e senha e seleciona o botão "Create user"</br></br> 7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo</br></br> |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator insere nome, email e senha e seleciona o botão "Create user", porém seu email já encontra-se cadastrado</br></br> 7.  O aplicativo retorna um erro, informando que seu email já encontra-se cadastrado. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator insere nome, email e senha e seleciona o botão "Create user", porem algum dos dados não é válido</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |

|Cadastro de usuário utilizando conta Google| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder se cadastrar utilizando-se de sua conta Google. |
| **Atores** | Usuário |
| **Pré condição** |O ator deve ter uma conta Google ativa.|
| **Pós condição** |É criado um novo perfil para o ator.|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator clica em registrar-se com Google</br></br> 7. O aplicativo redireciona o ator para a página de login do Google para a realização do login.</br></br>8. O aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo.  |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator clica em registrar-se com Google, porém sua conta já está cadastrada</br></br> 7.  O aplicativo retorna um erro, informando que sua conta já está vinculada a uma conta Plant Jammer ativa, e deve ser feito o login. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator clica em registrar-se com o Google, porém não tem uma conta Google válida.</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |


### Criar receita com ingredientes selecionados e preparar receitas criadas por chefs

|Criar receita com ingredientes selecionados| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder criar receitas com ingredientes que possui em casa. |
| **Atores** | Usuário, Sistema |
| **Pré condição** |O usuário deve estar logado no aplicativo|
| **Pós condição** |Receita deve ser criada de acordo com a quantidade de cada ingrediente e passo a passo do preparo|
| **Fluxo principal** |1. O ator acessa o Plant jammer</br></br>2. O ator acessa a aba de Lista de Compras</br></br>3. O ator busca pelos ingredientes desejados</br></br>4. O ator seleciona os ingredientes</br></br>5. O sistema recomenda receitas que utilizam os ingredientes selecionados</br></br>6. O ator seleciona uma das receitas recomendadas</br></br>7. O ator confirma que possui todos os ingredientes da receita</br></br>8. O sistema apresenta a roda de sabores e o score de sabor da receita, e recomenda ingredientes para melhorar a receita</br></br>9. Após analisar o score e a roda de sabores da receita, o ator pode adicionar mais ingredientes ou confirmar a seleção.</br></br>10. Se o score de sabor for abaixo de uma certa porcentagem o sistema alerta o ator perguntando se o ator deseja prosseguir assim mesmo.</br></br>11. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta de receitas criadas.</br></br>12. O ator pode modificar a quantidade de porções da receita|
| **Fluxo excepcional 1** |1. O ator acessa o Plant jammer</br></br>2. O ator acessa a aba de Lista de Compras</br></br>3. O ator busca pelos ingredientes desejados</br></br>4. O ator seleciona os ingredientes</br></br>5. O sistema recomenda receitas que utilizam os ingredientes selecionados</br></br>6. O ator seleciona uma das receitas recomendadas</br></br>7. ator confirma que possui todos os ingredientes da receita</br></br>8. O sistema apresenta a roda de sabores e o score de sabor da receita, e recomenda ingredientes para melhorar a receita</br></br>9. Após analisar o score e a roda de sabores da receita, o ator pode adicionar mais ingredientes ou confirmar a seleção.</br></br>10. Se o score de sabor for abaixo de uma certa porcentagem o sistema alerta o ator perguntando se o ator deseja prosseguir assim mesmo.</br></br>11. O sistema gera a receita com a quantidade de cada ingrediente, o passo a passo da receita e salva a receita na pasta de receitas criadas.</br></br>12. O ator pode modificar a quantidade de porções da receita</br></br>13. O ator agenda a receita.|



|Preparar receitas criadas por chefs| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder preparar receitas criadas por diversos chefs |
| **Atores** | Usuário |
| **Pré condição** |O ator deve estar logado no aplicativo.|
| **Pós condição** |Lista de ingredientes e suas quantidades, passo a passo do preparo|
| **Fluxo principal** | 1. O usuário acessa o Plant jammer</br></br>2. Realiza a busca por receitas com o filtro de Chefs ligado.</br></br>3. O usuário seleciona uma das receitas criadas por Chefs</br></br>4. O sistema apresenta os ingredientes necessários e o passo a passo de preparação|
| **Fluxo excepcional 1** | 1. O usuário acessa o Plant jammer</br></br>2. Realiza a busca por receitas com o filtro de Chefs ligado.</br></br>3. O usuário não seleciona nenhuma receita.|

## 5. Conclusão

O diagrama produzido irá auxiliar no processo de validação com os stakeholders, uma vez que é uma forma visual e simples de representar as principais funcionalidades do sistema e as interações entre ators e casos de uso.


## Bibliografia

1. Reinehr, Sheila. Livro Engenharia de Requisitos, 2020.

2. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 21/03/2021).

3. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

</div>