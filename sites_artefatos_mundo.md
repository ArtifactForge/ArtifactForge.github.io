# Sites de Avaliação de Artefatos — Panorama Internacional

> Levantamento de **conferências, simpósios e iniciativas internacionais** que conduzem
> *Artifact Evaluation* (AE) / avaliação de artefatos e atribuição de selos de
> reprodutibilidade. Complementa `sites_artefatos_brazil.md` (foco SBC/Brasil).
> Atualizado em 2026-06-12. URLs de "call for artifacts" são **versionados por ano** —
> troque o ano no caminho (ex.: `usenixsecurity26` → `usenixsecurity27`) para a edição corrente.

---

## 1. Políticas, padrões e vocabulário transversal

Definem a taxonomia de selos usada por quase todas as conferências abaixo.

| Iniciativa | O que é | Link |
|---|---|---|
| **ACM — Artifact Review and Badging (v1.1, atual)** | Política e taxonomia oficial: *Artifacts Available*, *Artifacts Evaluated – Functional/Reusable*, *Results Reproduced*, *Results Replicated*. Base terminológica do campo. | https://www.acm.org/publications/policies/artifact-review-and-badging-current |
| **ACM EIG on Reproducibility & Replicability** | Emerging Interest Group da ACM que coordena o esforço editorial e a conferência ACM REP. | https://reproducibility.acm.org/ |
| **ACM Reviewers — curso de badging** | Treinamento oficial de avaliadores. | https://reviewers.acm.org/training-course/artifact-review-and-badging |
| **artifact-eval.org** | Página histórica do movimento de AE (Krishnamurthi, Vitek et al.). | https://www.artifact-eval.org/ |
| **SIGPLAN — Empirical Evaluation Guidelines** | Diretrizes de avaliação empírica/reprodutibilidade referência em PL. | https://www.sigplan.org/Resources/EmpiricalEvaluation/ |
| **csartifacts/resources (GitHub)** | Recursos, guias e histórico comunitário do processo de AE em CS. | https://github.com/csartifacts/resources |

---

## 2. Hubs por comunidade (agregam várias conferências num só site)

A forma mais eficiente de localizar AE: estes hubs centralizam links históricos e por edição.

| Hub | Conferências cobertas | Link |
|---|---|---|
| **Systems Research Artifacts** | EuroSys, SOSP, OSDI, USENIX ATC, ASPLOS | https://sysartifacts.github.io/ (ex.: `/sosp2025/`) |
| **Security Research Artifacts** | USENIX Security, NDSS, ACSAC, CHES, PETS, IEEE S&P | https://secartifacts.github.io/ (ex.: `/usenixsec2026/`) |
| **conf.researchr.org** (tracks *Artifact Evaluation*) | ICSE, FSE/ESEC, ASE, ISSTA, ECOOP, MODELS, MSR, ISSRE | https://conf.researchr.org/ (cada edição com track próprio) |
| **researchartifacts.github.io** (vahldiek) | Código-base genérico reutilizado pelos hubs sys/sec | https://github.com/vahldiek/researchartifacts.github.io |

---

## 3. Segurança e Privacidade

| Evento | Trilha / processo | Link |
|---|---|---|
| **USENIX Security** — AE em 2 fases (disponibilidade + funcional/reprodutível) | Call for Artifacts | https://www.usenix.org/conference/usenixsecurity26/call-for-artifacts |
| USENIX Security — instruções de submissão | via hub | https://secartifacts.github.io/usenixsec2026/instructions |
| USENIX Security — Artifact Appendix Guidelines | modelo de apêndice | https://www.usenix.org/conference/usenixsecurity22/artifact-appendix-guidelines |
| **ACM CCS** — Artifact Evaluation Committee | Call / HotCRP | https://www.sigsac.org/ccs/CCS2026/call-for-artifacts/ · https://ccs2026a-artifacts.hotcrp.com/ |
| **NDSS** — AE desde 2024 | via hub | https://secartifacts.github.io/ndss |
| **IEEE S&P (Oakland)** | via hub | https://secartifacts.github.io/ |
| **ACSAC** — AE consolidada com guia de revisor | Paper Artifacts | https://www.acsac.org/2024/program/artifacts/ |
| **CHES (IACR)** — selos *Available* e *Functional* | Artifact Evaluation | https://ches.iacr.org/2026/artifacts.php |
| **PoPETs / PETS** (Privacy Enhancing Technologies) | Artifact Evaluation | https://petsymposium.org/artifacts.php |
| **WOOT** (Offensive Technologies, USENIX) | Call for Artifacts | https://www.usenix.org/conference/woot26/call-for-artifacts |
| **VehicleSec** (USENIX) | Call for Artifacts | https://www.usenix.org/conference/vehiclesec26/call-for-artifacts |

---

## 4. Sistemas, Redes, Armazenamento e HPC

