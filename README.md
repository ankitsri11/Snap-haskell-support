# Snap-haskell-support
Run Haskell helloworld code on Snap-CI

For example, I have created a smaple file "helloworld.hs" which has below code

> main = putStrLn "hello, world" 

Once you have Haskell code added, you can add the repo to Snap-CI and can follow below steps to install Haskell and run your helloworld file on Snap-CI:

> sudo yum install epel-release

> sudo yum install -y haskell-platform

> ghc --make helloworld

> ./helloworld
