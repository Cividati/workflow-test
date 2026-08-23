# workflow-test

Scratch repo for testing GitHub Actions. The workflow (`.github/workflows/workflow.yaml`) triggers on pushes to `main`, writes "oi nico" into `file.txt` and cats it. `script.hs` is actually a small bash script that touches `file.txt` (not Haskell).
