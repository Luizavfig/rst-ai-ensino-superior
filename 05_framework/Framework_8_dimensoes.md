# Framework conceitual de oito dimensões (proposta, não validada)

Extraído da Seção 6 de `02_tcc2/TCC2_Documento_Completo.md` (versão consolidada de 05/11/2026, incluindo a Seção 6.9 de revisão final da fundamentação e a Tabela 8). Rastreabilidade estudo a estudo: `03_dados/csv/06_framework_rastreabilidade.csv` (com a classe do vínculo), `03_dados/csv/10_dimensoes_x_estudos_verificado.csv` (conferência nos PDFs), `03_dados/csv/11_dimensoes_suficiencia.csv` (suficiência por dimensão) e `03_dados/csv/12_dimensoes_literatura_complementar.csv` (literatura brasileira, fora do corpus, que não conta como evidência).

## Proposta conceitual de framework

**Natureza.** Esta seção apresenta uma proposta conceitual derivada dos achados. Ela **não foi implementada nem validada empiricamente**, não resulta de consulta a especialistas e não constitui recomendação normativa nem prova de eficácia. A validação depende de trabalho futuro, que pode ocorrer em um mestrado, em que cada dimensão seria testada, refinada ou descartada. O escopo do framework neste TCC é a proposta; o TCC1 listava, entre as etapas do TCC2, desenvolvimento e avaliação do framework, e a avaliação não foi realizada. A orientadora deve confirmar esse recorte.

**Objetivo.** Organizar, em oito dimensões de governança e uso responsável de IA no ensino superior, os riscos, as lacunas e as condições de uso que as revisões incluídas apontam, indicando para cada dimensão a evidência que falta.

**Critério de construção.** A dimensão 1 parte de um sinal de benefício associado a uma condição de uso. As dimensões 2 a 7 decorrem de riscos, lacunas e recomendações nomeados pelas revisões. A dimensão 8 decorre das limitações metodológicas do próprio conjunto de estudos. A lista de estudos de cada dimensão vem das contagens de menção das Seções 4.5 a 4.8; a Seção 6.9 classifica cada vínculo (direto, qualificado, menção breve ou sem valor de evidência) e avalia a suficiência da evidência por dimensão. **[Pendente O8]**

**Tabela 7 – Visão geral do framework**

| Dimensão | Base nos achados (menções, não eficácia) | Evidência que falta |
|---|---|---|
| 1. Uso pedagógico orientado | Efeito maior com orientação em SCOPUS_380 e 234; numericamente maior, sem diferença significativa ou só em um desfecho, em IEEE_81 e SCOPUS_439; SCOPUS_639 cita dois primários (vínculo direto em 3 estudos) | Teste controlado do moderador "orientação" |
| 2. Integridade e avaliação | Integridade citada em 6 estudos (vínculo direto em 4; exatidão com vínculo direto em 2) | Medidas de ocorrência e de efeito de políticas |
| 3. Privacidade e dados | Citada em 12 estudos (vínculo direto em 11) | Efetividade de práticas em IES |
| 4. Equidade e viés | Citados em 8 estudos (vínculo direto em 7) | Auditorias de viés em ferramentas educacionais |
| 5. Transparência e explicabilidade | Citadas em 6 estudos | Relação com confiança calibrada e aprendizagem |
| 6. Letramento e formação | Citados em 9 estudos em categoria combinada com políticas; tendência separável em 4 (IEEE_132, SCOPUS_9, 431 e 596) | Efeito de programas de formação |
| 7. Políticas e governança | Tendência em 9 estudos (vínculo direto); a lista de orientação institucional insuficiente é a da dimensão 6 e não conta | Avaliação de políticas já adotadas |
| 8. Monitoramento e qualidade da evidência | 17 de 33 sem avaliação de qualidade dos primários; I² alto em 9 | Estudos longitudinais; medida de sobreposição |

### 6.1 Uso pedagógico orientado, com docente no circuito

**Definição.** Conjunto de condições de desenho pedagógico em que o uso de IA é planejado e acompanhado: orientação de uso, papel do docente na verificação e no feedback, tipo de tarefa e duração da intervenção.

