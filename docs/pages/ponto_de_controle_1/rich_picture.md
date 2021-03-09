# <center> Rich Pictures

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 09/02/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 12/02/2021 |  0.2   | Adição rich picture do Plant Jammer | Leonardo Gomes |

<div align="justify">

## 1. Introdução

`Rich pictures` é um técnica de modelagem cuja notação permite analisar problemas e expressar ideias. É um modelo informal, bem fácil de entender, e que pode ser construído colaborativamente com os stakeholders envolvidos. O uso dessa técnica pode auxiliar na identificação de:

- Processos de negócios e seus requisitos;
- Atores envolvidos nos processos de negócios e suas respectivas responsabilidades;
- Potenciais problemas e conflitos de interesse.

Para se criar um `rich picture`, basta começar com um problema central, bem no centro de uma página em branco, e acrescentar tópicos relacionados no entorno do tema principal.


Todo `rich picture` deve possuir ao menos alguns dos seguintes componentes.

| Componente | Definição |
| :--------: | :-------: |
| Atores | Atores são os usuários e stakeholders que são impactados pelo sistema, diretamente ou indiretamente. Um ator pode representar um ou um grupo de pessoas. Geralmente os atores são representados por "bonecos palitos". |
| Operações | As operações, também conhecidos como processos e/ou funções, são ações realizadas no sistema ou pelo sistema. As ações são, geralmente, representadas por elipses. |
| Tabelas | As tabelas são os conjuntos de dados de determinada entidade que será utilizada no sistema. Essas tabelas auxiliam na identificação de alguns dos dados que será necessário utilizar. São geralmente representado por retângulos. |
| Setas | As setas são os fluxos de informações que ocorrem no sistema. Podem ser ações realizadas, podem ser dados que vão de um módulo para outro. São representados por setas. |
| Bordas do sistema | As bordas do sistema são delimitações da atuação do próprio sistema. O sistema possui um conjunto de operações, tabelas e fluxos, que potencialmente interage com outros sistemas e atores. As bordas servem para delimitar até onde é interno do sistema e onde é externo ao sistema. São geralmente representados por um "núvem" que envolve tudo que o sistema faz. |

<p align='center'>
    <img src='assets/images/rich-picture-example.png'>
    <figcaption align='center'>
        <b>Figura 1: Exemplo de rich picture</b>
        <br>
        <small>Fonte: adapatado de Monk, A.; Howard, S. The Rich picture: a tool for reasoning about work context.</small>
    </figcaption>
</p>

Para a construção de `Rich Picture` efetivo, existe algumas boas práticas.

1. **Defina uma estrutura mínima**. Inclua somente a estrutura necessária para dar apoio aos processos e ações do atores.

2. **Defina o mínimo de processos necessários**. Um sistema possui diversos processo, e tentar representar todos irá deixar o rich picture poluído de informação. Dessa forma inclua somente o essencial.

3. **Defina bem as bordas do sistema**. Para quem não conhece o sistema é difícil saber o que faz e o que não faz parte do sistema. Desse modo, deixe claro até onde o sistema vai.

4. **Utilize uma linguagem compreensiva**. O rich picture é um documento informal, desse modo, a linguagem também deve ser informal. Evite malabarismos gramaticais.

5. **Utilize imagens**. Uma image vale mais que mil palavras, principalmente para `rich picture`. Abstraia conceitos utilizando imagens.


## 2. Objetivo

O objetivo desse documento é introduzir todos os interessados no projeto o escopo desse trabalho, de forma informal e de fácil entendimento. O tema escolhido foi o software chamado [Plant Jammer](https://www.plantjammer.com/), que visa ajudar entusiastas da culinária. A grande funcionalidade desse software é a capacidade de listar receitas de acordo com os alimentos que o usuário tem disponível em sua casa.

Visando ajudar os interessados a compreender os principais atores, ações, os dados necessários e o escopo do software, foi desenvolvido este Rich Picture.

## 3. Rich Picture

<div align='center'>
    <p>Rich Picture da aplicação Plant Jammer</p>
    <a href='assets/images/rich_picture.png' target='_blank'>
        <img src='assets/images/rich_picture.png'>
    </a>
    <figcaption align='center'>
      <b>Figura 2: rich picture do Plant Jammer</b>
      <br>
        <small>Fonte: Autor</small>
    </figcaption>
</div>


## Bibliografia

1. [Open Access] Leite, Julio Cesar Sampaio do Prado. Livro Vivo - Engenharia de Requisitos. Disponível em: http://livrodeengenhariaderequisitos.blogspot.com/ (Último acesso em 09/02/2021).

2. Monk, A; Howard, S. The Rich Picture. A Tool for Reasoning About Work Context. Disponível em https://www.ics.uci.edu/~wscacchi/Software-Process/Readings/RichPicture.pdf. (Último acesso em 09/02/2021).

3. WAGENINGEN University. Rich Picture. Disponível em http://www.mspguide.org/tool/rich-picture. (Último acesso em 09/02/2021).

</div>
