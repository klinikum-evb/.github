# Klinikum EvB

### Packages aus der Organisation nutzen

Im Tab "Packages" werden einige NPM Packages zur Verfügung gestellt. Um diese zu nutzen muss npm zunächst beigebracht werden, dass diese in einer anderen registry liegen. Das kann mit dem folgenden Befehl passieren:

```
npm login --registry=https://npm.pkg.github.com --scope=@klinikum-evb
```