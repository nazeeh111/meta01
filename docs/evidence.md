# Design evidence

Reviewed 23 October 2026. meta01 is an explicit execution preference for Codex, not a separately trained model or an independently measured capability upgrade.

## What informed the design

| Original source | Useful implication | Limit |
| --- | --- | --- |
| [OpenAI: Build skills](https://learn.chatgpt.com/docs/build-skills) | Load useful procedural detail when relevant; declare explicit invocation through native metadata. | Documentation describes operation, not meta01 performance. |
| [SkillsBench v4](https://arxiv.org/html/2602.12670v4) | Compatible domain procedures can help; inappropriate heavyweight workflows can displace stronger defaults. | Its 87 tasks and 18 configurations do not evaluate this general meta-skill or current GPT-6.1. Cross-task length/count comparisons do not establish a universal cap. |
| [SWE-Skills-Bench v1](https://arxiv.org/html/2603.15401v1) | Compatibility and available task headroom matter. | Preliminary, one older agent/model configuration; linked implementation was unavailable during review. |
| [Evaluating AGENTS.md v3](https://arxiv.org/html/2602.11988v3) | Target redundant or poorly matched instructions, not an arbitrary word budget. | Repository coding studies do not cover all creative or research work; necessary authority constraints need not improve a benchmark score. |
| [OneFlow v1](https://arxiv.org/html/2601.12307v1) | Require a practical reason for delegation. | Older-model workflow experiments do not settle modern native subagent utility; their optimizer recipes were not adopted. |

These are design inferences. Research supports neither a mandatory skill stack nor a claim that general meta instructions always improve a capable agent.

## Package choices

- `01` stays explicit-only. Ordinary requests use their normal routing.
- The skill uses the capabilities available in its host; it has no required companion skill, model preset, service or API.
- Adaptation is triggered by meaningful new information, not repeated catalog scans.
- Consequential judgments stay associated with the artifact version actually checked. Agreement or a successful tool exit does not establish the full outcome.
- Investigation, delegation and review are conditional. There is no fixed phase count, source quota, committee, document tree or universal visual style.

## Validation

- An independent fresh-context Sol/high consumer review inspected the frozen package and checked the cited original papers and official skill documentation. Nine local structure/privacy/link checks passed. This was source/package review, not nine task runs.
- The review found one documentation issue: invocation examples needed desktop versus CLI/IDE labels. The README now explains the desktop skill picker and CLI/IDE syntax. Runtime instructions and policy were unchanged after review.
- The native skill validator accepted the package. The runtime has no external relative reference or executable dependency; YAML parses the name as the string `01` and implicit invocation as Boolean `false`.
- Installed skill bytes match the package, with exact prior-byte backups and a separate recovery rehearsal. Global model/configuration and invocation policies were preserved.
- Native prompt diagnostic verification was unavailable (exit 1), so catalog eligibility or desktop invocation is not claimed. No raw prompt was retained. A decorative SVG preview was denied before rendering; that optional study was omitted from the published package and no alternate preview route was used.

The reviewed runtime SHA-256 values are:

```text
skills/01/SKILL.md
909f6afcb56dde8d1e06bcb2b4015ca08f32af43de0a1549c80503292f5b0eb1
skills/01/agents/openai.yaml
f1fbf057cd8e3acee7e031f63c92282cf025dcfb3d82b2538a76baebb00435cf
```

After publication, the maintainer used Codex's native Skill Installer to download commit `64884520e9a7a5eaacadfb63dafccffcc9b02903` into a fresh temporary destination. Both runtime files matched the reviewed SHA-256 values above. This verifies the clean remote download/copy route; desktop activation remains untested.

A separate fresh-context Sol/medium authored research task explicitly invoked only 01. It selected the installed Research guidance, investigated privacy-preserving room occupancy sensing, distinguished presence from headcount, checked manufacturer methods and produced a useful mechanism-level counterexample and qualified next experiment. No hardware was used or purchased. This is one successful observed workflow, not a controlled comparison or proof of general research superiority.

## Limits

No comparative task benchmark, token-saving estimate, broad anti-bias effect or general quality multiplier has been established for this revision. Skill instructions influence model decisions; they cannot guarantee obedience, factual accuracy, tool availability or successful execution. Meaningful task evidence should determine future revisions.
