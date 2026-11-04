# mlops-student

Zero-install MLOps lab: GitHub Actions generates data, drops PII, trains a fraud model, tests it, and publishes a container to GitHub Container Registry. Call `/health`, `/version`, and `/predict` from a browser terminal.

Nothing is installed on your laptop. You need a free GitHub account and a browser.

## Start here

1. Watch the recording in [`demo-player.html`](demo-player.html) (video: [`demo-walkthrough.mp4`](demo-walkthrough.mp4)).
2. Follow the checkpoints in [`lab-guide.html`](lab-guide.html).
3. Fork this repository as **public**, enable Actions, and run the `mlops-online` workflow.

If GitHub shows the HTML as source, download the files and open `demo-player.html` locally, or use the GitHub Pages URL once it is enabled:

https://mahan0227.github.io/mlops-student/demo-player.html

Starter: https://github.com/mahan0227/mlops-student

Published image: `ghcr.io/mahan0227/mlops-student:latest`

Rollback uses the previous `run-<id>` tag from the same registry.
