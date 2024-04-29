# 開発環境/マルチモデル構築環境のセットアップ

## 前提条件

- Java 17以上(17が一番推奨)のJDK、インストーラーに関しては[Adoptium](https://adoptium.net/releases.html)にアクセスするとダウンロード出来ます。
- 任意のJava IDE、例えば[Intellij IDEA](https://www.jetbrains.com/ja-jp/idea/download/?section=windows)(Community版推奨)、[Eclipse](https://www.eclipse.org/downloads/)など
- マイクラ用のモデリングソフトウェア、例えば[Blockbench](https://www.blockbench.net/downloads)や[Tabula](https://www.curseforge.com/minecraft/mc-mods/tabula-minecraft-modeler)(1.12.2版推奨)など

## 開発環境の構築

githubのアカウントがある場合、このプロジェクトを[テンプレートとして使用](https://github.com/new?template_name=LittleMaidModelProject-Template&template_owner=Yukkuritaku)することで開発環境を構築することができます。

アカウントが無い場合、このプロジェクトから`code`を押し、`Download ZIP`を押すとこのプロジェクトをzipファイルでダウンロードできます。

`build.gradle`ファイルをIDEにインポートすることで自動で環境が構築されます。

## マルチモデル作成環境の構築

まずはSugarCoffee氏のリトルメイドのプロジェクトファイルをダウンロードします。

使っているソフトウェアによって違うので、自分の環境のものをダウンロードしてください。

[利用条件のリンク](https://github.com/MMM666/littleMaidMob/blob/master/old/readme.txt)

[Tabulaプロジェクトファイル](https://www.dropbox.com/s/rxkmmrukrrpx42b/ModelLittleMaidBaseVer1.1.tbl?dl=0)

[Blockbenchプロジェクトファイル](https://www.dropbox.com/s/3rzp72bs0h87qqt/ModelLittleMaidBaseVer1.1.bbmodel?e=1&dl=0)

ダウンロードしたら、プロジェクトをモデリングソフトウェアで開いてください。

Blockbenchの場合、左上のFile→モデルを開くか`Ctrl+o`キーで開き、ModelLittleMaidBaseVer1.1.bbmodelを選択すると開けます。
開いたらFile->プロジェクトを開き、バージョンをForge 1.7-1.13にしてください。

Tabulaの場合、modを導入した後にマイクラを閉じ、modsフォルダの中にあるtabulaフォルダーにModelLittleMaidBaseVer1.1.tblを入れ、再びマイクラを起動することでモデリング出来るようになります。

---
ここまできたら開発環境の構築は完了です！　素敵なメイドさん作成ライフを！