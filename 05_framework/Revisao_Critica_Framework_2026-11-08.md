# Revisão crítica do framework de oito dimensões (versão para discussão)

**Data:** 08/11/2026 · **Situação:** proposta para discussão com as orientadoras (decisões N6 e N7). O texto do TCC2 (Seção 6) **ainda não foi alterado**.

**Arquivos de apoio:** `Literatura_Referencia_Framework.md` (36 referências conferidas), `Matriz_Cruzamento_Referencias.csv`, `Cobertura_Temas_Corpus.csv`, `componentes_x_corpus.csv`, `Requisitos_Derivados.md`, `fig_framework_revisado.png`.

## 1. Pergunta que orienta o framework

O TCC2 tem quatro perguntas de pesquisa (RQ1–RQ4) sobre a literatura, mas nenhuma sobre o artefato. Proposta de objetivo específico, a ser confirmada (N4):

> **OE5.** Derivar, dos achados da revisão terciária e de literatura de referência em governança de IA, IA responsável e interação humano-IA, um framework conceitual que oriente instituições de ensino superior na governança e no uso responsável de IA, com rastreabilidade de cada componente à evidência que o sustenta.

## 2. Especificação do artefato (item 6 do parecer do TCC1)

| Elemento exigido pelo parecer | Proposta |
|---|---|
| Público-alvo | Gestão de IES (reitoria, pró-reitorias de graduação e de TI, comitês de governança de dados e de IA), coordenações de curso e docentes. Estudantes são afetados pelas políticas, mas não são usuários diretos do framework |
| Finalidade | Apoiar o diagnóstico e a elaboração ou revisão de políticas institucionais de uso de IA em ensino e avaliação. **Não** certifica conformidade legal e **não** prova eficácia de práticas |
| Formato | Duas camadas (governança transversal G1–G2 e seis domínios C1–C6), cada componente com definição, problema, evidência, referências, diretrizes (requisitos rastreáveis) e perguntas de diagnóstico |
| Critérios de qualidade | Cobertura, consistência interna, rastreabilidade à evidência, clareza e utilidade percebida (Prat et al., 2015). Os três primeiros são avaliados agora; os dois últimos dependem de avaliação com especialistas |
| Método de derivação | Análise de framework conceitual (Jabareen, 2009), adaptada: Seção 3 |
| Estratégia de avaliação | Avaliação ex ante e analítica no TCC2; avaliação com especialistas como opção ou trabalho futuro (FEDS, Venable et al., 2016). Ver `Proposta_Requisitos_e_Avaliacao.md` |

## 3. Método de derivação

Adaptação das fases de Jabareen (2009):

1. **Mapear as fontes.** (a) Corpus: 34 estudos incluídos, com os vínculos estudo × tema já conferidos nos PDFs (`10_dimensoes_x_estudos_verificado.csv`) e as contagens das Tabelas 4 e 6 e da Seção 4.8 do TCC2. (b) Literatura de referência: 30 artigos e 6 documentos institucionais, selecionados por critérios explícitos e com DOI conferido.
2. **Identificar e categorizar conceitos.** Temas de risco, lacuna e tendência do corpus (23 temas) e elementos dos frameworks de referência (37 elementos de 7 fontes).
3. **Desconstruir e integrar.** Cruzar temas do corpus com elementos de referência; agrupar por objeto (o que é protegido ou promovido) ou por mecanismo (como a instituição age).
4. **Sintetizar.** Propor componentes e checar se cada um tem sustentação no corpus, na literatura de referência ou em ambos.
5. **Validar (analítico) e revisar.** Checar cobertura dos temas do corpus e dos princípios de referência; registrar o que fica de fora e por quê.

**Regra de decisão para manter um componente:** (i) sustentação direta em pelo menos 5 dos 34 estudos **e** em pelo menos 2 referências independentes; ou (ii) exigência normativa explícita em documento de referência, declarada como sustentação normativa e não empírica. Um componente sem sustentação no corpus não entra como componente; entra como lacuna.

## 4. Diagnóstico crítico do framework de 04/11/2026

