# BiblioTech

**Aplicativo mobile de apoio ao acompanhamento de empréstimos e renovações de livros para bibliotecas públicas.**

Projeto desenvolvido na disciplina de **Projeto Interdisciplinar (AAP2 e AAP3)** — Curso Superior de Tecnologia em Gestão da Tecnologia da Informação da **FATEC Barueri**.

---

## 📌 Sobre o Projeto

O **BiblioTech** é uma aplicação mobile complementar desenvolvida para modernizar a interação entre os leitores e a **Biblioteca Municipal Eny Cordeiro (Barueri/SP)**. 

O sistema atua de forma integrada ao fluxo presencial existente, reduzindo a dependência de atendimentos presenciais ou telefônicos para consultas de prazos e pedidos de renovação, sem substituir o controle administrativo interno da instituição.

---

## ⚙️ Funcionalidades (Versão 1)

- **Cadastro e Autenticação:** Criação de conta (nome, CPF, e-mail e senha) e login individualizado.
- **Recuperação de Senha:** Redefinição via link individual enviado ao e-mail cadastrado, com validade de **10 minutos**.
- **Empréstimos Ativos:** Visualização dos exemplares atualmente emprestados e suas datas de devolução.
- **Renovação Digital:** Solicitação de renovação pelo aplicativo com validação automática das regras de negócio e atualização imediata do prazo.
- **Notificação Preventiva:** Disparo automático de um alerta único **2 dias antes** da data prevista de devolução.
- **Histórico:** Consulta aos registros de empréstimos e devoluções vinculados à conta do leitor.

---

## 📋 Regras de Negócio

| Regra | Definição |
| :--- | :--- |
| **Prazo inicial** | 7 dias corridos a partir do registro presencial. |
| **Limite de renovações** | Até **2 renovações adicionais** por empréstimo. |
| **Acréscimo por renovação** | **+7 dias** somados à data prevista de devolução anterior. |
| **Prazo máximo total** | **21 dias** (7 dias iniciais + 2 renovações de 7 dias). |
| **Bloqueio por atraso** | Empréstimos vencidos não podem ser renovados digitalmente; a devolução deve ser feita presencialmente. |
| **Notificação preventiva** | Apenas **1 notificação** por empréstimo, enviada exatamente **2 dias antes** do vencimento. |
| **Operações presenciais** | Escolha, retirada e devolução física continuam sob responsabilidade do funcionário da biblioteca. |

---

## 🚫 Delimitação de Escopo (Não Contemplado na v1)

Para garantir a viabilidade técnica e o cumprimento do cronograma acadêmico, esta versão **não** contempla:

- Consulta ao catálogo completo ou pesquisa por título, autor e categoria.
- Verificação de disponibilidade de exemplares em tempo real.
- Reserva digital de livros.
- Registro digital de retirada ou devolução pelo próprio leitor.
- Cálculo, aplicação ou pagamento de multas.
- Atendimento via chat ou WhatsApp.
- Substituição integral do sistema administrativo da biblioteca.

---

## 📂 Artefatos e Documentação

O repositório reúne os entregáveis de engenharia de software e modelagem produzidos ao longo do projeto:

- **Modelagem de Processos (BPMN 2.0):**
  - `BPMN-AS-IS.pdf` — Mapeamento do fluxo atual de atendimento presencial.
  - `BPMN-TO-BE.pdf` — Mapeamento do processo futuro com suporte do aplicativo mobile.
- **Engenharia de Requisitos:** Requisitos Funcionais (RF), Requisitos Não Funcionais (RNF) e Regras de Negócio (RN).
- **Modelagem de Dados e Sistemas:** Modelo Entidade-Relacionamento (DER) e Diagramas UML.
- **Planejamento e Qualidade:** Plano de Negócio, gestão ágil e roteiros de testes.

---

## 👤 Autor e Instituição

- **Desenvolvedor:** Danilo de Castro Gomes
- **Instituição:** Faculdade de Tecnologia de Barueri — **FATEC Barueri**
- **Disciplina:** Projeto Interdisciplinar (AAP2 e AAP3)
