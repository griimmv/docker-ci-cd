# a ci-cd workflow for bun projects to be uploaded to docker via Github Container Registery

git clone this project first before building your project

then you need to setup GHCR (search google im too lazy to explain it)

now you build your project

then you can do git tag (e.g. git tag v1.0.0) your latest commit and simply push your project with tag to Github (e.g. git push v1.0.0)
the workflow should be done on github action
