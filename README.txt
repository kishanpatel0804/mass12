Mass 12 v2.3

Workout lifecycle:
- Starting a workout creates an autosaved active session only.
- Set values, RIR, notes and rest-timer state are continuously saved locally.
- Force-closing the PWA leaves the active session available via RESUME WORKOUT.
- Only FINISH WORKOUT commits the session to History and advances the program.
- CANCEL WORKOUT discards the active session after confirmation and does not add History.

PWA/iPhone:
- Explicit 180x180 apple-touch-icon is included.
- Manifest icons and start URL are versioned to encourage iOS icon/cache refresh.
- Service-worker cache name is mass12-v23.
