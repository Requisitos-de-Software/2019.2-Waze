## 1. Introdução

<p align="justify">
Explicitar os requisitos do aplicativo, abrangendo requisitos de usabilidade, confiabilidade, suportabilidade, desempenho, além de outros requisitos como sistemas operacionais, restrições de Design, interfaces e licenciamento. </p>

## 2. Escopo

<p align="justify">O Waze desenvolve soluções práticas que possibilitam às pessoas fazer escolhas melhores, como pegar a rota mais rápida, sair na hora certa e dividir caronas diariamente.</p>

## 3.  Funcionalidades

<p align="justify">As funcionalidades elicitadas estão disponíveis nas documentações presentes em [Waze Documentação](https://requisitos-de-software.github.io/2019.2-Waze/).</p>

## 4.  Usabilidades

### Interface gráfica simples e minimalista

<p align="justify">O Waze possui um interface gráfica bem simples e minimalista possibilitando que o usuário tenha facilidade no uso e  uma aprendizagem mais rapida, além disso seu design é bastante intuitivo.</p>

### Facilidade no uso

<p align="justify">O usuário tem a suas disposição divessas funcionalidades bem descritas e intuitivas. O usuário realiza a execução de alguma tarefa em no máximo 10 clicks.</p>

### Curva de Aprendizado

<p align="justify">Por possuir uma interface bastante intuitiva e descritiva, usuários tem um aprendizado rápido.Possuindo uma curva de aprendizado pequena.</p>

### Conhecimentos prévios

<p align="justify">A aplicação exige que o usuário tenha conhecimento básico no sistema operacional do seu dispositivo(Android ou IOS).</p>

### Cores

A interface gráfica possui cores para que ajude na identificação dos itens
desejados.

### Feedbacks

O sistema deve dar feedbacks ao usuário, de forma que o usuário seja sempre informado sobre sua ação na aplicação.


## 5.  Confiabilidade

### Disponibilidade

Os servidores devem estar sempre disponíveis(24 horas por dia, 7 dias da semana).

## Integridade dos Dados
Os dados mostrados na aplicação devem estar condizentes com o que está no banco de dados da aplicação.

## Privacidade dos Dados
Os dados pessoais do usuários devem ser mantidos seguros, para manter a privacidade do mesmo.

## Transparência
O aplicativo deve deixar transparente todas informaçoes coletadas do usuário sobre como serão usadas.

## 6.  Suportabilidade

### Internet

<p align="justify">A Waze deve ser capaz de funcionar em aparelhos sem acesso à internet, com funcionalidades reduzidas(mantendo outras essencias como localização aproximada,Informações sobre o trajeto, etc). </p>

### Compatibilidade

Dispositivo|Informação
--------|------
**Android**|O aplicativo Waze requer uma versão do sistema Android igual ou superior à 4.1.<br>Rastro: [Waze Play Store](https://play.google.com/store/apps/details?id=com.waze&hl=pt_BR)
**Apple**|O aplicativo Waze requer uma versão do sistema IOS igual ou superior à 10.0. Além disso é compativel com o iPhone, iPad e iPod touch.<br>Rastro:[Waze Apple Store](https://apps.apple.com/br/app/waze-gps-e-tr%C3%A2nsito-ao-vivo/id323229106)

### Permanência de dados

O aplicativo deve salvar os dados de acordo com as preferências do usuário.

## 7.  Desempenho

### Armazenamento

O aplicativo Waze tem o tamanho de 81 MB(Megabytes) no sistema Android e 166,6 MB nos sistemas iOS.
Rastro: [Waze Play Store](https://play.google.com/store/apps/details?id=com.waze&hl=pt_BR)/[ Waze Apple Store](https://apps.apple.com/br/app/waze-gps-e-tr%C3%A2nsito-ao-vivo/id323229106)

### Localização

<p align="justify">O aplicativo necessita que o aparelho estaja com o sistema de localização(GPS) ligado para que tenha maior precisão de sua localização. Caso contrário será mostrada a localização aproximada do aparelho.  </p>


## 8.  Restrições de Design

### Idiomas

O aplicativo tem suporte à uma grande variedade de idiomas, tendo como padrão o idioma local.

## 9.  Interfaces

A interface do aplicativo é desenvolvida voltada para aplicativos Mobile: iOS e Android.

## 10.  Licenciamento

<p align="justify">Software Waze v2.x é distribuído sobre Licença Pública Geral GNU v2. A versão 3 do programa Waze houve mudança para uma licença proprietária. A última fonte aberta da versão do cliente para iPhone é 3.9.2, para Android é 3.9.4.0.
Os usuários estão sujeitos às leis de direitos autorais. Disponíveis no <a href= "https://www.waze.com/pt-BR/legal/tos">termos de uso</a>.</p>

### 11. Referências 

>Waze - GPS, Mapas, Alertas, Trânsito em Tempo Real, Disponível em:https://play.google.com/store/apps/details?id=com.waze&hl=pt_BR

>Waze – GPS e Trânsito ao vivo,Disponível em:https://apps.apple.com/br/app/waze-gps-e-tr%C3%A2nsito-ao-vivo/id323229106

<a href="https://wiki.waze.com/wiki/Brasil"> SITE: Wikiwaze</a>, acesso disponível em 25/09/2019.


## 12. Histórico de Versões
|Data|Versão|Informação|Autor(es)|
|:----:|:----:|:----:|:----:|
| 25/09/19 |  1.0   | Documento de Especificaçõ Suplementar | Guilherme Leal e Moacir Mascarenha |
|27/09/19|2.0|Atualizado documento|Guilherme Leal e Moacir Mascarenha|
|27/09/19|2.1| Revisão e atualização|Guilherme Leal e Moacir Mascarenha|
|16/10/19|3.0| Atualizado a Confiabilidade|Lucas Alexandre |