**Justificativa.** Os efeitos relatados variam com a condição de uso. Essa dimensão organiza o que as revisões relatam como moderador do resultado, sem afirmar que a orientação cause o efeito.

**Evidências nos estudos incluídos.** *Orientação ou intervenção docente, vínculo direto:* SCOPUS_380 relata g = 1,20 com orientação de uso contra g = 1,14 no efeito global; SCOPUS_234, ganhos maiores com uso orientado e em habilidades de ordem inferior (nota de leitura do PDF); SCOPUS_639, avaliação por IA com melhor eficácia com humano no circuito, a partir de dois estudos primários citados. *Vínculo qualificado:* IEEE_81, intervenção docente com efeito numericamente maior (0,517 contra 0,477), sem diferença estatisticamente significativa; SCOPUS_439, intervenção docente amplifica significativamente apenas o engajamento cognitivo. *Condições de desenho, não orientação:* SCOPUS_391 relata que a disciplina modera os efeitos de ordem superior e, em regras de mineração exploratórias, intervenções em sala e de até uma semana (habilidades de ordem inferior) e pequenos grupos em STEM (ordem superior e não cognitivas) aparecem como promissores; o PDF não traz moderador de orientação docente. *Duração:* SCOPUS_439 relata ganho maior em duração média e IEEE_81, efeito menor em durações mais longas: o dado é contraditório. *Sem valor de evidência:* SCOPUS_26 traz a menção apenas na revisão de literatura do próprio estudo, que cita terceiros sobre envolvimento docente na verificação das respostas (não é achado da síntese).

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** B2 e B3 (análises documentais) e G4 (reportagem com entrevistados) descrevem a supervisão humana e o diálogo entre docentes e estudantes sobre as ferramentas permitidas; B3 trata de pesquisa acadêmica, e G4 reúne opiniões. Nenhum mede efeito de orientação docente, por isso a evidência que falta continua a mesma.

**Relação com as demais dimensões.** Depende de 6 (o docente precisa de letramento) e de 7 (políticas definem o que é uso permitido). Interage com 2 (formato da avaliação) e com 8 (efeitos de longo prazo e moderadores ainda não testados).

**Implicações para IES.** Definir, por curso ou disciplina, em que tarefas o uso de IA é previsto, quem verifica os resultados e como o docente é informado do uso.

**Questões para investigação futura.** O moderador "orientação" foi relatado por estudos de métodos e desfechos diferentes e nunca testado de forma controlada: que tipo de orientação, em que tarefa, por quanto tempo e com qual desfecho?

### 6.2 Integridade acadêmica e desenho da avaliação

**Definição.** Práticas e regras que protegem a autoria e a validade da avaliação quando estudantes e docentes usam IA.

**Justificativa.** Integridade acadêmica e plágio são citados como risco em seis estudos (quatro com vínculo direto; SCOPUS_456 por menção breve e SCOPUS_117 por menção secundária); exatidão das respostas, em quatro (IEEE_101 e 456 com vínculo direto; SCOPUS_196 por menção breve e SCOPUS_26 citando terceiros). A avaliação é onde a IA e a regra institucional mais se tocam.

**Evidências nos estudos incluídos.** Integridade e plágio, vínculo direto: 15, 12, IEEE_101 e 594; SCOPUS_456 (menção breve, na introdução e nas recomendações, citando terceiros) e SCOPUS_117 (uma ocorrência, em frase de implicações; sem valor de evidência). Exatidão e confiabilidade das respostas, vínculo direto: IEEE_101 e 456; SCOPUS_196 (menção breve, citando terceiros) e SCOPUS_26 (revisão de literatura do próprio estudo, citando terceiros; sem valor de evidência). Avaliação e feedback automatizados (15, 159, 431 e 639) são aplicação e contexto, não evidência de integridade.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** B2, B3, G3 (descrito só por fontes secundárias) e G4 descrevem exigências de autoria, declaração de uso e integridade nos documentos analisados; B1 e B4 analisam o grau de formalização das regras. Nenhum mede a ocorrência de violações nem o efeito das regras.

**Relação com as demais dimensões.** Liga-se a 7 (política de uso aceitável), a 1 (o desenho da tarefa reduz ou aumenta o incentivo ao uso indevido) e a 6 (formação para citar e verificar).

