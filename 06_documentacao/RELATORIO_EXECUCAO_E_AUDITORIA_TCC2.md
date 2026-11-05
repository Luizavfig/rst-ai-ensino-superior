# RELATÓRIO DE EXECUÇÃO E AUDITORIA DO TCC2

**Autora:** Luiza de Campos Velasque Figueiredo (UNIPAMPA, Engenharia de Software)
**Data desta auditoria:** 05/11/2026
**Objeto:** TCC2, revisão terciária sobre IA no ensino superior (versão consolidada de 04/11/2026)
**Repositório:** https://github.com/Luizavfig/rst-ai-ensino-superior

## Como ler este relatório

Cada atividade recebe um destes status:

| Status | Significado |
|---|---|
| PRONTA | Já existia antes desta auditoria e não foi alterada |
| REVISADA | Existia e foi conferida nesta auditoria, sem alteração |
| CORRIGIDA | Existia e foi alterada nesta auditoria |
| PRODUZIDA AGORA | Não existia e foi criada nesta auditoria |
| PENDENTE | Não foi feita; o motivo está descrito |

Planejado e executado são tratados à parte: o que o protocolo previa e não foi feito está no Apêndice D do TCC2 e na Seção 5 deste relatório.

**Resumo em uma frase.** O texto do TCC2 e a análise dos 53 estudos já estavam prontos em 04/11/2026 (34 incluídos, 19 excluídos, 5 não recuperados); esta auditoria conferiu os números por recálculo (90 de 91 conferências confirmadas, com 1 diferença explicada), reconstruiu a planilha e a figura do PRISMA que faltavam, organizou o repositório e registrou o que ainda depende da orientadora e da autora. O TCC2 **não deve ser considerado concluído** enquanto houver pendências das seções 14 e 15.

**Limite desta auditoria.** Os 53 PDFs não foram reabertos campo a campo nesta etapa. A conferência contra os PDFs existe em três camadas anteriores: as fichas F01 a F30 com página e trecho, a auditoria independente de 04/11/2026 (página e trecho das 19 exclusões) e a leitura independente de 47 PDFs feita na Fase 1 desta conversa. Esta auditoria cruzou essas camadas por autor e ano e recalculou os números. Ela não substitui a conferência humana por amostragem (pendência L12).

---

## 1. Situação inicial do projeto

| Item | Situação encontrada | Status |
|---|---|---|
| Projeto "TCC" (claude.ai) | 63 documentos e 3 arquivos (TCC1 em PDF, protocolo em PDF, planilha de rastreabilidade do corpus). TCC2 consolidado em 04/11/2026 | PRONTA |
| TCC2 (texto) | `TCC2_Documento_Completo.md`: resumo, 8 seções, referências e apêndices A a E | PRONTA |
| Seleção | 34 incluídos, 19 excluídos, 5 não recuperados, após quatro revisões (metodológica, científica, editorial e auditoria independente) | PRONTA |
| Fichas | Fichas F01 a F30 e Q1 a Q8 dos 53 estudos lidos, em 8 lotes com versões v1 e v2 | PRONTA |
| Framework | Oito dimensões, com evidências por ID (Seção 6 do TCC2 e `TCC2_Framework_Conceitual_Final.md`) | PRONTA |
| Pendências | O1 a O12 (orientadora) e L1 a L12 (autora) | PRONTA |
| Repositório GitHub | 5 arquivos: README do protocolo, `protocolo_atualizado_TCC.pdf`, `Artigos_Citados_TCC_Funcao.xlsx` e `material-suplementar/` (PDF e XLSX de rastreabilidade do corpus do TCC1). Último commit antes desta auditoria: `96e8964` | REVISADA |
| Planilha final, figura PRISMA, texto de SCOPUS_391 | Citados no TCC2 e no registro de alterações (`TCC2_Planilha_Final_Incluidos_Excluidos.xlsx`, `figs/fig1_prisma.png`, `txt/SCOPUS_391`) mas **ausentes** do Projeto | PENDENTE (ver PT1) |
| Leitura independente (Fase 1) | Feita nesta conversa antes da auditoria: 47 dos 53 PDFs, em trilha paralela, sem aplicar CI e CE | PRONTA (uso apenas de apoio) |

O TCC2 estava com texto completo, mas **não concluído**: dependia de decisões da orientadora (O1 a O12) e de dados que só a autora tem (L1 a L12).

## 2. Materiais e arquivos encontrados

**Projeto "TCC" (grupos).** Planos e versões v2 a v7.4 (02/11 a 03/11); fichas dos lotes 01 a 08 (v1 e v2); consolidações e planilha em texto; fluxo PRISMA v2; rascunhos de resultados e framework v2; relatórios de auditoria (03/11 e 04/11); registro de alterações; registro de decisões metodológicas; referências e `.bib`; método e fluxo definitivos; framework final; pendências; auditoria independente da seleção; `TCC1_Esclarecimentos_e_Correcoes`; TCC1 em LaTeX corrigido (`TCC_unipampa_corrigido_v2.tex`).

**Anexos da conversa.** TCC1 em PDF, parecer do TCC1, `Artigos_Citados_TCC_Funcao.xlsx`, quatro prompts de continuação e a lista de arquivos do corpus (`corpus_arquivos.json`, 58 entradas com ID oficial e arquivo).

**Arquivos locais da Fase 1.** `fase1_db_persist.json` (52 registros, 47 lidos e 5 sem texto) e planilhas auxiliares de controle de acesso. Status: PRONTA, uso de apoio.

**Não encontrados:** planilha final do TCC2, figura PRISMA original, texto extraído de SCOPUS_391 (PT1).

## 3. Pesquisas científicas revisadas

| Conjunto | n | Origem | Papel no TCC2 |
|---|---|---|---|
| Registros brutos | 2.489 | Scopus 936; IEEE Xplore 336; ACM 1.217 (protocolo, Tabela 2) | Identificação (TCC1) |
| Triados | 1.306 | Scopus 981; IEEE Xplore 325 | Triagem (TCC1) |
| Aprovados | 968 | Scopus 861; IEEE Xplore 107 | Triagem (TCC1) |
| Subconjunto de análise aprofundada | 64 | Seleção por hierarquia de evidência (74 − 11 + 1) | Seleção (TCC1) |
| Âncoras | 6 | SCOPUS_657, 388, 473, 967, 374 e 412 (média 6,75; Bond 2024, Kovalainen 2025, Chong 2025, Fu e Weng 2024, Fu, Weng e Wang 2025, Rehman 2025) | Contexto e comparação qualitativa. Sem PDF nem ficha no TCC2. O mapa ID para autor das seis não consta nos documentos lidos |
| Relatórios buscados no TCC2 | 58 | 64 menos 6 âncoras | Texto completo |
| Não recuperados | 5 | SCOPUS_227, 365, 375, 678, 970 | Fora da síntese |
| Avaliados | 53 | Lidos em texto completo | Elegibilidade e Q1 a Q8 |
| Excluídos | 19 | CE1 5; CE2 1; CI2 3; CI3 5; CI5 1; CI1 4 | Apêndice C |
| **Incluídos** | **34** | 9 sem ressalvas; 25 com ressalvas | Síntese |

