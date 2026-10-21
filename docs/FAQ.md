# FAQ

## Does Quick Boost apply or remove modifiers?
No. Quick Boost changes viewport visibility only.

## Does Quick Boost change render visibility?
No. Render visibility is intentionally left unchanged by Quick Boost.

## Does Restore simply turn everything on?
No. It restores the saved exact previous viewport state.

## Can I Boost twice?
A second Boost is blocked while a Quick snapshot is active.

## What are Modeling, Preview, Sculpt, Animation and Custom?
They are user-defined profile slots, not hard-coded presets.

## Do profiles survive saving and reopening a `.blend`?
Yes. Release testing includes save, full Blender shutdown, reopening, Apply, and exact state verification.

## What happens if I rename or reorder a modifier?
Rename and reorder recovery is supported and covered by release tests.

## What happens if an object or modifier is deleted after Boost?
Missing items are skipped and reported so remaining states can still restore.

## Does the add-on use the internet?
No. There is no telemetry, cloud service, account requirement, or external Python dependency.
