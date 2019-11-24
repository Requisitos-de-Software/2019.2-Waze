# Casos de uso

## 1. Introdução
O *diagrama de casos de uso* documenta o que o sistema faz do ponto de vista do usuário, descrevendo as principais funcionalidades do sistema e sua interação com os usuários. Nesse diagrama não nos aprofundamos em detalhes técnicos que dizem como o sistema faz.

## 2. Casos de uso :

## Versão 2

### **UC01 - Buscar Rota ( Para onde? )**

[![Buscar rota](img/caso1.png)](img/caso1.png)

| UC1 | informações | 
|:----:|:------:|
|**Caso de uso**|Buscar Rota|
|**Data**|16/11/19|
|**Hora**|16:00|
|**Autor(es)**|Matheus de Cristo, Moacir Mascarenha|
|**Ator**| Usuário|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> |
|**Fluxo alternativo**|**FA1**:<br> - Usuário abre localização(no Waze) recebida em outro App.<br> - O usuário recebe a rota até a localização<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário adiciona a rota aos favoritos<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário escolhe a opção de navegação|
|**Versão**| Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc01-buscar-rota-para-onde_1)|
|**Software Utilizado**|Draw.io| 

### **UC02 - Informações sobre o veículo**

[![Inforções veiculo](img/Cadastrar_informaçoes_sobre_o_carro.png)](img/Cadastrar_informaçoes_sobre_o_carro.png)

| UC02 | informações | 
|:----:|:------:|
|**Caso de uso**|Informações sobre o veículo|
|**Data**|26/09/19|
|**Hora**|15:38|
|**Autor(es)**|João Pedro, Matheus Estanislau|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Usuário indica tipo de veiculo |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Tipo de combustivel<br> **FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Placa do veículo<br> - Usuário digita placa de seu veiculo <br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Mais opções de rotas|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc02-informacoes-sobre-o-veiculo_1)|
|**Software Utilizado**|Lucidchart|

### **UC03 - Exibição de mapa**
[![Exibição de mapa](img/Exibicao_de_mapa2.png)](img/Exibicao_de_mapa2.png)

| UC03 | informações | 
|:----:|:------:|
|**Caso de uso**|Exibição de mapa|
|**Data**|26/09/19|
|**Hora**|16:25|
|**Autor(es)**|Matheus de Cristo, Moacir Mascarenha|
|**Ator**|Usuário|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa<br>- Usuário escolhe umas das opções de exibir no mapa<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br> - Usuário pressiona a label Velocimetro<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br>- Outras Opções<br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc03-exibicao-de-mapa_1)|
|**Software Utilizado**|Draw.io|


### **UC04 - Navegação**

[![Navegação](img/navegacao_caso_de_uso2.png)](img/navegacao_caso_de_uso2.png)

| UC04 | informações | 
|:----:|:------:|
|**Caso de uso**|Navegação|
|**Data**|16/11/19|
|**Hora**|19:26|
|**Autor(es)**|Matheus de Cristo, Moacir Mascarenha|
|**Ator**|Usuário|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Navegação<br> - Usuário acessa menu de preferencias|
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Navegação<br> - Usuário acessa o menu de Preferências<br> - Usuário escolhe alguma das opções(Evitar pedágio, passes de pedágio, Evitar balsas, Evitar vias expressas, Vias de terra e Evitar conversões difíceis)<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br> - Usuário pressiona detalhes do veículo<br> -Usuário especifica detalhes sobre veículo <br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc04-navegacao_1) |
|**Software Utilizado**|Draw.io|

### **UC05 - Economia de bateria**
[![economia_de_bateria](img/economia_bateria2.png)](img/economia_bateria2.png)

| UC05 | informações | 
|:----:|:------:|
|**Caso de uso**|Economia de bateria|
|**Data**|16/11/19|
|**Hora**|15:30|
|**Autor(es)**| Matheus de Cristo, Moacir Mascarenha|
|**Ator**|Usuário|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Economia de bateria
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Deixar ligado ao recarregar<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Economia de bateria<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Ligar durante o percurso atual <br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc05-economia-de-bateria_1)|
|**Software Utilizado**|Draw.io|

### UC06 - Voz e som

[![voz e som](img/som_e_voz_casos_de_uso2.png)](som_e_voz_casos_de_uso2.png)