| Evento | Trilha / processo | Link |
|---|---|---|
| **OSDI** | Call for Artifacts (USENIX) | https://www.usenix.org/conference/osdi26/call-for-artifacts |
| **NSDI** | Call for Artifacts (USENIX) | https://www.usenix.org/conference/nsdi26/call-for-artifacts |
| **FAST** (File and Storage Technologies) | Call for Artifacts (USENIX) | https://www.usenix.org/conference/fast26/call-for-artifacts |
| **EuroSys · SOSP · USENIX ATC · ASPLOS** | via hub Systems | https://sysartifacts.github.io/ |
| **SIGCOMM / CoNEXT / IMC** — Artifacts Evaluation Committee (selos ACM desde 2018) | comitê de AE de redes | https://www.sigcomm.org/ |
| **PPoPP** (Paralelismo) — Artifact Evaluation | track SIGPLAN | https://ppopp25.sigplan.org/track/PPoPP-2025-artifact-evaluation |
| **SC — Supercomputing** — Reproducibility Initiative (AD/AE + AE Reports) | iniciativa de reprodutibilidade | https://sc26.supercomputing.org/program/papers/reproducibility-initiative/ |
| SC — guia de reprodutibilidade da série | documentação Collegeville | https://collegeville.github.io/sc-reproducibility/ |

---

## 5. Linguagens de Programação e Compiladores

| Evento | Trilha / processo | Link |
|---|---|---|
| **POPL** — AE desde 2015 | Artifact Evaluation | https://popl26.sigplan.org/track/POPL-2026-artifact-evaluation |
| **PLDI** — declaração de intenção de artefato na submissão (novo em 2026) | PLDI Research Artifacts | https://pldi26.sigplan.org/track/pldi-2026-pldi-research-artifacts |
| **OOPSLA / SPLASH** | Artifact Evaluation | https://2026.splashcon.org/track/oopsla-2026 |
| **CGO** (Code Generation and Optimization) | Artifact Evaluation | https://2026.cgo.org/track/cgo-2026-artifact-evaluation |
| **ECOOP** | via conf.researchr.org | https://conf.researchr.org/ |

---

## 6. Engenharia de Software e Modelagem

| Evento | Trilha / processo | Link |
|---|---|---|
| **ICSE** — selos *Available* e *Reusable* | Artifact Evaluation | https://conf.researchr.org/track/icse-2026/icse-2026-artifact-evaluation |
| **FSE/ESEC · ASE · ISSTA · MSR · MODELS** | tracks de AE em conf.researchr.org | https://conf.researchr.org/ |
| **ISSTA** — Artifacts | exemplo de track histórico | https://conf.researchr.org/track/issta-2018/issta-2018-Artifacts |

---

## 7. Sistemas de Tempo Real / Embarcados

| Evento | Trilha / processo | Link |
|---|---|---|
| **ECRTS** (European Conf. on Real-Time Systems) | Artifact Evaluation | https://www.ecrts.org/artifact-evaluation/ |

---

## 8. Bancos de Dados

| Evento | Trilha / processo | Link |
|---|---|---|
| **ACM SIGMOD** — Availability & Reproducibility Initiative (selos *Reproducibility* e *Artifacts Available*) | reprodutibilidade SIGMOD | https://reproducibility.sigmod.org/ |
| **PVLDB / VLDB** — Reproducibility (em coordenação com SIGMOD) | reprodutibilidade VLDB | https://vldb.org/ |

---

## 9. Inteligência Artificial / Aprendizado de Máquina

| Evento | Trilha / processo | Link |
|---|---|---|
| **NeurIPS** — Paper Checklist obrigatório (reprodutibilidade/ética); desk-reject sem checklist | Main Track Handbook | https://neurips.cc/Conferences/2026/MainTrackHandbook |
| **ML Reproducibility Challenge** | desafio comunitário de reprodução | https://reproducibility-challenge.github.io/ |
| **ACM Multimedia** — Call for Reproducibility Papers | trilha de reprodutibilidade | https://2026.acmmm.org/site/call-reproducibility.html |
| **ACM SIGIR** — Artifact Badging (recuperação de informação) | política de selos | https://sigir.org/general-information/acm-sigir-artifact-badging/ |

---

## 10. Reprodutibilidade como evento próprio

| Evento | O que é | Link |
|---|---|---|
| **ACM REP** — Conf. on Reproducibility and Replicability | Conferência dedicada; edição 2026 em Delft (TU Delft), 20–22 jul. | https://acm-rep.github.io/2026/ |
| ACM REP — série e anais | índice da série | https://acm-rep.github.io/ |
| **Dagstuhl Seminars** sobre AE/reprodutibilidade | seminários e LIPIcs | https://drops.dagstuhl.de/ |

---

## 11. Notas de manutenção

- **Comece pelos hubs** (Seção 2): `sysartifacts.github.io` e `secartifacts.github.io` centralizam links históricos e poupam buscas por edição.
- **URLs versionados por ano**: troque o ano no caminho para a edição corrente (ex.: `osdi26` → `osdi27`; `/icse-2026/` → `/icse-2027/`).
- **Mapeie sempre à taxonomia ACM** (Seção 1): o nome dos selos varia entre comunidades, mas converge para *Available / Functional / Reusable / Reproduced / Replicated*.
- Para o contexto brasileiro (SBSeg, SBRC, SBES, CTA, modelo de 4 selos), ver `sites_artefatos_brazil.md`.
