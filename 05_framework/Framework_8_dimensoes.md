# Framework conceitual de oito dimensões (proposta, não validada)

Extraído sem alteração da Seção 6 de `02_tcc2/TCC2_Documento_Completo.md` (versão de 04/11/2026). A rastreabilidade estudo a estudo está em `03_dados/csv/06_framework_rastreabilidade.csv` e na aba `6_Framework` de `03_dados/TCC2_Planilha_Auditoria.xlsx`.

## Proposta conceitual de framework

**Natureza.** Esta seção apresenta uma proposta conceitual derivada dos achados. Ela **não foi implementada nem validada empiricamente**, não resulta de consulta a especialistas e não constitui recomendação normativa nem prova de eficácia. A validação depende de trabalho futuro, que pode ocorrer em um mestrado, em que cada dimensão seria testada, refinada ou descartada. O escopo do framework neste TCC é a proposta; o TCC1 listava, entre as etapas do TCC2, desenvolvimento e avaliação do framework, e a avaliação não foi realizada. A orientadora deve confirmar esse recorte.

**Objetivo.** Organizar, em oito dimensões de governança e uso responsável de IA no ensino superior, os riscos, as lacunas e as condições de uso que as revisões incluídas apontam, indicando para cada dimensão a evidência que falta.

**Critério de construção.** A dimensão 1 parte de um sinal de benefício associado a uma condição de uso. As dimensões 2 a 7 decorrem de riscos, lacunas e recomendações nomeados pelas revisões. A dimensão 8 decorre das limitações metodológicas do próprio conjunto de estudos. A lista de estudos de cada dimensão vem das contagens de menção das Seções 4.5 a 4.8.

**Tabela 7 – Visão geral do framework**

| Dimensão | Base nos achados (menções, não eficácia) | Evidência que falta |
|---|---|---|
| 1. Uso pedagógico orientado | Efeitos maiores com orientação (SCOPUS_380, 234, IEEE_81, SCOPUS_439) | Teste controlado do moderador "orientação" |
| 2. Integridade e avaliação | Integridade citada em 6 estudos | Medidas de ocorrência e de efeito de políticas |
| 3. Privacidade e dados | Citada em 12 estudos | Efetividade de práticas em IES |
| 4. Equidade e viés | Citados em 8 estudos | Auditorias de viés em ferramentas educacionais |
| 5. Transparência e explicabilidade | Citadas em 6 estudos | Relação com confiança calibrada e aprendizagem |
| 6. Letramento e formação | Citados em 9 estudos (inclui políticas) | Efeito de programas de formação |
| 7. Políticas e governança | Tendência em 9 estudos | Avaliação de políticas já adotadas |
| 8. Monitoramento e qualidade da evidência | 17 de 33 sem avaliação de qualidade dos primários; I² alto em 9 | Estudos longitudinais; medida de sobreposição |

### 6.1. Uso pedagógico orientado, com docente no circuito

**Definição.** Conjunto de condições de desenho pedagógico em que o uso de IA é planejado e acompanhado: orientação de uso, papel do docente na verificação e no feedback, tipo de tarefa e duração da intervenção.

**Justificativa.** Os efeitos relatados variam com a condição de uso. Essa dimensão organiza o que as revisões relatam como moderador do resultado, sem afirmar que a orientação cause o efeito.

**Evidências nos estudos incluídos.** SCOPUS_380 relata g = 1,20 com orientação de uso contra g = 1,14 no efeito global; SCOPUS_234, ganhos maiores com uso orientado e em habilidades de ordem inferior; IEEE_81, intervenção docente com efeito numericamente maior (0,517 contra 0,477), sem diferença estatisticamente significativa; SCOPUS_439, intervenção docente amplifica significativamente apenas o engajamento cognitivo; SCOPUS_639, avaliação por IA com melhor eficácia com humano no circuito; SCOPUS_391, disciplina modera os efeitos de ordem superior e pequenos grupos em STEM aparecem como promissores (mineração de regras, exploratória); SCOPUS_26, apenas como menção na revisão de literatura do próprio estudo, que cita terceiros sobre envolvimento docente na verificação das respostas (não é achado da síntese). Sobre a duração, SCOPUS_439 relata ganho maior em duração média e IEEE_81, efeito menor em durações mais longas: o dado é contraditório.

**Relação com as demais dimensões.** Depende de 6 (o docente precisa de letramento) e de 7 (políticas definem o que é uso permitido). Interage com 2 (formato da avaliação) e com 8 (efeitos de longo prazo e moderadores ainda não testados).

**Implicações para IES.** Definir, por curso ou disciplina, em que tarefas o uso de IA é previsto, quem verifica os resultados e como o docente é informado do uso.

**Questões para investigação futura.** O moderador "orientação" foi relatado por estudos de métodos e desfechos diferentes e nunca testado de forma controlada: que tipo de orientação, em que tarefa, por quanto tempo e com qual desfecho?

