## 🖼️ Wallpaper Change

### Summary

<!-- Brief description of what this PR changes. E.g. "Adds 3 new animated wallpapers to the Makima-inspired collection" -->

### Type of Change

- [ ] ➕ Addition (new wallpaper(s))
- [ ] ➖ Removal (deprecated/replaced wallpaper(s))
- [ ] 🔄 Replacement (same slot, new asset)
- [ ] ✏️ Metadata/organization change (renaming, folder restructuring, tagging)
- [ ] 🎬 Animated wallpaper support/config change

---

### Wallpaper Details

| Field                    | Value                          |
| ------------------------ | ------------------------------ |
| **Filename(s)**          |                                |
| **Source / Attribution** |                                |
| **License**              |                                |
| **Resolution**           |                                |
| **Aspect Ratio**         |                                |
| **Format**               | (png / jpg / gif / mp4 / webm) |
| **Static or Animated**   |                                |

> If the wallpaper is sourced from third-party artwork, confirm licensing/attribution is documented and compliant with repository usage terms.

---

### Pywal / Color Extraction Impact

- [ ] Verified `wal -i <wallpaper>` extracts a usable palette
- [ ] Checked contrast/readability of extracted `color0`–`color15` on dependent templates (Kitty, Waybar, rofi, etc.)
- [ ] No manual palette overrides required
- [ ] Manual palette overrides required (explain below)

<!-- If overrides were needed, explain why and where -->

### Rofi Wallpaper Picker Integration

- [ ] New wallpaper(s) correctly indexed by the picker script
- [ ] Folder icon glyph (Nerd Font) renders correctly for the containing directory
- [ ] Preview thumbnail generates without errors
- [ ] N/A — no picker changes required

---

### Screenshots / Preview

<!-- Attach before/after screenshots or a preview grid of the new wallpaper(s) -->

### Checklist

- [ ] File naming follows repository convention (kebab-case)
- [ ] Placed in correct directory per two-level folder navigation structure
- [ ] File size is reasonable (no unnecessarily large uncompressed assets)
- [ ] No duplicate or near-duplicate wallpapers introduced
- [ ] Tested end-to-end: selection → pywal generation → template deployment

---

### Additional Notes

-

<!-- (Optional) -->

- **Related Issue:** Closes #
