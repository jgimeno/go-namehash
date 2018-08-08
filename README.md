# Golang ENS Namehash implementation.

## How to use

Is very easy to use, import the library and use it like:

Import the library with dep:

```dep ensure -add "github.com/jgimeno/go-namehash"```

And use it like:

```nameHash := kns.NameHash("foo.eth")```

And it returns a common.Hash.
