How to update this repo:

```
git clone git@github.com:alphasheets-development/cabal-db.git
cd cabal-db
nix-shell -p haskellPackages.cabal-install
HOME=$(pwd) cabal update
git commit -a -m "Update cabal DB"
git push
```
