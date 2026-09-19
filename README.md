# Building 3D Reconstruction

This public repository runs an open-source single-image 3D reconstruction pipeline from GitHub Actions.

The input image is a tight crop of the central building from the supplied photo.

## Run
Open Actions -> Building 3D reconstruction -> Run workflow.

The finished PLY mesh and preview renders are saved as a workflow artifact.

## Free usage
Standard GitHub-hosted runners are free for public repositories.

## Limitation
One photo cannot reveal the back and hidden sides of a building. The upstream pipeline describes its output as a 2.5D depth reconstruction / relief, not a complete all-sides model.
