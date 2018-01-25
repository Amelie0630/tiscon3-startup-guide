# IntelliJのインストール(Mac)

## 前提条件

* [Terminalを起動](tipsForMac.md#terminalの起動方法)して `java -version` とコマンドを入力した時、結果が返ってきますか？
* [Terminalを起動](tipsForMac.md#terminalの起動方法)して `mvn --version` とコマンドを入力した時、結果が返ってきますか？

## インストール

1. https://www.jetbrains.com/idea/#chooseYourEdition のDOWNLOADボタンから、**Community** のバージョンを選んでダウンロードしてください。
1. ダウンロードできたインストーラーを起動して、表示される手順に従ってインストールを進めてください。よくわからない項目はそのままYESを選択してください。


## プラグインの設定

1. もし起動していなかったら `Finder` > `アプリケーション` からIntelliJを起動し、`Configure` > `Plugins` を選択します。<br>
![プラグイン設定1](../image/intellij_top_settings.png)

1. `Browse repositories...` ボタンを押下します。<br>
![プラグイン設定2](../image/intellij_setting_plugins.png)

1. 検索バーに `Lombok` と入力し、Lombok Pluginを選択します。
右側に表示されるInstallボタンを押下してください。<br>
![プラグイン設定3](../image/intellij_setting_install_lombok-plugin.png)
