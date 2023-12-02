# A `monorepo` template

This is a bare monorepo with workspaces template. Use it with `bun` and `rust` projects.

## How-to

Push the `Use this template` button in upper right corner to create a new repository. 

After cloning the repo locally, you can add or initialize new packages in the respective folders like so:

```shell
cd ./apps && bun create vite web
```

The `packages/` folder intended for the code shared between and/or used in your repo's `apps/` folder.

After creating the workspaces, install all the dependencies from the root folder of your repo like so:

```shell
bun install
```

Ravers gonna rave!
🤡