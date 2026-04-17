# @jai/jai-design-system

Angular component library for the JAI design system.

## Build

```sh
pnpm nx build jai-components
```

Build output:

`dist/libs/jai-design-system-components`

## Publish to npm

1. Login once:

```sh
npm login
```

2. Build the package:

```sh
pnpm nx build jai-components
```

3. Publish:

```sh
npm publish dist/libs/jai-design-system-components --access public
```

## Use in another app

```sh
npm install @jai/jai-design-system
```
