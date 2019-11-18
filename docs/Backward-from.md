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
|RQ03|O usuário pode dar feedback sobre as condições do seu percurso|BS13|ENT03|INS02|-|ST05|
|RQ04|O aplicativo deve auxiliar a navegação por um guia de áudio|-|ENT04|-|-|-|
|RQ05|O aplicativo deve informar a localização atual do usuário|BS01|-|-|-|-|
|RQ06|O usuário deve definir locais favoritos|BS02|-|-|-|-|
|RQ07|O aplicativo deve mostrar estabelecimentos importantes para o motorista|BS03|-|-|Q06|ST02|
|RQ08|O aplicativo deve fornecer informações sobre as condições da pista|BS04|ENT02|-|Q01,Q04,Q05|-|
|RQ09|O aplicativo deve sugerir a menor rota|BS05|-|-|-|ST04|
|RQ10|O aplicativo deve sugerir o tempo aproximado de rota|BS06||||ST03|
|RQ11|O aplicativo deve ter a opção para mudar a rota a qualquer momento|BS07|-|-|-|-|
|RQ12|O aplicativo deve disponibilizar uma funcionalidade para economia de bateria|BS08|-|-|-|-|
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
|RQ24|Precisão de rotas|BS18|-|INS00|Q05|-|
|RQ25|Mudança de Interface|-|-|INS01|-|-|
|RQ26|Veracidade de Informações de usuários|BS13|ENT03|INS02|-|ST05|
|RQ27|O aplicativo deve consumir menos rede de dados / opção offline|BS16|-|INS03|Q03|-|
|RQ28|Design mais intuitivo|BS15|-|INS04|-|-|
|RQ29|Integração com redes sociais|BS10|-|INS05|Q02|-|
|RQ30|Aumentar tamanho (km) de rotas|-|-|INS06|-|-|
|RQ31|Cadastro de usuário e login|INS07|-|-|-|-|
|RQ32|A aplicação tem que solicitar ao usuário que ele digite o trajeto do destino|-|-|INS08|-|-|
|RQ33|A aplicação tem que solicitar ao usuário um destino|-|-|-|INS08,INS09|-|
|RQ34|Validar endereço|-|-|INS10|-|-|
|RQ35|O usuário tem que receber dicas de lugares para que ele possa ir caso tenha digitado metade do endereço ou o endereço errado|-|-|INS11|-|-|
|RQ36|O aplicativo deve informar ao usuário sobre o engarrafamento|BS19|ENT03|-|Q01,Q04,Q05| ST01|
|RQ37|O aplicativo deve informar sobre estabelecimentos de interesse para motoristas|BS03|-|-|Q06|ST02|
|RQ38|O aplicativo de informar o tempo do percurso|BS06||||ST03|
|RQ39|O aplicativo deve calcular a melhor rota para o destino desejado pelo usuário|BS05|-|-|-|ST04|
|RQ40|O aplicativo deve conter uma area comum para feedback do usuário|BS13|ENT03|INS02|-|ST05|
|RQ41|O usuário deve ser informado sobre acontecimentos em sua rota|BS04|ENT02|-|Q01,Q04,Q05|-|
|RQ42|O aplicativo deve ter conexão com um aplicativo de mídia|BS10|-|-|Q02|-|
|RQ43|A navegação deve funcionar offline|BS16|-|INS03|Q03|-|
|RQ44|O usuário deve receber informações sobre a via|BS04,BS19|ENT02|-|Q01,Q04,Q05|-|
|RQ45|O usuário deve informar eventos na sua rota|BS04,BS19|ENT02|-|Q01,Q04,Q05|-|
|RQ46|	O usuário deve ser informado sobre estabelicimentos próximos|BS03|-|-|Q06|ST02|

<!-- |RQ||||||| -->

<!-- 
## RQ
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming
- Entrevista
- Introspecção
- Questionário
- Storytelling

### Elo: 

-------------------------
 -->

<!--
Links

Brainstorming (https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
Entrevista    (https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
Introspecção  (https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#3-requisitos-elicitados)
Questionário  (https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
Storytelling  (https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)
-->

## RQ01
### Categoria:
- Desenvovimento

### Elementos Rastreáveis:
- Brainstorming [BS20](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT01](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Storytelling [ST04](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Satisfação: BS20 satisfaz ENT01
- Agregação: ST04 agrega ENT01
--------------------------

## RQ02
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo:
- Agregação: BS04 e Q05 agregam ENT02
- Satisfaz: Q01 e Q04 satisfazem ENT02
--------------------------

## RQ03
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS13](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT03](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Introspecção [INS02](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#3-requisitos-elicitados)
- Storytelling [ST05](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Agregação: BS13, INS02 e ST05 agrega ENT03
- Satisfação: ST05 satisfaz ENT03
--------------------------

## RQ04
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Entrevista [ENT04](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)

### Elo:
- Não há artefatos para constituir o elo.
---------------------------

## RQ05
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS01](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo:
- Não há artefatos para constituir o elo.
-----------------------

## RQ06
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS02](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo:
- Não há artefatos para constituir o elo.
------------------------

## RQ07
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS03](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [QS06](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Storytelling [ST02](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Satisfação: BS03 e ST02 satisfaz o Q06
-------------------

## RQ08
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo:
- Agregação: BS04 e Q05 agregam ENT02
- Satisfaz: Q01 e Q04 satisfazem ENT02
---------------------
## RQ09
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS05](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Storytelling [ST04](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Representação: BS05 reprensenta o storytelling ST04 
-------------------------


## RQ10
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS06](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Storytelling [ST03](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Satisfação: BS06 satisfaz ST03
-------------------------



## RQ11
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS07](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo: 
- Não há artefatos para constituir o elo.
-------------------------


## RQ12
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS08](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ13
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS09](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo:
- Não há artefatos para constituir o elo.

-------------------------

## RQ14
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS10](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [Q02](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo: 
- Agregação: Q02 agrega BS10
-------------------------


## RQ15
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS11](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo: 
- Agregação: Q05 agrega BS11
-------------------------

<!-- • Os principais elos de rastreabilidade são:
• Satisfação: classe origem tem dependência de satisfação com a classe
destino.
• Recurso: classe origem tem dependência de recurso com a classe
destino.
• Responsabilidade: registra a participação, responsabilidade e ação de
pessoas sobre artefatos.
• Representação: captura a representação ou modelagem dos requisitos
em outras linguagens.
• Alocado: classe origem está relacionada à classe destino, que
representa um subsistema.
• Agregação: indica “composição” de elementos. -->

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
|16/11/19|4.0|Adicionados primeiros 15 elos|João Pedro, Moacir Mascarenha, Renan Cristyan|