Status: PRONTA e REVISADA (todas as somas recalculadas, aba 3 da planilha).

## 4. Artigos efetivamente analisados

Os 58 relatórios, com título, autores, ano, DOI, tipo, nota, justificativa, relação com RQ1 a RQ4 e dimensões do framework, estão em `03_dados/csv/01_estudos_58.csv` e na aba `1_Estudos_58` da planilha. Resumo:

| ID | Estudo | Situação | Nota (equiv. 8) | Código ou ressalva |
|---|---|---|---|---|
| SCOPUS_838 | Robertshaw e Asher (2019) | Incluído | 6,00 | IA clássica (PICOC) |
| SCOPUS_594 | Al-Shabandar et al. (2024) | Incluído | 4,00 | — |
| SCOPUS_906 | Hooshyar et al. (2024) | Incluído | 7,50 | IA clássica (PICOC) |
| SCOPUS_968 | Kozhanov et al. (2024) | Incluído | 4,00 | CI4, Nível |
| SCOPUS_852 | Ncube e Ngulube (2024) | Incluído | 6,00 | IA clássica (PICOC) |
| SCOPUS_840 | Parambil et al. (2024) | Incluído | 5,50 | IA parcial |
| SCOPUS_596 | Samman (2024) | Incluído | 4,00 | CI4, CI2 |
| SCOPUS_639 | Sembey et al. (2024) | Incluído | 7,00 | IA parcial |
| SCOPUS_588 | Wu (2024) | Incluído | 7,50 | Nível |
| SCOPUS_593 | Wu e Yu (2024) | Incluído | 7,00 | Nível |
| SCOPUS_456 | Chen e Cheung (2025) | Incluído | 7,00 | — |
| SCOPUS_447 | Chernikova et al. (2025) | Incluído | 6,00 | IA clássica (PICOC) |
| SCOPUS_264 | Cui et al. (2025) | Incluído | 6,50 | Nível |
| SCOPUS_66 | Deng et al. (2025) | Incluído | 7,50 | Nível |
| SCOPUS_289 | Jafari et al. (2025) | Incluído | 4,50 | Nível |
| SCOPUS_15 | Jeon (2025) | Incluído | 6,50 | Nível |
| SCOPUS_9 | Kesgin (2025) | Incluído | 4,50 | Nível |
| SCOPUS_129 | Khumalo et al. (2025) | Incluído | 3,50 | Nível |
| SCOPUS_427 | Liu et al. (2025) | Incluído | 6,50 | Nível |
| IEEE_101 | Milinthapunya et al. (2025) | Incluído | 4,00 | CI4, CI2 |
| SCOPUS_234 | Qu et al. (2025) | Incluído | 5,00 | CI4 |
| SCOPUS_26 | Sofroniou et al. (2025) | Incluído | 7,50 | IA parcial |
| SCOPUS_439 | Wang e Guo (2025) | Incluído | 6,50 | Nível |
| SCOPUS_391 | Xia et al. (2025a) | Incluído | 7,50 | — |
| SCOPUS_117 | Xia et al. (2025b) | Incluído | 8,00 | — |
| IEEE_81 | Xie et al. (2025) | Incluído | 4,50 | CI4 |
| IEEE_132 | Yin et al. (2025) | Incluído | 4,50 | CI4 |
| SCOPUS_485 | Zhu et al. (2025) | Incluído | 7,00 | Nível |
| SCOPUS_196 | Jiang (2026) | Incluído | 6,00 | — |
| SCOPUS_12 | Jimoh et al. (2026) | Incluído | 5,71 | — |
| SCOPUS_431 | Kan et al. (2026) | Incluído | 7,00 | — |
| SCOPUS_380 | Mo et al. (2026) | Incluído | 5,50 | — |
| SCOPUS_159 | Sun e Tian (2026) | Incluído | 5,00 | Nível |
| SCOPUS_1 | Vehapi e Ziberi (2026) | Incluído | 5,00 | — |
| SCOPUS_38 | Analyzing the Impact of AI Integration on Student Learning Performance: A Within (2025) | Excluído | 2,50 | CE1 — Estudo primário |
| SCOPUS_521 | Using machine learning for continuous updating of meta-analysis in educational c (2024) | Excluído | 4,50 | CI2 não satisfeito — Estudo metodológico, não é revisão concluída |
| SCOPUS_947 | Utilising digital education to enhance learning accessibility in isolated areas (2024) | Excluído | 1,50 | CE1 — Estudo primário |
| SCOPUS_966 | Fostering Evidence-Based Education with Learning Analytics: Capturing Teaching-L (2020) | Excluído | 1,00 | CE1 — Estudo primário |
| SCOPUS_854 | Integrating Chat-GPT in the Classroom: A Study on Linear Algebra Learning in Hig (2025) | Excluído | 4,00 | CE1 — Estudo primário com meta-análise embutida |
| SCOPUS_225 | Natural Learning Revolution: Reimagining Higher Education Through AI-Enabled Ope (2025) | Excluído | 2,50 | CE1 — Estudo de métodos mistos com framework e piloto |
| SCOPUS_350 | Artificial Intelligence: Objective or Tool in the 21st-Century Higher Education  (2025) | Excluído | 2,50 | CE2 — Documento de política sem protocolo |
| SCOPUS_193 | Applications of learning analytics in the study of academic performance in highe (2025) | Excluído | 4,50 | CI2 não satisfeito — Protocolo de revisão, sem síntese |
| SCOPUS_965 | Authentic Assessments for Digital Education: Learning Technologies Shaping Asses (2022) | Excluído | 3,00 | CI2 não satisfeito — Bibliometria, não revisão de estudos |
| SCOPUS_23 | How Do Teachers Matter in the GenAI Era? A Meta-Analysis of the Relationship Bet (2026) | Excluído | 5,50 | CI3 não satisfeito — IA não é objeto nem variável |
| IEEE_230 | Exploring the Impact of the Metaverse on Promoting Students' Access to Quality E (2025) | Excluído | 7,00 | CI3 não satisfeito — IA não é o foco |
| SCOPUS_463 | Strategies for learning English in higher education: a systematic mapping (2025) | Excluído | 6,86 | CI3 não satisfeito — IA é uma entre várias estratégias |
| SCOPUS_531 | Prevailing Themes and Future Research Agendas in Higher Education: A Systematic  (2025) | Excluído | 7,43 | CI3 não satisfeito — IA é um de oito agrupamentos temáticos |
| SCOPUS_641 | Perspectives on the Future of Maintenance Engineering Education (2021) | Excluído | 4,00 | CI3 não satisfeito — IA apenas como exemplo |
| SCOPUS_210 | Структурный анализ и особенности развития цифровой компетентности будущих педаго (2025) | Excluído | 2,00 | CI5 não satisfeito — Texto em russo |
| SCOPUS_130 | Effects of AI feedback on students' English writing performance in higher educat (2026) | Excluído | 8,00 | CI1 não satisfeito — Publicado após 31/03/2026 |
| SCOPUS_277 | Artificial Intelligence in English as a foreign language learning: A systematic  (2026) | Excluído | 5,00 | CI1 não satisfeito — Disponível online após 31/03/2026 |
| SCOPUS_476 | Explainable artificial intelligence in cognitive learning psychology: A psychome (2026) | Excluído | 6,00 | CI1 não satisfeito — Disponível online após 31/03/2026 |
| SCOPUS_818 | From Adoption to Agency: How AI Chatbots Are Reshaping Educational Responsibilit (2025) | Excluído | 6,50 | CI1 não satisfeito — Aceito após 31/03/2026 |
| SCOPUS_227 | Can ChatGPT as a generative AI tool enhance university student academic achievem (2025) | Não recuperado | n/d | Sem texto completo |
| SCOPUS_365 | The Influence of GAI on the Development of Students' Higher-Order Thinking Abili (2026) | Não recuperado | n/d | Sem texto completo |
| SCOPUS_375 | Analytics Education: Conceptual Network Structure, Key Challenges and Opportunit (2026) | Não recuperado | n/d | Sem texto completo |
| SCOPUS_678 | Meta-Analysis of the Application of AI and Spiritual Science in Guiding Learner  (2025) | Não recuperado | n/d | Sem texto completo |
| SCOPUS_970 | The Effects of ALEKS on Mathematics Learning in K-12 and Higher Education: A Met (2021) | Não recuperado | n/d | Sem texto completo |

