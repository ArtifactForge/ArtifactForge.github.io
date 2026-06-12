# SoK — Avaliação de Artefatos (Artifact Evaluation): Mapeamento do Estado da Arte

> **Objetivo.** Mapear o que existe hoje sobre **avaliação de artefatos** em conferências,
> simpósios e outros contextos — internacionais e no Brasil. Este repositório reúne o
> *corpus* de papers (PDFs baixados, nomeados pelo título), agrupados por similaridade
> temática, mais um levantamento de eventos/iniciativas em
> [`sites_avaliacao_artefatos.md`](./sites_avaliacao_artefatos.md).

- **Data do levantamento:** 2026-06-05
- **PDFs baixados:** 18 papers + 1 documento de política (19 arquivos)
- **Bases consultadas:** Google Scholar, arXiv, ACM DL, IEEE, SpringerLink, USENIX,
  Semantic Scholar, Dagstuhl (LIPIcs), SBC OpenLib (SOL), páginas de autores.
- **Critério de download:** priorizamos versões **abertas** (arXiv, preprints
  institucionais, SOL/SBC, páginas de autor). Papers relevantes em *paywall* estão
  listados na Seção "Relevantes não baixados" com seus links.

---

## Como o corpus está organizado

```
papers/
├── 01_processo_estudos_empiricos/      # Como o AE funciona e estudos empíricos sobre ele
├── 02_IA_LLM_na_avaliacao/             # IA/LLMs e agentes APLICADOS à avaliação de artefatos
├── 03_reprodutibilidade_badges_incentivos/  # Selos, checklists, incentivos, reprodutibilidade
├── 04_areas_especificas/               # AE por domínio (sistemas, segurança, análise de código)
├── 05_brasil_ciencia_aberta/           # Contexto brasileiro (SBC/SOL) + políticas
└── 06_retrospectivas_historico/        # Fundamentos e medições históricas
```

---

## Grupo 01 — Processo de AE e estudos empíricos
*Como a avaliação de artefatos funciona e o que a evidência empírica diz sobre ela.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Community_Expectations_for_Research_Artifacts_and_Evaluation_Processes.pdf` | Hermann, Winter, Siegmund — ESEC/FSE 2020 | Survey com membros de AECs sobre o que a comunidade espera de artefatos e do processo. |
| `Understanding_and_Improving_Artifact_Sharing_in_Software_Engineering_Research.pdf` | Timperley, Herckis, Le Goues, Hilton — EMSE 2021 (arXiv 2008.01046) | Estudo misto (ASE/EMSE/FSE/ICSE 2014–18 + survey de 153 autores): desencontro de expectativas entre criadores, usuários e revisores. |
| `Research_Artifacts_in_Software_Engineering_Publications_Status_and_Trends.pdf` | (JSS 2024, arXiv 2404.06852) | Mostra a razão de papers top-tier com artefatos subindo de 60,1% (2017) para 81,1% (2022). |
| `The_State_of_Open_Science_in_Software_Engineering_Research_A_Case_Study_of_ICSE_Artifacts.pdf` | (arXiv 2601.02066, 2026) | Estudo de caso de ciência aberta sobre os artefatos do ICSE. |

## Grupo 02 — IA / LLMs na avaliação de artefatos
*Cluster recente (2025–2026): usar agentes e LLMs para **automatizar** o AE — exatamente o tema que você destacou.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Supporting_Artifact_Evaluation_with_LLMs_A_Study_with_Published_Security_Research_Papers.pdf` | arXiv 2603.06862 (2026) | Toolkit LLM: rating de reprodutibilidade por texto, preparo autônomo de sandbox (28% dos artefatos), >72% de acurácia. |
| `Artisan_Agentic_Artifact_Evaluation.pdf` | arXiv 2602.10046 (2026) | Agente LLM que reproduz resultados dado paper+artefato; introduz o *Artisan-Bench*. |
| `Agent-Based_Software_Artifact_Evaluation.pdf` | arXiv 2602.02235 (2026) | Avaliação de artefatos de software baseada em agentes. |
| `An_Agentic_Approach_Towards_Replication_Package_Quality_Evaluation.pdf` | arXiv 2606.02006 (2026) | Avaliação end-to-end automatizada de conteúdo e alinhamento estrutural de pacotes de replicação. |
| `R-LAM_Reproducibility-Constrained_Large_Action_Models_for_Scientific_Workflow_Automation.pdf` | arXiv 2601.09749 (2026) | "Large Action Models" com restrição de reprodutibilidade para automação de workflows científicos. |

## Grupo 03 — Reprodutibilidade, selos e incentivos
*Padrões de selo, checklists e a economia de incentivos da reprodutibilidade.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Improving_Reproducibility_in_Machine_Learning_Research_NeurIPS_2019_Reproducibility_Program.pdf` | Pineau et al. — JMLR 22 (arXiv 2003.12206) | Relato do programa de reprodutibilidade do NeurIPS 2019 + o ML Reproducibility Checklist. |
| `Reproducibility_as_a_Technical_Specification.pdf` | Crick et al. (arXiv 1504.01310) | Propõe tratar reprodutibilidade como especificação técnica formal. |
| `Large_Language_Models_for_Software_Engineering_A_Reproducibility_Crisis.pdf` | arXiv 2512.00651 (2025) | Diagnostica a crise de reprodutibilidade na pesquisa de LLMs para SE. |

## Grupo 04 — Avaliação de artefatos por área específica
*Práticas de AE conforme o domínio: sistemas distribuídos, segurança, análise de código em larga escala.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Artifact_Evaluation_for_Distributed_Systems_Current_Practices_and_Beyond.pdf` | arXiv 2406.13045 (2024) | Práticas atuais de AE em sistemas distribuídos e direções futuras. |
| `A_Reproducibility_Study_of_Machine_Learning_Papers_in_Tier_1_Security_Conferences.pdf` | Olszewski et al. — ACM CCS 2023 | Reprodutibilidade de papers de ML nas top conferências de segurança. |
| `The_Fault_in_Our_Stars_Designing_Reproducible_Large-scale_Code_Analysis_Experiments.pdf` | Maj, Muroya, Siek, Di Grazia, Vitek — ECOOP 2024 | Metodologia para amostragem reproduzível em estudos de mineração de repositórios. |

