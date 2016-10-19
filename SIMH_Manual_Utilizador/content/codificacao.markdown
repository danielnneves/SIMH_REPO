---
layout: default
title: "Codificação de Episódios"
---


---

# 6. Codificação de Episódios

Através deste módulo é possível fazer a codificação de episódios ainda não codificados de uma determinada entidade hospitalar.

Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo "Codificação de Episódios", tal como ilustra a [](#figAcessoCodificacaoEpisodios).

![figAcessoCodificacaoEpisodios](img/pages/6_1.jpg)

<p class="caption" id="figAcessoCodificacaoEpisodios">Módulo Codificação de Episódios</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figPorCodificar](img/pages/6_2.jpg)

<p class="caption" id="figPorCodificar">Página de entrada do módulo Por Codificar</p>

Aqui, é possível realizar três ações distintas: **Pesquisa**, **Consulta** ou **Edição** de episódios. 

## 6.1. Pesquisa de episódios por codificar
<div id="codificacao-pesquisa-de-episodios"></div>

Na pesquisa de episódios por codificar, um utilizador deve preencher obrigatoriamente um dos seguintes campos:

* **Nº Processo** - Número de processo associado aos episódios a pesquisar;
* **Nº Episódio** - Número que identifica de forma inequívoca o episódio na entidade hospitalar do utilizador;
* **Nº Utente** - Número de utente de saúde do doente associado aos episódios a pesquisar;
* **Data de alta de** - Permite a pesquisa de episódios em que o doente teve data de alta a partir da data aqui definida;
* **até** - Permite a pesquisa de episódios em que o doente teve data de alta até a data aqui definida;
* **Especialidade** - Especialidade médica associada aos episódios a pesquisar.

De seguida deve clicar no botão **Pesquisar**.

A pesquisa realizada apenas devolve episódios relativos à entidade hospitalar do utilizador que efetuou a pesquisa.

