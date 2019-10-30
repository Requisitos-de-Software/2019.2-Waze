# Rich Picture - Verificação

## Introdução
<p align = "justify">
A verificação  um atividade onde o sistema é analizado para certificar-se que os requisitos foram atendidos. A Validação, é a certificação de que o sistema atende as necessidades e expectativas.
</p>

## Metodologia
<p align = "justify">
Para realizar a verificação dos documentos de Rich Pictures, foi utilizada a técnica de inspeção. Foi definida uma checklist onde cada tópico foi avaliado e os defeitos detectados foram descritos para que possam ser corrigidos o mais breve possível
</p>

## Rastreabilidade

[Rich Picture](https://requisitos-de-software.github.io/2019.2-Waze/richPicture/)

## Checklist
Justificativas baseadas em: [Complexity and rich pictures](http://leadershipforchange.org.uk/wp-content/uploads/Complexity-and-rich-pictures.pdf) e Slides de Aula

Questões|Justificativa
|-------|-------------|
|O rich picture possui um título expressivo?|O título deve ser significativo para identificação mais eficiente|
|Os atores estão bem definidos?|Os atores são usuários do sistema e é necessário ter seus papéis distinguidos|
|A simbologia esta coerente?|Os símbolos e imagens devem auxiliar a interpretação de situações reais do sistema|
|O fluxo de informações é coerente com o sentido das setas?|As conexões entre os símbolos devem ser signicativas, representando uma lógica, e os símbolos devem sempre estar conectados de alguma forma|
|A quantidade de texto é mínima?|A ideia é utilizar muitos símbolos fáceis de serem compreendidos e menos textos para explicá-los|
|As ideias que necessitaram de texto foram bem explicadas?|Caso seja necessário o uso de texto, este deve ser o mais breve e sucinto possível|
|Os rótulos são descritos corretamente?|Os rótulos devem ter bons nomes para que não seja necessário o uso de textos explicativos. Além disso, o uso de rótulos auxilia em um melhor entendimento do rich picture|
|Os rótulos são posicionados corretamente?|O posicionamento dos rótulos deve ser diretamente abaixo dos símbolos, para facilitar sua assimilação|
|O Rich Picture possui termos simples para que usuários não-técnicos possam compreender seu conteúdo?|O emprego de termos ou jargões técnicos pode dificultar o compreensão de um cliente sobre o diagrama|

## Inspeção

|Questões|RP00|RP01|RP02|RP03|
|--------|----|----|----|----|
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

## Conclusão
<p align = "justify">
A partir da verificação feita com a técnica de inspeção, foram observadas inconsistências, grande parte cosméticas, por exemplo: falta de títulos nos diagramas, rótulos mal posicionados e fluxo confuso em algumas situações.
</p>

## Refências Bibliográficas
> Rich Picture. Disponível em: http://systems.open.ac.uk/materials/T552/pages/rich/richAppendix.html. Acesso em: 27/10/19

>A Importância da validação e da verificação. Disponível em: https://www.devmedia.com.br/a-importancia-da-validacao-e-da-verificacao/24559. Acesso em: 27/10/19

>Complexity and rich pictures. Disponível em: http://leadershipforchange.org.uk/wp-content/uploads/Complexity-and-rich-pictures.pdf. Acesso em: 30/10/19

>Serrano, Milene. Serrano, Mauricio. Requisitos-Aula 04.2019, Slide 11.

>Guiabolso RichPicture. Disponível em: https://fga-disciplinas.github.io/2019.1-Guia-Bolso/analise/analise_rich_picture. Acesso em: 30/10/19

## Histórico de Versões
|Data|Versão|Descrição|Autor(es)|
|----|------|---------|---------|
|27/10/19|1.0|Criação do documento|Moacir Mascarenha, Renan Cristyan|
|30/10/19|1.1|Adicionadas justificativas|Moacir Mascarenha, Renan Cristyan|