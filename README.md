# meta01

**Adaptive execution for Codex.** One invocation. The capabilities your task needs.

**meta01** is a compact, explicit-only Codex skill installed as **01**. It asks Codex to select useful tools and specialist workflows, adapt when evidence changes, and carry the authorized task through delivery. You describe the outcome; you do not need to remember a stack of skill names.

In Codex CLI or the IDE extension:

```text
$01 Finish this feature in the existing repository.
```

In the desktop app, select **01** from the **@** skill picker and describe the task.

## Install

Ask Codex to install the skill:

```text
Install the Codex skill at
https://github.com/nazeeh111/meta01/tree/main/skills/01
```

CLI/IDE users can explicitly invoke `$skill-installer` with that URL. In the desktop app, use the installer from the **@** picker when available.

If you already have a skill named `01`, inspect and update that copy instead of installing a duplicate. Preserve your local customizations. Start a new Codex chat after installation, then select **@01** in the desktop app or use `$01` in CLI/IDE.

The package contains Markdown instructions and invocation metadata. It requires no additional package, account, API, background process or configuration framework. Capabilities come from your existing Codex environment; relevant specialist skills remain optional.

## How it works

- **Choose deliberately.** Use a direct route when clear. Discover an additional capability when it could materially improve the result.
- **Adapt to the work.** Check guidance against the actual artifact, versions and constraints. Reconsider the approach when requirements, evidence or opportunities change.
- **Challenge the favored answer.** Distinguish a required outcome from a suggested mechanism. Resolve consequential choices with evidence and useful independent scrutiny.
- **Coordinate proportionately.** Delegate separable work when it earns the cost, with concise briefs, clear ownership and model/effort choices within your authorization.
- **Finish the outcome.** Compare the current artifact with the full request and acceptance evidence. Keep meaningful partial results and concrete blockers visible.

These are decision criteria. The task determines the method, creative direction and useful amount of investigation.

## Try it

Use these with **@01** in the desktop app, or the `$01` prefix in CLI/IDE:

```text
$01 Investigate whether this proposed dependency earns its cost.
Compare it with the strongest current route, inspect the implementation,
and make the useful change if the evidence supports it.
```

```text
$01 Turn these notes into a usable interactive explanation.
Choose the tools and visual direction for the subject, retain editable
sources, and verify the result with representative interactions.
```

Explicit invocation keeps this execution preference out of ordinary requests. The skill respects the host's instructions, purpose-specific opt-ins, permissions and your model choices. It grants no additional tool access or authority to publish, spend or change accounts.

## Design and evidence

The runtime skill is one small file plus `agents/openai.yaml`. It is self-contained, so installing it does not require another discovery skill. Research and validation stay outside the runtime instructions.

[Design evidence and validation](docs/evidence.md) records the research basis, actual checks and limits. Existing studies evaluate other tasks, models and skill types. They do not establish that meta01 outperforms ordinary Codex, and this project makes no measured performance-multiplier claim.

To improve it, bring a concrete request, the observed outcome and the relevant artifact or check. A shorter prompt, longer checklist or larger team is useful only when it improves the work.

[MIT license](LICENSE).
