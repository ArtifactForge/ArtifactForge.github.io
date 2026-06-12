# Sites de Avaliação de Artefatos — Mapeamento de Eventos e Iniciativas

> Levantamento de **onde** a avaliação de artefatos (Artifact Evaluation / AE) acontece:
> conferências, simpósios, políticas e infraestrutura, no contexto internacional e brasileiro.
> Atualizado em 2026-06-05. Links coletados via busca; recomenda-se reconfirmar URLs de
> edições futuras (elas mudam de ano para ano).

---

## 1. Políticas e padrões transversais (definem o vocabulário da área)

| Iniciativa | O que é | Link |
|---|---|---|
| **ACM Artifact Review and Badging (v1.1, atual)** | Política e taxonomia oficial de selos da ACM: *Artifacts Available*, *Artifacts Evaluated – Functional/Reusable*, *Results Reproduced*, *Results Replicated*. Base terminológica de quase todas as conferências. | https://www.acm.org/publications/policies/artifact-review-and-badging-current |
| ACM Artifact Review and Badging (v1.0, histórica) | Versão anterior, ainda referenciada. | https://www.acm.org/publications/policies/artifact-review-badging |
| ACM Reviewers — curso de treinamento em badging | Material de formação de avaliadores de artefatos. | https://reviewers.acm.org/training-course/artifact-review-and-badging |
| **NISO / "Reproducibility Badging and Definitions"** | Padrão que harmoniza selos entre editoras. | (buscar via niso.org) |
| **csartifacts/resources (GitHub)** | Repositório comunitário com recursos, guias e histórico do processo de AE em CS. | https://github.com/csartifacts/resources |
| **artifact-eval.org** | Página histórica do movimento de AE (Krishnamurthi/Vitek et al.). | https://www.artifact-eval.org/ |
| **cTuning / cTuning Foundation AE (Grigori Fursin)** | Pioneiros em checklists reproduzíveis e crowdsourcing de avaliação. | https://cTuning.org/ae/ |

---

## 2. Hubs por comunidade (agregam várias conferências)

| Hub | Conferências cobertas | Link |
|---|---|---|
| **Systems Research Artifacts** | SOSP, OSDI, EuroSys, ASPLOS, ATC | https://sysartifacts.github.io/ (ex.: `/sosp2026/`) |
| **Security Research Artifacts** | USENIX Security, CCS, NDSS, S&P | https://secartifacts.github.io/ (ex.: `/usenixsec2025/`) |
| **conf.researchr.org (tracks "Artifact Evaluation")** | ICSE, FSE/ESEC, ASE, ISSTA, ECOOP, MODELS, PPoPP, ISSRE, MSR | https://conf.researchr.org/ (cada edição tem um track próprio) |
| **ACM SIGOPS — Artifact Evaluation** | Visão geral e diretrizes de sistemas operacionais. | https://www.sigops.org/2022/artifact-evaluation-present-and-future/ |

---

## 3. Conferências/eventos internacionais com AE consolidada

