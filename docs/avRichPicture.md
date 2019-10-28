# Verificação do Rich Picture

## Introdução
A verificação  um atividade onde o sistema é analizado para certificar-se que os requisitos foram atendidos. A Validação, é a certificação de que o sistema atende as necessidades e expectativas.

## Metodologia
Para realizar a verificação dos documentos de Rich Pictures, foi utilizada a técnica de inspeção. Foi definida uma checklist onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos o mais breve possível

## Rastreabilidade

[Rich Picture](https://requisitos-de-software.github.io/2019.2-Waze/richPicture/)

## Checklist
- O rich picture possui um título expressivo?
- Os atores estão bem definidos?
- A simbologia esta coerente?
- O fluxo de informações é coerente com o sentido das setas?
- A quantidade de texto é mínima?
- As ideias que necessitaram de texto foram bem explicadas?
- Os rótulos são descritos corretamente?
- Os rótulos são posicionados corretamente?
- O Rich Picture possui termos simples para que usuários não-técnicos possam compreender seu conteúdo?

## Inspeção

|Questões|RP00|RP01|RP02|RP03|
|-------|----|----|----|----|
|O rich picture possui um título expressivo?|❌|❌|❌|❌|
|Os atores estão bem definidos?|✔|✔|✔|❌|
|A simbologia esta coerente?|✔|✔|❌|✔|
|O fluxo de informações é coerente com o sentido das setas?|❌|❌|❌|❌|
|A quantidade de texto é mínima?|✔|✔|✔|✔|
|As ideias que necessitaram de texto foram bem explicadas?|✔|❌|✔|❌|
|Os rótulos são descritos corretamente?|✔|✔|❌|❌|
|Os rótulos são posicionados corretamente?|❌|❌|✔|❌|
|O Rich Picture possui termos simples para que usuários não-técnicos possam compreender seu conteúdo?|✔|✔|✔|✔|

### Observações

|Rich Picture|Observações|
|------------|-----------|
|RP00|<ul><li>Não possui um título posicionado na imagem.</li><li>Deveria haver uma seta de duas pontas indicando que há uma troca de informações entre o mapa e a localização.</li><li> A posição dos rótulos deveria ser abaixo dos símbolos, e não nas setas.</ul>|
|RP01|<ul><li>Não possui um título posicionado na imagem. </li><li>Deveria haver uma seta de duas pontas indicando que há uma troca de informações entre o mapa e a localização. </li><li> O rótulo de informações de trânsito está muito resumido e genérico, deveria ser expandido (acidentes, alertas, engarrafamentos, etc).</li><li>A posição dos rótulos deveria ser abaixo dos símbolos, e não nas setas.</li></ul>|
|RP02|<ul><li>Não possui um título posicionado na imagem.</li><li> Alguns símbolos não ficaram muito claros (relógio e sinal de wi-fi). O uso de rótulos específicos poderia resolver.</li><li>O fluxo entre o pagamento realizado pelo Waze rider, carpool e Waze driver está confuso.</li></ul>|
|RP03|<ul><li>Não possui um título posicionado na imagem.<li> Falta do rótulo especificando os atores. </li><li> O rótulo "acessa" está confuso, não ficou explícito quem acessa (não há seta apontando para este rótulo). </li><li> O uso de rótulos nos símbolos mais à esquerda facilitaria sua compreensão, não é claro o papel de cada símbolo. </li><li> Os rótulos deveriam ser posicionados abaixo dos símbolos.</li>
</ul>|

## Refências Bibliográficas
> Rich Picture, Disponível em: http://systems.open.ac.uk/materials/T552/pages/rich/richAppendix.html. Acesso em: 27 de outubro de 2019
>A Importância da validação e da verificação, Disponível em: https://www.devmedia.com.br/a-importancia-da-validacao-e-da-verificacao/24559

## Histórico de Versões
|Data|Versão|Descrição|Autor(es)|
|----|------|---------|---------|
|27/10/19|1.0|Criação do documento|Moacir Mascarenha, Renan Cristyan|