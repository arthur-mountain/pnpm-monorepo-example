# pnpm-monorepo-example

The monorepo example with pnpm

# Requirements

Create `pnpm-workspace.yaml` in foot

# Commands

##### Title: Add dependency in root workspace

- `pnpm add -W <package-name(s)>`
  - e.g. pnpm add -W lodash

##### Title: Add dependency in each workspace

- `cd <workspace-name> && pnpm add <package-name(s)>`
  - e.g. cd packages/project-a && pnpm add lodash
