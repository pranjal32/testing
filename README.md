# testing

## Build AirSync on GitHub Actions (macOS)

This repository includes a workflow at `/home/runner/work/testing/testing/.github/workflows/build-airsync.yml` that builds `sameerasw/airsync-mac` using the `AirSync Self Compiled` scheme on a macOS runner.

### Run it

1. Open **Actions** in this repository.
2. Run **Build AirSync (Self-Compiled)**.
3. (Optional) Set the `ref` input to a branch/tag/commit from `sameerasw/airsync-mac`.
4. After completion, download the **AirSync-app** artifact.

The artifact contains `AirSync.app`.