### Segurança
- **USENIX Security — Call for Artifacts** (política Open Science desde '25): https://www.usenix.org/conference/usenixsecurity26/call-for-artifacts
- **USENIX — Artifact Appendix Guidelines**: https://www.usenix.org/conference/usenixsecurity22/artifact-appendix-guidelines
- **ACM CCS — Call for Artifacts** (Artifact Evaluation Committee): https://www.sigsac.org/ccs/CCS2025/call-for-artifacts/
- NDSS, IEEE S&P (Oakland) — via secartifacts.github.io

### Sistemas / Redes / Paralelismo
- **EuroSys, SOSP, OSDI, ASPLOS, ATC** — via sysartifacts.github.io
- **PPoPP — Artifact Evaluation**: https://ppopp25.sigplan.org/track/PPoPP-2025-artifact-evaluation
- **SIGSIM-PADS — Reproducibility & Artifact Evaluation**: https://sigsim.acm.org/conf/pads/2026/blog/artifact-evaluation/
- SIGCOMM, CoNEXT — comitês de AE (referência citada pelo modelo brasileiro)

### Engenharia de Software / Linguagens / Modelagem
- **ICSE, FSE/ESEC, ASE, ISSTA** — tracks de AE em conf.researchr.org
- **ECOOP / ISSTA Artifacts**: https://conf.researchr.org/track/issta-2018/issta-2018-Artifacts
- **MODELS — Artifact Evaluation**: https://2025.models-conf.com/track/models-2025-artifact-evaluation
- **SIGPLAN** (POPL, PLDI, OOPSLA) — empenho histórico (Krishnamurthi/Vitek)

### Recuperação de Informação / IA / ML
- **ACM SIGIR — Artifact Badging**: https://sigir.org/general-information/acm-sigir-artifact-badging/
- **NeurIPS Reproducibility Program / ML Reproducibility Challenge**: https://reproducibility-challenge.github.io/ (e checklist de Pineau)

### Reprodutibilidade como evento próprio
- **ACM REP — Conference on Reproducibility and Replicability**: https://dl.acm.org/conference/rep (anais com "Lessons Learned ... at EuroSys")
- **Dagstuhl Seminars** sobre AE/reprodutibilidade (LIPIcs): https://drops.dagstuhl.de/

---

## 4. Brasil — SBC (Sociedade Brasileira de Computação)

### Infraestrutura e política nacional
| Item | Descrição | Link |
|---|---|---|
| **SBC OpenLib (SOL)** | Maior repositório de acesso aberto de Computação da América Latina; hospeda os anais. | https://sol.sbc.org.br/ |
| **SOL + Rede Brasileira de Reprodutibilidade** | Integração da SBC à RBR / avanço em ciência aberta. | https://www.sbc.org.br/sol-avanca-na-ciencia-aberta-e-integra-a-rede-brasileira-de-reprodutibilidade/ |
| **Horizontes (revista SBC)** | Artigo de divulgação "O Papel dos Artefatos na Reprodutibilidade..." (SBRC). | https://horizontes.sbc.org.br/index.php/2024/12/o-papel-dos-artefatos-na-reprodutibilidade-de-experimentos-um-estudo-do-sbrc/ |
| **HotCRP do CTA (C3SL/UFPR)** | Sistema de submissão dos Comitês Técnicos de Artefatos. | https://hotcrp.c3sl.ufpr.br/ |
| **AI Horizon Labs** | Principal grupo articulador do modelo brasileiro de selos (concepção, curadoria e desenvolvimento). | https://ai-horizon-labs.github.io |
| **LEA — Lab. de Estudos Avançados (UNIPAMPA)** | Grupo articulador do modelo brasileiro de selos. | https://sites.unipampa.edu.br/lea/ |

### Modelo brasileiro de selos (4 dimensões)
Disponível · Funcional · Sustentável · Reprodutível — espelhando SIGCOMM/USENIX/CoNEXT/EuroSys.
Articulado por UNIPAMPA + Tiago Heinrich (Max Planck Institute for Informatics).

### Eventos brasileiros com avaliação de artefatos
| Evento | Trilha/processo | Link |
|---|---|---|
| **SBSeg** (Simp. Bras. de Cibersegurança) — pioneiro (selo desde 2023) | Comitê Técnico de Artefatos; Salão de Ferramentas | https://www.sbseg2026.uff.br/chamadas/sf/ |
| SBSeg — documentação de avaliação de artefatos | Guia público do processo | https://doc-artefatos.github.io/sbseg2024/ |
| **SBRC** (Redes e Sistemas Distribuídos) — selos na Trilha Principal desde 2025 | Salão de Ferramentas + CTA; SeloR (reprodutível) | https://sbrc.sbc.org.br/2026/salao-de-ferramentas/ |
| **SBES / CBSoft** (Engenharia de Software) | Política de Ciência Aberta; seção "Disponibilidade de Artefatos" | https://cbsoft.sbc.org.br/2026/pt/symposiums/sbes/call/ |
| SBES — Política de Ciência Aberta (PDF, PT) | Adaptada das políticas de Open Science do ICSE | https://cbsoft.sbc.org.br/2025/docs/open-science_PT.pdf |
| **SBSI** (Sistemas de Informação) — Trilha de Pesquisa | Ciência aberta / artefatos | https://sbsi.sbc.org.br/2026/chamada-pesquisa.php |
| **SBSC** (Sistemas Colaborativos) | Trilha principal com incentivo a artefatos | https://sbsc.sbc.org.br/2026/index.php/trilha-principal/ |

> Outros simpósios SBC em adoção progressiva: SBBD, WSCAD, SBLP, SBCAS, SBGames — verificar editais por ano.

---

## 5. Notas de manutenção
- URLs de "call for artifacts" são **versionados por ano** — troque o ano no caminho para a edição corrente.
- Para AE de sistemas e segurança, prefira os hubs `sysartifacts.github.io` e `secartifacts.github.io`, que centralizam links históricos.
- O vocabulário de selos varia: confira sempre o mapeamento para a taxonomia ACM (Seção 1).
