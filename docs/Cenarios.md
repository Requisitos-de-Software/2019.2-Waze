# Cenários

## 1. Introdução
<p align="justify">
Os cenários são narrativas textuais que descrevem sistemas da  perspectiva de um ou mais usuários, narrando seus objetivos, planos e reações. São uma estratégia para compreender as interações entre ambientes e sistemas, assim como elicitar a parte comportamental do software, sua dinâmica e/ou seu fluxo.
</p>


## 2. Metodologia

| Tag cenário | Informações | 
|:--:|:--:|
|**Data**| -- |
|**Hora**| -- |
|**Autor(es)**| -- |
|**Cenário**| -- |
|**Objetivo**| -- |
|**Contexto**| -- |
|**Atores**| -- |
|**Recursos**| -- |
|**Restrição**| -- |
|**Episódios**| -- |
|**Exceção**| -- |
## 3. Cenários


### **C1 - Chegar a um destino desejado**

| C1 | Informações | 
|:--:|:--:|
|**Data**|24/09/19|
|**Hora**|19:02|
|**Autor(es)**|Renan Cristyan|
|**Cenário**|Chegar a um destino desejado|
|**Objetivo**|Utilizar um sistema de navegação por GPS|
|**Contexto**|Local: Centro da cidade<br>Tempo: Durante a manhã<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à internet<br> Veículo|
|**Restrição**|Ter o Waze previamente instalado no smartphone<br> Ter acesso à internet|
|**Episódios**|Usuário quer ir a algum lugar<br>Usuário utiliza o Waze no seu smartphone<br>Usuário digita o lugar que deseja chegar no campo de pesquisa do aplicativo<br>Waze tenta calcular a melhor rota possível<br>Usuário segue essa rota até chegar no local|
|**Exceção**|Rota calculada pelo Waze pode não ser a melhor<br>Distração ao usar o smartphone enquanto dirige pode causar acidentes|

<br>

### **C2 - Encontrar alguém através da localização**

| C2 | Informações | 
|:--:|:--:|
|**Data**|27/09/19|
|**Hora**|16:48|
|**Autor(es)**|João Pedro|
|**Cenário**|Encontrar alguém através da localização|
|**Objetivo**|Encontrar localização de alguém utilizando um sistema de navegação por GPS|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet e localização atual de um amigo|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à rede<br>Veículo<br>Localização atual do Usuário<br>Localização atual da pessoa|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado<br>Recurso de localização do Smartphone ligado<br>|
|**Episódios**|Usuário quer encontrar amigo em um lugar desconhecido pelo usuário<br>Usuário recebe localização do amigo por outro aplicativo<br>Usuário abre a localização de seu amigo usando Waze no seu smartphone<br>Waze calcula a melhor rota para chegar ao destino<br>Waze mostra possíveis eventos no percurso<br>Waze guia o usuário até o destino<br>|
|**Exceção**|Localização enviada inválida<br>Rota calculada pelo Waze não ser a melhor opção<br>Aplicativo sem acesso à rede<br>Distração ao usar o smartphone enquanto dirige que pode causar acidentes<br>|

<br>

### **C3 - Planejar uma rota**

| C3 | Informações | 
|:--:|:--:|
|**Data**|27/09/19|
|**Hora**|19:30|
|**Autor(es)**|Renan Cristyan|
|**Cenário**|Planejar uma rota|
|**Objetivo**|Fazer o planejamento de uma rota e sair quando for a hora certa|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à internet<br>Localização do usuário<br>Localização do destino desejado|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado<br>Recurso de localização do Smartphone ligado<br>|
|**Episódios**|Usuário deseja ir a algum lugar mas não imediatamente<br>Usuário utiliza a ferramenta de planejamento de rota do Waze<br>Usuário digita o local que deseja ir<br>Usuário escolhe que horas deseja chegar no local<br>Waze calcula a rota e o melhor momento para partir<br>Waze notifica o usuário quando for hora de sair|
|**Exceção**|Aplicativo sem acesso à internet<br>Bateria do smatphone acabar|

### **C4 - Saber sobre alertas dentro da rota**

