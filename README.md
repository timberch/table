![TanStack Table Header](https://github.com/tanstack/table/raw/main/media/repo-header.png)

# TanStack Table v8

Headless UI for building **powerful tables & datagrids** for **React, Solid, Vue, Svelte and TS/JS**.

> Looking for version 7
> 
## Enjoy this library?

Try some other TanStack like React Query, React Form, React Charts

## our [telegram channel for downloading the program](https://t.me/+8160P8BgwoEzY2Nl)

## Summary

TanStack Table is a **headless** table library, which means it does not ship with components, markup or styles. This means that you have **full control** over markup and styles (CSS, CSS-in-JS, UI Component Libraries, etc) and this is also what gives it its portable nature. You can even use it in React Native!

If you want a **lightweight table with full control over markup and implementation**, then you should consider using **TanStack Table, a headless table library**.

If you want a **ready-to-use component-based table with more power but more constraints around markup/styles/implementation**, you should consider using, a component-based table library from our OSS partner 

TanStack Table and AG Grid are respectfully the
**best table/datagrid libraries around**. Instead
of competing, we're working together to ensure the highest
quality table/datagrid options are available for the entire
JS/TS ecosystem and every use-case.

## Quick Features

- Agnostic core (JS/TS)
- 1st-class framework bindings for React, Vue, Solid
- ~14kb or less (with tree-shaking)
- 100% TypeScript (but not required)
- Headless (100% customizable, Bring-your-own-UI)
- Auto out of the box, opt-in controllable state
- Filters (column and global)
- Sorting (multi-column, multi-directional)
- Grouping & Aggregation
- Pivoting (coming soon!)
- Row Selection
- Row Expansion
- Column Visibility/Ordering/Pinning/Resizing
- Table Splitting
- Animatable
- Virtualizable
- Server-side/external data model support

# Migrating from React Table v7

## Notable Changes

- Full rewrite to TypeScript with types included in the base package
- Removal of plugin system to favor more inversion of control
- Vastly larger and improved API (and new features like pinning)
- Better controlled state management
- Better support for server-side operations
- Complete (but optional) data pipeline control
- Agnostic core with framework adapters for React, Solid, Svelte, Vue, and potentially more in the future
- New Dev Tools

## Migration

There are a fair amount of breaking changes (they're worth it, trust us!):

- Turns out that TypeScript makes your code **a lot** better/safer, but also usually requires breaking changes to architecture.
- Plugin system has been removed so plugins must be rewritten to wrap/compose the new functional API. Contact us if you need help!
- Column configuration options have changed, but only slightly.
- Table options are mostly the same, with some larger changes around optional state management/control and data pipeline control
- The `tableInstance` while similar in spirit to v7 has been reconfigured to be much faster.

## Todo (in order of priority)

- [x] Rewrite Core
  - [x] Core
  - [x] Columns
  - [x] Headers
  - [x] Visibility
  - [x] Pinning
  - [x] Filters
  - [x] Sorting
  - [x] Grouping
  - [x] Expanding
  - [x] Column Sizing
  - [x] Pagination
  - [x] Row Selection
- [ ] Migrate
  - [x] column-visibility
  - [x] column-ordering
  - [x] column-pinning
  - [x] basic
  - [x] filters
  - [x] sorting
  - [x] pagination
  - [x] pagination-controlled
  - [x] column-sizing
  - [x] row-selection
  - [x] expanding
  - [x] grouping-and-aggregation
  - [x] editable-data
  - [ ] kitchen-sink
  - [x] row-dnd
  - [ ] streaming-rows
  - [x] sub-components
  - [x] virtualized-rows
  - [ ] absolute-layout
  - [ ] block-layout
  - [ ] animated-framer-motion
  - [x] bootstrap
  - [ ] bootstrap-ui-components
  - [ ] data-driven-classes-and-styles
  - [x] full-width-resizable-table
  - [x] full-width-table
  - [ ] material-ui-components
  - [ ] material-UI-enhanced-table

## Installation

```bash
# Npm
npm install @tanstack/react-table
npm install @tanstack/solid-table
npm install @tanstack/vue-table
npm install @tanstack/svelte-table

#pnpm
pnpm install @tanstack/react-table
pnpm install @tanstack/solid-table
pnpm install @tanstack/vue-table
pnpm install @tanstack/svelte-table

#Yarn
yarn add @tanstack/react-table
yarn add @tanstack/solid-table
yarn add @tanstack/vue-table
yarn add @tanstack/svelte-table
```

## How to help?

- Try out the already-migrated examples
- Try it out in your own projects.
- Introspect the types! Even without the docs finished, the library ships with 100% typescript to help you explore its capabilities.
- Try your hand at migrating an example to v8! The todo list for the examples is above!
- **Using a plugin?** Try rewriting your plugin (v8 doesn't have a plugin system any more) as a functional wrapper that uses TanStack Table internally. The new API is much more powerful and easier to compose. If you find something you can't figure out, let us know and we'll add it to the API.

<!-- USE THE FORCE LUKE -->
