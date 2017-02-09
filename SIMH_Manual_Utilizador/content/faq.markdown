---
layout: default
title: "FAQ's"
---


---

<div id="faq"></div>

# FAQ's

<p class="faq"> 1. Porque não aparecem alguns episódios na pesquisa? </p>
 
Existem três hipóteses para que o episódio não surja no SIMH:

* **Hipótese 1:** O episódio em causa já se encontra codificado no WEBGDH.
* **Hipótese 2:** O episódio em causa não reúne as condições necessárias para ser codificado.
* **Hipótese 3:** Os episódios poderão não estar a integrar no SIMH, ou poderá não ser possível proceder com a codificação de episódios, devido à incongruência de informação no SONHO e no SIMH.
<br>
No seguinte ficheiro <a href="./file/SIMH_IntegraçãoSONHO.pdf">Integração SIMH-SONHO</a> podem consultar detalhadamente quais as possiveis razões de o episódio não aparecer no SIMH.
<br>
É de fazer notar que **nos mapeamentos os códigos deverão mapear um ou mais códigos do sonho para apenas um no SIMH, não sendo possível mapear um código do sonho para mais que um do SIMH.**
<br>
<br>
<p class="faq"> 2. O episódio de cirurgia de ambulatório não aparece no SIMH ?  </p>

Deverá validar o código do tipo de cirurgia, ou seja, o SIMH apenas tem em conta os episódios de cirurgia de ambulatório em que o campo COD_TIPO_CIR seja 18 (GPRSNSCIR - MRC) ou 19 (GPRSNSCIR - MRA).

Caso pretendam que estes episódios surjam no SIMH, deverão alterar os seus códigos de tipo de cirurgia.
<br>
<br>
<p class="faq"> 3. Porque as imagens aparecem desformatadas? Porque não consigo pesquisar? </p>

Valide se a versão do browser que está a ser usada é a correta para o uso da aplicação.
<br>
<br>

<p class="faq"> 4. O que fazer quando o médico codificador não está no Registo Nacional de Profissionais? </p>

Existem, na aplicação, duas maneiras de criar um médico codificador: 

* Através da associação do mesmo pelo RNP (módulo Médicos Codificadores).
* Na Gestão de Utilizadores. 

**NOTA: Apenas deverão criar o Médico Codificador NUM dos módulos acima referido e não em ambos. Apenas deverão criar um médico no módulo da Gestão de Utilizadores no caso de não conseguirem no módulo Médicos Codificadores (por não se encontrar inscrito no RNP, por exemplo).** 
**No caso de o médico não estar inscrito no RNP, deverão então criá-lo na Gestão de Utilizadores. 
Para tal, deverão colocar o tipo de utilizador como “Utilizador Médico Codificador” e não como “Utilizador Aplicacional” ou o sistema não deixará que o mesmo codifique episódios.**


<br>
<br>
<p class="faq"> 5. Como imprimir o Manual de Utilizador? </p>

*	No browser que estiver a utilizar, escolher a opção de imprimir, como mostra o exemplo abaixo:

![figGestaoEspecialidades](img/pages/imprimirManual1.png)

<p class="caption" id="figImprimirManual1">Página de entrada do módulo Gestão de Especialidades</p>

*	Irá abrir uma janela, que deverá ter a opção Print to PDF (ou semelhante):

![figGestaoEspecialidades](img/pages/imprimirManual2.png)

<p class="caption" id="figImprimirManual2">Página de entrada do módulo Gestão de Especialidades</p>

*	Depois é só salvar o documento como PDF, e a partir daqui já poderá ser impresso

![figGestaoEspecialidades](img/pages/imprimirManual3.png)

<p class="caption" id="figImprimirManual2">Página de entrada do módulo Gestão de Especialidades</p>

**NOTA: O manual encontra-se ainda em constantes modificações, pelo que se guardar uma versão do mesmo deverá ter em conta que poderá estar desatualizada**
<br>
<br>
<p class="faq"> 6. O que fazer quando o mesmo episódio aparece no SIMH e no WEBGDH?  </p>

Existirão episódios codificados no WEBGDH que irão aparecer no SIMH para codificar devido a uma questão de sincronização com os dados do SONHO.

Caso alguns destes episódios surjam na pesquisa no SIMH, mas já estejam codificados no WEBGDH, deverão marcar estes episódios para **Não Codificável** no SIMH com a causa **Codificado em ICD9CM**.

