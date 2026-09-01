
# A Github Actions workflow to solve the repetitiveness of building Docker image and pushing it to production

## How to use
You need to setup GHCR first (search google im too lazy to explain it)

then you download the ci-cd.yml raw file

configure IMAGE_NAME

then you can do git tag (e.g. git tag v1.0.0) your latest commit and simply push your project with tag to Github (e.g. git push v1.0.0).
The workflow should be executing in github actions now
