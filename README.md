# git-flow

##The overall flow of Gitflow is:


- A `develop` branch is created from `main`
- A `release` branch is created from `develop`
- `Feature` branches are created from `develop`
- When a `feature` is complete it is merged into the `develop` branch
- When the `release` branch is done it is merged into `develop` and `main`
- If an issue in `main` is detected a `hotfix` branch is created from `main`
- Once the `hotfix` is complete it is merged to both `develop` and `main`
