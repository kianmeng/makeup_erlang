# MakeupErlang

[![Build Status](https://github.com/elixir-makeup/makeup_erlang/workflows/CI/badge.svg)](https://github.com/elixir-makeup/makeup_erlang/actions)

A [Makeup](https://github.com/elixir-makeup/makeup/) lexer for the `Erlang` language.

## Installation

Add `makeup_erlang` to your list of dependencies in `mix.exs`:

```elixir
def deps do
  [
    {:makeup_erlang, "~> 1.0"}
  ]
end
```

The lexer will automatically register itself with `Makeup` for the languages `erlang` and `erl`
as well as the extensions `.erl`, `.hrl` and `.escript`.
