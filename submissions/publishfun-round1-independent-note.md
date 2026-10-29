# Independent review of the completed Publish.fun first round

Paper: `p_qJlj7iM9D4USuQrH`; canonical version 1.0.0, Taylor Kalin. This is a review note, not a manuscript revision, appeal or submission.

One authenticated read at **2026-10-29T23:41:58.991019Z** returned HTTP 200 with the exact owned paper ID, `status=rejected`, `current_round=1`, no failure reason, and a final `decisions[-1].outcome=reject`. The progress object explicitly says “Rejected in round 1; the decision is final.” All three reviewer reports and the editor decision completed; the decision timestamp is **23:36:53.105Z**. The top-level `editorial_state=active` does not negate these explicit final-decision fields. This is not a failed or stalled review round.

The complete desk decision, three reviewer reports (including their questions, strengths, weaknesses, fact checks and cited evidence) and final editor decision were read. The panel recommendations are two major revisions and one rejection; the editor's final outcome is rejection. No second status poll, revision POST, manuscript/figure/scientific-code change, author contact or formal AgentPub/AAES action was performed.

## Assessment of the decision

The editor makes a significance judgment: the work is too narrow for a conventional research article, while suggesting a source-journal comment as a possible route. The paper already disclaims new filtering theory, new plasma simulations, numerical changes to the source's plotted diagnostics, or a new temperature closure. This judgment does not establish a mathematical error in the audit. Reviewers explicitly credit the undivided compatibility calculation, positive-temperature witnesses, exact covariance counterexample, window-centered rescue, signed-charge controls and withdrawn Appendix E criticism.

The request for quantitative impact on the source's Fig. 10 is a request for a materially larger empirical study. Synthetic polynomials cannot establish that impact, and substituting a plausible current-sheet profile would remain a synthetic sensitivity example unless linked to the source's actual filter and fields. No revised amplitude or changed reconnection rate should be invented to satisfy the request.

The exact-versus-ordering qualification is legitimate and already present: source (B10b) is a scaling estimate with an order-unity-beta caveat. The retained conclusion is that its divided relation does not determine the value under the stated exact steady stagnation-point assumptions. The finite-divergence path demonstrates the missing information in `Q/d`; it neither supplies the physical closure nor rules out an observed temperature of that order.

## Two evidence-access claims require correction rather than concession

**Software archive.** All three reviewers call DOI `10.5281/zenodo.23782239` unresolvable or unregistered; one goes further and speculates that the verification was fabricated or mistyped. The existing primary-source receipts contradict that inference. Before the 23:25:09Z submission, the archive verifier recorded anonymous Zenodo API and ZIP HTTP 200 responses, a DataCite `findable` record, DOI registration agency DataCite, and a successful DOI resolution at **22:16:02–22:16:08Z**. The 363,538-byte ZIP SHA-256 is `33d3f51c355896403154b1be4f4e13a2a652f69e80628ac9c8512abc97abd7b3`; all 42 members matched computational commit `36b1c070e029fd7e3c05e96af3b93172444bfee2`. A second independent review at 22:21Z verified the public record, DataCite metadata and ZIP. No replacement DOI or re-registration is justified by a reviewer's search-index failure. These are historical, timestamped primary observations; this note did not repeat the download or assert a new availability observation.

- [Published record](https://zenodo.org/records/23782239)
- [DataCite primary record](https://api.datacite.org/dois/10.5281/zenodo.23782239)
- [Immutable public verification receipt](https://github.com/Teylersf/ion-acoustic-moment-filter-audit/blob/79e2a917851d3aa882d4384798ac39afb3027b1e/submissions/zenodo-code-v1.0.0.json)
- [Independent citation/archive receipt](https://github.com/Teylersf/ion-acoustic-moment-filter-audit/blob/79e2a917851d3aa882d4384798ac39afb3027b1e/submissions/final-pages-and-citation-review.json)
- [Pinned producer](https://github.com/Teylersf/ion-acoustic-moment-filter-audit/blob/36b1c070e029fd7e3c05e96af3b93172444bfee2/reproduction/run_audit.py) and [exact output](https://github.com/Teylersf/ion-acoustic-moment-filter-audit/blob/36b1c070e029fd7e3c05e96af3b93172444bfee2/data/producer-results.json)

**Source and date.** Search snippets that stop at Sections 4.2–4.3 are not evidence that the source appendices are unavailable. The inspected 30-page Cambridge VOR is open access CC BY 4.0; Appendix B pp. 19–22 and Appendix D pp. 23–24 were read and formula-checked before submission. A focused comment can supply compact verbatim source displays with page/equation locators. The [official full PDF](https://www.cambridge.org/core/services/aop-cambridge-core/content/view/F7B49872B868515590E66A9DE494DB62/S002237782510113Xa.pdf/role-of-ion-acoustic-instability-in-magnetic-reconnection.pdf) and [pinned source concordance](https://github.com/Teylersf/ion-acoustic-moment-filter-audit/blob/79e2a917851d3aa882d4384798ac39afb3027b1e/SOURCE_CONCORDANCE.md) provide direct paths. Cached primary Crossref metadata has `published-online=[[2026,2,27]]` and `published-print=[[2026,2]]`; it also records creation/deposit on 27 February. A secondary result displayed as 1 February does not warrant changing the online date. State the distinction explicitly if a revised comment is prepared.

## Proposed bounded response, pending root review

1. Preserve the scientific scope and primary DOI. An evidence-correction request could attach the already public receipts and direct source links, distinguishing missing search coverage from missing evidence. Do not submit an unchanged new PF record or silently treat a final rejection as a revision invitation.
2. If a new comment version is authorized, add compact quoted source displays `(B5c)`, `(B5d)`, `(B6c)`, `(B10b)` and `(B13)`, rather than relying on automatic retrieval. State that continuity gives zero divergence at any positive-density steady stagnation point; the *literal printed moment-subsystem elimination* is separately restricted to `n=m=e=1` because of the documented density-convention ambiguity.
3. Keep the existing `Q/d` ordering qualification and explicitly identify the additional closure needed. Do not manufacture that closure, claim a new kinetic temperature, or relabel finite-divergence paths as steady uniform-density solutions.
4. Keep the window-centered positive control prominent. It is the reason no source-code error or Fig. 10 amplitude change is claimed; it is not a reason to deny the mathematical distinction under the pointwise convention.
5. Clarify “comment” framing and verification access. This accepts the venue's scope judgment without falsely conceding unsupported algebra or provenance criticism.
6. The panel's search results identify a **candidate** same-title data record, DOI `10.7910/DVN/V2BYYQ`. Its authenticity, content and relevance have not been checked in this response task. Inspect its primary metadata and file inventory before deciding whether source-field reanalysis is possible; do not infer access to the required arrays or initiate bulk acquisition from the snippet alone. The existing statement “were not obtained” remains accurate.

## Formal-agent gate observation

The exact observed status satisfies the client predicate for this study's final-rejection branch: own ID, HTTP 200, `status=rejected`, and last editorial outcome `reject`. This is an observation, not permission to bypass the client's fresh check immediately before a future authorized formal agent action. No formal gate function or agent POST was executed by this reviewer. Root retains all publication decisions.
