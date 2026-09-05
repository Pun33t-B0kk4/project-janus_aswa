# Examples

## Inputs

- `test_unsafe.json` graded unsafe telemetry case
- `test_safe.json` benign telemetry case

## Run

```bash
python run_baseline.py --input examples/test_unsafe.json
```

## Outputs

Running the baseline writes:

- console trace
- `last_run.json` (gitignored local artifact)

`baseline_output_screenshot.png` is the captured baseline console output used in the proposal.
