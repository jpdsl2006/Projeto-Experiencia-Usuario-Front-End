### 3. RESULTADOS DO TESTE 
[1 solução por equipe]

**Avaliação de cada Tarefa (para cada usuário)**

Para o teste, as tarefas observadas nos vídeos foram consolidadas em 4 ações principais:
- **T1:** Cadastro e Configuração de Permissões Iniciais.
- **T2:** Agendamento de Nova Consulta (com anexo de guias).
- **T3:** Navegação (Calendário e visualização de Histórico).
- **T4:** Configuração de Lembretes (Perfil).

| Usuário / Tarefa | Grau de Sucesso | Total de Erros | Tipos de Erros | Tempo Médio | Grau de Satisfação |
| :--- | :--- | :--- | :--- | :--- | :--- |
| **Usuário 1: Roberto** | | | | | |
| T1: Cadastro | Sucesso Completo | 0 | - | ~45s | Muito Satisfeito ("Já fui direto") |
| T2: Agendamento | Sucesso Completo | 0 | - | ~2m 10s | Satisfeito (Conseguiu marcar para o familiar Carlos) |
| T3: Navegação | Sucesso Parcial | 1 | (1) Falha do Sistema | ~1m 20s | Confusão Leve (Apontou que o filtro do Histórico não exibiu todas as consultas que ele havia acabado de marcar) |
| T4: Lembretes | Sucesso Completo | 0 | - | ~40s | Satisfeito |
| **Usuário 2: Lucas** | | | | | |
| T1: Cadastro | Sucesso Completo | 0 | - | ~40s | Muito Satisfeito ("Muito prático") |
| T2: Agendamento | Sucesso Completo | 0 | - | ~1m 30s | Satisfeito (Sugeriu como melhoria que o preenchimento da clínica e endereço fossem automáticos) |
| T3: Navegação | Sucesso Completo | 0 | - | ~45s | Satisfeito |
| T4: Lembretes | Sucesso Completo | 0 | - | ~30s | Muito Satisfeito ("O sistema é perfeito pra mim") |
| **Usuário 3: Giselle** | | | | | |
| T1: Cadastro / Login | Sucesso Completo | 0 | - | ~25s | Muito Satisfeito |
| T2: Agendamento | Sucesso Completo | 0 | - | ~1m 15s | Muito Satisfeito (Elogiou bastante a função de tirar foto e anexar guias médicas de papel) |
| T3: Navegação | Sucesso Completo | 0 | - | ~30s | Muito Satisfeito ("Visão de forma bem intuitiva") |
| T4: Lembretes | Sucesso Completo | 0 | - | ~40s | Muito Satisfeito ("Está suprindo todas as minhas necessidades") |

**Links dos vídeos:**
- Vídeo 1: https://youtu.be/-H_b5ERztqo
- Vídeo 2: https://youtu.be/LhFKDiY_-oc
- Vídeo 3: https://youtu.be/FiSr0UgGigE

### Respostas do Formulário do Usuário (Pré-Teste)

Antes de iniciarem as tarefas no protótipo, os usuários responderam a um breve questionário para validar o enquadramento no público-alvo. O resumo das respostas confirmou a diversidade de perfis atendidos pelo sistema:

- **Usuário 1 (Roberto):** Perfil focado no cuidado familiar. Relatou que agenda consultas médicas frequentemente (mensalmente) para dependentes (como seu pai, Sr. Carlos). Atualmente, sente falta de um sistema que centralize essas informações, pois acaba dependendo da memória ou de papéis.
- **Usuário 2 (Lucas):** Perfil prático e dinâmico. Vai ao médico de forma mais espaçada (semestral/anual) e confessou que não utiliza nenhuma ferramenta específica para se organizar, o que frequentemente resulta em esquecimento das datas. Valoriza muito integrações com WhatsApp.
- **Usuário 3 (Giselle):** Perfil organizado (representando a Persona Primária). Realiza consultas de rotina (trimestral/semestral) e atualmente utiliza o bloco de notas e a agenda do celular para não se perder. Tem receio de perder documentos físicos e guias médicas impressas.

---

### Conclusão da Avaliação por Observação do Usuário

A avaliação por observação demonstrou que o **MedFEI** possui um alto nível de aceitação e cumpre com eficácia as metas de usabilidade propostas na fase de concepção. A interface provou ser intuitiva, permitindo que usuários com diferentes níveis de familiaridade tecnológica (desde os mais analógicos até os mais dinâmicos) completassem o fluxo principal de agendamento em poucos minutos, sem necessidade de intervenção dos avaliadores.

**Pontos Fortes Validados:**
* **Curva de Aprendizado e Praticidade:** O tempo médio de cadastro (menos de 1 minuto) e a facilidade de permissões iniciais foram elogiados de forma unânime ("muito prático").
* **Notificações:** A funcionalidade de integração com WhatsApp e notificações nativas (*Push*) atendeu perfeitamente à dor dos usuários que costumam esquecer compromissos.
* **Digitalização de Documentos:** A opção de acionar a câmera ou galeria para anexar guias médicas em PDF/JPEG durante o agendamento foi o recurso de maior destaque, superando as expectativas do perfil organizado (Giselle).
* **Gestão Familiar:** A funcionalidade de gerenciar e alternar para a visão de "Dependentes/Familiares" funcionou de forma fluida.

**Oportunidades de Melhoria (Gargalos Identificados):**
Apesar do alto índice de sucesso, a observação revelou pequenos atritos na interação que servirão como base para futuras iterações (melhorias de Front-End):
1. **Autocompletar / UX de Formulários:** Houve a sugestão válida de automatizar o preenchimento da clínica e endereço atrelados ao médico selecionado, reduzindo o esforço cognitivo e os cliques durante um novo agendamento.
2. **Atualização de Estado (Bug Visual):** Foi reportado um comportamento inesperado onde o painel de "Histórico" não refletiu instantaneamente as múltiplas consultas recém-agendadas sob o filtro de "Familiar", exigindo uma atualização de tela ou navegação extra.

**Veredito Final:**
O sistema demonstra maturidade na sua Arquitetura de Informação e cumpre os princípios ergonômicos da ISO 9241. As poucas barreiras encontradas não impediram a conclusão da tarefa principal (agendamento). O protótipo está validado pelo usuário final e pronto para etapas avançadas de desenvolvimento e refinamento de código.
