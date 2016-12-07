---
layout: default
title: "Simulador de Codificação"
---


---
<div id="simulador"></div>

# 7. Simuladores


Através deste módulo é possível simular a codificação clínica e o agrupamento em GDH de um episódio. 
Este serve de suporte ao processo de codificação de episódios (módulo [6. Codificação do Episódio](#codificar)).

Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo "Simuladores", tal como ilustra a [](#figAcessoSimuladores).

![figAcessoSimuladores](img/pages/7_1.jpg)

<p class="caption" id="figAcessoSimuladores">Módulo Simuladores</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figSimuladores](img/pages/7_2.jpg)

<p class="caption" id="figSimuladores">Página de entrada do módulo Simuladores</p>

Esta página é composta por 5 áreas principais:

* **Tipo de Agrupador** - Nesta área deve ser feita a seleção do tipo de ICD e do agrupador a utilizar para o resto da simulação. No caso de ter sido escolhido ICD-10-CM/PCS, o agrupador a usar será necessariamente o APR (APR-DRG). Caso o ICD escolhido seja ICD9, o agrupador poderá ser alternado entre as várias opções disponíveis.
![figSimuladoresTipoAgrupador](img/pages/7_3.jpg)

* **Outros dados** - Nesta área, é possível parametrizar o episódio com informação auxiliar, tal como o sexo do paciente ou o destino após alta.
![figSimuladoresOutrosDados](img/pages/7_4.jpg)

* **Tabelas de diagnósticos e de Procedimentos** - Nesta área é possível visualizar os diagnósticos e procedimentos que vão sendo adicionados ao episódio nas suas tabelas respetivas, que inicialmente começam vazias.
![figSimuladoresTabelasVazias](img/pages/7_5.jpg)

À medida que vão sendo escolhidos e adicionados diagnósticos e procedimentos a cada tabela, passa a ser possível realizar um conjunto de operações adicionais sobre cada registo adicionado. Tomando como exemplo a seguinte imagem,
![figSimuladoresTabelasPreenchidas](img/pages/7_6.jpg)
verifica-se que os códigos adicionados podem ser removidos ao clicar em ![logo](img/remover.jpg) ou reposicionados, usando para isso a opção ![logo](img/subir.jpg) para mover o código para cima ou a opção ![logo](img/descer.jpg) para mover o código para baixo, na sua tabela respetiva.

* **Diagnósticos** - Nesta área é possível consultar os códigos de diagnósticos disponíveis segundo a versão de ICD escolhida e adicioná-los à tabela de diagnósticos.

![figSimuladoresDiagnosticosVazio](img/pages/7_7.jpg)

Tomando como exemplo a seguinte imagem,
![figSimuladoresDiagnosticosPreenchido](img/pages/7_8.jpg)
a consulta de um diagnóstico inicia-se através da escolha da letra no **Índice** ![logo](img/step1.jpg) segundo a qual o nome do diagnóstico a pesquisar se inicia.
Seguidamente, no **Detalhe do Índice** deve-se pesquisar pelo código final de diagnóstico a usar e clicar em na lupa ![logo](img/step2.jpg) para inspecioná-lo na zona de Códigos.
Nessa zona, passa a ser possível a adição desse código ![logo](img/step3.jpg) à tabela de diagnósticos.
![figSimuladoresDiagnosticosTabelaDiagnostico](img/pages/7_9.jpg)

* **Procedimentos** - Nesta área é possível consultar os códigos de procedimentos disponíveis segundo a versão de ICD escolhida e adicioná-los à tabela de procedimentos. 

![figSimuladoresProcedimentosVazio](img/pages/7_10.jpg)

Tomando como exemplo a seguinte imagem,
![figSimuladoresProcedimentosPreenchido](img/pages/7_11.jpg)
a consulta de um procedimento realiza-se escolhendo uma das opções das várias zonas disponíveis. As zonas devem ser preenchidas por esta ordem: **Section**, **Body System**, **Operation**, **Body Part**, **Approach**, **Device** e **Qualifier**.
No final do preenchimento, a descrição do procedimento escolhido estará presente na zona **ICD10 Código Procedimento**.
Nessa zona, passa a ser possível a adição desse código à tabela de procedimentos, ao clicar no botão **Adicionar**.
![figSimuladoresProcedimentosTabelaProcedimentos](img/pages/7_12.jpg)


No fim da codificação do episódio, a simulação de agrupamento do mesmo pode ser feita no botão **Simular**.

Para ser permitido ao utilizador simular o agrupamento de um episódio, este deve, pelo menos, preencher os seguintes campos obrigatórios:

|    |  Campos Obrigatórios [](#figSimuladoresAgrupamento)															| 		|    
|----|--------------------------------------------------------------------------------------------------------------|-------|
| a) |  Data de admissão                																			|		|
| b) |  Data de alta                	  																			|		|
| c) |  Destino após alta				  																			|		|
| d) |  Data de nascimento                																			| 		|
| e) |  Sexo																										|		|
| f) |  Lista de diagnósticos (adicionar pelo menos 1 diagnóstico à tabela de diagnósticos)							|		|