### 6.2. Integridade acadêmica e desenho da avaliação

**Definição.** Práticas e regras que protegem a autoria e a validade da avaliação quando estudantes e docentes usam IA.

**Justificativa.** Integridade acadêmica e plágio são citados como risco em seis estudos; exatidão das respostas, em quatro. A avaliação é onde a IA e a regra institucional mais se tocam.

**Evidências nos estudos incluídos.** Integridade e plágio: 15, 12, IEEE_101, 117, 456, 594. Exatidão e confiabilidade das respostas: 196, IEEE_101, 456, 26. Avaliação e feedback automatizados como aplicação: 15, 159, 431, 639.

**Relação com as demais dimensões.** Liga-se a 7 (política de uso aceitável), a 1 (o desenho da tarefa reduz ou aumenta o incentivo ao uso indevido) e a 6 (formação para citar e verificar).

**Implicações para IES.** Explicitar, por tipo de avaliação, o que é uso permitido, o que deve ser declarado e como a autoria é verificada.

**Questões para investigação futura.** Nenhum estudo incluído mediu a ocorrência de violações nem testou políticas de avaliação; os estudos relatam a preocupação. Quais desenhos de avaliação são mais robustos ao uso de IA, e com que custo?

### 6.3. Privacidade e proteção de dados

**Definição.** Tratamento de dados pessoais e acadêmicos por sistemas de IA: coleta, consentimento, minimização, retenção, segurança e responsabilidade do fornecedor.

**Justificativa.** Privacidade e segurança de dados são o risco mais citado (12 estudos). Por ser transversal ao uso de qualquer ferramenta, merece dimensão própria.

**Evidências nos estudos incluídos.** Citam privacidade ou segurança de dados: IEEE_132, 15, 129, 9, 12, 117, 594, 639, 840, 968, 852, 838. SCOPUS_840 trata de medidas de cibersegurança baseadas em IA e convencionais em ensino superior online. SCOPUS_852 revisa programas de pós-graduação e descreve tipos de dados, riscos e práticas e marcos de privacidade em análise de dados educacionais (incluído com ressalva de IA clássica, R1). **Lacuna:** nenhum dos 34 estudos incluídos avaliou a efetividade de práticas de privacidade em IES. Esta dimensão, portanto, se apoia em menções de risco e em descrições de práticas, não em evidência de efeito.

**Relação com as demais dimensões.** Condiciona 7 (política institucional) e 5 (transparência sobre quais dados o sistema usa). Afeta 4 (dados enviesados) e 1 (que dados o docente pode inserir).

**Implicações para IES.** Mapear quais dados cada ferramenta recebe, onde são processados e por quanto tempo são mantidos, antes da adoção.

**Questões para investigação futura.** Que práticas de privacidade IES adotam, e com que efeito sobre exposição de dados? Há diferença entre ferramentas institucionais e ferramentas de consumo?

### 6.4. Equidade e viés algorítmico

**Definição.** Atenção a diferenças de acesso, de desempenho e de tratamento entre grupos de estudantes associadas ao uso de IA ou a viés em seus dados e modelos.

**Justificativa.** Viés e equidade aparecem em 8 estudos; acessibilidade e inclusão aparecem como benefício em SCOPUS_129. Viés regional e cultural da própria literatura é lacuna apontada por seis estudos.

**Evidências nos estudos incluídos.** Citam viés ou equidade: IEEE_132, 15, 12, 129, 594, 596, 968, 852. Viés regional e cultural da literatura: SCOPUS_12, 1, IEEE_101, SCOPUS_129, 26 e 593.

**Relação com as demais dimensões.** Relaciona-se com 5 (explicabilidade permite examinar o viés), 3 (dados) e 8 (monitorar efeitos por grupo).

**Implicações para IES.** Prever monitoramento de resultados por grupo e verificação de acessibilidade das ferramentas adotadas.

**Questões para investigação futura.** Nenhum estudo incluído audita viés em ferramentas educacionais com dados próprios. Que auditorias são viáveis para uma IES?

### 6.5. Transparência e explicabilidade

**Definição.** Informação sobre o que a ferramenta faz, com que dados e com que limites, e grau em que suas decisões ou saídas podem ser explicadas a estudantes e docentes.

**Justificativa.** Transparência e explicabilidade são citadas em 6 estudos, e um deles (SCOPUS_264) mede a relação entre desempenho tecnológico e confiança.

**Evidências nos estudos incluídos.** Citam transparência ou explicabilidade: 12, 159, 264, 639, 840, 852. SCOPUS_264 relata r = 0,407 entre desempenho tecnológico e confiança do aprendiz; SCOPUS_838 relata, em outra métrica, r de 0,127 a 0,229 entre learning analytics em bibliotecas e desempenho (sem relação com explicabilidade). A métrica e o desfecho de SCOPUS_264 não são comparáveis aos de outros estudos.