**Campos por artigo (pedido 1 da etapa final).** Preenchidos a partir do TCC2, da planilha consolidada e das referências: título, autores, ano, base de origem (pelo prefixo do ID), DOI, tipo de revisão, base de estudos, nota Q1 a Q8, nível de evidência, ressalva, código de exclusão, justificativa, resultado principal (Tabela 5), RQ1 a RQ4 e dimensões do framework. **Não replicados nesta planilha:** objetivo e país ou contexto (campo F05) de 52 dos 58, porque estão apenas nas fichas dos lotes (pendência PT2). País está registrado para 6 estudos do Lote 1. Para cinco estudos não recuperados, autores e DOI não constam nos documentos além do primeiro autor.

**Q1 a Q8 por critério.** Aba 2 da planilha (53 estudos, fórmulas ativas). Evidência textual de cada nota (trecho e página): fichas do Projeto (`TCC2_Fichas_Lote*_v2.md`), não replicada aqui.

## 5. Estudos brasileiros, governança de IA e frameworks

**Estudos brasileiros.** Nenhum estudo brasileiro foi identificado nos documentos disponíveis. Verificação feita: busca textual por "Brasil", "Brazil", "América Latina" e "português" no TCC2 completo, no protocolo e nos 52 registros da leitura independente. O TCC2 menciona "português" apenas no critério CI5. A leitura independente registra "América Latina" apenas como lacuna geográfica em SCOPUS_12 e SCOPUS_1. **Limite:** o país ou a afiliação (F05) de 52 dos 58 estudos não foi replicado nesta auditoria, de modo que a ausência de estudos brasileiros **não está provada**, apenas não foi encontrada. Conferir F05 nas fichas é a pendência PT2.

**Governança, políticas e regulação.** Nove estudos apontam regulação, governança e marcos éticos como tendência (SCOPUS_15, 129, 9, 12, 594, 596, 639, IEEE_101, IEEE_132). Privacidade com descrição de práticas e marcos: SCOPUS_852 (pós-graduação) e SCOPUS_840 (cibersegurança). Nenhum dos 34 avaliou a efetividade de políticas, práticas ou programas de formação (TCC2, Seção 5.5).

**Frameworks, modelos e diretrizes.** SCOPUS_159 propõe um framework conceitual de quatro componentes (captura de dados, análise de IA, avaliação e feedback, supervisão humana), não validado (ficha F16 e F29). SCOPUS_639 aponta falta de frameworks de desenho, avaliação e uso. SCOPUS_12 recomenda infraestruturas éticas e de governança (F28). SCOPUS_225 propõe um framework e foi excluído por CE1 (estudo de métodos mistos com piloto de 240 estudantes).

**Quais artigos fundamentam cada parte do TCC2:**

| Parte | Estudos | Fonte no TCC2 |
|---|---|---|
| RQ1, IA generativa e LLM (22) | IEEE_132, 15, 9, 12, 1, 196, 380, 431, IEEE_101, IEEE_81, 117, 234, 26, 264, 391, 427, 439, 456, 485, 66, 594, 968 | Tabela 4 |
| RQ1, chatbots (13) | 15, 1, 196, 431, IEEE_81, 117, 264, 391, 427, 456, 485, 588, 593 | Tabela 4 |
| RQ2, magnitudes de efeito (22) | IEEE_132, 1, 159, 196, 380, 117, 391, IEEE_81, 234, 26, 264, 427, 439, 456, 485, 66, 588, 593, 9, 906, 838, 447 | Tabela 5 |
| RQ2, benefícios descritivos (9) | 12, 15, 431, 129, 289, 840, 852, 968, 594 | Seção 4.6 |
| RQ3, riscos e preocupações éticas | Listas por tema | Tabela 6 |
| RQ4, lacunas e tendências | Listas por tema | Seção 4.8 |
| Framework, por dimensão | Ver seção 9 e aba `6_Framework` | Seção 6 |

As listas completas por tema estão em `03_dados/csv/01_estudos_58.csv` (colunas RQ1 a RQ4) e em `03_dados/csv/06_framework_rastreabilidade.csv`. Status: REVISADA (IDs das listas conferidos contra os 34 incluídos).

## 6. Etapas metodológicas realizadas

