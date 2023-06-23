# rancher-desktop

Rancher Desktopのセットアップ中に起きたことをメモする

## トラブルシューティング

`docker login`に失敗したときに以下の結果が返ってきたら`docker-credential-helper`をインストールする。

```
Error saving credentials: error storing credentials - err: docker-credential-osxkeychain resolves to executable in current directory (./docker-credential-osxkeychain), out: ``
```

```sh
brew install docker-credential-helper
```
