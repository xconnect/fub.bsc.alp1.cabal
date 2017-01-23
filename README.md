HowToCabal
==========

How to use cabal (haskell build program)

* sudo apt-get install cabal-install
* cabal update
* create a folder for your haskell project
* copy the haskell files from this repo into your haskell project folder
* change to your haskell project folder
* cabal init
* follow the initialization steps
* edit the <your project>.cabal file
   * "main-is:" comment in and add the haskell file name with the main function
   * cabal-version >= 1.10
   * Executable -> default-language: Haskell 2010
   *touch LICENSE in your project folder
* cabal install "your-haskell-project-file-to-build"
