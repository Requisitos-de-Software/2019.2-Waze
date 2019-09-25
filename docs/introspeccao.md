# 1. Introspecção

<p align="justify">
Obter informações a respeito de um software por meio da introspecção, assim será uma forma de imaginar o caminho do usuário no sistema.
</p>

<p align="justify"><b>
Problema:</b> uma instrospecção de um especialista de área diferente pode não ser adequada para a experiência dos reais usuários interessados.
</p>

## 2. Perspectiva do Usuário
<p align="justify">
    Descrever a perspectiva do usuário quanto ao aplicativo já existente Waze.
    E também sugestões de percepções individuais do que poderia ser o <i>"my Waze"</i>.
</p>

### 2.1 Primeiro acesso:
 <ul>
    <li> Deve aparecer opções de registrar e/ou login</li>
    <li> Deve conectar gps para localizar usuário no mapa</li>
    <li><i> Deve ter opções de selecionar idioma</i></li>
 </ul>


### 2.2 Registro:
 <ul>
    <li> Deve ter opções de login com contas Google ou Facebook ou campo com email/senha para cadastrar</li>
    <li> Deve conectar gps para localizar usuário no mapa</li>
 </ul>


### 2.3 Tela principal:
 <ul>
    <li> Deve ter busca de rotas</li>
    <li> Deve ter menu de rotas favoritas</li>
    <li> Deve ter rotas planejadas (agendadas)</li>
    <li> Deve ter opção de conectar ao Waze Carpool</li>
    <li> Deve ter opção de integrar com meu app de mídia</li>
    <li> Deve ter opção de selecionar meu tipo de veículo</li>
 </ul>


### 2.4 Campo de Busca:
 <ul>
    <li> Deve ter opções de filtros para buscar restaurantes, postos e outros</li>
    <li> Deve ter histórico de rotas</li>
    <li> Deve ter locais favoritos</li>
    <li> Deve ter rotas planejadas/programadas </li>
 </ul>


### 2.5 Rotas :
 <ul>
    <li> Deve mostrar a melhor rota para local escolhido</li>
    <li> Deve mostrar as rotas alternativas </li>
    <li> Deve mostrar opções de compartilhamento e informações da rota</li>
    <li><i> Deve ter opções de desativa/ativar o que é mostrado no mapa </i></li>
 </ul>


### 2.7 Integração com apps de mídia :
 <ul>
   <li>Deve conectar com apps de mídia</li>
   <li>Deve continuar a navegação enquanto integrado com app de mídia</li>
 </ul>


### 2.8 Configurações :
 <ul>
   <li>Deve ter configurações Geral de usuário</li>
   <li>Deve ter configurações de Personalização de Som e Voz</li>
   <li>Deve ter configurações de Navegação</li>
   <li>Deve ter configurações de Detalhes do carro</li>
   <li>Deve ter configurações de Passes de pedágio</li>
   <li>Deve ter configurações de Alertas e avisos</li>
   <li>Deve ter configurações de Postos de combustível</li>
   <li>Deve ter configurações de Velocímetro</li>
   <li>Deve ter configurações de Notificações</li>
   <li>Deve ter configurações de Percursos Planejados</li>
   <li>Deve ter configurações de Lembretes</li>
   <li>Deve ter configurações de  Conta e Login</li>
   <li>Deve ter configurações de Privacidade</li>
   <li>Deve ter configurações de Relatar um Problema</li>
   <li>Deve ter configurações de Cental de Ajuda</li>
   <li>Deve ter configurações de Informações sobre o app</li>
   <li>Deve ter configurações de Compartilhar app</li>
   <li>Deve ter configurações de Editor de mapas do Waze</li>
   <li>Deve ter configurações de Enviar logs</li>
 </ul>


### 2.9 Carpool :
 <ul>
      <li>Deve ter opção de dar Carona</li>
      <li>Deve ter opção de integrar/ ir para o app Carpool</li>
 </ul>


## Requisitos Elicitados e MoSCo

| Código | Descrição | Prioridade |
|--------|-----------|------------|
| INS00  | Precisão de rotas          |  Should         |
| INS01  | Mudança de Interface          |  Would          |
| INS02  | Veracidade de Informações de usuários          | Should            |
| INS03  | O aplicativo deve consumir menos rede de dados / opção offline          | Should            |
| INS04  | Design mais intuitivo           | Would            |
| INS05  |Integração com redes sociais           | Could            |
| INS06  | Aumentar tamanho (km) de rotas | Could            |
| INS07 |Cadastro de usuário e login | Must |
| INS08 | A aplicação tem que solicitar ao usuário que ele digite o trajeto do destino.| Must |
| INS09 | A aplicação tem que solicitar ao usuário um destino | Must |
| INS10 | Validar endereço | Must |
| INS11 | O usuário tem que receber dicas de lugares para que ele possa ir caso tenha digitado metade do endereço ou o endereço errado.| Could|



## Histórico de Versões

|   Data   | Versão |           Descrição           |             Autor(es)              |
|:--------:|:------:|:-----------------------------:|:----------------------------------:|
| 09/09/19 |  1.0   |    Documento Introspecção     |           Guilherme Leal, Matheus Estanislau|
| 09/09/19 |  1.1   | INS's, MOSCOW, e complementos | Guilherme Leal, Matheus Estanislau |
| 09/09/19 |  1.2   | Revisão | Guilherme Leal, Matheus Estanislau |
| 09/09/19 |  1.3   | Deploy version | Guilherme Leal |
| 25/09/19 |  2.0   | Separação de Personas | Guilherme Leal |