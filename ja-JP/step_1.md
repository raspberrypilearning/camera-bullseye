Python Picamera モジュールは現在、デフォルトの状態では最新バージョンの Raspberry Pi OS (**Bullseye** と呼ばれます) と互換性がありません。

Picamera モジュールを使用する場合には、カメラのレガシーサポートを有効にする必要があります。 <iframe width="560" height="315" src="https://www.youtube.com/embed/E7KPSc_Xr24" title="YouTube ビデオプレーヤー" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen mark="crwd-mark"></iframe>

ターミナルウィンドウを開き、次のコマンドを入力します:

```bash
sudo raspi-config
```

カーソルキーで `Interface Options` を選択し、 'Enter' キーを押します。

![interface options が選択された状態](images/interface-options.png)

'Legacy Camera Enable/disable legacy camera support' が選択されていることを確認し 'Enter' キーを押します。

![レガシーカメラが選択された状態](images/enable-legacy.png)

カーソルキーで `<Yes>` を選択し、 'Enter' キーを押します。

もう一度 'Enter' を押して確認します。

![レガシーカメラサポートについて表示する [OK] がハイライトされた画面](images/ok.png)

カーソルキーで `<Finish>` を選択します。

![[Finish] がハイライトされた状態](images/finish.png)

'Enter' を押して再起動します。

![再起動を選択](images/reboot.png)

