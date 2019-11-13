# Backward-From

## Introdução

<p align = "justify">
A  rastreabilidade  de  requisitos  pode  ser  vista  como  a  habilidade  de  acompanhar  e  descrever a vida de um requisito, em ambas as direções; pré-rastreabilidade documenta  a  o  contexto  a  partir  do  qual  emergem  os  requisitos;  pós-rastreabilidade  vincula  os  requisitos  ao  desenho  do  sistema  e  sua  implementação  (DAVIS, 1993).

Um requisito é rastreável se é possível descobrir quem sugeriu o requisito (a fonte), por que o requisito existe (rationale), que outros requisitos estão relacionados a ele (dependência entre requisitos), e como o requisito se relaciona com outras informações, tais como desenho do sistema, implementação e documentação (SOMMERVILLE, 1998).

A  rastreabilidade  backward-from (para trás) liga os requisitos elicitados às suas fontes.
</p>

## Matriz de Rastreabilidade

|ID|Requisito|Brainstorming(BS)|Entrevista(ENT)|Introspecção(INS)|Questionário(Q)|Storytelling(ST)|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|RQ01|O aplicativo deve indicar rotas de acordo com preferencias pré selecionadas pelo usuário|BS20|ENT01|-|-|ST04|
|RQ02|O aplicativo deve informar sobre as condições da via|BS04|ENT02|-|Q01,Q04,Q05|-|
|RQ03|O usuário pode dar feedback sobre as condições do seu percurso|-|ENT03|-|-|ST05|
|RQ04|O aplicativo deve auxiliar a navegação por um guia de áudio|-|ENT04|-|-|-|
|RQ05|O aplicativo deve informar a localização atual do usuário|BS01|-|-|-|-|
|RQ06|O usuário deve definir locais favoritos|BS02|-|-|-|-|
|RQ07|O aplicativo deve mostrar estabelecimentos importantes para o motorista|BS03|-|-|Q06|ST02|
|RQ08|O aplicativo deve fornecer informações sobre as condições da pista|BS04|ENT02|-|Q01,Q04,Q05|-|
|RQ09|O aplicativo deve sugerir a menor rota|BS05|-|-|-|ST04|
|RQ10|O aplicativo deve sugerir o tempo aproximado de rota|BS06||||ST03|
|RQ11|O aplicativo deve ter a opção para mudar a rota a qualquer momento|BS07|-|-|-|-|
|RQ12| aplicativo deve disponibilizar uma funcionalidade para economia de bateria|BS08|-|-|-|-|
|RQ13|O aplicativo deve ter um sistema de chat|BS09|-|-|-|-|
|RQ14|O aplicativo deve ter integração com aplicativos de streaming|BS10|-|-|Q02|-|
|RQ15|O aplicativo deve ter o mapa atualizado|BS11|-|-|Q05|-|
|RQ16|O usuário deve ser capaz de avaliar feedback de outros usuários|BS13|-|-|-|-|
|RQ17|O aplicativo deve ser leve o suficiente para ter um bom desempenho na maioria dos dispositivos|BS14|-|-|-|-|
|RQ18|O aplicativo deve intuitivo e agradável|BS15|-|INS04|-|-|
|RQ19|O aplicativo deve ter suporte offline|BS16|-|INS03|Q03|-|
|RQ20|O aplicativo deve ter suporte para anúncios|BS17|-|-|-|-|
|RQ21|O usuário deve ser capaz de editar informações no mapa|BS18||INS00|Q05||
|RQ22|O aplicativo deve ter opção de evitar algumas situações durante o percurso|BS19|-|-|-|-|
|RQ23|O aplicativo deve poder definir suas preferências de percurso|BS20|ENT01|-|-|-|
<!-- |RQ24|||||||
|RQ25|||||||
|RQ26|||||||
|RQ27||||||| -->

## Referência Bibliográfica
> DAVIS, A. M.; Software   Requirements:   Objects,   Functions   and   States. Englewood Cliffs, New Jersey: Prentice Hall. 1993. 

> SOMMERVILLE, I.; Software Engineering. Addison-Wesley, Reading, MA, 1998.

> SAYÃO, M., LEITE, J. C. S. P.; Rastreabilidade de Requisitos. Monografia em Ciências da Computação, No. 20/05. Departamento de Informática, PUC-RJ, Rio de Janeiro, 2005. Disponível em: http://www.dbd.puc-rio.br/depto_informatica/05_20_sayao.pdf 

## Histórico de Versões

|Data|Versão|Descrição|Autor(es)|
|----|------|---------|---------|
|10/11/19|1.0|Criação do documento|Moacir Mascarenha, Renan Cristyan|
|10/11/19|2.0|Preenchida parcialmente a tabela|João Pedro, Moacir Mascarenha|
|10/11/19|3.0|Preenchida Matriz de Rastreabilidade|João Pedro, Moacir Mascarenha, Renan Cristyan|