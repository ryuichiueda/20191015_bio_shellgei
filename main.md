# 解析が捗るコマンド入門

千葉工業大学 上田 隆一

<p style="font-size:50%">
This work is licensed under a <a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">Creative Commons Attribution-ShareAlike 4.0 International License</a>.
<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/">
<img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
</p>

---

## 質問1

* データ処理や解析にはどんなソフトウェアを使ってますか？

---

## 質問2

* では、データがどんなふうにコンピュータに保存されているか把握していますか？

---

## あるデータはあるソフトでしか利用できない？

* 例
    * .docxファイルは、あのソフトでしか開けない
    * .aiファイルは、あのソフトでしか開けない
    * .exeファイルは、あのOSでしか実行できない<br />$ $
* これはなぜなのか？
    * 競合他社のソフトを使われたくない

---

## 時代の変化

* 複雑な形式のデータから扱いやすいデータへ
    * オープンソースの台頭
        * 誰でも理解しやすい合理的なデータ形式に
        * 企業がデータフォーマットを独占できない状況に

---

## 「誰でも理解しやすい」

* 一番の条件は「テキストデータ」であること
    * メモ帳で開いて字で読める
    * 例: yaml, json, csv, tsv, html, markdown<br />$ $
* テキストデータの処理
    * 昔は重要だった
    * 今また重要に

---

## テキスト処理の道具

* 専用のソフト
    * 一般によく行われる処理を行うときに便利<br />$ $
* 汎用ソフト
    * エディタ: テキストを編集
    * コマンド: テキストを検索・変換・集計<br />$ $
    * いつもやらないことをやるときに便利
    * <span style="color:red">「いつもやらないこと」はいつもやる</span>

---

## コマンドに親しむ

* 今のところ環境はLinuxがよい
    * 使用者が多くネット上に情報がたくさん

---

## 今回やること

* バイオインフォマティクスの問題集があるので素直に使わせてもらいましょう

<iframe src="//www.slideshare.net/slideshow/embed_code/key/yhup0TPQPN95jI" width="595" height="485" frameborder="0" marginwidth="0" marginheight="0" scrolling="no" style="border:1px solid #CCC; border-width:1px; margin-bottom:5px; max-width: 100%;" allowfullscreen> </iframe> <div style="margin-bottom:5px"> <strong> <a href="//www.slideshare.net/EmiHattori1/ss-80854726" title="バイオシェル芸 問題のみ" target="_blank">バイオシェル芸 問題のみ</a> </strong> from <strong><a href="https://www.slideshare.net/EmiHattori1" target="_blank">Emi Hattori</a></strong> </div>



---

## 環境

* Linux環境（ネイティブ環境，WSL，仮想環境）を準備できた人はそれを使用
* 準備できなかった人は講師のサーバを使います