**Implicações para IES.** Explicitar, por tipo de avaliação, o que é uso permitido, o que deve ser declarado e como a autoria é verificada.

**Questões para investigação futura.** Nenhum estudo incluído mediu a ocorrência de violações nem testou políticas de avaliação; os estudos relatam a preocupação. Quais desenhos de avaliação são mais robustos ao uso de IA, e com que custo?

### 6.3 Privacidade e proteção de dados

**Definição.** Tratamento de dados pessoais e acadêmicos por sistemas de IA: coleta, consentimento, minimização, retenção, segurança e responsabilidade do fornecedor.

**Justificativa.** Privacidade e segurança de dados são o risco mais citado (12 estudos). Por ser transversal ao uso de qualquer ferramenta, merece dimensão própria.

**Evidências nos estudos incluídos.** Citam privacidade ou segurança de dados com vínculo direto: IEEE_132, 15, 129, 9, 12, 117, 594, 840, 968, 852 e 838. SCOPUS_639 aparece na contagem de menção (12 estudos), mas tem duas ocorrências do tema e não conta como evidência da dimensão. SCOPUS_840 trata de medidas de cibersegurança baseadas em IA e convencionais em ensino superior online. SCOPUS_852 revisa programas de pós-graduação e descreve tipos de dados, riscos e práticas e marcos de privacidade em análise de dados educacionais (incluído com ressalva de IA clássica, R1). **Lacuna:** nenhum dos 34 estudos incluídos avaliou a efetividade de práticas de privacidade em IES. Esta dimensão, portanto, se apoia em menções de risco e em descrições de práticas, não em evidência de efeito.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** B6 (resumo de evento) e G1 (reportagem) citam a proteção de dados entre os princípios dos documentos; G2 e G3 descrevem, por fontes secundárias, a classificação de risco do parecer CNE/CP 15/26. B1 foi mapeado nesta dimensão no Apêndice G. Nenhum avalia a efetividade de práticas de privacidade.

**Relação com as demais dimensões.** Condiciona 7 (política institucional) e 5 (transparência sobre quais dados o sistema usa). Afeta 4 (dados enviesados) e 1 (que dados o docente pode inserir).

**Implicações para IES.** Mapear quais dados cada ferramenta recebe, onde são processados e por quanto tempo são mantidos, antes da adoção.

**Questões para investigação futura.** Que práticas de privacidade IES adotam, e com que efeito sobre exposição de dados? Há diferença entre ferramentas institucionais e ferramentas de consumo?

### 6.4 Equidade e viés algorítmico

**Definição.** Atenção a diferenças de acesso, de desempenho e de tratamento entre grupos de estudantes associadas ao uso de IA ou a viés em seus dados e modelos.

**Justificativa.** Viés e equidade aparecem em 8 estudos; acessibilidade e inclusão aparecem como benefício em SCOPUS_129. Viés regional e cultural da própria literatura é lacuna apontada por seis estudos.

**Evidências nos estudos incluídos.** Citam viés ou equidade com vínculo direto: IEEE_132, 12, 129, 594, 596, 968 e 852; SCOPUS_15 é menção breve (uma frase de recomendação; dois dos três usos de "bias" não se referem a viés algorítmico). Lacuna contextual da literatura (construto distinto do viés algorítmico): SCOPUS_12, 1, IEEE_101, 129 e 26 apontam a representatividade regional e cultural; SCOPUS_593 sugere investigar diferenças de gênero e culturais como moderadores.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** Só B6 (resumo de evento) e G1 (reportagem) citam equidade e combate a vieses, como princípios; não há análise empírica de viés em ferramentas.

**Relação com as demais dimensões.** Relaciona-se com 5 (explicabilidade permite examinar o viés), 3 (dados) e 8 (monitorar efeitos por grupo).

**Implicações para IES.** Prever monitoramento de resultados por grupo e verificação de acessibilidade das ferramentas adotadas.

**Questões para investigação futura.** Nenhum estudo incluído audita viés em ferramentas educacionais com dados próprios. Que auditorias são viáveis para uma IES?

### 6.5 Transparência e explicabilidade

