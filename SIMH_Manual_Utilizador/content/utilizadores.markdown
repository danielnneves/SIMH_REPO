---
layout: default
title: "Gestão de Utilizadores"
---


---

# 5. Gestão de utilizadores
<div id="gestao-de-utilizadores"></div>

Através deste módulo é possível realizar a gestão de utilizadores pertencentes a uma entidade hospitalar. 

Esta gestão apenas está acessível a um utilizador que detenha o perfil de administrador da entidade hospitalar onde exerce funções.

Para isso, o utilizador deve, a partir da página inicial, ao módulo de “Gestão de Utilizadores”, tal como ilustra a [](#figAcessoGestaoUtilizadores).

![figAcessoGestaoUtilizadores](img/pages/5_1.jpg)

<p class="caption" id="figAcessoGestaoUtilizadores">Módulo de Gestão de Utilizadores</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figGestaoUtilizadores](img/pages/5_2.jpg)

<p class="caption" id="figGestaoUtilizadores">Página de Gestão de Utilizadores </p>

Aqui, é possível realizar três ações distintas: **Criação**, **Pesquisa** ou **Edição** de utilizadores. 


## 5.1 Criação de utilizadores
<div id="criacao-de-utilizadores"></div>

Para criar novos utilizadores, o utilizador com perfil de administrador deve clicar no botão **Criar**, tal como a [](#figAcessoCriarUtilizadores) ilustra.

![figAcessoCriarUtilizadores](img/pages/5_1_1.jpg)

<p class="caption" id="figAcessoCriarUtilizadores">Página de Criação de Utilizadores </p>
 
Atenta-se que o administrador de uma entidade hospitalar apenas pode criar novos utilizadores para essa mesma entidade.

Ao clicar neste botão aparecerá a página de **Criar Utilizador** (ver [](#figCriarUtilizadores)).

![figCriarUtilizadores](img/pages/5_1_2.jpg)

<p class="caption" id="figCriarUtilizadores">Página de Criação de Utilizadores </p>

Para a criação de um utilizador devem ser preenchidos os seguintes campos obrigatórios:

|    |  Campos Obrigatórios [](#figCriarUtilizadores)	| 		|    
|----|--------------------------------------------------|-------|
| a) |  Nome       		                				|		|
| b) |  Nº Mecanográfico                   				|		|
| c) |  E-mail				              				|		|
| d) |  Perfil                          				| 		|

Os perfis disponíveis para novos utilizadores são:

* **Administrativo da Entidade** - Trabalhadores que pertencem a uma entidade hospitalar.
* **Médico Codificador** - Trabalhadores que pertencem a uma entidade hospitalar. Ao invés do perfil **Administrativo da Entidade**, um médico codificador é responsável pela codificação de um episódio.

No final da edição, o administrador deve clicar no botão **Criar**, para completar a criação de um novo utilizador.


### 5.2 Pesquisa de utilizadores
<div id="pesquisa-de-utilizadores"></div>

Para consultar por utilizadores existentes na entidade hospitalar, deve-se clicar no botão **Pesquisar**, tal como a [](#figAcessoPesquisarUtilizadores) ilustra.

![figAcessoPesquisarUtilizadores](img/pages/5_2_1.jpg)

<p class="caption" id="figAcessoPesquisarUtilizadores">Página de Criação de Utilizadores </p>

Atenta-se que o administrador de uma entidade hospitalar apenas pode pesquisar por utilizadores que pertençam à sua entidade hospitalar.

Adicionalmente, os utilizadores a pesquisar podem ser filtrados por nome de utilizador, perfil ou estado.

Os perfis disponíveis para pesquisa são:

* **Administrativo da Entidade** - Trabalhadores que pertencem a uma entidade hospitalar.
* **Médico Codificador** - Trabalhadores que pertencem a uma entidade hospitalar. Ao invés do perfil **Administrativo da Entidade**, um médico codificador é responsável pela codificação de um episódio.

Os estados disponíveis para pesquisa são:

* **Ativo** - Utilizadores que pertencem à entidade e que podem aceder ao sistema.
* **Bloqueado** - Utilizadores que pertencem à entidade e que foram bloqueados de aceder ao sistema.

A [](#figPesquisaUtilizadores) ilustra como exemplo uma pesquisa de utilizadores efetuada por um administrador do Hospital Espírito Santo, EPE - Évora.

![figPesquisaUtilizadores](img/pages/5_2_2.jpg)

<p class="caption" id="figPesquisaUtilizadores">Pesquisa de utilizadores</p>


### 5.3 Edição de utilizadores
<div id="edicao-de-utilizadores"></div>

Após efetuar uma pesquisa por utilizadores ([5.2. Pesquisa de utilizadores](#pesquisa-de-utilizadores)) e ao seleccionar um utilizador devolvido pela mesma ([](#figPesquisaSeleccaoUtilizadores)),

![figPesquisaSeleccaoUtilizadores](img/pages/5_3_1.jpg)

<p class="caption" id="figPesquisaSeleccaoUtilizadores">Pesquisa e seleção de um utilizador</p>

as opções seguintes opções tornam-se disponíveis:

* **Editar** - Permite a edição dos dados referentes ao utilizador seleccionado;
* **Remover** - Permite remover o utilizador seleccionado do sistema;
* **Ativar** - Permite ativar o acesso ao sistema do utilizador de seleccionado, caso ele esteja bloqueado. Encontra-se inativa se o utilizador seleccionado já estiver ativo.
* **Bloquear** - Bloqueia o acesso ao sistema do utilizador seleccionado, caso ele esteja ativo. Encontra-se inativa se o utilizador seleccionado já estiver bloqueado.

A [](#figEdicaoUtilizadores) ilustra como exemplo a página de edição de um utilizador, após o administrador o ter seleccionado e clicado no botão **Editar**.

![figEdicaoUtilizadores](img/pages/5_3_2.jpg)

<p class="caption" id="figEdicaoUtilizadores">Pesquisa de utilizadores</p>
