# 📊 Scripts SQL para Monitoramento e Análise de Banco de Dados Oracle

Este repositório reúne uma coleção de scripts SQL desenvolvidos para apoiar DBAs e desenvolvedores na monitoração do banco de dados Oracle, análise de desempenho e identificação de gargalos. Os scripts são úteis para diagnosticar problemas, otimizar consultas e extrair estatísticas detalhadas do ambiente.

---

## 📂 Conteúdo

| Script                                    | Descrição                                                                        |
|-------------------------------------------|----------------------------------------------------------------------------------|
| `consultar_temp_sql.sql`                   | Consulta o uso da tablespace temporária por sessões e operações em andamento.    |
| `consultar_top_buffers_queries.sql`       | Identifica as queries que apresentam maior consumo de buffers no banco de dados. |
| `consumo_queries_estatisticas.sql`        | Exibe estatísticas detalhadas sobre o consumo de recursos pelas queries.         |
| `consumo_queries_mais_executadas.sql`     | Lista as queries mais executadas no banco de dados.                             |
| `consumo_queries_recursos_por_schema.sql` | Apresenta o consumo de recursos agrupado por schema.                            |
| `pesquisar_comandos_executados.sql`       | Pesquisa os comandos SQL executados recentemente no banco.                      |
| `pesquisar_queries_candidatas_compartilhamento.sql` | Identifica queries candidatas para otimização e compartilhamento.              |
| `pesquisar_queries_sessao.sql`             | Lista as queries em execução por sessão ativa.                                 |
| `pesquisar_queries_sga_texto.sql`          | Pesquisa queries armazenadas na SGA com base no texto informado.                |
| `ver_sql_gerando_redo.sql`                 | Verifica as queries que estão gerando alto volume de redo logs.                 |

---

## 🛠️ Pré-requisitos

- Banco de dados Oracle em execução.
- Permissões adequadas para execução de scripts de monitoramento.
- Ferramenta para execução de scripts SQL (SQL*Plus, SQL Developer, etc.).