| UC06 | informações | 
|:----:|:------:|
|**Caso de uso**|Voz e som|
|**Data**|16/10/19|
|**Hora**|16:13|
|**Autor(es)**| Matheus de Cristo, Moacir Mascarenha|
|**Ator**|Usuário|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Voz e som
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Sons<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Voz Waze<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Idioma de entrada.<br>**FA4:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Som<br>**FA5:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Mostrar tocador de áudio<br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc06-voz-e-som_1) |
|**Software Utilizado**|Draw.io|

### UC07- Notificações
[![notificações](img/notificacao_caso_de_uso2.0.png)](notificacao_caso_de_uso2.0.png)

| UC07 | informações | 
|:----:|:------:|
|**Caso de uso**|Notificações|
|**Data**|13/10/19|
|**Hora**|04:18|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção Push<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção E-mail<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção Texto<br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc07-notificacoes)|
|**Software Utilizado**|Draw.io|


### UC08- Geral
[![geral]()]()

| UC08 | informações | 
|:----:|:------:|
|**Caso de uso**|Geral|
|**Data**|13/10/19|
|**Hora**|03:14|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Idioma<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Unidades<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Atualizar mapa da minha área<br>**FA4:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Personalização de anúncios<br>**FA5:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Impedir bloqueio<br>**FA6:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Manter Waze no topo<br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc08-geral)|
|**Software Utilizado**|Draw.io|

### UC09- Postos de Combustível

[![postos]()]()

