# Requisitos do Ritmo App
---

## Requisitos Funcionais (RF)

| ID | Requisito | Descrição |
|---|---|---|
| **RF01** | **Gerenciamento de hábitos** | O sistema deve permitir criar, editar, excluir, pausar temporariamente e reativar hábitos, definindo nome, descrição, frequência (diária, semanal ou mensal), duração estimada, horário preferido, dias específicos da semana, prioridade e categoria. |
| **RF02** | **Agendamento de hábitos e eventos** | O sistema deve permitir criar agendas semanais ou mensais com hábitos e eventos únicos ou recorrentes, incluindo data, hora, localização e notificações, integrando-os à linha do tempo da rotina. |
| **RF03** | **Verificação e registro diário** | O sistema deve apresentar diariamente os hábitos agendados e os eventos programados e permitir registrar cada hábito como concluído, parcialmente concluído ou não concluído, incluindo o horário de conclusão e observações associadas ao registro. |
| **RF04** | **Consistência e sequências** | O sistema deve calcular e exibir a taxa de consistência dos hábitos, sequências de dias, maiores sequências alcançadas e indicadores visuais de evolução. |
| **RF05** | **Metas progressivas e de consistência** | O sistema deve permitir definir metas de curto, médio e longo prazo para hábitos e metas de consistência para grupos de hábitos, monitorando e exibindo o progresso e o indicador de alcance. |
| **RF06** | **Lembretes adaptativos e de progresso** | O sistema deve enviar lembretes adaptativos com base no histórico de conclusão, incluindo notificações de preparação, foco, prioridade, proximidade de sequências significativas e resumos semanais de progresso. |
| **RF07** | **Gamificação** | O sistema deve atribuir pontos e níveis por hábitos concluídos, conceder bônus por sequências e diversidade de hábitos e permitir ranking opcional entre amigos ou grupos. |
| **RF08** | **Agendamento e ajuste inteligente de carga** | O sistema deve sugerir horários ideais e alternativos para hábitos considerando histórico, conflitos, preferências e intervalos ociosos, além de recomendar aumento ou redução de frequência ou duração com base na consistência, feedback e carga total. |
| **RF09** | **Categorias e equilíbrio de hábitos** | O sistema deve permitir classificar hábitos em categorias e gerar relatórios de equilíbrio entre elas, sugerindo hábitos de categorias pouco representadas quando apropriado. |
| **RF10** | **Registro e análise de obstáculos** | O sistema deve permitir registrar motivos de não conclusão, analisar esses motivos e gerar sugestões de ajustes e ações corretivas específicas. |
| **RF11** | **Visões e relatórios de produtividade** | O sistema deve fornecer visão semanal, mapa de calor e relatórios de produtividade com métricas de conclusão, tempo médio, consistência global, diversidade e gráficos interativos. |
| **RF12** | **Integração com calendário** | O sistema deve sincronizar hábitos e eventos com o calendário padrão do dispositivo, criando blocos de tempo reservados. |
| **RF13** | **Hábitos condicionais, em cadeia e de preparação** | O sistema deve permitir criar dependências e condições entre hábitos, incluindo hábitos que só podem ser marcados após outro hábito, hábitos exigidos apenas quando uma condição for satisfeita e hábitos-gatilho de preparação. |
| **RF14** | **Desafios temporários e hábitos sazonais** | O sistema deve permitir criar hábitos com duração limitada ou aplicáveis apenas em determinadas estações ou meses, exibindo contadores e ativando-os automaticamente nos períodos definidos. |
| **RF15** | **Anotações diárias** | O sistema deve permitir adicionar uma anotação geral ao final de cada dia, associada ao resumo diário e disponível para consulta posterior. |
| **RF16** | **Comparação e análise de períodos** | O sistema deve permitir comparar consistência e tempo gasto entre semanas ou meses e identificar tendências de melhoria ou declínio. |
| **RF17** | **Lembretes por localização** | O sistema deve utilizar localização e geofencing para enviar notificações quando o usuário estiver em locais associados a determinados hábitos. |
| **RF18** | **Hábitos em grupo** | O sistema deve permitir criar hábitos compartilhados, acompanhar o progresso dos membros e exibir conquistas coletivas. |
| **RF19** | **Modelo de dia ideal** | O sistema deve permitir criar um modelo de dia com horários para hábitos e eventos e medir diariamente o desvio entre o modelo e a execução real. |
| **RF20** | **Foco diário** | O sistema deve permitir selecionar um hábito como foco do dia, destacando-o e fornecendo lembretes adicionais. |
| **RF21** | **Histórico de edições** | O sistema deve manter o histórico de alterações de hábitos e eventos, permitindo visualizar a evolução das configurações e reverter para versões anteriores. |
| **RF22** | **Sugestão de novos hábitos** | O sistema deve recomendar novos hábitos com base em baixa consistência, ausência de hábitos em determinadas categorias, interesses e objetivos declarados. |
| **RF23** | **Bloqueio de distrações** | O sistema deve, durante o horário de um hábito, sugerir o bloqueio de notificações de outros aplicativos por meio da API de Não Perturbe do Android e registrar se o bloqueio foi ativado. |
| **RF24** | **Cálculo e visualização de impacto** | O sistema deve estimar o impacto de cada hábito na produtividade geral com base em correlações entre conclusão e pontuação de produtividade, exibindo a medida de impacto e destacando hábitos mais transformadores. |
| **RF25** | **Sugestão de pausas** | O sistema deve sugerir pausas curtas após sequências de hábitos, considerando a duração acumulada e o estado de movimento detectado pelo acelerômetro. |
| **RF26** | **Integração com aplicativos de saúde** | O sistema deve permitir importar dados de passos ou calorias de aplicativos de saúde compatíveis e vinculá-los a hábitos de exercício. |
| **RF27** | **Backup e restauração** | O sistema deve realizar backup automático dos dados de hábitos e eventos em arquivo criptografado a cada dois dias e permitir restaurar os dados em caso de perda. |
| **RF28** | **Recompensas personalizadas** | O sistema deve permitir configurar recompensas pessoais vinculadas ao alcance de metas de consistência e registrar as conquistas. |
| **RF29** | **Análise de correlação** | O sistema deve calcular e exibir correlações entre a conclusão de diferentes hábitos para identificar relações relevantes entre comportamentos. |
| **RF30** | **Templates de rotina** | O sistema deve permitir salvar conjuntos de hábitos e eventos como modelos de rotina e carregá-los em dias ou semanas específicas. |
| **RF31** | **Confirmação por voz** | O sistema deve permitir marcar hábitos como concluídos por comando de voz, utilizando reconhecimento de fala e confirmação auditiva. |
| **RF32** | **Conversão de eventos em tarefas e hábitos preparatórios** | O sistema deve permitir converter eventos únicos em séries de hábitos preparatórios, com datas de vencimento e organização baseada no tempo restante. |
| **RF33** | **Recuperação de hábitos** | O sistema deve detectar períodos prolongados sem conclusão, enviar incentivo e sugerir reinclusão gradual com carga reduzida. |
| **RF34** | **Exportação de dados** | O sistema deve permitir exportar o histórico de hábitos e eventos em CSV ou JSON, com opção de incluir anotações e métricas de consistência, e gerar relatórios semanais ou mensais em PDF para impressão. |