| C4 | Informações | 
|:--:|:--:|
|**Data**|28/09/19|
|**Hora**|16:06|
|**Autor(es)**|João Pedro|
|**Cenário**|Saber de possíveis alertas dentro de uma rota|
|**Objetivo**|Utilizar um sistema de navegação por GPS com avisos de eventos dentro da rota desejada|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet , Ter o Waze previamente instalado<br>|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>acesso à rede<br>Localização do destino desejado<br>|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado<br>|
|**Episódios**|Usuário quer saber de possíveis eventos em seu trajeto. desconhecido pelo usuário<br>Usuário insere o local desejado<br>Waze calcula a melhor rota para chegar ao destino<br>Waze mostra possíveis alertas no percurso<br>Usuário abre mais informações sobre esses eventos<br>Usuário dá feedback sobre estes eventos<br>Waze calcula tempo estimado para a rota<br>|
|**Exceção**|Alertas desatualizados<br>Alertas errados<br>Aplicativo sem acesso à rede<br>|

### **C5 - Adicionar alerta**

| C5 | Informações | 
|:--:|:--:|
|**Data**|28/09/19|
|**Hora**|18:49|
|**Autor(es)**|João Pedro|
|**Cenário**|Adicionar alerta|
|**Objetivo**|Utilizar um sistema de navegação por GPS para alertar motoristas|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet<br>|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>acesso à rede<br>Localização atual<br>|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|Usuário se depara com algum evento nas pista (Trânsito,Acidente,Perigo...) <br> Usuário insere o local do evento <br> Usuário especifica o tipo de evento <br>Waze envia este evento como alerta aos outros motoristas|
|**Exceção**|Localização do alerta errada<br>Alerta desatualizado<br>Alerta errado<br>Aplicativo sem acesso à rede<br>|


### **C6 -  Melhor Horário para o percurso**

| C6 | Informações | 
|:--:|:--:|
|**Data**|28/09/19|
|**Hora**|21:15|
|**Autor(es)**|João Pedro|
|**Cenário**|Encontrar o melhor horário para um caminho desejado|
|**Objetivo**|Utilizar um sistema de navegação por GPS e experiências de outros motoristas para  descobrir o melhor horário para um percurso|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>acesso à rede<br>Localização atual|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|Usuário abre o aplicativo Waze<br>Usuário pesquisa pelo local desejado<br>Waze calcula melhor rota<br>Usuário confirma a rota<br>Usuário acessa opção de encontrar melhor hora para sair<br>Waze retorna uma estatísticas da melhor hora para esta rota|
|**Exceção**|Hora sugerida não ser melhor opção<br>Aplicativo sem acesso à rede|

### **C7 - Buscar postos de combustíveis com melhor preço**

| C7 | Informações | 
|:--:|:--:|
|**Data**|29/09/19|
|**Hora**|22:37|
|**Autor(es)**|João Pedro, Moacir|
|**Cenário**|Encontrar o melhor preço de combustível na minha região|
|**Objetivo**|Encontrar melhores preços de combustíveis na minha região, sugeridos pelo aplicativo|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>acesso à rede<br>Localização atual|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|Usuário verifica que o combustível do seu carro está acabando<br>Usuário abre o aplicativo Waze<br>Usuário acessa o mapa<br>Usuário acessa a pesquisa<br>Usuário clica na opção postos de combustíveis<br>Waze mostra postos próximos a sua localização<br>Waze mostra o preços atualizados dos combustíveis disponíveis<br>Waze mostra distância até os postos de combustíveis próximos<br>Usuário acessa posto de combustível de sua preferência<br>Waze sugere melhor rota até o posto escolhido|
|**Exceção**|Aplicativo sem acesso à rede<br>Local não contém postos próximos<br>Preços desatualizados<br>Estabelecimento fechado<br>Rota sugerida não ser melhor opção|

### **C8 - Buscar Estacionamentos próximo ao destino**

| C8 | Informações | 
|:--:|:--:|
|**Data**|29/09/19|
|**Hora**|23:05|
|**Autor(es)**|João Pedro, Moacir|
|**Cenário**|Encontrar um lugar para estacionar o carro ao chegar em um destino|
|**Objetivo**|Antes de chegar ao destino buscar um estacionamento|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à rede<br>Localização atual|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|O usuário abre o aplicativo Waze<br>O usuário acessa a pesquisa<br>O usuário realiza a pesquisa de uma rota<br>O usuário clica na opção de estacionamento mais próximo<br>O aplicativo sugere estacionamento próximo do destino<br>O usuário clica na opção ”estacionar aqui”<br>O aplicativo gera uma rota até o estacionamento|
|**Exceção**|Aplicativo sem acesso à rede<br>Local há estacionamento próximo ao destino<br>Rota sugerida não ser melhor opção<br>Estacionamento não cadastrado|

