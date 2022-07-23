# **LF trimmer**
**英文整形・翻訳アプリ**

テキストボックスに入力した英文から
改行文字(LF)やハイフネーションを自動的に削除した後、
文章をAPI経由で
- Google翻訳
- DeelpL翻訳<br>

のいずれかの翻訳サービスに掛け、結果を出力させる。

# 手順

1. 左側のテキストボックスに翻訳したい文章を入力.

2. 入力した文章からLFやハイフネーションを取り除き、`Google`でGoogle翻訳、
   `DeepL`でDeepL翻訳に掛ける。なお、DeepL翻訳を用いる場合、予めDeepL API用のアカウントを
   作り、`./module/config.ini`の`API_key`の項に専用のAPIキーを、`free_or_pro`にアカウント種別を入力しておく。

3. 結果を出力。

# その他
- ./module/figureの各種画像は同名のファイルで差し替え可能.

# Author
* Yuki Ishii
* Keio University
* rinkobu@keio.jp

# License
This application is under [MIT license](https://opensource.org/licenses/mit-license.php)