| Etapa | Como foi feita (fonte) | Números | Origem | Lacuna documental | Status |
|---|---|---|---|---|---|
| Bases | Scopus, IEEE Xplore, ACM Digital Library. Web of Science foi considerada e removida por falta de acesso institucional (protocolo, Seção 2.2) | 936; 336; 1.217 | TCC1 | ACM não incorporada à triagem (D1) | REVISADA |
| String de busca | Três blocos booleanos (IA, ensino superior, tipo de revisão), campos TITLE-ABS-KEY no Scopus e título e resumo em IEEE e ACM (protocolo, Seção 2.4). Validação com 5 artigos de controle, todos recuperados | 1 string unificada | TCC1 | Strings adaptadas por base constam do apêndice do protocolo; **o relatório de execução da busca não consta dos documentos** | REVISADA |
| Período | Estudos de 2019 a 2026, corte oficial da busca em 31/03/2026 (protocolo, CI1 e nota 1) | 2019 a 31/03/2026 | TCC1 | **Data de execução da busca não consta** (L1) | REVISADA |
| Duplicatas | Protocolo prevê remoção com Rayyan | n/d | TCC1 | **Número e ferramenta não constam** (L2, D3) | PENDENTE |
| Triagem por título e resumo | CE4 172; CE1 102; CE6 48; CE7 11 | 1.306 triados; 968 aprovados; 333 excluídos; 5 incertos | TCC1 | Incertos não reavaliados e sem ID (L4, D6) | REVISADA |
| κ de Cohen | Amostra de 10%, intervalo mínimo de 7 dias | κ = 0,466 (moderado; mínimo do protocolo 0,60) | TCC1 | Recalibração e tabela de contingência não constam (L5, D10) | REVISADA |
| Seleção para análise aprofundada | Hierarquia de evidência por título e resumo | 968 para 74 para 64 | TCC1 | Composição das 11 retiradas diverge entre documentos (L9, D8) | REVISADA |
| Recuperação de textos | Três vias do protocolo (Seção 4.4) | 53 de 58 | TCC2 | Tentativas não documentadas (L3, D12) | PENDENTE |
| Elegibilidade (texto completo) | CI1 a CI5 e CE1 a CE7, regras R1 a R7, revisora única | 34 incluídos; 19 excluídos | TCC2 | Regras aguardam a orientadora (O1) | PRONTA |
| Extração | Ficha F01 a F30 | 53 fichas | TCC2 | Apêndices e materiais suplementares fora do PDF não consultados | PRONTA |
| Qualidade | Q1 a Q8 (Sim 1,0; Parcial 0,5; Não 0); limiar de inclusão 3,0 | média 5,87 | TCC2 | Notas por item das âncoras indisponíveis | REVISADA (recalculada) |
| Síntese | Narrativa e quantitativa descritiva; sem meta-análise nova | contagens de menção | TCC2 | Sobreposição entre meta-análises não medida (D21) | REVISADA |
| Sensibilidade | Cenários A (30 estudos) e B (38 estudos) | Seção 4.9 do TCC2 | TCC2 | Depende de O1 e O5 | REVISADA (recalculada) |
| Framework | 8 dimensões derivadas dos achados | Seção 6 | TCC2 | Não validado (O8) | REVISADA |

**Decisões metodológicas registradas:** regras R1 a R7 (Seção 3.2 do TCC2); decisões V1 a V13 (`TCC2_Registro_Decisoes_Metodologicas.md`); alterações A1 a A22 (seção 10).

**Alterações em relação ao protocolo inicial:** inventário D1 a D22 (seção 11 e aba `5_Desvios`). As principais: ACM fora da triagem; 968 para 64 por seleção intencional; incertos não reavaliados; duplicatas sem contagem; ausência de data da busca e de pré-registro; κ abaixo de 0,60; revisora única; análises previstas e não feitas (sobreposição, comparação antes e depois de 2022, teoria preliminar).

## 7. Resultados obtidos

Valores do TCC2 (Seções 4 e 8), todos recalculados na seção 8 deste relatório.

- **Seleção.** 34 incluídos (33 de 2024 a 2026 e 1 de 2019), 19 excluídos, 5 não recuperados. Nota média 5,87 (mediana 6,0; mínimo 3,5; máximo 8,0). 19 estudos com nota 6,0 ou mais.
- **RQ1.** IA generativa (22 estudos) e chatbots (13) predominam. Tutoria e aprendizagem adaptativa 9; avaliação e feedback 4; learning analytics 5; ML, PLN e visão computacional 7.
- **RQ2.** 22 estudos relatam magnitudes de efeito: valores globais de 0,392 a 1,14 (g, d, SMD, ES) e correlações de 0,127 a 0,407. Os valores **não são comparáveis nem agregáveis**. Há heterogeneidade alta (I² de 71% a 97,6% em 9 estudos), sinais de viés de publicação (5) e ausência de acompanhamento de longo prazo. Alguns desfechos não mostram efeito (metacognição, autoeficácia, resolução de problemas).
- **RQ3.** Privacidade (12), dependência (11), letramento e políticas (9), viés (8), integridade (6), transparência (6), exatidão (4). 17 de 33 revisões com Q5 aplicável não avaliaram a qualidade dos primários.
- **RQ4.** Longo prazo (10), moderadores (9), viés regional (6). Tendências: governança (9), uso orientado (4), letramento (4), integração curricular (3).
- **Conclusão compatível com os dados (TCC2, Seção 5.2).** As revisões relatam, em geral, efeitos positivos de IA generativa em aprendizagem, motivação e engajamento, com evidência heterogênea, sem verificação da qualidade dos primários em metade dos casos e sem acompanhamento de longo prazo. Os dados não permitem concluir que a IA melhora a aprendizagem em geral.

Status: PRONTA e REVISADA.

## 8. Análises e cálculos realizados

Todas as fórmulas (233) estão ativas na planilha `03_dados/TCC2_Planilha_Auditoria.xlsx` e foram recalculadas no LibreOffice, sem células de erro.

| Cálculo | Dados de entrada | Fórmula | Resultado | Onde conferir |
|---|---|---|---|---|
| Nota equivalente em 8 pontos | Total bruto (soma de Q1 a Q8) e máximo aplicável (8, ou 7 se Q5 = N/A) | equivalente = total / máximo × 8 | SCOPUS_12: 5,0 / 7 × 8 = 5,71 | Aba 2 (colunas K a M, fórmulas) |
| Nota média dos 34 | 34 equivalentes | média aritmética | 5,87 | Aba 2, bloco de resumo |
| Mediana, mínimo e máximo | 34 equivalentes | MEDIAN, MIN, MAX | 6,00; 3,50; 8,00 | Aba 2 |
| Estudos por limiar de nota | 34 equivalentes | contagem de nota ≥ limiar | ≥2,0: 34; ≥3,0: 34; ≥4,0: 33; ≥6,0: 19 | Aba 2; Tabela 3 do TCC2 |
| Média por critério (Q1 a Q8) | Q1 a Q8 dos 34 (Q5 sem os N/A) | média da coluna | Q1 1,00; Q2 0,69; Q3 0,85; Q4 0,60; Q5 0,33; Q6 0,87; Q7 0,74; Q8 0,78 | Aba 2 |
| Q5 (avaliação da qualidade dos primários) | Q5 dos 33 com critério aplicável | contagem de 0, 0,5 e 1 | Não 17; Parcial 10; Sim 6 | Aba 2 |
| Média sem e com ressalvas | 9 e 25 equivalentes | média aritmética | 6,19 e 5,76 | Aba 4 |
| Cenário A (sem IA clássica) | 30 estudos (34 menos 838, 906, 447, 852) | média; contagem ≥ 6,0 | 30 estudos; média 5,81; 15 com nota ≥ 6,0 | Aba 4 |
| Cenário B (corte pela data da busca) | 38 estudos (34 mais 130, 277, 476, 818) | média; contagem ≥ 6,0 | 38 estudos; média 5,93; 22 com nota ≥ 6,0 | Aba 4 |
| Fluxo PRISMA | Contagens da Tabela 1 | somas e subtrações (968+333+5; 74−11+1; 64−6; 53+5; 19+34) | Todas fecham (12 conferências) | Aba 3 (fórmulas) |
| Anos dos incluídos | Ano de cada referência | contagem por ano | 2019: 1; 2024: 9; 2025: 18; 2026: 6 | Aba 4 |
| Contagens de menção (RQ1, RQ3, RQ4) | Listas de IDs das Tabelas 4 e 6 e da Seção 4.8 | tamanho da lista = número declarado | Todas coincidem | Aba 4 |

