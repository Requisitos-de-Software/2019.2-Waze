# Backward-From

## Introdução

<p align = "justify">
A  rastreabilidade  de  requisitos  pode  ser  vista  como  a  habilidade  de  acompanhar  e  descrever a vida de um requisito, em ambas as direções; pré-rastreabilidade documenta  a  o  contexto  a  partir  do  qual  emergem  os  requisitos;  pós-rastreabilidade  vincula  os  requisitos  ao  desenho  do  sistema  e  sua  implementação  (DAVIS, 1993).

Um requisito é rastreável se é possível descobrir quem sugeriu o requisito (a fonte), por que o requisito existe (rationale), que outros requisitos estão relacionados a ele (dependência entre requisitos), e como o requisito se relaciona com outras informações, tais como desenho do sistema, implementação e documentação (SOMMERVILLE, 1998).

A  rastreabilidade  backward-from (para trás) liga os requisitos elicitados às suas fontes.
</p>

## Matriz de Rastreabilidade

|ID|Requisito|Brainstorming(BS)|Entrevista(ENT)|Introspecção(INS)|Questionário(Q)|Storytelling(ST)|Análise de Protocolo(AP)|
|:--:|:--:|:--:|:--:|:--:|:--:|:--:|:--:|
|RQ01|O aplicativo deve indicar rotas de acordo com preferencias pré selecionadas pelo usuário|BS20|ENT01|-|-|ST04|AP05|
|RQ02|O aplicativo deve informar sobre as condições da via|BS04|ENT02|-|Q01,Q04,Q05|-|AP09|
|RQ03|O usuário pode dar feedback sobre as condições do seu percurso|BS13|ENT03|INS02|-|ST05|-|
|RQ04|O aplicativo deve auxiliar a navegação por um guia de áudio|-|ENT04|-|-|-|-|
|RQ05|O aplicativo deve informar a localização atual do usuário|BS01|-|-|-|-|-|
|RQ06|O usuário deve definir locais favoritos|BS02|-|-|-|-|-|
|RQ07|O aplicativo deve mostrar estabelecimentos importantes para o motorista|BS03|-|-|Q06|ST02|-|
|RQ08|O aplicativo deve fornecer informações sobre as condições da pista|BS04|ENT02|-|Q01,Q04,Q05|-|AP09|
|RQ09|O aplicativo deve sugerir a menor rota|BS05|-|-|-|ST04|-|
|RQ10|O aplicativo deve sugerir o tempo aproximado de rota|BS06|-|-|-|ST03|AP06,AP07|
|RQ11|O aplicativo deve ter a opção para mudar a rota a qualquer momento|BS07|-|-|-|-|AP10|
|RQ12|O aplicativo deve disponibilizar uma funcionalidade para economia de bateria|BS08|-|-|-|-|AP12|
|RQ13|O aplicativo deve ter um sistema de chat|BS09|-|-|-|-|-|
|RQ14|O aplicativo deve ter integração com aplicativos de streaming|BS10|-|-|Q02|-|-|
|RQ15|O aplicativo deve ter o mapa atualizado|BS11|-|-|Q05|-|AP09|
|RQ16|O usuário deve ser capaz de avaliar feedback de outros usuários|BS13|-|-|-|-|-|
|RQ17|O aplicativo deve ser leve o suficiente para ter um bom desempenho na maioria dos dispositivos|BS14|-|-|-|-|-|
|RQ18|O aplicativo deve intuitivo e agradável|BS15|-|INS04|-|-|-|
|RQ19|O aplicativo deve ter suporte offline|BS16|-|INS03|Q03|-|-|
|RQ20|O aplicativo deve ter suporte para anúncios|BS17|-|-|-|-|-|
|RQ21|O usuário deve ser capaz de editar informações no mapa|BS18|-|INS00|Q05|-|-|
|RQ22|O aplicativo deve ter opção de evitar algumas situações durante o percurso|BS19|-|-|-|-|-|
|RQ23|O aplicativo deve poder definir suas preferências de percurso|BS20|ENT01|-|-|-|-|
|RQ24|Precisão de rotas|BS18|-|INS00|Q05|-|-|
|RQ25|Mudança de Interface|-|-|INS01|-|-|-|
|RQ26|Veracidade de Informações de usuários|BS13|ENT03|INS02|-|ST05|-|
|RQ27|O aplicativo deve consumir menos rede de dados / opção offline|BS16|-|INS03|Q03|-|-|
|RQ28|Design mais intuitivo|BS15|-|INS04|-|-|-|
|RQ29|Integração com redes sociais|-|-|INS05|-|-|-|
|RQ30|Aumentar tamanho (km) de rotas|-|-|INS06|-|-|-|
|RQ31|Cadastro de usuário e login|-|-|INS07|-|-|AP02|
|RQ32|A aplicação tem que solicitar ao usuário que ele digite o trajeto do destino|-|-|INS08|-|-|-|
|RQ33|A aplicação tem que solicitar ao usuário um destino|-|-|-|INS08,INS09|-|-|
|RQ34|Validar endereço|-|-|INS10|-|-|-|
|RQ35|O usuário tem que receber dicas de lugares para que ele possa ir caso tenha digitado metade do endereço ou o endereço errado|-|-|INS11|-|-|-|
|RQ36|O aplicativo deve informar ao usuário sobre o engarrafamento|BS19|ENT03|-|Q01,Q04,Q05| ST01|-|
|RQ37|O aplicativo deve informar sobre estabelecimentos de interesse para motoristas|BS03|-|-|Q06|ST02|-|
|RQ38|O aplicativo de informar o tempo do percurso|BS06|-|-|-|ST03|AP07,AP06|
|RQ39|O aplicativo deve calcular a melhor rota para o destino desejado pelo usuário|BS05|-|-|-|ST04|-|
|RQ40|O aplicativo deve conter uma area comum para feedback do usuário|BS13|ENT03|INS02|-|ST05|-|
|RQ41|O usuário deve ser informado sobre acontecimentos em sua rota|BS04|ENT02|-|Q01,Q04,Q05|-|-|
|RQ42|O aplicativo deve ter conexão com um aplicativo de mídia|BS10|-|-|Q02|-|-|
|RQ43|A navegação deve funcionar offline|BS16|-|INS03|Q03|-|-|
|RQ44|O usuário deve receber informações sobre a via|BS04,BS19|ENT02|-|Q01,Q04,Q05|-|-|
|RQ45|O usuário deve informar eventos na sua rota|BS04,BS19|ENT02|-|Q01,Q04,Q05|-|-|
|RQ46|O usuário deve ser informado sobre estabelicimentos próximos|BS03|-|-|Q06|ST02|-|
|RQ47|O Waze deve mostrar um pequeno resumo sobre o que é o app|-|-|-|-|-|AP01|
|RQ48|O usuário deve ser capaz de utilizar o app sem fazer um cadastro/login|-|-|INS07|-|-|AP02|
|RQ49|Deve ser mostrado os termos de serviços|-|-|-|-|-|AP03|
|RQ50|O usuário deve ser capaz de informar que tipo de carro utiliza|-|-|-|-|-|AP04|
|RQ51|O usuário deve ser capaz de informar o destino|BS20|ENT01|-|-|ST04|AP05|
|RQ52|O Aplicativo deve informar o tempo do percurso|BS06|-|-|ST03|-|AP07,AP06|
|RQ53|O Aplicativo deve informar a hora de chegada no destino|BS06|-|-|ST03|-|AP07,AP06|
|RQ54|O Aplicativo deve informar a velocidade do veiculo|-|-|-|-|-|AP08|
|RQ55|O usuario deve ser capaz de informar eventos na rota, como transito, acidentes e radares|BS04|ENT02|-|Q01,Q04,Q05|-|AP09|
|RQ56|O usuário deve ser capaz de alterar a rota|BS07|-|-|-|-|AP10|
|RQ57|O usuário deve ser capaz de compartilhar sua rota|-|-|-|-|-|AP11|
|RQ58|O waze deve ter uma opção de economia de bateria|BS08|-|-|-|-|AP12|


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
- Analise de Protocolo [AP05](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Satisfação: BS20 e AP05 satisfaz ENT01
- Agregação: ST04 agrega ENT01
--------------------------

## RQ02
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Agregação: BS04,AP09 e Q05 agregam ENT02
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
O aplicativo deve fornecer informações sobre as condições da pista
## RQ08
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Agregação: BS04,AP09 e Q05 agregam ENT02
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
- Analise de Protocolo [AP06](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow) e [AP07](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Satisfação: BS06 E AP06 satisfaz ST03
- Agregação: AP07 agrega ST03
-------------------------

## RQ11
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS07](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Analise de Protocolo [AP10](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo: 
- Satisfação: AP10 satisfaz BS07
-------------------------

## RQ12
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS08](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Analise de Protocolo [AP12](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)
### Elo: 
- Satisfação: AP12 satisfaz BS08
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
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)
### Elo: 
- Agregação: Q05 e AP09 agrega BS11
-------------------------

## RQ16
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS13](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ17
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS14](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ18
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS15](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS04](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
### Elo: 
- Agregação: INS04 agrega BS15
-------------------------

## RQ19
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS16](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS03](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Questionário [Q03](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo: 
- Satisfação: INS03 e Q03 satisfaz BS16
-------------------------

## RQ20
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS17](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)

### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ21
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS18](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS00](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Questionário [Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
### Elo: 
- Agregação: BS18 e Q05 agrega INS00
-------------------------

## RQ22
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS19](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

##RQ23
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS20](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT01](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#51-moscow)
### Elo: 
- Satisfação: ENT01 satisfaz BS20
-------------------------

## RQ24
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS18](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS00](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Questionário [Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
### Elo: 
- Agregação: BS18 e Q05 agrega INS00
------------------------

## RQ25
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS1](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ26
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS13](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT03](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#51-moscow)
- Introspecção [INS02](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Storytelling [ST05](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Agregação: BS13, INS02 e ST05 agrega ENT03
- Satisfação: ST05 satisfaz ENT03
-------------------------

## RQ27
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS16](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS03](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Questionário [Q03](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
### Elo: 
- Satisfação: INS03 e Q03 satisfaz BS16
-------------------------

## RQ28
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS15](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS04](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
### Elo: 
- Agregação: INS04 agrega BS15
---------------------

## RQ29
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS05](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)

### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ30
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS06](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

## RQ31
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS07](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Analise de Protocolo [AP02](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)
 
### Elo: 
- Agregação:AP02 agrega INS07
-------------------------

## RQ32
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS08](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)[INS09](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
 
 
### Elo: 
- Agregação: INS08 agrega INS09
-------------------------

## RQ33
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS08](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)[INS09](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
 
### Elo: 
- Agregação: INS08 agrega INS09
-------------------------


## RQ34
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS10](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
 
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------


## RQ35
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS11](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
 
### Elo: 
- Não há artefatos para constituir o elo.
-------------------------

|RQ36|O aplicativo deve informar ao usuário sobre o engarrafamento|BS19|ENT03|-|Q01,Q04,Q05| ST01|-|

## RQ36
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS19](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT03](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#51-moscow)
- Questionário [Q01 Q04 Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Storytelling [ST01](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

 
### Elo: 
- Satisfação: BS29 satisfaz ST01
- Satisfação: Q01 satisfaz Q05
- Agregação: Q05 agrega Q04
- Agregação: ENT03 agrega Q01,Q05
-------------------------

## RQ37
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS03](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [QS06](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Storytelling [ST02](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Satisfação: BS03 e ST02 satisfaz o Q06
-------------------------

## RQ38
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS06](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Storytelling [ST03](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)
- Analise de Protocolo [AP06](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow) e [AP07](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Satisfação: BS06 E AP06 satisfaz ST03
- Agregação: AP07 agrega ST03

-------------------------

## RQ39
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS05](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Storytelling [ST04](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Representação: BS05 reprensenta o storytelling ST04 
-------------------------

## RQ40
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS13](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT03](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#51-moscow)
- Introspecção [INS02](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Storytelling [ST05](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Agregação: BS13, INS02 e ST05 agrega ENT03
- Satisfação: ST05 satisfaz ENT03
-------------------------

## RQ41
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Agregação: BS04,AP09 e Q05 agregam ENT02
- Satisfaz: Q01 e Q04 satisfazem ENT02

-------------------------

## RQ42
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS10](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [Q02](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)

### Elo: 
- Agregação: Q02 agrega BS10

-------------------------

## RQ43
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS16](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Introspecção [INS03](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Questionário [Q03](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
### Elo: 
- Satisfação: INS03 e Q03 satisfaz BS16

-------------------------

## RQ44
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04 BS19](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Agregação: BS04,AP09 e Q05 agregam ENT02
- Satisfaz: Q01 e Q04 satisfazem ENT02
- Agregação: BS19 agrega BS04
- Agregação: ENT02 agrega BS19 

-------------------------

## RQ45
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS04 BS19](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT02](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Questionário [Q01, Q04, Q05](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Analise de Protocolo [AP09](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Agregação: BS04,AP09 e Q05 agregam ENT02
- Satisfaz: Q01 e Q04 satisfazem ENT02
- Agregação: BS19 agrega BS04
- Agregação: ENT02 agrega BS19 
 
-------------------------

## RQ46
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Brainstorming [BS03](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Questionário [QS06](https://requisitos-de-software.github.io/2019.2-Waze/Questionario/#7requisitos-elicitados)
- Storytelling [ST02](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)

### Elo:
- Satisfação: BS03 e ST02 satisfaz o Q06
-------------------------

## RQ47
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Analise de Protocolo [AP01](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Não há artefatos para constituir o elo.
-------------------------

## RQ48
### Categoria:
- Desenvolvimento

### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Introspecção [INS07](https://requisitos-de-software.github.io/2019.2-Waze/introspeccao/#31-moscow)
- Analise de Protocolo [AP02](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)
 
### Elo: 
- Agregação:AP02 agrega INS07
-------------------------

## RQ49
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Analise de Protocolo [AP03](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Não há artefatos para constituir o elo.
-------------------------

## RQ50
### Categoria:
- Desenvolvimento

### Elementos Rastreáveis:
- Analise de Protocolo [AP04](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Não há artefatos para constituir o elo.
-------------------------

## RQ51
### Categoria:
- Desenvovimento

### Elementos Rastreáveis:
- Brainstorming [BS20](https://requisitos-de-software.github.io/2019.2-Waze/Brainstorm/#3-requisitos-levantados)
- Entrevista [ENT01](https://requisitos-de-software.github.io/2019.2-Waze/Entrevista/#5-requisitos-elicitados)
- Storytelling [ST04](https://requisitos-de-software.github.io/2019.2-Waze/Storytelling/#3-requisitos-elicitados_1)
- Analise de Protocolo [AP05](https://requisitos-de-software.github.io/2019.2-Waze/analiseProtocolo/#41-moscow)

### Elo:
- Satisfação: BS20 e AP05 satisfaz ENT01
- Agregação: ST04 agrega ENT01
--------------------------

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
|17/11/19|4.1|Adicionados elos de 15 a 30|João Pedro, Moacir Mascarenha|
|17/11/19|4.2|Adicionados elos de 31 a 51|João Pedro, Moacir Mascarenha|