**Definição.** Informação sobre o que a ferramenta faz, com que dados e com que limites, e grau em que suas decisões ou saídas podem ser explicadas a estudantes e docentes.

**Justificativa.** Transparência e explicabilidade são citadas em 6 estudos, e um deles (SCOPUS_264) mede a relação entre desempenho tecnológico e confiança.

**Evidências nos estudos incluídos.** Citam transparência ou explicabilidade: 12, 159, 264, 639, 840, 852. SCOPUS_264 relata r = 0,407 entre desempenho tecnológico e confiança do aprendiz; SCOPUS_838 relata, em outra métrica, r de 0,127 a 0,229 entre learning analytics em bibliotecas e desempenho (sem relação com explicabilidade). A métrica e o desfecho de SCOPUS_264 não são comparáveis aos de outros estudos.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** B2, B3, B6, G1 e G3 (este, por fontes secundárias) citam transparência e declaração de uso de IA como princípio ou exigência; não medem confiança nem aprendizagem.

**Relação com as demais dimensões.** Sustenta 4 (examinar viés), 3 (saber que dados são usados) e 1 (docente avalia a saída).

**Implicações para IES.** Exigir do fornecedor informação mínima sobre funcionamento, dados e limites, e informar a comunidade acadêmica.

**Questões para investigação futura.** A explicabilidade melhora a confiança calibrada ou apenas a confiança? Qual o efeito sobre a aprendizagem?

### 6.6 Letramento em IA e formação docente

**Definição.** Competências de estudantes, docentes e gestores para entender, usar, verificar e questionar sistemas de IA, e programas institucionais que as desenvolvem.

**Justificativa.** Falta de letramento, de formação docente e de políticas é o terceiro tema mais citado (9 estudos, em categoria que reúne formação e políticas) e é tendência futura apontada por quatro.

**Evidências nos estudos incluídos.** Tendência separável de letramento e formação docente, vínculo direto: IEEE_132, SCOPUS_9, 431 e 596. Tema combinado de letramento, formação e políticas (categoria única da Tabela 6): 289, 129, 9, 12, 196, 431, IEEE_101, 234, 456. A extração não separou, por estudo, o que se refere à formação e o que se refere a políticas; por isso a Dimensão 7 usa a lista de regulação e governança (RQ4) e não conta a segunda lista como evidência própria.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** B1 e B1a recomendam formação continuada; B2, B4, B6, G1 e G4 citam formação docente, capacitação, orientação formativa ou letramento em IA. São descrições e recomendações, sem medida do efeito de programas.

**Relação com as demais dimensões.** Pré-condição de 1 e 2; apoia 3 a 5, pois a verificação depende do conhecimento de quem usa.

**Implicações para IES.** Oferecer formação diferenciada para docentes, estudantes e técnicos, ligada às regras vigentes na IES.

**Questões para investigação futura.** Que conteúdos e formatos de formação alteram o comportamento e os resultados? Nenhum estudo incluído mede o efeito de programas de formação.

### 6.7 Políticas e governança institucional

**Definição.** Regras, responsabilidades e instâncias que definem o uso aceitável de IA, a escolha de ferramentas, a prestação de contas e a revisão periódica.

**Justificativa.** Regulação, governança e marcos éticos são a tendência apontada por mais estudos (nove) e a ausência de políticas aparece como risco.

**Evidências nos estudos incluídos.** Apontam regulação e governança como tendência, vínculo direto: SCOPUS_15, 129, 9, 12, 594, 596, 639, IEEE_101 e IEEE_132. A orientação institucional insuficiente aparece no tema combinado de letramento e políticas (289, 129, 9, 12, 196, 431, IEEE_101, 234 e 456), que é a lista da Dimensão 6 e não foi separada por componente; por isso não conta como evidência própria desta dimensão. SCOPUS_639 aponta falta de frameworks de desenho, avaliação e uso.

