# W03 ANTI-SLOP ANALYSIS — HYPOTHESES, NOT VERDICTS

This analysis explicitly rejects **“AI-looking = bad”** and **“this looks generic”** as evidence. It maps observable structure to a falsifiable harm claim, supporting evidence or absence thereof, legitimate counter-context, and current synthesis result. No visual taste judgement establishes authority.

**Evidence grades:** DIRECT=NORMATIVE_TEXT or exact source CODE within narrow scope; SYSTEM-SPECIFIC=official guidance for that system; INFERRED=reasoning from such guidance without outcome measurement; INSPIRATION-ONLY=visual metadata (Landbook) and cannot establish engineering quality.

## DECORATIVE_CARD_OVERLOAD

- **Observable structure:** Repeated card/surface borders around units without distinct content grouping.
- **Claimed harm:** Extra boundaries could weaken grouping and increase scanning steps.
- **Evidence / grade:** NONE directly: S3/S4/S5 document meaningful grouping, not harm from card counts. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Dense catalogs/cards may intentionally represent self-contained items.
- **Current result:** **WEAK / INSUFFICIENT — no visual audit or measured harm**.

## CONTAINER_NESTING_WITHOUT_INFORMATION_VALUE

- **Observable structure:** Multiple nested wrappers/borders that do not represent additional information relation.
- **Claimed harm:** Possible perceived complexity or maintenance cost.
- **Evidence / grade:** S3/O14 and S6/O26 show useful nested layout scaffolding; no direct evidence of useless nesting harm. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Grid wrappers can implement responsive containment without being semantic sections.
- **Current result:** **WEAK / INSUFFICIENT — cannot infer from presence of DOM wrappers**.

## UNIFORM_VISUAL_WEIGHT

- **Observable structure:** Main content, supporting metadata and headings presented with indistinguishable prominence despite unequal task priority.
- **Claimed harm:** Reduced scannability or lost topic/subtopic recognition.
- **Evidence / grade:** S2/O06-O08, S4/O19, S5/O21,O23; inference from documented hierarchy value. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Comparable catalog entries may legitimately use equal emphasis.
- **Current result:** **CANDIDATE W03-A01 / LOW; no user testing**.

## WEAK_INFORMATION_HIERARCHY

- **Observable structure:** Heading ranks, navigation labels and content grouping fail to reflect actual topic structure.
- **Claimed harm:** Harder navigation and comprehension; missing programmatic relationships can affect assistive technology.
- **Evidence / grade:** S1/O01,O05 normative only for actual requirements; S2/O06-O09 explanatory. Normative scope limited to actual SC; other claims are contextual.
- **Legitimate counter-context:** An untitled small decorative sub-block is not necessarily a new section.
- **Current result:** **SCOPE SPECIFIC — covered by W03-P01; no separate anti candidate**.

## EXCESSIVE_SECTION_FRAGMENTATION

- **Observable structure:** Numerous tiny heading/region divisions for material that belongs in a single context.
- **Claimed harm:** Potential loss of continuous reading flow or landmark usefulness.
- **Evidence / grade:** No direct controlled source quantifies too many sections; WAI only explains meaningful headings/regions. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Step-by-step instructions may legitimately need small subsections.
- **Current result:** **WEAK / INSUFFICIENT**.

## MEANINGLESS_METRIC_SURFACES

- **Observable structure:** Numerical badges/cards lack defined units, provenance, timeframe or decision relevance.
- **Claimed harm:** Misinterpretation or misplaced trust.
- **Evidence / grade:** No seven-family source directly tests metric semantics or data provenance; outside authorized research domain. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Operational dashboards need repeated KPI summaries for rapid monitoring.
- **Current result:** **UNRESOLVED / OUTSIDE EVIDENCE — no candidate**.

## WHITESPACE_WITHOUT_STRUCTURAL_PURPOSE

- **Observable structure:** Large empty gaps not attributable to intended grouping, reading width or task emphasis.
- **Claimed harm:** Could hide important content below fold or reduce information access.
- **Evidence / grade:** S3/O12,O13, S4/O20 support different widths/models, not empirical harm from particular gaps. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Editorial design may deliberately employ generous negative space.
- **Current result:** **WEAK / INSUFFICIENT**.

## DECORATIVE_ICON_SATURATION

- **Observable structure:** Many icons repeat without adding identifiable meaning to categories/actions.
- **Claimed harm:** Potential signal dilution.
- **Evidence / grade:** No qualifying direct evidence in W03's layout corpus; icons only touched by Carbon geometry. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Icon-rich toolbars can efficiently support expert users with accessible labeling.
- **Current result:** **UNRESOLVED / NOT SUPPORTED**.

## GENERIC_HERO_COMPOSITION

- **Observable structure:** Repeated headline, subcopy and CTA layout across domains without mapping to user intent.
- **Claimed harm:** Potential domain mismatch, generic content, weak task discovery.
- **Evidence / grade:** Landbook W02-S5/W03-O30 provides listing metadata only; no showcase visual evidence or outcomes. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Simple marketing landers may benefit from familiar conventions.
- **Current result:** **REJECT AS EVIDENCED CLAIM IN W03; future hypothesis only**.

## FAKE_DASHBOARD_DENSITY

- **Observable structure:** Interfaces visually packed with metrics/controls not grounded in actual tasks.
- **Claimed harm:** Supposed confusion or low decision value.
- **Evidence / grade:** Carbon S4/O20 positively documents legitimate high-density models; no W03 measured fake data examples. Do not reclassify suggestions as measured fact.
- **Legitimate counter-context:** Complex analytics/products require full-width, high-density presentation.
- **Current result:** **REJECT BLANKET CLAIM; need task and data-provenance audit**.

## Aggregate findings

- Only the scoped **W03-A01 Undifferentiated content priority** hypothesis has enough cross-source reasoning for a LOW-confidence `CANDIDATE`, not acceptance. It remains challengeable by dense/uniform comparison layouts.
- Decorative card overload, nested containers, section fragmentation and whitespace excess lack direct harm evidence in this corpus. Their names do not constitute anti-pattern records.
- Carbon's content-fit models (W03-O18/O20) are positive counterevidence to a blanket **dense = bad** rule.
- Failed Landbook example-detail inspection means no gallery-based visual anti-pattern may be asserted. W03-O30 is listing metadata only.
- A WCAG finding can be made only by testing the actual success criterion against an actual interface. None was tested here.

## Review instruction

Do not generalize W03-A01 to all minimalist/dense pages; ask for an actual target, content hierarchy, users/tasks and outcome evidence before promotion.