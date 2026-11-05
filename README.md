# Revisão Sistemática Terciária: IA no Ensino Superior

**Autora:** Luiza de Campos Velasque Figueiredo
**Instituição:** UNIPAMPA, Campus Alegrete, RS
**Ano:** 2026

Repositório do TCC (revisão sistemática terciária, RST, sobre Inteligência Artificial no Ensino Superior), com o protocolo, o TCC2, as planilhas, o fluxo PRISMA, o framework e o relatório de auditoria. Metodologia: Kitchenham e Charters, PRISMA 2020 e AMSTAR 2 (inspiração dos critérios de qualidade Q1 a Q8).

**Situação (05/11/2026).** O texto do TCC2 está completo (34 estudos incluídos, 19 excluídos, 5 não recuperados), mas o trabalho **não está concluído**: depende de decisões da orientadora e de informações da autora. Veja o relatório de auditoria, seções 14 e 15.

## Questões de pesquisa

- **RQ1** Quais são as principais aplicações de IA no Ensino Superior?
- **RQ2** Quais benefícios são reportados?
- **RQ3** Quais desafios, limitações e preocupações éticas são discutidos?
- **RQ4** Quais lacunas e tendências de pesquisa são identificadas?

## Estrutura

| Caminho | Conteúdo |
|---|---|
| `protocolo_atualizado_TCC.pdf` | Protocolo da revisão. Fica na raiz porque o TCC1 cita esse arquivo |
| `material-suplementar/` | Rastreabilidade do corpus do TCC1 (PDF e XLSX). Fica na raiz pelo mesmo motivo |
| `02_tcc2/TCC2_Documento_Completo.md` | Texto completo do TCC2 (versão de 04/11/2026) |
| `03_dados/TCC2_Planilha_Auditoria.xlsx` | Planilha com fórmulas: 58 estudos, notas Q1 a Q8, fluxo PRISMA, conferências, desvios, framework, pendências |
| `03_dados/csv/` | Os mesmos dados em CSV (7 arquivos, numerados de 01 a 07) |
| `03_dados/tcc1/` | Planilha de artigos citados no TCC1 |
| `04_prisma/` | Figura do fluxo PRISMA (`fig1_fluxo_prisma.png`) e a tabela de contagens |
| `05_framework/Framework_8_dimensoes.md` | Framework conceitual de 8 dimensões, com evidências por estudo |
| `06_documentacao/RELATORIO_EXECUCAO_E_AUDITORIA_TCC2.md` | Relatório de execução e auditoria (15 tópicos) |
| `07_referencias/Referencias_TCC2.md` | Referências do TCC2 |

## Como consultar

- **Lista dos estudos analisados** (título, autores, ano, DOI, nota, situação, RQ1 a RQ4, dimensões): `03_dados/csv/01_estudos_58.csv` ou aba `1_Estudos_58`.
- **Notas Q1 a Q8 de cada estudo:** `02_qualidade_Q1Q8_53.csv` ou aba `2_Qualidade_Q1Q8` (a planilha calcula total, equivalente em 8 pontos, médias e medianas por fórmula).
- **Fluxo PRISMA:** `04_prisma/fig1_fluxo_prisma.png` e `03_fluxo_prisma.csv`.
- **Desvios entre protocolo e execução:** `04_desvios_protocolo.csv` (22 itens).
- **Framework e estudos que o sustentam:** `06_framework_rastreabilidade.csv`.
- **Pendências e alterações:** abas `8_Pendencias` e `9_Alteracoes`.

## Como conferir os resultados

1. Abra `03_dados/TCC2_Planilha_Auditoria.xlsx`. Nas abas `2_Qualidade_Q1Q8` e `3_Fluxo_PRISMA` as fórmulas estão ativas: altere uma nota e os totais recalculam.
2. A aba `4_Conferencias` (e `05_conferencias_recalculo.csv`) lista cada número do TCC2 com valor declarado, valor recalculado e resultado. Nada foi alterado para os números coincidirem.
3. As diferenças de identificação entre a leitura independente dos PDFs e a lista oficial estão em `07_crosswalk_fase1_oficial.csv`.

## Limites conhecidos

- Esta organização não substitui a conferência humana por amostragem das fichas contra os PDFs.
- As fichas F01 a F30, as versões intermediárias e os registros de decisão ficam no Projeto "TCC" do claude.ai, não neste repositório.
- Nenhum estudo brasileiro foi encontrado nos documentos, mas o país de 52 dos 58 estudos não foi replicado na planilha (relatório, seção 5).
- Não constam nos documentos: data da busca, número de duplicatas, pré-registro. Estão marcados como pendentes.

---

## Protocolo original

Protocolo de uma RST sobre aplicações de IA no Ensino Superior, que sintetiza estudos secundários publicados entre 2019 e 2026. Documento completo: [`protocolo_atualizado_TCC.pdf`](./protocolo_atualizado_TCC.pdf).

**Palavras-chave:** Inteligência Artificial · Ensino Superior · Revisão Sistemática Terciária · PRISMA 2020 · IA Generativa · Learning Analytics
