# Etapa 2 – Busca estruturada (registrada em 08/11/2026, antes da execução)

## Objetivo
Encontrar, de forma reproduzível, a literatura mais influente sobre cada componente do framework
(G1, G2, C1–C6) e verificar se as referências usadas na primeira versão do framework aparecem nela.

## Base e parâmetros
- Base: OpenAlex (api.openalex.org/works), consultada em 08/11/2026.
- Campo: título (`title.search`), com operadores booleanos e frases entre aspas.
- Filtro: `type:article|review` (artigos e revisões; inclui artigos de conferência indexados como article).
- Ordenação: `cited_by_count:desc` (número de citações no OpenAlex, usado como indicador de influência).
- Corte: os 20 primeiros resultados de cada consulta são triados.
- Sem restrição de ano.

## Consultas (uma por componente; B9 cobre políticas institucionais)
| Código | Componente | Consulta no título |
|---|---|---|
| B1 | G1 | "AI governance" OR "artificial intelligence governance" |
| B2 | G1/princípios | ("AI ethics" OR "ethics of artificial intelligence") AND (guidelines OR principles) |
| B3 | todos (educação) | ("artificial intelligence" OR AI) AND education AND (ethics OR ethical) |
| B4 | C1 | "human-centered AI" OR "human-centered artificial intelligence" OR "human-AI interaction" |
| B5 | G1/G2 | "algorithmic auditing" OR "AI accountability" OR "algorithmic accountability" |
| B6 | C3 | "learning analytics" AND (ethics OR ethical OR privacy) |
| B7 | C6 | "AI literacy" |
| B8 | C2 | (ChatGPT OR "generative AI") AND (assessment OR "academic integrity") |
| B9 | G1 (educação) | (ChatGPT OR "generative AI") AND (policy OR policies OR guidelines) AND ("higher education" OR university) |
| B10 | C4 | ("algorithmic bias" OR fairness) AND education |
| B11 | C5 | (explainable OR explainability) AND education |

## Critérios
- Inclusão: SC2 da Etapa 1 (a obra propõe, sintetiza ou analisa princípios, frameworks de orientação, diretrizes,
  políticas, governança, regulação ou letramento de IA, ou ética de IA/dados educacionais; em geral ou na educação).
- Exclusão: os mesmos da Etapa 1 (X-E1 método/relato; X-E2 estudo primário empírico sem proposta de princípios ou
  framework; X-E3 sem relação com IA ou dados; X-SC2 contribuição principal fora do SC2, inclusive obras de outro
  setor específico, como saúde) e X-SEM (estudo do corpus).
- Triagem por título; resumo do OpenAlex quando houver dúvida.

## Regras de decisão sobre as 36 referências da primeira versão (fixadas antes da classificação)
1. Confirmada pela Etapa 1: citada por ≥ 1 estudo da semente (SC1) e atende SC2.
2. Confirmada pela Etapa 2: aparece entre os 20 resultados triados de alguma consulta B1–B11 e atende SC2.
3. Regra normativa: documento normativo ou institucional aplicável ao contexto do trabalho — lei brasileira
   (LGPD), projeto de lei brasileiro sobre IA (PL 2.338/2023), recomendação/orientação de organismo
   multilateral de que o Brasil é membro (UNESCO), regulamento de referência internacional (Regulamento
   (UE) 2024/1689) e norma técnica de referência (NIST AI RMF). Não dependem de busca bibliográfica.
4. Regra de método: obra original de um método efetivamente usado no trabalho (Design Science, DSRM,
   análise de framework conceitual, FEDS, taxonomia de avaliação, Delphi).
5. Referência que não se enquadra em 1–4: retirada do papel de fonte do framework. Se o componente que ela
   sustentava ficar sem apoio, usa-se uma obra incluída nas Etapas 1 ou 2 que trate do mesmo ponto (substituição).

## Limitações conhecidas
- Ordenar por citações favorece obras mais antigas e de áreas com mais citações.
- O corte em 20 resultados por consulta é arbitrário, mas fixado antes da execução.
- O OpenAlex pode classificar tipos e títulos de forma imperfeita.
