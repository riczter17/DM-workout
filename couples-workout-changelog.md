# Couples Workout Tracker - Changelog

## v2.4 - 3 May 2026
- Timer-based exercises (unit: "sec") now use a dedicated seconds dropdown
  - Range: 5 to 180 seconds in 5-second increments
  - Options display with "s" suffix (e.g. "40s", "45s")
  - Labels show "S1" / "S2" (set 1 / set 2) instead of "R1" / "R2"
- Rep-based exercises unchanged (0-30 reps, labelled "R1" / "R2")
- Applies to: Plank Hold, Single-arm Holds, and any future timer-based exercises
- Fully backward compatible with existing session data

## v2.3 - 2 May 2026
- Added ability to change session date after creation
  - Tap the date in the session header to edit
  - Date picker with Save/Cancel buttons
  - Validates against duplicate dates (cannot change to a date with an existing session)
  - Week number updates automatically after date change
- Fully backward compatible with v2.0, v2.1, and v2.2 data

## v2.2 - 1 May 2026
- Replaced reps number inputs with dropdown rollers (0-30 range, native iOS scroll picker)
- Added per-person "+ Hold" toggle (same pattern as weight toggle)
  - Hold duration dropdown: 1-60 seconds
  - Per-person: one person can have a hold, the other doesn't
  - Toggle state persists in session data
- "+ Weight" and "+ Hold" buttons now sit side by side when both available
- "Last wk" hint now shows hold duration per person
- Progress view shows "Her hold" / "Him hold" columns when hold data exists
- Fully backward compatible with v2.0 and v2.1 data

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
