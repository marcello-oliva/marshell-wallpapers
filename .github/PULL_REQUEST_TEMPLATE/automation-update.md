## ⚙️ Script Change

### Summary

<!-- What does this PR change, and why? Keep it concise but complete. -->

### Type of Change

- [ ] 🐛 Bug fix
- [ ] ✨ New feature / new script
- [ ] ♻️ Refactor (no functional change)
- [ ] 🚀 Performance improvement
- [ ] 💥 Breaking change
- [ ] 🧹 Cleanup / dead code removal

---

### Affected Scripts / Modules

| Path      | Change Type | Notes |
| --------- | ----------- | ----- |
| `bin/...` |             |       |
| `lib/...` |             |       |

<!-- Add rows as needed. If a script's Depends on: header changed, note it explicitly. -->

### Dependency Impact

- [ ] `Depends on:` headers updated to reflect new/removed dependencies
- [ ] No new external dependencies introduced
- [ ] New dependency introduced (list below, with justification)

<!-- New dependencies, if any -->

---

### Architecture & Conventions

- [ ] Follows `module::function` namespacing convention
- [ ] Include guards present (for sourced lib files)
- [ ] `lib/` used rather than `core/` for shared logic
- [ ] No folder-plus-same-named-file anti-pattern introduced
- [ ] kebab-case naming maintained for files/directories

---

### Testing Performed

<!-- Describe how this was tested: manual runs, edge cases, specific Hyprland/Kitty/yazi scenarios exercised -->

- [ ] Manually tested on CachyOS + Hyprland
- [ ] Verified no regressions in dependent scripts
- [ ] Tested edge cases (empty input, missing dependency, concurrent invocation, etc.)
- [ ] `shellcheck` run with no new warnings (if Bash)

```
<!-- Paste relevant test output / terminal session here -->
```

---

### Breaking Changes

<!-- If this PR breaks existing behavior, config, or CLI usage, describe the migration path -->

- [ ] No breaking changes
- [ ] Breaking changes (migration steps below)

---

### Checklist

- [ ] Code is self-documenting or includes necessary comments (Italian inline comments follow existing convention where applicable)
- [ ] No hardcoded paths that should be configurable
- [ ] Error handling covers expected failure modes
- [ ] Related documentation updated (README, help text, `--help` output)

---

### Additional Notes

-

<!-- (Optional) -->

- **Related Issue:** Closes #
