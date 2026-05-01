# Couples Workout Tracker - Changelog

## v2.1 - 1 May 2026
- Added 12kg kettlebell to weight picker (inserted between 11.5 and 13 in the weight array)
- Added per-person "Add weight" toggle on non-weighted exercises
  - For exercises marked as non-weighted in the library (e.g. bridges, plank), each person now has a "+ Add weight" button
  - Tapping reveals the weight picker for that person only
  - The other person's view is unaffected
  - Toggle state persists in session data
- Updated progress view: weight columns now show per-person (Her kg / Him kg) instead of single shared column
- Fixed "Last wk" hint to show weight per person (previously only showed her weight)
- Fully backward compatible with v2.0 data

## v2.0
- Placeholder font styling (lighter colour for unfilled fields)
- Dumbbell weight picker (4-40kg in 1.5kg increments)
- Per-exercise variation notes
- Future session creation (no date restriction)
- Version number on home screen
- Warm-up / cool-down reference page
- Timezone fix (UTC to local)
- Export/import
