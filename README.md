![logo](./images/logo.png)

<br>

# Descrição
O Ritmo App é o seu espaço aconchegante para construir hábitos e organizar a rotina. Com um visual relaxante e cozy, o app transforma produtividade em algo leve e prazeroso, sem a pressão ou a frieza dos apps tradicionais.

Crie novos hábitos, monte cronogramas, defina lembretes e organize suas tarefas em um único lugar, tudo em um ambiente pensado para trazer calma ao seu dia a dia. Porque construir uma rotinha melhor não precisa ser estressante, pode ser, literalmente, confortável.

<br>

# Backlog
[Veja Aqui](./docs/backlog.md)

<br>

# Sprint Backlog

## Sprint 1

| ID | User Story | Prioridade | Requisito | Story Points |
|---|---|---|---|---|
| US01 | Como usuário, eu quero criar, editar, excluir, pausar e reativar hábitos definindo nome, descrição, frequência, duração, horário, dias, prioridade e categoria, para que eu possa organizar minha rotina de forma flexível. | High | RF01 | 8 |
| US02 | Como usuário, eu quero criar agendas semanais ou mensais com hábitos e eventos (únicos ou recorrentes), incluindo data, hora, local e notificações, para que minha rotina fique organizada em uma linha do tempo única. | High | RF02 | 8 |
| US03 | Como usuário, eu quero visualizar diariamente meus hábitos e eventos agendados e registrar cada hábito como concluído, parcialmente concluído ou não concluído, com horário e observações, para que eu acompanhe minha execução diária. | High | RF03 | 8 |
| US04 | Como usuário, eu quero visualizar minha taxa de consistência, sequências atuais e maiores sequências já alcançadas, para que eu entenda minha evolução ao longo do tempo. | High | RF04 | 5 |
| US05 | Como usuário, eu quero definir metas de curto, médio e longo prazo para hábitos individuais e para grupos de hábitos, para que eu possa acompanhar meu progresso rumo a objetivos específicos. | Medium | RF05 | 5 |
| US07 | Como usuário, eu quero receber um resumo semanal do meu progresso, para que eu tenha uma visão consolidada da minha semana. | Medium | RF06 | 3 |
| US14 | Como usuário, eu quero registrar o motivo pelo qual não concluí um hábito, para que o sistema possa analisar padrões de obstáculos. | Medium | RF10 | 2 |
| US18 | Como usuário, eu quero criar hábitos condicionais e em cadeia, que só podem ser marcados após outro hábito ou quando uma condição for satisfeita, para que eu modele dependências reais da minha rotina. | Low | RF13 | 8 |
| US19 | Como usuário, eu quero configurar hábitos-gatilho de preparação, para que eu seja preparado antes de realizar hábitos dependentes. | Low | RF13 | 5 |
| US21 | Como usuário, eu quero adicionar uma anotação geral ao final de cada dia, associada ao resumo diário, para que eu registre reflexões e possa consultá-las depois. | Medium | RF15 | 2 |
| US26 | Como usuário, eu quero criar um modelo de dia ideal com horários para hábitos e eventos, para que eu tenha uma referência de rotina planejada. | Medium | RF19 | 5 |
| US28 | Como usuário, eu quero selecionar um hábito como foco do dia, com destaque visual e lembretes adicionais, para que eu direcione minha atenção prioritária. | Medium | RF20 | 3 |

<br>

# Arquitetura

![arquitetura](./docs/architecture.png)

<br>

# Tecnologias

**Front-end:**
- React Native
- React Navigation
- Nativewind
- WaterMelonDB
- Zustand
- React Hook Form
- Axios
- Tanquery Stack

<br>

**Back-end:**
- Node Express
- TypeScript
- Prisma
- Zod
- Vitest + Supertest
- Pino