### **C9 - Adicionando local aos favoritos**

| C9 | Informações | 
|:--:|:--:|
|**Data**|29/09/19|
|**Hora**|23:20|
|**Autor(es)**|João Pedro, Moacir|
|**Cenário**|O usuário possui um local que deseja salvar como favorito|
|**Objetivo**|Permitir ao usuário que salve locais de sua preferência para que depois tenha um acesso rápido a esta rota|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à rede<br>Localização atual|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|O usuário abre o aplicativo Waze<br>O usuário acessa a pesquisa<br>O usuário clica na opção “Favoritos<br>O usuário clica na opção “Adicionar novo favorito”<br>O usuário digita o local na barra de pesquisa “Pesquisar endereço”<br>O aplicativo sugere locais<br>O usuário seleciona uma das opções|
|**Exceção**|Aplicativo sem acesso à rede<br>Rota sugerida não ser melhor opção<br>Localização inválida|


### **C10 - Planejar uma viagem futura**

| C10 | Informações | 
|:--:|:--:|
|**Data**|29/09/19|
|**Hora**|23:33|
|**Autor(es)**|João Pedro, Moacir|
|**Cenário**|Agendar um percurso para um evento agendado|
|**Objetivo**|O usuário deseja planejar uma viagem adicionando uma rota para ser notificado em certa data|
|**Contexto**|Local: localização atual do usuário<br>Pré-condição: Acesso à internet|
|**Atores**|Usuário|
|**Recursos**|Smartphone<br>Acesso à rede<br>Localização atual<br>Ter permissão da agenda do Smartphone ou rede social|
|**Restrição**|Ter acesso à internet<br>Ter o Waze previamente instalado|
|**Episódios**|O usuário abre o aplicativo Waze<br>O usuário acessa a pesquisa<br>O usuário clica na opção “Planejado”<br>O usuário clica no botão laranja para adicionar um destino<br>O usuário digita o local na barra de pesquisa “Digite o destino”<br>O usuário adiciona informações sobre a data e horário para o percurso planejado<br>O usuário seleciona uma das opções|
|**Exceção**|Aplicativo sem acesso à rede<br>Rota sugerida não ser melhor opção<br>Localização inválida|


## 4. Referências Bibliográficas

> LUCENA, S.V.; KEMCZINSKI, A.;  GASPARINI, I.;  MATOS, A.V.M.; OGAWA, A.N.; "Modelagem de requisitos baseada em cenários para o Storyboard da Metodologia para Construção de Objetos de Aprendizagem Interativos", Nuevas Ideas en Informática Educativa TISE, 2014.

## 5. Histórico de versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|24/09/19|1.0|Criação do documento|Renan Cristyan|
|27/09/19|2.0|Incluido Cenário 1 |Renan Cristyan|
|27/09/19|2.1|Criado Cenário 2|João Pedro|
|27/09/19|2.2|Criado Cenário 3|Renan Cristyan|
|28/09/19|2.3|Criado Cenário 4|João Pedro|
|28/09/19|2.4|Criado Cenário 5|João Pedro|
|28/09/19|2.5|Criado Cenário 6|João Pedro|
|28/09/19|2.6|Criado Cenário 7|João Pedro, Moacir|
|28/09/19|2.7|Criado Cenário 8|João Pedro, Moacir|
|28/09/19|2.8|Criado Cenário 9|João Pedro, Moacir|
|28/09/19|2.9|Criado Cenário 10|João Pedro, Moacir|


<!-- | C1 | Informações | 
|:--:|:--:|
|**Data**||
|**Hora**||
|**Autor(es)**||
|**Cenário**||
|**Objetivo**||
|**Contexto**||
|**Atores**||
|**Recursos**||
|**Restrição**||
|**Episódios**||
|**Exceção**|| -->
