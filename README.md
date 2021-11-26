# scoop-apps [![Build status](https://ci.appveyor.com/api/projects/status/a2rk8k3j8xm0neev/branch/main?svg=true)](https://ci.appveyor.com/project/JaimeZeng/scoop-apps/branch/main) [![Excavator](https://github.com/JaimeZeng/scoop-apps/actions/workflows/excavator.yml/badge.svg)](https://github.com/JaimeZeng/scoop-apps/actions/workflows/excavator.yml)

## Installation / 安装

```powershell
scoop bucket add sapps https://github.com/JaimeZeng/scoop-apps
scoop update
```

## Manifests / 应用

All manifests can be listed with:

```powershell
scoop install scoop-completion
scoop install scoop-search
scoop-search sapps/<app_name>
```

Install apps from this bucket with:

```powershell
scoop install sapps/<app_name>
```