**Literatura complementar brasileira (fora do corpus de 34 e dos 53 avaliados).** Uma busca exploratória feita em 05/11/2026, fora do protocolo e sem avaliação por Q1–Q8 (Apêndice G), localizou estudos documentais sobre regras institucionais de IA generativa em universidades brasileiras (Apêndice G, B1 a B4) e o parecer CNE/CP 15/26, aprovado em 01/09/2026 e ainda sem homologação (G3). Esses trabalhos descrevem políticas já adotadas, com princípios recorrentes (transparência, integridade acadêmica e supervisão humana) e grau de formalização heterogêneo, mas analisam o conteúdo dos documentos e não medem a efetividade das políticas; por isso não alteram a lacuna declarada abaixo. B2 e B4 foram lidos só no resumo da página, e G3, só por fontes secundárias. Esse material não sustenta a síntese nem entrou em nenhuma contagem deste trabalho. **[Pendente O13, O15, L13]**

**Relação com as demais dimensões.** Estrutura as demais: define o que 2 e 3 exigem, o que 1 permite, quem executa 6 e como 8 acompanha.

**Implicações para IES.** Atribuir responsabilidade (comitê, unidade ou cargo) e prever revisão das regras, dado o ritmo de mudança das ferramentas.

**Questões para investigação futura.** Nenhum estudo incluído avalia políticas de IA já adotadas por IES (adoção, conformidade ou efeito). Que modelos de governança funcionam em instituições de portes e contextos distintos?

### 6.8 Monitoramento do impacto e qualidade da evidência

**Definição.** Acompanhamento sistemático dos efeitos do uso de IA na instituição e critérios para julgar a evidência que sustenta cada decisão.

**Justificativa.** A literatura secundária tem limitações que afetam qualquer decisão baseada nela: ausência de avaliação de qualidade dos primários, heterogeneidade alta, viés de publicação, curta duração e sobreposição não medida.

**Evidências nos estudos incluídos.** 17 de 33 estudos sem avaliação da qualidade dos primários (Q5 = Não); nove com I² ≥ 70% (SCOPUS_196, IEEE_132, SCOPUS_9, 1, 380, IEEE_81, SCOPUS_439, 66 e 391); viés de publicação em SCOPUS_380, 456, 593, 66 e 838; efeitos de longo prazo como lacuna em SCOPUS_15, 12, 380, IEEE_101, 234, 391, 66, 594, 852 e 838.

**Literatura complementar brasileira (fora do corpus; não conta como evidência).** Nenhum item do Apêndice G foi mapeado nesta dimensão: a dimensão 8 trata de propriedades do corpus avaliado.

**Relação com as demais dimensões.** Fecha o ciclo com 1 a 7: indicadores de uso, de efeito e de risco alimentam a revisão das regras.

**Implicações para IES.** Definir indicadores e prazos de revisão; tratar os efeitos publicados como evidência heterogênea, não como previsão para a instituição.

**Questões para investigação futura.** Estudos longitudinais, avaliação de qualidade dos primários e medida da sobreposição entre meta-análises.

**Como validar (proposta, não realizado).** Uma validação futura poderia combinar consulta estruturada a especialistas (docentes, gestores, profissionais de TI e de proteção de dados) para refinar as dimensões e um estudo de caso em uma IES para testar a aplicabilidade e os indicadores da dimensão 8. O método de validação deve ser definido com a orientadora.

### 6.9 Revisão final da fundamentação das dimensões

**Objetivo.** Verificar se cada dimensão tem evidência suficiente no corpus de 34 estudos, corrigir vínculos fracos e separar o que vem do corpus do que vem da literatura complementar brasileira. Os vínculos foram conferidos nos PDFs (palavras-chave com leitura do contexto) ou nas fichas; a conferência por assistente de IA não substitui a conferência humana da autora. **[Pendente L12]**

**Regra de classificação (desta revisão final; não é regra do protocolo).** O vínculo é *direto* quando o estudo trata o tema como achado ou recomendação própria; *qualificado* quando a diferença relatada não é significativa ou vale só em um desfecho; *menção breve* quando o tema aparece em uma frase; e *sem valor de evidência* quando a menção cita terceiros na revisão de literatura do próprio estudo, é secundária (uma ou duas ocorrências), é aplicação sem relação com a dimensão ou repete lista já usada em outra dimensão. A suficiência é *adequada* com pelo menos 5 estudos diretos, 2 deles com nota 6,0 ou mais, e pelo menos 5 estudos diretos fora os quatro de IA clássica (cenário A da Seção 4.9); *parcial* com 3 ou 4 estudos diretos ou se faltar alguma dessas condições; *frágil* com 2 ou menos. "Adequada" significa suficiente para sustentar a dimensão como organização do que a literatura aponta, nunca prova de eficácia. **[Pendente O8]**

