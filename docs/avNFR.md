# NFR-Análise
 
## Introdução
A verificação é uma atividade onde o sistema é utilizado para certificar-se que os requisitos foram atendidos. A Validação, é a certificação de que o sistema atende as necessidades e expectativas.
 
## Metodologia
Para realizar a verificação dos documentos de NFR, foi utilizada a técnica de inspeção. Foi definida uma checklist onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos o mais breve possível
 
## Checklist
- Os softgoals representam metas que não têm definições claras?
- Softgoals são decompostos em operacionalizações ?
- Os relacionamentos entre os softgoals expressam as relações de influência e interdependência de uns com os outros?
- Para cada softgoal, existem mais evidências positivas do que evidências negativas?
- Os objetivos foram decompostos em uma hierarquia com AND/OR de softgoals?
- Os objetivos mais críticos foram devidamente marcados/sinalizados?
- Os graus de satisfação foram indicados?
- O sentido das setas que ligam os softgoals é coerente?
- As linhas tracejadas e contínuas foram utilizadas corretamente?
 
## Inspeção
 
|Questões|NFR00|NFR01|NFR02|NFR03|NFR04|
|--------|-----|-----|-----|-----|-----|
|Os softgoals representam metas que não têm definições claras?|✔|✔|✔|-|✔|
|Softgoals são decompostos em operacionalizações?|❌|✔|✔|✔|✔|
|Os relacionamentos entre os softgoals expressam as relações de influência e interdependência de uns com os outros?|✔|✔|✔|✔|✔|
|Para satisfazer o softgoal, existem mais evidências positivas do que evidências negativas?|✔|✔|✔|✔|✔|
|Os objetivos foram decompostos em uma hierarquia com AND/OR de softgoals?|❌|✔|✔|✔|✔|
|Os objetivos mais críticos foram devidamente marcados/sinalizados?|❌|❌|❌|❌|❌|
|Os graus de satisfação foram indicados?|✔|✔|✔|✔|✔|
|O sentido das setas que ligam os softgoals é coerente?|-|✔|✔|✔|✔|
|As linhas tracejadas e contínuas foram utilizadas corretamente?|-|✔|❌|❌|❌|
 
### Observações
 
|NFR|Observações|
|---|-----------|
|NFR00|<ul><li>Os softgoals devem ser decompostos em operacionalizações.</li><li>Os softgoals devem ser decompostos em hierarquias and/or.</li><li>Não há nenhuma indicação de quais objetivos são críticos.\</li></ul>|
|NFR01|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li></ul>|
|NFR02|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre a operalização **Modo hibernar** e o softgoal **Economia de dados**, deve ser indicada por uma seta tracejada.</li>
</ul>|
|NFR03|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre as operalizações **Suporte offline** e **Prover manutenção** e os softgoals **Dispositivos Android ou IOS**, poderiam ser indicadas por setas tracejadas.</li></ul>|
|NFR04|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre a operalização **Monitoramento** e o softgoal **Prevenir falhas**, deve ser indicada por uma seta tracejada.</li></ul>|
 
## Referências Bibliográficas
> Enhancing Data Warehouse Design with the NFR Framework. Disponível em: http://www.inf.puc-rio.br/wer02/zip/Enhancing_Data(4).pdf. Acesso em: 29/10/19
 
## Histórico de Versões
|Data|Versão|Descrição|Autor(es)|
|----|------|---------|---------|
|28/10/19|1.0|Criação do documento|Moacir Mascarenha, Renan Cristyan|


