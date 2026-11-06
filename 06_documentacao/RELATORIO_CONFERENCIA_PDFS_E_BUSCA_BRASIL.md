# Relatório de conferência dos 53 PDFs e busca complementar brasileira

Data: 05/11/2026. Continua o `RELATORIO_EXECUCAO_E_AUDITORIA_TCC2.md` (commit `73bf8fe`), que não foi refeito.

## 1. Resumo

- Os 53 PDFs foram lidos de novo e conferidos contra as referências, as fichas e o TCC2. **DOI, primeiro autor e ano conferem nos 53.** Seis DOIs de conferências IEEE não reaparecem no texto lido agora, mas estão registrados nas fichas.
- **Os números da Tabela 5 (22 estudos), a lista de I² ≥ 70% (9) e a lista de viés de publicação (5) correspondem aos PDFs.** Quatro pontos do texto precisaram de correção ou precisão (seção 5).
- **Nenhum dos 53 estudos avaliados é brasileiro.** A busca complementar localizou 6 trabalhos acadêmicos brasileiros, 1 TCC de especialização da UNIPAMPA, 4 itens de literatura cinzenta ou normativa, incluindo o parecer CNE/CP 15/26. Tudo isso está **fora do corpus** (Apêndice G do TCC2).
- Nenhum resultado foi inventado e nenhuma decisão metodológica foi alterada.

## 2. O que foi efetivamente conferido

| Verificação | Resultado |
|---|---|
| PDFs do corpus abertos e lidos | 53 de 53 (42 com texto extraído e verificado por script; 11 lidos diretamente, com notas de leitura registradas) |
| Os 5 não recuperados (SCOPUS_227, 365, 375, 678, 970) | Não consultados: o PDF não existe nos documentos |
| DOI da referência no PDF | 43 confirmados; 1 parcial (SCOPUS_289, prefixo impresso e truncado); 6 só nas fichas (IEEE_101, 81, 132; SCOPUS_968, 596, 38); 3 sem DOI em lugar nenhum (SCOPUS_838, 965, 966) |
| Primeiro autor no PDF | 53 de 53 |
| Ano no PDF | 53 de 53 |
| País da primeira afiliação | 51 de 53 identificados; SCOPUS_838 e 485 sem afiliação no texto lido; IEEE_230 só por indício (financiamento); SCOPUS_210 inferido da instituição |
| Tabela 5, números dos efeitos | 22 de 22 conferem (18 por busca automática no texto; 4 por nota de leitura: IEEE_132, IEEE_81, SCOPUS_234, 9). "2.571" do texto é "2571" no PDF |
| I² ≥ 70% (9 estudos) | 9 de 9 confirmados |
| Viés de publicação (5 estudos) | 5 de 5 sustentados, com uma precisão (SCOPUS_838) |
| Vínculos tema/dimensão (108 pares estudo-dimensão) | 2 fracos (SCOPUS_639 em privacidade; 117 em integridade), 3 qualificados no texto, o restante com respaldo |
| Restrições de busca, Google Scholar (SCOPUS_1), base única (968), trim-and-fill de Deng (0,712 → 0,881 em desempenho acadêmico) | Conferem |

**O que não foi refeito:** a pontuação Q1–Q8 (julgamento), a classificação do nível F21 e o preenchimento de cada célula das Tabelas 4 e 6 além da checagem por palavra-chave. A conferência foi feita por assistente de IA e **não substitui** a conferência humana por amostragem (L12).

## 3. Artigos consultados

Os 53 do corpus, pelo ID oficial, todos com leitura do PDF em 05/11/2026:

- **34 incluídos:** SCOPUS_838, 594, 906, 968, 852, 840, 596, 639, 588, 593, 456, 447, 264, 66, 289, 15, 9, 129, 427, 234, 26, 439, 391, 117, 485, 196, 12, 431, 380, 159, 1; IEEE_101, IEEE_81, IEEE_132.
- **19 excluídos:** SCOPUS_38, 521, 947, 966, 854, 225, 350, 193, 965, 23, 463, 531, 641, 210, 130, 277, 476, 818; IEEE_230.

