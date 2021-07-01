# Typescript Debug Repro

To Setup:

- `npm i`
- `npm run build`
- In VS Code run the `Launch Program` task

Set the following breakpoints:

- `./packages/lib1/index.ts:2`
- `./packages/lib2/index.ts:4`

Notice that the breakpoint on `./packages/lib2/index.ts:4` will be hit, but the breakpoint on `./packages/lib1/index.ts:2` is skipped.

Video Recording: https://www.youtube.com/watch?v=Bln3lQE36Fw
