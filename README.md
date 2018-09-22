# scoop-bucket　@ eamat

## マニフェストの作成方針
設定ファイル類はできるだけ`persist`に収める
AppDataにデータが散らばらないよう、Portable仕様での起動が可能なものはそれを利用する。

## 自分用メモ

jsonファイルのアップデートには `checkver`スクリプトを使用する

```powershell
ps> .\bin\checkver.ps1 <appname> -f
```

または

```powershell
ps> .\bin\checkver.ps1 <appname> -u
```

まとめて

```powershell
ps> .\bin\checkver.ps1 * -u
```

-f と -u のコマンドの違いはいまいちよく分からない

### 参考

[scoop bucket を作成する](https://blog.haniyama.com/2018/03/12/scoop-bucket/)

[App Manifests・lukesampson /スクープWiki](https://github.com/lukesampson/scoop/wiki/App-Manifests)