**Resultado das conferências.** 90 de 91 conferências confirmadas (aba `4_Conferencias`). A única diferença é o cruzamento com a leitura independente de PDFs (52 registros, 50 coincidem em primeiro autor e ano, 2 diferenças explicadas): SCOPUS_66 tem publicação online em dezembro de 2024 e ano de volume 2025 (o TCC2 usa 2025 e documenta, Seção 4.3), e SCOPUS_596 aparece como "Samman" no TCC2 e "Al Samman" na leitura dos PDFs (mesmo estudo).

**Fonte dos dados de entrada.** Totais e classes: tabelas do TCC2. Notas Q1 a Q8 por critério: aba `1_QUALIDADE` de `TCC2_Planilha_Consolidada` (03/11/2026). Os 34 totais da Tabela 2 foram reproduzidos a partir dessas notas, sem exceção, o que mostra que as notas da planilha de 03/11 são as mesmas usadas no texto de 04/11.

Status: PRODUZIDA AGORA (recálculo) sobre resultados PRONTOS.

## 9. Desenvolvimento das oito dimensões do framework

O framework é uma **proposta conceitual, não implementada nem validada** (TCC2, Seção 6). As dimensões 2 a 7 derivam de riscos, lacunas e recomendações nomeados pelas revisões; a dimensão 1 parte de um sinal de benefício associado à condição de uso; a dimensão 8 deriva das limitações do próprio conjunto de estudos. As dimensões se apoiam em menções de risco, descrições de práticas e recomendações, **não em evidência de efetividade** (Seção 5.5 do TCC2).

| Dimensão | Seção | Estudos (n) | Nota média dos estudos | Forte / Moderado / Fraco / Inconclusivo | Evidência que falta |
|---|---|---|---|---|---|
| D1 Uso pedagógico orientado | 6.1 | 7 | 6,21 | 1 / 5 / 1 / 0 | Teste controlado do moderador "orientação" |
| D2 Integridade e avaliação | 6.2 | 11 | 6,16 | 1 / 5 / 5 / 0 | Medidas de ocorrência e de efeito de políticas |
| D3 Privacidade e dados | 6.3 | 12 | 5,43 | 1 / 6 / 5 / 0 | Efetividade de práticas de privacidade em IES (nenhum dos 34 avaliou) |
| D4 Equidade e viés | 6.4 | 12 | 5,14 | 0 / 5 / 7 / 0 | Auditorias de viés em ferramentas educacionais |
| D5 Transparência e explicabilidade | 6.5 | 6 | 5,95 | 0 / 4 / 2 / 0 | Relação com confiança calibrada e aprendizagem |
| D6 Letramento e formação | 6.6 | 11 | 5,06 | 0 / 4 / 6 / 1 | Efeito de programas de formação |
| D7 Políticas e governança | 6.7 | 14 | 5,23 | 0 / 6 / 7 / 1 | Avaliação de políticas já adotadas por IES |
| D8 Monitoramento e qualidade da evidência | 6.8 | 18 | 5,71 | 2 / 10 / 6 / 0 | Estudos longitudinais; avaliação de qualidade dos primários; medida de sobreposição |

Cada dimensão tem definição, justificativa, evidências por ID, relações, implicações para IES e questões de investigação em `05_framework/Framework_8_dimensoes.md`. A relação estudo a estudo (108 linhas dimensão x estudo) está em `03_dados/csv/06_framework_rastreabilidade.csv`. Observações: (a) a coluna "Estudos (n)" acima é a união de todas as evidências da dimensão e por isso pode superar o número da Tabela 7, que conta só o indicador principal (6, 12, 8, 6, 9 e 9 para D2 a D7, coincidentes); (b) a Tabela 7 lista 4 estudos para a dimensão 1 e a Seção 6.1 lista 7; a rastreabilidade usa a lista da Seção 6.1, mais completa.

Status: PRONTA (texto de 04/11); REVISADA (listas de IDs conferidas contra os 34 incluídos; indicadores principais de D2 a D7 coincidem com a Tabela 7); PRODUZIDA AGORA (tabela de rastreabilidade em CSV e planilha).

## 10. Alterações e correções realizadas

**Em 03/11 e 04/11 (registro do Projeto, A1 a A22).** Já estavam prontas:

