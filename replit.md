# Chromium on Replit

## Run

The project uses the existing Nix configuration to provide Chromium and the
`run.sh` launcher to start it. The configured Replit workflow is **Chromium**
and runs:

```sh
bash run.sh
```

Start the workflow from the Run button to open Chromium in the desktop preview.

## Notes

- Chromium is installed through `replit.nix`.
- The launcher stores its profile under `.config/`.
- Sound output is not supported by this project due to Replit's VNC implementation.