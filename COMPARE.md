# COMPARE.md — Google AI Mode (one shot) vs. the pipeline (Claude → Grok → Claude)

No winner is declared here. Two different tools were asked two different things, and that difference is most of the lesson.

## What was compared

| | Google AI Mode (`workflow/00`) | The pipeline (`workflow/07`) |
|---|---|---|
| Prompt | The teacher's Facebook framing plus the question, verbatim, once | A research brief Claude wrote (`02`), answered by Grok (`03`), rewritten by Claude (`04`), edited by a person |
| Who wrote the prompt | The teacher, effectively | Claude Code, at my request |
| Steps | One | Four, plus human edits |
| Cost | Free | Paid tiers (Claude Code; Grok Heavy ≈ $300/mo) |
| Runs | One | One of each step; not rerolled |

## What each answer contains

**Both:** the verdict is yes.

**Google:** a general TOK map. Four labeled rationales: epistemic duty, preventing harm (elections, public health, markets), the echo-chamber effect, undermining trust. An offer to go deeper by Area of Knowledge or by Kant versus utilitarianism. It matches "a brief rationale" and is the right length for the ask.

**Pipeline:** a particular case (India 2018, about two dozen killed), a named philosopher with the actual parable (Clifford's shipowner), a proportional duty (reach × harm), two explicit limits on that duty (verification is unequally affordable; official checkers fail), and a claim about chatbots (asking a machine is not checking). It is longer than the teacher asked for.

**What Google has that the pipeline lacks:** the offer to reframe by AOK and by ethical framework, which is the vocabulary a TOK class grades on.

**What the pipeline has that Google lacks:** Clifford, India 2018, reach × harm, the membership-fee limit, the "who verifies the verifiers" limit, and the two-machines line.

## The honest reading

Google names kinds of harm. The pipeline names a case of harm and then limits the duty. The cheap answer still said yes; the paid stack bought particularity, not permission.

## Confounds, so nobody overreads this

- Different prompts. Google saw the class question; Grok saw a brief that already named Clifford and India. Some of the pipeline's "depth" was placed there by the brief.
- Different shapes. Google is a one-shot search box. The pipeline is multi-step with a human editing between steps.
- Randomness. Either tool run again could produce a different answer. Neither was rerolled, and Google's text was not touched.
- The pipeline's author cared more, spent more, and edited. That is not a property of the models.

## The line to take into class

Same verdict from both tools. The disagreement is in the particulars and in the limits, and those came from a prompt a human asked a machine to write. Whether that counts as the human's work, the machine's, or neither is the question this folder is for.