A [](#figPesquisaPorCodificar) ilustra como exemplo uma pesquisa de episódios por codificar efetuada por um utilizador.

![figPesquisaPorCodificar](img/pages/6_1_1.jpg)

<p class="caption" id="figPesquisaPorCodificar">Pesquisa de episódios por codificar</p>

## 6.2. Consulta de um episódio
<div id="codificacao-consulta-de-episodios"></div>

Após realizar a pesquisa de episódios por codficar (ver [6.1. Pesquisa de episódios por codificar](#pesquisa-de-episdios-por-codificar)), e ao seleccionar um episódio, passa a ser possível a consulta do mesmo.
Para tal, deve-se clicar no botão **Consultar**, tal como a [](#figConsultaEpisodioPorCodificar) ilustra.

![figConsultaEpisodioPorCodificar](img/pages/6_2_1.jpg)

<p class="caption" id="figConsultaEpisodioPorCodificar">Consulta de um episódio por codificar</p>

Ao clicar neste botão, o utilizador transita para a página de detalhe do episódio tal como a [](#figDetalheEpisodioPorCodificar) ilustra.

![figDetalheEpisodioPorCodificar](img/pages/6_2_2.jpg)

<p class="caption" id="figDetalheEpisodioPorCodificar">Detalhe de um episódio</p>

Nesta página é possível visualizar a seguinte informação:

* **Identificação do Episódio**
![figDetalheEpisodioPorCodificar1](img/pages/6_2_3.jpg)

* **Dados do Episódio**
![figDetalheEpisodioPorCodificar2](img/pages/6_2_4.jpg)

* **Dados da Codificação**
![figDetalheEpisodioPorCodificar3](img/pages/6_2_5.jpg)

* **Dados das Sessões**
![figDetalheEpisodioPorCodificar4](img/pages/6_2_6.jpg)

A informação presente na área **Identificação do Episódio** encontra-se sempre visível durante as transições entre as abas **Dados do Episódio**, **Dados da Codificação** e **Dados das Sessões**.
Durante a consulta de um episódio todos os campos se encontram bloqueados, não sendo possível realizar alterações ao mesmo.

## 6.3. Edição de um episódio
<div id="codificacao-edicao-de-episodios"></div>

Após efetuar uma pesquisa por episódios por codficar ([6.1. Pesquisa de episódios por codificar](#pesquisa-de-episdios-por-codificar)) e ao seleccionar um episódio devolvido pela mesma passa a ser possível a edição do mesmo.
Para tal, deve-se clicar no botão **Editar**, tal como a [](#figEditaEpisodioPorCodificar) ilustra.

![figEditaEpisodioPorCodificar](img/pages/6_3_1.jpg)

<p class="caption" id="figEditaEpisodioPorCodificar">Edição de um episódio por codificar</p>

Ao clicar neste botão, o utilizador transita para a página de codificação do episódio tal como a [](#figCodificacaoEpisodioPorCodificar) ilustra.

![figCodificacaoEpisodioPorCodificar](img/pages/6_3_2.jpg)

<p class="caption" id="figCodificacaoEpisodioPorCodificar">Codificação de um episódio</p>

Para realizar o processo de codificação, é necessário preencher a secção de **Informação do Episódio** e a de **Codificação** do episódio.

Na secção de **Informação do Episódio** (ver [](#figCodificacaoInformacaoEpisodioPorCodificar)), secção onde o utilizador começa a codificação do episódio, é possível visualizar e editar a seguinte informação: **Identificação do Episódio**, **Identificação do Doente**, **Identificação do Médico**, **Natureza da Admissão**, **Destino após Alta**, **Intervenção Cirúrgica** **Serviços** e **Outros Dados**.

![figCodificacaoInformacaoEpisodioPorCodificar](img/pages/6_3_3.jpg)

<p class="caption" id="figCodificacaoInformacaoEpisodioPorCodificar">Passo 1 da codificação: Informação do Episódio</p>

Nesta página irá estar visível o botão **Simular** para utilizadores com perfil médico codificador. Ao clicar neste botão, o utilizador será transportado para um ecrã com o nome **Simular Codificação** (ver [](#figCodificacaoSimularEpisodioPorCodificar)) onde será possível realizar a simulação da codificação do episódio (ver [# 7. Simulador de Codificação](#simulador-de-codificao)).

![figCodificacaoSimularEpisodioPorCodificar](img/pages/6_3_4.jpg)

<p class="caption" id="figCodificacaoSimularEpisodioPorCodificar">Simular Codificação</p>

Para prosseguir para a secção de **Codificação** (ver [](#figCodificacaoCodificacaoEpisodioPorCodificar)) do episódio o utilizador deve premir o botão **Codificar**. 
Nesta secção, é possível visualizar e editar a seguinte informação: **Identificação do Episódio**, **Diagnósticos**, **Procedimentos** e **Dispositivos Médicos**.

![figCodificacaoCodificacaoEpisodioPorCodificar](img/pages/6_3_5.jpg)

<p class="caption" id="figCodificacaoCodificacaoEpisodioPorCodificar">Passo 2 da codificação: Codificação do Episódio</p>

Para adicionar um novo diagnóstico à tabela de diagnósticos ou um novo procedimento à tabela de procedimentos, é necessário preencher um código na caixa de código e adicioná-lo à tabela ![logo](img/pages/6_3_6.jpg).
Quer na tabela de diagnósticos, quer na tabela de procedimentos, os códigos adicionados podem ser removidos ao clicar em ![logo](img/remover.jpg) ou reposicionados, usando para isso a opção ![logo](img/subir.jpg) para mover o código para cima ou a opção ![logo](img/descer.jpg) para mover o código para baixo.

No caso do episódio pertencer ao módulo de internamento, a área de diagnósticos terá, adicionalmente, para cada diagnóstico, informação relativa ao indicador PNA (Presente na admissão):
![figCodificacaoCodificacaoEpisodioPorCodificar3](img/pages/6_3_7.jpg)
Para adicionar um novo diagnóstico a esta tabela, terá de se indicar o PNA correspondente.

Nesta última secção, e assim que a codificação do episódio estiver terminada, esta pode ser gravada premindo o botão **Gravar**.
Também existe a possibilidade de guardar a folha de codificação como rascunho. Para isso, nesta ultima secção, o utilizador deverá clicar no botão **Guardar Rascunho**.

