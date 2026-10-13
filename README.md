# gemini-cli-action-lab

Throwaway CI lab (owner-side, vdp-hunt lane W2-MCPCONF-CI-ACTION): official
`google-github-actions/run-gemini-cli@v0` action usage exactly as
`examples/workflows/pr-review` uses it (settings input, `--yolo` via action,
artifact/telemetry steps), fed by a fork-PR workspace.

Benign markers only; dummy API key; no secrets; no third-party systems.
Payload effects are appends to `/tmp/w2-mcpconf-action-marker.log` on
ephemeral GitHub-hosted runners.
