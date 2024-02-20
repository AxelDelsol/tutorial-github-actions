Sample project to learn Github Actions

The goal of this project is to learn Github Actions. The project is considered successful once the following CI specifications are met.
In order to simulate a real project, echo statements will be used.

| Name | Description | Event | Conditions (if any) |
| ---- | ----------- | ----- | ------------------- |
| Lint | Execute a linter to check the code conventions | On push | Branches starting with "wip" are ignored |
| Test | Run project tests | On push | Branches starting with "wip" are ignored |
| Release | Build and push a docker image or publish a library on a private registry | On push | Only on tags (which should be printed) |
