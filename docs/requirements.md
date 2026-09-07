# Requisitos do Ritmo App
---

## Requisitos Funcionais (RF)

| ID | Descrição |
|----|-----------|
| RF01 | Permitir ao usuário criar hábitos com nome, descrição, frequência (diária, semanal ou mensal), duração estimada, horário preferido e dias específicos da semana. |
| RF02 | Permitir ao usuário criar agendas semanais ou mensais com eventos únicos ou recorrentes (provas, reuniões, compromissos), com data, hora, localização e notificação, integrando esses eventos à linha do tempo de hábitos. |
| RF03 | Apresentar, a cada manhã, uma lista de hábitos e eventos programados para o dia, permitindo marcar cada hábito como concluído, parcialmente concluído ou não concluído, registrando o horário de conclusão. |
| RF04 | Calcular, para cada hábito, uma taxa de consistência (percentual de dias concluídos em relação ao total esperado) e exibi-la em gráfico de sequência de dias. |
| RF05 | Permitir ao usuário definir metas de curto, médio e longo prazo para cada hábito, monitorando o progresso e exibindo um indicador de alcance. |
| RF06 | Enviar notificações em horários estratégicos com base no histórico de conclusão do usuário, aprendendo os melhores momentos para lembrar cada hábito. |
| RF07 | Atribuir pontos e níveis ao usuário por hábito concluído, com bônus por sequências longas e diversidade de hábitos, e exibir ranking opcional entre amigos ou grupos. |
| RF08 | Sugerir horários ideais para realização de cada hábito, com base no histórico de conclusão, conflitos com outros itens da agenda e preferências do usuário. |
| RF09 | Permitir classificar hábitos em categorias (físico, mental, espiritual, social, profissional) e gerar relatórios de equilíbrio entre elas. |
| RF10 | Ao marcar um hábito como não concluído, permitir selecionar um motivo (falta de tempo, indisposição, esquecimento, imprevisto) e analisar esses motivos para sugerir ajustes. |
| RF11 | Recomendar automaticamente o aumento ou a redução da frequência/duração de cada hábito, com base na taxa de consistência e no feedback do usuário. |
| RF12 | Exibir uma grade semanal com os sete dias e os hábitos agendados para cada dia, com indicadores visuais de conclusão. |
| RF13 | Sincronizar hábitos e eventos com o calendário padrão do dispositivo, criando blocos de tempo reservados para cada item. |
| RF14 | Gerar métricas de produtividade (total de hábitos concluídos por semana, tempo médio gasto por hábito, taxa de consistência global, índice de diversidade) em gráficos interativos. |
| RF15 | Permitir criar hábitos que dependem da conclusão de outro hábito no mesmo dia, bloqueando a marcação do segundo até que o primeiro seja concluído. |
| RF16 | Permitir criar hábitos com duração limitada (desafios temporários), exibindo contador regressivo e notificações de incentivo durante o período. |
| RF17 | Permitir adicionar observações textuais a cada conclusão de hábito, associadas ao registro do dia para consulta futura. |
| RF18 | Permitir comparar a consistência e o tempo gasto em hábitos entre duas semanas ou meses selecionados, identificando tendências de melhoria ou declínio. |
| RF19 | Enviar notificações quando o usuário estiver em um local propício para um hábito específico. |
| RF20 | Permitir criar um hábito compartilhado entre múltiplos usuários, com visualização do progresso dos demais membros e painel de conquistas coletivas. |
| RF21 | Analisar o histórico de registros para identificar períodos ociosos do dia e sugerir a alocação de hábitos nesses intervalos. |
| RF22 | Permitir criar um modelo de "dia ideal", com horários para cada hábito e evento, e medir diariamente o desvio entre o modelo e a execução real. |
| RF23 | Enviar mensagens de incentivo quando o usuário estiver próximo de completar uma sequência significativa (ex.: 7 ou 30 dias). |
| RF24 | Permitir exportar todo o histórico de hábitos e eventos em formato CSV ou JSON, incluindo anotações e métricas de consistência. |
| RF25 | Sugerir categorias para novos hábitos com base no nome e na descrição informados. |
| RF26 | Permitir selecionar um hábito como "foco do dia", destacando-o na lista e enviando lembretes adicionais. |
| RF27 | Manter um registro de todas as alterações feitas em hábitos e eventos, permitindo reverter para versões anteriores. |
| RF28 | Recomendar novos hábitos com base em categorias com baixa consistência ou ausência de hábitos, alinhados aos interesses do usuário. |
| RF29 | Durante o horário agendado de um hábito, sugerir o bloqueio de notificações de outros aplicativos e registrar se o bloqueio foi ativado. |
| RF30 | Enviar lembretes antecipados para hábitos que exigem preparação prévia, reduzindo a procrastinação. |
| RF31 | Estimar o impacto de cada hábito na produtividade geral do usuário, com base em correlações entre conclusão do hábito e pontuação de produtividade do dia. |
| RF32 | Exibir um calendário em formato de mapa de calor, com cores representando a consistência diária. |
| RF33 | Sugerir uma pausa curta quando o usuário concluir vários hábitos em sequência, com base na duração acumulada. |
| RF34 | Permitir importar dados de passos ou calorias de aplicativos de saúde e vincular esses dados a hábitos de exercício. |
| RF35 | Permitir definir uma meta de consistência semanal para um grupo de hábitos e monitorar o progresso. |
| RF36 | Permitir criar hábitos sazonais, aplicáveis apenas em determinadas estações ou meses, com ativação automática na data apropriada. |
| RF37 | Sugerir horários alternativos disponíveis no dia quando um hábito não for concluído no horário previsto. |
| RF38 | Permitir configurar recompensas personalizadas ao atingir metas de consistência, registrando a conquista. |
| RF39 | Permitir definir níveis de prioridade para cada hábito, destacando os de alta prioridade e enviando lembretes mais insistentes. |
| RF40 | Calcular correlações entre a conclusão de diferentes hábitos e exibir essas descobertas ao usuário. |
| RF41 | Permitir salvar um conjunto de hábitos e eventos como um modelo (template) de rotina e carregá-lo em dias ou semanas específicas. |
| RF42 | Permitir marcar um hábito como concluído por comando de voz, com confirmação auditiva para evitar erros. |
| RF43 | Para hábitos com baixa consistência, gerar relatório detalhado com os principais motivos de não conclusão e sugerir ações corretivas. |
| RF44 | Permitir converter um evento único em uma série de hábitos preparatórios, com datas de vencimento. |
| RF45 | Permitir criar um hábito que serve como gatilho para outro (hábito de preparação), lembrando o usuário do hábito gatilho. |
| RF46 | Enviar um resumo semanal com a evolução da consistência e o progresso em metas, destacando avanços e áreas de atenção. |
| RF47 | Permitir pausar um hábito por um período definido sem penalizar sua consistência, reativando-o automaticamente ao final do período. |
| RF48 | Analisar a carga total de hábitos do usuário (em minutos por dia) e sugerir se está adequada, leve ou excessiva. |
| RF49 | Exibir um painel com as maiores sequências já alcançadas para cada hábito. |
| RF50 | Permitir criar hábitos condicionais, exigidos apenas sob condições específicas, verificando a condição antes de cobrar o hábito. |
| RF51 | Sugerir hábitos de outras categorias quando o usuário concentrar todos os hábitos em uma única categoria. |
| RF52 | Gerar relatório semanal ou mensal em PDF com gráficos de consistência, lista de hábitos concluídos/não concluídos e progresso em metas. |
| RF53 | Exibir contador regressivo para eventos importantes e criar automaticamente subtarefas preparatórias com base no tempo restante. |
| RF54 | Ao agendar um hábito ou evento, verificar conflitos com itens já agendados, sugerindo remanejamentos ou alertando sobre sobreposição. |
| RF55 | Permitir adicionar, ao final de cada dia, uma nota geral associada ao resumo diário. |
| RF56 | Quando o usuário ficar vários dias sem concluir um hábito, enviar mensagem de incentivo e sugerir reinclusão gradual com carga reduzida. |
| RF57 | Calcular e exibir, para cada hábito, uma medida de impacto baseada na correlação com a produtividade geral. |

