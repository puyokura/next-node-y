# nodeTube

日本語の(node.jsで作られた)YouTubeビューワー

所詮Yukiのめちゃくちゃ改造版です。

動作が重い代わりに安定しています。

`/@keiji`というコマンドで掲示板へアクセスできるようになりました。

掲示板のID/PWは[こちら](https://forms.gle/pdjX5HhZNx2ZQqpU6)から作成できます。

入るためのパスワードは[passsend.jf6deu.net](https://passsend.jf6deu.net/)から入手できます。

使い方は[こちらのScratch](https://scratch.mit.edu/projects/1081970754)に詳しく載っています。

# デプロイ方法

いまのところrenderしか対応してないけど

[ここ](http://render.com/deploy?repo=https://github.com/JF6DEU/nodeTube/)からデプロイできるよ。(事前にrenderアカウント作成必須)

先生モードとしてバックグラウンド再生はできないよ。

タブ切り替えると一瞬で再生が止まるよ。(ホントは`setTimeout`をブラウザが止めてしまって...おっとこれ以上は言えないなぁ)

# 注意事項

定期的にインスタンスを再起動してね。(プロキシを読むため)

renderだとManual DeployからRestart serviceをクリックしたらできるよ。