País, objetivo e contribuição de cada um: `03_dados/csv/08_conferencia_53_pdfs.csv` e Apêndice F do TCC2.

**Países (primeira afiliação) dos 34 incluídos:** China 12; Hong Kong 1; África do Sul 2; Estados Unidos 2; Iraque, Estônia, Cazaquistão e Hungria, Emirados Árabes Unidos, Bahrein, Austrália, Alemanha, Irã, Coreia do Sul, Turquia, Tailândia, Reino Unido, Nigéria, Malásia e Kosovo 1 cada; sem afiliação no texto lido: 2 (SCOPUS_838 e 485). **Nenhum no Brasil ou na América Latina.** Entre os 19 excluídos, o único latino-americano é SCOPUS_463 (Peru, CI3).

## 4. Pesquisas brasileiras (literatura complementar, fora do corpus)

Busca exploratória de 6 consultas (português e inglês) mais leitura das páginas. Detalhe, referências e limites: `08_literatura_complementar/Literatura_Complementar_Brasil.md`.

| Cód. | O que é | Achado principal |
|---|---|---|
| B1 | RICHARDT et al. (2026), WICS/CSBC, UNIPAMPA. Governança da IA generativa nas universidades federais: revisão sistemática (92 recuperados, 30 selecionados) + análise documental de 9 universidades | Institucionalização heterogênea; só a UFDPar tem política formal ("Alto"); descompasso entre uso e regulação |
| B1a | TCC de especialização (UNIPAMPA, 2025), versão anterior de B1 | Mesmos achados |
| B2 | PLACCA (2026), Revista do CERES. Diretrizes de UNICAMP, UFBA, UFG, UNESP, UNESPAR e UFC | Convergência em transparência, integridade e supervisão humana; formalização desigual |
| B3 | NORONHA; FERRO (2026), WEI/CSBC. Documentos de ANDIFES, UDESC, UFC, UFMS, UFF e UNESP sobre IA na pesquisa | IA como apoio sob supervisão, uso declarado, restrições por plágio |
| B4 | Práxis Educativa, v. 21 (2026), DOI 10.5212/PraxEduc.v.21.26177.014. Seis universidades públicas | Diferenças no grau de formalização e em quem decide; autores não constam na página lida |
| B5 | MATOS et al. (2024), RAM, DOI 10.1590/1678-6971/eRAMD240061. Semissistemática (45 artigos) | Discussão ética incipiente em Administração |
| B6 | ARAÚJO; BATISTA, Seminário Inovações Curriculares. Governança da personalização por IA | Regras mínimas e estruturas internas de governança nas IES; ano não consta |
| G1 a G4 | Pesquisa FAPESP (2024); ABMES (2026); parecer **CNE/CP 15/26** (aprovado em 01/09/2026, aguarda homologação, lido só por fontes secundárias); UFMG Educativa (2025) | Princípios de transparência, integridade, letramento; IES devem criar políticas próprias |

**Leitura para o TCC2:** convergem com as dimensões D7, D2, D5 e D6 e **confirmam a lacuna da Dimensão 7** (documentam políticas adotadas, mas nenhum mede efetividade). Não alteram nenhuma contagem. Não lidos: diretrizes da UFAM e a consulta pública (acesso falhou).

## 5. Correções feitas e o que foi só registrado