---

## Requisitos Não Funcionais (RNF)

| ID | Descrição |
|----|-----------|
| RNF01 | O aplicativo deve ser desenvolvido em React Native (front-end) e Node.js (back-end), compilado exclusivamente para a plataforma Android. |
| RNF02 | O sistema deve possuir um motor de regras responsável por vincular hábitos a gatilhos contextuais. |
| RNF03 | O sistema deve possuir um algoritmo de recomendação para ajustar automaticamente as cargas diárias de hábitos. |
| RNF04 | O sistema deve possuir um mecanismo de detecção de padrões para identificar períodos de maior ou menor aderência do usuário. |
| RNF05 | Os hábitos devem ser armazenados em um banco de dados local com índices que garantam consultas rápidas. |
| RNF06 | O envio de lembretes adaptativos deve utilizar o serviço Firebase Cloud Messaging. |
| RNF07 | A sincronização de hábitos e eventos deve ser feita por integração com o calendário nativo do dispositivo Android. |
| RNF08 | Os lembretes por localização devem utilizar geolocalização (GPS) e geofencing. |
| RNF09 | A categorização automática de hábitos deve ser feita por um modelo leve de classificação de texto, executado localmente no dispositivo. |
| RNF10 | O bloqueio de distrações deve utilizar a API "Não Perturbe" nativa do sistema Android. |
| RNF11 | A sugestão de pausas deve utilizar o sensor de acelerômetro do dispositivo para detectar movimento. |
| RNF12 | A importação de dados de saúde deve ser feita por integração com a API gratuita do Google Fit. |
| RNF13 | O sistema deve realizar backup automático dos dados em arquivo criptografado, a cada dois dias, com opção de restauração em caso de perda de dados. |
| RNF14 | A confirmação de hábitos por voz deve utilizar uma API de reconhecimento de fala. |

