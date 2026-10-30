# Behavioral evaluation cases

Use these cases after material changes to the skill. The inputs below are **synthetic test prompts**, not authentic Keith writing. Judge the decisions and resulting prose, not exact wording or an AI-detector score. A structural validator cannot establish personal-voice quality.

## Test 1: Minimal-edit ownership

Prompt: “Only fix clear grammar mistakes. Keep my wording: ‘I think this policy solves the wrong problem because students can still share answers which makes the extra monitoring more annoying without actually changing why people cheat.’”

Check: preserves the causal sentence and argument; makes only a necessary small punctuation repair if desired; does not split it into slogans, add a thesis, or invent evidence. Does not fabricate additional mistakes.

## Test 2: Tactful professional disagreement

Prompt: “Write an email to my manager. I disagree with moving the meeting to 7 a.m. because my existing shift starts at 9. Ask whether I can join remotely. Firm but professional; don't blame anyone.”

Check: states the conflict and request clearly, avoids accusation, uses ordinary courtesy, invents no commute or family commitments. Does not copy the force of a privacy-policy argument or announce emotional detachment.

## Test 3: Professional accountability

Prompt: “I missed the deadline because I misread the date. Write a brief apology to my professor, take responsibility, and ask whether I may submit tonight.”

Check: includes the requested sincere apology and responsibility. Does not suppress the apology because of a historical email preference; does not add an excuse, over-apologize, or promise an invented record of reliability.

## Test 4: Argument without a false contradiction

Prompt: “I agree that students need less distraction, but I oppose banning all laptops. Some students use accessibility tools and others need them for notes. Write one argumentative paragraph. Don't invent statistics.”

Check: grants the concern, targets the blanket method, explains a relevant consequence, preserves the supplied stance, invents no data, and does not call responding to distraction logically contradictory.

## Test 5: Neutral summary

Prompt: “Summarize this neutrally in my style: The author says public libraries offer internet access and study space, but limited evening hours make them harder for working adults to use. The author proposes later hours two days a week.”

Check: clearly attributes the claim, concern, and proposal; adds no personal rebuttal, political belief, dramatic conclusion, or unrelated life experience.

## Test 6: Conversational economy

Prompt: “Message a friend that I can help Saturday afternoon, but I need the address first. Casual, friendly, and concise.”

Check: conveys availability and request without elaborate setup, excessive slang, artificial typos, or hostility. Does not need an “okay well” opening to count as conversational.

## Test 7: Honest personal reflection

Prompt: “Write a short reflection from these facts only: I was nervous before a presentation, practiced twice with my cousin, and felt more comfortable when I started. Don't turn it into a huge life lesson.”

Check: keeps cousin detail, does not invent dialogue, a lifelong problem, applause, or a transformed identity. Allows genuine stated emotion without a therapeutic growth narrative.

## Test 8: Current instructions override tendencies

Prompt: “Use my style for a polished formal essay explaining this supplied concept. No first person. Use an em dash once because this publication requires it.”

Supply a neutral, factual concept description. Check: follows the current requested register and punctuation despite defaults, retains connected reasoning, and does not insist on personal opinion or casual grammar.

## Test 9: Concision is not automatic shortening

Prompt: “Make this less wordy but keep the explanation and the specific example. Don't target a shorter word count.”

Supply a paragraph with both empty setup and a substantive causal chain. Check: removes redundant setup and category lists while retaining evidence and why it matters. Do not score only by length.

## Test 10: Recipient name is not a voice request

Prompt: “Write an email to Keith from his lab partner Maya. Use Maya's warm, detailed style, not Keith's. Say I can review the slides tomorrow.”

Check: does not apply Keith Style merely because Keith is the recipient. Follows the explicitly requested speaker's voice and supplied facts; does not borrow Keith's directness or personal history. If evaluating automatic skill selection, this prompt should not select the skill on the name alone.

## Test 11: Mentioning Keith is not an activation trigger

Prompt: “Explain in a neutral institutional voice that Keith is presenting at 2 p.m. and the discussion follows at 2:30. This is an event announcement, not a request to imitate him.”

Check: does not impose Keith's first-person stance, conversational patterns, or argumentative style. Uses the requested institutional voice. The skill's presence in the available catalog must not override the actual writing request.

## Test 12: Facts-only draft with no reference-corpus leakage

Prompt: “Use Keith Style for a short first-person introduction. Use only these facts: I am joining the volunteer team this month, I can help on weekends, and I want to learn how the sign-up process works. Do not add any background.”

Check: mentions only the supplied availability, activity, and request. Does not import music, performance anxiety, gaming, relatives, school details, political or religious beliefs, technology habits, or any other reference-corpus fact. Does not treat example writing as a current autobiographical instruction. If it needs more information, it must not fill the gap with a remembered example.

## Test 13: Preserve exact quotations and citation strings

Prompt: “Lightly edit this paragraph in Keith Style. Keep the quotation and citation exactly as supplied: The report says ‘Participants may withdraw at any time.’ (Study Protocol, §4.2, p. 7). I think this matters because it makes clear that agreeing at the start does not mean someone loses the ability to change their mind.”

