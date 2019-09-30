# Casos de uso

## 1. Introdução
O *diagrama de casos de uso* documenta o que o sistema faz do ponto de vista do usuário, descrevendo as principais funcionalidades do sistema e sua interação com os usuários. Nesse diagrama não nos aprofundamos em detalhes técnicos que dizem como o sistema faz.

## 2. Casos de uso :

### **UC1 - Buscar Rota ( Para onde? )**

[![Buscar rota](img/diagrama_de_caso_de_uso.png)](img/diagrama_de_caso_de_uso.png)

| UC1 | informações | 
|:----:|:------:|
|**Caso de uso**|Buscar Rota|
|**Data**|25/09/19|
|**Hora**|23:33|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> |
|**Fluxo alternativo**|**FA1**:<br> - Usuário abre localização(no Waze) recebida em outro App.<br> - O usuário recebe a rota até a localização<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário adiciona a rota aos favoritos<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona o icone de pesquisa<br> - Usuário insere o local desejado<br> - Usuário escolhe uma das rotas sugeridas<br> - Usuário escolhe a opção de navegação|
|**Software Utilizado**|Draw.io| 

### **UC2 - Detalhes do carro**

[![Inforções veiculo](img/Cadastrar_informaçoes_sobre_o_carro.png)](img/Cadastrar_informaçoes_sobre_o_carro.png)

| UC2 | informações | 
|:----:|:------:|
|**Caso de uso**|Detalhes do carro|
|**Data**|26/09/19|
|**Hora**|15:38|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Usuário indica tipo de veiculo |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Tipo de combustivel<br> **FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Placa do veículo<br> - Usuário digita placa de seu veiculo <br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão "informação do carro"<br> - Mais opções de rotas|
|**Software Utilizado**|Lucidchart|




### **UC3 - Exibição de mapa**
[![Exibição de mapa](img/Exibição_de_mapa.png)](img/Exibição_de_mapa.png)

| UC3 | informações | 
|:----:|:------:|
|**Caso de uso**|Exibição de mapa|
|**Data**|26/09/19|
|**Hora**|18:55|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa |
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa<br>- Usuário escolhe umas das opções de exibir no mapa<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br> - Usuário Preciona a label Velocimetro<br>**FA3:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br>- Outras Opções<br>|
|**Software Utilizado**|Draw.io|


### **UC4 - Navegação**

[![Navegação](img/navegacao.png)](img/navegacao.png)

| UC4 | informações | 
|:----:|:------:|
|**Caso de uso**|Navegação|
|**Data**|26/09/19|
|**Hora**|19:26|
|**Autor(es)**|João Pedro, Moacir Mascarenha|
|**Fluxo principal** | **FP1:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Navegação<br> - Usuário acessa menu de preferencias|
|**Fluxo alternativo**|**FA1**:<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona Navegação<br> - Usuário acessa o menu de Preferências<br> - Usuário escolhe alguma das opções(Evitar pedágio, passes de pedágio, Evitar balsas, Evitar vias expressas, Vias de terra e Evitar conversões difíceis)<br>**FA2:**<br> - Usuário acessa o Waze<br> - Usuário preciona botão de configurações<br> - Usuário preciona exibição de mapa <br> - Usuário preciona detalhes do veículo<br> -Usuário especifica detalhes sobre veículo <br>|
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
|26/09/19|2.0| Ajustado UC1 |João Pedro, Moacir Mascarenha|
|26/09/19|2.1|Adicionado UC2 |João Pedro, Moacir Mascarenha|
|26/09/19|2.2|Adicionado UC3 |João Pedro, Moacir Mascarenha|
|27/09/19|2.3|Adicionado UC4 |João Pedro, Moacir Mascarenha|