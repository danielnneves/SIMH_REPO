---
layout: default
title: "Acoes Bloco"
---


---
<div id="acoesBloco"></div>

# 13. Ações em bloco

Este módulo tem como objetivo agilizar a mudança de estado dos episódios, permitindo-o fazer em bloco. O utilizador pode exercer ações sobre 25 episódios de cada vez.

Para aceder, o utilizador deve, a partir da página inicial, aceder ao módulo de "Ações Bloco", tal como ilustra a figura [](#figAcessoAcoesBloco). 

![figAcessoAcoesBloco](img/pages/14_1.jpg) 

<p class="caption" id="figAcessoAcoesBloco">Módulo de Ações em Bloco</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figAcoesBloco](img/pages/14_2.jpg)

<p class="caption" id="figAcessoAcoesBloco">Página Inicial das Ações em Bloco</p>

Este módulo apenas pesquisa por episódios no estado de **Rascunho**, **Por Codifcar** ou **Em Auditoria**, permitindo as seguintes alterações:
O utilizador será obrigado a preencher sempre o filtro do **Estado**, poderá ou não selecionar um dos outros filtros.

|  		Alterações de Estados			                ||    
|------------------------------|----------------------------|
| **Estado Atual do Episódio**| **Alterações Possíveis do Episódio**|
|------------------------------|----------------------------|
| Rascuhno	    	     	   | Finalizar <br> Auditar     |
| Por Codificar   			   | Não Codificável    	    |
| Em_Auditoria	 			   | Finalizar           	    |

**Há dois pontos importantes a ter em conta neste módulo:*

* Para que os episódios em rascunho apareçam na pesquisa, têm de ter passado nas validações quando foram criados, ou seja, têm de ser considerados rascunhos válidos.

* No caso de o utilizador pretender alterar o estado de **"Por Codificar"** para "Não Codificável", terá de preencher a **causa de não codificar**. A causa escolhida será aplicada a todos os episódios selecionados.

 
Após realizar a pesquisa, os resultados ficaram visíveis de acordo com a seguinte figura:

![figResultadosAcoesBloco](img/pages/14_3.jpg) 

<p class="caption" id="figResultadosAcoesBloco">Lista de Resultados das Ações em Bloco</p>
Existe ainda o campo **"Alterar estado para"** de preenchimento obrigatório. Aqui o utilizador deverá selecionar o estado para a qual pretende alterar os episódios da lista de resultados.
Após escolher o estado a alterar, deverá selecionar os episódios que pretende modificar. Se pretender modificar todos, então no local das descrições da coluna (Selecionar) poderá selecionar todos de uma vez.

De seguida, ao selecionar o botão **Alterar**, os episódios selecionados ficaram com a alteração respetiva.

O utilizador poderá também consultar os detalhes de um determinado episódio. O botão **Consultar** ficará disponível ao selecionar um episódio da lista de resultados, como demonstra a seguinte figura.

![figDetalhesAcoesBloco](img/pages/14_4.jpg) 

<p class="caption" id="figResultadosAcoesBloco">Consulta de Episódios</p>

Quando selecionado o botão de consulta o utilizador é enviado para o detalhe do episódio ([6.2. Consulta de um episódio](#codificacao-consulta-de-episodios))