| # | Onde | Antes | Depois | Evidência |
|---|---|---|---|---|
| 1 | Tabela 2, Referências, `07_referencias`, CSV 01 e 06, planilha | "Samman" / "SAMMAN, A. M. A." | "Al Samman" / "AL SAMMAN, A. M." (reordenado) | PDF: "Adel Mahmoud Al Samman" |
| 2 | Seção 5.3 | Xie et al. e Wang e Guo com "efeitos maiores" com intervenção docente | Diferença de Xie (0,517 vs 0,477) não significativa; Wang e Guo significativa só no engajamento cognitivo | PDFs de IEEE_81 e SCOPUS_439 |
| 3 | Seção 6.1 e `05_framework` | SCOPUS_26 como evidência de envolvimento docente; IEEE_81 "aumentam o efeito" | SCOPUS_26 é menção na revisão de literatura do estudo, citando terceiros; IEEE_81 reformulado | PDF de SCOPUS_26; IEEE_81 |
| 4 | Seção 4.7 (iii) | Robertshaw e Asher "citado entre as limitações" | Egger não significativo; os autores reconhecem o risco de viés de publicação nas limitações | PDF de SCOPUS_838 |
| 5 | Seção 4.3 | Sem país | Parágrafo de origem geográfica | Apêndice F |
| 6 | Seção 6.7, 7 (item 14) e 8 | Sem literatura brasileira | Parágrafo marcado como fora do corpus; limitação 14; trabalho futuro | Apêndice G |
| 7 | Apêndices F e G; nota de versão | — | Incluídos | — |

**Registrado, sem alterar o texto (decisões O14 e observações):**
- SCOPUS_639 (privacidade) e SCOPUS_117 (integridade) entram na contagem por menções fracas (uma frase em cada). SCOPUS_26 (dependência e exatidão) vem de frase da própria revisão de literatura.
- SCOPUS_234 relata três valores globais (1,34; 0,46; 0,94) em modelos diferentes; a Tabela 5 traz 0,94.
- SCOPUS_968 lista CAPES e CNPq entre os financiadores, mas os autores são do Cazaquistão e da Hungria.
- SCOPUS_838: DOI ausente no PDF e nas fichas.

## 6. Divergências de autoria, ano e outras

Autores e anos: nenhuma divergência, exceto a grafia do item 1. Fluxo e contagens do PRISMA: sem mudança (os números da fase anterior seguem 90 de 91 conferências OK, mais 53 de 53 neste relatório). IDs trocados do TCC1 (D18) e SCOPUS_12: os PDFs conferem com título, autores, ano e DOI da referência (L7 só depende da autora).

## 7. Decisões que dependem da autora e da orientadora

Ver `DECISOES_PENDENTES_AUTORA_ORIENTADORA.md`. Novas: **O13** (destino da literatura brasileira), **O14** (contagem por menção), **O15** (citar B1), **L13** a **L15**.

## 8. O que ainda impede a conclusão do TCC2

1. Confirmação da orientadora (O1 a O15).
2. Dados só da autora: data da busca, duplicatas, pré-registro, tentativas de recuperação dos 5 textos, recalibração do κ, composição 74 → 64.
3. Cinco textos não recuperados, três deles meta-análises de efeito.
4. Segundo revisor e recalibração do κ = 0,466.
5. Conferência humana por amostragem das fichas (L12) e leitura crítica da autora.
6. Declaração de uso de IA e diagramação no modelo UNIPAMPA.

## 9. Limites desta conferência

- A leitura de 11 PDFs foi direta e registrada em notas manuais, não por busca automática.
- A busca brasileira foi exploratória; algumas páginas foram lidas apenas no resumo, uma página foi bloqueada por robots e dois documentos não abriram. O parecer CNE/CP 15/26 só foi visto por fontes secundárias.
- O país é o da primeira afiliação, não o da amostra dos estudos primários.

## 10. Arquivos criados ou alterados

`02_tcc2/TCC2_Documento_Completo.md`; `03_dados/TCC2_Planilha_Auditoria.xlsx` (abas 10 a 13; 233 fórmulas preservadas); `03_dados/csv/01`, `06`, novos `08`, `09`, `10`; `05_framework/Framework_8_dimensoes.md`; `07_referencias/Referencias_TCC2.md`; `08_literatura_complementar/`; `06_documentacao/` (este relatório e a lista de decisões); `README.md`.

**Confirmações:** nenhum artigo, autor, DOI, número ou referência foi inventado; o que não constava está marcado como [INFORMAÇÃO NÃO DISPONÍVEL NOS DOCUMENTOS FORNECIDOS]; a literatura complementar está identificada como tal.
