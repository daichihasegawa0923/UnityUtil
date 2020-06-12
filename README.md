# UnityUtil
Unityでよく使う処理をまとめたパッケージ集です

## パッケージの説明
### TestPlayerPrefsPackage
* 概要<br>
PlayerPrefsの値を自由に変更できます
PlayerPrefsの値を確認できます
* 使い方<br>
    1. TestPlayerPrefsSceneを開き、再生ボタンを押してゲームの実行をする
    2. PlayerPrefsの値を保存したい場合
        * 最上部のテキストボックスにPlayterPrefsのキー値を文字列で入力する<br>例：abc
        * 保存したい方を、右側のドロップダウンから選択する
        * 上から2番目のテキストボックスに保存したい値を入力する
        * SETボタンをクリックする→ログに値が保存された旨のメッセージが表示されたら成功
    3. PlayerPrefsの値を確認したい場合
        * 最下部のテキストボックスに、確認したいPlayerPrefsのキー値を入力する
        * GETボタンを入力する→ログに保存されている値が表示される

* 注意点
    * UIがうまく表示されない場合は、Scene上のTestPlayerPrefsManager内のUIを調整する
    * 実行結果がログに出力されるので、ログが確認できる状態で使用する

## ファイル構成

    UnityUtil
    ┣ bin・・・完成したPackageを保存
    ┗ src・・・Package編集用のUnityプロジェクトファイルを保存