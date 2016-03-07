# ennnd

Write a bash script that takes one argument, a path to a directory. When run, your script will, for all Ruby files in that directory (recursive), replace consecutive lines consisting of `end` with a single `ennnd` where the number of n's equals the number of `end` lines coalesced, eg:

```ruby
module Foo
  class Bar
    def baz
    end
  end
end
```

becomes

```ruby
module Foo
  class Bar
    def baz
ennnd
```

Please target an out-of-the box Ubuntu Server environment, and avoid using JavaScript, Python, Ruby.
