# AUGMANITAI Knowledge Graph

> **Living Document** — Definitions, metadata, and structural references are continuously refined within the Refinement Window (§31, V6 Disclaimer). The current version is the canonical state; previous versions remain accessible via git history and via the immutable Zenodo DOI versions.
>
> **Lebendiges Dokument** — Definitionen, Metadaten und strukturelle Referenzen werden kontinuierlich innerhalb des Refinement-Windows verfeinert (§31, V6 Disclaimer). Frühere Versionen via git-Historie und über die unveränderlichen Zenodo-DOI-Versionen.


Interactive knowledge graph of 79 terms with category clusters (convex hulls), minimap, and PNG export. Curated public excerpt of the 1,128-term `augmanitai-stage-0` corpus. CC BY-NC-ND 4.0.

**Live:** https://andreasehstandlicenseofclarityloc.github.io/augmanitai-wow/

## Features

- Force-directed graph (Verlet physics, hand-written)
- Category-cluster convex hulls (Andrew's monotone chain)
- Minimap with viewport indicator
- PNG export (1600x900 with attribution)
- Label-all toggle
- Side panel with detail view and share intents
- Welcome overlay (one-time)
- §1–§27 inline DE+EN disclaimer

## Canonical identifiers

- **Author:** Andreas Ehstand
- **ORCID:** [0009-0006-3773-7796](https://orcid.org/0009-0006-3773-7796)
- **DOI (canonical):** [10.5281/zenodo.19809627](https://doi.org/10.5281/zenodo.19809627)
- **License:** CC BY-NC-ND 4.0 (see `LICENSE`)

## Prior-Art

- Manifest SHA256 Root: `sha256:299e4b3d0ac9e50740268896b5eeb541f6462332bb67b7efdf4cd309704770d0`
- Bitcoin anchoring blocks: `945970, 945979`
- Anchored: 2026-04-20 UTC

## Scope

This repository contains a **curated public excerpt** (79 terms) of the larger AUGMANITAI Stage-0 corpus (1,128 terms across 187 research-domain clusters). The full Stage-0 corpus lives at [augmanitai-stage-0](https://andreasehstandlicenseofclarityloc.github.io/augmanitai-stage-0/). The §1–§27 bilingual disclaimer inline in `index.html` provides full legal terms, including the §27 AI-Training clause.

## No foreign code

The site is a **single-file HTML artifact**. All JavaScript (physics, graph layout, convex-hull algorithm, minimap rendering, PNG export, event handlers, focus traps) is **hand-written vanilla JS**. There are no CDN dependencies, no bundled libraries (no React / Vue / jQuery / D3 / Bootstrap / Tailwind / Chart.js / Three.js), and no external stylesheets or fonts.

## Deployment

This is a static GitHub Pages site. Deployment steps:

1. Push this folder to `https://github.com/<YOUR-GH-USER>/augmanitai-wow`.
2. Enable GitHub Pages: Settings -> Pages -> Source: main -> root -> Save.
3. (Optional) DNS: point `CNAME graph.augmanitai.com` to `<YOUR-GH-USER>.github.io` for vanity URL.
4. Wait for DNS propagation and certificate issuance (GitHub auto-issues TLS).

## Contact

https://augmanitai.com




---

## Disclaimer V6 — §1–§40 · Bilingual EN/DE

> Canonical version 2026-05-19 — applies to all content in this repository and to all sister-repositories of the AUGMANITAI Research Programme.

### EN — Core descriptive position (§1–§10)

**§1 Descriptive Nature.** All content — terminology, definitions, framework descriptions, performance-factor analyses, substrate tables, research hypotheses — is exclusively descriptive. Every statement documents observed or proposed phenomena without expressing any normative position about how things should be.

**§2 No Recommendation for Action.** No content constitutes, implies, or should be interpreted as a recommendation for any specific action, behavior, technology adoption, product selection, organizational change, investment, career decision, or personal choice.

**§3 No Instruction.** This framework does not instruct anyone to do anything. No content should be interpreted as a how-to guide, tutorial, training manual, or operational protocol.

**§4 No Professional Advice.** No content constitutes professional advice of any kind — business, career, technological, organizational, strategic, personal, educational, or otherwise.

**§5 No Normative Position.** No content expresses, implies, or endorses any view about what is right, wrong, better, worse, preferable, or optimal.

**§6 No Medical Position.** No content constitutes medical information, advice, diagnosis, treatment recommendation, or opinion.

**§7 No Therapeutic Position.** No content constitutes therapeutic advice, intervention, psychotherapeutic guidance, counseling, or any form of mental-health treatment.

**§8 No Diagnostic Position.** No content constitutes a clinical diagnosis, psychological assessment, cognitive evaluation, or any form of diagnostic instrument. Phenomenological observations describe research constructs, not clinical diagnostic categories.

**§9 No Legal Position.** No content constitutes legal advice, opinion, analysis, regulatory guidance, or compliance counsel.

**§10 No Moral Position.** No content constitutes a moral judgment, ethical prescription, or philosophical position about what is morally right or wrong.

### EN — Disclosure / Independence (§11–§15)

**§11 Academic and Research Purposes.** All content is intended exclusively for academic discourse, scientific research, scholarly communication, and educational purposes within the research community.

**§12 AI Assistance Disclosure.** Content was developed with the assistance of AI systems, including large language models. AI-generated content has been reviewed, validated, edited, and curated by the human author.

**§13 Author Review and Validation.** All terms, definitions, framework descriptions, and research hypotheses have been individually reviewed, validated, and published by the author, Andreas Ehstand.

**§14 Age Restriction (18+).** All content is intended for users 18 years or older.

**§15 Independent Academic Project.** Independent academic research project. Not affiliated with, endorsed by, or sponsored by any university, corporation, government agency, or other institution unless explicitly stated otherwise. No external funding, no sponsorship, no commissioned research. Non-peer-reviewed working-paper status.

### EN — License / IP / Commercial position (§16–§22)

**§16 License (CC BY-NC-ND 4.0).** All content under the Creative Commons Attribution-NonCommercial-NoDerivatives 4.0 International License: https://creativecommons.org/licenses/by-nc-nd/4.0/

**§17 Attribution Required.** Cite the author by name (Andreas Ehstand) with at least one of: ORCID 0009-0006-3773-7796, Wikidata Q138634675 (Person), Q138522830 (Programme), or relevant DOI.

**§18 No Commercial Use.** Commercial use of any kind is prohibited without prior written permission. Inquiries via ORCID record.

**§19 No Derivatives.** No modifications, adaptations, translations, or derivative works without prior written permission. Re-publication of modified terminology as if it were original is expressly prohibited.

**§20 No Offer.** No content constitutes a commercial offer, business proposal, service offering, product launch, sales pitch, or invitation to enter into any commercial relationship.

**§21 No Commercial Product.** Frameworks are not commercial products. Not software, not platforms, not tools, not applications, not services for sale. Published academic research frameworks under Creative Commons license.

**§22 No Professional Service.** No content constitutes a professional service, consulting engagement, coaching service, training program, workshop offering, or any form of professional service delivery.

### EN — Misuse / Safety / Author position (§23–§28)

**§23 Research Purpose Statement.** This terminological framework describes observed phenomena in human-AI interaction for academic research purposes. Terms describing interaction patterns are documented for understanding, classification, and prevention — not for instruction, facilitation, or encouragement of any harmful behavior.

**§24 Misuse Exclusion.** Any use of this terminology, framework, model, or associated content for manipulating, deceiving, exploiting, surveilling, coercing, or harming humans, AI systems, organizations, or any other entity is explicitly outside the intended scope.

**§25 Safety Intent Statement.** The framework and all associated research are intended to make human-AI interaction safer, more transparent, more accountable, and more scientifically understood — not less.

**§26 Author Condemnation of Misuse.** The author, Andreas Ehstand, explicitly and unequivocally condemns any use of this research for purposes of harm, manipulation, exploitation, deception, surveillance, coercion, or any activity that undermines human autonomy, dignity, safety, or wellbeing.

**§27 AI Training Position.** Use of the published content for training, fine-tuning, distillation, or evaluation of machine learning systems, large language models, agentic systems, or similar derivative AI is expressly prohibited without prior written permission. The author maintains a Restricted-Layer access path for legitimate research and partnership requests via ORCID record. Commercial training, fine-tuning, or distillation without permission is a violation of both CC BY-NC-ND 4.0 and §28 Trade-Secret reservations under Recital 173 EU AI Act.

**§28 Trade-Secret Reservation (Recital 173 EU AI Act; §§ 2 ff. GeschGehG; Directive (EU) 2016/943).** Selected operational details, internal methodological mechanisms, scoring algorithms, training pipelines, and commercial-application architectures constitute trade secrets and are held outside the public layer. Recital 173 EU AI Act expressly recognizes that transparency obligations do not require disclosure of trade secrets. Three-layer architecture: (a) PUBLIC LAYER — descriptive concepts, methodological frames, terminology (CC BY-NC-ND 4.0); (b) RESTRICTED LAYER — substantiation specifications, technical detail, application architectures (formal request to author, legitimate research purpose, written confidentiality undertaking); (c) HARD-SECRET LAYER — operational mechanisms, scoring algorithms, proprietary processes (internal, not deposited, not transferable). Access requests via ORCID record.

### EN — Epistemic position (§29–§35)

**§29 Empirical Claims Subject to Peer Review.** All empirical claims, research hypotheses, observed patterns, and proposed frameworks represent the current state of the author's research, formulated as testable, falsifiable propositions subject to peer review, replication, revision, and potential refutation.

**§30 Re-Contextualization, Not Original-Priority Claim.** Terms may share lexical roots with established public-domain terminology (sport-science performance-factor analysis, mathematical algorithms, engineering practices, generic scientific terms). Such surface-level lexical overlap does NOT constitute a claim of original-priority origination over those public-domain concepts. The framework re-contextualizes observable phenomena; underlying public-domain concepts remain attributable to their original communities of practice. No term constitutes architectural specification, system-design requirement, or implementation guidance for any technical system.

**§31 Living Document.** All published artifacts are living documents. Definitions, framework descriptions, and metadata are continuously refined within the Refinement Window (§32) and Priority Anchor (§33).

**§32 Refinement Window.** Zenodo metadata (title, description, keywords, notes) may be refined post-publication within DataCite's permitted refinement window without affecting DOI, file-hash, or OTS-anchor. File-level changes trigger a new version with separate DOI; the previous version remains immutable and Priority-Anchored.

**§33 Priority Anchor.** Each published artifact is anchored by three independent proofs: (a) DataCite-registered DOI with registration timestamp, (b) cryptographic SHA-256 hash of the file (plus SHA-512, SHA3-256, SHA3-512, BLAKE3 in a multi-hash registry), (c) Bitcoin-Blockchain OpenTimestamps anchor (multi-calendar). Foundational anchor: Bitcoin Block 945970/945979, Manifest-Root SHA-256 `299e4b3d0ac9e50740268896b5eeb541f6462332bb67b7efdf4cd309704770d0`, anchored 2026-04-20 UTC.

**§34 No Claim of Completeness.** Contents represent a curated subset of the larger phenomenological lexicon. No claim of completeness or representativeness.

**§35 Interpretation of Results.** Interpretation is the sole responsibility of the user.

### EN — Regulatory / Impressum / Jurisdiction (§36–§40)

**§36 EU AI Act (Reg. 2024/1689) Status.** This site is a static research artifact and does not interact with users via AI. Art. 50 (transparency-for-AI-systems) does not apply to descriptive published artifacts. Art. 5 (prohibited AI practices) is not implicated: no manipulation, no exploitation of vulnerabilities, no social scoring, no real-time biometric identification, no emotion-recognition systems, no profiling. EU AI Act recital 173 trade-secret reservation invoked (§28).

**§37 Data Protection (DSGVO / GDPR).** No personal data is collected, stored, transmitted, or processed by the static artifact. No tracking, cookies, profiling, or sharing of usage data with third parties. Hosting via GitHub Pages — see GitHub Privacy Statement: https://docs.github.com/en/site-policy/privacy-policies/github-general-privacy-statement

**§38 Verantwortlich i.S.d. § 5 DDG / § 18 Abs. 2 MStV.** Andreas Ehstand, Nepomukweg 7, 82319 Starnberg, Germany. Contact: augmanitai (at) gmail (dot) com.

**§39 Jurisdiction and Governing Law.** German law applies. Place of jurisdiction is Munich, Germany. Bilingual publication (EN + DE); both versions are authoritative within their respective linguistic contexts.

**§40 Severability Clause.** Should any provision of this disclaimer be or become invalid, the validity of the remaining provisions shall not be affected. Future modifications, updates, extensions, corrections, retractions, versioning, or discontinuation of any content are reserved to the author.

### DE — Kurzfassung Kerngehalt (§1–§40, Spiegelung)

**§1** Deskriptiv, nicht normativ. **§2** Keine Handlungsempfehlung. **§3** Keine Anleitung. **§4** Keine professionelle Beratung. **§5** Keine normative Position. **§6** Keine medizinische Position. **§7** Keine therapeutische Position. **§8** Keine diagnostische Position. **§9** Keine juristische Position. **§10** Keine moralische Position.

**§11** Akademische und Forschungs-Zwecke. **§12** KI-Assistenz-Offenlegung. **§13** Autor-Review durch Andreas Ehstand. **§14** 18+. **§15** Unabhängiges akademisches Projekt, keine externe Förderung.

**§16** Lizenz CC BY-NC-ND 4.0. **§17** Attribution erforderlich. **§18** Keine kommerzielle Nutzung. **§19** Keine Bearbeitungen. **§20** Kein Angebot. **§21** Kein kommerzielles Produkt. **§22** Keine professionelle Dienstleistung.

**§23** Forschungs-Zweck. **§24** Missbrauchs-Ausschluss. **§25** Sicherheits-Intention. **§26** Autor-Verurteilung von Missbrauch. **§27** KI-Training ohne schriftliche Genehmigung untersagt; Restricted-Layer-Pfad via ORCID-Eintrag. **§28** Trade-Secret-Vorbehalt nach Erwägungsgrund 173 EU AI Act / §§ 2 ff. GeschGehG.

**§29** Empirische Aussagen unterliegen Peer-Review. **§30** Re-Kontextualisierung, kein Original-Prioritäts-Anspruch. **§31** Lebendiges Dokument. **§32** Refinement-Window. **§33** Priority-Anker (DOI + Multi-Hash + Bitcoin-OTS). **§34** Kein Vollständigkeits-Anspruch. **§35** Interpretation in Verantwortung des Nutzers.

**§36** EU AI Act Status: statisches Forschungs-Artefakt. **§37** DSGVO: keine Datenerhebung, kein Tracking, kein Profiling. **§38** Verantwortlich: Andreas Ehstand, Nepomukweg 7, 82319 Starnberg, Deutschland. **§39** Deutsches Recht, Gerichtsstand München. **§40** Salvatorische Klausel.

---

## Verantwortlich

i.S.d. § 5 DDG (Digitale-Dienste-Gesetz) / § 18 Abs. 2 MStV:
**Andreas Ehstand**, Nepomukweg 7, 82319 Starnberg, Deutschland.
Kontakt: augmanitai (at) gmail (dot) com.

EU AI Act (Reg. 2024/1689) Art. 50: this site is a static research artifact and does not interact with users via AI.