| # | Problema encontrado | Evidência | Consequência |
|---|---|---|---|
| F1 | **Dependência sem dimensão.** "Dependência e preguiça metacognitiva" é o 2.º risco mais citado (11 estudos; 10 sem SCOPUS_26, que não conta pela regra O14), mas não tem dimensão própria; a D1 cobria só orientação docente (3 estudos diretos) | `Cobertura_Temas_Corpus.csv`; Tabela 6 do TCC2 | Lacuna grave de cobertura |
| F2 | **Responsabilização ausente.** Responsabilidade/prestação de contas é princípio convergente (Jobin et al., 2019) e princípio da UNESCO (2021), e não aparecia no framework | Matriz de cruzamento | Framework centrado em temas, sem dizer quem responde |
| F3 | **Mistura de níveis.** D7 (políticas e governança) e D8 (monitoramento) não são domínios de risco como D2–D5: são mecanismos que operam sobre todos os outros (NIST, 2023; Papagiannidis et al., 2025) | Estrutura das referências | Lista plana esconde a dependência entre componentes; reforça o hiato princípio-prática (Mittelstadt, 2019) |
| F4 | **D1 com base empírica estreita.** Definida por um moderador relatado em 3 estudos | `11_dimensoes_suficiencia.csv` | Sustentação frágil se lida isoladamente; a literatura de supervisão humana e agência (Shneiderman; Molenaar; UNESCO; AI Act) dá base conceitual mais forte |
| F5 | **Segurança e validação de ferramentas sem lugar.** SCOPUS_840 (cibersegurança) e a exigência de validar ferramentas (UNESCO, 2023; deveres do usuário institucional no Regulamento UE 2024/1689) não tinham componente | Fichas; referências | Omissão operacional relevante para IES |
| F6 | **Evidência desigual não explicitada na arquitetura.** D4 (equidade) tem a menor nota média do corpus e nenhuma auditoria de viés com dados próprios | `componentes_x_corpus.csv` | Deve ser mantida por base normativa e conceitual, mas declarada como dimensão de evidência fraca |

**O que não é problema:** D2, D3, D5 e D6 têm sustentação suficiente pela regra de decisão; mudam só de nome ou escopo.

## 5. Framework revisado: duas camadas, oito componentes

![Framework revisado](fig_framework_revisado.png)

Nenhuma dimensão foi descartada. Duas foram reclassificadas como camada transversal (F3), uma foi ampliada para incluir dependência e agência (F1, F4), uma passou a incluir segurança (F5) e a responsabilização foi incorporada à governança (F2).

| Componente | Origem (framework de 04/11) | Decisão | Estudos do corpus (n) | Nota Q média | Q ≥ 6,0 | Sem ressalvas | Referências principais |
|---|---|---|---|---|---|---|---|
| **G1** Governança institucional e responsabilização | D7 + responsabilização | Reclassificada como transversal; ampliada | 9 | 4,86 | 2 | 2 | Papagiannidis et al. (2025); Mäntymäki et al. (2022); Batool et al. (2025); Mittelstadt (2019); Chan (2023); Raji et al. (2020); NIST (2023); UNESCO (2021, 2023); Reg. UE 2024/1689; PL 2.338/2023 |
| **G2** Monitoramento e avaliação baseada em evidências | D8 | Reclassificada como transversal | 17 | 5,81 | 9 | 6 | NIST (2023); Zawacki-Richter et al. (2019); Mittelstadt (2019) |
| **C1** Agência humana, supervisão e uso pedagógico orientado | D1 + dependência + colaboração humano-IA | Ampliada e renomeada | 15 | 5,67 | 8 | 6 | Shneiderman (2020a, 2020b); Molenaar (2022); Amershi et al. (2019); Floridi et al. (2018); Kasneci et al. (2023); Holmes et al. (2022); UNESCO (2021); Reg. UE 2024/1689 |
| **C2** Avaliação da aprendizagem e integridade acadêmica | D2 | Mantida; escopo inclui IA usada para avaliar | 5 | 5,44 | 2 | 3 | Perkins et al. (2024); Moorhouse et al. (2023); Cotton et al. (2024); Holmes et al. (2022); Reg. UE 2024/1689 (Anexo III, 3) |
| **C3** Privacidade, proteção de dados e segurança | D3 + segurança | Ampliada | 11 | 5,29 | 4 | 3 | Slade e Prinsloo (2013); Tsai et al. (2018); Jobin et al. (2019); UNESCO (2021); LGPD |
| **C4** Equidade, inclusão e viés | D4 + viés regional | Mantida; evidência fraca declarada | 10 | 4,77 | 2 | 3 | Baker e Hawn (2022); Raji et al. (2020); Jobin et al. (2019); Floridi et al. (2018) |
| **C5** Transparência e explicabilidade | D5 | Mantida (responsabilização migra para G1) | 6 | 5,95 | 3 | 1 | Khosravi et al. (2022); Floridi et al. (2018); Amershi et al. (2019); Jobin et al. (2019) |
| **C6** Letramento em IA e desenvolvimento profissional | D6 | Mantida; renomeada | 11 | 5,06 | 3 | 4 | Ng et al. (2021); Long e Magerko (2020); Chan (2023); UNESCO (2023); Reg. UE 2024/1689 (art. 4) |

