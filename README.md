# WORKSPACE TEMPLATE

## Start web project

```sh
# create a workspace directory
npx generate-github-directory https://github.com/rocket-hangar/workspace-template my-project
cd my-project

# create an app
npx generate-github-directory https://github.com/rocket-hangar/rocket-scripts-templates/tree/master/templates/web my-app

# add "my-app" to workspaces of package.json

# install
yarn

# start
cd my-app
direnv allow .

# start
yarn run start
```

## Start electron project

```sh
# create a workspace directory
npx generate-github-directory https://github.com/rocket-hangar/workspace-template my-project
cd my-project

# create an app
npx generate-github-directory https://github.com/rocket-hangar/rocket-scripts-templates/tree/master/templates/electron my-app

# add "my-app" to workspaces of package.json

# install
yarn

# directory
cd my-app
direnv allow .

# start
yarn run start
```