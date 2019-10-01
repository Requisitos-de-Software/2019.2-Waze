# Análise de Protocolo

## Introdução

<p align = "justify">
  Análise de protocolo solicita ao usuário que realize alguma tarefa no aplicativo e verbalize explicando o processo que está executando, permitindo analisar algo sobre um dado ponto de vista.
</p>

## Metodologia
<p align = "justify">
  Para aplicar a técnica foi escolhido um usuário que nunca utilizou o aplicativo Waze com o objetivo de extrair detalhes sobre as ações realizadas, o encontro com o usuário foi na FGA, quinta-feira dia 26/09 as 10:00 horas. 
</p>

## Verbalizações do Usuário
<p align="justify">
  Ao iniciar o aplicativo o mesmo solicitou permissão para acessar o local do usuário
  ao conceder permissão o Waze mostrou uma breve informação do que é o aplicativo no final da informação foi perguntado se o usuário deseja fazer login ou iniciar sem, o usuário entrevistado optou por não realizar o login e foi mostrado os termos de serviço da aplicação, que foram aceitas, na tela inicial o usuário selecionou a opção informação do carro e selecionou a opção particular, após isso o usuário selecionou a opção de digitar o destino e selecionou a rota para sua residência, após o Waze realizar os cálculos da rota usuário selecionou a opção de começar a rota e o aplicativo mostrou o tempo, a hora de chegada, a distância e a velocidade do veículo.
<p align="justify">
  O usuário também notou a opção de informar eventos na rota, como trânsito, polícia, acidente, radar, bate-papo, o usuário também notou a possibilidade de alterar a rota tendo a visão de 3 rotas alternativas no map, também foi notada a opção de compartilhar o percurso nas redes sociais, ao clicar na lupa que fica contida no canto inferior esquerdo, podendo informar a localização da casa, local de trabalho,eventos, favoritar locais. Ao navegar pelas configurações o usuário também notou uma importante ferramenta de economizar bateria.
</p>

## Requisitos levantados

### MoSCoW

| Código | Descrição | Prioridade |
|--------|-----------|------------|
| AP01  | O Waze deve mostrar um pequeno resumo sobre o que é o app |  Would  |
| AP02  | O usuário deve ser capaz de utilizar o app sem fazer um cadastro/login | Should |
| AP03  | Deve ser mostrado os termos de serviços | Would |
| AP04  | O usuário deve ser capaz de informar que tipo de carro utiliza | Would |
| AP05  | O usuário deve ser capaz de informar o destino  | Must |
| AP06  | O Aplicativo deve informar o tempo do percurso | Should |
| AP07 | O Aplicativo deve informar a hora de chegada no destino | Should |
| AP08 | O Aplicativo deve informar a velocidade do veiculo | Could |
| AP09 | O usuario deve ser capaz de informar eventos na rota, como transito, acidentes e radares | Should |
| AP10 | O usuário deve ser capaz de alterar a rota | Should |
|AP11 | O usuário deve ser capaz de compartilhar sua rota | Would |
|AP12 | O waze deve ter uma opção de economia de bateria | Could |

### First Things First

Funcionalidades |Beneficio Relativo|Penalidade Relativa|Valor Total| Valor %| Custo Relativo| Custo %| Risco Relativo|Risco %| Prioridade
----------------|------------------|-------------------|-----------|---------|---------------|---------|---------------|--------|-----------
Deve ser mostrado os termos de serviço	|3	|3	|9	|4.81	|1	|2.13	|1	|2.22	|1.486
O aplicativo deve informar a velocidade do veículo	|5	|3	|13	|6.95	|2	|4.26	|1	|2.22	|1.295
O waze deve mostrar resumo sobre o app	|3	|1	|7	|3.74	|1	|2.13	|1	|2.22	|1.156
O aplicativo deve informar a hora de chegada no destino	|6	|4	|16	|8.56	|3	|6.38	|2	|4.44	|0.994
O aplicativo deve informar o tempo do percurso	|7	|6	|20	|10.70	|5	|10.64	|4	|8.89	|0.709
O usuário deve ser capaz de compartilhar sua rota	|3	|1	|7	|3.74	|2	|4.26	|1	|2.22	|0.698
O usuário deve ser capaz de usar o app sem cadastro	|7	|7	|21	|11.23	|5	|10.64	|5	|11.11	|0.693
O aplicativo deve ser capaz de informar alertas na rota	|7	|8	|22	|11.76	|5	|10.64	|7	|15.56	|0.639
O usuário deve ser capaz de alterar rota	|7	|9	|23	|12.30	|6	|12.77	|7	|15.56	|0.599
O usuario deve ser capaz de informar o destino	|9	|9	|27	|14.44	|7	|14.89	|9	|20.00	|0.580
O usuário ser capaz de informar o tipo de veículo que usa	|3	|2	|8	|4.28	|3	|6.38	|1	|2.22	|0.571
O waze deve ter uma opcao de economia de bateria	|5	|4	|14	|7.49	|7	|14.89	|6	|13.33	|0.347

## Referências Bibliográfica

>SEQ18RRANO, Maurício; SERRANO, Milene. Requisitos - Aula 07. 1º/2019. 50 slides. Material apresentado para a disciplina de Requisitos de Software no curso de Engenharia de Software da UnB, FGA.

## Histórico de Versões

| Data | Versão | Descrição | Autor(es) |
|:--:|:--:|:--:|:--:|
|30/09/19|1.0| Criado documento |Matheus Estanislau e Lucas Alexandre| 
|30/09/19|1.1| Adicionado FTF |Matheus Estanislau, Lucas Alexandre e Moacir Mascarenha|

