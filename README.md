# Chamber-Subtree-Module


## Add this repo as a module

### Add using SSH
```
git subtree add --prefix chamber git@github.com:yogeshpaliyal/Chamber-Subtree-Module.git master --squash
```

### Add using HTTPS
```
git subtree add --prefix chamber https://github.com/yogeshpaliyal/Chamber-Subtree-Module.git master --squash
```

## Add module in `settings.gradle`
```
include ':chamber'
```

## implement module in `build.gradle` (app level)
```
implementation project(":chamber")
```