## Requisitos Não Funcionais (RNF)

| ID | Requisito | Descrição |
|---|---|---|
| **RNF01** | **Plataforma e tecnologia** | O aplicativo deve ser desenvolvido com React Native e Node.js e compilado exclusivamente para Android. |
| **RNF02** | **Persistência local e desempenho de consulta** | Os hábitos devem ser armazenados em banco de dados local com índices para permitir consultas rápidas. |
| **RNF03** | **Notificações** | O sistema deve utilizar Firebase Cloud Messaging para envio de notificações adaptativas. |
| **RNF04** | **Processamento local** | A categorização automática de hábitos deve utilizar um modelo leve de classificação de texto executado localmente. |
| **RNF05** | **Integração com Android** | O sistema deve utilizar a API de Não Perturbe do Android para o bloqueio de distrações. |
| **RNF06** | **Localização** | Os lembretes baseados em localização devem utilizar GPS e geofencing. |
| **RNF07** | **Sensores do dispositivo** | A detecção de movimento utilizada para sugestões de pausa deve utilizar o sensor de acelerômetro. |
| **RNF08** | **Integração com saúde** | A integração com dados de passos ou calorias deve utilizar a API gratuita do Google Fit. |
| **RNF09** | **Segurança de backup** | Os backups automáticos devem ser armazenados em arquivo criptografado no armazenamento interno do dispositivo. |
| **RNF10** | **Reconhecimento de fala** | A confirmação por voz deve utilizar uma API de reconhecimento de fala e fornecer confirmação auditiva. |
| **RNF11** | **Visualização de dados** | Os relatórios e indicadores devem ser apresentados por meio de gráficos, calendários, grades e outros elementos visuais interativos conforme especificado nos módulos. |