# <center> Como criar e adicionar novos documentos na documentação

<div align="justify">

Esse tutuorial tem como objetivo explicar o passo a passo para adicionar um novo documento na documentação do projeto.

### Histórico de Versão
|    Data    | Versão | Descrição            | Autor(es)       |
| :--------: | :----: | :------------------: | :-------------: |
| 12/02/2021 |  0.1   | Criação do documento | Durval Carvalho |
| 12/02/2021 |  0.2   | Correção de erros ortográficos | Leonardo Gomes |

## Configuração de ambiente

A documentação do projeto foi construida utilizando a ferramenta [`Docsify`]((https://docsify.js.org/)). O Docsify é um gerador de websites estáticos sobre demanda, em outras palavras, o docsify criar páginas web (HTML, CSS e JS) com base em arquivos estáticos (Markdown), a medida que essas páginas são solicitadas. Sua configuração é bastante simples, sendo necessário somente a configuração básicas da biblioteca no arquivo `index.html`.

A integração do docsify com o github é feito automaticamente, desse modo, toda vez que um novo commit é adicionado na master é atualizado os arquivos do docsify, não sendo necessário nenhuma outra ação para atualizar o site da documentação.

Para rodar o docsify localmente, é necessário instalá-lo. Sendo que a maneira mais simples é por meio do `npm`, assim sendo necessário instalar o `npm` primeiro. Uma vez instalado, basta executar o seguinte comando:

```bash
# Comando para instalar o docsify globalmente
$ npm i docsify-cli -g
```

Após a instação do docsify, navegue até o diretório onde está o `index.html` e execute o seguinte comando:

```bash
$ docsify init .
```

Caso tudo tenha ocorrido com sucesso, o site docsify irá rodar um server local e o site da documentação será servido na URL http://localhost:3000.

## Criando novos documentos

A criação de novas páginas na documentação é bastante simples, e envolve somente a escrita de um arquivo `markdown`.

Primeiro analise a estrutura de diretório atual e localize o melhor local para o novo documento.

Caso o documento em questão seja de caráter técnico (documentação de pacote, API, relatório de decisão, etc) utilize o [template de documentos](primeiros-passos/template-documentos.md).


## Roteamento do docsify

O roteamento do docsify é bastante simples, e funciona da seguinte maneira.

Suponha que o diretório da documentação seja composto por um arquivo `index.html`, onde está configurado o docsify, e os documento `doc1.md` e `di1/doc2.md`.

<div align='center'>
    <a href='assets/images/roteamento_docsify.png' target='_blank'>
        <img src='assets/images/roteamento_docsify.png'>
    </a>
</div>

Esses documentos serão servidos nas seguintes urls

* doc1.md → http://localhost:3000/#/doc1
* doc2.md → http://localhost:3000/#/dir1/doc2

Como pode ser visto, todos os endpoints são relativos ao `index.html`.

## Linkagem

Outra maneira de carregar páginas da documentação é através de links. Para adicionar um link pode-se utilizar caminhos completos como os apresentados na seção anterior, mas também é possível criar caminhos relativos (recomendado).

Suponha que seja necessário criar um link no documento `doc1.md` para o `doc2.md`. Essa ação é possível de ser realizada das seguintes maneiras:

```markdown
<!-- Tags de markdown -->
![documento 2](dir1/doc2)
```

```markdown
<!-- Tags de HTML -->
<img src="dir1/doc2">
```

## Sidebar

O sidebar é a região do site onde ficará agrupado os principais pontos de entrada da documentação. Para adicionar um novo documento no sidebar é preciso modificar o arquivo `_sidebar.md`. Esse arquivo contém todos o markdown que será renderizado na região do sidebar.

Uma vez que o próprio sidebar é um documento markdown, a adição de um novo documento é feito por meio de um link.

O sidebar do diretório do exemplo poderia ser da seguinte maneira:

```markdown
* [Home](/)
* [Documentação do Módulo 1](docs1.md)
    * [Documento 1](docs1.md)
    * [Documento 2](dir1/docs2.md)
```

A renderização desse markdown ficaria da seguinte maneira:

<div align='center'>
    <a href='assets/images/sidebar_docsify.png' target='_blank'>
        <img src='assets/images/sidebar_docsify.png'>
    </a>
</div>

Observe que agrupamos os dois documentos em uma "pasta" ("Documentação do Módulo 1") no arquivo do sidebar. Para que esse agrupamento ocorra, é preciso que os _bullet points_ sejam aninhados (_nested_) e que a pasta possua um link para o primeiro documento da lista.

Existem outras maneiras de escrever o sidebar. Para mais informação consulte a documentação do docsify [sobre sidebar](https://docsify.js.org/#/custom-navbar).

## Conclusão

Com essas informações, você já conhece o mínimo necessário para criar novos documentos. O Docsify é uma ferramenta bastante simples e flexível. É possível extender suas funcionalidades por meio de plugins que a comunidade produz. Para mais informações acesse a [documentação oficial do docsify](https://docsify.js.org/).


</div>