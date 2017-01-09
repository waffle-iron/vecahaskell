# VECA in Haskell

This project is about learning Haskell while developing a DSL for the verification of component architectures (see [VECA](https://github.com/pascalpoizat/veca)).

The idea came while I was coding in Java algorithms that run beyond a DSL plugin written with XText/XTend. These algorithms, and the structures they operate on (mainly trees and transition systems) were written formally in a paper and it was time to implement them.

The Java generics or patterns I needed were quite painful (I may compare the code to transform the information in a tree one day, just for fun) and the typing was not as strong as I would have liked. Then I thought about trying Scala or Kotlin, that have stronger type systems and may operate with Java. But, in the end, why not writing code in a language that is closer to the formalizing in the papers?

## Haskell notes

These notes are prior to a (to appear someday) blog post on installing and running an Haskell development platform on a Mac.

### Libraries

- [Hackage central package archive](https://hackage.haskell.org)

### Building

- [Stack](https://haskellstack.org/)
- Cabal (used by Stack)

### Testing

- HUnit
- SmallCheck
- QuickCheck
- [Tasty](http://documentup.com/feuerbach/tasty)

### IDE

- [Haskell layer](https://github.com/syl20bnr/spacemacs/tree/master/layers/%2Blang/haskell) for [Spacemacs](http://spacemacs.org)

### TODO

- continuous integration (putting Travis CI in the picture)
- documentation generation

## Acknowledgements

### For help in installing / running Haskell:

This includes Haskell, Stack, and Spacemacs

[@BeRewt](https://twitter.com/BeRewt),
[@kaddourkardio](https://twitter.com/kaddourkardio), 
[@SergeStinckwich](https://twitter.com/SergeStinckwich),
[@spacemacs](https://twitter.com/spacemacs)

### For help with the Haskell language:

This includes code refactoring / enhancement

[@BeRewt](https://twitter.com/BeRewt)
