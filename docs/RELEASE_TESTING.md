# Release Testing — Modifier State Vault 1.1.0

## Release artifact

SHA-256:

`8c6c9af146c66d24743e78370708548c6ae111e30e6e3d3093c785986c75ce8e`

## Functional regression

- PASS: 18
- FAIL: 0

Covered registration, statistics, Quick Boost, exact Restore, double-Boost protection, profile operations and deleted-modifier safety.

## Stress test

- Objects: 240
- Modifiers: 1200
- PASS: 17
- FAIL: 0

Covered statistics, Quick Boost, exact mixed-state restoration and exact profile restoration across 1200 modifiers.

## Master release regression

- PASS: 54
- FAIL: 0
- SKIP: 0

Covered:
- Safe / Strong / All / Custom
- Selected / Visible / Active Collection / Whole Scene
- exact statistics
- all five profiles
- rename/reorder
- deleted modifier
- deleted object
- empty scope
- render-state safety
- double-Boost protection

## Persistence

PASS.

Verified:
- profile saved into `.blend`
- Blender fully closed
- `.blend` reopened
- pre-Apply state differed
- saved profile applied
- exact viewport/render state restored

## Manual QA

Manual UI smoke test: PASS.

## Extension package

Blender Extension validation: PASS.
