## Elixir Introduction

* Use iex for intractive shell once Elixir is installed

### Variables
```elixir
var1 = 1
var2 = var1
var1 + var2
```

### functions - iex anonymous oneline
```elixir
fn_add = fn (arg1, arg2) -> arg1 + arg2 end
```

### functions - iex anonymous multiline
```elixir
fn_add = fn (arg1, arg2) ->
arg1 + arg2
end
```

### functions - iex anonymous using captrue operator
```elixir
fn_add = &(&1+&2)
```

### functions - iex call
```elixir
fn_add.(1, 4)
> 5
```

#### notes for this section
all above methods are to create anonymous functions in intractive shell
fn_add is not the function name but it just a variable that store the anonymous function
anonymous functions could be usefule while pass functions as arguments