| # | Problema | Decisão | Evidência | Observação |
|---|---|---|---|---|
| A1 | Fluxo e rascunho v2 referiam 35 candidatos | Fechar a seleção por regras R1–R7; 34 incluídos após a auditoria independente (eram 30) | Protocolo §3–§4; PDFs dos 53 | Rascunho v2 e Fluxo PRISMA v2 superados |
| A2 | Dois "58" e dois "5" ambíguos | Nomear cada conjunto com IDs | TCC1 .tex; Planilha; Fichas | — |
| A3 | CE3/CE7 trocados | Alinhar ao protocolo | Protocolo §3 | — |
| A4 | Limiar 3,0 descrito como sensibilidade | Descrever como critério de inclusão §5 | Protocolo §5 | — |
| A5 | Revisor único como desvio | Limitação planejada | Protocolo §8.4 | — |
| A6 | Análises previstas não feitas | Registrar D21 | Protocolo §7.3 e §7.5 | — |
| A7 | CI1 × CE7 em 130, 277, 476 e 818 | Codificar CI1 não satisfeito; D22 | Protocolo CI1/CE7; fichas | Depende de O5 |
| A8 | SCOPUS_391 fora da Tabela Z | Incluir com valores do PDF | txt/SCOPUS_391 | Z = 22 (após auditoria independente) |
| A9 | Contagens de ano | Usar ano de referência (1/9/18/6) | Fichas F03 | SCOPUS_66: 2025 |
| A10 | Linguagem causal | "associadas" | Revisão científica | — |
| A11 | Dimensão 3 e SCOPUS_852 | Reescrever (852 incluído com ressalva) | Planilha (852 = IA clássica, R1) | — |
| A12 | DOI com ruídos nas fichas | Extração por regex; overrides | Fichas F07–F09 | — |
| A13 | Xia 2025 duplicado | 2025a/2025b | Referências | — |
| A14 | Citações aninhadas | Função cp() | Revisão editorial | — |
| A15 | Figura do PRISMA com setas erradas | Redesenho | Inspeção visual | — |
| A16 | Pendências externas e esclarecimentos do TCC1 | Redigir O1–O12, L1–L12 e T1–T16 | Revisões 1–3 | — |
| A17 | Referências | 34 + 10 conferidas; lacunas marcadas | Fichas; .tex TCC1 | Lacunas L8 |
| A18 | Corte de CI1 aplicado de forma desigual | Regra R7; 277 e 476 excluídos | PDFs p.1; protocolo nota 1 | Depende de O5 e L1 |
| A19 | R1 mais estrita que o PICOC | Incluir IA clássica (838, 906, 447, 852) com ressalva | Protocolo Tabela 1 e string | Depende de O3 |
| A20 | CE2 por relato incompleto | R3 revista; IEEE_101 e 596 incluídos com ressalva | Fichas F08–F12; PDFs | Depende de O4 |
| A21 | Sem sensibilidade para as decisões limítrofes | Cenários A (30) e B (38) | Planilha; final_data | — |
| A22 | Exclusões sem página do PDF | Página e trecho para as 19 | PDFs | — |

**Nesta auditoria (05/11/2026):**

| # | Alteração | Arquivo | Status |
|---|---|---|---|
| N1 | Caminho da figura no TCC2 trocado de `figs/fig1_prisma.png` para `../04_prisma/fig1_fluxo_prisma.png` (único trecho alterado do texto) | `02_tcc2/TCC2_Documento_Completo.md` | CORRIGIDA |
| N2 | Figura do PRISMA regenerada a partir das contagens da Tabela 1 (o original não estava disponível) | `04_prisma/fig1_fluxo_prisma.png` | PRODUZIDA AGORA |
| N3 | Planilha de auditoria reconstruída (10 abas, fórmulas) | `03_dados/TCC2_Planilha_Auditoria.xlsx` | PRODUZIDA AGORA |
| N4 | CSVs de rastreabilidade (7 arquivos) | `03_dados/csv/` | PRODUZIDA AGORA |
| N5 | Framework, fluxo PRISMA e referências extraídos do TCC2 sem alteração de conteúdo | `05_framework/`, `04_prisma/`, `07_referencias/` | PRODUZIDA AGORA |
| N6 | Arquivo `Artigos_Citados_TCC_Funcao.xlsx` movido para `03_dados/tcc1/` (histórico preservado com `git mv`) | `03_dados/tcc1/` | CORRIGIDA (organização) |
| N7 | README principal reescrito, com o texto do protocolo preservado | `README.md` | CORRIGIDA |

**Nenhum número, tabela, referência ou conclusão do TCC2 foi alterado.** Nenhuma estatística foi modificada para os números coincidirem.

## 11. Problemas encontrados e como foram resolvidos

**Desvios entre protocolo e execução (herdados do TCC1, já registrados no TCC2).**

| # | Item | Planejado | Executado |
|---|---|---|---|
| D1 | Bases | Três bases (Scopus, IEEE Xplore, ACM; protocolo, Tab. 2) | Duas bases na triagem (ACM não incorporada) |
| D2 | Contagem de identificação | 2.489 brutos (936 + 336 + 1.217) | 1.306 triados (981 + 325) |
| D3 | Duplicatas | Registro do número removido (§4.2) | [INFORMAÇÃO NÃO DISPONÍVEL NOS DOCUMENTOS FORNECIDOS] |
| D4 | Data e ferramenta da busca | Registro da data de execução | [INFORMAÇÃO NÃO DISPONÍVEL NOS DOCUMENTOS FORNECIDOS] |
| D5 | Pré-registro | Identificador do protocolo | Sem identificador de pré-registro nos documentos |
| D6 | Incertos da triagem (5) | Promoção ao texto completo (§4.3) | Não reavaliados; IDs não documentados |
| D7 | Passagem 968 → 64 | Texto completo de todos os elegíveis | Seleção intencional de 74 por hierarquia de evidência (tipo inferido de título e resumo), 64 após ajustes; 904 como contextualização |
| D8 | Composição das 11 retiradas (74 → 64) | — | Descrita de modo diferente no .tex v2 e na Auditoria Etapa 1; a soma fecha (74 − 11 + 1 = 64) |
| D9 | Avaliação de qualidade | Todos os incluídos | Seis no TCC1 (âncoras); 53 no TCC2 |
| D10 | Concordância (κ) | κ ≥ 0,60 | κ = 0,466 (amostra de 10%, intervalo ≥ 7 dias); recalibração não documentada |
| D11 | Revisor independente | Revisora única (protocolo §8.4), com medidas compensatórias | Sem segundo revisor na triagem nem no texto completo; as medidas compensatórias estão registradas apenas em parte (κ do TCC1) |
| D12 | Recuperação de textos | Três vias antes de CE5 (§4.4) | Tentativas não documentadas para 5 textos |
| D13 | Corte temporal | CI1: até 31/03/2026 (nota 1) | Quatro registros com publicação ou aceite posterior ao corte (SCOPUS_130, 277, 476 e 818) estavam no corpus de 968; três estudos de 2026 (SCOPUS_12, 1 e 196) só trazem a data de aceite, até 16/03/2026 |
| D14 | Redação de critérios | Protocolo: CI2, CE1, CE2, CE4, CE5, CE6 | TCC1 usa formulações próprias (por exemplo, CE4 como foco principal fora do escopo de IA) |
| D15 | Limiar de nota | Protocolo §5: inclusão com nota ≥ 3,0; sensibilidade em 2,0; 3,0; 4,0 | TCC1 usa o limiar de 3,0; TCC2 aplica e reporta os três cenários |
| D16 | Q5 em mapeamento e scoping | Leitura do protocolo por objetivo | Prática do TCC1: N/A só em mapeamento e scoping |
| D17 | Rótulo das questões | RQ1–RQ4 (protocolo) | QP1–QP4 no texto do TCC1; RQ1–RQ4 no TCC2 |
| D18 | IDs trocados | — | Divergência de IDs em 12, 641, 818 e 852 entre listas |
| D19 | Planilha de rastreabilidade | — | RST_Rastreabilidade não reproduz as contagens do TCC1 (estado de triagem diferente) |
| D20 | Nota † da Tabela 3 do TCC1 | — | Não reproduzível nos documentos (V5) |
| D21 | Análises previstas no protocolo e não realizadas | Matriz de sobreposição por amostragem (§7.5); comparação antes/depois de 2022 (§7.3); teoria preliminar (§7.1) | Não realizadas; comparação inviável (um único incluído anterior a 2024, SCOPUS_838) |
| D22 | Redação de CE3 e CE7 | CE3 duplicata; CE7 anterior a 2019 ou data não verificável (espelho de CI1) | TCC1 descreve CE7 como "fora da janela temporal"; aqui os quatro registros posteriores ao corte foram codificados como CI1 não satisfeito |

