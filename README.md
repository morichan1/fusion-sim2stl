# fusion-sim2stl
Fusion360のシミュレーション結果をstlに変換するためのノートブックです


# 使い方
Fusion360の静的応力解析の変位の可視化を行います。

こちらの記事を参考に、シミュレーションの閲覧方を戻してください。
https://qiita.com/tomohiron907/items/bc288df4798c709c48bd#:~:text=%E6%9C%80%E6%96%B0%E3%81%AEFusion,%E8%A7%A3%E9%99%A4%E3%81%99%E3%82%8B%20%3E%20%E9%81%A9%E7%94%A8


変位をX,Y,Zに設定して、それぞれのパターンで下のコマンドテキストからvtuを取得してください。
https://www.autodesk.com/jp/support/technical/article/caas/sfdcarticles/sfdcarticles/JPN/How-to-export-Fusion-360-simulation-results.html
Win or Macでコマンド違います。
hoge_x.vtuとしておくとわかりやすいかも


そしてノートブックを再生して同時に3つのファイルをアップロードしてください。
