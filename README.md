# Protocolo de Revisão Sistemática Terciária
## Evidence-Based AI Applications in Higher Education

**Autora:** Luiza de Campos Velasque Figueiredo  
**Instituição:** Universidade Federal do Pampa (UNIPAMPA) — Campus Alegrete, RS, Brasil  
**Contato:** luizavelasque.aluno@unipampa.edu.br  
**Ano:** 2026

---

## Resumo

Este repositório documenta o protocolo de uma **Revisão Sistemática Terciária (RST)** sobre aplicações de Inteligência Artificial (IA) no Ensino Superior, elaborado em conformidade com as diretrizes de Kitchenham e Charters, o PRISMA 2020 e a ferramenta AMSTAR 2.

O protocolo foi registrado previamente à execução da busca com o objetivo de mitigar vieses de relatório e de publicação. A RST sintetiza evidências provenientes de estudos secundários — revisões sistemáticas, mapeamentos sistemáticos, scoping reviews e meta-análises — publicados entre **2019 e 2026**.

---

## Questões de Pesquisa

| ID | Questão |
|----|---------|
| **RQ1** | Quais são as principais aplicações de Inteligência Artificial no Ensino Superior reportadas em revisões sistemáticas da literatura? |
| **RQ2** | Quais benefícios são relatados na literatura sobre o uso de IA no Ensino Superior? |
| **RQ3** | Quais desafios de implementação, limitações metodológicas e preocupações éticas são discutidos nos estudos secundários analisados? |
| **RQ4** | Quais lacunas de pesquisa e tendências futuras são identificadas nos estudos analisados? |

---

## Estratégia de Busca (Framework PICOC)

| Elemento | Descrição |
|----------|-----------|
| **Population** | Instituições e contextos de Ensino Superior (*higher education, university, undergraduate, postgraduate, tertiary education*) |
| **Intervention** | Aplicações de IA clássica (learning analytics, sistemas tutores inteligentes, aprendizagem adaptativa) e IA Generativa (LLMs, chatbots, ferramentas de geração de conteúdo) |
| **Comparison** | Não se aplica — revisão terciária de natureza exploratória e descritiva |
| **Outcome** | Aplicações identificadas, benefícios, desafios, limitações, preocupações éticas, lacunas e tendências de pesquisa |
| **Context** | Estudos secundários: revisões sistemáticas, mapeamentos sistemáticos, scoping reviews, meta-análises, umbrella reviews |

### Bases de Dados

| Base | Registros Recuperados |
|------|----------------------|
| Scopus | 936 |
| ACM Digital Library | 1.217 |
| IEEE Xplore | 336 |
| **Total bruto** | **2.489** |

### String de Busca Final

```
( "artificial intelligence" OR "generative AI"
  OR "large language model*" OR "LLM*"
  OR "ChatGPT" OR "GPT-4"
  OR "Microsoft Copilot" OR "GitHub Copilot" OR "Gemini"
  OR "intelligent tutoring system*" OR chatbot*
  OR "learning analytics" OR "adaptive learning" )
AND
( "higher education" OR "tertiary education"
  OR "postsecondary education" OR "university education" )
AND
( "systematic review" OR "systematic literature review"
  OR "scoping review" OR "meta-analysis"
  OR "systematic mapping" OR "mapping review" OR "mapping study"
  OR "umbrella review" OR "review of reviews" OR "tertiary review"
  OR "evidence synthesis" )
```

---

## Critérios de Elegibilidade

### Inclusão

| ID | Critério |
|----|----------|
| CI1 | Estudos secundários publicados entre 2019 e 2026 |
| CI2 | Revisão sistemática, mapeamento sistemático, scoping review, revisão integrativa com protocolo explícito, meta-análise ou umbrella review |
| CI3 | Foco temático central no uso, aplicação ou impacto de IA no Ensino Superior |
| CI4 | Publicados em periódicos revisados por pares ou anais de conferências com revisão formal |
| CI5 | Disponíveis em texto completo, redigidos em inglês ou português |

### Exclusão