**Problemas encontrados nesta auditoria.**

| # | Problema | Como foi tratado | Situação |
|---|---|---|---|
| P1 | 40 dos 52 IDs gravados na base da Fase 1 são provisórios (por exemplo `SCOPUS_26x`) | Cruzamento por número do arquivo com `corpus_arquivos.json` (ID oficial). Ver `07_crosswalk_fase1_oficial.csv` | Resolvido; a base não foi usada para decisões |
| P2 | A leitura independente do #53 (SCOPUS_818) não aplicou o corte de CI1: o aceite é de 09/04/2026, após 31/03/2026 | A seleção oficial já exclui SCOPUS_818 por CI1 (Apêndice C). Erro apenas da trilha paralela | Resolvido |
| P3 | Trilha paralela da Fase 1 não aplica CI1 a CI5 e CE1 a CE7 e diverge da seleção oficial | Declarada como apoio; seleção oficial é a do Projeto (04/11) | Resolvido |
| P4 | Planilha final, figura PRISMA e texto de SCOPUS_391 citados mas ausentes do Projeto | Planilha reconstruída e figura regenerada dos documentos; originais não localizados | Parcial (PT1) |
| P5 | `TCC2_Planilha_Consolidada` (03/11) traz status de elegibilidade provisórios e superados (por exemplo SCOPUS_818 "Elegível") | Usada só para as notas Q1 a Q8, cujos 34 totais reproduzem a Tabela 2. Não usada para elegibilidade | Resolvido |
| P6 | Leitura independente cobre 47 de 53 PDFs; faltam SCOPUS_906, 968, 641, 965, 852 e 838 | Esses seis têm ficha oficial | Aberto (PT4) |
| P7 | Fichas dos lotes 2 a 8 não foram relidas integralmente nesta auditoria | Conferência apoiada no TCC2, na planilha de 03/11 e na leitura independente | Aberto (PT2, PT3) |
| P8 | Cópia do TCC2 no repositório foi transcrita da versão do Projeto sem acesso ao arquivo bruto | 91 conferências de consistência interna passaram; comparar com o arquivo do Projeto antes da entrega | Aberto (L12) |
| P9 | A referência de SCOPUS_838 não tem DOI | Mantida sem DOI (não criado) | Aberto (PT8) |

## 12. Arquivos produzidos e atualizados

**No repositório GitHub** (estrutura completa no `README.md`):

| Arquivo | Conteúdo | Status |
|---|---|---|
| `README.md` | Objetivo, estrutura, como consultar e conferir | CORRIGIDA |
| `protocolo_atualizado_TCC.pdf` | Protocolo (mantido na raiz porque o TCC1 o cita por esse nome) | PRONTA |
| `material-suplementar/` | Rastreabilidade do corpus do TCC1 (PDF e XLSX) | PRONTA |
| `02_tcc2/TCC2_Documento_Completo.md` | TCC2 completo (04/11/2026) | PRONTA, com N1 |
| `03_dados/TCC2_Planilha_Auditoria.xlsx` | Planilha de auditoria com fórmulas | PRODUZIDA AGORA |
| `03_dados/csv/01` a `07` | Estudos, qualidade, PRISMA, desvios, conferências, framework, crosswalk | PRODUZIDA AGORA |
| `03_dados/tcc1/Artigos_Citados_TCC_Funcao.xlsx` | Artigos citados no TCC1 | PRONTA, movida |
| `04_prisma/` | Tabela e figura do fluxo | PRODUZIDA AGORA |
| `05_framework/Framework_8_dimensoes.md` | Framework | PRODUZIDA AGORA (extração) |
| `06_documentacao/RELATORIO_EXECUCAO_E_AUDITORIA_TCC2.md` | Este relatório | PRODUZIDA AGORA |
| `07_referencias/Referencias_TCC2.md` | Referências | PRODUZIDA AGORA (extração) |

**No Projeto "TCC":** este relatório (`claude/TCC2_Relatorio_Execucao_e_Auditoria.md`). Os demais documentos do Projeto não foram alterados.

**Não incluídos no repositório (decisão):** fichas F01 a F30, versões v1 a v7.4, registros de decisões e auditorias anteriores. Permanecem no Projeto. Se a orientadora quiser tudo no GitHub, é preciso exportá-los do Projeto (pendência PT2).

## 13. Conferências realizadas

| Conferência | Resultado |
|---|---|
| Aritmética do PRISMA (12 somas e subtrações) | Todas fecham |
| Texto x tabelas do TCC2 (contagens, anos, ressalvas, níveis, médias) | 90 de 91 conferências confirmadas |
| Notas Q1 a Q8 x totais da Tabela 2 | 34 de 34 reproduzidos |
| Listas de IDs (Tabelas 4 e 6, RQ4, framework) x 34 incluídos | Todos os IDs existem; contagens declaradas coincidem |
| Cenários A e B (nº de estudos, média, estudos com nota 6,0 ou mais) | Reproduzidos (30, 5,81, 15; 38, 5,93, 22) |
| Fórmulas da planilha | Recalculadas no LibreOffice: 233 fórmulas, sem células de erro; 12 conferências aritméticas do PRISMA (aba 3) todas OK |
| Leitura independente de PDFs x lista oficial (52 registros) | 50 coincidem; 2 diferenças explicadas |
| Corte de CI1 x protocolo | O protocolo fixa 31/03/2026 como data de corte oficial e prevê atualização em dois anos (Seções 3 e 8), o que sustenta a regra R7 |
| String e bases x TCC2 | Coerentes com o protocolo (3 bases, 2.489 brutos) |
| Links do TCC1 para o repositório | O TCC1 cita a URL do repositório e o arquivo `protocolo_atualizado_TCC.pdf`; ambos mantidos |
| Estudos brasileiros | Nenhum encontrado; ausência não provada (seção 5) |
| Envio ao GitHub | Registrado na seção 16, após a verificação |

**Divergências investigadas e origem.** Nenhuma divergência numérica entre texto, tabelas e planilha. As divergências de identificação (IDs provisórios da Fase 1, ano de SCOPUS_66, grafia de Samman) têm origem documentada (seção 11). Nada foi alterado para igualar números.

