# Maintainer Tips

This document aims to lay out some guidelines for the maintainers of elm-community. 

## Maintaining *-extra packages

1) Make sure that new functions have a purpose. If someone wants to make `takeTwo`, then make sure there’s a reason why they can’t just use `take 2` instead.
2) Group breaking changes as much as possible
3) Ensure that docs for all new functions have _examples_ of usage and output. For bonus points, make them doc-tests
4) Naming is a big part of making *-extra good. If someone wants to make a new function, check other languages to see what they call that function. For example, `groupWhile` means something different to Haskell devs as it does for JS devs
5) There is never any rush to merge any PRs in a *-extra package. Take your time, and ask for feedback from other users on how useful they might think a function is
6) Avoid adding new types. There might be a justification for adding a new type, but it would have to be a really really good one. If a function doesn’t work with the data type in the name, then it doesn’t belong in that package
7) Try to keep as much in the same module. People will expect all the list-extra functions to be in `List.Extra`, not `List.Extra.Banana`
