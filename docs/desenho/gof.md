# <center> PADRÕES GoF


### Histórico de versão<br>

|Data | Versão | Descrição | Autor(es)|
| -- | -- | -- | -- |
| 23.04.2021 | 0.1 | Criação do documento | Bruna Almeida<br>Damarcones Porto|
| 25.04.2021 | 0.1 | Adição da introdução | Bruna Almeida<br>Damarcones Porto|

### Participantes

* Bruna Almeida
* Damarcones Porto

<br><br>


### Introdução
<div align="justify">

Padrões de projeto são soluções padronizadas para um problema recorrente no projeto de sistemas, que seja comprovadamente útil em um determinado contexto. São soluções que independem de tecnologia ou linguagem de programação e ajudam a promover uma boa prática de projeto.
<br><br>

Os Design Patterns codificam o conhecimento existente, de forma que possa ser reaplicado em contextos diferentes, além de aprimorar a comunicação entre desenvolvedores. Além disso, tornam projetos OO mais flexíveis, elegantes e reusáveis.
<br><br>

O Padrão GoF (Gang of Four) é um repertório de soluções e princípios que ajudam os desenvolvedores a criar software, e que são codificados em um formato estruturado, consistindo em: Nome; Problema que soluciona; e Solução do problema.
<br><br>

Existem 23 padrões do GoF, divididos em quatro categorias: criacionais, estruturais e comportamentais, além dos Padrões de classe e Padrões de classe. Para a arquitetura do Software Gama Boyle Lab, foram selecionados os seguintes padrões, que se adequam melhor ao projeto:</div><br>

- Proxy;
- Builder;

<div align="justify">Cada padrão será detalhado seguidamente.</div><br>


#### **Proxy**
<div align="justify">Proxy é um padrão de design estrutural que permite fornecer um substituto ou espaço reservado para outro objeto. Um proxy controla o acesso ao objeto original, permitindo que você execute algo antes ou depois que a solicitação chega ao objeto original.
<br><br>
A figura 1 demonstra a implementação do padrão GoF Proxy. No código do projeto, ele possibilita o lançamento de exceções em qualquer parte do código ao qual foi chamado.
</div><br>

<div align="center"><img src="../../imagens/padroes/proxy.png" width="600" ></div>
<figcaption align='center'>
    <b>Figura 1 - Implementação do padrão GoF Proxy</b>
</figcaption>
<br>



#### **Builder**
<div align="justify">Builder é um padrão de design criacional que permite construir objetos complexos passo a passo. O padrão permite produzir diferentes tipos e representações de um objeto usando o mesmo código de construção.
<br><br>
O padrão Builder está implementado na figura 2, onde ocorre a criação de novos objetos do tipo experimento de forma separada.
</div><br>


<div align="center"><img src="../../imagens/padroes/builder.png" width="600" ></div>
<figcaption align='center'>
    <b>Figura 2 - Implementação do padrão GoF Builder</b>
</figcaption>
<br>



## Referências
DEVMEDIA, **Design Patterns: Padrões “GoF”**. Disponível em: [devmedia.com.br/design-patterns-padroes-gof/16781](https://www.devmedia.com.br/design-patterns-padroes-gof/16781). Acesso em 24 de abril de 2021.

FACOM, **Padrões GoF**. Disponível em: [facom.ufu.br/~bacala/ESOF/05b-Padr%C3%B5es%20Gof.pdf](http://www.facom.ufu.br/~bacala/ESOF/05b-Padr%C3%B5es%20Gof.pdf). Acesso em 24 de abril de 2021.

MEDIUM, **Design Patterns — Parte 2 — Os Padrões do GOF**. Disponível em: [medium.com/xp-inc/desing-patterns-parte-2-2a61878846d](https://medium.com/xp-inc/desing-patterns-parte-2-2a61878846d). Acesso em 24 de abril de 2021.

BRIZENO, **Classificação dos Padrões de Projeto GoF**. Disponível em: [brizeno.wordpress.com/2011/12/12/classificacao-dos-padroes-de-projeto-gof/](https://brizeno.wordpress.com/2011/12/12/classificacao-dos-padroes-de-projeto-gof/). Acesso em 24 de abril de 2021.