**Conferências que não foram feitas:** comparação byte a byte da cópia do TCC2 com o arquivo do Projeto; reabertura dos 53 PDFs; verificação de DOI em cada PDF nesta etapa (DOIs conferidos na primeira página dos PDFs nas auditorias de 03/11 e 04/11, conforme o Apêndice C); comparação com o TCC1 além das seções citadas no TCC2 (PT7).

## 14. Pendências que dependem da orientadora

Nenhuma aprovação foi simulada.

| # | Tema ou informação necessária | Recomendação ou finalidade |
|---|---|---|
| O1 | Conjunto de 34 (sensibilidade 30 e 38) e regras R1–R7 | Confirmar as regras e o conjunto; R1, R3 e R7 foram revistas na auditoria independente de 04/11/2026 |
| O2 | Papel das âncoras (G1) | Manter como contexto e comparação qualitativa |
| O3 | CI3: exclusão de SCOPUS_23, IEEE_230, 463, 531 e 641; inclusão com ressalva de SCOPUS_838, 906, 447 e 852 (IA clássica) | Confirmar; caso mais discutível entre exclusões: 531; entre inclusões: 852 e 447 |
| O4 | CI2/CE1/CE2: exclusão de SCOPUS_193, 965, 521, 225, 854 e 350; inclusão com ressalva de IEEE_101 e 596 | Confirmar exclusão por desenho, não por rótulo, e leitura de CE2 como ausência de busca reproduzível |
| O5 | CI1: SCOPUS_130, 277, 476 e 818 × data da busca | Manter exclusão pela regra R7; se a busca foi depois de 31/03/2026, o TCC1 precisa esclarecer a nota 1 |
| O6 | CI4: seis conferências (IEEE_132, IEEE_81, IEEE_101, SCOPUS_234, 596 e 968) | Manter com ressalva (R4) |
| O7 | Regras de qualidade V1–V6 e P13 | Confirmar limiar bruto e equivalente lado a lado; alta qualidade ≥ 6,0; Q5 N/A em SCOPUS_12 |
| O8 | Escopo do framework | Aceitar como proposta conceitual; validação em trabalho futuro |
| O9 | Nível de evidência F21 (julgamento da autora) | Confirmar o uso como descrição e não como medida de eficácia |
| O10 | Tratamento do κ = 0,466 e dos desvios do TCC1 | Confirmar apresentação como limitação (Seção 7; Apêndice D) e se haverá errata do TCC1 |
| O11 | Declaração de uso de IA | Confirmar forma e texto exigidos pela universidade |
| O12 | Título, estrutura e modelo | Confirmar título e uso do modelo UNIPAMPA |

## 15. Pendências técnicas ou científicas que ainda existem

**Da autora (informação que só ela tem):**

| # | Tema ou informação necessária | Recomendação ou finalidade |
|---|---|---|
| L1 | Data de execução da busca em cada base e interface/versão | Esclarece o corte de 31/03/2026 e a lacuna do PRISMA |
| L2 | Número de duplicatas removidas e ferramenta usada (protocolo: Rayyan) | Completa o fluxo PRISMA (hoje n/d) |
| L3 | Tentativas de recuperação dos 5 textos pelas três vias do §4.4 | Se algum texto for obtido, entra no fluxo (SCOPUS_227, 365 e 970 são meta-análises de efeito) |
| L4 | IDs dos 5 registros incertos da triagem do TCC1 | Permite dizer se coincidem com os 5 não recuperados |
| L5 | Recalibração do κ: amostra efetiva, datas, tabela de contingência e correção | Fecha a limitação principal da triagem |
| L6 | Identificador, plataforma e data do pré-registro | Completa PRISMA/Kitchenham |
| L7 | Confirmar a identidade de SCOPUS_12 | Remove a ressalva de identidade |
| L8 | Volume, número e páginas de SCOPUS_12, 391, 593, 264 e das conferências | Referências completas |
| L9 | Composição das 11 retiradas de 74 → 64 | Fecha inconsistência do TCC1 |
| L10 | Nota † da Tabela 3 do TCC1 (não reproduzível) | Fecha pendência do TCC1 |
| L11 | Versão do modelo de IA usada nesta etapa (TCC1 declara Claude Sonnet 4.6) e revisão do texto da declaração | Seção 3.6 |
| L12 | Leitura crítica do documento e conferência por amostragem das fichas contra os PDFs | Condição para a defesa; o trabalho foi preparado com apoio de IA |

**Técnicas, identificadas nesta auditoria:**

| # | Tema ou informação necessária | Recomendação ou finalidade |
|---|---|---|
| PT1 | Arquivos citados no TCC2 e no registro de alterações e ausentes do Projeto: TCC2_Planilha_Final_Incluidos_Excluidos.xlsx, figs/fig1_prisma.png, txt/SCOPUS_391 | Planilha reconstruída a partir dos documentos (esta planilha); figura PRISMA regenerada dos números documentados. Localizar os originais ou aceitar as versões reconstruídas |
| PT2 | Campos por artigo não replicados nesta planilha: objetivo (F01/Q1), país (F05) para 52 de 58, resultado detalhado (F20) dos estudos sem efeito global | Estão nas fichas F01–F30 (Projeto, claude/TCC2_Fichas_Lote*.md). Extrair e consolidar |
| PT3 | Conferência humana por amostragem das fichas contra os PDFs (L12) | Não substituída por esta auditoria: o cruzamento aqui feito compara só 1º autor e ano com a leitura independente de 47 PDFs |
| PT4 | Leitura independente (Fase 1) cobre 47 dos 53 PDFs; faltam SCOPUS_906, 968, 641, 965, 852 e 838 | Esses seis têm ficha oficial no Projeto; a leitura independente deles não foi feita |
| PT5 | Defeitos da base Fase 1: 40 de 52 IDs gravados são provisórios; sem aplicação de CI1/CE (o #53, SCOPUS_818, tem aceite em 09/04/2026, após o corte) | Base não usada para decisões; usada só como leitura independente de apoio, com o cruzamento por Nº |
| PT6 | Diagramação no modelo oficial UNIPAMPA (LaTeX) não disponível; TCC2 entregue em Markdown | Converter para o modelo oficial |
| PT7 | TCC1_Esclarecimentos_e_Correcoes (T1–T16) não foi relido nesta auditoria | Reconciliar com o TCC1 antes de qualquer errata |
| PT8 | Referências: SCOPUS_838 sem DOI na lista; lacunas de volume/páginas (L8); 10 referências além dos 34 (âncoras e método) | Completar com a página da editora; não criar dados |

**Continuam válidos sem essas respostas:** os 34 incluídos, as tabelas de resultados, o framework e a conferência numérica. Dependem delas: número de duplicatas, data da busca, possível entrada dos 5 textos, fechamento das limitações do TCC1, formatação no modelo UNIPAMPA e a conferência humana das fichas.

## 16. Verificação do envio ao GitHub

Preenchida após o envio (ver o final deste arquivo).