Notas: (a) contagens = união dos vínculos diretos e das listas temáticas conferidas, sem SCOPUS_26 (regra O14) e sem menções breves; (b) em C6, 9 dos 11 estudos vêm da categoria combinada "falta de letramento, formação docente e políticas", não separável (já registrado no TCC2); (c) "n" indica quantas revisões **mencionam ou descrevem** o tema, não evidência de eficácia. Nenhum componente tem evidência de eficácia nos 34 estudos.

### 5.1 Componentes, um a um

**G1 — Governança institucional e responsabilização**
- *Definição:* sistema de regras, papéis, processos e mecanismos de prestação de contas pelo qual a IES decide, autoriza, acompanha e responde pelo uso de IA (Mäntymäki et al., 2022).
- *Problema:* nove revisões apontam regulação e governança como tendência, nenhuma avalia políticas adotadas; princípios sem mecanismo não mudam a prática (Mittelstadt, 2019).
- *Estrutura:* práticas estruturais (quem decide), procedimentais (como se decide, avalia e audita) e relacionais (com quem se decide), conforme Papagiannidis et al. (2025); classificação do uso por risco, com avaliação e admissão tratadas como uso sensível (Reg. UE 2024/1689, Anexo III, ponto 3); validação ética e pedagógica de ferramentas antes da adoção (UNESCO, 2023).
- *Exemplo institucional:* comitê de IA com representação docente, discente e técnica; inventário de ferramentas em uso; política de uso aceitável revisada anualmente.
- *Relações:* condiciona C1–C6; recebe informação de G2.

**G2 — Monitoramento e avaliação baseada em evidências**
- *Definição:* ciclo de coleta de indicadores, acompanhamento de efeitos e revisão periódica das decisões (funções medir e gerenciar do NIST, 2023).
- *Problema:* 17 de 33 revisões com o critério aplicável não avaliaram a qualidade dos primários; I² ≥ 70% em 9; 10 apontam falta de estudos de longo prazo.
- *Exemplo:* indicadores por semestre (uso declarado, ocorrências de integridade, incidentes de dados, resultados de aprendizagem em disciplinas com e sem IA), com relatório ao comitê de G1.
- *Relações:* fecha o ciclo de G1; alimenta a revisão de todos os domínios.

**C1 — Agência humana, supervisão e uso pedagógico orientado**
- *Definição:* condições para que estudantes e docentes mantenham julgamento, autoria e controle sobre o uso de IA, com supervisão humana proporcional ao risco da tarefa.
- *Problema:* dependência e perda de esforço cognitivo (10 revisões); efeitos maiores relatados com orientação ou humano no circuito (3 diretas, 2 qualificadas); colaboração humano-IA como tendência (4).
- *Fundamentação:* alto nível de automação é compatível com alto controle humano (Shneiderman, 2020a); níveis de automação entre docente e IA (Molenaar, 2022); supervisão humana como princípio (UNESCO, 2021) e obrigação em usos de alto risco (Reg. UE 2024/1689); autonomia como princípio ético (Floridi et al., 2018).
- *Exemplo:* para cada disciplina, definir em que tarefas a IA é usada, quem verifica o resultado e em que pontos a decisão é necessariamente humana.
- *Relações:* depende de C6; interage com C2 (desenho da tarefa) e G2 (efeitos de longo prazo).

**C2 — Avaliação da aprendizagem e integridade acadêmica**
- *Definição:* regras e desenhos de avaliação que preservam autoria e validade quando há uso de IA, e controles sobre IA usada para avaliar estudantes.
- *Problema:* integridade e exatidão citadas como risco (5 revisões com vínculo direto); nenhuma mede ocorrência ou efeito de política.
- *Fundamentação:* escala de níveis de uso permitido por avaliação (Perkins et al., 2024); diretrizes de universidades (Moorhouse et al., 2023); avaliação de resultados por IA como uso de alto risco (Reg. UE 2024/1689).
- *Exemplo:* adotar uma escala de uso permitido em cada plano de ensino; vedar decisão automatizada de nota sem revisão humana.
- *Relações:* G1 (política), C1, C6.

**C3 — Privacidade, proteção de dados e segurança**
- *Definição:* tratamento de dados pessoais e acadêmicos por sistemas de IA (base legal, minimização, retenção, consentimento, contratos com fornecedores) e segurança dos ambientes.
- *Problema:* risco mais citado do corpus (11 revisões com vínculo direto); SCOPUS_840 trata de segurança de ambientes online; nenhuma avalia efetividade de práticas.
- *Fundamentação:* ética de dados educacionais (Slade; Prinsloo, 2013); política institucional de analytics (Tsai et al., 2018); LGPD.
- *Exemplo:* lista de ferramentas autorizadas com análise de tratamento de dados; proibição de inserir dados pessoais de estudantes em ferramentas não contratadas.

