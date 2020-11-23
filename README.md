# fp-ts-snippets README

A set of snippets to help with writing fp-ts code.

![Preview](images/preview.gif)

## Features

| snippet | expanded |
|--|--|
| `ta`    | `import * as T from "fp-ts/Task";`            |
|`te`     | `import * as TE from "fp-ts/TaskEither";`     |
|`op`     | `import * as O from "fp-ts/Option";`          |
|`ar`     | `import * as A from "fp-ts/Array";`           |
|`fpfn`   | `import { _ } from "fp-ts/function";`         |
|`fpp`    | `import { pipe } from "fp-ts/function";`      |
|`fpf`    | `import { flow } from "fp-ts/function";`      |
|`io`     | `import * as IO from "fp-ts/IO"`              |
|`ioe`    | `import * as IOE from "fp-ts/IOEither"`       |
|`fold`   | `{E, TE, O, IOE}.fold(leftSideFn, rightSideFn)`  |
|`tryc`   | `{E, TE, O, IOE}.tryCatch(tryFn, onError)`       |
|`reduce` | `{E, TE, O, IOE}.reduce(initialValue, reducer)`  |

## Requirements

- These snippets will only work in a typescript file.

## Extension Settings

N/A

## Known Issues

Very much a first draft of useful snippets. More will come with more usage of fp-ts.

## Release Notes

### 1.1.13

Simplify release notes
