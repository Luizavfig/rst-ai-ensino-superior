# Seleção reproduzível da literatura de referência do framework

Realizada em 08 e 09/11/2026, **depois** da primeira versão do framework, para verificar e refazer a escolha das 36 referências usadas como literatura de referência. Não é o procedimento original: na primeira versão, parte das referências foi escolhida por serem conhecidas na área, com critérios redigidos depois da escolha. Este registro substitui aquela justificativa.

Protocolos registrados antes da execução: `PROTOCOLO.md` (Etapa 1) e `BUSCA.md` (Etapa 2).

## Etapa 1 – Snowballing para trás a partir do corpus (OpenAlex)

| Passo | Número |
|---|---|
| Estudos da semente (34 incluídos + 6 âncoras) | 40 |
| Sem lista de referências no OpenAlex (S289, I81) | 2 |
| Estudos usados | 38 |
| Referências registradas no OpenAlex para os 38 | 2.945 |
| Registros com termos do filtro no título (conjuntos A e B) | 224 |
| Obras distintas triadas | 176 |
| Excluídas: estudo da própria semente (X-SEM) | 1 |
| Excluídas: diretriz de método ou relato (X-E1) | 3 |
| Excluídas: estudo primário empírico (X-E2) | 35 |
| Excluídas: sem relação com IA ou dados (X-E3) | 31 |
| Excluídas: contribuição principal fora do SC2 (X-SC2) | 36 |
| Incluídas (registros) | 70 |
| Incluídas (obras distintas; 1 registro duplicado) | 69 |
| – núcleo (citadas por ≥ 2 estudos da semente) | 11 |
| – complementares (citadas por 1 estudo) | 58 |

Arquivos: `ids.tsv` (semente), `presenca.tsv` (referências do framework citadas por cada estudo), `raw.tsv` (registros filtrados), `log_listas.tsv`, `triagem_etapa1.tsv` e `triagem_decisoes.py` (decisões e motivos).

Além da triagem, verificou-se diretamente, para 25 referências da primeira versão com identificador no OpenAlex, quantos estudos da semente as citam (`presenca.tsv`). Dez são citadas por pelo menos um estudo.

### Esclarecimentos de critério fixados durante a triagem da Etapa 1 (antes da Etapa 2)
- "Framework" foi entendido como framework de orientação (o que fazer, como governar ou usar), e não como taxonomia técnica de sistemas.
- Frameworks didáticos de uso da IA em uma disciplina não atendem SC2.
- Obras restritas a outro setor (saúde, ambiente, consumo, administração pública, empresas) não atendem SC2, pois SC2 fala em IA "em geral ou na educação".
- Quando o resumo mostra que ética, diretrizes ou políticas são apenas um tema secundário, a obra não atende SC2.
Esses esclarecimentos também foram aplicados às referências da primeira versão; dois deles afetaram Zawacki-Richter et al. (2019) e Kasneci et al. (2023).

## Etapa 2 – Busca estruturada no OpenAlex

11 consultas no título (B1–B11), tipos `article` e `review`, ordenadas por número de citações; triagem dos 20 primeiros de cada consulta.

| Passo | Número |
|---|---|
| Posições triadas (11 × 20) | 220 |
| Obras distintas | 214 |
| Excluídas X-SEM | 2 |
| Excluídas X-E2 | 37 |
| Excluídas X-E3 | 29 |
| Excluídas X-SC2 | 38 |
| Incluídas | 108 |

Arquivos: `busca_resultados.tsv` (todas as respostas das subconsultas), `busca_top20.tsv` (20 primeiros de cada consulta após a união), `triagem_etapa2.tsv` e `triagem_decisoes_b.py`.

### Desvios de execução
1. O OpenAlex não aceitou parênteses nem três termos ligados por OR no filtro de título (o filtro é ignorado sem aviso e a resposta traz cerca de 318 milhões de registros). As consultas B2, B3, B4, B5, B8, B9 e B10 foram executadas como subconsultas simples (uma para cada combinação de termos), e os resultados foram unidos e reordenados por citações antes do corte de 20. A lógica booleana é a mesma.
2. O OpenAlex reduz plurais e algumas derivações (policy = policies; university = universities; explainable = explainability = explain; fairness = fair). Subconsultas idênticas por esse motivo não foram repetidas (uma foi conferida e deu o mesmo resultado). O ruído trazido por "explain" e "fair" foi excluído na triagem.
3. Na subconsulta B9_8 foram registrados apenas os 8 primeiros resultados (3 ou mais citações) de 18, porque o corte da união em B9 ficou em 36 citações.
4. O filtro `type:article|review` excluiu obras que o OpenAlex classifica como `conference-paper`. O protocolo supunha que artigos de conferência estariam incluídos. Isso afetou três referências da primeira versão (Amershi et al., 2019; Raji et al., 2020; Long; Magerko, 2020). O filtro **não** foi alterado depois de conhecido o efeito; a questão está registrada como limitação e como decisão para a orientação.

## Classificação das 36 referências da primeira versão

Arquivo: `classificacao_36_referencias.csv`.

