# Food Savings Hub dashboard

This public repository is intended to host the **generated grocery deals dashboard only**.

The private `food-savings-hub` repository will build and publish `index.html` here. No passwords, private workflow files, or SMTP credentials should be published.

## Setup

1. In **Settings → Pages**, select **Deploy from a branch**, branch **main**, folder **/(root)** and save (once `index.html` is published).
2. The private generator needs a GitHub Actions secret named `DASHBOARD_PUBLISH_TOKEN` with **Contents: Read and write** permission scoped **only** to this public repository.
3. The publishing workflow will update `index.html` at a stable URL.

Shopping list data is stored in each visitor's browser, not in this public repository.