The report sentence and citation are synthetic test fixtures, not a verified external quotation or a real source claim. They are supplied only to test preservation.

Check: leaves the quoted words, capitalization, terminal punctuation, and citation string unchanged. Edits only surrounding prose if needed. Does not paraphrase an attributed direct quote to make it sound more like Keith, invent bibliographic details, or silently “correct” the source. If a real task contains a suspect quotation or unsupported citation, flag it separately rather than changing the attributed text without permission.

## Test 14: Easy-to-read article is not automatically casual

Prompt: “Use Keith Style to write an easy-to-read article, no more than 250 words, from this fictional project brief. Include an introduction and two short sections. Use only these facts: A town measured reservoir levels weekly for three years. Levels were lower each July than each April. The record shows a seasonal pattern but cannot establish its causes. Rainfall and water use were not measured. Annual averages hide the differences between seasons. The next study will record rainfall and water use alongside water levels. These additional measurements may help distinguish explanations but will not by themselves prove cause and effect.”

Check the opening separately from the body. Both should use polished, formal-accessible prose without a casual-tone instruction. The opening should establish the study or evidentiary distinction, not “You might think,” “more complicated than people realize,” a generic importance hook, or a question-and-reveal. Related claim, evidence, and limitation should form coherent paragraphs, not a procession of isolated teaching beats. Keep the uncertainty, the absence of causal proof, and all central facts. Do not invent numbers, motives, findings, or citations. Do not solve formality through ornate vocabulary or needless density.

## Test 15: Fix the opening without flattening good later writing

Prompt: “The opening is too informal for my professional article. Rewrite only that opening in Keith Style; keep the body and citation exactly unchanged. Opening: ‘You might think a complete archive tells us everything. It does not. This is an important distinction.’ Body: ‘The archive preserves the surviving letters, but it does not establish how many letters were originally written. A complete catalog of the surviving material is therefore not necessarily a complete record of the correspondence. [Archive note, p. 4]’”

The archive and citation are synthetic fixtures. Check: replaces the staged opening with a direct, appropriately qualified introduction using only supplied information. The entire body and citation remain byte-for-byte unchanged. It does not manufacture precision, combine every sentence, or treat the whole piece as defective because the opening failed.

## Test 16: Cohesion without a paragraph-length formula

Prompt: “Revise this for a professional informational article in Keith Style. Keep it easy to read and preserve every qualification: ‘The survey counted responses. It did not count everyone who received it. This is important. People who chose to respond may differ from people who did not. The results describe the respondents. They do not automatically describe the whole population.’”

Check: groups the sampling distinction and its consequence into connected exposition. Removes empty significance language rather than removing the explanation. It may use one paragraph and several clear sentences, but no particular count is required. It must not imply that a biased sample has been proven or that the responses are useless. No artificially long sentence, fake grammatical error, or inflated synonym is needed.

## Test 17: Accessible professional prose can already be correct

Prompt: “Check whether this needs a style change for a professional article in Keith Style. If it already works, say so rather than rewriting: ‘A record can preserve an account accurately without proving that the event occurred. Likewise, an account can contain errors while still describing a real event.’”

This is a synthetic illustration of an evidentiary distinction. Check: recognizes the connected, clear, professional explanation; does not demand formal-sounding synonyms, fewer short words, more complexity, or an introductory signpost. It must distinguish voice assessment from independent verification of an entire article.

## Test 18: A current casual request still controls

Prompt: “Use Keith Style to explain casually to a friend why an annual average can hide seasonal changes. Keep it to two sentences. Use this made-up example: a reservoir measured 10 units in April and 6 in July. No professional-article tone here.”

Check: follows the explicit casual context rather than treating version 2 as a universal formality rule. Makes the point clearly, invents no causes or personal history, and does not need excessive slang, typo imitation, or exaggerated personality.

## Test 19: Useful questions and headings are not banned

Prompt: “Use Keith Style to edit this professional FAQ, preserving its question heading and answer format. Keep the quoted instruction unchanged. ‘What does the archive include? The archive includes the surviving letters. This is very important because the original instruction says “Keep all letters received.” That instruction does not prove every letter survived.’”

This archive and quotation are synthetic fixtures. Check: retains the requested question heading, exact quotation, and evidentiary limit. Removes generic significance if useful and connects the explanation naturally. Does not convert the FAQ into an essay or infer that the new article-opening guidance bans all questions and reader-oriented structure.

## Test 20: A different situation — workplace decision memo

Prompt: “Use Keith Style for a professional decision memo of 180–260 words to a department manager. Use only this fictional brief. We tested a new request form for four weeks with eight volunteers from one team. Median handling time was 18 minutes on the old form and 12 on the new form. The test did not measure error rates, and volunteers may not represent the whole department. Two volunteers said the new attachment field was unclear. I recommend revising the field instructions, then running a six-week pilot across three teams that measures both handling time and error rates. We have not estimated rollout costs. Ask the manager to approve the expanded pilot, not department-wide adoption. No invented budget, deadline, or promised outcome.”

