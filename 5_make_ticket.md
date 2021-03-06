# チケットの発行
## チケット駆動開発とは
チケット駆動開発とは，新しい機能の追加やバグを修正するとき，その内容や目的をチケットに書くことで開発していく手法です。開発者はこのチケットに書かれた内容に沿ってコードを修正し，コミットします。逆に言えば，開発者はチケットに書かれていないコミットは禁止です。今回は，Githubのissueの機能をチケットと見立てて開発していきます。

## issueの発行
ここからはBさんの作業です。まずissueでチケットを発行してください。issueタブでNew issueを選択します  

![](スクリーンショット 2016-03-12 03.28.58.png)
次にissueに追加することを書きます。書き終わったらsubmit new issueでissueを発行します。  

![](スクリーンショット 2016-03-12 03.33.20.png)
書き終わったら，右にあるlabelsでenhancement(拡張)を選択し，誰が拡張するのか(自分)を選択してください

![](スクリーンショット 2016-03-12 03.34.12.png)
## ブランチの作成とソフトウェアの拡張
ブランチを作成して，そのブランチ内で機能を追加しましょう。以下のコマンドを入力してください  
~~~
git branch 1
git checkout 1
~~~
今回ブランチ名は，issueの番号と関連つけるため番号にします。作成したブランチで，2,3,5の倍数でGithubを表示する拡張を行ってください。完了したら以下のコマンドを入力してください
~~~
git add FizzBuzz.java
git commit -m "refs #1 2,3,5,の倍数でGithubを表示"
~~~
コミットメッセージに「refs #"issue番号"」とすることでissueの内容と関連つけることができます。


