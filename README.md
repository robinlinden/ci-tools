# Continuous integration tool repository

This repository contains tools for working with the TokTok Haskell repositories.
Its purpose is mainly to centralise the costly building of external tools like
`hlint` and `stylish-haskell`, which otherwise each CI build would have to do,
itself. We also store some smaller scripts here that support the CI builds, so
we can reduce duplication between the separate CI configurations.
