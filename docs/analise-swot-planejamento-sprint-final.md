# Diagnostico Situacional - Sprint Final

Projeto: ConsultaFacil

## 1. Analise SWOT

### 1.1 Forcas

1. Backlog estruturado em epicos e historias, com labels e prioridades definidas
2. Template de Pull Request ja configurado no repositorio
3. Dominio do projeto (agendamento de consultas) e simples e objetivo

### 1.2 Fraquezas

1. Nenhuma issue concluida ate o momento (0 fechadas, 9 abertas)
2. Pipeline de CI ainda sem linter e checagem de qualidade configurados
3. Squad composta por uma unica pessoa, sem redundancia em caso de imprevisto

### 1.3 Oportunidades

1. Tema simples facilita o entendimento da banca avaliadora
2. Estrutura de labels ja pronta agiliza a priorizacao MoSCoW
3. Issue de Linter/CI ja aberta, restando apenas finalizar

### 1.4 Ameacas

1. Data da apresentacao e inegociavel
2. Progresso zerado em issues concluidas aumenta o risco de atraso
3. Dependencia total de uma unica pessoa no desenvolvimento

## 2. Matriz TOWS

| Vetor | Cruzamento | Acao operacional |
|---|---|---|
| Ofensivo | Forca interna + Oportunidade externa | Usar o backlog ja organizado para apresentar o progresso de forma clara a banca |
| Reforco | Fraqueza interna + Oportunidade externa | Finalizar a issue de Linter/CI antes da entrega, aproveitando que ja esta aberta |
| Confronto | Forca interna + Ameaca externa | Priorizar as historias de maior prioridade (H1, H2, H3) para garantir entrega mesmo com prazo apertado |
| Sobrevivencia | Fraqueza interna + Ameaca externa | Cortar do escopo (wont-have) a historia H6, de prioridade baixa, para concentrar esforco no fluxo nuclear |

## 3. Plano de Contingencia

Ambiente de desenvolvimento local configurado com dados de teste pre-carregados, permitindo executar a demonstracao do fluxo de cadastro, busca e agendamento mesmo em caso de falha de conexao ou indisponibilidade de servicos externos.
