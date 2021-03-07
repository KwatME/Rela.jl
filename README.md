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

### Infered

Folder { (Folder/* - (Cell/, Function/, Problem/))

Folder ^ Folder/Function/*

Folder/Problem/* v Folder

### Association

- Positive: {, >, +, /, ^,
- Negative: -, \\, v

## Design

Be real, specific, minimal, and modular.
