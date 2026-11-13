## Avaliação de IHC através de Inspeção Heurística

A avaliação heurística foi conduzida pelos membros da equipe (Gustavo, João Pedro e Luan) analisando todas as telas do protótipo **Saúde+** com base nas Dez Heurísticas de Nielsen (1994). O objetivo foi identificar violações de usabilidade e classificá-las de acordo com seu Grau de Severidade (0 a 4).

### 1. Violações Heurísticas Encontradas
*(Consolidado das avaliações individuais da equipe)*

**Avaliador: Gustavo Souza**
| Heurística Violada | Descrição do Problema | Severidade (0 a 4) | Print da Tela |
| :--- | :--- | :---: | :--- |
| **H7. Flexibilidade e eficiência de uso** | No formulário de "Nova Consulta", após o usuário selecionar a "Clínica", o sistema exige a digitação manual do "Local / Endereço". Isso gera ineficiência, pois o sistema já deveria preencher o endereço automaticamente com base na clínica selecionada. | **2** (Simples) | <img width="1920" height="710" alt="image" src="https://github.com/user-attachments/assets/5aeb7ef2-0b43-4993-97b2-5f7728529265" /> |
| **H10. Ajuda e documentação** | Não há um botão de "Ajuda" (FAQ ou Suporte) visível no Dashboard ou na tela de Perfil para orientar usuários inexperientes sobre como adicionar ou gerenciar "Familiares/Dependentes". | **1** (Cosmético) | <img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/a173cb25-42ff-41f7-b24f-c30d69850766" /> |

**Avaliador: João Pedro**
| Heurística Violada | Descrição do Problema | Severidade (0 a 4) | Print da Tela |
| :--- | :--- | :---: | :--- |
| **H1. Visibilidade do status do sistema** | Após agendar uma consulta para um Familiar (ex: Sr. Carlos), ao navegar para a aba "Histórico" e aplicar o filtro "Familiar", a nova consulta não apareceu de imediato, sugerindo uma falha na atualização de estado da tela em tempo real. | **3** (Grave) | <img width="1920" height="930" alt="image" src="https://github.com/user-attachments/assets/9bcb6977-8817-47e7-b9fc-89572f3405a2" /> |
| **H3. Controle e liberdade para o usuário** | Durante o agendamento, se o usuário clicar acidentalmente fora da janela (modal) ou no botão de voltar do navegador, todos os dados preenchidos são perdidos sem um aviso de confirmação (ex: "Deseja realmente sair? Os dados serão perdidos"). | **3** (Grave) | <img width="1920" height="928" alt="image" src="https://github.com/user-attachments/assets/34feba64-a739-4eab-a190-645e08410cea" /> |

**Avaliador: Luan Salandini**
| Heurística Violada | Descrição do Problema | Severidade (0 a 4) | Print da Tela |
| :--- | :--- | :---: | :--- |
| **H1. Visibilidade do status do sistema** | Ao clicar no botão "Salvar agendamento", o sistema não exibe nenhum indicador visual de carregamento (como um *spinner* ou mudança de texto para "Salvando..."). Se a internet oscilar, o utilizador pode achar que não clicou e apertar o botão várias vezes. | **2** (Simples) | <img width="1920" height="931" alt="image" src="https://github.com/user-attachments/assets/c1404983-85c2-4a63-ad3e-39370183dcef" /> |
| **H5. Prevenção de erros** | Na seleção de data no Calendário para agendamento, o sistema permite que o usuário clique em dias que já passaram (datas retroativas), retornando o erro apenas ao tentar salvar, em vez de desabilitar (ficar cinza) os dias passados. | **2** (Simples) | <img width="1920" height="927" alt="image" src="https://github.com/user-attachments/assets/8b10515a-611f-49c5-8e31-e1d93559988f" /> |

---

### 2. Indicação de Boas Práticas - Heurísticas Não Violadas
*(Exemplos de onde o Saúde+ atendeu perfeitamente aos princípios de Nielsen - Solução em Equipe)*

- **H1. Visibilidade do status do sistema:** Atendida ao exibir um modal de *feedback* imediato ("Consulta agendada!") com um ícone de "check" verde assim que o usuário finaliza a marcação.
- **H2. Compatibilidade entre sistema e mundo real:** O design da aba "Calendário" simula fielmente a aparência de uma agenda de papel de parede/smartphone, utilizando ícones e formatos de calendário que os pacientes já usam no dia a dia.
- **H3. Controle e liberdade para o usuário:** Atendida na funcionalidade de "Excluir consulta" (botão vermelho claro) dentro dos detalhes da marcação, permitindo que o usuário cancele rapidamente um agendamento feito por engano.
- **H4. Consistência e padrões:** As cores primárias (tons de azul para ações principais de salvar/continuar) e o formato dos botões mantêm o mesmo padrão visual do início ao fim em todas as telas.
- **H5. Prevenção de erros:** O sistema possui o "Alerta de conflito", que bloqueia e avisa preventivamente o usuário caso ele tente agendar duas consultas no mesmo dia com horários e distâncias incompatíveis.
- **H6. Reconhecimento em lugar de lembrança:** O Dashboard possui a seção "Próxima consulta" em destaque, assim o usuário reconhece imediatamente seu próximo compromisso sem precisar forçar a memória ou navegar até o calendário.
- **H7. Flexibilidade e eficiência de uso:** A interface oferece "Atalhos rápidos" na página inicial (ex: Nova consulta, Meus documentos), criando uma rota mais curta e eficiente para as tarefas mais comuns.
- **H8. Projeto minimalista e estético:** A tela de "Perfil" possui uma interface limpa, dividida em blocos com bastante respiro em branco (white space), sem excesso de informações que não sejam focadas nas permissões e cadastro.
- **H9. Auxiliar os usuários a reconhecer, diagnosticar e recuperar erros:** No cadastro, o campo de senha orienta o usuário antecipadamente com a mensagem "Mínimo de 6 caracteres", evitando que ele tente salvar senhas curtas e falhe.
- **H10. Ajuda e documentação:** Os *placeholders* (textos cinzas dentro dos campos de preenchimento, como "Seu nome completo" ou "Digite a senha novamente") atuam como uma documentação contextual que guia o usuário sem a necessidade de um manual extenso.
