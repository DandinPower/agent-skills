---
name: report-findings
description: Write a self-contained report of findings from the current conversation for a low-context reader. Use when the user asks for a report, write-up, or handoff after a long or multi-turn session.
---

# Report findings

The reader is **low-context**: intelligent, but they have not seen the conversation, your tool calls, your reasoning, or the files you opened, and they may be switching in from other work. The report must stand alone.

## Steps

1. **Fix the scope.** Name the content the user asked about and the reader. If the user named a reader (a manager, a teammate, their future self), write for that reader. Otherwise write for the low-context reader above. Done when you can say in one sentence what question the report answers.
2. **Collect the final state.** Walk the whole conversation from the start, not only the recent turns. For each finding in scope, record its latest state: long sessions revise early conclusions, so the last word wins. Mention an earlier conclusion only when the reversal itself matters to the reader. When a claim rests on a file, command, or data you can still reach, check it against that source. Done when every finding in scope has a latest state and a basis: verified, observed in the conversation, or inferred.
3. **Write** the report by the rules below.
4. **Reread as the reader.** Read the draft as someone who saw none of the conversation. Fix every term the reader cannot know, every pointer back into the conversation ("the earlier approach", "option B", "fix #2"), and every claim with no basis. Done when a full pass finds nothing to fix.
5. **Deliver** in the location and format the user asked for. If they named neither, answer in chat.

## Writing rules

- **Key points first.** The first few sentences carry the answer, the outcome, or the decision the reader must make. Supporting detail follows in order of importance (progressive disclosure). Each sentence uses only ideas the reader has already met.
- **Plain words.** Replace every term coined during the work (nicknames, abbreviations, labels) with a plain description any reader would understand.
- **Simplified Technical English.** Write mostly in the style of ASD-STE100: short sentences, one idea per sentence, active voice, and the same word for the same thing throughout.
- **Prose for connected ideas, bullets for separate items.** Use a paragraph where ideas build on each other. Use a list only for items that stand alone.
- **Concise, with the key context.** Keep what the reader needs to understand or act. Leave out the rest unless the user asks for it.
- **Confidence is visible.** Say which findings are verified, which are inferred, and what is still open.
