For relating elements.

## Install

```sh
julia
```

```julia
using Pkg: add

add(url="https://github.com/KwatME/Rela.jl")
```

## Use

See [examples](notebook/example.ipynb).

## Relationship

### Specific

" (comment)

{ (contain)

\> (become)

\+ (make)

\- (break)

/ (increase amount)

\ (decrease amount)

^ (increase function)

v (decrease function)

### Association

- Positive: {, >, +, /, ^,
- Negative: -, \\, v

### Infered

Folder { Folder/..., except Cell/, Function/, and Problem/.

Folder ^ Folder/Function/..., but a function.md can override this relationship.

Folder/Problem/... v Folder, but a problem.md can override this relationship.

## Design

Be real, specific, minimal, and modular.
