## 📊 Scripts SQL para Monitoramento e Análise Oracle
Este repositório contém uma coleção de scripts SQL desenvolvidos para ajudar DBAs e desenvolvedores a monitorar o banco de dados Oracle, analisar desempenho e identificar gargalos. Os scripts podem ser utilizados para diagnosticar problemas, otimizar consultas e obter estatísticas detalhadas do sistema.

## 📂 Conteúdo
##📄 Script	📝 Descrição

|---------------------------------------------------|---------------------------------------------------------------------------------|
`consultar_temp_sql.sql`                            |  Consulta o uso de tablespace temporário por sessões e operações em andamento.  |
`consultar_top_buffers_queries.sql`	                |  Identifica as queries com maior consumo de buffers no banco de dados.          |
`consumo_queries_estatisticas.sql`	                | Exibe estatísticas detalhadas sobre o consumo de recursos pelas queries.        |
`consumo_queries_mais_executadas.sql`	              |  Lista as queries mais executadas no banco de dados.                            |
`consumo_queries_recursos_por_schema.sql`	          |  Apresenta o consumo de recursos agrupado por schema.                           |
`pesquisar_comandos_executados.sql`	                |  Pesquisa os comandos SQL executados recentemente no banco.                     |
`pesquisar_queries_candidatas_compartilhamento.sql`	|  Identifica queries candidatas para otimização e compartilhamento.              |
`pesquisar_queries_sessao.sql`	                    |  Lista as queries em execução por sessão ativa.                                 |
`pesquisar_queries_sga_texto.sql`	                  |  Pesquisa queries armazenadas na SGA com base no texto informado.               |
`ver_sql_gerando_redo.sql`	                        |  Verifica as queries que estão gerando grande volume de redo logs.              |

