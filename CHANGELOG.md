## 0.4.0
- Updates ROHD dependency to at least v0.4.0
- Breaking: made `columnWidth` an optional named argument in `TrackerField` (https://github.com/intel/rohd-vf/issues/10).
- Increased minimum Dart SDK version to 2.18.0.
- Upgraded and made lints more strict within ROHD-VF, leading to some quality and documentation improvements.

## 0.3.1
- `Stream`s in `Monitor` and `Sequencer` are now synchronous (fix https://github.com/intel/rohd-vf/issues/8).
- `Tracker` now writes to files asynchronously to improve performance (fix https://github.com/intel/rohd-vf/issues/12).
- Fixed bugs related to test, simulation, and objection completions (https://github.com/intel/rohd-vf/pull/15).

## 0.3.0
- Updates ROHD dependency to at least v0.3.0

## 0.2.0
- Updates ROHD dependency to at least v0.2.0
- Adds `Tracker` to make logging events during a test simple for reading or parsing.

## 0.1.1

- Fix documentation issues.

## 0.1.0

- The first formally versioned release of ROHD Verification Framework.
