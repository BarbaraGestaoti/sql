# 💻 Queries SQL & Scripts de Análise

Esta pasta contém o dicionário técnico de scripts SQL desenvolvidos para a extração, limpeza e modelagem de dados no setor de saúde. Os códigos foram estruturados seguindo as melhores práticas de Analytics Engineering, com foco em performance, legibilidade e governança de dados brutos.

Todos os exemplos utilizam uma abordagem prática voltada para cenários de Saúde Pública (Vigilância) e Gestão Hospitalar (Faturamento e Assistência).

---

## 🛠️ Sumário de Estruturas Disponíveis

| # | Padrão SQL | Aplicação Prática na Saúde | Objetivo Técnico |
|---|---|---|---|
| 1 | **Consulta com Filtros** | Auditoria de atendimentos por especialidade | Filtragem de linhas e ordenação temporal |
| 2 | **Campos Calculados** | Indicadores clínicos (ex: Taxa de Letalidade) | Regras de negócio e prevenção de divisão por zero |
| 3 | **Agregações** | Ocupação de leitos, faturamento e média de permanência | Consolidação macro gerencial (`GROUP BY`) |
| 4 | **INNER JOIN** | Cruzamento de prontuários com dados demográficos | Integração de tabelas e cruzamento de chaves |
| 5 | **CASE WHEN** | Classificação de risco e faixas etárias epidemiológicas | Lógica condicional e padronização |
| 6 | **COALESCE** | Higienização de cadastros com dados ausentes | Tratamento de valores nulos (`NULL`) |

Quando houver atualizações sobre outras queries aplicadas, incluo nas pastas.
