# Requisitos e avaliação do framework: o que o TCC1 previa e como resolver

**Data:** 08/11/2026 · **Para:** decisão com as orientadoras (N3). Nada foi retirado do plano sem justificativa.

## 1. O que o TCC1 prometeu

Seção 8 e Tabela 13 do TCC1: "(iii) identificação dos requisitos necessários; (iv) desenvolvimento do framework de governança e uso responsável da IA no Ensino Superior; e (v) avaliação do framework", com avaliação prevista para novembro.

## 2. Enquadramento metodológico

O framework é um **artefato**; por isso a pesquisa de Design Science (DSR) é o enquadramento adequado (Hevner et al., 2004). No processo de Peffers et al. (2007), as etapas do TCC1 correspondem a:

| Etapa DSR (Peffers et al., 2007) | Etapa do TCC1 | Situação em 08/11/2026 |
|---|---|---|
| Identificar o problema | Lacunas da revisão terciária | Feito (TCC1 + TCC2, RQ1–RQ4) |
| Definir objetivos da solução | (iii) Requisitos | **Feito agora:** 22 requisitos rastreáveis (`Requisitos_Derivados.md`) |
| Projetar e desenvolver | (iv) Framework | Feito (04/11) e **revisado agora** (`Revisao_Critica_Framework.md`) |
| Demonstrar | — | Não previsto; pode ser feito com um caso ilustrativo (aplicar o diagnóstico a documentos públicos de uma IES) |
| Avaliar | (v) Avaliação | **Parcial:** avaliação analítica ex ante feita; avaliação com pessoas pendente de decisão |
| Comunicar | TCC2 e publicação | Em andamento |

## 3. Etapa de requisitos: resolvida com justificativa

A identificação de requisitos foi feita como derivação analítica a partir de duas fontes: os achados dos 34 estudos e a literatura de referência. Cada requisito informa a origem e a natureza da sustentação. Justificativa metodológica: em DSR, os objetivos da solução podem ser inferidos do problema e do conhecimento existente (Peffers et al., 2007); a revisão terciária é exatamente esse conhecimento. **Limite:** os requisitos não foram priorizados por partes interessadas. Isso é avaliado na etapa 4.

## 4. Etapa de avaliação: opções

Segundo o FEDS (Venable et al., 2016), a avaliação pode ser **ex ante** (antes do uso real) ou **ex post**, e **artificial** (sem uso em contexto real) ou **naturalística**. Para um framework conceitual ainda não usado, com risco principal de ser incompleto ou pouco útil, a estratégia indicada começa ex ante e artificial e evolui para naturalística.

| Opção | O que é | Já feito? | Prazo até 23/11 | Exige CEP? | O que entrega |
|---|---|---|---|---|---|
| **A. Analítica (ex ante, artificial)** | Cobertura de temas do corpus e de princípios de referência; consistência; rastreabilidade (Prat et al., 2015) | **Sim** (Seção 6 da revisão crítica) | Cabe | Não | Completude e coerência demonstradas; utilidade não demonstrada |
| **A + demonstração** | Aplicar os 22 requisitos como lista de diagnóstico a documentos públicos de IES (ex.: a política de IA de uma universidade, se publicada) | Não | Cabe (≈ 6–8 h) | Não (documentos públicos; Res. CNS 510/2016, art. 1.º, parágrafo único, II) | Mostra que o framework é aplicável e onde é vago |
| **B. Especialistas (ex ante, avaliação com pessoas)** | Questionário com 5–10 especialistas (docentes de computação/educação, gestores de TI e de graduação) avaliando clareza, relevância e completude de cada componente e requisito | Não | **Não cabe** | **Provavelmente sim:** TCC com participantes humanos deve submeter protocolo ao sistema CEP/Conep (Res. CNS 510/2016, art. 1.º, VIII, § 1.º; Ofício Circular n.º 17/2022/CONEP) | Validade de conteúdo percebida |
| **C. Delphi (ex ante, consenso)** | Duas ou três rodadas com painel de especialistas (Okoli; Pawlowski, 2004) | Não | Não cabe | Sim | Consenso e priorização |
| **D. Naturalística (ex post)** | Uso do framework por uma IES real e análise dos efeitos | Não | Não cabe | Sim | Utilidade e efeito reais |

## 5. Recomendação para discutir com as orientadoras

1. **No TCC2:** opção A (já feita) + demonstração com documentos públicos. Declarar no texto que a avaliação com pessoas não foi realizada, com dois motivos verificáveis: exigência de protocolo no CEP para TCC com participantes humanos e prazo de entrega (23/11/2026).
2. **Incluir no TCC2 o protocolo da opção B** (instrumento, critérios, perfil dos especialistas, análise) como apêndice ou trabalho futuro, para que a avaliação seja executável numa continuação (iniciação científica ou mestrado).
3. **Registrar como desvio** do plano do TCC1, no Apêndice D: "avaliação do framework restrita a avaliação analítica ex ante; avaliação com especialistas planejada e não executada", com a justificativa acima.

Se as orientadoras preferirem a opção B ainda no TCC2, é preciso confirmar com o CEP da UNIPAMPA se o caso se enquadra em alguma dispensa e, em caso negativo, rever o cronograma de defesa.

## 6. Esboço do instrumento para a opção B (para apêndice ou trabalho futuro)

Para cada componente (G1, G2, C1–C6) e cada requisito (R01–R22), escala de 1 a 5:

- **Clareza:** a definição é compreensível sem explicação adicional?
- **Relevância:** o componente ou requisito é importante para uma IES brasileira?
- **Aplicabilidade:** a IES conseguiria implementá-lo com os recursos usuais?

Perguntas abertas: componentes faltantes; componentes redundantes; requisitos inviáveis.
Análise: mediana e intervalo interquartil por item; índice de validade de conteúdo por item como critério de corte, a definir com as orientadoras.