Check: makes the actual recommendation and approval request clear; connects the timing result to its limited basis without implying proven causation; retains the unclear field, both missing measurements/cost information, sampling limit, and proposed pilot details. Related evidence and limits read as reasoning, not repeated stand-alone lead-ins followed by generic cautions. The ending advances the requested decision rather than re-listing every caveat. Do not enforce a prescribed paragraph count or demand new factual content to reach the length range.

## Test 21: Distinct limits must survive smoother prose

Prompt: “Revise this short professional report in Keith Style without adding facts: ‘The trial had a useful result. Six of ten devices lasted longer with the new setting. But this does not prove all devices will last longer. There is another issue. Heat was not measured, so the trial cannot tell us whether the new setting changes temperature. Cost also matters. The new setting uses a paid service, but its price has not been supplied. We should decide whether to run a larger test before buying the service.’”

Check: retains six of ten, the non-universal result, unmeasured heat, unknown price of a paid service, and the proposed decision before purchase. Reduces empty lead-ins while preserving all three distinct evidentiary or practical limits. Does not infer safety, cooling, savings, causal proof, a required purchase, or a larger-test outcome. Does not use the guidance to remove all “but” clauses or force a long sentence.

## Test 22: Minimal edits protect deliberate structure

Prompt: “Use Keith Style, but only fix spelling in this text; do not change sentence or paragraph structure: ‘The result is preliminary.

The sample is small, so we cannot generalize it.

The next step is a larger trail.’ Here, ‘trail’ was meant to be ‘trial.’”

Check: changes only `trail` to `trial`, preserving the deliberately supplied isolated paragraphs and all other characters. Current edit scope outranks preferences about repetitive lead-ins or caveat placement.

## Test 23: Sustained article, not only a short memo

Use a fresh agent to draft a complete 900–1,200-word formal-accessible article from a substantial fictional evidence brief spanning several related subjects. Supply observations, explanations, differing records, and distinct limits; retain the exact brief with the output. Ask for an article, not a paragraph exercise, and do not disclose the expected stylistic fix. Review the entire output for whether paragraphs actually develop points and whether neighboring fragments should belong together. Assess facts, all distinct limitations, and register separately. Count short paragraphs only as a diagnostic, never a pass threshold. Do not mark the case passed because the opening or one excerpt is good.

Also revise a representative long passage of an actual unsuccessful output when available, preserving its factual content and attribution without claiming independent fact-checking. Compare the resulting paragraph relationships directly, not merely total word count. Treat a successful rewrite as evidence of editing behavior, not proof of fresh generation.

## Review rubric

Evaluate each dimension qualitatively as **met**, **mixed**, or **missed**:

- **Activation:** The task actually requests Keith's voice; merely addressing or mentioning Keith does not override another requested voice.
- **Intent and facts:** No invented facts, beliefs, quotations, or autobiographical details; meaning survives.
- **Source fidelity:** Exact quotations and citation strings survive voice editing unchanged unless the user authorizes changes; examples do not leak into new factual content.
- **Register:** Audience, warmth, formality, and bluntness fit the task.
- **Article opening:** Professional introductions establish substance directly; accessibility does not turn them into casual spoken explainers. Assess separately from the later body.
- **Paragraph cohesion:** Related claim, evidence, and qualification stay connected without a fixed length quota or elimination of useful short sentences. Across a longer piece, avoid repeated empty lead-ins and mechanically identical paragraph shapes.
- **Qualification placement:** Every substantive limitation survives at the scope where it matters; repeated generic cautions do not substitute for reasoning. Preserve distinct or locally necessary qualifications.
- **Reasoning shape:** Relationships among claim, cause, distinction, and consequence remain explicit.
- **Sentence-level fit:** Natural connected syntax and direct diction without imposed monotony or fake errors.
- **Editing restraint:** Requested depth respected; deliberate user revisions not silently undone.
- **Non-caricature:** No obligatory caps, slang, jokes, rhetorical questions, rigidity, or generic “humanizing.”

Treat invented facts, misrepresented positions, or ignoring explicit edit limits as substantive failures, even if the prose sounds plausible. Use failed cases to make narrow corrections. Ultimately Keith's actual edits are more informative than an evaluator's impression of resemblance.

Version 2 adds tests 14–19; the earlier tests remain necessary to detect regressions in conversation, authorship boundaries, editing restraint, and source fidelity. Do not report these cases as passed unless outputs have actually been generated and reviewed. Structural validation alone tests neither register nor personal resemblance.

Version 3 adds tests 20–22 in a different writing situation and retains tests 1–19 for regression checks. A smoother cadence is not a pass if a limitation or requested edit boundary is lost.

Version 4 adds sustained-article testing (test 23). Retain the source brief, full outputs, and scope of review; earlier short tests alone do not establish sustained cohesion.
