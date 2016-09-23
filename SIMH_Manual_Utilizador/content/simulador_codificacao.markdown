---
layout: default
title: "Simulador de Codificação"
---


---

# 7. Simulador de Codificação
<div id="simulador-de-codificacao"></div>

Através deste módulo é possível simular a codificação clínica de um episódio em ICD-10-CM/PCS (versão 2017). 
Este serve de suporte ao processo de codificação de um episódio (módulo [# 6. Codificação de Episódios](#codificacao-episodios)).

Para isso, o utilizador deve, a partir da página inicial, aceder ao módulo "Simulador de Codificação", tal como ilustra a [](#figSimuladorCodificacao).

![figSimuladorCodificacao](img/pages/7_1.jpg)

<p class="caption" id="figSimuladorCodificacao">Módulo Simulador de Codificação</p>

Ao aceder a este módulo, aparecerá a seguinte página:

![figSimuladorICD10](img/pages/7_2.jpg)

<p class="caption" id="figSimuladorICD10">Página de entrada do módulo Simulador de Codificação</p>

Esta página é composta por 4 áreas principais:

* **Outros dados** - Nesta área, é possível parametrizar o episódio com informação auxiliar, tal como o sexo do paciente ou o destino após alta.
![figSimuladorCodificacaoOutrosDados](img/pages/7_3.jpg)

* **Tabelas de diagnósticos e de Procedimentos** - Nesta área é possível visualizar os diagnósticos e procedimentos que vão sendo adicionados ao episódio nas suas tabelas respectivas, que inicialmente começam vazias.
![figSimuladorCodificacaoTabelasVazias](img/pages/7_4.jpg)

À medida que vão sendo escolhidos e adicionados diagnósticos e procedimentos a cada tabela, passa a ser possível realizar um conjunto de operações adicional sobre cada registo adicionado.

Tomando como exemplo a seguinte imagem,
![figSimuladorCodificacaoTabelasPreenchidas](img/pages/7_5.jpg)
verifica-se que os códigos adicionados podem ser removidos ao clicar em ![logo](img/remover.jpg) ou reposicionados, usando para isso a opção ![logo](img/subir.jpg) para mover o código para cima ou a opção ![logo](img/descer.jpg) para mover o código para baixo, na sua tabela respectiva.

* **Diagnósticos** - Nesta área é possível consultar os códigos de diagnósticos disponíveis em ICD-10 e adicioná-los à tabela de diagnósticos.

![figSimuladorCodificacaoDiagnosticosVazio](img/pages/7_6.jpg)

Tomando como exemplo a seguinte imagem,
![figSimuladorCodificacaoDiagnosticosPreenchido](img/pages/7_7.jpg)
a consulta de um diagnóstico inicia-se através da escolha da letra no **Index** ![logo](img/step1.jpg) segundo a qual o nome do diagnóstico a pesquisar se inicia.
Seguidamente, no **Detalhe do Index** deve-se pesquisar pelo código final de diagnóstico a usar e clicar em na lupa ![logo](img/step2.jpg) para inspecioná-lo na zona de Códigos.
Nessa zona, passa a ser possível a adição desse código ![logo](img/step3.jpg) à tabela de diagnósticos.
![figSimuladorCodificacaoDiagnosticosTabelaDiagnostico](img/pages/7_8.jpg)

* **Procedimentos** - Nesta área é possível consultar os códigos de procedimentos disponíveis em ICD-10 e adicioná-los à tabela de procedimentos.

![figSimuladorCodificacaoProcedimentosVazio](img/pages/7_9.jpg)

Tomando como exemplo a seguinte imagem,
![figSimuladorCodificacaoProcedimentosPreenchido](img/pages/7_10.jpg)
a consulta de um procedimento realiza-se escolhendo uma das opções das várias zonas disponíveis. As zonas devem ser preenchidas por esta ordem: **Section**, **Body System**, **Operation**, **Body Part**, **Approach**, **Device** e **Qualifier**.
No final do preenchimento, a descrição do procedimento escolhido estará presente na zona **ICD10 Código Procedimento**.
Nessa zona, passa a ser possível a adição desse código à tabela de procedimentos, ao clicar no botão **Adicionar**.
![figSimuladorCodificacaoProcedimentosTabelaProcedimentos](img/pages/7_11.jpg)
