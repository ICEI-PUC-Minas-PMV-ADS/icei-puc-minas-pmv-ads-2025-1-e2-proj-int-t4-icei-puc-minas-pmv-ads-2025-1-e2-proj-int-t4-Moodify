# Especificações do Projeto

<span style="color:red">Pré-requisitos: <a href="1-Documentação de Contexto.md"> Documentação de Contexto</a></span>

Definição do problema e ideia de solução a partir da perspectiva do usuário. É composta pela definição do  diagrama de personas, histórias de usuários, requisitos funcionais e não funcionais além das restrições do projeto.

Apresente uma visão geral do que será abordado nesta parte do documento, enumerando as técnicas e/ou ferramentas utilizadas para realizar a especificações do projeto

## Personas
### Persona 1
![image](https://github.com/user-attachments/assets/58333bce-beb8-4bd3-a72e-3a6c6d064904)

Figura 1 - Primeira Persona

### Persona 2
![image](https://github.com/user-attachments/assets/184cd9ae-2ac5-4699-8517-acb83b68ecbe)

Figura 2 - Segunda Persona

### Persona 3
![image](https://github.com/user-attachments/assets/24a444cd-ca92-49c4-94fe-27ac82bd462a)

Figura 3 - Terceira Persona

### Persona 4
![image](https://github.com/user-attachments/assets/4e67e182-ef0d-4493-b4aa-56c4952370cf)

Figura 4 - Quarta Persona

### Persona 5
![image](https://github.com/user-attachments/assets/acf897df-e5cc-4404-aab8-52f0ec350e54)

Figura 5 - Quinta Persona

## Histórias de Usuários

Com base na análise das personas foram identificadas as seguintes histórias de usuários:

|EU COMO... `PERSONA`| QUERO/PRECISO ... `FUNCIONALIDADE` |PARA ... `MOTIVO/VALOR`                 |
|--------------------|------------------------------------|----------------------------------------|
|Bruno | quero playlists dinâmicas que acompanhem a intensidade do meu treino | para que eu tenha motivação extra durante os exercícios. |
|Bruno | quero poder selecionar músicas com base no BPM | para garantir que a trilha sonora esteja sincronizada com meu ritmo de treino. |
|Camila | quero playlists que me ajudem a estimular a criatividade durante meu trabalho | para manter um fluxo produtivo sem distrações. |
|Camila | quero poder alternar entre diferentes gêneros musicais sem trocar de playlist | para que a trilha sonora acompanhe minha inspiração ao longo do dia. |
|Eduardo | quero playlists instrumentais que me ajudem a manter o foco durante cálculos e análises | para melhorar minha produtividade. |
|Eduardo | quero a opção de alternar automaticamente entre músicas e podcasts sem precisar sair do aplicativo | para facilitar o fluxo de trabalho. |
|Rafaela | quero playlists específicas para diferentes momentos de estudo | para que eu possa manter a concentração e otimizar meu tempo de aprendizado. |
|Rafaela | quero um temporizador integrado às playlists | para que a música mude conforme meu tempo de foco, ajudando a manter meu ritmo de estudos. |
|Marcelo | quero que o sistema sugira músicas baseadas no meu calendário | para que eu tenha trilhas sonoras adequadas para reuniões, trabalho e viagens. |
|Marcelo | quero integração com dispositivos inteligentes | para que a música se adapte automaticamente ao ambiente em que estou, proporcionando uma experiência mais fluida. |

## Requisitos

As tabelas que se seguem apresentam os requisitos funcionais e não funcionais que detalham o escopo do projeto.

### Requisitos Funcionais

|ID    | Descrição do Requisito  | Prioridade |
|------|-----------------------------------------|----|
|RF-001|O sistema deve permitir que o usuário selecione um estado emocional (ex: feliz, triste, relaxado, motivado)| ALTA | 
|RF-002| O aplicativo deve integrar com plataformas como Spotify, Apple Music, Deezer entre outros para reproduzir as músicas recomendadas | ALTA |
|RF-003| O aplicativo deve permitir que os usuários se cadastrem com um e-mail e senha | ALTA |
|RF-004| O aplicativo deve ter um sistema para que o usuário possa informar seu humor atual (ex: "feliz", "triste", "ansioso", etc.)| ALTA |
|RF-005| O sistema deve exibir uma playlist correspondente ao humor selecionado | ALTA |
|RF-006| O aplicativo deve permitir que o usuário escute as músicas diretamente no app, com controle básico de reprodução (play, pause, skip, volume) | ALTA |
|RF-007| O usuário deve poder sugerir músicas para cada categoria | MEDIA |
|RF-008| O app pode enviar notificações para sugerir novas playlists ou músicas com base em mudanças de humor do usuário ao longo do tempo | ALTA |
|RF-009| O sistema deve armazenar as músicas sugeridas em um banco de dados | ALTA |
|RF-010| O usuário deve poder acessar o aplicativo via desktop e mobile | MEDIA |
|RF-011| O aplicativo deve permitir que o usuário dê feedback sobre as sugestões de música, ajudando o sistema a aprender e melhorar as recomendações | ALTA |
|RF-012| O aplicativo deve armazenar um histórico de musicas ou playlists que o usuário ouviu, para que ele possa voltar a elas quando quiser | MEDIA |
|RF-013| O sistema deve permitir a seleção de cantores, gêneros e estilos musicais | MEDIA |
|RF-014| O sistema deve exibir frases motivacionais ou reflexivas de acordo com o humor selecionado | BAIXA |


### Requisitos não Funcionais

|ID     | Descrição do Requisito  |Prioridade |
|-------|-------------------------|----|
|RNF-001| O sistema deve ter uma interface intuitiva e responsiva | MÉDIA | 
|RNF-002| As respostas do back-end devem ser rápidas para garantir boa usabilidade |  ALTA | 
|RNF-003| O sistema deve ser compatível com futuras integrações com serviços de streaming |  MEDIA| 
|RNF-004| O aplicativo deve ser capaz de lidar com falhas temporárias, como perda de conexão com a internet ou falhas no serviço de streaming, sem fechar ou travar completamente|  ALTA | 
|RNF-005| O sistema deve ser capaz de lidar com um grande número de usuários simultâneos, sem comprometer a performance do aplicativo |  ALTA | 
|RNF-006| O aplicativo deve armazenar as preferências e playlists do usuário de forma segura na nuvem, garantindo a recuperação em caso de troca de dispositivo |  MEDIA | 
|RNF-007| O aplicativo deve coletar dados de uso (respeitando a privacidade) para melhorar as sugestões com base no comportamento do usuário |  BAIXA | 
|RNF-008| O aplicativo deve ser projetado para funcionar bem em smartphones (Android e iOS) e também em tablets |  ALTA | 



Com base nas Histórias de Usuário, enumere os requisitos da sua solução. Classifique esses requisitos em dois grupos:

- [Requisitos Funcionais
 (RF)](https://pt.wikipedia.org/wiki/Requisito_funcional):
 correspondem a uma funcionalidade que deve estar presente na
  plataforma (ex: cadastro de usuário).
- [Requisitos Não Funcionais
  (RNF)](https://pt.wikipedia.org/wiki/Requisito_n%C3%A3o_funcional):
  correspondem a uma característica técnica, seja de usabilidade,
  desempenho, confiabilidade, segurança ou outro (ex: suporte a
  dispositivos iOS e Android).
Lembre-se que cada requisito deve corresponder à uma e somente uma
característica alvo da sua solução. Além disso, certifique-se de que
todos os aspectos capturados nas Histórias de Usuário foram cobertos.

## Restrições

O projeto está restrito pelos itens apresentados na tabela a seguir.

|ID| Restrição                                             |
|--|-------------------------------------------------------|
|01| O primeiro MVP não terá integração com APIs externas como Spotify e YouTube.|
|02| Apenas músicas cadastradas no banco de dados poderão ser recomendadas inicialmente.|
|03| O app deve ser leve e não consumir muitos recursos do dispositivo do usuário.|
|04| Algumas funcionalidades, como streaming de música, exigirão conexão com a internet.|
|05| Se o app tiver um modo offline, deve haver um limite para o armazenamento de dados no dispositivo.|
|06| O app deve funcionar corretamente em diferentes modelos de smartphones, podendo ter variações de desempenho.|




## Diagrama de Casos de Uso

Desenvolvemos o Diagrama de Casos de Uso compondo os principais requisitos essenciais para o desenvolvimento correto da plataforma, para os usuários e dentro do sistema. 


![Diagrama de Caso de Uso - Moodify](https://github.com/user-attachments/assets/ac10d078-56a6-4cc4-9f63-a6e9a593a58a)