## Grupo 05 — Brasil: ciência aberta e selos da SBC
*O caminho brasileiro: 4 selos (Disponível/Funcional/Sustentável/Reprodutível) via Comitês Técnicos de Artefatos (CTA), articulado por UNIPAMPA + Tiago Heinrich.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Permitindo_Maior_Reprodutibilidade_de_Experimentos_em_Ambientes_Distribuidos_com_Nodos_de_Baixa_Confiabilidade.pdf` | Antunes Jr., Cordeiro, Gaspary (UFRGS) — SBRC | Mecanismo para aumentar reprodutibilidade de experimentos em ambientes distribuídos. |
| `_politicas_referencia/SBES_2025_Politica_de_Ciencia_Aberta_PT.pdf` | SBES/CBSoft 2025 | Política de Ciência Aberta do SBES (adaptada do ICSE) — **documento de referência, não paper**. |

**Leitura-chave brasileira (HTML, não-PDF):** *"O Papel dos Artefatos na Reprodutibilidade de
Experimentos: Um Estudo do SBRC"*, Thales G. C. de Lima & Vinícius Fulber-Garcia (UFPR),
Horizontes/SBC, dez/2024 — mostra a disponibilização de artefatos no SBRC subindo de **12,3%
(2014) para 45,8% (2024)**.
<https://horizontes.sbc.org.br/index.php/2024/12/o-papel-dos-artefatos-na-reprodutibilidade-de-experimentos-um-estudo-do-sbrc/>

## Grupo 06 — Retrospectivas e fundamentos históricos
*As raízes do movimento de AE e as primeiras medições quantitativas.*

| Arquivo (PDF) | Autores / Ano / Venue | Em uma linha |
|---|---|---|
| `Measuring_Reproducibility_in_Computer_Systems_Research.pdf` | Collberg, Proebsting et al. (Univ. Arizona TR, 2014) | Mediu a (in)disponibilidade de código/dados em pesquisa de sistemas; propôs esquema de especificação de reprodutibilidade. |
| `Community-Driven_Reviewing_and_Validation_of_Publications.pdf` | Fursin & Dubach (arXiv 1406.4020) | Crowdsourcing da avaliação de artefatos e revisão de publicações — precursor do AE moderno. |

---

## Relevantes, porém não baixados (paywall / só-HTML)
Mantidos aqui para completar o mapa; PDFs livres não foram localizados.

| Referência | Por que importa | Link |
|---|---|---|
| Krishnamurthi & Vitek, *The Real Software Crisis: Repeatability as a Core Value*, CACM 58(3), 2015 | Manifesto seminal do AE; experiência em 5 AECs. | https://dl.acm.org/doi/10.1145/2658987 |
| Collberg & Proebsting, *Repeatability in Computer Systems Research*, CACM 59(3), 2016 | Versão publicada do estudo de Arizona (o TR aberto está no Grupo 06). | https://dl.acm.org/doi/10.1145/2812803 |
| *Lessons Learned from Five Years of Artifact Evaluations at EuroSys*, ACM REP 2025 | Retrospectiva quantitativa (~50% reproduzíveis; ~20% indisponíveis após 4 anos). | https://dl.acm.org/doi/10.1145/3736731.3746152 |
| *Research artifacts and citations in computer systems papers*, PMC9044204 | Artefatos compartilhados ≈ +34% citações. | https://www.ncbi.nlm.nih.gov/pmc/articles/PMC9044204/ |
| *The Automated LLM Speedrunning Benchmark*, arXiv 2506.22419 | Adjacente: capacidade de agentes de reproduzir resultados (não AE em si). | https://arxiv.org/abs/2506.22419 |

---

## Síntese do que o mapa mostra
1. **AE virou norma** em top-tier de SE/sistemas/segurança (60%→81% de papers com artefato, 2017–2022).
2. **Frente quente (2026):** automatizar o AE com **agentes/LLMs** — grupo inteiro de papers muito recentes (Grupo 02).
3. **Vocabulário convergiu** na taxonomia de selos da ACM, mas a *implementação* varia por comunidade (hubs de sistemas e segurança).
4. **Brasil** adota modelo próprio de 4 selos via CTAs (SBSeg 2023 → SBRC 2025 → expansão), com forte protagonismo de UNIPAMPA/UFPR/UFRGS.
5. **Lacunas conhecidas:** ~20% dos artefatos somem em 4 anos; falta de incentivo para criadores e revisores; reprodutibilidade não se aplica bem a estudos qualitativos.

## Próximos passos sugeridos
- Buscar acesso institucional (IEEE/ACM/Springer) para os itens em paywall acima.
- Ampliar o Grupo 05 com mais papers brasileiros do SOL (SBSeg, SBRC, SBES) descrevendo os CTAs.
- Converter o artigo da Horizontes (HTML) em PDF de referência, se desejado.
- Considerar extração de metadados (BibTeX) para gerar uma planilha/biblioteca Zotero.
