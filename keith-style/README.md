# Keith Style

A portable Agent Skill for drafting and editing in Keith's voice across conversational, academic, explanatory, reflective, and professional situations. The entrypoint is `SKILL.md`; detailed patterns, labeled examples, provenance, and test cases live in `references/`.

## Version 4: developed paragraphs in sustained prose

Updated October 30, 2026 after a supplied v3 article still separated related claims, evidence, and limits into short isolated paragraphs. Preserves the professional, accessible register and v3's protections for distinct qualifications, useful topic sentences, and edit scope. The focused change makes the unit of reasoning the basis for paragraph construction and adds a concrete example and an adjacent-paragraph revision check. It imposes no paragraph-length quota and does not require longer sentences. Long-form and cross-genre tests supplement the earlier short cases; synthetic evaluations are not Keith-authored evidence or personal approval.

## Use

Place the entire `keith-style` directory in the skills location supported by your agent, keeping the reference paths intact. In systems that support named invocation, request `$keith-style`; otherwise ask the agent to read `SKILL.md` and apply it to the writing task. Example: “Use Keith Style. Lightly edit this email, keeping my wording and a professional tone.” The agent still needs the actual assignment and facts.

This package has been prepared as files, not installed or published. It does not require access to the private source chats to operate.

## What is included

- `SKILL.md`: activation, core voice, drafting/editing workflow, boundaries.
- `references/voice-patterns.md`: syntax, grammar, causal structure, diction, and concision.
- `references/registers.md`: situation-specific tone and form.
- `references/examples.md`: authentic excerpts and user changes to AI drafts, clearly labeled.
- `references/evidence.md`: provenance, confidence, limits, and design sources.
- `references/evaluation.md`: synthetic tests and a qualitative rubric.

## Before putting this in a public GitHub repository

The examples contain personal writing, and the provenance contains private conversation links. Review and redact anything you do not want public. Publishing authority and a license are not assumed. A private repository is the conservative starting point. Removing provenance links for a public version should not remove authorship labels or turn AI-assisted text into a claim of unaided authorship.

This is a grounded, revisable style model, not a promise of indistinguishability or a method for misrepresenting authorship. Future real edits from Keith should refine it.