**Relação com as demais dimensões.** Sustenta 4 (examinar viés), 3 (saber que dados são usados) e 1 (docente avalia a saída).

**Implicações para IES.** Exigir do fornecedor informação mínima sobre funcionamento, dados e limites, e informar a comunidade acadêmica.

**Questões para investigação futura.** A explicabilidade melhora a confiança calibrada ou apenas a confiança? Qual o efeito sobre a aprendizagem?

### 6.6. Letramento em IA e formação docente

**Definição.** Competências de estudantes, docentes e gestores para entender, usar, verificar e questionar sistemas de IA, e programas institucionais que as desenvolvem.

**Justificativa.** Falta de letramento, de formação docente e de políticas é o terceiro tema mais citado (9 estudos, em categoria que reúne formação e políticas) e é tendência futura apontada por quatro.

**Evidências nos estudos incluídos.** Tema (letramento, formação e políticas): 289, 129, 9, 12, 196, 431, IEEE_101, 234, 456. Tendência de letramento e formação docente: IEEE_132, SCOPUS_9, 431 e 596. A extração não separou, por estudo, o que se refere à formação e o que se refere a políticas; por isso a Dimensão 7 usa a lista de regulação e governança (RQ4).

**Relação com as demais dimensões.** Pré-condição de 1 e 2; apoia 3 a 5, pois a verificação depende do conhecimento de quem usa.

**Implicações para IES.** Oferecer formação diferenciada para docentes, estudantes e técnicos, ligada às regras vigentes na IES.

**Questões para investigação futura.** Que conteúdos e formatos de formação alteram o comportamento e os resultados? Nenhum estudo incluído mede o efeito de programas de formação.

### 6.7. Políticas e governança institucional

**Definição.** Regras, responsabilidades e instâncias que definem o uso aceitável de IA, a escolha de ferramentas, a prestação de contas e a revisão periódica.

**Justificativa.** Regulação, governança e marcos éticos são a tendência apontada por mais estudos (nove) e a ausência de políticas aparece como risco.

**Evidências nos estudos incluídos.** Apontam regulação e governança como tendência: SCOPUS_15, 129, 9, 12, 594, 596, 639, IEEE_101 e IEEE_132. Orientação institucional insuficiente aparece no tema de letramento e políticas: 289, 129, 9, 12, 196, 431, IEEE_101, 234, 456. SCOPUS_639 aponta falta de frameworks de desenho, avaliação e uso.

**Relação com as demais dimensões.** Estrutura as demais: define o que 2 e 3 exigem, o que 1 permite, quem executa 6 e como 8 acompanha.

**Implicações para IES.** Atribuir responsabilidade (comitê, unidade ou cargo) e prever revisão das regras, dado o ritmo de mudança das ferramentas.

**Questões para investigação futura.** Nenhum estudo incluído avalia políticas de IA já adotadas por IES (adoção, conformidade ou efeito). Que modelos de governança funcionam em instituições de portes e contextos distintos?

### 6.8. Monitoramento do impacto e qualidade da evidência

**Definição.** Acompanhamento sistemático dos efeitos do uso de IA na instituição e critérios para julgar a evidência que sustenta cada decisão.

**Justificativa.** A literatura secundária tem limitações que afetam qualquer decisão baseada nela: ausência de avaliação de qualidade dos primários, heterogeneidade alta, viés de publicação, curta duração e sobreposição não medida.

**Evidências nos estudos incluídos.** 17 de 33 estudos sem avaliação da qualidade dos primários (Q5 = Não); nove com I² ≥ 70% (SCOPUS_196, IEEE_132, SCOPUS_9, 1, 380, IEEE_81, SCOPUS_439, 66 e 391); viés de publicação em SCOPUS_380, 456, 593, 66 e 838; efeitos de longo prazo como lacuna em SCOPUS_15, 12, 380, IEEE_101, 234, 391, 66, 594, 852 e 838.

**Relação com as demais dimensões.** Fecha o ciclo com 1 a 7: indicadores de uso, de efeito e de risco alimentam a revisão das regras.

**Implicações para IES.** Definir indicadores e prazos de revisão; tratar os efeitos publicados como evidência heterogênea, não como previsão para a instituição.

**Questões para investigação futura.** Estudos longitudinais, avaliação de qualidade dos primários e medida da sobreposição entre meta-análises.

**Como validar (proposta, não realizado).** Uma validação futura poderia combinar consulta estruturada a especialistas (docentes, gestores, profissionais de TI e de proteção de dados) para refinar as dimensões e um estudo de caso em uma IES para testar a aplicabilidade e os indicadores da dimensão 8. O método de validação deve ser definido com a orientadora.

