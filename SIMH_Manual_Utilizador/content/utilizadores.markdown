---
layout: default
title: "Gestão de Utilizadores"
---


---

# 5. Gestão de utilizadores
<div id="gestao-de-utilizadores"></div>

Através deste módulo é possível realizar a gestão de utilizadores pertencentes a uma entidade hospitalar. 

Esta gestão apenas está acessível a um utilizador que detenha o perfil de administrador da entidade hospitalar onde exerce funções.

Para isso, o utilizador deve aceder, a partir da página inicial, ao módulo de “Gestão de Utilizadores”, tal como ilustra a [](#figAcessoGestaoUtilizadores).

![figAcessoGestaoUtilizadores](img/pages/5_1.jpg)

<p class="caption" id="figAcessoGestaoUtilizadores">Módulo de Gestão de Utilizadores</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figGestaoUtilizadores](img/pages/5_2.jpg)

<p class="caption" id="figGestaoUtilizadores">Página de Gestão de Utilizadores </p>

Aqui, é possível realizar três ações distintas: **Criação**, **Pesquisa** ou **Edição** de utilizadores. 


## 5.1 Criação de utilizadores
<div id="criacao-de-utilizadores"></div>

Para criar novos utilizadores, o utilizador deve clicar no botão **CRIAR**. 
Atenta-se que o administrador de uma entidade hospitalar apenas pode criar novos utilizadores para essa mesma entidade.
Ao clicar neste botão aparecerá a página de **Criar Utilizador** (ver [](#figCriarUtilizadores)).

![figCriarUtilizadores](img/pages/5_1_1.jpg)

<p class="caption" id="figCriarUtilizadores">Página de Criação de Utilizadores </p>

Para a criação de utilizador deve ser preenchido os seguintes campos obrigatórios:

|    |  Campos Obrigatórios   					| 		|    
|----|------------------------------------------|-------|
| a) |  Nome       		                		|		|
| b) |  Nº Mecanográfico                   		|		|
| c) |  E-mail				              		|		|
| d) |  Perfil                          		| 		|

Os perfis disponíveis para novos utilizadores são:

* **Administrador da Entidade** - Utilizadores que administram a entidade. Têm permissões para criar e editar utilizadores.
* **Administrativo da Entidade** - Utilizadores que pertencem à entidade mas não administram a mesma. Têm permissões para consultar/codificar/simular episódios, consultar relatórios e de auditoria.

No final da edição, para gravar as alterações, o utilizador deve clicar no botão **GUARDAR**. Após clicar irá ser notificado com o resultado da operação.


### 5.2 Pesquisa de utilizadores
<div id="pesquisa-de-utilizadores"></div>

Para consultar por utilizadores existentes na entidade hospitalar, deve-se clicar no botão **PESQUISAR**.
Adicionalmente, estes utilizadores podem ser filtrados por nome de utilizador, perfil ou estado.

Os perfis disponíveis para pesquisa são:

* **Administrador da Entidade** - Utilizadores que administram a entidade. Têm permissões para criar e editar utilizadores.
* **Administrativo da Entidade** - Utilizadores que pertencem à entidade mas não administram a mesma. Têm permissões para consultar/codificar/simular episódios, consultar relatórios e de auditoria.

Os estados disponíveis para pesquisa são:

* **Ativo** - Utilizadores que pertencem à entidade e que podem aceder ao sistema.
* **Bloqueado** - Utilizadores que pertencem à entidade e que foram bloqueados de aceder ao sistema.

A pesquisa realizada apenas devolve utilizadores relativos à entidade hospitalar do utilizador que efetuou a pesquisa.

A [](#figPesquisaUtilizadores) ilustra como exemplo uma pesquisa de utilizadores efetuada por um administrador do Hospital Espírito Santo, EPE - Évora.

![figPesquisaUtilizadores](img/pages/5_2_1.jpg)

<p class="caption" id="figPesquisaUtilizadores">Pesquisa de utilizadores</p>


### 5.3 Edição de utilizadores
<div id="edicao-de-utilizadores"></div>

Após efetuar a pesquisa de utilizadores ([5.2. Pesquisa de utilizadores](#pesquisa-de-utilizadores)), e ao seleccionar um utilizador devolvido pela mesma ([](#figPesquisaSeleccaoUtilizadores)),

![figPesquisaSeleccaoUtilizadores](img/pages/5_3_1.jpg)

<p class="caption" id="figPesquisaSeleccaoUtilizadores">Pesquisa e seleção de um utilizador</p>

as opções seguintes opções tornam-se disponíveis:

* **EDITAR** - Permite a edição do utilizador seleccionado;
* **REMOVER** - Remove o utilizador seleccionado do sistema;
* **ATIVAR** - Ativa o acesso ao sistema do utilizador de seleccionado, caso ele esteja bloqueado. Encontra-se inativa se o utilizador seleccionado já estiver ativo.
* **BLOQUEAR** - Bloqueia o acesso ao sistema do utilizador seleccionado, caso ele esteja ativo. Encontra-se inativa se o utilizador seleccionado já estiver bloqueado.

