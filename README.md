# Sistema Inteligente de Perfil e Evolução Docente (Monday.com + IA)

Repositório de documentação técnica e arquitetura do projeto de criação de perfil 360º de professores na Monday.com.

## Documentos do Projeto

1. [**Plano de Coleta de Dados, Arquitetura e Fluxos Mermaid**](./plano_perfil_professor_monday.md)
   - Modelo relacional de Boards na Monday.com (Chave única por E-mail/CPF)
   - Plano de coleta passiva (Agendamento, Design Instrucional, Suporte e Assistência ao Docente) e ativa (Pós-Gravação e Situações Eventuais)
   - Fluxos de trabalho completos em Mermaid
   - Governança, fases de implementação e backlog

2. [**Motor de Pontuação, Cálculo de Risco de Abandono e Prompt de IA**](./motor_ia_e_pontuacao.md)
   - Fórmulas determinísticas das 4 Dimensões (Didática/Expressão, Fluência Digital, Comprometimento/Assiduidade e Relacionamento/Abertura)
   - Cálculo de evolução histórica (Delta vs. Baseline do Trello)
   - Índice de Risco de Abandono (IRA)
   - Estrutura de Payload JSON e System Prompt de produção para o LLM
