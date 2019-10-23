# Casos de uso

## 1. Introdução
O *diagrama de casos de uso* documenta o que o sistema faz do ponto de vista do usuário, descrevendo as principais funcionalidades do sistema e sua interação com os usuários. Nesse diagrama não nos aprofundamos em detalhes técnicos que dizem como o sistema faz.

## 2. Casos de uso :

### **UC01 - Buscar Rota ( Para onde? )**

[![Buscar rota](img/diagrama_de_caso_de_uso.png)](img/diagrama_de_caso_de_uso.png)

| UC01 | informações | 
|:----:|:------:|
|**Caso de uso**|Buscar Rota|
|**Data**|25/09/19|
|**Hora**|23:33|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> |
|**Fluxo alternativo**|**FA1**:<br> - Usuário abre localização(no Waze) recebida em outro App.<br> - O usuário recebe a rota até a localização<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário adiciona a rota aos favoritos<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário escolhe a opção de navegação|
|**Software Utilizado**|Draw.io| 

### **UC02 - Detalhes do carro**

[![Inforções veiculo](img/Cadastrar_informaçoes_sobre_o_carro.png)](img/Cadastrar_informaçoes_sobre_o_carro.png)

| UC02 | informações | 
|:----:|:------:|
|**Caso de uso**|Detalhes do carro|
|**Data**|26/09/19|
|**Hora**|15:38|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Usuário indica tipo de veiculo |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Tipo de combustivel<br> **FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Placa do veículo<br> - Usuário digita placa de seu veiculo <br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Mais opções de rotas|
|**Software Utilizado**|Lucidchart|




### **UC03 - Exibição de mapa**
[![Exibição de mapa](img/Exibição_de_mapa.png)](img/Exibição_de_mapa.png)

| UC03 | informações | 
|:----:|:------:|
|**Caso de uso**|Exibição de mapa|
|**Data**|26/09/19|
|**Hora**|18:55|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa<br>- Usuário escolhe umas das opções de exibir no mapa<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br> - Usuário Preciona a label Velocimetro<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br>- Outras Opções<br>|
|**Software Utilizado**|Draw.io|


### **UC04 - Navegação**

[![Navegação](img/navegacao.png)](img/navegacao.png)

| UC04 | informações | 
|:----:|:------:|
|**Caso de uso**|Navegação|
|**Data**|26/09/19|
|**Hora**|19:26|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Navegação<br> - Usuário acessa menu de preferencias|
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Navegação<br> - Usuário acessa o menu de Preferências<br> - Usuário escolhe alguma das opções(Evitar pedágio, passes de pedágio, Evitar balsas, Evitar vias expressas, Vias de terra e Evitar conversões difíceis)<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br> - Usuário preciona detalhes do veículo<br> -Usuário especifica detalhes sobre veículo <br>|
|**Software Utilizado**|Draw.io|

### **UC05 - Economia de bateria**
[![economia_de_bateria](img/caso_de_uso_economia_de_bateria.png)](img/caso_de_uso_economia_de_bateria.png)

| UC05 | informações | 
|:----:|:------:|
|**Caso de uso**|Economia de bateria|
|**Data**|07/10/19|
|**Hora**|06:00|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Economia de bateria
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Economia de bateria<br> - Usuário acessa a opção Deixar ligado ao recarregar<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Economia de bateria<br> - Usuário acessa a opção Economia de bateria<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Economia de bateria<br> - Usuário acessa a opção Ligar durante o percurso atual <br>|
|**Software Utilizado**|Draw.io|

### UC06 - Voz e som

[![voz e som](img/caso_de_uso_voz_e_som.png)](img/caso_de_uso_voz_e_som.png)

| UC06 | informações | 
|:----:|:------:|
|**Caso de uso**|Voz e som|
|**Data**|07/10/19|
|**Hora**|06:10|
|**Autor(es)**| Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Voz e som
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Voz e som<br> - Usuário acessa a opção Sons<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Voz e som<br> - Usuário acessa a opção Voz Waze<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Voz e som<br> - Usuário acessa a opção Idioma de entrada.<br>**FA4:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Voz e som<br> - Usuário acessa a opção Som<br>**FA5:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> -  Usuário preciona Voz e som<br> - Usuário acessa a opção Mostrar tocador de áudio<br>|
|**Software Utilizado**|Draw.io|


## 3. Referências Bibliográficas
>O que é UML e Diagramas de Caso de Uso: Introdução Prática à UML, Disponível em:
https://www.devmedia.com.br/o-que-e-uml-e-diagramas-de-caso-de-uso-introducao-pratica-a-uml/23408

>Editor gráfico online , Disponível em: https://www.draw.io/

>Revisão e compartilhamento de gráficos e diagramas, Disponível em: https://www.lucidchart.com


## Histórico de Versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|25/09/19|1.0| Criado documento |João Pedro, Moacir Mascarenha|
|26/09/19|2.0| Ajustado UC01 |João Pedro, Moacir Mascarenha|
|26/09/19|2.1|Adicionado UC02 |João Pedro, Moacir Mascarenha|
|26/09/19|2.2|Adicionado UC03 |João Pedro, Moacir Mascarenha|
|27/09/19|2.3|Adicionado UC04 |João Pedro, Moacir Mascarenha|
|07/10/19|2.4|Atualizado UC02, UC03,UC04 |Moacir Mascarenha|
|07/10/19|2.5|Adicionado UC05 e UC06 | Moacir Mascarenha|