**C4 — Equidade, inclusão e viés**
- *Definição:* prevenção de efeitos desiguais entre grupos de estudantes e de exclusão por acesso, idioma ou contexto.
- *Problema:* viés citado em 7 revisões e viés regional em 5; nota média mais baixa do corpus (4,77); nenhuma auditoria com dados próprios. **Componente mantido por base conceitual e normativa; evidência do corpus fraca.**
- *Fundamentação:* Baker e Hawn (2022); auditoria interna (Raji et al., 2020); justiça como princípio convergente (Jobin et al., 2019).
- *Exemplo:* exigir do fornecedor informação sobre testes de viés; acompanhar resultados por grupo em G2; garantir acesso institucional às ferramentas exigidas.

**C5 — Transparência e explicabilidade**
- *Definição:* informação clara sobre quando e como a IA é usada e explicações adequadas a cada público.
- *Problema:* citada em 6 revisões; SCOPUS_264 relaciona antecedentes de confiança.
- *Fundamentação:* explicabilidade educacional (Khosravi et al., 2022); diretrizes de interação humano-IA (Amershi et al., 2019); explicabilidade como princípio (Floridi et al., 2018).
- *Exemplo:* informar no plano de ensino as ferramentas usadas e seus limites; documentar quando uma decisão contou com apoio de IA.

**C6 — Letramento em IA e desenvolvimento profissional**
- *Definição:* competências de estudantes, docentes e técnicos para usar, avaliar criticamente e ensinar com IA.
- *Problema:* falta de letramento e formação (9 revisões, categoria combinada); tendência em 4.
- *Fundamentação:* Ng et al. (2021); Long e Magerko (2020); Chan (2023); obrigação de letramento no Reg. UE 2024/1689 (art. 4).
- *Exemplo:* formação docente obrigatória antes de liberar ferramentas em disciplinas; conteúdo de letramento crítico nos currículos.

### 5.2 Componentes considerados e não incluídos

| Candidato | Fonte | Motivo de não incluir | Tratamento |
|---|---|---|---|
| Sustentabilidade ambiental | UNESCO (2021); Jobin et al. (2019) | Nenhum dos 34 estudos trata do tema | Registrado como lacuna e limitação de cobertura (único elemento das referências sem componente: 36 de 37 cobertos) |
| Propriedade intelectual e direitos autorais | UNESCO (2023) | Sem vínculo no corpus | Lacuna; pode ser tratado em G1 como questão jurídica |
| Bem-estar e saúde mental | Literatura geral | Sem vínculo no corpus | Lacuna |
| Contratação de fornecedores | UNESCO (2023); Reg. UE 2024/1689 | Não é domínio, é procedimento | Incorporado a G1 (validação de ferramentas) e C3 (contratos de dados) |

## 6. Avaliação analítica já realizada (ex ante)

| Critério | Verificação | Resultado |
|---|---|---|
| Cobertura dos temas do corpus | 23 temas de risco, lacuna e tendência das Tabelas 4 e 6 e da Seção 4.8 × componentes | 23 de 23 cobertos (framework de 04/11: 22 de 23; faltava dependência) |
| Cobertura de princípios de referência | 37 elementos de 7 fontes (Jobin; Floridi; UNESCO 2021; Reg. UE 2024/1689; NIST; Chan; Papagiannidis) × componentes | 36 de 37 cobertos; sem cobertura: sustentabilidade |
| Rastreabilidade | Cada componente tem IDs do corpus, contagem, nota média e referências | 8 de 8 |
| Consistência interna | Componentes não redundantes; camada de mecanismo separada da de domínio | Atendida após a reclassificação de D7 e D8 |
| Clareza e utilidade | Dependem de leitores externos | **Não avaliadas** (ver proposta de avaliação) |

O cruzamento é um julgamento analítico da autora com apoio de IA, não uma validação; deve ser conferido pelas orientadoras.

## 7. Limitações desta revisão

- A literatura de referência foi selecionada por critérios explícitos, mas sem busca sistemática; outra seleção poderia mudar nomes e fronteiras dos componentes.
- As contagens do corpus medem menção e descrição, não eficácia.
- A tese de doutorado da coorientadora ainda não foi incorporada (N1). Quando disponível, a revisão deve ser refeita na fase 3 do método.
- O framework continua não validado empiricamente.

## 8. Decisões necessárias

| # | Decisão | Recomendação |
|---|---|---|
| N6 | Adotar a arquitetura em duas camadas (G1–G2 + C1–C6) no lugar da lista plana de oito dimensões | Adotar |
| N7 | Aceitar a ampliação de D1 (dependência e agência) e as mudanças de nome | Aceitar |
| N4 | Acrescentar o objetivo específico OE5 | Acrescentar |
| N1 | Incorporar a tese da coorientadora | Assim que disponível |
