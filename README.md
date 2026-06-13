# ArtifactForge

> **Onde a ciência vira artefato reprodutível.**
> Um panorama da Avaliação de Artefatos (*Artifact Evaluation* / AE) e dos selos de
> reprodutibilidade no Brasil e no mundo — com destaque para a experiência brasileira,
> que forjou um modelo próprio e levou inovações ao campo global de artefatos.

🔗 **Site:** [artifactforge.github.io](https://artifactforge.github.io/) · site estático bilíngue (PT-BR / EN)

---

## O que é

ArtifactForge é uma página única (`index.html`) que mapeia, de forma curada, **eventos,
políticas e infraestrutura** de avaliação de artefatos e reprodutibilidade. Serve como
ponto de partida para autores, avaliadores e organizadores de trilhas de artefatos.

O conteúdo está organizado em quatro grandes blocos:

| Seção | Âncora | Conteúdo |
|-------|--------|----------|
| **Brasil** | `#brasil` | A experiência da SBC, o modelo de 4 selos, eventos e infraestrutura nacional |
| **Mundo** | `#mundo` | Conferências internacionais com AE, organizadas por área |
| **Padrões** | `#politicas` | A taxonomia oficial da ACM e documentos de referência |
| **Recursos** | `#recursos` | Links de destaque e navegação (footer) |

---

## A experiência brasileira (em destaque)

A comunidade da **SBC**, articulada pela **UNIPAMPA e parceiros**, construiu um processo
público e transparente de avaliação de artefatos com um **modelo próprio de quatro selos**.
A prática foi sistematizada em documentação aberta e em um artigo acadêmico.

- 📘 **Documentação viva:** [doc-artefatos.github.io](https://doc-artefatos.github.io/) — critérios, fluxo de submissão, papel dos Comitês Técnicos de Artefatos (CTA) e significado de cada selo.
- 📄 **Paper resultante (ACM DL):** [doi.org/10.1145/3806097.3806100](https://dl.acm.org/doi/abs/10.1145/3806097.3806100) — traz inovações ao campo, incluindo a **sustentabilidade** dos artefatos como dimensão própria de avaliação.

### O modelo brasileiro de selos

Espelha práticas de SIGCOMM, USENIX, CoNEXT e EuroSys e é mapeável à taxonomia da ACM,
com o diferencial de tratar a **sustentabilidade** como eixo explícito.

| Selo | Significado |
|------|-------------|
| 🔵 **Disponível** | Artefato depositado de forma pública e persistente, com identificador estável. |
| 🟢 **Funcional** | Pode ser instalado e executado; faz o que o paper descreve. |
| 🟠 **Sustentável** | Documentação, licença e estrutura que permitem manutenção e reuso ao longo do tempo. |
| 🟣 **Reprodutível** | Os resultados centrais do paper podem ser reproduzidos a partir do artefato. |

### Eventos da SBC com avaliação de artefatos

- **SBSeg** — Cibersegurança. **Pioneiro:** selo desde 2023.
- **SBRC** — Redes e Sistemas Distribuídos. Selos na Trilha Principal desde 2025 (SeloR).
- **SBES / CBSoft** — Engenharia de Software. Política de Ciência Aberta.
- **SBSI** — Sistemas de Informação.
- **SBSC** — Sistemas Colaborativos.
- *Em adoção progressiva:* SBBD, WSCAD, SBLP, SBCAS, SBGames.

### Infraestrutura e política nacional

- **SBC OpenLib (SOL)** — maior repositório de acesso aberto de Computação da América Latina; integra a Rede Brasileira de Reprodutibilidade.
- **HotCRP do CTA · C3SL/UFPR** — sistema de submissão e gestão dos Comitês Técnicos de Artefatos.
- **AI Horizon Labs** e **LEA · UNIPAMPA** — grupos articuladores do modelo brasileiro de selos.

---

## Panorama mundial

Dezenas de conferências conduzem *Artifact Evaluation* e atribuem selos de
reprodutibilidade. O site as organiza por área, começando pelos **hubs por comunidade**:

- **Hubs** — [sysartifacts.github.io](https://sysartifacts.github.io/), [secartifacts.github.io](https://secartifacts.github.io/), [conf.researchr.org](https://conf.researchr.org/)
- **Segurança** — USENIX Security, ACM CCS, NDSS, ACSAC, CHES, PoPETs
- **Sistemas & Redes** — OSDI/NSDI/FAST, EuroSys/SOSP/ATC/ASPLOS, SIGCOMM/CoNEXT, PPoPP, SC
- **Linguagens** — POPL, PLDI, OOPSLA/SPLASH, CGO
- **Eng. de Software** — ICSE, FSE/ASE/ISSTA/MSR/MODELS
- **Bancos de Dados** — SIGMOD, PVLDB/VLDB
- **IA / ML** — NeurIPS, ML Reproducibility Challenge, ACM Multimedia, SIGIR
- **Reprodutibilidade** — ACM REP, Dagstuhl, ECRTS

---

## A taxonomia da ACM

Os nomes dos selos variam entre comunidades, mas convergem para a taxonomia oficial da
[ACM Artifact Review and Badging (v1.1)](https://www.acm.org/publications/policies/artifact-review-and-badging-current):

1. **Artifacts Available** — depositados de forma pública e persistente.
2. **Evaluated · Functional** — documentados, consistentes, completos e executáveis.
3. **Evaluated · Reusable** — acima de funcional: facilitam reuso e repropósito.
4. **Results Reproduced** — resultados obtidos de novo com os artefatos dos autores.
5. **Results Replicated** — resultados obtidos de forma independente, sem os artefatos.

---

## Estrutura do repositório

```
.
├── index.html                  # O site completo (HTML + CSS + JS embutidos)
├── sites_artefatos_brazil.md   # Notas de curadoria — eventos/infra do Brasil
├── sites_artefatos_mundo.md    # Notas de curadoria — conferências do mundo
└── LICENSE
```

### Detalhes técnicos

- **Página única, sem build.** Todo o CSS e o JavaScript estão embutidos no `index.html`. Basta abrir o arquivo no navegador ou publicar via GitHub Pages.
- **Bilíngue (PT-BR / EN).** Um *toggle* de idioma alterna o conteúdo via atributos `data-pt` / `data-en`; a escolha é persistida em `localStorage`.
- **Animações de scroll** via `IntersectionObserver`, com *fallback* gracioso.
- **Tipografia:** Fraunces (títulos), IBM Plex Sans (texto) e IBM Plex Mono (código), servidas pelo Google Fonts.

---

## Marcos

| | |
|---|---|
| **2023** | SBSeg · selo pioneiro |
| **4** | selos brasileiros |
| **45,8%** | artefatos disponíveis no SBRC (2024), ante 12,3% em 2014 |

---

## Licença & créditos

© 2026 [AI Horizon Labs](https://ai-horizon-labs.github.io). Concepção, desenvolvimento e
curadoria por AI Horizon Labs. Consulte o arquivo [LICENSE](LICENSE) para os termos de uso.

> As URLs de *"call for artifacts"* são versionadas por ano; troque o ano no caminho para
> chegar à edição corrente. Levantamento atualizado em jun. 2026.