**Tabela 8 – Suficiência da evidência por dimensão (corpus de 34 estudos)**

| Dimensão | Estudos com vínculo direto | Nota média (equiv. 8) | Diretos com nota ≥ 6,0 | Diretos no cenário A | Vínculos que não são diretos | Suficiência |
|---|---|---|---|---|---|---|
| D1 Uso pedagógico orientado | 3 | 5,83 | 1 | 3 | qualificados: IEEE_81, 439; condições de desenho: 391; sem valor de evidência: 26 | Parcial |
| D2 Integridade e avaliação | 4 | 5,05 | 1 | 4 | menção breve: 196, 456; sem valor de evidência: 117, 159, 26, 431, 639 | Parcial |
| D3 Privacidade e dados | 11 | 5,29 | 4 | 9 | sem valor de evidência: 639 | Adequada |
| D4 Equidade e viés | 7 | 4,53 | 1 | 6 | menção breve: 15 | Parcial |
| D5 Transparência e explicabilidade | 6 | 5,95 | 3 | 5 | — | Adequada |
| D6 Letramento e formação | 4 | 5,0 | 1 | 4 | tema combinado com D7: 9 estudos (não separável) | Parcial |
| D7 Políticas e governança | 9 | 4,86 | 2 | 9 | sem valor de evidência: 196, 234, 289, 431, 456 | Adequada |
| D8 Monitoramento e qualidade da evidência | 17 | 5,81 | 9 | 15 | menção breve: 594 | Adequada |

**Resultado.** A evidência é adequada nas dimensões 3, 5, 7 e 8 e parcial nas dimensões 1 (três estudos diretos, só um com nota de 6,0 ou mais), 2 (quatro estudos diretos de integridade), 4 (sete estudos diretos, só um com nota de 6,0 ou mais e média de 4,53, a mais baixa) e 6 (quatro estudos com tendência separável; os outros nove vêm de categoria combinada com políticas). Nenhuma dimensão tem estudo do corpus que avalie a eficácia de práticas institucionais: a evidência é de menção, de descrição ou, na dimensão 1, de moderador relatado por meta-análises (comparação entre estudos, não teste controlado), e na dimensão 8, de propriedades do próprio corpus. A dimensão 8 não depende de menção: as contagens de I², viés de publicação e avaliação de qualidade vêm de dados dos estudos. O número 17 nesta linha (estudos com vínculo direto, união de três listas) não se confunde com os 17 de 33 estudos sem avaliação de qualidade dos primários. O cenário B (38 estudos) não foi calculado por dimensão, porque a ligação dos quatro estudos pós-corte às dimensões não foi extraída: [INFORMAÇÃO NÃO DISPONÍVEL NOS DOCUMENTOS FORNECIDOS]. A classificação não altera as Tabelas 4 a 6, que seguem a regra de menção. **[Pendente O14]**

**Corpus original e literatura complementar brasileira.** As Tabelas 7 e 8 e as Seções 6.1 a 6.8 usam só os 34 estudos incluídos. A literatura complementar brasileira do Apêndice G (busca exploratória de 05/11/2026, fora do protocolo, sem Q1 a Q8) aparece em cada dimensão em parágrafo separado e **não conta como evidência**, não entra em nenhuma contagem e não altera a suficiência da Tabela 8. Mapeamento por dimensão (códigos do Apêndice G): D1, B2, B3 e G4; D2, B1, B2, B3, B4, G2, G3 e G4; D3, B1, B6, G1, G2 e G3; D4, B6 e G1; D5, B2, B3, B6, G1 e G3; D6, B1, B1a, B2, B4, B6, G1 e G4; D7, B1, B1a, B2, B4, B6, G1, G2 e G3; D8, nenhum. O mapeamento foi feito pela autora do documento a partir dos resumos e textos lidos e é interpretativo. **[Pendente O13]**
