# create github pages

リポジトリ単位の github pagesの話になります。

---

リポジトリの Settingsタブ  
![image1](imgs/ghpages-1.gif)  

github pagesの設定をNoneから上二つのどちらかに変更する。作り立ての場合はdocsはディレクトリがまだないため選べないので後述。
![image2](imgs/ghpages-2.gif)

docsディレクトリを作ってpushすれば、前述のgithub pagesのdocsディレクトリを選べるようになる。
![image3](imgs/ghpages-3.gif)

---

markdownを使いたい場合、 index.mdを適当に作ってpushすれば変換されて表示される。  
レイアウトを変更したい場合は別途ヘルプ等参照(凝ったことしないなら`_layout`ディレクトリつくってそこにhtmlを放り込むぐらいで可能)。

---

できたページは https://`ユーザー名`.github.io/`リポジトリ名`/

[このマークダウンの結果](https://case-of-t.github.io/create-gh-pages/)
