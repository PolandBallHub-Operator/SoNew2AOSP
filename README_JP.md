# sonew2aosp

Xperia 端末を AOSP (Android Open Source Project) 風の UI に変更するための .NET 8.x WinForms ツールです。

## 特徴
- **Root/BLU 不要**: ADB コマンドを利用するため、端末の改造は不要です。
- **多言語対応**: セットアップ時に英語、日本語、ドイツ語を選択可能です。
- **AOSP UI 化**: Launcher 3、設定画面、ロック画面を AOSP 風に変更できます。
- **BigClock (2行時計) 単体切り替え**: ロック画面の時計表示を AOSP スタイルに切り替えられます。
- **一括 AOSP モード**: ランチャークリア、AOSP設定・ランチャー解放、壁紙設定を一括で実行します。
- **オーバーレイマネージャー**: 端末内のオーバーレイを GUI で一括管理（有効/無効/アンインストール/再インストール）できます。

## スクリーンショット

### ロゴ
![sonew2aosp Logo](./sonew2aospApp/Resources/logo.png)

### AOSP化前のロック画面
<img src="./images/lockscreen_before.png" width="30%">

### AOSP化後のロック画面
![AOSP化後のロック画面](./images/lockscreen_after.png)

### AOSP化前の設定画面
![AOSP化前の設定画面](./images/settings_before.png)

### AOSP化後の設定画面
![AOSP化後の設定画面](./images/settings_after.png)

## 使用条件
- Windows OS
- .NET 8.x ランタイム
- ADB (Android Debug Bridge) が使用可能な環境
- Android 12 以上の Xperia 端末（推奨）

## 使い方
1. Xperia 端末で「USB デバッグ」を有効にし、PC と接続します。
2. 本ツールを起動します。
3. 言語を選択してセットアップを開始します。
4. 各ボタンをクリックして AOSP UI 化を適用します。
5. オーバーレイマネージャーで詳細なカスタマイズが可能です。
6. 一括 AOSP モードを実行する際は、ランチャーデータ消去の確認ダイアログが表示されます。

## 開発者向け
本プロジェクトは .NET 8.0 WinForms で作成されています。
ビルドするには以下のコマンドを実行してください：
```bash
dotnet build
```

## 注意事項
- キャリア版、グローバル版の両方に対応していますが、機種によっては一部の機能が動作しない場合があります。
- 本ツールの使用は自己責任で行ってください。
