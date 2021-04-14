For building .md network.

## Install

```sh
julia
```

```julia
using Pkg: add

add(url="https://github.com/KwatME/MDNetwork.jl")
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

Folder { Folder/..., except \_f/ and \_p/.

Folder ^ Folder/Function/..., but a \_f.md can override this relationship.

Folder/\_p/... v Folder, but a \_p.md can override this relationship.
