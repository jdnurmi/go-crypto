*** DO NOT USE THIS UNLESS YOU KNOW WHY IT EXISTS ***

This fork modifies some of the key selection heuristics to
handle very old PGP keys that don't have proper flags set.

You almost certainly do not want this - use the originals below:

```
go get github.com/ProtonMail/go-crypto
```

This module is backwards compatible with x/crypto/openpgp,
so you can simply replace all imports of `golang.org/x/crypto/openpgp` with
`github.com/ProtonMail/go-crypto/openpgp`.

A partial list of changes is here: https://github.com/ProtonMail/go-crypto/issues/21#issuecomment-492792917.
