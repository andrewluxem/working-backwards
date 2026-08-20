# working-backwards

Working backwards starts with a specific customer, a supported problem, and the future experience before features or implementation. This skill produces an internal Working Backwards PR/FAQ or audits one without inventing customer proof, endorsements, or launch commitments.

It produces:

- **Working Backwards PR/FAQ** (A. Draft): built from an idea brief, customer evidence, constraints, and decision needed.
- **PR/FAQ Audit** (B. Audit): built from an existing future press release, FAQ, or full PR/FAQ.

It executes the [Working Backwards playbook](https://www.andrewluxem.com/playbooks/working-backwards). The playbook teaches the framework. This skill runs it and returns a working artifact.

**Static by construction: no dependencies, executable code, telemetry, network calls, remote instructions, auto-update, scheduled work, or background behavior.** It reads only the files in its own skill folder. Nothing happens until a user or agent invokes it.

## Install

Clone and copy the skill into Claude Code:

```bash
git clone https://github.com/andrewluxem/working-backwards.git
cp -r working-backwards/skills/working-backwards ~/.claude/skills/
```

Or install it as a Claude Code plugin:

```text
/plugin marketplace add andrewluxem/working-backwards
/plugin install working-backwards@working-backwards
```

For clients that install from an archive, keep using the versioned [working-backwards v1.0.0 ZIP](https://www.andrewluxem.com/downloads/working-backwards-v1.0.0.zip).

## Invoke it

```text
Write the PR/FAQ for this idea
Write the PR/FAQ for a saved reconciliation view. The customer is an analyst who
Turn this idea dump into a PR/FAQ. Product for everyone, solves reporting. Launch
```

Naming the skill is always valid: `use the working-backwards skill`.

## Files

```text
.claude-plugin/
  plugin.json
  marketplace.json
skills/working-backwards/
  SKILL.md
  meta.yaml
  LICENSE.md
  assets/
  references/
README.md
LICENSE
```

The complete canonical package is copied under `skills/working-backwards/`, including every asset, reference, example, and license file present in the source.

## Versioning

Plugin installation is version-pinned. When behavior changes, update the version consistently in `SKILL.md`, `meta.yaml`, and `.claude-plugin/plugin.json`, then add a changelog entry. Reinstalling is an explicit update; this repository never auto-updates itself.

## License

MIT. See [LICENSE](LICENSE). The canonical skill folder carries the same authorization in [skills/working-backwards/LICENSE.md](skills/working-backwards/LICENSE.md).

---

## More playbooks

This skill packages one playbook from the free library at [github.com/andrewluxem/playbooks](https://github.com/andrewluxem/playbooks). Every playbook is free to read, with no email required.
