# Protocolo do levantamento de referências do framework (registrado em 08/11/2026, antes da execução)

## Etapa 1 – Snowballing para trás a partir do corpus
- Base: OpenAlex (api.openalex.org), campo referenced_works, consultado em 08/11/2026.
- Semente: 40 estudos = 34 incluídos + 6 âncoras do TCC I (ids.tsv).
- Consulta por estudo (duas por estudo; o OpenAlex aceita até 6 termos por filtro e não reduz palavras ao radical):
  A: works?filter=cited_by:<ID>,title.search:framework|frameworks|guidelines|principles|governance|ethics
  B: works?filter=cited_by:<ID>,title.search:ethical|policy|policies|regulation|responsible|literacy
- Estudos sem lista de referências no OpenAlex (referenced_works_count <= 1) não puderam ser usados: S289 (1) e I81 (0).
- Critérios de inclusão (triagem por título; em caso de dúvida, resumo):
  SC1 obra citada por pelo menos um estudo da semente (segundo o OpenAlex);
  SC2 a obra propõe, sintetiza ou analisa princípios, frameworks, diretrizes, políticas, governança, regulação ou letramento de IA (em geral ou na educação), ou ética de dados educacionais.
- Critérios de exclusão: diretrizes de relato ou método de revisão (PRISMA, AMSTAR, scoping etc.); estudos primários empíricos sem proposta de princípios ou framework; obras não relacionadas a IA ou dados.
- Classificação: citada por >= 2 estudos da semente = núcleo; citada por 1 = complementar.
- Limitação conhecida: o OpenAlex não registra todas as referências (ex.: estudos com referenced_works_count = 0 ou baixo) e quase não indexa documentos normativos (UNESCO, leis).

## Etapa 2 – Busca estruturada
(registrada antes de executar; ver BUSCA.md)

Resultados: ver RESULTADO.md.

## Nota de execução
- Para estudos com até 60 referências no OpenAlex, a lista completa de referências foi baixada em uma consulta (works?filter=cited_by:<ID>) e o mesmo filtro de palavras do título (conjuntos A e B) foi aplicado localmente. O resultado é o mesmo da consulta filtrada; a mudança só reduz o número de consultas, que estavam sendo limitadas pelo OpenAlex.
