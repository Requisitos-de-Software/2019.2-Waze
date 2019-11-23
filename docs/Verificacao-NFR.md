# NFR - Verificação
 
## 1. Introdução
A verificação é uma atividade onde o sistema é utilizado para certificar-se que os requisitos foram atendidos. A Validação, é a certificação de que o sistema atende as necessidades e expectativas.
 
## 2. Metodologia
Para realizar a verificação dos documentos de NFR, foi utilizada a técnica de inspeção. Foi definida uma checklist onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos o mais breve possível.
 
## 3. Rastreabilidade

[NFR Framework](https://requisitos-de-software.github.io/2019.2-Waze/NFR/)

## 4. Inspeção
Questões e Justificativas baseadas em:<br>
[Enhancing Data Warehouse Design with the NFR
Framework](http://www.inf.puc-rio.br/wer02/zip/Enhancing_Data(4).pdf)

|Questão|Justificativa|
|-------|-------------|
|Os softgoals representam metas que não têm definições claras?| Um softgoal representa uma meta que não tem uma definição clara e/ou critérios sobre se é satisfeita ou não.  [3. Overview of the NFR Framework -2° Paragrafo ]|
|Softgoals são decompostos em operacionalizações?|Todo softgoal deve se decompor em uma ou mais operacionalizações, e os sentidos das setas que os ligam devem ser debaixo para cima. [3. Overview of the NFR Framework -Passo 1]|
|Os relacionamentos entre os softgoals expressam as relações de influência e interdependência de uns com os outros?|Os objetivos programáticos são relacionados por meio de relacionamentos que representam a influência ou interdependência de um softgoal em outro. [3. Overview of the NFR Framework -Passo 3]|
|Para cada softgoal, existem mais evidências positivas do que evidências negativas?| Diz-se que um softgoal é "satisfeito" quando há evidência positiva e pouca evidência negativa contra ela. [3. Overview of the NFR Framework -2° Paragrafo ]|
|Os objetivos foram decompostos em uma hierarquia com AND/OR de softgoals?|Os objetivo do NFR devem ser decompostos em um hierarquia de operacionalizações and/or. [3. Overview of the NFR Framework -Passo 1]|
|Os objetivos mais críticos foram devidamente marcados/sinalizados?|Objetivos críticos devem ser sinalizados com '!' e mais críticos com '!!'. [3. Overview of the NFR Framework -4° Paragrafo]|
|Os graus de satisfação foram indicados?|A satisfação ocorre em 4 intensidades: '++'(muito satisfeito), '+'(satisfeito), '-'(insatisfeito), '--'(muito insatisfeito). [3. Overview of the NFR Framework -4° Paragrafo ]|
|O sentido das setas que ligam os softgoals é coerente?|As operacionalizações devem se ligar aos softgoals, e as setas devem ter este sentido|
|As linhas tracejadas e contínuas foram utilizadas corretamente?| As setas com linhas continuas indicam a relação de interdependência implicita e as pontilhadas as realações explicitas. [3. Overview of the NFR Framework -2° Paragrafo -Fig.2]|
 
## 5. Checklist
 
|Questões|[NFR00](https://requisitos-de-software.github.io/2019.2-Waze/NFR/#nfr00-geral)|[NFR01](https://requisitos-de-software.github.io/2019.2-Waze/NFR/#nfr01-usabilidade)|[NFR02](https://requisitos-de-software.github.io/2019.2-Waze/NFR/#nfr02-desempenho)|[NFR03](https://requisitos-de-software.github.io/2019.2-Waze/NFR/#nfr03-suportabilidade)|[NFR04](https://requisitos-de-software.github.io/2019.2-Waze/NFR/#nfr04-confiabiliade)|
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
 
## 6. Observações
 
|NFR|Observações|
|---|-----------|
|NFR00|<ul><li>Os softgoals devem ser decompostos em operacionalizações.</li><li>Os softgoals devem ser decompostos em hierarquias and/or.</li><li>Não há nenhuma indicação de quais objetivos são críticos.</li></ul>|
|NFR01|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li></ul>|
|NFR02|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre a operalização **Modo hibernar** e o softgoal **Economia de dados**, deve ser indicada por uma seta tracejada.</li></ul>|
|NFR03|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre as operalizações **Suporte offline** e **Prover manutenção** e os softgoals **Dispositivos Android ou IOS**, poderiam ser indicadas por setas tracejadas.</li></ul>|
|NFR04|<ul><li>Não há nenhuma indicação de quais objetivos são críticos.</li><li>A representação da interdependência, entre a operalização **Monitoramento** e o softgoal **Prevenir falhas**, deve ser indicada por uma seta tracejada.</li></ul>|

## 7. Conclusão
A partir da inspeção dos NFRs foi possivel identificar e catalogar deficiências nos diagramas como: o uso incorreto das setas de linhas preenchidas e a falta de indicações de softgoals criticos.
 
## 8. Referências Bibliográficas
> Enhancing Data Warehouse Design with the NFR Framework. Disponível em: http://www.inf.puc-rio.br/wer02/zip/Enhancing_Data(4).pdf. Acesso em: 29/10/19
 
## 9. Histórico de Versões
|Data|Versão|Descrição|Autor(es)|
|----|------|---------|---------|
|28/10/19|1.0|Criação do documento|Moacir Mascarenha, Renan Cristyan|
|30/10/19|1.1|Adição de justificativas|Moacir Mascarenha, Renan Cristyan|
|23/11/19|1.2|Adição das partes citadas da referências|Moacir Mascarenha|