| UC08 | informações | 
|:----:|:------:|
|**Caso de uso**|Postos de Combustível|
|**Data**|13/10/19|
|**Hora**|03:32|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível<br>- Usuário acessa a opção Tipo de combustível<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível<br>- Usuário acessa a opção Ordenar por<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível por<br>- Usuário acessa a opção Ordenar postos<br>|
|**Versão**|Atual: 2.0 <br> Anterior: [1.0](https://requisitos-de-software.github.io/2019.2-Waze/CasoDeUso/#uc09-postos-de-combustivel|
|**Software Utilizado**|Draw.io|

## Versão 1


### **UC01 - Buscar Rota ( Para onde? )**

[![Buscar rota](img/diagrama_de_caso_de_uso.png)](img/diagrama_de_caso_de_uso.png)

| UC01 | informações | 
|:----:|:------:|
|**Caso de uso**|Buscar Rota|
|**Data**|25/09/19|
|**Hora**|23:33|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> |
|**Fluxo alternativo**|**FA1**:<br> - Usuário abre localização(no Waze) recebida em outro App.<br> - O usuário recebe a rota até a localização<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário adiciona a rota aos favoritos<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário escolhe a opção de navegação|
|**Versão**|Atual: 1.0 |
|**Software Utilizado**|Draw.io| 

### **UC02 - Informações sobre o veículo**

[![Inforções veiculo](img/Cadastrar_informaçoes_sobre_o_carro.png)](

| UC02 | informações | 
|:----:|:------:|
|**Caso de uso**|Informações sobre o veículo|
|**Data**|26/09/19|
|**Hora**|15:38|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Usuário indica tipo de veiculo |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Tipo de combustivel<br> **FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Placa do veículo<br> - Usuário digita placa de seu veiculo <br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão "informação do carro"<br> - Mais opções de rotas|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Lucidchart|




### **UC03 - Exibição de mapa**
[![Exibição de mapa](img/Exibição_de_mapa.png)](img/Exibição_de_mapa.png)

| UC03 | informações | 
|:----:|:------:|
|**Caso de uso**|Exibição de mapa|
|**Data**|26/09/19|
|**Hora**|18:55|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa<br>- Usuário escolhe umas das opções de exibir no mapa<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br> - Usuário pressiona a label Velocimetro<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br>- Outras Opções<br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|


### **UC04 - Navegação**

[![Navegação](img/navegacao.png)](img/navegacao.png)

| UC04 | informações | 
|:----:|:------:|
|**Caso de uso**|Navegação|
|**Data**|26/09/19|
|**Hora**|19:26|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Navegação<br> - Usuário acessa menu de preferencias|
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Navegação<br> - Usuário acessa o menu de Preferências<br> - Usuário escolhe alguma das opções(Evitar pedágio, passes de pedágio, Evitar balsas, Evitar vias expressas, Vias de terra e Evitar conversões difíceis)<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona exibição de mapa <br> - Usuário pressiona detalhes do veículo<br> -Usuário especifica detalhes sobre veículo <br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|

### **UC05 - Economia de bateria**
[![economia_de_bateria](img/caso_de_uso_economia_de_bateria.png)](img/caso_de_uso_economia_de_bateria.png)

| UC05 | informações | 
|:----:|:------:|
|**Caso de uso**|Economia de bateria|
|**Data**|07/10/19|
|**Hora**|06:00|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Economia de bateria
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Deixar ligado ao recarregar<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Economia de bateria<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Economia de bateria<br> - Usuário acessa a opção Ligar durante o percurso atual <br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|

### UC06 - Voz e som

[![voz e som](img/caso_de_uso_voz_e_som.png)](img/caso_de_uso_voz_e_som.png)

| UC06 | informações | 
|:----:|:------:|
|**Caso de uso**|Voz e som|
|**Data**|07/10/19|
|**Hora**|06:10|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona Voz e som
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Sons<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Voz Waze<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Idioma de entrada.<br>**FA4:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Som<br>**FA5:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> -  Usuário pressiona Voz e som<br> - Usuário acessa a opção Mostrar tocador de áudio<br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|


### UC07- Notificações
[![notificações](img/notificacao_caso_de_uso.png)](img/notificacao_caso_de_uso.png)

| UC07 | informações | 
|:----:|:------:|
|**Caso de uso**|Notificações|
|**Data**|13/10/19|
|**Hora**|04:18|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção Push<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção E-mail<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Notificações<br>- Usuário acessa a opção Texto<br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|


### UC08- Geral
[![geral](img/geral_caso_de_uso.png)](img/geral_caso_de_uso.png)

| UC08 | informações | 
|:----:|:------:|
|**Caso de uso**|Geral|
|**Data**|13/10/19|
|**Hora**|03:14|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Idioma<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Unidades<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Atualizar mapa da minha área<br>**FA4:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Personalização de anúncios<br>**FA5:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Impedir bloqueio<br>**FA6:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Geral<br>- Usuário acessa a opção Manter Waze no topo<br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|


### UC09- Postos de Combustível

[![postos](img/postos_de_combustivel_caso_de_uso.png)](img/postos_de_combustivel_caso_de_uso.png)

| UC08 | informações | 
|:----:|:------:|
|**Caso de uso**|Postos de Combustível|
|**Data**|13/10/19|
|**Hora**|03:32|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível<br>- Usuário acessa a opção Tipo de combustível<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível<br>- Usuário acessa a opção Ordenar por<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário pressiona botão de configurações<br> - Usuário pressiona a opção de Postos de Combustível por<br>- Usuário acessa a opção Ordenar postos<br>|
|**Versão**|Atual: 1.0|
|**Software Utilizado**|Draw.io|






## 3. Referências Bibliográficas
>O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML, Disponível em:
https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408

>Editor gráfico online , Disponível em: https://www.draw.io/

>Revisão e compartilhamento de gráficos e diagramas, Disponível em: https://www.lucidchart.com


## 4. Histórico de Versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|25/09/19|1.0| Criado documento |João Pedro, Moacir Mascarenha|
|26/09/19|2.0| Ajustado UC01 |João Pedro, Moacir Mascarenha|
|26/09/19|2.1|Adicionado UC02 |João Pedro, Moacir Mascarenha|
|26/09/19|2.2|Adicionado UC03 |João Pedro, Moacir Mascarenha|
|27/09/19|2.3|Adicionado UC04 |João Pedro, Moacir Mascarenha|
|07/10/19|2.4|Atualizado UC02, UC03,UC04 |Moacir Mascarenha|
|07/10/19|2.5|Adicionado UC05 e UC06 | Moacir Mascarenha|
|16/10/19|2.6|Adicionado UC07,UC08 e UC09 | Moacir Mascarenha|
|17/11/19|3.0|Adicionado Versão 2 | Matheus Estanislau, Moacir Mascarenha|
|23/11/19|4.0|Ajjustados Casos de Uso de acordo com a verificação| João Pedro Matheus Estanislau |