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
| **Pré condição** |O usuário deve ter email válido|
| **Pós condição** |É criado um novo perfil para o usuário|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator insere nome, email e senha e seleciona o botão "Create user"</br></br> 7. A aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo</br></br> |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator insere nome, email e senha e seleciona o botão "Create user", porém seu email já encontra-se cadastrado</br></br> 7.  O aplicativo retorna um erro, informando que seu email já encontra-se cadastrado. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator insere nome, email e senha e seleciona o botão "Create user", porem algum dos dados não é válido</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |

|Cadastro de usuário utilizando conta Google| Author: *Hugo Rocha*|
| :- | :- |
| **Objetivo** | O ator deve poder se cadastrar utilizando-se de sua conta Google. |
| **Atores** | Usuário |
| **Pré condição** |O usuário deve ter uma conta Google ativa.|
| **Pós condição** |É criado um novo perfil para o usuário.|
| **Fluxo principal** | 1. O ator acessa o aplicativo do Plant Jammer </br></br> 2. O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br> 3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4. O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5. O ator seleciona a linguagem do app e a unidade de medida</br></br>6. O ator clica em registrar-se com Google</br></br> 7. O aplicativo redireciona o ator para a página de login do Google para a realização do login.</br></br>8. O aplicativo inicia o modo Tour, onde será explicado e explorado as funcionalidades do aplicativo.  |
| **Fluxo excepcional 1** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3. O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.  O ator clica em registrar-se com Google, porém sua conta já está cadastrada</br></br> 7.  O aplicativo retorna um erro, informando que sua conta já está vinculada a uma conta Plant Jammer ativa, e deve ser feito o login. </br></br>8. O ator é redirecionado para a página de login.</br></br>|
| **Fluxo excepcional 2** | 1. O ator acessa o aplicativo do Plant Jammer</br></br>2.  O ator seleciona seu objetivo no aplicativo (Comer mais vegetais, Esvaziar a geladeira, Descobrir novas receitas, Comer comidas saudáveis)</br></br>3.  O ator seleciona se possui alguma restrição alimentar (Alergias, intolerâncias, etc)</br></br>4.  O ator seleciona seus pratos favoritos (Macarrão, Lasanhas, etc)</br></br>5.  O ator seleciona a linguagem do app e a unidade de medida</br></br>6.   O ator clica em registrar-se com o Google, porém não tem uma conta Google válida.</br></br>7.  O ator é redirecionado novamente para a página de cadastro.</br></br> |

## 5. Conclusão

O diagrama produzido irá auxiliar no processo de validação com os stakeholders, uma vez que é uma forma visual e simples de representar as principais funcionalidades do sistema e as interações entre usuários e casos de uso.


## Bibliografia

1. Reinehr, Sheila. Livro Engenharia de Requisitos, 2020.

2. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 21/03/2021).

3. SOMMERVILLE,I.;SoftwareEngineering,9.ed.,Addison-Wesley

</div>