---


## Épicos e requisitos relacionados

| Épico | Descrição | RFs Relacionados |
|---|---|---|
| Gestão de Hábitos | Criação, edição e configuração de hábitos (CRUD, dependências, condições, templates) | RF01, RF15, RF16, RF36, RF39, RF41, RF44, RF45, RF47, RF50 |
| Agenda e Sincronização | Eventos, calendário, conflitos e integração com o dispositivo | RF02, RF12, RF13, RF53, RF54 |
| Execução Diária | Fluxo do dia a dia: marcar conclusão, motivos, foco do dia, notas | RF03, RF10, RF17, RF26, RF29, RF42, RF55 |
| Metas | Definição e acompanhamento de metas individuais e em grupo | RF05, RF35, RF38 |
| Notificações e Lembretes | Lembretes adaptativos, por localização, incentivo e antecipação | RF06, RF19, RF23, RF30, RF33, RF56 |
| Gamificação e Social | Pontos, níveis, ranking, hábitos compartilhados e recompensas | RF07, RF20 |
| Recomendação / IA | Sugestões automáticas baseadas em histórico e padrões do usuário | RF08, RF11, RF21, RF25, RF28, RF37, RF51 |
| Analytics e Consistência | Cálculos, gráficos e visualizações de desempenho | RF04, RF09, RF14, RF18, RF22, RF32, RF40, RF48, RF49 |
| Produtividade / Impacto | Correlação entre hábitos e produtividade geral | RF31, RF57 |
| Relatórios e Exportação | Geração de relatórios e exportação de dados | RF24, RF43, RF46, RF52 |
| Metadados e Auditoria | Histórico de alterações e versionamento | RF27 |
| Integrações Externas | Conexão com apps/serviços de terceiros (saúde, fitness) | RF34 |