# labvm

[![Deploy to Azure](https://aka.ms/deploytoazurebutton)](https://portal.azure.com/#create/Microsoft.Template/uri/https%3A%2F%2Fgithub.com%2Fkikukawa9%2Flabvm%2Fblob%2Fmain%2Fazuredeploy.json)

# デフォルトブラウザの変更

```
setdefaultbrowser edge
```

# Azure CLI

```
az login
```
この場合上記で設定したデフォルトブラウザが使用される

# Azure PowerShell


```
Connect-AzAccount -DeviceCode
```

`-DeviceCode` がない場合 Sigin inのウィンドウが表示されるが、JavaScriptのエラーとなる。