| Situação | Quantidade | Referências |
|---|---|---|
| Confirmada pela Etapa 1 (e também pela Etapa 2, quando indicado) | 8 | Floridi et al. (2018); Holmes et al. (2022); Chan (2023); Moorhouse et al. (2023); Cotton et al. (2024); Baker; Hawn (2022); Khosravi et al. (2022); Ng et al. (2021) |
| Confirmada só pela Etapa 2 | 6 | Jobin et al. (2019); Papagiannidis et al. (2025); Mäntymäki et al. (2022); Batool et al. (2025); Shneiderman (2020b); Perkins et al. (2024) |
| Regra normativa | 6 | UNESCO (2022); Miao; Holmes (2023); União Europeia (2024); NIST (2023); Brasil (2018); Brasil (2023) |
| Regra de método | 6 | Hevner et al. (2004); Peffers et al. (2007); Jabareen (2009); Venable et al. (2016); Prat et al. (2015); Okoli; Pawlowski (2004) |
| Substituída | 4 | Mittelstadt (2019) → Morley et al. (2020); Raji et al. (2020) → Koshiyama et al. (2024); Slade; Prinsloo (2013) → Pardo; Siemens (2014); Tsai et al. (2018) → Prinsloo; Slade (2013) |
| Retirada | 6 | Shneiderman (2020a); Amershi et al. (2019); Molenaar (2022); Zawacki-Richter et al. (2019); Long; Magerko (2020); Kasneci et al. (2023) |

Resultado: 30 referências (26 mantidas + 4 substitutas). As 10 retiradas ou substituídas continuam na lista de referências do TCC porque são citadas na Seção 3.8, que explica a seleção. No TCC, as letras do BibTeX ficam assim: Shneiderman (2020a) = "Bridging the gap…" (retirada) e Shneiderman (2020b) = "Human-centered artificial intelligence…" (confirmada).

### Substitutas (dados conferidos no Crossref em 09/11/2026)
| Chave | Referência | Origem | Uso no framework |
|---|---|---|---|
| morley2020 | MORLEY, J. et al. From what to how: an initial review of publicly available AI ethics tools, methods and research to translate principles into practices. Science and Engineering Ethics, v. 26, n. 4, p. 2141-2168, 2020. DOI 10.1007/s11948-019-00165-5 | Etapa 2, B2 (posição 3) | Distância entre princípios e prática (G1; separação entre governança e domínios) |
| koshiyama2024 | KOSHIYAMA, A. et al. Towards algorithm auditing: managing legal, ethical and technological risks of AI, ML and associated algorithms. Royal Society Open Science, v. 11, n. 5, 230859, 2024. DOI 10.1098/rsos.230859 | Etapa 2, B5 (posição 8) | Auditoria de algoritmos (G1, C4; R03, R04, R16) |
| pardo2014 | PARDO, A.; SIEMENS, G. Ethical and privacy principles for learning analytics. British Journal of Educational Technology, v. 45, n. 3, p. 438-450, 2014. DOI 10.1111/bjet.12152 | Etapa 2, B6 (posição 1) | Princípios éticos e de privacidade para dados educacionais (C3; R13) |
| prinsloo2013 | PRINSLOO, P.; SLADE, S. An evaluation of policy frameworks for addressing ethical considerations in learning analytics. In: LAK '13, 2013, Leuven. New York: ACM, 2013. p. 240-244. DOI 10.1145/2460296.2460344 | Etapa 1 (complementar) | Políticas institucionais para o uso ético de dados de estudantes (C3; R13) |

O conteúdo atribuído a cada substituta foi conferido no resumo disponível no OpenAlex, não no texto completo.

## Efeito no framework
Nenhum componente ficou sem literatura de referência. A estrutura (G1–G2, C1–C6) e as 22 diretrizes não mudaram; mudaram as referências citadas em R03, R04, R05, R06, R07, R08, R09, R13, R16 e R22. A matriz de cruzamento (37 elementos de 7 fontes) usa apenas fontes confirmadas e não muda.

## O que esta seleção não resolve
- Ela foi feita depois da construção do framework: confirma ou substitui referências, mas não reconstrói o framework a partir das obras encontradas.
- As obras incluídas nas Etapas 1 e 2 que não estavam na primeira versão (por exemplo, princípios éticos para IA na educação e as análises de políticas institucionais de IA generativa) não foram incorporadas ao texto. A leitura dessas obras e a decisão de incorporá-las ficam para a validação do framework.
- A triagem foi feita por uma pessoa, por título e, em caso de dúvida, pelo resumo, sem segunda avaliação independente.

## Conferência do que o TCC afirma sobre cada referência (09/11/2026)
Ficha de cada uma das 30 referências, com critério, evidência, onde é citada e conferência da afirmação: `Referencias_Framework_Criterios_e_Rastreabilidade.pdf`, gerado por `gerar_fichas_framework.py`. Resultado da conferência:
- 18 confirmadas (resumo, página oficial ou catálogo);
- 10 parciais ou sem resumo, a conferir no texto completo (pendência L16);
- 2 sem conteúdo específico a conferir (LGPD) ou confirmadas em fontes secundárias (PL 2.338/2023).
