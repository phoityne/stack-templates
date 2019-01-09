# Stack Templates

Project Templates for Easy & Quick starting Haskell programming.


## Creating New Project

```
> stack new package-name github:phoityne/hs-project ^
  -p "module:Project.Top.Module" ^
  -p "module-path:Project/Top/Module" ^
  -p "paths-module:Paths_package_name"
>
> cd package-name
>
> stack test
 . . .
1 example, 0 failures
Completed 2 action(s).
>
```

## Template Parameters

|PARAM|REQUIRED|DESCRIPTION|EXAMPLE|
|:--|:--|:--|:--|
|module|yes|module name.| Phoityne.VSCode|
|module-path|yes|module folder hierarchy. |Phoityne/VSCode|
|paths-module|yes|Paths module name|Paths_phoityne_vscode|

## Libraries

|FUNCTIONALITY|LIBRARY|
|:--|:--|
|Command line argument|[cmdargs](http://hackage.haskell.org/package/cmdargs)|
|config file|[yaml](http://hackage.haskell.org/package/yaml)|
|Logging|[hslogger](http://hackage.haskell.org/package/hslogger)|
|Template Engine|[stache](http://hackage.haskell.org/package/stache)|
|Test Framework|[hspec](http://hackage.haskell.org/package/hspec)|
|Data access|[lens](http://hackage.haskell.org/package/lens)|
|App Context|ExceptT, StateT|