| ID | Critério |
|----|----------|
| CE1 | Estudos primários sem protocolo formal de revisão sistemática |
| CE2 | Revisões narrativas ou sínteses temáticas sem protocolo de busca explícito |
| CE3 | Estudos duplicados |
| CE4 | Escopo restrito à Educação Básica, Técnica, Ensino Médio ou treinamento corporativo |
| CE5 | Sem acesso ao texto completo |
| CE6 | Capítulos de livro, editoriais, cartas ao editor, preprints sem versão publicada |
| CE7 | Publicados anteriormente a 2019 ou data não verificável |

---

## Avaliação da Qualidade Metodológica (AMSTAR 2 + Kitchenham)

| ID | Critério | Peso |
|----|----------|------|
| Q1 | Objetivo ou questão de pesquisa claramente definidos | 1,0 |
| Q2 | Estratégia de busca descrita de forma explícita e reproduzível | 1,0 |
| Q3 | Critérios de inclusão/exclusão claros e aplicados consistentemente | 1,0 |
| Q4 | Processo de seleção descrito e replicável | 1,0 |
| Q5 | Qualidade metodológica dos estudos primários avaliada | 1,0 |
| Q6 | Métodos de extração e síntese adequadamente descritos | 1,0 |
| Q7 | Resultados discutidos com base nas evidências, sem extrapolações | 1,0 |
| Q8 | Ameaças à validade reconhecidas e discutidas | 1,0 |
| | **Pontuação máxima** | **8,0** |
| | **Limiar mínimo de inclusão** | **≥ 3,0** |

---

## Processo de Seleção

O processo segue estritamente o fluxograma **PRISMA 2020**, em quatro etapas:

1. **Exportação e gerenciamento bibliográfico** — Zotero (RIS, BibTeX, CSV)
2. **Identificação e remoção de duplicatas** — plataforma Rayyan
3. **Triagem por título e resumo** — classificação em Incluir / Excluir / Incerto
4. **Avaliação do texto completo** — aplicação dos critérios CI/CE com registro de motivos

---

## Síntese dos Dados

A síntese adota abordagem **predominantemente qualitativa**, estruturada em:

- **Síntese narrativa estruturada** organizada por RQ
- **Categorização temática** por domínio de IA e contexto educacional
- **Análise de convergências e divergências** entre estudos
- **Análise de sobreposição** (*citation overlap matrix*) entre revisões incluídas
- **Comparação longitudinal** pré e pós-2022 (marco da IA Generativa)

---

## Referências Metodológicas

- KITCHENHAM, B.; CHARTERS, S. *Guidelines for performing systematic literature reviews in software engineering*. EBSE-2007-01, 2007.
- PAGE, M. J. et al. The PRISMA 2020 statement. *BMJ*, v. 372, p. n71, 2021.
- SHEA, B. J. et al. AMSTAR 2. *BMJ*, v. 358, p. j4008, 2017.

---

## Artigos de Controle (Gold Standard)

| Ref. | Artigo | Tipo |
|------|--------|------|
| GS1 | Zawacki-Richter et al. (2019) — *Systematic review of research on AI applications in higher education* | Revisão Sistemática |
| GS2 | Crompton & Burke (2023) — *AI in higher education: the state of the field* | Revisão Sistemática (PRISMA) |
| GS3 | Bond et al. (2024) — *A meta systematic review of AI in higher education* | Meta-Revisão (Umbrella Review) |
| GS4 | Ouyang et al. (2022) — *AI in online higher education: 2011–2020* | Revisão Sistemática |
| GS5 | Salas-Pilco & Yang (2022) — *AI applications in Latin American higher education* | Revisão Sistemática |

---

## Palavras-chave

`Inteligência Artificial` · `Ensino Superior` · `Revisão Sistemática Terciária` · `PRISMA 2020` · `IA Generativa` · `Learning Analytics` · `Síntese de Evidências`

---

## Licença

Este protocolo é disponibilizado publicamente para fins de transparência metodológica e reprodutibilidade científica.
